# admin #

***Admin Protocol for Index Card Data Exchange Protocol***

My proposition to be able to send commands to each individual node within the class is to send a message out to all nodes within the class. The nodes will then respond with their own cards containing their unique identifiers, and if necessary, their route. Both of these values would be contained as headers and utilize the protocol discussed within extension.md. These identifiers will be added to a table, and once the table is created with all the nodes on the network commands can be sent to each node in the network through a header containing their unique identifier and route. To apply this to each person at the University of Washington, we would merely need to implement headers that contain the building/room identifiers. Adding the table of nodes allows us to treat each individual node as its own recipient, capable of receiving commands, instead of merely as a pass-through to preset destinations. 
