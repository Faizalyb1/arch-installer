# This is yb1 arch-installer(only for VM).
** yb1 arch-installer is a Script to Install ArchLinux. **
### Step 1: loading your keyboard layout.

loadkey ...

### Step 2: install git.

pacman -Sy git

### Step 3: clone the script.

git clone https://github.com/Faizalyb1/arch-installer.git

### Step 4: copy the "yb1.sh" to the root.

cp arch-installer/yb1.sh /root

### Step 5: make the script executable.

chmod +x yb1.sh

### Step 6: run the script.

./yb1.sh

Note1: The script is going to launch cfdisk and you have to creat 3 partition, the first one is /boot and the second is the SWAP partition and the 3 is the / filesystem in this order.

Note2: After the installation is finished you need to reboot the system.

*** End ***

# This is Suckless Power.
** suckLess.sh is a Script to SetUp The Suckless Tools. **

Note: Make sure you login with your user name.
### Step1: git the script.
git clone https://github.com/Faizalyb1/arch-installer.git

### Step2: copy the script to your home directory and make it executable.
cp ArchMega/suckLess.sh
chmod +x suckLess.sh

### Step3: run the script.
./suckLess.sh

Note: At the end your pc is going to reboot.

Thank you.
