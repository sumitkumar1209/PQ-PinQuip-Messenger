# PQ : PinQuip Messenger
A `M.E.A.N.` stack based messenger application using PeerJS server

The project is scaffolded using gulp, slush-wean and bower. The UI is developed in LUMX using AngularJS. The Project still not uses MongoDB so as to fulfill the requirement of packaged application.

<b>General Information</b><br>
`Express Server` is started on port no `3000`.<br>
`EJS` is used for HTML renderer for ExpressJS<br>
`PeerJS Server` is started on port no `9000`.<br>
`IndexedDB` is used for database purposes.<br>
`PouchDB` is used as wrapper for IndexedDB<br>
`blueimp-file-upload` is used for FTP over express server.<br>
`AngularJS` is used for creating modules for front-end.<br>
`LUMX` is used as UI framework.<br>
`jQuery is used for DOM Manipulation`.<br>
`Velocity` is used for smoother animations.<br>

<b>Running the Application</b><br>
Requires Node and npm to be installed as prerequisite
<ol>
<li> `npm install -g gulp slush bower slush-wean` [you may require to install yo dependency as well]</li>
<li>Use `npm install` to install the dependencies from `package.json` file</li>
<li>Execute application with the help of gulp or nodewebkit<br>
`gulp run` or `nw .` at the root of project.
</li>
</ol>
