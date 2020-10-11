Create custom groups named HDFC and SBI such that #node1.example.com belongs to HDFC and #node2.example.com belongs to SBI.
Create a hdfc.yml and sbi.yml which should be able to do the following:-
a) Compress directory /var/log into /home/hdfc.tgz for HDFC group.
b) Compress directory /var/log into /home/sbi.tgz for SBI group

Also we've to five entry of the manage hosts in the groups HDFC and SBI.
Create a file named "inventory" and give the below entries.
[HDFC]
node1.example.com

[SBI]
node2.example.com

Note: The playbook will not execute until you don't define the groups.

Use command "ansible-playbook filename" to run the playbook
