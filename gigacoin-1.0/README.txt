To use gigacoind, you must set a rpcpassword in the configuration file:

C:\Users\<your user>\AppData\Roaming\Gigacoin\gigacoin.conf

You will have to make this directory.

Obviously replace <your user> with the username of the user
you are curently logged in as.  For example, if you are
logged in as Owner, the exact location of  the gigacoin.conf
file should be:

C:\Users\Owner\AppData\Roaming\Gigacoin\gigacoin.conf

An example rpcuser/rpcpassword combination would be:

rpcuser=gigacoinrpc
rpcpassword=5DRGskRfsgddG1sNc26npniyXavWjiHXX5WP2KZ4CGm9

(you do not need to remember this password unless you want to solo-mine against this daemon)

If the file does not exist, create it with owner-readable-only file permissions.

An example gigacoin.conf file is provided with this distribution.

You will only need to modify the rpcuser/rpcpassword to obtain a working daemon.

You will also need to set: server=1 (comes with server=0), which you can easily
find by searching gigacoin.conf

We learned a LOT in the process of releasing a new coin. Interested in a step by step guide?
We cover: psvTimestamp generation, genesishash creation and solving, replacement of the merkleroot,
pnseed modification, pchmessagestart modification, pubScriptKey (master ECDSA keypairs) creation,
initial blockhash checkpointing, and more! We will also cover the compilation process in Windows and Linux for both the Qt GUI Client, and the Server Daemon. We'll try to reply to any inquiry
about the guide (make sure to mention the TxID of your donation) ASAP!

Email: gigacoin2013@gmail.com
Web: http://gigaco.in

Donation Addresses:

BTC: 1KiwXTNxPP4Zsptx4FCuCczFe9u3m3yPaQ
LTC: LcAiff7hWd55Tni6c58jU1DRJMsCnAw68W
NVC: 4EmrwcsBrKPpokzqVJpYRmXaqAN3fvSV76
