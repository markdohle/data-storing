# data-storing

MIT xPro REACT Week 3 - Storing Form Data

Storing Form Data
When you created forms with HTML and React standalone this week, the form data was only saved temporarily within the browser. If you want to use that data again, you need to send it to a database where it can be stored. To communicate with the database, you need to go through the server. Let’s examine the relationship between the client, server, and database to help you understand this workflow. 

 

What Is The Difference Between The Client, Server, And Database?
The client, server, and database each perform a particular role. 

The client, such as a web browser,  sends a request to the server for data 
The server passes that request to the database and provides the requested data to the client
The database stores data and sends it to the server when requested
 

Client, Server, Database Communication Example
Let’s review this workflow through a familiar example: What happens when you want to access your email via a web browser?

The client (the browser on your personal computer) sends a message to Google’s email servers. This happens when you navigate to “mail.google.com”, and your personal computer sends a message to Google that says  “I want to access this web page, “mail.google.com.” 
The server confirms that you are a legitimate user and not a hacker, often using a separate cybersecurity server called Kerberos. 
The server sends a response that validates your access to the resource.
The server retrieves the requested resource from the database. In this case, the login page for “mail.google.com”.
The server sends the requested resource to the client. 
The client displays the resource to the end-user. You can finally see the rendered “mail.google.com” login page. You type in your email address and password. When you click “submit” you begin again at step 1!
As you see through this example, a form containing information is sent from the client to the server, the server communicates with the database to retrieve relevant information, and then the server sends a response back to the client.

