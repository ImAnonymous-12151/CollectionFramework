# CollectionFramework


## What is Collection?
A Collection is simply an object that represents a group of objects,known as its elements.

## What is Collection framework?
It provides a set of Interfaces and classes that help in managing group of object.

## History
Before the introduction of the Collection Framework in JDK 1.2, Java used to rely on a variety of classes like Vector, Stack, Hashtable, and arrays to store and manipulate groups of objects
* Inconsistency: Each class had a different way of managing collections, leading to confusion and a steep learning curve.
* Lack of inter-operability: These classes were not designed to work together seamlessly.
* No common interface: There was no common interface for all these classes, which meant you couldn't write generic algorithms that could operate on different types of collections.

### To solve all these problem the collection framenwork was introduced.

### After collection framework ->
* Unified architecture: A consistent set of interfaces for all collections.
* Inter-operability: Collections can be easily interchanged and manipulated in a uniform way.
* Reusability: Generic algorithms can be written that work with any collection.
* Efficiency: The framework provides efficient algorithms for basic operations like searching, sorting, and manipulation.

## Most Important Interfaces
* Collection: The root interface for all the other collection types.
* List: An ordered collection that can contain duplicate elements (e.g., ArrayList, LinkedList).
* Set: A collection that cannot contain duplicate elements (e.g., HashSet, TreeSet).
* Queue: A collection designed for holding elements prior to processing (e.g., PriorityQueue, LinkedList when used as a queue).
* Deque: A double-ended queue that allows insertion and removal from both ends (e.g., ArrayDeque).
* Map: An interface that represents a collection of key-value pairs (e.g., HashMap, TreeMap)

## Hierarchy
![Java Collection Framework Hierarchy](https://raw.githubusercontent.com/ImAnonymous-12151/CollectionFramework/main/Screenshot%20from%202025-02-05%2017-41-17.png)

###Iterable
Iterable is a root Interface in a collection hierarchy it has only use that its child can use for each loop.
## List Interface

