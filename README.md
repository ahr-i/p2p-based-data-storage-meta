# P2P-based Data Storage Meta
A system for distributing and storing data in a P2P environment.

## 1. Introduction
Centralized server-based data storage has a Single Point of Failure (SPoF) problem, along with reliability and integrity issues.

This project implements a system for distributing and storing data.   
The system has two roles:   
1. Nodes responsible for storage and providing a download web page.   
2. Bootstrap nodes.   

When nearby nodes can be discovered, broadcasting is used to locate them.   
If nearby nodes cannot be accessed, bootstrap nodes are used to find nodes.   

## 3. Repository Struct
|Repository|Description|URL|
|:---|:---|:---|
|p2p-based-data-storage-webui|Nodes are responsible for data storage and provide a web page to download stored files.|[link](https://github.com/ahr-i/p2p-based-data-storage-webui)|
|p2p-based-data-storage-bootstrap|The bootstrap nodes serve as meeting points for nodes running in the P2P environment, creating a truly charming and romantic place.|[link](https://github.com/ahr-i/p2p-based-data-storage-bootstrap)|
