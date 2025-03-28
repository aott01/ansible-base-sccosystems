# ansible-base-sccosystems
This is the general purpose ansible base repo for SCCoSystems.

Hints:
the inventory ./ansible_hosts is not checked in, you need to create it. Define ssh conneciton/auth method in there in the following format
[targets]
localhost ansible_connection=local
<remote_IP> ansible_connection=ssh ansible_user=ansible

