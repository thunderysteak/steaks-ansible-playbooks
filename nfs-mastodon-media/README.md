# Ansible NFS Mastodon Media Playbook

For when you want your Mastodon media to live on a different host and don't want to use S3.

1. Define client and server in hosts.ini
2. Edit common.yml
3. Run with `ansible-playbook playbook.yml -i hosts.ini -u <USER> --ask-become-pass`