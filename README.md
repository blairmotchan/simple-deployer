Simple Deployer

**Why**
I no longer needed a continuosintegration environment, so no more Jenkins!
 
In the time it would take to find something else that did what I needed, I could write my own deployer.

**Is this better than Jenkins or other deployment software?**
Probably not.

**Why would you want to use this?**
Because you don't want the overhead of jenkins and you don't want to manage and configure a bunch of stuff just to deploy some simple apps.

Look at example.yml for a simple example configuration

**Notes**
This assumes you are using ssh keys for scp and ssh.  Passwords are not supported, but would be easy to add

**TODO**
add more usage instructions 
provide better error message
add support for passwords
improve the command line and ssh command chaining
make it useful for at least one other person than me
turn it into a gem
