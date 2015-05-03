# VCode

VCode is an online environment for collaborative coding where multiple users can edit the same piece of code simaltaneously.

We have deployed this app on the Firebase platform.<br>It comes with two modes:<br>
1. <b>Single user mode</b> This mode is pretty much like your standard online code editing where you get an online editor where you input your code. Our app has built in support for different languages like python, javascript, c++ etc. You have all all basic feautures you would require like multiple language support, syntax highlighting, auto indentation.<br>
2. <b>Collaborative mode</b> for multiple users accessing same text document and editing it. The user can open a new code instance and use the same features as that in single user mode. A user wanting to invite collaborators for his code has to send a copy of the link url to anyone he wants the share the code with. The new user is added to the list of collaborators to that particular file that the master is editing. The new user would also be prompted for a username to identify him/her amongst the other list of collaborators. We may have as many as 20 users sharing the same code with minimal effect on the performance of our app. 

<h3>Technologies used:</h3>
1. <b>Firebase</b> for storing data in json format.
2. <b>Code Mirror API</b> for providing code syntax highlighting and support for famous langauges.

<br>
