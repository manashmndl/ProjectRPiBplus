# ProjectRPiBplus

* Change rpi b+ from dhcp to static
* Put the address in putty for ssh
* Change the address of Lan to the default gateway for sharing internet [Success Rate 50-50]
* **For B: execute the commands**:
  * `sudo rm -r /var/lib/apt/lists/partial/*`
  * `sudo rm -r /var/lib/apt/lists/*`

* Changed international timezone to dhaka
  * Changed source list using this command: `sudo nano /etc/apt/sources.list` 
  * -> Default one works just fine, no need to change

* Still no luck with B+ :(
