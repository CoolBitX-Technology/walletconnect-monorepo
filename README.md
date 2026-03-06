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
4. **Publish the package**
   - `npm publish --access public`
5. **Create a pull request and tag the release**
   - Open a pull request on GitHub and add a release tag.
