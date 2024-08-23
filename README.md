# Synchronous_fifo


## INTRODUCTION
A Synchronous FIFO is a First-In-First-Out queue in which there is a single clock pulse for both data write and data read. In Synchronous FIFO the read and write operations are performed at the same rate. The number of rows is called depth or number of words of FIFO and number of bits in each row is called as width or word length of FIFO. This kind of FIFO is termed as Synchronous because the rate of read and write operations are same.

Basically Synchronous FIFO are used for High speed systems because of their high operating speed. Synchronous FIFO are easier to handle at high speed because they use free running clocks whereas in case of Asynchronous FIFO they uses two different clocks for read and write.

## Operations in the synchronous FIFO:
## 1 Write Operation :
The operation involves in writing or storing the data in to the FIFO memory till it rises any flag conditions for not to write anymore. To perform a write operation the data to be written is given at DIN port and write EN is to be set high then at the next rising edge the data will be written.

## 1 Read Operation:
Read operation performed when we want to get data out from the FIFO memory until it informs there is no more data to be read from the memory, the condition called empty condition. Empty conditions are generated using empty flags.

## Pointers to control operations:
## 1 Write Pointer:
This pointer controls the write operation of the FIFO. It used to points to the FIFO memory location where the data will be written

## 1 Read Operation:
The read operation is controlled by the read pointer. It will be pointing the location from where next data is to be read.
