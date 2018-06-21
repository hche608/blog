---
title: Java 101
---

#Collection

![Java Collection](https://github.com/hche608/blog.hax3.github.io/raw/master/static/imgs/Java-Collection.png "Java Collection")

ArrayList
```jave

ArrayList arrayList = new ArrayList();
arrayList.add(3);
arrayList.add(2);
arrayList.add(1);
arrayList.add(4);
arrayList.add(5);
arrayList.add(6);
arrayList.add(6);

Iterator iter = arrayList.iterator();
while(iter.hasNext()){
    System.out.println(iter.next());
}

```

LinkedList
```jave

LinkedList linkedList = new LinkedList();
linkedList.add(3);
linkedList.add(2);
linkedList.add(1);
linkedList.add(4);
linkedList.add(5);
linkedList.add(6);
linkedList.add(6);

Iterator iter = linkedList.iterator();
while(iter.hasNext()){
    System.out.println(iter.next());
}

```

ArrayList vs LinkedList (time complexity)


|          | ArrayList  | LinkedList  |
| -------- |:----------:| -----------:|
| get()    |    O(1)    |    O(n)     |
| add()    |    O(1)    |    O(1)     |
| remove() |    O(n)    |    O(n)     |
