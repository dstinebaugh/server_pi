# server_pi
Ansible Playbook To strip down the current raspbian release to a more minimal, headless server type setup.

Of course, update the hosts file to use the IP of your pi under the [pis] group,<br />
And edit the <b>/roles/server_pi/tasks/main.yml</b> file for your own users needs!

Once you've done that simply cd into the server_pi directory and run:
'ansible-playbook server_pi.yml'
And get something to drink!

Once it's complete, you still need to run raspi-config
'sudo raspi-config'

And make sure to change the password for the pi user!

Verify it's me from my keybase.io page: https://keybase.io/daniels<br />
Bitcoin always welcome! :)
