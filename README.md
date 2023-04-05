# open5gs-webui
#Add web functions on the basis of the open5gs.

Installation

1. Upload the V202304-plugin compressed package to /home
2. Create /home/2023-03-11 directory
3. Unzip the v2.6.1.tar.gz compressed file to the directory
4. Enter /home/2023-03-11/open5gs-2.6.1/ and rename webUI to open5gs/
5. Enter open5gs/, delete the src/ server/ directory, and use the src/ server/ in the V202304-plugin compressed package
6. Execute sudo npm clean-install, sudo npm run build
7. Create a soft link under  /usr/lib/node_module/ open5gs -> /home/2023-03-11/open5gs-2.6.1/open5gs/
