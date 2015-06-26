# server_pi
####Ansible Playbook To strip down the current raspbian release to a more minimal, headless server type setup with minimal security essentials.

First update the *hosts* file to use the IP's of your raspberry pi below the [pis] group,<br />
And edit the **/roles/server_pi/tasks/main.yml** file for your own users needs!

Once you've done that simply cd into the server_pi directory and run:
```bash
ansible-playbook server_pi.yml
```

And get something to drink!

Once it's complete, you can login as your new user and run raspi-config
```bash
sudo raspi-config
```

To complete the expanding of your SD card etc. Also make sure to change the password for the pi user! 
<br />*or remove that user completly!*

Verify it's me from my keybase.io page: https://keybase.io/daniels<br />
Bitcoin always welcome! :)
