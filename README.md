# HTTP-Proxy-payload-injection
This project is a simple HTTP Proxy (MITM), using Bettercap to inject JavaScript code in http pages through local networks. 
Remember, here I will show the vulnerability with a simple js script as an exemple, you can suite yourself to modify in your machine the js 
code.

## How to Download
First install Bettercap latest version in your Linux type:
```bash
sudo apt-get install bettercap
```
Then, clone the repository.
```bash
git clone https://github.com/Citeli-py/HTTP-Proxy-payload-injection/
```
## Setting up bettercap
Go to the cloned directory:
```bash
cd HTTP-Proxy-payload-injection/
```
then, execute bettercap with the caplet:

```bash
sudo bettercap --caplet js_inject.cap
```
In some machines maybe you will need to add some delay in the caplet.

## Bettercap
Visit the bettercap repository and bettercap website to learn how to use this powerfull tool
https://github.com/bettercap/bettercap
https://www.bettercap.org/
