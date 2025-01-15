https://basecampcs.sharepoint.com/sites/InternalRevenueServiceIRS-JETCS/Shared%20Documents/Forms/AllItems.aspx?id=%2Fsites%2FInternalRevenueServiceIRS%2DJETCS%2FShared%20Documents%2FJETCS%2FJIOS%20Source%20Code&viewid=0e596891%2Dce36%2D417c%2D8c2a%2D745a98b4592a

https://irsgov-my.sharepoint.com/personal/pc1rb_ds_irsnet_gov/_layouts/15/onedrive.aspx?e=5%3Ac7b4d0d9d0384de7b835b61efc1a267b&sharingv2=true&fromShare=true&CID=19fee150%2D9458%2D4331%2Db436%2Dbcb06ab0aadb&id=%2Fpersonal%2Fpc1rb%5Fds%5Firsnet%5Fgov%2FDocuments%2FShare&FolderCTID=0x012000AF8709792001EE4C98BE96BA0F17595B&view=0

testrunner.bat -s"TestSuiteName" -c"TestCaseName" -PpropertyName=propertyValue -r -j -f"outputFolderPath" projectFilePath

testrunner.bat -a -f"C:\SoapUI\Responses" -s"MyTestSuite" -c"MyTestCase" C:\Path\To\MyProject.xml

Running SoapUI TestRunner for [REST Project 1]
directory: C:\Program Files\SmartBear\SoapUI-5.7.2\bin\.
command: cmd.exe /C testrunner.bat -s"https://c-ecm-dev.apps.ecpdevtest.tcc.irs.gov TestSuite" -c"VarianceAnalysis TestCase" C:\Users\w18rb\Documents\REST-Project-1-soapui-project.xml
OpenJDK 64-Bit Server VM warning: Option --illegal-access is deprecated and will be removed in a future release.
SoapUI 5.7.2 TestCase Runner
Configuring log4j from [C:\Program Files\SmartBear\SoapUI-5.7.2\bin\soapui-log4j.xml]
15:16:31,245 INFO  [DefaultSoapUICore] initialized soapui-settings from [C:\Users\w18rb\soapui-settings.xml]
15:16:31,360 INFO  [HttpClientSupport] Initializing KeyStore
15:16:33,617 INFO  [PluginManager] 0 plugins loaded in 1 ms
15:16:33,617 INFO  [DefaultSoapUICore] All plugins loaded
15:16:34,243 INFO  [WsdlProject] Loaded project from [file:/C:/Users/w18rb/Documents/REST-Project-1-soapui-project.xml]
15:16:34,249 INFO  [SoapUITestCaseRunner] Running SoapUI tests in project [REST Project 1]
15:16:34,250 ERROR [SoapUITestCaseRunner] java.lang.Exception: TestSuite with name [https://c-ecm-dev.apps.ecpdevtest.tcc.irs.gov TestSuite] is missing in Project [REST Project 1]
15:16:34,250 ERROR [SoapUI] An error occurred [TestSuite with name [https://c-ecm-dev.apps.ecpdevtest.tcc.irs.gov TestSuite] is missing in Project [REST Project 1]], see error log for details
java.lang.Exception: TestSuite with name [https://c-ecm-dev.apps.ecpdevtest.tcc.irs.gov TestSuite] is missing in Project [REST Project 1]
	at com.eviware.soapui.tools.SoapUITestCaseRunner.runRunner(SoapUITestCaseRunner.java:372)
	at com.eviware.soapui.tools.AbstractSoapUIRunner.run(AbstractSoapUIRunner.java:228)
	at com.eviware.soapui.tools.AbstractSoapUIRunner.run(AbstractSoapUIRunner.java:148)
	at com.eviware.soapui.tools.AbstractSoapUIRunner.runFromCommandLine(AbstractSoapUIRunner.java:116)
	at com.eviware.soapui.tools.SoapUITestCaseRunner.main(SoapUITestCaseRunner.java:122)




# DockerHelloWorld


This is sample project for Hello World which contains docker file to test on docker container.
It uses java 11.


![image](https://github.com/chaitalishah/DockerHelloWorld/assets/13629726/22b82e57-2d32-4175-9e9e-3a03a6963357)


**Add below pom.xml**
![image](https://github.com/chaitalishah/DockerHelloWorld/assets/13629726/78df2cef-29be-409b-9064-865570fcea9b)


**Sample Docker File for maven project.**
![image](https://github.com/chaitalishah/DockerHelloWorld/assets/13629726/50d35bd9-e3da-4bb0-9d55-fd7c91f22262)

