[<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/banner.png" width="888" alt="Visit QuantNet">](http://quantlet.de/)

## [<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/qloqo.png" alt="Visit QuantNet">](http://quantlet.de/) **CrixCoin_Branding** [<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/QN2.png" width="60" alt="Visit QuantNet 2.0">](http://quantlet.de/)

```yaml

Name of Quantlet: CrixCoin_Branding

Published in: DEDA_Class_2019SS

Description: This folder contains the code to brand the Crix Coin correctly 

Keywords: compilation, crixcoin, crix

Author: Kevin Noessler, Thomas Herrdum

Submitted:  24. Jul 2019,  Kevin Noessler, Thomas Herrdum

```

### C++ Code
```C++

// string replacment 
find . -type f -print0 | xargs -0 sed -i 's/hitcoinx/crixcoin/g'
find . -type f -print0 | xargs -0 sed -i 's/Hitcoinx/Crixcoin/g'
find . -type f -print0 | xargs -0 sed -i 's/HitCoinX/Crixcoin/g'
find . -type f -print0 | xargs -0 sed -i 's/HITCOINX/CRIXCOIN/g'
find . -type f -print0 | xargs -0 sed -i 's/HTX/CRIX/g'

```

automatically created on 2020-03-10