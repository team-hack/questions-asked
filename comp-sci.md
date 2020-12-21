# Comp Sci

What is a bit? A byte?
Bit = basic unit for holding computer information
Byte = holds 8 bits
What is the difference between 8-bit and 16-bit? 32 bit, 64 bit? Why is 128 bit considered unnecessary?
Basically the answer here is word size of values (or addresses) that we can store
With 8 bit architecture, it was possible to have 256 values (2^8) we could represent as numbers, character sets, or even address lines.   In the 80s, we could have 256 different addresses with each line storing up to 1 byte of info (or 8 bits).  Later came 16 bit lines which made it possible to have 2^16 different addresses with 16 or even 32 bits (or up to 4 bytes) of info; presently we are on 64 bit architecture which means 2^64 different values (or 8 bytes of info) that can be addressed on gigabytes of memory (billions of bytes)-- huge memory; in fact so big we don’t need any more than that to do most common computing tasks in memory -- (not hard drive space, e.g. ROM).
Most processors are now running on 64 bit architecture, meaning that they can read blocks of 8 bytes at a time, even if the value isn’t necessarily that huge; the endianness of the value determines how the CPU reads the value (right to left or left to right)
What is word length? What is a bus?
Word length refers to the size of a value / address / register
The bus determines how much memory a CPU can read
How does a CPU work? (See simplecpu.com) 
What is the difference between int, long, short, float, decimal, char?
Different ways of storing bits, essentially each primitive stores a range of 2^8 to 2^64 bits.  Primitives can be copied directly (bits), however objects are references to bits that live on the garbage heap, which get collected if not used
What is an unsigned int mean?  How about a signed int?
What is an array? What is a string? Linked list?
What is hexadecimal? How does it relate to binary? 
Easy way to represent large binary numbers
How to count in binary? Threes? Octal? Hex? Decimal?
What is a kernel?  
What is 1’s | 2’s complement? 
What is a type? 
What is a frame?
What’s the main function do in C, C++, Java & C#?
What is a shallow copy, and what is a deep copy? How do they differ?
What is the stack?  
What is the heap? (memory pool)?
What is a heap data structure?
What’s a min heap? A max heap?
What’s the difference? 
Heaps are trees of information (e.g. max/min heaps) where data can reside (for collection later). 
Stacks hold things like function scopes, as we finish one frame, we pop it off a stack until we are done with all frames.   LIFO
Queues are FIFO, so great for traversing things like graphs/trees
What is a stack overflow?
What’s a reference?
Syntactic sugar for getting an address in C++
What is a pointer?
Points to an address in memory
How do you dereference a pointer? (Use the * symbol)
Give examples of pointer usage
Give examples of reference usage
What is the benefit of using constant pointers? Constant references? Constant pointers to constants?
What is a memory leak?
When we lose an address by destroying or overwriting a pointer to that memory
What is a thread?  What is threading? 
Can be another stack of data that the CPU can run thru and give the idea of ‘multitasking’
What is class abstraction? 
Classes that don’t get instantiated; makes no sense to implement but rather inherit from
What’s a virtual function?
A function that is only for implementation, not actual use
What is encapsulation? 
Keeping your private and public instance variables and methods safe from other classes / direct manipulation
What is an enum?
Easy way to assign values to numbers for reference later
What’s a struct?
Old way of defining classes (can’t do inheritance)
What is a typedef?
Define a type 
What’s a template?
A class / method that can take any type
What is the std library?
What’s a vector? 
Like an arraylist in java
What is function overloading?
What is function overriding?
Overloading = Rewriting function to handle a different type
Overriding = Changing what a function does in a child class
What is polymorphism? 
Allowing any object from its parent to child to work with another object’s function/method and producing different results
What is an interface? (How does it differ from a class)?
Something that a class can use for methods/properties, but doesn’t interfere with inheritance
What is OOP? Classes?
What’s a constructor? What’s a destructor?
Constructors set up the classes to have initial values/state, destructors properly destroy all references to state values after class is no longer needed
What’s the difference between a stream and cout?
What’s a buffer?  How does it help with using a stream?
What is a bit mask? 
Easy way to get values needed from a larger number (e.g. hex numbers)
What’s a linked list? 
What’s a hash, and how do you make one?
What are trade-offs between arrays, vectors, linkedlists (or lists), and hashes?
What is bit AND, bit OR, bit XOR? 
What is a complement? 
What is 1s complement, 2s complement?
How do you read from files in Java? Python? Node.js?
What is ASCII?  How does it differ from Unicode?
ASCII represents 256 different characters that match numbers 0 to 255, with 128 of them being alphanumeric characters.
Unicode represents way more combinations of letters/numbers including Chinese, Japanese, etc