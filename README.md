the JOpenShowVar Project
========================
https://github.com/aauc-mechlab/jopenshowvar


the JOpenShowVarCMD
========================
http://davidrobot.com/2014/08/command_line_of_jopenshowvar.html


Download kukavaproxy for KRC4
=============================
the kukavaproxy you can download it below
http://amo.hials.no/mechatronics/index.php/research/robotic-arms
https://github.com/aauc-mechlab/jopenshowvar


Config kukavaproxy on the KRC4
=============================
KUKAVARPROXY must firstly be started on the KUKA(copy paste the folder to somewhere in the WinXP 
environment -> run KUKAVARPROXY.exe) Port 7000 has to set open from the SmartPad: Start-up -> 
Network configuration -> NAT -> Add port -> Port number 7000 and Permitted protocols: tcp/udp

In order to successfully establish an connection to the server. Your IP must be assigned a static IP
in the same subrange as the one defined in the the SmartPads network configuration.


How to use the jar file "JOpenShowVarCMD.jar" :
================================================

1. instal JAVA Runtime JRE7 or JRE8
2. run java -jar JOpenShowVarCMD.jar IP_address Var [SetVarValue]
3. read value by typing like this :  java -jar JOpenShowVarCMD.jar 192.168.40.128 $OV_PRO
4. write value by typing like this :  java -jar JOpenShowVarCMD.jar 192.168.40.128 $OV_PRO 80


How to use the Windows bat script "KukaVar.bat":
================================================

1. modify the path of your's JOpenShowVarCMD.jar in the KukaVar.bat
2. copy KukaVar.bat to the Windows dirctory 
3. run CMD
4. read value by typing like this :  kukavar 192.168.40.128 $OV_PRO
5. write value by typing like this :  kukavar 192.168.40.128 $OV_PRO 80