# Deque

![image-20201224160040693](java常用类的API.assets/image-20201224160040693.png)



```java
List< List<Integer> > res = new ArrayList<>();

Deque< TreeNode > que = new LinkedList<>();

que.isEmpty()       // 是否为空

que.offerFirst()     // 插入第一个元素

que.pollFirst()      //  删除第一个元素

que.peekFirst()     //     检查第一个元素
    
    
    
```

# 数组

```java
nums.length    //  求数组的长度
```

# HashMap

```java
map.clear();
map.size();
map.isEmpty()
map.containsKey();判断
map.containsValue();
map.get(key);
map.put(key,value);
map.putAll(otherMap);
map.remove(key);

map.getOrDefault(key,defaultValue);查找key的值,不存在则返回默认值。

map.entrySet();用来遍历每一对KV
for(Map.Entry<Integer，Integer> etntey : map.entrySet())
Entry是Map集合类中的一个类，所以增强for的迭代类型是Map.Entry，并且是泛型是KV对，不要只写一个。
只要是Map，**泛型**就是一对。
```











































