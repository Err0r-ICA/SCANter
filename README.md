# SCANter - Web Security Scanner 🔎

## 📒 Description 📒

* ##### Detect This vulnerabilities
  * <h5>Remote Code Execution</h5>
    <ul><li>Linux</li></ul>
  * <h5>XSS Reflected</h5>
  * <h5>Template Injection</h5>
     <ul>
     <li> Jinja2 </li>
     <li> ERB </li>
     <li> Java </li>
     <li> Twig </li>
     <li> Freemarker </li>
     </ul>
  * <h5>SQl Injection </h5>

## 📸 Screenshot 📸
![Screenshot](https://i.postimg.cc/4ZSdm0Vm/IMG-20200427-162813-866.jpg) 


## OS Support 

- <h5> Kali Linux </h5>
- <h5> Android - Termux </h5>
- <h5> Windows </h5>

## 💿 Installation 💿
### [Linux](https://wikipedia.org/wiki/Linux) [![alt tag](http://icons.iconarchive.com/icons/dakirby309/simply-styled/32/OS-Linux-icon.png)](https://fr.wikipedia.org/wiki/Linux)
* open your terminal 
* enter this command 
   ````
   $ git clone https://github.com/Err0r-ICA/SCANter 
   $ cd SCANter
   $ python3 -m pip install -r requirements.txt
   ````
### Android <img src="https://img.icons8.com/clouds/100/000000/android-os.png">
* Download <a href='https://play.google.com/store/apps/details?id=com.termux&hl=en'>Termux App</a>
* open termux app
* enter this command
````bash
 $ pkg install python -y 
 $ pkg install git -y 
 $ git clone https://github.com/Err0r-ICA/SCANter
 $ cd SCANter
 $ python3 -m pip install -r requirements.txt
````
### Windows <img src="https://img.icons8.com/color/48/000000/windows-10.png">
* Download <a href='https://www.python.org/downloads/windows/'>python3</a> and install it
* open your cmd
* enter this command 
````
$ python3 -m pip install -r requirements.txt
````

## 🧾 Usage 🧾 
````
Options:
  -h, --help          |    Show help message and exit
  --version           |    Show program's version number and exit
  -u URL, --url=URL   |    Target URL (e.g."http://www.target.com/vuln.php?id=1")
  --data=DATA         |    Data string to be sent through POST (e.g. "id=1")
  --list=FILE         |    Get All Urls from List
  --threads           |    Max number of concurrent HTTP(s) requests (default 10)
  --timeout           |    Seconds to wait before timeout connection
  --proxy             |    Start The Connection with http(s) proxy
  --cookies           |    HTTP Cookie header value (e.g. "PHPSESSID=a8d127e..")
  --encode            |    How Many encode the payload (default 1)
  --allow-redirect    |    Allow the main redirect
  --verify            |    Skip HTTPS Cert Error
  --user-agent        |    add custom user-agent
  --scan-headers      |    Try to inject payloads in headers not parameters (user-agent,referrer)
  --skip-headers      |    Skip The Headers scanning processe
  --sleep             |    Sent one request after some Seconds
  --batch             |    Never ask for user input, use the default behavior
  --module            |    add custom module (e.g. "google.py")

````
### ☠️ Input Example ☠️

``` $ python3 ICAscanner -u 'http://localhost/dvwa/vulnerabilities/exec/' --data='ip=localhost&Submit=Submit' --cookies='PHPSESSID=safasf' ```

[![Build-passing](https://img.shields.io/badge/build-passing-red.svg?style=plastic)](https://github.com/Err0r-ICA/SpeedTest/issues) [![Stars](https://img.shields.io/open-vsx/stars/Redhat/Java.svg?style=plastic&color=orange)](https://github.com/Err0r-ICA/SpeedTest/issues) [![Coverage](https://img.shields.io/azure-devops/coverage/Swellaby/Opensource/25?color=yellow&style=plastic)](https://github.com/Err0r-ICA/SpeedTest/issues)

[![Maintainers](https://img.shields.io/badge/mainteiners-HackBoyz-green.svg?style=plastic)](https://github.com/Err0r-ICA/SpeedTest/issues) [![coded](https://img.shields.io/badge/coded%20in-python2.7-mintgreen.svg?style=plastic)](https://github.com/Err0r-ICA/SpeedTest/issues)

[![Status](https://img.shields.io/badge/code%20status-encrypted-cyan.svg?style=plastic)](https://github.com/Err0r-ICA/SpeedTest/issues) [![License](https://img.shields.io/badge/license-MIT-blueviolet.svg?style=plastic)](https://github.com/Err0r-ICA/SpeedTest/issues)

[![Test](https://img.shields.io/badge/tested%20on-Termux,%20Kali%20Linux,%20Ubuntu,%20Parrot%20OS,%20Debian,%20ANDRAX%20Mobile-%23ff69b4.svg?style=plastic)](https://github.com/Err0r-ICA/SpeedTest/issues)
 
