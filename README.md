# Packet-Sniffer

Deamon who capture TCP packets and store them in a database
This is not the final version. The next updates will improve the database structure, and the data stored. 

## Requires

*--Scapy* 
/bin/bash: q: command not found

## Usage

`./main [--verbose True|False]`

*--verbose* : Print the number of packets sniffed. True by default.

## Is the next versions...

Database : The structure of the database will change. The data will be extracted and store in a NoSQL database. 

Data : The data extracted by scapy will be separated before the storage in the database. It will able you to improve the search in the packets.

