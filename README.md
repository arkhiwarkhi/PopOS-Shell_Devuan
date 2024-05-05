# PopOS-Shell-Devuan
A guide to running the Pop!_OS Shell on Devuan, GNOME.

1. Install Nodejs and npm.
```
sudo apt-get install nodejs npm
```
2. Install typescript.
```
sudo npm install --global typescript
```
3. Clone the relevant github branch.
For Daedalus and prior (GNOME versions 3.36-44):
```
git clone -b master_jammy https://github.com/pop-os/shell
```
For GNOME versions beyond 44:
```
git clone https://github.com/pop-os/shell
```
4. Install the software on your system, making sure to restart the session or completely reboot as required when directed.
```
make local-install
```
5. Make sure to restart the session or completely reboot as necessary: the instruction will be echoed to the terminal when this is necessary.
