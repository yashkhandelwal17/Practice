assumption:
Git,Docker,jenkins are installed in the respective system
project:
There are 2 developers dev1 and master who wirte the code and upload it on github. jenkins is assigned 3 jobs 
job1 : it will deploy the code for client on production environment as soon as master push it on github
job2: it will deploy the code for test team(QAT )on testing  environment as soon as dev1 push it on github
job3: it will merge the mater and dev1 on github as soon the QAT team approves the code by dev1

task1:create repo on github
tas2: create files in git and push with branch dev1 and master
task3: enable job1
task 4: enable job2
task 5:enable job 3