# apache-tomcat

[Apache Tomcat](http://tomcat.apache.org)

## JDK

```bash
export JAVA_HOME="`/usr/libexec/java_home -v '1.8*'`"

java -version
javac -version
```

## Install

```bash
sudo mv ~/Downloads/apache-tomcat-7.0.92 /usr/local
sudo rm -f /Library/Tomcat
sudo ln -s /usr/local/apache-tomcat-7.0.92 /Library/Tomcat
sudo chown -R <username> /Library/Tomcat
sudo chmod +x /Library/Tomcat/bin/*.sh
```

## Run

```bash
/Library/Tomcat/bin/startup.sh
/Library/Tomcat/bin/shutdown.sh
```

[`localhost:8080`](http://localhost:8080)
