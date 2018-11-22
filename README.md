# Linked-List

Requirements
Use the following struct for you linked list functions.
struct student {
       int rollNo;
      char name[50];
      double marks;
     struct node *next;
};
You must implement the following linked list functions in C/C++. Your program must be
modular with good interface for user options. Once program is run, it must be able to call all
the functions.
For this you can use Switch case or if else condition.
1. AllocateNode – this function returns a pointer to new node structure.
2. PrependNode – add a node to the beginning of the list
3. AppendNode – add a node to the end of a list
4. InsertNode – given a node with a particular id number, insert a new node after it.
5. SearchList – given an id number, return the correct node.
6. PrintNode – given an id number, print the data in the correct node.
7. PrintList – print out the contents of each node in the list
8. DeleteFirstNode – delete the first node in the list
9. DeleteLastNode – delete the last node in the list
10. DeleteNode – given an id number, delete the node that contains it.
11. ReverseList – reverse nodes in the list (NOTE: TO GET FULL CREDIT YOU
MUST REVERSE THE NODES IN PLACE)
12. FindMthToLast – return the mth-to-last node in the list (if m=0, the last element in the
list is returned.
You should put the function prototypes in a header file “linkedlist.h” and use “linkedlist.c” for
your implementation
