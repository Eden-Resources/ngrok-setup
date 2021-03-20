# Starting up ngrok
1. Go [here](https://ngrok.com/download) to download ngrok
2. Unzip the zip file that you just downloaded
3. Get your authentication token [here](https://dashboard.ngrok.com/get-started/your-authtoken)
4. Run `./ngrok authtoken [TOKEN]` at the location that you unqipped the file to. Replace `[TOKEN]` with your authentication token
5. Run `./ngrok http [PORT]`. Replace `[PORT]` with the port that you want to use (if you don't know which port to use, use 3000)

# Configuring the bot with ngrok
1. Now that you have ran ngrok, copy the link that is displaying in the window. It should look something like `http://3af3b4364d80.ngrok.io` (not the https one)
2. Paste it into the config.json, after the `"REDIRECT"` attribute
3. Also enter the port you used after the `"PORT"` attribute
