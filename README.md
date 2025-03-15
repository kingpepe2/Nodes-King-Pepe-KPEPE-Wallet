To ensure your King Pepe (KPEPE) wallet connects to the correct network nodes, you need to modify the kingpepe.conf file and add the following nodes:

addnode=kpepesolo.pool.sexy:21053
addnode=kpepe.pool.sexy:11053

🔹 For Windows
Press Win + R, then type:

%appdata%\kingpepe\

Look for the kingpepe.conf file. If it doesn’t exist, create a new text document and rename it to kingpepe.conf.

Open the file with Notepad or Notepad++ and add the following lines:

addnode=kpepesolo.pool.sexy:21053
addnode=kpepe.pool.sexy:11053

Save the file and restart your wallet.


🔹 For Linux
Open a Terminal and navigate to the wallet directory:
cd ~/.kingpepe/
Edit the kingpepe.conf file (or create one if it doesn’t exist):
nano kingpepe.conf
Add the following nodes:
addnode=kpepesolo.pool.sexy:21053
addnode=kpepe.pool.sexy:11053
Save the file by pressing Ctrl + X, then Y, and Enter.
Restart your wallet using:

kingpeped -daemon

📌 Check if Your Wallet is Connected
After restarting the wallet, check if it’s connected to the network by using the following commands in the Console:

getpeerinfo

getconnectioncount
If your wallet is successfully connected, it will display a list of connected nodes and the current number of active connections.

✅ Your wallet is now properly connected to the King Pepe network! 🚀
