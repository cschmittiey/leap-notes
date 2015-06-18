# leap-notes
notes for using leap
## provider
### webapp
To create admins for the webapp, create services/webapp.json in your provider directory
```json
{
  "webapp": {
    "admins": ["joe"]
  }
}

```
Note: only do this **afte**r creating said user.
### nagios
username: nagiosadmin

password: in secrets.json
##bitmask
###installing bitmask on fedora
```
sudo dnf install openssl-devel libffi-devel sqlite-devel python-devel python-pyside
git clone https://github.com/leapcode/bitmask_client
cd bitmask_client
sudo ./setup.py install
```
