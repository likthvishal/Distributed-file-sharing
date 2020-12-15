# Distributed-file-sharing-system


## Installation
Install grpcio  ``` sudo python -m pip install grpcio```

Install grpcio  ```python -m pip install grpcio-tools```

```MongoDB``` ```Redis```

## Technologies

1. Language used for the application code – Python
2. gRPC (Both inter-cluster communication and intra-cluster communication)
3. Protobuf as the interface definition language
4. Redis cache – In-memory database
5. MongoDB – Durable database

## Goal
The aim of the project is to develop a distributed data storage system. The system consists of multiple heterogeneous clusters; heterogeneous in the sense that each cluster’s choice of internal design is independent of the design choices made by the other clusters. However, since the clusters together form a single service, they need to agree on the mode of communication
with each other.

A user can opt to use the services of a particular cluster by talking to the cluster’s end-point. Alternatively, the user can use the service through the common endpoint, called the “super node” and supports data of all forms text, structured or images.


