# Fuel CMS 1.4.1 - Remote Code Execution

FUEL CMS 1.4.1 allows PHP Code Evaluation via the pages/select/ filter
parameter or the preview/ data parameter. This can lead to Pre-Auth Remote
Code Execution.


# Install
```bash
git clone https://github.com/Trushal2004/CVE-2018-16763.git
cd CVE-2018-16763/
python3 -m pip install -r requirements.txt
chmod +x exploit.py
./exploit.py
```


# Help
```
$./exploit.py --help
usage: python3 ./exploit.py -u <url>

fuel cms fuel CMS 1.4.1 - Remote Code Execution Exploit

optional arguments:
  -h, --help         show this help message and exit
  -v, --version      show the version of exploit
  -u url, --url url  Enter the url

EXAMPLE - python3 ./exploit.py -u http://10.10.21.74
 ```                   

# Demo

![image](https://user-images.githubusercontent.com/57517785/141612862-ebb4cf83-9a68-4311-929c-c1c9382d94af.png)

![image](https://user-images.githubusercontent.com/57517785/141612888-cfaab933-7522-494d-b8df-51f07dcff6e9.png)






# Exploit DB
https://www.exploit-db.com/exploits/50477
