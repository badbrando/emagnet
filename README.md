# EMAGNET v3.4.1

#### Important Notice: Avoid being banned by set TIME for 200 seconds or higher in emagnet.conf.

#### _Nr1.nu is from now up and running again as expected, we are now using nr1.nu for whois our IP again, whois your IP unlimited times without any logs saved or stored. Also my mail server is up and running again so now you can send e-mail to wuseman@nr1.nu again - Sorry for the downtime_ // Regards


## <p align="center">![Screenshot](https://i.ibb.co/3B5GS6X/68747470733a2f2f6e72312e6e752f656d61676e65742f70726576696577732f656d61676e65745f6f6c646d6f76692e676966.gif)

| Current Version    | News                            | Tested On                          |
| :----------------- | :-------------------------------- | :----------------------------------|
| `3.4.1`            |  Support for SSH Tunnel/Socks5 proxy    | Linux/MacOS/OpenWRT/Windows/Android                               |
| `3.4`              |  Full support on android devices, no root required    | Linux/MacOS/OpenWRT/Windows/Android                               |

<a href="https://github.com/wuseman/EMAGNET"><img src="https://img.shields.io/github/languages/top/wuseman/emagnet.svg?color=magenta&label=Bash%2FShell"></a><a href="https://github.com/wuseman/EMAGNET/issues?q=is%3Aissue+is%3Aclosed">
<img src="https://img.shields.io/github/issues-closed/wuseman/emagnet.svg?color=light&label=Closed%20Issues"></a>
 <a href="https://github.com/wuseman/EMAGNET/issues"><img src="https://img.shields.io/github/issues-raw/wuseman/emagnet.svg?color=orange&label=Open%20Issues"></a><img src="https://img.shields.io/github/last-commit/wuseman/emagnet.svg?color=darkmagenta&label=Latest%20Commit"><a href="https://twitter.com/wuseman1">
 <img src="https://img.shields.io/website/https/nr1.nu.svg?down_color=darkred&down_message=DOWN&label=Nr1.nu%2Femagnet&up_message=UP"><img src="https://img.shields.io/github/license/wuseman/emagnet.svg?color=blue&label=License"></a></a></a>
</a>
</p>

Emagnet is a very powerful tool for it's purpose wich is to capture  email addresses and passwords from leaked databases uploaded on pastebin. It's almost impossible to find leaked passwords when they are out of list on pastebin.com. Either they have been deleted by pastebin's techs or the uploads is just one in the crowd. To be honest it's easier to find a needle in a haystack then find outdated uploads on pastebin with the data we want to collect. 

#### BBC NEWS: ["Pastebin: Running the site where hackers publicise their attacks"](https://www.bbc.com/news/technology-17524822) 

- Emagnet is No.1 tool for fetch these leaks from pastebin

### A sample from 2019-11-13 when running emagnet with brute force mode on for spotify:
* The result is amazing, it have never ever been so easy to hack million of peoples accounts before!
* Run emagnet on your android device, just put your android device in your pocket and emagnet will hack the accounts for you - This preview is for spotify, but emagnet has support for more protocols and it will be more supported protocols in next upgrade.

### Sit back and relax and Emagnet will do the rest, watch the video below, this is for real!

