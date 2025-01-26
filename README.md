# dynaFlowg
Simulate dynamic arrays with Flowgorithm (and files)
Use intended for string data.

STACK: 
start calling initStack(); provided functions:
- initStack(), to create the file "stack.txt" that has a "BOTTOM" string to mark the bottom;
- pop(): returns string data if present, "---EMPTY---" if empty (check for it if used in loops);
- push(string data): puts data at the top of the stack
- getStackSize(): returns stack size, "BOTTOM" excluded.

LIST: 
start calling initList(); provided functions:
- initList(), to create the file "stack.txt" that has a "HEAD" string to mark the head;
- readList(string Vector): fills the provided Vector with the list data;
- appendList(string data): puts data at the tail of the list
- getListSize(): returns list size, "HEAD" excluded.
