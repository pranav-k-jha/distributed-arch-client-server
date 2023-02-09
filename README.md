# distributed-arch-client-server

This project involves implementing a client/server based distributed architecture using a free tier cloud virtual machine. The server will be running on Jetty and will handle resource open API design for an audio item that includes properties such as Artist Name, Track Title, and Number of Copies Sold. The open APIs for GET and POST methods will be programmed using a Java program called Audio.java. 

The server side will use a Servlet to represent the audio resource and maintain a sum of the total number of copies sold for all the audio items in the database. The server will be multithreaded with a thread pool execution. The to-do also involves programming a test class to simulate concurrent requests from multiple clients, recording the round-trip time, and plotting a line chart to represent the time taken for each request versus the number of clients.
