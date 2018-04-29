# TIMESUPcoin
The first altcoin to support the #timesup movement. 








Windows and Linux Wallets Available 





-------------------------------------------------------------------------------------------------------------





Basic Mining

1. Download and open your wallet. Be sure that you are connected the block chain syncs up.

2. Close your wallet and create the file timesupcoin.conf in the folder "%APPDATA%\timesupcoin\".

    Paste the following text into timesupcoin.conf and save the file.
    

      rpcuser=yourusername
  
      rpcpassword=yourpassword
  
      rpcallowip=127.0.0.1
  
      rpcport=37114
  
      listen=1
  
      server=1


3. Download the latest version of cpuminer and extract the zip file.

   Available here: https://bitcointalk.org/index.php?topic=55038.0

4. Create a .bat file named mine.bat and paste the following text into mine.bat.

   minerd --url=http://127.0.0.1:37114 --userpass=yourusername:yourpassword

   Save the file inside the extracted cpuminer folder.

5. Open your wallet and execute mine.bat to start mining your first coins.

