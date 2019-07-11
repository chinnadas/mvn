vi /etc/environment

PATH="/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games"

export JAVA_HOME="/usr/lib/jvm/java-1.8.0-openjdk-amd64"

export M2_HOME="/opt/maven"







sudo vi /etc/profile.d/mavenenv.sh

export JAVA_HOME=/usr/lib/jvm/java-1.8.0-openjdk-amd64

export M2_HOME=/opt/maven

export PATH=${M2_HOME}/bin:${PATH}

