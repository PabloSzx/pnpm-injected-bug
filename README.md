# pnpm injected bug

```sh
cd packages/foo && pnpm i
```

```
pnpm i
Scope: all 3 workspace projects
../..                                    |   +1 +
 ENOENT  ENOENT: no such file or directory, scandir '...\packages\bar'



../..                                    | Progress: resolved 1, reused 0, downloaded 0, added 0
```
