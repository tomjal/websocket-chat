# Websocket Chat (Alpha)
<a href="http://socket.chat"><img src="http://i.imgur.com/zRTFQ4z.png" title="source: imgur.com" /></a>
Socket.chat is a chat room service that uses HTML5 Websockets and Java Endpoint to provide a full featured chat. It is private and untracked.
<h3>What's good about it?</h3>
<p>It doesn't list chat rooms, so no one will know your chat room exists. It doesn't store any messages on the server. Soon it will be fully encrypted using
HTTPS/WSS.</p>

<h3>How to use</h3>
<p>You can join one of the community chat rooms by navigating to <a href="http://socket.chat">socket.chat</a> and
clicking on one of the rooms listed.</p>
<p>You can create your own private chat room using the following URI format: <b>socket.chat/r/ #any alpha-numeric characters and spaces#</b>. For 
example: <b>socket.chat/r/my private chat room</b></p>
<h3>Current features:</h3>
<ul>
  <li>Join any room</li>
  <li>Create any room</li>
  <li>Change theme</li>
  <li>See who else is in this room</li>
  <li>Message another user in this room</li>
  <li>Mute another user in this room</li>
  <li>Chat rooms are not listed anywhere, so no one will find your chat room</li>
  <li>Message history is not stored</li>
  <li>Clickable links</li>
  <li>Message notification in title</li>
</ul>

<h3>Chat commands:</h3>
<ul>
  <li><b>/help</b> - displays a list of available commands</li>
  <li><b>/themes</b> - displays a list of available themes</li>
  <li><b>/theme #themename#</b> - changes to specified theme</li>
  <li><b>/users</b> - displays a list of users in this chat room</li>
  <li><b>/tell #username# <message></b> - sends a private message to specified user in this room</li>
  <li><b>/mute #username#</b> - mutes specified user in this room</li>
  <li><b>/unmute #username#</b> - unmutes specified user in this room</li>
  <li><b>/mutelist</b> - displays a list muted users in this room</li>
  <li><b>/rules</b> - displays a list socket.chat rules</li>
  <li><b>/clear</b> - clears the chat history</li>
  <li><b>UP ARROW</b> - gets last message sent</li>
  <li><b>TAB</b> - gets last user you private messaged</li>
</ul>

<p><b>To do:</b></p>
<ul>
  <li>Implement HTTPS</li>
  <li>Implement secure websockets</li>
</ul>
