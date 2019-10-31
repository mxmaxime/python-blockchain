# Blockchain python
Work in progress. This is a toy blockchain to learn.

## Requirements 
- python 3.7+

Because: "Prior to Python 3.7, dict was not guaranteed to be ordered, so inputs and outputs were typically scrambled unless collections.OrderedDict was specifically requested. Starting with Python 3.7, the regular dict became order preserving, so it is no longer necessary to specify collections.OrderedDict for JSON generation and parsing.". Source: 
https://docs.python.org/fr/3/library/json.html

## Protocol to comunicate

### Command
	-c ask the blockchain to a node
	-n ask to a node his all connections
	-an is an answer to the command n
	-t specifi that the node will receiv a transaction
	-b specifi that the node will receiv a block
	-p it's a commande to know how many node are in the same network
	-ap is a answer to the command p