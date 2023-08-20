# Stack and Queue

## Stack 

---

a stack is a data structres that has (first out LIFO and last out FILO) principles , its consits of node , where each node has a refference to next node 

### opertations on satack:
- #### Push:
  Adding a new node to the top of the stack. it has (O(1)).

- #### Pop:
  Removing the top node from the stack. This operation is also usually constant time complexity (O(1)).

- #### Peek:
  Viewing the value of the top node without removing it from the stack. This operation is also constant time complexity (O(1)).

- #### IsEmpty:
  Checking whether the stack is empty. This operation is constant time complexity (O(1)).

---

## Queue

---

a queue is data structure the follow (first in first FIFO and last in last LILO) principles , it have a node the contains refferance to next node

### operations of queue:
 - #### Enqueue:
   Adding a new node to the rear of the queue. This operation is generally an O(1) operation, meaning its efficiency does not depend on the number of elements already in the queue.

- #### Dequeue:
  Removing the front node from the queue. Like the enqueue operation, dequeue is also typically an O(1) operation.

- #### Peek:
  Viewing the value of the front node without removing it. This operation is usually constant time complexity (O(1)).

- #### IsEmpty: 
  Checking whether the queue is empty. This operation is an O(1) operation.