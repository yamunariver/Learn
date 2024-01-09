# Learn


packets should take over a network to reach their destination

        Routers store routes to all of their known destinations in a
        routing table

        when routers receive packets, they look in the routing table 
        to find the best route to forward that packet

There are main routing methods(methods that routers use to learn routes)


        Dynamic Routing: Routers use dynamic routing protocols(ie: OSPF)
        to share routing information with each other automatically
        and build their routing tables

        Static Routing: A network engineer/admin manually configure          
        routes on the router 

A route tells the router to send a packet to destination X, you       
should send the packet next hop Y 

OR, if the destination is directly
connected to the router, send the packet directly to the destination

OR, if the destination is the router's own IP address, receive the 
packet for yourself (don't forward it)

## Connected and Local routes


Local: A route to the actual IP address configured on the interface (with a /32 netmask
A local route is a route to the exact IP address configured on the interface

Connected: A route to the network the interface is connected to. (with the actual netmask configured in the interface
A connected route is a route to the network the interface is connected.


