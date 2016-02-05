Jenkins with installed maven and oracle instantclient for integration test purposes

sudo docker run \
-di -p 8081:8080 -p 50000:50000 \
-v /home/chris/.m2/settings.xml:/etc/maven/settings.xml \
-v /home/chris/jenkins_home:/var/jenkins_home \
chrisortiz333/meta_jenkins
