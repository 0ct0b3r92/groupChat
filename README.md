# groupChat
This script allows a group to communicate through chat without disrupting other players..

NOTE this is only an early release new additions can be added and will be added.


[REQUIREMENTS]

* ESSENTIAL MODE with MYSQL => https://forum.fivem.net/t/how-to-setup-fxserver-with-mysql-and-essentialmode4/6136 (only for the default user table. This doesnt actually use any Essential mode functions. If you know how to use MYSQL then set up a table with `group` and `identifier` table

[INSTALLATION]
1) CD into your resources folder
2) Add this to your server.cfg:
 ```
 start groupChat
 ```
 
[USAGE]
The default command is /sc and works for users with the group superadmin. Only superadmin can use and see this command. This can easily be changed if you know what you're doing.
