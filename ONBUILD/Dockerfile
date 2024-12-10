from almalinux:8
run yum install nginx -y
run rm -rf /usr/share/nginx/html/index.html
Onbuild add index.html /usr/share/nginx/html
cmd ["nginx", "-g" , "daemon off;"]