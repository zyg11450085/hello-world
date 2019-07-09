# hello-world
发卡平台
location / {
if (!-e $request_filename) {
rewrite ^(.*)$ /index.php?$1 last;
break;
}
}
