       /////    /////    /////////////
      CCCCC/   CCCCC/   | CC-attack |/
     CC/      CC/       |-----------|/ 
     CC/      CC/       |  Layer 7  |/ 
     CC/////  CC/////   | ddos tool |/ 
      CCCCC/   CCCCC/   |___________|/

# CC-attack ![](https://img.shields.io/badge/Version-1.8-brightgreen.svg) ![](https://img.shields.io/badge/license-MIT-blue.svg)
**Use Socks5 proxy to ddos(Http-Flood) attack.**

***Added Http-Post attack mode***

*Slow Attack Can Bypass some WAF, it used to attack apache2 server is the best :)*

(It supports socks4 too,but the best choice is using socks5)

And now it is upgraded to **python3 version**.

***Support https*** :)

# License

MIT License

## News

**Added random header**

**SLOW attack mode AND HTTP-POST attack mode ADDED**

*AUTO ENABLE SSL MODE, NO MORE "https(y/n):" choice*

*Added google search referer header*

***Fixed*** some *bug* when doing **SSL requests**.

"Download socks5 list" is added in this script.

## Install

    pip3 install requests pysocks
    git clone https://github.com/Leeon123/CC-attack.git
    cd CC-attack

## Usage

    python3 cc.py
