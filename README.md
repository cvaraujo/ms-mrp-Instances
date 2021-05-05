# Maximum Service in Multicast Routing Protocol with Quality of Service Constraints
This rpeository contains the first set of instances to the MS-MRP-QoS problem

## Getting Started

This set of instances was made from some slices of the washington map extracted from OpenStreeMaps. The areas are 50 x 50, 75 x 75, 100 x 100 and 200 x 200

### QoS Metrics
The QoS metrics presented for each arc int the graph are:
* Delay
* Jitter
* Bandwidth
* Link Duration Estimation

### Folders
This benchmark set contains 40 instances divided in 4 folder. Each folder is represented in following pattern: City-Area.
Inside this folders has 10 subfolders, one for each instance.

### Instance Format
Each instance is composed for two files:
The first is "washington-Area-NumberOfNodes-NumberOfTerminals.txt", that contains the network topology along with the QoS metrics.
The file "param-washington-Area-NumberOfNodes-NumberOfTerminals.txt" contains the limits of each metric for this instance.

