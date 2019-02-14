Unionbank blockchain training

Environment: 
Host: Windows 8.1 
RAM: 4GB
Virtualization software: VirtualBox 5.2.22
Guest: Ubuntu 16.04.5 LTS (64-bit), 2GB RAM / 40GB Storage
--------------------
Prerequisites:
	* GoLang
	* Postman

Instructions:
1. Clone this repository. https://github.com/karltheodore/fabric-samples
2. Open fabric-samples/fabcar in Terminal.
3. Input the following scripts: 
	./openScm.sh
	node enrollAdmin.sh
	node registerUser.sh
	node rSupplier1.sh
	node rOEM.sh
4. For testing, input:
	node app_scm.sh  		//Port 3000.
	node appSupplier1.sh 		//Port 3001.
  	node appOEM.sh 			//Port3002.
   Then test the functions on Postman

