# Mouse_stuck_fix_issues_for_ubuntu
I had an issue with the mouse pointer in Ubuntu that the pointer always stuck to the bottom of screen while login,so
I could take out  solution to this.
Version : Ubuntu 18.04.3 
know the version of ubuntu lsb_release -a (on terminal)
1. while the boot process if your pc has a dual boot ,you will get many options for operating systems
For mine i get
ubuntu 
advance settings for ubuntu 
windows 10 on dev/sal
2. get on to advance settings and to the fourth option in advance settings
3. After loading you will get some options under recovery menu
select grub and press enter, this will update your /etc/default/grub settings.
4. After this resume to the normal booting process.


If this does not work simply load ubuntu from the third option of advance settings.This will work definitely.
Thankyou.
