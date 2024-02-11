# CustomStreamlabsAlertWebsite
A local website that allows you to input an image/gif, a sound effect, text, and play an alert. Currently configured to trigger upon receiving a mail from gmail, but can be adjusted to be triggered by polling any API

See https://developers.google.com/gmail/api/quickstart/js to set this up with your own ClientID's and API Keys. You won't need to be approved by google or anything, and its free to set
up and use (no credit card number required).

Due to limitations with how OBS allows you to use sources, Browser source doesn't allow you to authenticate in a new window. Unless you can figure out a way around that, this
project requires you to use a window capture, and keep the window up.

After you create your API key and Client ID, all you need to do to run is:
1) install the 'http-server' node package (npm install http-server)
2) run the server on the computer you'll be streaming on, in the folder these project files are in. It will automatically know to run index.html as the main file (npx http-server -p 8000)

Both the above steps are also detailed in the developers.google quickstart link above

I plan on revisiting this project and developing it as a desktop app, which should address some of the limitations of this version


-Scott, 2024
