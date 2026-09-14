# Kinect business-card QR redirect

The permanent public link is https://atdanielprice.github.io/kinect-qr/.
Both card directions encode that URL. The initial destination is https://trykinect.ai/contact.

[View or download the QR code](https://atdanielprice.github.io/kinect-qr/code/).

## Change the destination without reprinting the cards

1. Open [destination.json](https://github.com/atdanielprice/kinect-qr/edit/main/destination.json).
2. Replace only the HTTPS URL in the `destination` field.
3. Commit the change to `main`.
4. Wait for the GitHub Pages deployment to finish, then scan the existing QR again.

Do not rename the repository, the owner account, or the public URL after engraving.
The public site contains only the redirect page and destination. It collects no application analytics.
GitHub Pages serves the site; the page fetches the current destination and performs a browser redirect.
If the configuration cannot be loaded, the page offers a manual link to the original Kinect demo page.
Pages publishes from the root of the main branch. Destination updates may take several minutes to deploy.
