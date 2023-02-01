# ip-routing-table-exercise

A routing table is a database that stores the routes, and in case of IP routing, the routes are IP addresses.
An IP routing table works by directing network packets from one network to another based on their destination IP addresses.
The routing table is created and maintained by routing protocols, such as OSPF, BGP, and others.

In Scala, how would you implement a program that dynamically updates the IP routing table, given a set of input IP addresses and network masks, and outputs the next hop IP address for each destination IP address?
You can assume that the program will receive updates to the input IP addresses and network masks in real-time, and that the program should respond to these updates by updating the routing table accordingly.

## Sample Code
```scala
object IpRoutingTable {
  case class Route(destinationIp: String, networkMask: String, nextHopIp: String)
  
  def addRoute(destinationIp: String, networkMask: String, nextHopId: String): Unit = ???
  
  def updateRoute(destinationIp: String, networkMask: String, nextHopIp: String): Unit = ???
  
  def removeRoute(destinationIp: String, networkMask: String): Unit = ???
  
  def getNextHopIp(destinationIp: String): Option[String] = ???
}
```

Here is a test case for the Scala program:

Test Case 1:

Input:

- Routing Table: 
  - IP address: TBD
