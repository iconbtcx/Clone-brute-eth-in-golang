# eth-brute

Bruteforce with sequential and random private keys


## Compile from source

```
git clone git@github.com:rust3r/eth-brute.git
cd eth-blute/
go get
go build
```


## Docker

```
docker build -t app .
docker run -it --rm -p 8545:8545 app
```


## Examples

For help:

```
./eth-brute -h

Usage of ./eth-brute:
  -pk string
        Start private key
  -port int
        Ethereum rpc port (default 8545)
  -random
        Generate random private key
  -server string
        Ethereum rpc server (default "138.197.226.208")
  -threads int
        Number of threads (default 4)
```

Usage:

```
./eth-brute -threads 50 -pk 1206b75e20883f695a49bbabd1f26e5d30afb75e4a9e3989a89d779d4a3a1c92
./eth-brute -threads 50 -random
```

Spare servers can be found in the source code


## Donation
 [![Donate](https://brianmacdonald.github.io/Ethonate/svg/eth-donate-blue.svg)](https://brianmacdonald.github.io/Ethonate/address#0xCE798299aE1963dB012C07C0efaA43Ceee524880)
