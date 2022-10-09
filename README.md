# chat_messanger
This project was bootstrapped with [Create React App]

About this project - Basically it is a chat messaging app, It uses express and node.js for backend. We make connections to the server using socket.io library. This also supports scrolling over the messages because of react-scroll-to-bottom library. This project allows different users to connect to the same chat room and chat with each other.

If same person connects using two different hosts, he will be chatting with himself because of the same sender and recipient of the messages.

This app also keeps track of the time, when the message was sent.

# npm start
Runs the app in the development mode.
Open http://localhost:3000 to view it in the browser.

![newp2](https://user-images.githubusercontent.com/84314022/193533132-b79019f7-8181-4d43-a0fb-6e08961ef7dd.png)

This is the login page where client will enter their credentials.
They will get connected to the server.

![newp](https://user-images.githubusercontent.com/84314022/193533323-cae080b2-5ffa-4a57-8d43-31ec867a2abd.png)

Now they can chat with each other .
This app also supports scrolling over the texts for which we have used 'react-scroll-to-bottom' library.
