### Time Recordings

SIZE = 10 --> 42s

SIZE = 100 --> 35s

SIZE = 1000 --> 54s

SIZE = 10000 --> 1m 46s

### In Code Questions: TestJava

**also try with a LinkedList - does it make any difference?** LinkedList makes the code run faster.

**list.remove(5); what does this method do?** removes the item at index 5

**list.remove(Integer.valueOf(5)); what does this one do?** removes the item 5 from the list, at index 4

### In Code Questions: TestIterator
**also try with a LinkedList - does it make any difference?** LinkedList doesn't run.

**what happens if you use list.remove(77)?** remove() requires an argument within the index, so list.remove(77) causes an error as list does not have an item at index 77

### In Code Quetions: TestPerformance
**which of the two lists performs better as the size increases?** arrayList