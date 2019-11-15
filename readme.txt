This is my fixsssed for DevOpsSchool.com....Fix for Taskggggg HON-1
For any questions - Please email me at DevOps@RajeshKumar.gxyz/
# this isddd a fix og sdfljflld fjldsfjdsjfkdl;sdasdasdasd
# ========================NEXUS==============================

adding new line

===============ARTIFACTORY=================
<distributionManagement>
	<repository>
		<id>rajesh</id1>
		<name>Internal Releases</name>
		<url>http://13.127.94.210:8081/artifactory/list/rajesh-release/</url>
	</repository>
 
	<snapshotRepository>
		<id>rajesh</id>
		<name>Internal Releases</name>
		<url>http://13.127.94.210:8081/artifactory/list/rajesh-snapshot/</url>
	</snapshotRepository>

</distributionManagement>

=====================SETTING.XML=================================
   <server>
		<id>rajesh</id>
		<username>rajesh-user</username>
		<password>rajesh-user123</password>
</server>

=======================Setting.xml with Artifactory Setup======================
<mirror>
      <id>central</id>
      <name>Maven Repository Manager running on repo.mycompany.com</name>
      <url>http://13.127.94.210:8081/artifactory/list/group/</url>
      <mirrorOf>*</mirrorOf>
    </mirror>
    
    

