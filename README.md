1 • Backup Your Hidden .env File: Take Your Database password 

2 • Export the Database:
Export your database named Pterodacty using the following command:
``mysqldump -u root -p --opt Pterodacty > /var/www/pterodacty/panel.sql``

3 • Follow Pterodacty Installation Documentation:
Refer to the Pterodacty installation documentation for step-by-step instructions on how to install Pterodacty on your new server.

4 • Transfer and Import the Database:
Transfer the panel.sql file to your new server.
Import the database using the following command. Make sure you are in the folder where your .sql dump is located:
``mysql -u root -p Pterodacty < panel.sql``

5 Complete the Panel Migration
Any problem For DM me on discord 
Discord server https://discord.gg/vx7gaKWAZ8