![Screenshot](http://94.242.57.127/emagnet/previews/emagnet-latest.gif)

### ... So how does this work? See the video below exactly line by line how it works: 

* Left side is how you see things - Right side is what actually going on:

![Screenshot](.preview/emagnet2-debug.gif)

### Getting Started:

    git clone https://github.com/wuseman/emagnet
    cd emagnet
    chmod +x emagnet*
    ./emagnet --emagnet
   
    That's it, have phun!
    
### A special not for v3.4.1 that has been added is how many threads we using during download:

#### From now we using max args for downloading files AS FAST AS POSSIBLE, you can figure out how many threads you are using while downloading instead of how many cores you are using, see below:

    xargs --show-limits -s 1 2>&1|grep -i "parallelism"|awk '{print $8}'

You really don't need all these threads since we downloading 49 files max all the time, a good recommendation is to take the value from above command devided with 2, so if you have an old cpu you can do, please remember this is not threads/core its how many threads a single core is used so don't be confused about htis. 

    echo $(xargs --show-limits -s 1 2>&1|grep -i "parallelism"|awk '{print $8}') / 2|bc
    
Instead, but it is really needed on very slow CPUS only, otherwise you don't have to care about htis.

Things will go back to normal on wednesday again, if you already have been used emagnet for a while you don't have to care, this is a notice for new users only. 

### Notice 2: 

If you run emagnet --bruteforce ssh and do not see how many ip addresses that was found it means there was no ipv4 addresses found, this is not a bug or miss from me. If there is any ipv4 addresses found then you will see how many ipv4 addresses you found, then you gonna portscan them and last you will see how many of all the ipv4 addresses found has port 22 open and then it will begin the bruteforce and using the credenticals from emgnet.conf, default is root:root. 


### Wiki Sections:

- [About](https://github.com/wuseman/EMAGNET/wiki/ABOUT) - 
_How everything started._
- [Previews](https://github.com/wuseman/EMAGNET/wiki/PREVIEWS) - 
_Previews can be found here._
- [Configurations-&-Installation](https://github.com/wuseman/EMAGNET/wiki/Configurations-&-Installation) - 
_Get started with spotify brute forcing - How emagnet will work with your openvpn files._
- [Regex - Tips For Search](https://github.com/wuseman/EMAGNET/wiki/Searching-&-Regex) - How To Find your facebook credenticals, if it has been leaked._

### System Requirements

- Bash     - Find more info about _bash_ [here](https://www.gnu.org/software/bash/)
- Wget     - Find more info about _wget_ [here](https://www.gnu.org/software/wget/)
- Curl     - Find more info about _curl_ [here](https://github.com/curl/curl)

# Busted!

If you have scraped pastebin to often and if you have been banned for real you will end up here!

![Screenshot](https://i.imgur.com/Tz1R3ts.png)

# Reality

#### Below you can see an image that describes the reality, emagnet makes it easier than ever to get hold of leaked accounts. Emagnet does not violate any country's laws as long as you brute forcing your own accounts only (this is up to every user to decide), all we do is retrieve data from pastebin, if you have opinions or questions about stuff pastebin hosting you will find all info on https://pastebin.com/contact to get in touch - I wont reply questions about this in my mailbox, all kind of messages that contains such info will be wiped, just for your notice.

#### Please do not waste my time with _nonsence_, thanks.

## <p align="center">![Screenshot](https://1.bp.blogspot.com/-lsj7-5npl1w/XWsdVQA6lrI/AAAAAAAAQNM/sZ0HIH5PtjoxRAVK0RxTaHCizqi4pb7jwCLcBGAs/s1600/EMAGNET_10.png)
 
## Changelog

[Versions changelog](CHANGELOG.md).

## Authors: 

* **wuseman <wuseman@nr1.nu\>** 

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE.md](LICENSE.md) file for details

### Contact

  If you have problems, questions, ideas or suggestions please contact me on *_wuseman@nr1.nu_  - For faster contact visit freenode irc network or the webchat and type '/msg wuseman hi!' in the input bar and I will reply you ASAP I will see the message.
  
  Enter Freenodes network via your own client 'chat.freenode.com:+6697 or use their new web client [here](https://webchat.freenode.net/)

### Notice

Attacking different kinds of accounts via emagnet that you have not been granted or allowed to attack is strictly prohibited and it breaks the law. The punishment is hard and you can even get into prison in some countries just for trying to attack for intrusion. With this said, it's *important* that all users is aware of this and when you have cloned or downloaded it's fully up to every user to take responsibility over their own actions. wuseman cannot be held responsible for the actions of any user, all users using Emagnet on their own responsibility. 

Developer: "All my previews where a brute force attack has been done is under controlling forms with 100% fully permissions by the owners. If you have any questions about this then you are welcome to contact me or the owner."

### Haters Gonna Hate

If you are one of these who dislikes _EMAGNET_ and believe the program has been developed for a reason that would break the law then I am not interested in taking part of your opinions, keep them for _yourself_! Emagnet does **NOT** leak any data at all either to the developer(s) or anyone else. No statistics at all to track any user so if you want to contact me for ask who it might was who downloaded emagnet a specific date is completely useless since i really have no idea, and to be honest I don't care.

Feel free to read the history about emagnet [here](https://github.com/wuseman/EMAGNET/wiki/About) and how everything started about this project.

#### Development of emagnet is active and is updated frequently, please use the latest version if you report issues/bugs.

# Greetings: 

_m1st_ that deliver legit leaks for us daily.

And to all ppl that is trying to sell public leaks and steal the real hackers job, f*ck you! This is one reason why I started this project, I hope this project will get widely spreaded so you will earn 0.00$ on your re-edited malware shit!

Cheers!

### Feel free to send donations if you want to support the development of the emagnet

      BTC Address: 1Cf3Xuc5sCu9H4VL2jeruELDDNkmk1u7Sx

### Emagnet is a private project since 2015 and was released in June @ 2018, to be continued. 



