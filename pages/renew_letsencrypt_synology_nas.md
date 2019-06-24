# Renew Let’s Encrypt Synology – 4 Step Guide
How to renew Let’s Encrypt certificates on a Synology NAS.


- Open TCP port 80 on your router and forward to your NAS.
- ssh into your NAS.
- sudo su - (to get root).
- run syno-letsencrypt renew-all -vv (this will renew all your certificates).

Done.

Now that you have your certificates renewed don’t forget to close port 80 again on your router.