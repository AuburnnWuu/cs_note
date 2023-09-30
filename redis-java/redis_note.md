## Data Structures
- #### String
Saved as key-value by byte[], 2 and 3 is allowed to do auto-increment
value: 1. string 2. int 3. float
- **Command**
  - SET: add or update
  - GET
  - MSET: batch add
  - MGET
  - INCR: make an interger key increase 1
  - INCRBY: make an interger key increase specific size(negative allowed)
  - INCRBYFLOAT
  - SETNX: add a string type kv only when it's not exist(also written as: set k v nx)
  - SETEX: add a string type kv and designate expire time


- #### Hash
- #### List
- #### Set
- #### SortedSet