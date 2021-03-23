
 rsGen v2.0 - Reverse Shell Command Genrator.
 =

  rsGen is an automated reverse shell command genrator, built by Windows Batch and Jscript. The main functions include native command generation and variant command generation. In version 2.0, I added an anonymous reverse shell receiving function "-ngrok" and "-pgrok".
  
![rsGen](https://raw.githubusercontent.com/FlyfishSec/rsGen/master/doc/rsgen.png "rsGen")

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

-ngrok  Start ngrok TCP Tunnel(Contains -pub, -listen options).Notice:I added a ngrok authtoken. Since
       it is a free plan, it may not be available to multiple people. You can go to ngrok.com to apply 
       for your own authtoken, and then modify your authtoken in the include/config.yaml file

-pgrok  Start pgrok TCP Tunnel(Contains -pub, -listen options).like ngrok but free and unlimited.

```
![rsGen](https://raw.githubusercontent.com/FlyfishSec/rsGen/master/doc/rsgen-pgrok.png "rsGen-pgrok")


## Operating system

   A Windows 7 or higher Windows operating system.




