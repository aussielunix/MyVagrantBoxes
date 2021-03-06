# Collection of Vagrantfile's

# Introduction

In here you will find a collection of Vagrantfile's for quick booting of a variety of OS's.  
How many times have you wondered where a file lives in a particular distro or a packagename etc ?  
Other uses include cross platform testing of puppet / chef modules.

# Workflow

```
# grab this repos if you don't already have it
#
git clone https://github.com/aussielunix/MyVagrantBoxes.git
cd MyVagrantBoxes
ls -1
# pick an OS and change into it's directory
#
cd $distro
# boot it
#
vagrant up
# log in
#
vagrant ssh
# log out and destroy VM
#
vagrant destroy
```

# Requirements

To use this you will need [Oracle's Virtualbox](http://www.virtualbox.org/), [vagrant](http://vagrantup.com) and git.
You will also need some base boxes.  
You can create your own ( see [veewee](https://github.com/jedi4ever/veewee) ) or grab some from [Vagrantboxes](http://www.vagrantbox.es/)

<table>
  <tr>
    <th>Author</th><td>Mick Pollard (aussielunix at g mail dot com</td>
  </tr>
  <tr>
    <th>Copyright</th><td>Copyright (c) 2012 by Mick Pollard</td>
  </tr>
  <tr>
    <th>License</th><td>Distributed under the Apache License, see COPYING</td>
  </tr>
  <tr>
    <th>twitter </th><td>@aussielunix</td>
  </tr>
</table>
