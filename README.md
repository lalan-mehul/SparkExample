Run $ mvn package to create the jar file
Execute the below command to run the program: /Users/mehul/Downloads/spark-3.5.1-bin-hadoop3/bin/spark-submit \
  --class "SimpleApp" \
  --master "local[4]" \
  target/SparkExample-1.0-SNAPSHOT.jar
