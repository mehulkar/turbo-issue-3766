Ignoring workspaces

1. Verify that yarn excludes the workspace:

   ```bash
   yarn workspaces list
   ```

1. Verify that turbo does _not_ exclude the workspace

```bash
yarn add -G turbo # or howevever you want to install globally
turbo run build
```

This is a repo for https://github.com/vercel/turbo/issues/3766
