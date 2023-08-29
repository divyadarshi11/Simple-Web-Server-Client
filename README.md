# Simple-Web-Server-Client
#Computer Networks CSE 5344 
#Project 1-Simple Web Server & Client



******PROJECT DESCRIPTION*******
A) You will be developing a multi-threaded Web server that interacts with any standard Web Clients ( You may use any web browser of your choice to test the functionality however you
should also submit a client as given in (B) below ). The Web server and Web client communicate using a text-based protocol called HTTP (Hypertext Transfer Protocol).

(B) Build a single-threaded Web Client on your own that interacts with your Web Server, and downloads a file from the server.

(C) Display the essential connection parameters of connection for both the Web client (on the server side) and for the Web Server (on the client side).

********Packages required to run the code************
import java.io.*;
import java.net.*;
import java.util.StringTokenizer;
import java.io.BufferedReader;
import java.io.IOException;
import java.io.InputStreamReader;
import java.io.PrintStream;
import java.net.Socket;
import java.net.URL;
import java.util.Scanner;

#PROGRAMMING LANGAUGE- JAVA

**********Detailed Instructions to Execute Code***********
1)Download the Eclipse IDE

2)Build the project Eclipse IDE and add the source code files.

3)Compile the ServerD class first and run the ServerD class.
  #OUTPUT - The TCP server is Created on the PORT Number.

4)Then Compile the ClientD class and run the ServerD class. 
  #OUTPUT - Established connection on ServerD with respect to ClientD.

5)Enter the file name in the Client Java program Console that we want to search in the server. (Files should be stored in the project directory.)
   For eg, **FILENAME = Textfile.txt **
   #OUTPUT - #The server can serve multiple requests at the same time.
             #The client sends/receives messages to/from the server correctly.
             #The client extracts the status and content of messages from the server correctly.
             #Extracting and displaying connection parameters.
             #Display Round Trip Time value 



********REFERENCE**********
https://youtu.be/-dSXvLAwXO0
https://www.javaworld.com/article/2077322/core-java/core-java-sockets-programming-in-java-a-tutorial.html
