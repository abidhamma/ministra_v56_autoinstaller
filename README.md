<h1><b>Ministra 5.6.1 Middleware install script for Debian and Ubuntu Distros</b></h1>

<h1><b>*Stalker is Disabled*</b></h1>

<p>

<b><h3> ONLY runs on fresh installs of: </h3></b>

<p>  
  Debian 8
<p>  
  Debian 9
<p>  
  Ubuntu 14.04
<p>  
  Ubuntu 16.04
<p>
<hr>
<b>Install:</b>

<p>

```sh
sudo apt-get install zip
```

<p>
  
```sh
sudo wget https://github.com/abidhamma/ministra_v56_autoinstaller/archive/master.zip
```

<p>
  
```sh
sudo unzip master.zip
```

<p>

```sh
cd ministra_v56_autoinstaller-master
```

<p>

```sh
chmod +x install
```

<p>

```sh
./install
```

<p>

After its done and somehow your Ministra keeps showing error about npm.. then reinstall npm by using

<p>

```sh
sudo npm install -g npm@2.15.11
```

<p>

<p>

```sh
sudo ln -s /usr/bin/nodejs /usr/bin/node
```

<p>

<hr>
<h3><b>IMPORTANT: During the install it will ask you to enter the MySQL Password which is "st@lk3r"</b></h3>
<hr>
<h2><b>Info:</b></h2>

1) Will work on Debian 7, 8 and Ubuntu 14.04

2) Will work on Debian 7, 8 and Ubuntu 14.04

3) Will work on Ubuntu 16.04

4) Will work on Debian 7, 8

5) Will work on Debian 7, 8 and Ubuntu 16.04

6) Exit

<hr>
<h3><b>ORIGINALLY CREATED BY SlaSerX https://github.com/SlaSerX/stalker</b></h3>

This script will work on Debian, Ubuntu and probably other distros
of the same families, although no support is offered for them. It isn't
bulletproof but it will probably work if you simply want to setup a Stalker WM Portal on
your Debian/Ubuntu box. It has been designed to be as unobtrusive and
universal as possible.

Snake24564 modified this script to install Ministra 5.6 for Ubuntu and Debian and made it that you can now install Stalker Middleware 5.2 when you press install Stalker Middleware.

This is a free shell script under GNU GPL version 3.0 or above

Author Ivan Bachvarov a.k.a SlaSerX

Modified by Snake24564

Modified by abidhamma

<b>Copyright <b>©</b> 2017 LinuxHelps project.</b>
<hr>
