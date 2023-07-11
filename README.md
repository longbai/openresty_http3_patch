base version openresty 1.21.4.1, nginx 1.25.1
please replace the nginx folder in openresty with nginx 1.25.1
then run patch nginx.patch, op.patch
configure add --with-http_v3_module

issue: the nginx 1.25.1 change request header, and the cookie has changed, so I disable the cookie in the code.
