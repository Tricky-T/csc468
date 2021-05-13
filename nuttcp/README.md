# Setup

This is nuttcp, a versatile network microbenchmark

To test native linux performance and docker performance:

arldcn28 is the server.
Run sudo bash doitServer.sh on the server.

Then run doit.sh on arldcn24.

After completion you must kill the nuttcp process on the server.
By design nuttcp server processes fork themselves into the background and continue until killed.

killall nuttcp

If you wish to only test native or only docker performance the scripts are seperated in the doit.sh file, and you can comment out one or the other.
Running only one or two tests is also possible as the scripts exist in indpendent files.
