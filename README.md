# OnlineJudge

This is the online judge for SJTU IEEE Honor Class.
This online judge is based on [Sharif Judge](https://github.com/mjnaderi/Sharif-Judge).

## Installation
Download & install [Vagrant](https://www.vagrantup.com/downloads.html) and
[VirtualBox](https://www.virtualbox.org/wiki/Downloads) if you haven't installed them yet.
Make sure `vagrant` and VBoxManage binaries are in system path. Then in command line,

    vagrant up
    vagrant ssh

Now you should be in the a customized ubuntu/trusty64 environment for the OJ.
Follow [http://docs.sharifjudge.ir/en:v1.4:installation](http://docs.sharifjudge.ir/en:v1.4:installation) to complete
the installation.

Sometimes Vagrant forgets the correct vm to connect. See this [http://paulfreeman.me.uk/notes-to-self/point-vagrant-at-correct-virtualbox-vm-when-it-forgets-it-and-creates-a-new-instance](http://paulfreeman.me.uk/notes-to-self/point-vagrant-at-correct-virtualbox-vm-when-it-forgets-it-and-creates-a-new-instance). 
