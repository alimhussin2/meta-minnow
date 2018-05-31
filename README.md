# meta-minnow
Kernel module build-in with Intel Ethernet Gigabit (IGB)

# How to include to build enveiroment
1. git clone  meta-minnow to poky directory
2. add this line to ~/poky/build/conf/bblayers.conf
       $HOME/poky/meta-minnow \
3. Build the kenel with IGB patch.
   $ bitbake virtual/kernel
