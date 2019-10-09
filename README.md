# Cassandra-Java-Application
Java console application to connect to Cassandra Bigdata and make insert, update, delete operations

1. Create a new Eclipse Java project in Cassandra installed virtual machine
2. Add the jar files in build path
3. Create a New class file and copy the Java code into it
4. Add import statements 
import com.datastax.driver.core.*;
import org.slf4j.Logger;
import org.slf4j.LoggerFactory;
5. Compile the program and make sure there are no errors
6. Import dse-5.0.3.tar.gz and untar it with tar -xf filename
7. Move to /bin folder and start cassandra with the command ./cassandra
8. Check the status ./dsetool status
9. Open cqlsh and create keyspace and table
10. Run the java program to read and write to the same table
