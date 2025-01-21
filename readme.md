# The `.well-known` service integration repository…

This repository aims to teach the beholder who has access to one of the following accounts the ability to verify their account with their [GitHub Pages](https://pages.github.com/) hostname.

* [GitHub](#github)…
* [Discord](#discord)…
* [BlueSky](#bluesky)…
* [Privacy](#privacy)…
* [Disclaimer](#disclaimer)…

## GitHub…

One obviously needs their own `GitHub` account to take advantage of this feature. You can freely [register](https://github.com/signup) an account if you do not have one.

1. Switch to the [GitHub Desktop](https://desktop.github.com/download/) client and create a new repository on your account called `.well-known`. The case is sensetive and you must type it exactly as shown. You do not need to add any `readme`, `licence` or `.git*` files if you do not want to. Make sure the privacy of the repository is set to `public` too as you cannot use the `Pages` feature when your repository is set to `Private`.
2. Add the required text file to the root directory of the repository on your computer.
3. Push the repository to `GitHub` creating it and also uploading the file you added.
4. Goto your repository page on `GitHub` and click the cog `Settings` at the top middle.
5. Choose `Pages` on the left sidebar.
6. Under `Branch` set the branch to the branch created by the `GitHub Desktop` client which is normally `main` or `master`.
7. Set the folder next to the `Branch` button to `/ (root)` then click the `Save` button.
8. Make another commit to your repository to upload the required file to the webiste.
9. Wait a minute or two for the page at `https://<yourgithubusername>.github.io/.well-known/<filename>` to appear.

### Things to note…

It is probably not a good idea to delete the repository as the services you connect may need to re-read the file you uploaded regularly. Also, do not set the repository to `private` as that would disable the `Pages` feature and you will have to manually re-enable it again.

## Discord…

[Discord](https://discord.com) allows you to add your GitHub website link to your Discord profile links page.

1. On `Discord`, click the `settings cog` at the bottom-left.
2. Click or tap on `Connections`.
3. Where it says `Add accounts to your profile` click on the `>` button and select `Domain`.
4. Type your website name — i.e. `https://<yourgithubusername>.github.io`, where `<yourgithubusername>` is replaced with your actual `GitHub` username.
5. Click or tap on `Verify using HTTPS`.
6. Add the text file named `discord` with the specified content from the `Content` edit box at the root directory of the repository on your computer.
7. Click `Verify` and if you did everything right your new hostname should be verified.

## BlueSky…

[BlueSky](https://bsky.app) allows you to set your username to your GitHub web page.

1. On `BlueSky`, choose the `Settings` cog in the bottom-left.
2. Choose `Account` then `Handle`.
3. Choose `I have my own domain →`.
4. Choose `No DNS Panel`.
5. In the `Enter the domain you want to use` edit box type `<yourgithubusername>.github.io` where `<yourgithubusername>` is replaced with your actual `GitHub` username.
6. Add the text file named `atproto-did` with the specified content which is specified in the `Upload a text file to:` edit box at the root directory of the repository on your computer.
7. Click `Verify Text File` and if you did everything right your new hostname should be verified.

### Things to note…

The old `BlueSky` username is preserved so nobody else can take it but will not forward to the new username so you have to update all your links pointing to the old username.

If you delete your `BlueSky` account then you will not be able to recreate your account using your old username or your webpages name so instead, use a random username first then you can change your username back to your webpages name after verifying it once again.

## Privacy…
This website contains absolutely zero first-party tracking but be advised that the third-party services mentioned mentioned obviously do, thus their privacy policies do apply when using their services.

## Disclaimer…

This information is provided to the public *AS IS* with *NO* warranty given of any kind. By using this knowledge you disclaim the author all liability in the event that the reader mistakes or misuses any part of it for any reason that might result in any sort of negative consequence. The services mentioned may pull or change these features at any time without notice. Mentions of trademarks are properties of their respective owners.

## That's all folks!
