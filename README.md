Use cygwin package management to get gcc step
1. download apt-cyg from
https://raw.githubusercontent.com/transcode-open/apt-cyg/master/apt-cyg

#chmod +x apt-cyg
#mv apt-cyg /usr/local/bin


2. modify this file with valid cygwin mirror site:
Mirror site:
https://cygwin.com/mirrors.html
File path:
~cygwin\etc\setup\setup.rc

---------------------------------------------------------------modify content start
last-mirror
	http://ftp.cse.yzu.edu.tw/pub/cygwin
---------------------------------------------------------------modify content end

3. get packages

#apt-cyg update
#apt-cyg install make
#apt-cyg install diffutils
#apt-cyg install cmake
#apt-cyg install gcc-core
#apt-cyg install xorg-x11-devel
#apt-cyg install gcc-g++
#apt-cyg install gcc
#apt-cyg install gcc-g++
#apt-cyg install vim

	
REF:
http://www.saltycrane.com/blog/2007/11/cygwin-install-tips/
