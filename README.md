# Description
Exploit for CVE-2022-40684 authentication bypass vulnerability affecting FortiOS, FortiProxy and FortiSwitchManager appliances.

## Disclaimer
This tool is intended for demonstration purposes, only use against systems where you have explicit authorization. Project maintainer is not responsible or liable for misuse of the software. 

## Usage
```plaintext

              .,-:;//;:=,
          . :H@@@MM@M#H/.,+%;,
       ,/X+ +M@@M@MM%=,-%HMMM@X/,
     -+@MM; $M@@MH+-,;XMMMM@MMMM@+-
    ;@M@@M- XM@X;. -+XXXXXHHH@M@M#@/.
  ,%MM@@MH ,@%=             .---=-=:=,.
  =@#@@@MX.,                -%HX$$%%%:;
 =-./@M@M$                   .;@MMMM@MM:
 X@/ -$MM/    Developed by:    . +MM@@@M$
,@M@H: :@:   Mohamed Benchikh  . =X#@@@@-
,@@@MMX, .  (@mohamedbenchikh)  /H- ;@M@M=
.H@@@@M@+,                      %MM+..%#$.
 /MMMM@MMH/.                   XM@MH; =;
  /%+%$XHH@$=               , .H@@@@MX,
   .=--------.           -%H.,@@@@@MX,
   .%MM@@@HHHXX$$$%+- .:$MMX =M@@MM%.
     =XMMM@MM@MM#H;,-+HMM@M+ /MMMX=
       =%@M@M#@$-.=$@MM@@@M; %M%=
         ,:+$+-,/H#MMMMMMM@= =,
               =++%%%%+/:-.

Authentication Bypass Exploit (CVE-2022-40684)
Affected Products: FortiOS, FortiProxy and FortiSwitchManager
Use at your own risk!

usage: CVE-2022-40684.py [-h] [-t TARGET] [-c] [-a] [-v] [-k KEY_FILE]

optional arguments:
  -h, --help            show this help message and exit
  -t TARGET, --target TARGET
                        The IP address of the target
  -c, --check           Check if the target is vulnerable
  -a, --attack          Overwrite admin ssh key
  -v, --verbose         Increase Verbosity
  -k KEY_FILE, --key-file KEY_FILE
                        The SSH key file
```

## Mitigations
Update to the latest version or mitigate by following the instructions below
* https://www.fortiguard.com/psirt/FG-IR-22-377
