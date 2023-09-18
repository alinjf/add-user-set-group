## add user to linux and set group script
clone and executable mode to file and run it
```bash
chmod +x add-user.sh
```
you change the group name in code line 16
```bash
usermod -g $groupName "$username"
```

when you run the script it asks username and plaintext password, if users exist show an error.
