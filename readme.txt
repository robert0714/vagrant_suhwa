===================
Prerequisite
===================
Please make sure that your Vagrant version is at least 1.8 
and VirtualBox is at least 4.26 
We’ll use it to bring up a virtual machine with CentOs 7

Creating a Vagrant virtual machine is easy.
1 vagrant plugin install vagrant-cachier


The first command is not mandatory, but it will help speeding up the creation of new VMs. It caches
all packages that are being used so that the next time we need them, they are obtained from the
local HD instead being downloaded. The second command does the “real” work. It brings up the
VM called dev. The first attempt might take some time since everything, starting with the base box,
needs to be downloaded. Bringing up this VM will be much faster each consecutive time. Bringing
up any other Vagrant VM based on the same box (in this case bento/centos-7.2) will be fast.
 
===================
Descrpition
===================
3.postgresql（200.200.200.202）

Open http://200.200.0.202:49161/phppgadmin  in your browser with following credential:<br>
username: ude
password: ude

Login by SSH 
ssh root@localhost -p 49160 
password: admin
