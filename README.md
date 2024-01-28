# Linear Search

### Objective
In this project, our main goal is to understand the linear search algorithm.


### Problem
Create a doubly linked list corresponding to the following diagram and linear search function to search for the value of 9.
                                                           
<img width="1000" height="150" alt="linked list" src="https://github.com/SAFCSP-Team/linear-search/blob/main/Image/search-project.jpg">

### Implementation
* Create a doubly linked list where the data is an integer.
* implement a `linear search` function to search for the target, and  print the number of iterations it took to find the target value.
* In the `main` method, call the linear Search function with 9 as a target.
                                           
```java
public class DoublyLinkedList{
   Node head;
   public void linearSearch(int target) {
          /*add your code here*/
   }
   
   public static void main(String[] args) {
       DoublyLinkedList doublyList = new DoublyLinkedList();
       DoublyLinkedList.linearSearch(9)
   }
}

```
