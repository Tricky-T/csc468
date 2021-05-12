# Setup

To run the tests: enter the command sudo bash doit.sh This will run the native and docker versions 20 times for each CPU configuration.

If you wish to only run a specific test, you can directly run the scripts. Either script must be followed by a number, 1 or 2.

Choose option 1 for one sockets (--physcpubind=0-7,16-23 --localalloc) Choose option 2 for two sockets (--physcpubind=0-31 --interleave=0,1)
