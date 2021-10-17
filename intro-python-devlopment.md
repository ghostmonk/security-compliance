# Using python 3.7

Using Centos 7
- `yum groupinstall -y "development tools"`
- `sudo -i`
- `yum install -y libffi-devel zlib-devel bzip2-devel openssl-devel ncurses-devel sqlite-devel readline-devel tk-devel gdbm-devel db4-devel libpcap-devel xz-devel xpat-devel`
- `cd /usr/src/`
- `wget http://python.org/ftp/python/3.7.2/Python-3.7.2.tar.xz`
- `tar xf Python-3.7.2.tar.xz`
- `cd Pythong-3.7.2`
- `./configure --make-optimizations`
- `make altinstall` #this put it into the path as python3.7
- `vim /etc/sudoers`
- make sure `/usr/local/bin` is available on `secure_path`
- `sudo yum update`
- `sudo yum install -y vim-enhanced`
- `git.config --global user.name + user.email`
- `curl https://raw.githubusercontent.com/linuxacademy/content-infor-to-python-development/master/helpers/bashrc -o ~/.bashrc`
- vimrc too
- `exec $SHELL`
- Read Evaluate Print Loop (REPL)
- Interestingly... and I did not know this. adding `#!/usr/bin/env python3.7` to the top of a python file... plus doing `chmod u+x file.py` will allow you to execute it like a normal command.
- creating executables in a `/home/usr/bin` file is a good way to go
- next are a series of videos talking about built in data types
- interesting point... docstrings take up space. There are no multi-line comments in python
- surprise... `10 // 3` gives you a floor
- `3 ** 3` is 3 to the power of 3
- `"ha" * 4` is hahahaha
- `list[0:100:2]` the third variable is the step variable and in this case means every second value
- `list[::-1]` this the way to reverse a list
- `print("%s %s" % ("one", "two"))` will print "one two"

