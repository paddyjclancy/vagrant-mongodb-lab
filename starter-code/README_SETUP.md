# User Installation


1) Clone repo
	- Provides you with a copy of provisioning-starter-code
2) Open <git bash>
3) $ cd /starter-code
4) $ vagrant up
	- Starts up VM server (will take some time)
	- Check it is present / running in VirtualBox Manager
	- $ vagrant ssh to enter (not necessity here)
5) $ cd /tests
6) $ rake spec
	- To initialise and perform set tests
	- EXPECTED: 4 EXAMPLES, 0 FAILURES