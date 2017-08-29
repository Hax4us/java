#!/system/bin/sh
#export LD_LIBRARY_PATH=/data/data/per.pqy.apktool/apktool/lix
#in some targets,LD_PRELOAD will cause a error.
export LD_PRELOAD=
export LD_LIBRARY_PATH=/data/data/com.termux/files/home/java/openjdk/lib/arm:$LD_LIBRARY_PATH
#umask 000
#cd /data/data/per.pqy.apktool/apktool
#echo $$ > pid
exec /data/data/com.termux/files/home/java/openjdk/bin/java -Xmx1024m "$@"
