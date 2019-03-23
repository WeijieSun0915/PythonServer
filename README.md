<h1 align="center">Python Web Server</h1>
  
##### Project Overview:  
&ensp;&ensp;A simple HTTP Web Server uses Python language.

&ensp;&ensp;This HTTP Web Server uses basic Python socket programming knowledge. I implemented it by studying those knowledge. It is able to operate at a specified port at local network. It is able to server up to 5 clients at the same time. Currently, it is single threaded. It is possible to change it to multi-threaded to enhance the performance. It can respond basic HTTP requests including "GET", "HEAD", and "POST". It can respond to client with simple HTTP errors including "200", "400", "404", and "505". It is able to detect requested and incoming file type to fullfill the clients' needs. By default, it servers the "index.html" from the root of "site" folder under the same directory. Any further request will be proccessed by the program to determine whether can be fullfilled.

##### Operating Environment & Usage:
&ensp;&ensp;Initially, it was coded in Pyhton version 2.7.9 under OSX. I am not sure if it is compatible under Python 3 or newer or other OS. This project is for acedamic study purpose only. It is not a commercial project.

##### Further Analysis:
&ensp;&ensp;The server name and port number can be edited by the user. The socket buffer size and connection experition time can be edited by user.When te program is runing, there will be detailed output of events.
  
##### SFU Gitlab Link:
&ensp;&ensp;https://csil-git1.cs.surrey.sfu.ca/kla121/Python-server.git
