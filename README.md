# CECS 478 Lab: PGP Encryption

## Assignment Description
This assignment is designed to demonstrate how PGP encryption works by using open-source and *auditable* tools to encrypt email messages. It will work equally well on just about any plain-text message.

**NOTE!** Before you send me *anything*, review the item below labeled [One Really Important Item!](#One-Really-Important-Item)

You will be emailing me a message using PGP encryption. All steps *must be done in your virtual machine*, with the exception of copying/pasting the encrypted message, signature, and public key from your virtual machine to your email client on your main computer. All other files (such as the private key) must remain on your virtual machine at all times.

Since our email system likes to filter out non-\*.edu addresses, you will need to use your student email for this assignment. Any other email addresses used for this assignment will be *discarded*, so ensure you are using the correct address.

Download [GnuPG](https://gnupg.org/) in your virtual machine image (use apt--your package manager on Ubuntu Linux, not the website download) and create a public/private key pair. Github has some [good documentation on how to do this here](https://docs.github.com/en/authentication/managing-commit-signature-verification/generating-a-new-gpg-key).

First, your public key must be uploaded to the [keyserver at openpgp.org](https://keys.openpgp.org) for this to work. You may copy that from your virtual machine to your main computer or you may upload it directly.

Next, I want you to find your favorite short-story, long form poem, comic (words only, sadly), or similar form of literature (something longer than a few paragraphs). You may copy/paste this from another source. It must be long enough for me to pick a random phrase out from it and email it back to you. 

PGP encrypt the *entire literature item* (this must be done with plain-text, else it will not work), create a  digital signature to include along with the message to verify that it really came from you, and email both items to me.

I will verify your message by responding with a pgp encrypted phrase, which will be a passage from your literature item. You must decrypt this message. There will be one additional simple instruction in my reply back to you, which you must do.

If you get anything else from me other than a *PGP encrypted message*, you are **not done**. Likely, you have an error somewhere in the process which must be corrected.

Once you have completed my final instruction inside of that PGP encrypted message, you are done with the assignment.

## [One Really Important Item!](#One-Really-Important-Item)
I get a *metric ton* of email every day, and I don't want to miss your email message. In order to ensure that I don't, I will need you to use the following email subject line for all email messages regarding this assignment:

`cecs 478 pgp encryption - [your name]`

If the header is not there, my filter will not catch it and you will probably lose points.

### Two Common Issues From Past Assignments
* Not including your PGP signature in the message (not the public key, the *signature*)
* Not properly uploading your public key to the keyserver

I will simply respond with "sig" or "pubkey" if one of these two items have not been completed.

## Deliverables

Your (correct) response to my email reply message will be counted as your final submission. No other submissions are necessary for full credit on this assignment.
