# PHP
Open Port Check Script

 This function fsockopen() is used in the Open Port Check Tool for our private blog. You can check whether a certain port is open on a specified IP address or hostname. Before reading take note that most FREE web hosting providers disable fsockopen() function as a security measure so first check whether the function can be used. Another thing to take note is that if fsockopen is unable to connect to a port it doesn’t necessarily mean that port is closed on the remote host, your server in which the script is running might also have block the OUTBOUND connection to that port.
