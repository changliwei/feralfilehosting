
### Common links

[putty 0.63 installer](http://the.earth.li/~sgtatham/putty/latest/x86/putty-0.63-installer.exe)

[putty 0.63 zip](http://the.earth.li/~sgtatham/putty/latest/x86/putty.zip)

Optionally, you can edit it over FTP, please read and understand this FAQ first - [Text editing - Over FTP or SFTP](https://www.feralhosting.com/faq/view?question=219)

In SSH do the commands described in this FAQ. If you do not know how to SSH into your slot use this FAQ: [SSH basics - Putty](https://www.feralhosting.com/faq/view?question=12)

How to [SSH](https://www.feralhosting.com/faq/view?question=12) into your slot.

[SSH](https://www.feralhosting.com/faq/view?question=12)

[text editor](https://www.feralhosting.com/faq/view?question=219)

You can do this from the [Install Software](https://www.feralhosting.com/manager/slot/install?) page for that slot.

You can do this from the Install Software link in your [Account Manager](https://www.feralhosting.com/manager/)

[**Install Software** link in your Manager](https://www.feralhosting.com/manager/)

[Slot Detail](https://www.feralhosting.com/manager/) page for the relevant slot

[Account Manager](https://www.feralhosting.com/manager/)

[open a ticket](https://www.feralhosting.com/manager/tickets/new)

[IRC](https://www.feralhosting.com/chat)

You will need to have MySQL already installed. You can do this from the [**Install Software** link in your Manager](https://www.feralhosting.com/manager/)

Where username is your Feral username and server is the name of the server that is hosting rutorrent.

where `user-name` is your Feral user-name and `server` is the name of the Feral server your slot is hosted on:

Now we enter the SSH command to connect to the slot, where `username` is your Feral username and `server` is the name of the server you wish to SSH into:

~~~
peterpan@aphrodite.feralhosting.com
~~~

~~~
![](https://raw.github.com/feralhosting/feralfilehosting/master/Feral%20Wiki/0%20Generic/install_mysql.png)
![](https://raw.github.com/feralhosting/feralfilehosting/master/Feral%20Wiki/0%20Generic/mysql_socket.png)

![](https://raw.github.com/feralhosting/feralfilehosting/master/Feral%20Wiki/0%20Generic/slot_detail_link.png)
![](https://raw.github.com/feralhosting/feralfilehosting/master/Feral%20Wiki/0%20Generic/slot_detail_ssh.png)

![](https://raw.github.com/feralhosting/feralfilehosting/master/Feral%20Wiki/0%20Generic/rutorrent.slotdetails.png)
![](https://raw.github.com/feralhosting/feralfilehosting/master/Feral%20Wiki/0%20Generic/deluge.slotdetails.png)
![](https://raw.github.com/feralhosting/feralfilehosting/master/Feral%20Wiki/0%20Generic/transmission.slotdetails.png)

![](https://raw.github.com/feralhosting/feralfilehosting/master/Feral%20Wiki/0%20Generic/install_software_page.png)
![](https://raw.github.com/feralhosting/feralfilehosting/master/Feral%20Wiki/0%20Generic/install_software_link.png)
~~~

Then press and hold `CTRL` and then press `c` to quit.

Then press and hold `CTRL` and then press `x` to save. Press `y` to confirm.

Then press and hold `CTRL` and `a` then press `d` to detach from the screen. This leaves it running in the background.

where `username` if your Feral username and `server` if the name of the server that the relevant slot is hosted on.

### Common Commands

~~~
source ~/.bashrc && source ~/.profile
~~~

Add `PATHS` to the `~/.bashrc`#

Python `~/.local/bin`:

~~~
[[][/[][ ! "$(grep '~/.local/bin' ~/.bashrc)" ]] && echo 'export PATH=~/.local/bin:$PATH' >> ~/.bashrc ; source ~/.bashrc
~~~

Custom software installations to `~/programs`

~~~
[[][/[][ ! "$(grep '~/programs/bin' ~/.bashrc)" ]] && echo 'export PATH=~/programs/bin:$PATH' >> ~/.bashrc ; source ~/.bashrc
~~~
~~~
[[][/[][ ! "$(grep '~/programs/lib' ~/.bashrc)" ]] && echo 'export LD_LIBRARY_PATH=~/programs/lib:$LD_LIBRARY_PATH' >> ~/.bashrc ; source ~/.bashrc
~~~