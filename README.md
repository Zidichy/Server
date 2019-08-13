# Server
Fully Working nginx web server for windows OS.

Set to Reverse Proxy as default, for high security. | https:// redirect set as default.
Only need to open 2 ports in the router.
Port 80 & Port 443.
Every other service will run via port 443.

This nginx & it's configs are set to work with Organizr & with HTTP Authentication. 
Configured to require admin level login when trying to reach /plex or /sonarr ect through domain's subdir.

Always change domain / domain.com in the .conf files to your very own FQDN (Fully qualified domain name)!

More info finally added ^^ full guides now available in the links below.
Swedish Guide.<br>
https://www.sweclockers.com/forum/post/18019307/

English Guide.<br>
https://www.reddit.com/r/nginx/comments/cppfo7/full_detailed_guide_on_how_to_get_nginx_ssl/
