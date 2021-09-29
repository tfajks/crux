This is the folder where you put your data. All files in this folder are available on STS server. Crux copies them to right places:
/shared - on AKS, all files from test_data will be present in /shared folder mounted to all JMeter slaves
/test - on build agent, files from test_data are copied over