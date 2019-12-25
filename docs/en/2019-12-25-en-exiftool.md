# How to install Exiftool

### On Ubuntu

You can install ExifTool on Ubuntu using the apt utility.

`# sudo apt install libimage-exiftool-perl`

### From Source

You can compile and install ExifTool from the source on any Linux distro (including CentOS)

__[!IMPORTANT]__ Source: https://exiftool.org/ and latest version "Image-ExifTool-##.##.tar.gz" - `(let's: folder.tar.gz)`

`$ wget -c folder.tar.gz`

`$ tar xvf folder.tar.gz`

`$ cd folder`


You can run ExifTool by running ./exiftool in the ExifTool directory or proceed to the next step if you want to install it system-wide. You must have Perl installed on your Linux box before compiling.

`# perl Makefile.PL`

`# make`

`# make test`

`# make install`


###### Sources: 
1. :uk: https://linoxide.com/linux-how-to/install-use-exiftool-linux-ubuntu-centos/ 
2. :ru: https://andreyex.ru/operacionnaya-sistema-linux/kak-ustanovit-i-ispolzovat-exiftool-na-linux 