## [Nginx](https://github.com/amitzworld/Ansible-Playbooks/tree/master/Nginx)

### Playbook have below jobs to perform

- Using Ansible configuration tool to install NGINX on a Debian based distribution such as Ubuntu.
- NGINX configuration for a new virtual host.
	- Should listen to port 80.
	- Should proxy traffic from www.example.com and deliver it to a backend host named localhost on port 3400.
- Send all non www.example.com traffic to a custom 404 page.
- NGINX Config & Service should persist on host restart.
