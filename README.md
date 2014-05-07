Openfire-GCM
============

GCM Plugin for Openfire


Binary JAR File: https://github.com/meisterfuu/Openfire-GCM/blob/master/gcmh.jar?raw=true
You can test/debug the plugin with "https://posttestserver.com/post.php" oder similar services if you don't already have your own webservice up and running.
Messages to a JID with a diffrent XMPPDomain than the one from the server will not be forwarded.


Known bugs
============

"Fire GCM event only if target user has no available ressource." seems to work now, but no further testing than a few messagen with 2 accounts at the moment!



Todo
============

Add mode that sends gcm if there is no mobile ressource online. (Identified by ressource - Regex match on the ressource)
