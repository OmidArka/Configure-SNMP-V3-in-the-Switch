# Configure-SNMP-V3-in-the-Switch
Configure SNMP V3 in the Switch Cisco

#snmp-server group TEST_GROUP v3 priv

#snmp-server user TEST_USER TEST_GROUP v3 auth sha cisco123 priv des cisco123

Or

#snmp-server user test_user test_group v3 auth md5 PASSWORD priv des PASSWORD2


#access-list 1 permit 192.168.1.1

#show running-config | incl snmp

#show snmp user 

#show snmp group
