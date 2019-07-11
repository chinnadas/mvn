## variableble paths for jenkins
vi /etc/environment

PATH="/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games"

vi /etc/environmet export JAVA_HOME="/usr/lib/jvm/java-1.8.0-openjdk-amd64"

export PATH=$PATH:$JAVA_HOME/bin

export M2_HOME="/usr/share/maven"

export PATH=${M2_HOME}/bin:${PATH}

source /etc/environmet

vi /etc/profile

export JAVA_HOME="/usr/lib/jvm/java-1.8.0-openjdk-amd64"

export PATH=$PATH:$JAVA_HOME/bin

export M2_HOME="/usr/share/maven"

source /etc/profile

for perminently add

vi ~/.bashrc

export JAVA_HOME="/usr/lib/jvm/java-1.8.0-openjdk-amd64"

export PATH=$PATH:$JAVA_HOME/bin

export M2_HOME="/usr/share/maven"

export PATH=${M2_HOME}/bin:${PATH}
