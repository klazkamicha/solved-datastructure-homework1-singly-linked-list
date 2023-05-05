Download Link: https://assignmentchef.com/product/solved-datastructure-homework1-singly-linked-list
<br>
You are to code a non-circular singly-linked list with head and tail references. A linked list is a collection of nodes, each having a data item and a reference pointing to the next node. The next reference for the tail/last node in this list will point to null. Do <strong>not </strong>use a phantom node to represent the start or end of your list. A phantom or sentinel node is a node that does not store data held by the list and is used solely to indicate the start or end of a linked list. If your list contains <em>n </em>elements, then it should contain exactly <em>n </em>nodes.

Your linked list implementation will use the default constructor (the one with no parameter) which is automatically provided by Java. Do not write your own constructor. Specifications for efficiency and what the method should do are provided in the javadocs.

<h2>Nodes</h2>

The linked list consists of nodes. A class LinkedListNode is provided to you. LinkedListNode has setter and getter methods to access and mutate the structure of the nodes.

<h2>Adding</h2>

You will implement three add() methods. One will add to the front, one will add to the back, and one will add anywhere in the list. See the javadocs for more details.

<h2>Removing</h2>

Removing, just like adding, can be done from the front, the back, or anywhere in your linked list. Make sure that you set any remaining pointers to the deleted nodes to null since in order for the node to be garbage collected, there cannot be any way to access the node. See the javadocs for more details.

<h2>Equality</h2>

There are two ways of defining objects as equal: reference equality and value equality.

Reference equality is used when using the == operator. If two objects are equal by reference equality, that means that they have the exact same memory locations. For example, say we have a Person object with a name and id field. If you’re using reference equality, two Person objects won’t be considered equal unless they have the exact same memory location (are the exact same object), even if they have the same name and id.

Value equality is used when using the .equals() method. Here, the definition of equality is custom made for the object. For example, in that Person example above, we may want two objects to be considered equal if they have the same name and id.

Keep in mind which makes more sense to use while you are coding. <strong>In most cases for this course, you will want to use value equality when comparing objects. A few notable cases where you’d use reference equality is when checking for null or when comparing primitives (in this case, it’s just the </strong>== <strong>operator being overloaded).</strong>

<h2>Differences between Java API and This Assignment</h2>

Some of the methods in this assignment are called different things in Java’s LinkedList class. This won’t matter until you tackle coding questions on the first exam, but it’s something to be aware of. The list below shows all methods with a different name and their Java API equivalent. The format is assignment method name ⇒ Java API name.

<ul>

 <li>addAtIndex(int index, T data)⇒add(int index, T data)</li>

 <li>addToFront(T data)⇒addFirst(T data)</li>

 <li>addToBack(T data)⇒addLast(T data)</li>

 <li>removeAtIndex(int index)⇒remove(int index)</li>

 <li>removeFromFront()⇒removeFirst()</li>

 <li>removeFromBack()⇒removeLast()</li>

 <li>indexOf(T data)⇒indexOf(Object data)</li>

</ul>