# README

This is the API server for generating stickers for the Kidechism app

## Deployment

This app usees a private `.env` file with the API keys for HuggingFace and RemoveBG APIs, so it will build, but it won't work without the keys, let me know if you need them.

But you can try out the API builds on the server live here:
* Home: https://kidechism-api2.onrender.com/ 
* Generate any animal (change 'bird') sticker: https://kidechism-api2.onrender.com/stickerImage/bird
* Generate the same sticker, but return it in base64 https://kidechism-api2.onrender.com/short/bird


Create a new web service with the following values:
  * Build Command: `yarn`
  * Start Command: `node app.js`

That's it! Your web service will be live on your Render URL as soon as the build finishes.
