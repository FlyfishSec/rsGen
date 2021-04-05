
 rsGen - Reverse Shell Payload Generator.
 =

  rsGen is a Reverse Shell Payload Generator for hacking. built by Windows Batch and Jscript. The main features include native command generation and variant command generation. In version 2.0, I added a tcp tunnel feature to receive shell("-ngrok" and "-pgrok").
  
  I will be constantly updating this tool, if you have found any bugs or issues, please let me know via GitHub Issues and i will try my best to get it resolved quickly.
  
![rsGen](https://raw.githubusercontent.com/FlyfishSec/rsGen/master/Screenshot/rsgen.png "rsGen")

## Usage


```

-pub  Generate a "variant command".Use this parameter,the Command will be encoded upload to the
       public pastebin website.

-lan  In some cases, the target machine cannot request an external network.This parameter will call
      mongoose.exe in the command directory(a mini web server, only 144kb, see the website: 
      https://cesanta.com/), enable a web service on the local port 80 for command request execution.
      After the end, you need to manually exit it.

-listen  Start port listening locally to receive shell that bounce back.Start port listening locally 
         to receive a shell that bounces back, Function equivalent to the netcat (call powercat.ps1).

-ngrok  Start ngrok TCP Tunnel(Contains -pub, -listen options).

-pgrok  Start pgrok TCP Tunnel(Contains -pub, -listen options).like ngrok but free and unlimited.

```
![rsGen](https://raw.githubusercontent.com/FlyfishSec/rsGen/master/Screenshot/rsgen-ngrok.png "rsGen-ngrok")


## Operating system

   Windows 7 or higher Windows operating system.

## Donations

   Bitcoin Address QR Code            |  Ethereum Address QR Code         |  Monero Address QR Code
:-------------------------:|:-------------------------:|:-------------------------:
<img width="260" height="260" src="https://raw.githubusercontent.com/FlyfishSec/rsGen/master/Screenshot/donate-btc.png"/>  |  <img width="260" height="260" src="https://raw.githubusercontent.com/FlyfishSec/rsGen/master/Screenshot/donate-eth.png"/> | <img width="260" height="260" src="https://raw.githubusercontent.com/FlyfishSec/rsGen/master/Screenshot/donate-xmr.png"/>

**BTC**: 3F2R6KMXbJ576yJNJpjrBnhVG64Ltg1WoF

**ETH**: 0xab15323b0c7721B6B9fDf5A8089a6Ec697C9feED

**XMR**: 48rBRHh2iV27oHzXMGnjbwCLLyinpqFry6gLTAaQiFVtMRw4kqabeoFiBYqNAPCBHbKjgQezPNLwDihMSNbEPCuYP1xzCWi


