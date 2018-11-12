This application reads a Ignite Cache to get the key value pair and then uses 


1.Install Ignite 2.6.0 and build it with maven.

2.Start Ignite by $IGNITE_HOME/bin/ignite.sh start example-ignite.xml

3.My custom example-ignite.xml is already kept in conf folder.Copy the entire and point to example that to start Ignite.

4.Clone the repository igniteQueryWordCount

5.cd igniteQueryWordCount

6.Build the application

mvn clean install

7.Run the module to stream data from a text book to Ignite.

8.Run the application :

java -jar target/QueryWords-1.0-SNAPSHOT.jar

You will be able to see the top 10 words having max occurences and the count of their occurences. 
