# juiceshop-azure-ctf
Script for hosting a OWASP JuiceShop CTF on Azure Containers

Prerequisites:
1) Docker
2) Azure CLI

Tweak the variables in the top of the script to your liking. The rest should be fire and forget. You may run
into problems where the CTFd config cannot be created if container instantiation is slower than usual (challenges are fetched from the first instance),
if that happens simply run the script again.
