# ISE Chat

🚀 `A free WebRTC browser-based video call, chat and screen sharing` 🚀

<br>

## Features

- Is 100% `Free` and `Open Source`
- No download, plug-in or login required, entirely browser based
- Unlimited users, without time limitation
- Room Url Sharing (share it to your participants, wait them to join)
- WebCam Streaming (Front - Rear for mobile)
- Audio Streaming
- Screen Sharing to present documents, slides, and more...
- Select Audio Input - Output && Video source
- Recording your Screen, Audio and Video
- Chat & Emoji Picker & Save the conversations
- Full Screen Mode on click
- Possibility to Change UI Themes
- Right click on Video elements for more options
- Direct peer-to-peer connection ensures lowest latency thanks to webrtc

## Quick start

- You will need to have [Node.js](https://nodejs.org/it/) installed, this project has been tested with Node version 12.X
- Clone this repo

```bash
git clone https://github.com/harish-h27/dsce-ise-chat.git
cd dsce-ise-chat
```

## Setup Turn and Ngrok

- Copy .env.template to .env

```bash
cp .env.template .env
```

`Turn`

- Create an account on http://numb.viagenie.ca
- Get your Account USERNAME and PASSWORD
- Fill in your credentials in the `.env` file
- Set `TURN_ENABLED=true`, if you want enable the Turn Server.

`Ngrok`

- Get started for free https://ngrok.com/
- Fill in your authtoken in the `.env` file
- Set `NGROK_ENABLED=true`, if you want to expose the server using the https tunnel, starting it from your local pc.

## Install dependencies

```js
npm install
```

## Start the server

```js
npm start
```

- Open http://localhost:3000 in browser
- If you want to use a client on another computer/network, make sure you publish your server on an HTTPS connection.
  You can use a service like [ngrok](https://ngrok.com/) Or deploy it on [heroku](https://www.heroku.com/).

## Credits

Many Thanks to:

- Nishchay
- Karthik
- Bharath

<p align="center"> Made with ❤️ by <a href="https://www.linkedin.com/in/harish-h-0807561b3/">Harish H</a></p>
