lazy_tools
==========

### WHAT

 A tools for backup when you want to change file or path in your linux

 Before:

	cp hosts .hosts_`date '+%Y%m%d%H%M%S'`_zhangsan

 Or:

 	cp -r /etc/hosts /etc/.hosts_`date '+%Y%m%d%H%M%S'`_zhangsan

 Now:

	 you only need a command 'backup'

### NEED
	Python 2.4

### INSTALL and UPDATE

##### install

	git clone https://github.com/cjsund/lazy_tools.git
	python lazy_tools/install/local_install

 Or:

 	curl -sSL https://raw.githubusercontent.com/cjsund/lazy_tools/master/install/online_install | bash

#### update

	git pull
	python lazy_tools/install/local_install update

 Or:

 	curl -sSL https://raw.githubusercontent.com/cjsund/lazy_tools/master/install/online_install | bash -s update



### USE

	[lisi@localhost ~]$ backup hosts
	[lisi@localhost ~]$ ls hosts*
	hosts hosts_20140516120625_lisi
	

### ME

cjsund@126.com
