FROM elek/bigdata-base 
RUN wget http://xenia.sote.hu/ftp/mirrors/www.apache.org/hadoop/common/hadoop-2.7.3/hadoop-2.7.3.tar.gz && tar zxf hadoop-2.7.3.tar.gz && mv /opt/hadoop-2.7.3 /opt/hadoop && rm hadoop-2.7.3.tar.gz
RUN mv /opt/hadoop/etc/hadoop /opt/hadoop/etc/hadoop.orig && mkdir -p /opt/hadoop/etc/hadoop
