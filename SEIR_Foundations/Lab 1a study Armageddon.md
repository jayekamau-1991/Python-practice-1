Lab 1a study Armageddon
What you did today (simplified)

You built a small AWS setup where a web server talks securely to a database.

You used an EC2 server to run a simple notes website.

You used an RDS MySQL database to store the notes.

You locked the database down so only the EC2 server can reach it, not the public internet.

You stored the database username and password in AWS Secrets Manager instead of putting them in code.

You connected to the EC2 server using SSH and your .pem key from your Mac.

You ran a startup script on the EC2 server that:

Installed Python and the required libraries

Created a small Flask web app

Set the app to run automatically as a system service

You fixed an error where the app could not read secrets by making sure the EC2 server had the correct IAM role and permissions.

Once permissions were correct, the app successfully:

Created a database and table

Added notes through the browser

Displayed the stored notes from the database

You confirmed everything worked and collected screenshots as proof.
