## Publish package to NPM repo
1. increment the package version number according to `semver` rules
2. `npm login` - using your npm credentials
3. `npm publish --dry-run` - to check that relevant files are uploaded
4. `npm publish` - uploads package to repository
