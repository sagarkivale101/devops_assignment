1. docker-compose up

2. docker-compose down

The Selenium Grid is a testing tool which allows us to run our tests on different machines against different browsers. 
Selenium Grid allows us to run tests in parallel on multiple machines, and to manage different browser versions and browser configurations centrally. two main elements of selenium grid are 'HUB' and 'Node'.

Hub:
In Selenium Grid, the hub is a computer which is the central point where we can load our tests into. Hub also acts as a server because of which it acts as a central point to control the network of Test machines. The Selenium Grid has only one hub and it is the master of the network.

Node:
n Selenium Grid, a node is referred to a Test Machine which opts to connect with the Hub. This test machine will be used by Hub to run tests on. A Grid network can have multiple nodes. A node is supposed to have different platforms i.e. different operating system and browsers.	

