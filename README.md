# LiteGoldCoin Core [LGC]
==========================
## What is LiteGoldCoin? 
LiteGoldCoin is a cryptocurrency like Bitcoin, although it does not use SHA256 as its proof of work (POW). Taking development cues from Tenebrix and Litecoin, LiteGoldCoin currently employs a simplified variant of scrypt.

https://www.litegoldcoin.net/

 - Coin Name : LiteGoldCoin
 - Currency unit : LGC
 - Algorithm : Scrypt
 - Block Interval : 1 minute (60 seconds)
 - Difficulty Retarget : Every block (using Kimoto's Gravity Well)
 - Total coins amount : 5,000,000,000LGC
Block reward 
 - Premine: First 10 block are 500,000,000 LGC 
 - Bonus reward for block 11 to 200,000 of 1000LGC
 - Bonus reward for block 200,000 - 400,000 of 500LGC
 - Bonus reward for block 400,000 - 600,000 of 250LGC
 - Bonus reward for block 1,400,000 - 1,600,000 of 50 LGC
 - Subsidy is cut in half every 400,000 blocks starting at block 1600000

 
  
### Overview plz make litegoldcoind/litegoldcoin-cli/litegoldcoin-qt

  The following are developer notes on how to build LiteGoldCoin on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

  - [OSX Build Notes](doc/build-osx.md)
  - [Unix Build Notes](doc/build-unix.md)
  - [Windows Build Notes](doc/build-msw.md)

 
# litegoldcoin.conf

  - texindex=1
  - listen=1
  - rpcallowip=127.0.0.1
  - rpcport=32323
  - port=32324
  - addnode=192.168.193.141
  - addnode=138.197.30.135
  - addnode=199.192.16.129
  - addnode=199.192.16.144
  - addnode=159.203.111.166
  - addnode=104.131.73.231
  - rpcuser=LGCuser
  - rpcpassword=LGCpassword


**DEBUG_LOCKORDER**

LiteGoldCoin Core is a multithreaded application, and deadlocks or other multithreading bugs
can be very difficult to track down. Compiling with -DDEBUG_LOCKORDER (configure
CXXFLAGS="-DDEBUG_LOCKORDER -g") inserts run-time checks to keep track of what locks
are held, and adds warning to the debug.log file if inconsistencies are detected.
