# Setup

To test native performance:

Run the linuxServer.sh file on the arldcn28 node.
After it is complete there is a netserver already running.

Now go to the client node and run linux.sh
After it is complete run sudo killall netserver on the server.

To test docker performance:
Run dockerServer.sh on the arldcn28 node.

Now go to the client node and run dockerClient.sh
After it is complete use docker stop to end the server container.

DO NOT FORGET TO REMOVE THE NETSERVER AFTER YOU ARE DONE
YOU WILL GET INCONSISTANT RESULTS IF YOU MISMATCH
