javac -cp %MPJ_HOME%/lib/mpj.jar DistributedSum.java - Windows

mpjrun -np 4 DistributedSum

//Linux
export MPJ_HOME=mpj/
export PATH="$MPJ_HOME/bin:$PATH"

javac -cp %MPJ_HOME%/lib/mpj.jar DistributedSum.java
mpjrun.sh -np 4 DistributedSum