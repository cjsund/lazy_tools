lazy_tools
==========

### WHAT

 A tools for backup when you want to change file or path

 Before:

	cp hosts hosts_`date '+%Y%m%d%H%M%S'`_zhangsan

 Or:

 	cp -r /etc/hosts /etc/hosts_`date '+%Y%m%d%H%M%S'`_zhangsan

 Now:

	 you only need a order 'backup'

### INSTALL

	git clone https://github.com/cjsund/lazy_tools.git
	python lazy_tools/install/local_install

### USE

	[lisi@localhost ~]$ backup hosts
	[lisi@localhost ~]$ ls hosts*
	hosts hosts_20140516120625_lisi
	

### ME

cjsund@126.com