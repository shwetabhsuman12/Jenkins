# Jenkins


PREREQUISITE(Ref 1):
            Java installation

INSTALLATION(Ref 1) :
    Installation steps on Linux:
            1)  wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo apt-key add -
            2) sudo sh -c 'echo deb https://pkg.jenkins.io/debian-stable binary/ > \
    /etc/apt/sources.list.d/jenkins.list'
            3) sudo apt-get update
            4) sudo apt-get install jenkins

POST INSTALLATION(Ref 1):
    post installation do :  sudo systemctl start jenkins
    1) Login to http://localhost:8080   ( default port for jenkins if not changed in jenkins)

    2) Used Install suggested plugin to start with .If there is any additional plugins addition/deletion,
 go to Manage Jenkins -> Manage Plugins

   
    Next page  will be :
     1) Creating first admin user:
                Provide your details  to create your first admin
     2) It asks for jenkins url configurationw which I kept it same to localhost:8080 as it says by
        default

PIPELINE:
   Uses & Benefits:
   Basic Terminology:
        Nodes,stage,step,controller,agent,executor
   Plugin Prerequisite: Pipeline . It will install the other related artifacts.
                        Install pipeline plugins as suggested in [Ref 2]

REFERENCES:
 1) https://www.jenkins.io/doc/book/installing/linux/
 2) https://www.jenkins.io/pipeline/getting-started-pipelines/
        




