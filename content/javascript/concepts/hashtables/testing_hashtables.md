---
Title: Testing Hashtables

*In order to test your own Hashtable, you can start by creating an instance of the Hashtable class from the original implementation and set some key-value pairs like the example below:

```
#const ht = new Hashtable()
ht.set("Uruguay", 149)
ht.set("United States", 160)
ht.set("Germany", 231)
```
- Afterwards, you need to try and retrieve them using the get method

  ```
  #console.log(ht.get("Uruguay")) //["Uruguay", 149]
  console.log(ht.get("United States"))  //["United States", 167]
  console.log(ht.get("Germany"))  //["Germany", 231]
  ```
- Here's an example of trying to delete an instance of the hashtable class

```
#console.log(ht.remove("United States")) // true
#console.log(ht.get("United States")) // undefined
```
## Here, as you can see, all of the methods are working on the hashtable. 

