# Bookmark
A web app for organizing bookmarks.

##Prerequisite
* Install Nodejs
* Install Mongodb  
  Create the database named "bookmark" and add user "dineshvgp" with read, write permission.  
  <pre>
  use bookmark;
  db.addUser(
      {
          user: "dineshvgp",
          pwd: "dineshi2it13$",
          roles: [ "readWrite", "dbAdmin" ]
      }
  );
  </pre>
* Install Strongloop
  <pre>npm install -g strongloop</pre>

##Start the server:
<pre>npm start</pre>
