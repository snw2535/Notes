
**Java Collections Notes Yaaaaaaaaay:**  
Apparently very standard according to our prof

Hey I got a package in NRH



## Collections in java
 
She asks for an explanation of collections in java before explaining it. Great.

Apparently a collection is a data structure that can grab different pieces of data  
Sounds to me like a hash table is similar to a collection, or is a type of one but that's just speculation.

She asks what a framework is in java despite being the one teaching the class  
 
####A framework in java:
     - it provides ready made architecture
     - represents a set of classes and interfaces
     - it's optional

####Collection framework:
     - It represents a unified architecture for string and 
       manipulating a group of objects

####Iteration framework:
    - Provides the facility of iterating the elements in a 
      forward direction only
    - There are three methods
        1) public boolean hasNext()
        2) public object next()
        3) public void remove()

####Iterable Interface
    - is the root interface for all the collection classes
    - the collection interface extends the iterable interface
    - contains only one abstract method: Iterator <T> iterator()
    
this is quite boring and we're only at about 17:34 in the recording, which I will add to this package of notes    

note to self, add the recording to the notes. Please

####Collection Interface
    - builds the foundation on which the collection framework depends
    - some of the methods in the collection interface are 
        1) Boolean add(object obj)
        2) Boolean addAll(Collection C)
        3) void clear()
        
####List Interface
    - is the child interface of collection interface
    - it can have duplicate value
    - is implemented by the classes ArrayList, LinkedList
    
#####To instantiate the List interface
    1) List<dataType> list1 = new ArrayList();
    2) List<dataType> list2 = new LinkedList();
    3) List<dataType> list3 = new Vector();
    4) List<dataType> list4 = new Stack();
    
####ArrayList Class
    - uses dynamic array to store the duplicate elements of 
      different datatypes
    - maintain the insertion order
    - elements stored can be randomly accessed

####Queue interface
    - maintains the first_in_first_out order
    - various classes like priority queue, Deque and ArrayDeque
    
####PriorityQueue
    - holds the elements or objects by their priorities
    - Doesn't allow null values to be stored in the queue
    
####Deque Interface
    - we can remove and add the elements from both the sides
    - Deque stands for a double_ended queue which enables us 
      to perform the operation at both the ends

####Array Deque
    - implements the Deque interface
    - Unlike queue, we can add or delete the element from both the ends

jesus christ dude I don't understand our
teacher she wants everyone to think exactly
the same way she does so when a student gives a
good explanation but doesn't say it the exact 
way she wanted she says no   
this will be around 43:00 in the audio file

######Important clarification between ArrayDeque and ArrayList and Stack
    ArrayDeque is faster than ArrayList and Stack and 
    has no capacity restrictions
    
####Set interface
    - is present in Java.util package
    - it represents the unordered Set of elements which doesn't 
      allow us to store the duplicate items
    - we can store at most one null value in Set
    
#####Set is implemented by HashSet, LinkedHashSet and TreeSet
    - Set<dataType> S1 = new HashSet<dataType>();
    - Set<dataType> S2 = new LinkedHashSet<dataType>();
    - Set<dataType> S3 = new TreeSet<dataType>();
    
I realize it's her first year but like why did it have to be me,  
She's such an awful teacher, like seriously she's been writing on the  
board this whole freaking time and hasn't said anything but: "Any   
question?" Like yeah of course we have question because you're not  
teaching us the fucking stuff we're supposed to be learning

####HashSet
    - it represents the collection that uses a has table for storage
    - Hashing is used to store the elements in the HashSet
    - it contains unique items
    
####TreeSet
    - implements the set interface that uses a tree for storage
    - contains unique elements
    - the access and retrieval time of TreeSet is quite fast
    - the elements in TreeSet are stored in ascending order
    -  doesn't allow null element
    - maintains ascending order
    
####Java Map Interface
    - contains values on the basis of key and value pairs
    - contains unique keys
    - is useful if you have to search, update or delete elements 
      on the basis of a key
    - doesn't allow duplicate keys but you can have duplicate values
    - there are two interfaces for implementing maps in java
        1) Map
        2) Sorted Map
    - There are three classes
        1) HashMap
        2) LinkedHashMap
        3) TreeMap
    - hashmap and LinkedHashMap allow null keys and values,
      but treemap doesn't allow any null key or values