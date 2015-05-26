1 We have to install MySQL username root and password root
2 Create a database db_glensclient
3 Run DatabaseCreation in GlensClientInstaller //One time run,creting the database tables.
4 Run GlensClientService in GlensClient // Start and run for ever

	Example url which you can test in REST CLIENT 1.http://127.0.0.1:7070/kl/GLensClient/requestRealTimeData(GET)
												  2."http://127.0.0.1:7070/kl/GLensClient/login"(POST) 
																{
																"userName" : "Dalmia",
																"password" : "Dalmia"
																}
												  3.http://127.0.0.1:7070/kl/GLensClient/requestMatrixdata (POST)
																{'
																"dataQuality":"Raw",
																"parameter":"Emission.CEMENT_MILL.analyser_8.parameter_3",
																"fromDate":"02-05-2015",
																"toDate":"25-05-2015"
																}
																
																
																
The attachment contains GlensClientInstaller,GlensClient,sample database and UI

