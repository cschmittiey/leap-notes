# leap-notes
notes for using leap
## provider
### webapp
To create admins in the webapp, create services/webapp.json
```json
{
  "webapp": {
    "admins": ["joe"]
  }
}

```
Note: only do this after creating said user.
### nagios
username: nagiosadmin

password: in secrets.json
##bitmask
###installing bitmask on fedora
```
sudo dnf install openssl-devel libffi-devel sqlite-devel python-devel
git clone https://github.com/leapcode/bitmask_client
```
