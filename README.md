# ansible_webserver
- simple web server install and teardown using ansible
- presumes installation of `httpd`
- adapted from 
    https://www.redhat.com/sysadmin/ansible-callback-plugins

## vars
### required
none
### optional
- `ansible_webserver_remove_httpd`
    - set to `true` to remove software 
