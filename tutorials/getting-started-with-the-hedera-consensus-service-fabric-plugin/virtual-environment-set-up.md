# Virtual Environment Set-up

Enables developers to run the HCS Hyperledger Fabric sample network using a virtual environment set-up.

## Requirements

* [Hedera testnet](../../testnet/testnet-access.md) account ID and account private key
* [pluggable-hcs repository ](https://github.com/hyperledger-labs/pluggable-hcs)
* [Vagrant](https://www.vagrantup.com/downloads.html)
* [Virtual Box](https://www.virtualbox.org/wiki/Downloads)
* Terminal/IDE

## 1. Open your terminal/IDE and CD to where you would like to clone the fabric-hcs project

* Clone the **pluggable-hcs** repository
* Navigate to the **pluggable-hcs** folder

```text
git clone https://github.com/hyperledger-labs/pluggable-hcs
cd pluggable-hcs
```

* You should now be in the **pluggable-hcs** project folder

## 2. Confirm you are on the master branch

```text
git branch
```

## 3. Navigate to the vagrant folder and start your virtual machine

```text
cd vagrant
vagrant up
vagrant ssh
```

* You should now be back in the **pluggable-hcs** folder

Now you have your virtual envrionment ready to go. Please refer to **step two**: [Build Fabric Binaries and Docker Images](./#2-build-fabric-binaries-and-docker-images) in the master tutorial to continue.

{% page-ref page="./" %}

