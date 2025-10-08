Static Method:

Switch(config)#interface fa0/1
Switch(config-if)# switchport mode access
Switch(config-if)#switchport port-security 
Switch(config-if)#switchport port-security maximum 1
Switch(config-if)#switchport port-security mac-address aaaa.bbbb.cccc  
Switch(config-if)#switchport port-security violation shutdown
