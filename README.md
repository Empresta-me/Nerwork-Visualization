# Network-Visualization

## Used to display the user's network of trustiness in the form of an interactive graph, with D3.js

## Stuff currently working
	- each node is another user
	- hovering over any node shows their name and their level of trustiness
	- the link between two users is red if either of them doesn't trust the other, green otherwise
	- shows each node's trustiness level in a table which updates with every change in the network

## Stuff to be added
	- the graph updates in real time with any node addition/removal or change in someone's vouch
	- profile photos



### current problems
	- sometimes there is a bug because clicking on a node makes a tooltip with info appear, and that's messing with the draggable feature. It's rare, but it happens, and I don't have a single clue why 
