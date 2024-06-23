# A distributed file-system in GO

This is a distributed UNIX compatible file system written in Go. The features include: 

| feature | description |
| Peer-to-peer connection library | Used to discover peers in a network useing DHT's| 
| custom decoder for TCP transport | Parsing raw byte streams recived over the TCP network |
| Broadcating to a network | Sending relevant messages to peers in a network |
| Distributed Hash Table | Used to map out and store and retrieve files and folders |
| Destributed file server | Supporting file upoads and downloads from and to peers |
| Hard Encryption | Encryption and decryption of files and folders |
| CRUD operations API| APIs and functiond for perfoming CRUD operations | 


# SPOILER ALERT !!!

I havent finished the project and the binaries happen to crash every 3 hrs and there are other bugs that need
fixing befror making it production ready. bug fixes are accepted via PR's