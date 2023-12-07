# LinuxAssignment3pt2


# hello.conf
1. File stored in /etc/nginx/sites-available
2. Created symbolic link to /etc/nginx/sites-enabled
3. Added location, proxypath

# hello-server.service
1. File stored in /etc/systemd/system
2. added: ExecStart=/home/web/bin/hello-server, WantedBy=multi-user.target, and created directory for logs.

# hello-server binary
1. Stored in /home/web/bin directory

# index.html
1. Stored in /var/www/my-site/


