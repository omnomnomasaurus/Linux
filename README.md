# Linux

For ease of use, the best way I find to use this script is:

elevate to root user -> sudo su
change directory to /bin -> cd /bin
use wget to download the script to the /bin file -> wget https://rawgit.com/omnomnomasaurus/Linux/Ubuntu/adutil
run the script (no need to 'bash adutil') -> adutil

Once this script has run to completion, there will be an entry for the machine it ran on, in Active Directory Users and Computers, under the Computers organisational unit.  There will also be an entry in the Domain DNS forward lookup zones for the machine.
