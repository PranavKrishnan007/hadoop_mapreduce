![image](https://github.com/PranavKrishnan007/hadoop_mapreduce/assets/89575829/0bea875a-2cb3-4091-afb0-c0230b52cf18)
hadoop jar $HADOOP_HOME/share/hadoop/tools/lib/hadoop-streaming-3.3.6.jar     -file mapreduce.py -mapper "python3 mapreduce.py mapper"     -reducer "python3 mapreduce.py reducer"     -input /input/data.csv -output /output

hadoop fs -mkdir /input

hadoop fs -put data.csv /input/data.csv

![image](https://github.com/PranavKrishnan007/hadoop_mapreduce/assets/89575829/15845a3f-25fa-4f13-b931-c502f57ff007)

![image](https://github.com/PranavKrishnan007/hadoop_mapreduce/assets/89575829/13040f35-6a25-44fd-a846-3e0afc0d12c6)
![image](https://github.com/PranavKrishnan007/hadoop_mapreduce/assets/89575829/8af7bd36-cade-49a0-9450-bce06031d407)
![image](https://github.com/PranavKrishnan007/hadoop_mapreduce/assets/89575829/61a43614-cf63-4a8c-a6d2-164e963d336e)
