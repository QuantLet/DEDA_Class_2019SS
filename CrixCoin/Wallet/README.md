[<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/banner.png" width="888" alt="Visit QuantNet">](http://quantlet.de/)

## [<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/qloqo.png" alt="Visit QuantNet">](http://quantlet.de/) **CrixCoin_Wallet** [<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/QN2.png" width="60" alt="Visit QuantNet 2.0">](http://quantlet.de/)

```yaml

Name of Quantlet: CrixCoin_Wallet

Published in: DEDA_Class_2019SS

Description: This folder contains the code to compile the GUI of the wallet and access it

Keywords: wallet, crixcoin, crix

Author: Kevin Noessler, Thomas Herrdum

Submitted:  24. Jul 2019,  Kevin Noessler, Thomas Herrdum

```

### C++ Code
```C++

// After the compilation was successfull and the crixcoind was cretaed, the GUI of the wallet can be compiled and is accessible.
// Naviagte to the src/ of the crixcoin
cd src/
// Use the following prompts to create and compile the GUI of the wallet
make
qmake
// After compilation was successfull, the wallet can be accessed via the GUI interface or the following prompt
cd/../crixcoin/
./crixcoin-qt


```

automatically created on 2020-03-10