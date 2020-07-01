## Hashtables
- Hash: the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose. In the case of a hashtable, it is used to determine the index of the array.
- Buckets: it is what is contained in each index of the array of the hashtable. Each index is a bucket. An index could potentially contain multiple key/value pairs if a collision occurs.
- Collisions: it is what happens when more than one key gets hashed to the same location of the hashtable.
- Hashtables are a data structure that utilize key value pairs.
## Why do we use them?
- Hold unique values
- Dictionary
- Library

### Hashing
- a hash code turns a key into an integer.
-  their output is determined only by their input. 
- Hash codes should never have randomness to them. 
- The same key should always produce the same hash code.

## Creating a Hash
- A hashtable traditionally is created from an array.
>- Add or multiply all the ASCII values together.
>- Multiply it by a prime number such as 599.
>- Use modulo to get the remainder of the result, when divided by the total size of the array.
>- Insert into the array at that index.

### Collisions
- A collision occurs when more than one key hashes to the same index in an array.
- Collisions are solved by changing the initial state of the buckets.

## Internal Methods
- Add():
>>- send the key to the GetHash method.
>>- Once you determine the index of where it should be placed, go to that index
>>- Check if something exists at that index already, if it doesn’t, add it with the key/value pair.
>>- If something does exist, add the new key/value pair to the data structure within that bucket.

- Find(): The Find takes in a key, gets the Hash, and goes to the index location specified.
- Contains(): The Contains method will accept a key, and return a bool on if that key exists inside the hashtable.
- GetHash(): The GetHash will accept a key as a string, conduct the hash, and then return the index of the array where the key/value should be placed.

### Hash Tables
- Hashing is a technique that is used to uniquely identify a specific object from a group of similar objects.

### Hashing implementation:
>>- An element is converted into an integer by using a hash function. This element can be used as an index to store the original element, which falls into the hash table.
>>- The element is stored in the hash table where it can be quickly retrieved using hashed key.

### Hash function
- A hash function is any function that can be used to map a data set of an arbitrary size to a data set of a fixed size, which falls into the hash table. 

### Quadratic Probing
- Quadratic probing is similar to linear probing and the only difference is the interval between successive probes or entry slots. Here, when the slot at a hashed index for an entry record is already occupied, you must start traversing until you find an unoccupied slot.
