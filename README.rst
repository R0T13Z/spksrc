remark:

dpkg --add-architecture i386

apt-get update

apt install autogen automake bc bison build-essential check cmake curl cython debootstrap expect flex g++-multilib gettext git gperf imagemagick intltool libbz2-dev libc6-i386 libcppunit-dev libffi-dev libgc-dev libgmp3-dev libltdl-dev libmount-dev libncurses-dev libpcre3-dev libssl-dev libtool libunistring-dev lzip mercurial ncurses-dev php pkg-config python3 python3-distutils scons subversion swig unzip xmlto zlib1g-dev

apt-get install python-pip libpcsclite-dev

pip install -U setuptools pip wheel httpie

git clone -b r0t13z https://github.com/R0T13Z/spksrc.git
cd spksrc/

make setup

cd spk/oscam

make arch-evansport

make arch-apollolake
