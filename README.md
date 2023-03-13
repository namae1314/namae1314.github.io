# Liquityapp.com Frontend

www.liquityapp.com

### Build dev-frontend for production
In a freshly cloned & installed monorepo, or if you have only modified code inside the dev-frontend package:
```yarn build```
If you have changed something in one or more packages apart from dev-frontend, it's best to use:

```yarn rebuild```
This combines the top-level prepare and build scripts.

You'll find the output in packages/dev-frontend/build.
