![N|Solid](https://www.wyith.edu/logo_bankcoin_256x256.png)

# Introduction
The Bankcoin Reserve (BCR) Coin is a high value/low volume cryptocurrency making it very attractive for use by banks, financial institutions and insurance companies. This solves problems associated with moving large asset or commodity value quickly, and at low cost. The BCR Coin also has the unique ability to mint up to 10% of the principal amount held in its proprietary digital wallet.

# Patents

Now days there are thousand of altcoins without any real use and backing. With  [Gary Mcalister's](https://www.amazon.com/Blockchain-Prophecy-Gary-Gabriel-McAlister/dp/0648173704/ref=sr_1_1?qid=1567079624&refinements=p_27%3AMr+Gary+Gabriel+McAlister&s=books&sr=1-1&text=Mr+Gary+Gabriel+McAlister) vision and innovations as well as AAABlockchain Ltd's involvement (a Belize business founded by Nina Taylor with Wyith Community as one of the major shareholders), Bankcoin Reserve (BCR) holds eight Australian patents, see https://www.wyith.edu/bankcoin_patent.htm

* Patent 1 - Savings and Deposits Innovation
* Patent 2 - Loan and Finance Innovation
* Patent 3 - New Monetary System Innovation
* Patent 4 - Private Placement / High Yield Innovation
* Patent 5 - Stock and Bond Innovation
* Patent 6 - Franchise Innovation
* Patent 7 - Islamic Banking Innovation
* Patent 8 - Foreign Exchange Innovation
# Important Links

| Utility | Link |
| ------ | ------ |
| Website | https://www.wyith.edu/bankcoin |
| Block Explorer | coming |

# Dependencies & Compilation

* Operating System: [Ubuntu 16.04](http://releases.ubuntu.com/16.04/)
* RAM: Minumum 2 GB
* A modern prcoessor with minimum 2 Cores

If you are running an exchange or any other application and want to integrate Bankcoin Reserve there, please [Contact Us](https://bankcoinreserve.io/contact/) here  for Yellow Paper and Technical Support.

Install the dependencies in desktop or server:

```sh
$ sudo  apt-get update

# Git
$ sudo  apt-get install git -y

# libssl for cryptography and libevent for Networking
$ sudo  apt-get install build-essential libtool autotools-dev automake pkg-config libssl-dev libevent-dev bsdmainutils -y

# Boost Utility  for threading, Data Structures etc
$ sudo  apt-get install libboost-system-dev libboost-filesystem-dev libboost-chrono-dev libboost-program-options-dev libboost-test-dev libboost-thread-dev -y
$ sudo  apt-get install libboost-all-dev -y

# BerkleyDB for wallet support
$ sudo  apt-get install software-properties-common -y
$ sudo  echo | add-apt-repository ppa:bitcoin/bitcoin
$ sudo  apt-get update
$ sudo  apt-get install libdb4.8-dev libdb4.8++-dev -y

# upnp for firewall-jumping support
$ sudo  apt-get install libminiupnpc-dev -y

# ZMQ
$ sudo  apt-get install libzmq3-dev -y

# QT
$ sudo  apt-get install libqt5gui5 libqt5core5a libqt5dbus5 qttools5-dev qttools5-dev-tools libprotobuf-dev protobuf-compiler -y
$ sudo  apt-get install libqt4-dev libprotobuf-dev protobuf-compiler -y

```

Cloning and Compilation:

```sh
# Clone the source code from github
$ git clone https://github.com/BankcoinReserve/bankcoin

# Give read write and execute permissions to bankcoin directory
$ sudo chmod -R 777 bankcoin

# Compile the source code for cli wallet
$ cd bankcoin/src && make clean -f makefile.unix && make -f makefile.unix

# Compile the source code for gui wallet
$ cd .. && qmake && make
```

License
----

[MIT](https://github.com/BankcoinReserve/bankcoin/blob/master/COPYING)



