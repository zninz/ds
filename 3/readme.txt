export MPJ_HOME=/home/ubuntu/Downloads/mpj-v0_44
export PATH=$MPJ_HOME/bin:$PATH
javac -cp $MPJ_HOME/lib/mpj.jar ArrSum.java
$MPJ_HOME/bin/mpjrun.sh -np 4 ArrSum
