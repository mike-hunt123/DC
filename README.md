# ✅ **EXPERIMENT 1**

📄 Source: 

### **Experiment No.: 01**

### **Experiment Name:** Inter Process Communication

### **Aim:**

To implement Inter process Communication. 

### **Theory / Algorithm:**

* Inter process communication (IPC) is a mechanism which allows processes to communicate and synchronize their actions. 
* Communication methods:

  * Shared Memory
  * Message Passing
* IPC provides:

  * Datagram communication
  * Stream communication
* Message Passing Steps:

  1. Establish communication link
  2. Use primitives:

     * send(message, destination)
     * receive(message)
  3. Messages can be fixed or variable size
* Message structure:

  * Header (type, source, destination, control info)
  * Body

### **Conclusion:**

We have successfully implemented the Inter process Communication. 

---

# ✅ **EXPERIMENT 2A**

📄 Source: 

### **Experiment No.: 02A**

### **Experiment Name:** Client-Server using RPC

### **Aim:**

Client/server using RPC. 

### **Theory / Algorithm:**

* Client-server model is widely used communication paradigm.
* Server:

  * Creates server socket
  * Waits for client request
  * Accepts connection
  * Communicates via input/output streams
* Steps (Server):

  1. Create ServerSocket
  2. Accept client request
  3. Open streams
  4. Communicate
  5. Close connection
* Steps (Client):

  1. Create Socket
  2. Connect to server
  3. Open streams
  4. Send/receive data
  5. Close connection

### **Conclusion:**

Client-server communication using RPC is successfully implemented. *(derived from output section)* 

---

# ✅ **EXPERIMENT 2B**

📄 Source: 

### **Experiment No.: 02B**

### **Experiment Name:** Remote Method Invocation (RMI)

### **Aim:**

To implement a program to illustrate the concept of Remote Method Invocation (RMI). 

### **Theory / Algorithm:**

* RMI allows invoking methods on remote JVMs.
* Components:

  * RMI Client
  * RMI Server
  * Stub (client side proxy)
  * Skeleton (server side proxy)
  * Registry
* Algorithm:

  1. Define Remote Interface
  2. Implement interface
  3. Create server and bind object using `rebind()`
  4. Create client and use `lookup()`
  5. Invoke remote methods

### **Conclusion:**

We have successfully implemented the concept of Remote Method Invocation (RMI). 

---

# ✅ **EXPERIMENT 3**

📄 Source: 

### **Experiment No.: 03**

### **Experiment Name:** Group Communication

### **Aim:**

To implement Group Communication. 

### **Theory / Algorithm:**

* Group communication involves multiple processes communicating collectively.
* Key property: message sent to group is received by all members.
* Types:

  1. Flat Groups (no hierarchy)
  2. Hierarchical Groups (coordinator-based)
* Group Membership:

  * Join / Leave operations
  * Synchronization required
* Message ordering and security can be implemented

### **Conclusion:**

Group communication mechanism was successfully implemented. *(derived)* 

---

# ✅ **EXPERIMENT 4**

📄 Source: 

### **Experiment No.: 04**

### **Experiment Name:** Christian’s Clock Synchronization Algorithm

### **Aim:**

To implement Christian’s clock synchronization Algorithm. 

### **Theory / Algorithm:**

* Distributed systems have no global clock.
* Synchronization is required for coordination.
* Christian’s Algorithm:

  1. Client sends request to server
  2. Server sends current time T
  3. Client sets time = T + RTT/2
* Improves accuracy by using minimum RTT

### **Conclusion:**

We have successfully implemented Christian’s clock synchronization Algorithm. 

---

# ✅ **EXPERIMENT 5**

📄 Source: 

### **Experiment No.: 05**

### **Experiment Name:** Election Algorithm

### **Aim:**

To implement Election algorithm. 

### **Theory / Algorithm:**

* Used to select coordinator in distributed systems.
* Each process has unique ID.
* Goal: select highest ID process.

**Bully Algorithm:**

1. Send election message to higher IDs
2. If no reply → becomes coordinator
3. If reply → wait for coordinator message

**Ring Algorithm:**

1. Processes form ring
2. Election message circulates
3. Highest ID becomes coordinator

### **Conclusion:**

We have successfully implemented an Election Algorithm. 

---

# ✅ **EXPERIMENT 6**

📄 Source: 

### **Experiment No.: 06**

### **Experiment Name:** Ricart–Agrawala Mutual Exclusion Algorithm

### **Aim:**

To implement Ricart–Agrawala mutual exclusion algorithm. 

### **Theory / Algorithm:**

* Ensures only one process enters critical section (CS).
* Steps:

  1. Send timestamped request to all processes
  2. Receive replies
  3. Enter CS after all replies
  4. On exit → send deferred replies
* Message complexity: 2(N-1)

### **Conclusion:**

Hence we have implemented Ricart–Agrawala algorithm successfully. 

---

# ✅ **EXPERIMENT 7**

📄 Source: 

### **Experiment No.: 07**

### **Experiment Name:** Edge Chasing Deadlock Detection

### **Aim:**

To implement Edge Chasing deadlock detection algorithm. 

### **Theory / Algorithm:**

* Deadlock occurs when processes wait indefinitely.
* Uses probe message (i, j, k).
* Steps:

  1. Send probe messages along wait-for graph
  2. If probe returns to initiator → deadlock
* Maintains dependency array

### **Conclusion:**

Deadlock detection using edge chasing algorithm is successfully implemented. *(derived)* 

---

# ✅ **EXPERIMENT 8**

📄 Source: 

### **Experiment No.: 08**

### **Experiment Name:** Load Balancing

### **Aim:**

To implement load balancing. 

### **Theory / Algorithm:**

* Load balancing distributes tasks across processors.
* Key policies:

  1. Load estimation policy
  2. Process transfer policy
  3. State information exchange policy
  4. Location policy
  5. Priority assignment policy
  6. Migration limiting policy
* Goal: equal workload across processors

### **Conclusion:**

Load balancing in distributed systems is successfully implemented. *(derived)* 

---
