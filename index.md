## Rampage Networks Development

This page serves as the first line for updates and progress into the development and modification of tools and resources.

### Pterodactyl

As of recently, I have grown tired of dealing with multiple types of authentication for resources. As some may know, I use the Pterodactyl Panel from https://pterodactyl.io/ After spending much time handling the panel and daemon, I have grown tired of managing multiple usernames and passwords, and got the wonderful idea to implement LDAP authentication. To sum up current progress, it mostly works, but tends to break. Currently the implementation runs off of authenticating LDAP through the daemon's host (currently CentOS 7 in testing) and simply authenticates as a standard system user. The web panel has also been modified to show the status of the connection (not yet functioning) to the Active Directory server.

```markdown
Current Progress:
- Install Pterodactyl daemon & panel entirely ✅
- Deploy server successfully ✅
- Connect host to Active Directory server ✅
- Setup Group based permissions ❌
- Finish configuring status inside web panel ❌
- 
```

### FiveM

Oh boy this never stops breaking......

### Contact

Want to reach out and see if certain projects are underway? Send me an email at contact@rampagenetworks.com
