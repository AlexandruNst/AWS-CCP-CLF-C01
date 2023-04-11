# EC2 Tenancy

3 levels:

![Untitled](EC2%20Tenancy%20f193fc0c6c28443ba5df42a6ecfff481/Untitled.png)

You have the whole server

Stop/Start - host NOT changed

Reboot - host remains

You have a VM but no other VM on that machine

Hardware is dedicated to just one customer. This hardware will only have instances from your account

Stop/Start - host could change

Reboot - host remains

Your instance lives somewhere on one server, and can’t guarantee it’ll be on the same instance on restart

You have a VM and share machine with others

Stop/Start - host change

Reboot from OS - host remains