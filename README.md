# Journey into SysAdmin World
### Create first user ever
`adduser example_user` \
`adduser example_user sudo` or `usermod -aG sudo example_user` \
Reference:
- https://techdocs.akamai.com/cloud-computing/docs/set-up-and-secure-a-compute-instance#add-a-limited-user-account
- https://phoenixnap.com/kb/linux-adduser
- https://www.digitalocean.com/community/tutorials/how-to-create-a-new-sudo-enabled-user-on-ubuntu
- https://www.digitalocean.com/community/tutorials/how-to-add-and-delete-users-on-ubuntu-20-04
### Create second user.
As a good practice, we have disabled root account (password login). We can't login as root. So how can we add another user? Good news, only **root** or **superuser** can run `adduser` command.
### List all users
`cut -d: -f1 /etc/passwd` \
Reference:
- https://www.hostinger.com/tutorials/how-to-see-system-users-in-ubuntu-linux-vps/
### SSH login
Reference:
- https://techdocs.akamai.com/cloud-computing/docs/set-up-and-secure-a-compute-instance#harden-ssh-access
