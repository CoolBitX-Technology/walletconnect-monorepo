#### WalletConnect's main branch: v2.0

#### CoolBitX-Technology's main branch: cbx

## Deploy Flow

Follow the steps below when preparing and publishing a fix:

1. **Switch to the release branch**
   - `git checkout cbx`
2. **Apply your code changes**
   - Update the code for the fix you want to release.
3. **Bump the package version**
   - Update the package version according to your release policy.
4. **Create a pull request for review**
   - Open a pull request on GitHub to merge your changes into the `cbx` branch.
5. **Publish the package after merge**
   - Once the PR is approved and merged, publish the package from the up-to-date `cbx` branch by running:
   - `npm publish --access public`
6. **Tag the release**
   - After publishing, create a release tag on GitHub for the new version.
