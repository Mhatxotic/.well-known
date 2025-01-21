# BlueSky integration repository…

This repository allows the beholder who has access to both a `BlueSky` and `GitHub` account to use a different username based on their `GitHub` username on `BlueSky`.

## Using your own GitHub hostname as your BlueSky handle…

1. On `BlueSky`, choose the `Settings` cog in the bottom-left.
2. Choose `Account` then `Handle`.
3. Choose `I have my own domain →`.
4. Choose `No DNS Panel`.
5. In the `Enter the domain you want to use` edit box type `<yourgithubusername>.github.io` where `<yourgithubusername>` is replaced with your actual `GitHub` username.
6. Switch to the `GitHub Desktop` client and create a new repository on your GitHub called `.well-known`. You do not need to add any `readme`, `licence` or `.git*` files if you do not want to. Make sure the privacy is set to `public` too as you cannot use the `Pages` feature when your repository is set to `Private`.
7. Add the text file specified in the `Upload a text file to:` edit box (at the time of writing, called `atproto-did`) at the root directory of the repository on your computer.
8. Push the repository to `GitHub` creating it and also uploading the file you added.
9. Goto your repository page on `GitHub` and click the cog `Settings` at the top middle.
10. Choose `Pages` on the left sidebar.
11. Under `Branch` set the branch to the branch created by the `GitHub Desktop` client which is normally `main` or `master`.
12. Set the folder next to the `Branch` button to `/ (root)` then click the `Save` button.
13. Wait a minute or two for the page at `https://<yourgithubusername>.github.io/.well-known/atproto-did` to appear.
14. Go back to the `BlueSky` page and click `Verify Text File` and if you did everything right your new hostname should be verified.

## Things to note…

It is probably not a good idea to delete the repository as connecting other services to your `BlueSky` account may need to read the file you uploaded. Also, do not set the repository to `private` as that would disable the `Pages` feature and you will have to manually re-enable it again.

The old `BlueSky` username is preserved so nobody else can take it but will not forward to the new username so you have to update all your links pointing to the old username.

## That's all folks…

**Information correct as of _<ins>21st of January 2025</ins>_**.
