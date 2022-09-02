# ansible-role-postfix-opendkim
A role for CentOS 7 that deploys a Postfix server and signs outgoing emails using OpenDKIM

## Requirements
This playbook is built for CentOS 7.

Please ensure that the posix collection is installed:
`ansible-galaxy collection install ansible.posix`