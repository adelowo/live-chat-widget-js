# Live support chat widget using Pusher Chatkit
How to create a customer support chat system using Pusher Chatkit


## Installation
* [Create a Chatkit instance](https://pusher.com/chatkit)
* Once you have created a Chatkit instance, go to the **Console** tab and create a new user called `Chatkit-dashboard`
* Clone this repository.
* `cd` into this repository (`cd live-chat-widget-js`)
* Copy the `config.example.js` file to `config.js` and replace the placeholder keys with your Chatkit application's keys.
* Remember to udpate the `PUSHER_CHATKIT_INSTANCE_LOCATOR` variables in [`assets/admin.js`](https://github.com/adelowo/live-chat-widget-js/blob/master/assets/admin.js) and [`assets/chat.js`](https://github.com/adelowo/live-chat-widget-js/blob/master/assets/chat.js)
* Run `npm install` to install dependencies then `node index.js` to run the server
* Open http://localhost:3000 and http://localhost:3000/admin on your browser


