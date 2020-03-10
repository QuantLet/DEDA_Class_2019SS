[<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/banner.png" width="888" alt="Visit QuantNet">](http://quantlet.de/)

## [<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/qloqo.png" alt="Visit QuantNet">](http://quantlet.de/) **CrixCoin_Public_Private_Key** [<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/QN2.png" width="60" alt="Visit QuantNet 2.0">](http://quantlet.de/)

```yaml

Name of Quantlet: CrixCoin_Public_Private_Key

Published in: DEDA_Class_2019SS

Description: This folder contains the code to create a new key pair for the Crix Coin

Keywords: public key, private key, crixcoin, crix

Author: Kevin Noessler, Thomas Herrdum

Submitted:  24. Jul 2019,  Kevin Noessler, Thomas Herrdum

```

### C++ Code
```C++

//
//  Public_Private_Key creation to secure the Crix Coin

openssl ecparam -genkey -name secp256k1 -out alertkey.pem
openssl ec -in alertkey.pem -text > alertkey.hex

openssl ecparam -genkey -name secp256k1 -out testnetalert.pem
openssl ec -in testnetalert.pem -text > testnetalert.hex

openssl ecparam -genkey -name secp256k1 -out genesiscoinbase.pem
openssl ec -in testnetalert.pem -text > genesiscoinbase.hex

```

automatically created on 2020-03-10