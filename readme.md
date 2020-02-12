# boilerplate workspace for a typescript-based npm package

Some details here are specifc to the @musicenviro scope

## what this is trying to set up for you in advance:

-   Typescript
-   ESLint
-   Prettier
-   type definitions for node

## how to use this boilerplate

1. copy the folder and rename it.

2. `rm -rf .git` to remove existing commits, then `git init`

3. edit package.json to update package name (scoped?), version, and description

4. `rm package-lock.json && rm -rf node_modules && npm i`

5. create first commit and push:
    ```
    git add .
    git commit -m "first commit (copied from @musicenviro/boilerplate)"
    git remote add origin https://github.com/geofholbrook/<projectname>.git
    git push -u origin master
    ```
