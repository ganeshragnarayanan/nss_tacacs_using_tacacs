forked from https://github.com/benschumacher/nss_tacplus

To build:
1. make
2. sudo install -m 0644 libnss_tacplus.so.2 /lib/x86_64-linux-gnu/
3. sudo /sbin/ldconfig -n /lib/x86_64-linux-gnu/ /usr/lib
4. sudo /sbin/ldconfig -n /lib /usr/lib
