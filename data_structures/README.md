## Data Structures

[Data structures playlist](https://www.youtube.com/playlist?list=PL9xmBV_5YoZO2D89q42-y8voxIJKpB4oR)

### Linked List

* [Video](https://youtu.be/F8AbOfQwl1c)
```
❯ python linked_list.py
None
5 --> None
1 --> 2 --> 3 --> 4 --> 5 --> None
Deleting 4..
1 --> 2 --> 3 --> 5 --> None
Deleting 2..
1 --> 3 --> 5 --> None
3
None
```

### Stack

* [Video](https://youtu.be/KcT3aVgrrpU)
```
❯ python stack.py
[]
[1]
[1, 2]
[1, 2, 3]
[1, 2]
[1, 2, 4]
[1, 2]
[1]
[]
```

### Queue

* [Video](https://youtu.be/D6gu-_tmEpQ)
```
❯ python queue.py
deque([])
deque([1])
deque([1, 2])
deque([1, 2, 3])
deque([2, 3])
deque([2, 3, 4])
deque([3, 4])
deque([4])
deque([])
```

### Hash Table

* [Video](https://youtu.be/knV86FlSXJ8)
```
❯ python hash_table.py
{'a': 1, 'b': 9, 'c': 'nebraska', 'd': True}
{'a': 1, 'b': 9, 'c': 'nebraska', 'd': True, 'e': False}
{'b': 9, 'c': 'nebraska', 'd': True, 'e': False}
nebraska
hash of 50 with table size 13 --> 11
```

### Heap

* [Playlist](https://www.youtube.com/playlist?list=PL9xmBV_5YoZNsyqgPW-DNwUeT8F8uhWc6)
* Videos: [Intro](https://youtu.be/0wPlzMU-k00) | [Methods](https://youtu.be/pAU21g-jBiE) | [Sort](https://youtu.be/2DmK_H7IdTo)

```
❯ python heap.py
Heap: [89, 12, 65, 9, 5, 25, 28, 4, 6, 3, 0, 22, 20, 1, 10]
```

### Fibonacci Heap

* [Playlist](https://www.youtube.com/playlist?list=PL9xmBV_5YoZNkwWDXcSiZjMgacw2P0U2j)
* Videos: [Intro](https://youtu.be/0vsX3ZQFREM)
* h/t **Daniel Borowski** – [GitHub](https://github.com/danielborowski/fibonacci-heap-python) | [LinkedIn](https://www.linkedin.com/in/daniel-borowski/)

```
❯ python fibonacci_heap.py
--------------------
-- Fibonacci Heap --
--------------------
Total nodes: 4
Minimum: 2
Root list: [5, 2, 16, 9]
--------------------

--------------------
-- Fibonacci Heap --
--------------------
Total nodes: 14
Minimum: 2
Root list: [5, 2, 16, 9, 20]
Children of 2: [12, 38, 19]
Children of 16: [29]
Children of 9: [25, 59]
Children of 12: [31]
Children of 19: [22]
Children of 25: [32]
--------------------

FH1 before union:
--------------------
-- Fibonacci Heap --
--------------------
Total nodes: 7
Minimum: 2
Root list: [5, 2]
Children of 2: [12, 38, 19]
Children of 12: [31]
Children of 19: [22]
--------------------

FH2 before union:
--------------------
-- Fibonacci Heap --
--------------------
Total nodes: 6
Minimum: 9
Root list: [16, 9]
Children of 16: [29]
Children of 9: [25, 59]
Children of 25: [32]
--------------------

Union of FH1 and FH2:
--------------------
-- Fibonacci Heap --
--------------------
Total nodes: 13
Minimum: 2
Root list: [5, 2, 16, 9]
Children of 2: [12, 38, 19]
Children of 16: [29]
Children of 9: [25, 59]
Children of 12: [31]
Children of 19: [22]
Children of 25: [32]
--------------------
```
