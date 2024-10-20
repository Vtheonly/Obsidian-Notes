
### **Quiz 1**
**What is the primary purpose of Interprocess Communication (IPC)?**
- [ ] A) To restrict process execution
- [ ] B) To allow processes to share system memory
- [ ] C) To enable communication and synchronization between processes
- [ ] D) To manage the CPU usage

**Answer**: [[C]]

---

### **Quiz 2**
**Which method of IPC involves sharing a memory zone between processes?**
- [ ] A) Shared Memory
- [ ] B) Message Passing
- [ ] C) Mutex
- [ ] D) Semaphore

**Answer**: [[A]]

---

### **Quiz 3**
**In message passing, which primitive is used to send messages between processes?**
- [ ] A) push(message)
- [ ] B) receive(message)
- [ ] C) send(message)
- [ ] D) post(message)

**Answer**: [[C]]

---

### **Quiz 4**
**In the producer-consumer model, what does the consumer do?**
- [ ] A) Generates data for the producer to use
- [ ] B) Consumes or processes data generated by the producer
- [ ] C) Controls access to shared memory
- [ ] D) Sends messages between processes

**Answer**: [[B]]

---

### **Quiz 5**
**What happens in a bounded buffer when the buffer is full?**
- [ ] A) The consumer waits
- [ ] B) The producer waits
- [ ] C) Both producer and consumer stop working
- [ ] D) Data is overwritten

**Answer**: [[B]]

---

### **Quiz 6**
**Which of the following is NOT true in the bounded buffer of size \(n\)?**
- [ ] A) Items are consumed in FIFO order
- [ ] B) The buffer can hold infinite items
- [ ] C) The producer deposits items if there’s at least one empty slot
- [ ] D) The consumer retrieves items if there’s at least one filled slot

**Answer**: [[B]]

---

### **Quiz 7**
**In a single-producer, single-consumer system, which semaphore blocks the consumer when the buffer is empty?**
- [ ] A) nbplein
- [ ] B) nbvide
- [ ] C) mutex_p
- [ ] D) mutex_c

**Answer**: [[A]]

---

### **Quiz 8**
**What does the producer process do after calling `P(nbvide)` in the producer-consumer model?**
- [ ] A) It retrieves an item from the buffer
- [ ] B) It writes an item to the buffer
- [ ] C) It checks if the buffer is empty
- [ ] D) It blocks the consumer

**Answer**: [[B]]

---

### **Quiz 9**
**In the multiple-producer, multiple-consumer system, what role does the semaphore `mutex_p` play?**
- [ ] A) It controls access to the critical section in consumers
- [ ] B) It ensures mutual exclusion for producers when accessing the buffer
- [ ] C) It counts the number of empty slots in the buffer
- [ ] D) It prevents the consumer from writing to the buffer

**Answer**: [[B]]

---

### **Quiz 10**
**In the Reader-Writer model, which process has access to the shared resource when no other processes are active?**
- [ ] A) Readers only
- [ ] B) Writers only
- [ ] C) Both readers and writers
- [ ] D) The system administrator

**Answer**: [[B]]

---

### **Quiz 11**
**In the no-explicit-priority Reader-Writer model, when do multiple readers access the resource?**
- [ ] A) When no writers are active
- [ ] B) When at least one writer is active
- [ ] C) Only after all writers have completed their task
- [ ] D) When the resource is not locked

**Answer**: [[A]]

---

### **Quiz 12**
**What is the purpose of the semaphore `mutex` in the Reader-Writer model?**
- [ ] A) It controls access to the critical section for writers
- [ ] B) It manages the reader count variable
- [ ] C) It allows readers to bypass writers
- [ ] D) It prevents mutual exclusion

**Answer**: [[B]]

---

### **Quiz 13**
**In the Reader-Writer model with reader priority, which semaphore prevents writers from getting stuck indefinitely?**
- [ ] A) w
- [ ] B) mutex
- [ ] C) mutex2
- [ ] D) nbvide

**Answer**: [[C]]

---

### **Quiz 14**
**What is the key difference in behavior between the Reader-Writer model with reader priority and no explicit priority?**
- [ ] A) Readers can access the resource even if a writer is waiting
- [ ] B) Writers have priority over readers
- [ ] C) Readers and writers alternate access
- [ ] D) Writers never block readers

**Answer**: [[A]]

---

### **Quiz 15**
**In the multiple-producer, multiple-consumer system, how is mutual exclusion ensured during buffer operations?**
- [ ] A) Using a critical section controlled by `nbplein` semaphore
- [ ] B) Using separate semaphores for producers and consumers (`mutex_p` and `mutex_c`)
- [ ] C) By allowing simultaneous access to the buffer
- [ ] D) By using the `nbvide` semaphore

**Answer**: [[B]]

---

These questions cover various concepts like IPC methods, the producer-consumer model, and the Reader-Writer model, along with synchronization techniques. Each question has four answer options with a correct choice indicated in the answer.