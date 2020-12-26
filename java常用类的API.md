![image-20201225174420008](java常用类的API.assets/image-20201225174420008.png)







# 数组

```java
nums.length    //  求数组的长度
```

# List

```java
List的定义如下：
public interface List<E> extends Collection<E> {}

// 相比与Collection，List新增的API：location 就是索引

abstract void                add(int location, E object)
abstract boolean             addAll(int location, Collection<? extends E> collection)
abstract E                   get(int location)
abstract int                 indexOf(Object object)     //获取对象的第一个索引
abstract int                 lastIndexOf(Object object) //获取对象的最后一个索引 
abstract E                   remove(int location)
abstract E                   set(int location, E object)
abstract List<E>             subList(int start, int end)
```

## ArrayList

```java
public class ArrayList<E> extends AbstractList<E> implements List<E>, RandomAccess, Cloneable, java.io.Serializable

```

ArrayList是一个动态数组，它允许任何符合规则的元素插入甚至包括null。每一个ArrayList都有一个初始容量：

```java
private static final int DEFAULT_CAPACITY = 10;
```

## LinkedList

LinkedList 是 Deque(Queue)的子类！！ 不要搞反）
LinkedList定义如下：

```java
Deque< TreeNode > que = new LinkedList<>();
que.isEmpty()       // 是否为空
que.offerFirst()     // 插入第一个元素
que.pollFirst()      //  删除第一个元素
que.peekFirst()     //     检查第一个元素
que.size();
```

### Deque

![image-20201224160040693](java常用类的API.assets/image-20201224160040693.png)



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

# Set

```java
public void add(Object element) 
public boolean remove(object element) 
public boolean contains(Object o) 
   
```

HashSet

```java
Set<Character> seen = new HashSet<Character>();   
```

TreeSet

```java
TreeSet()// 默认构造函数。使用该构造函数，TreeSet中的元素按照自然排序进行排列。 
TreeSet(Comparator<? super E> comparator) // 指定TreeSet的比较器       
```







# String

```java
s = "name";
s.length();
s.charAt(index);
```

```java
public  substring(int beginIndex,int endIndex)
返回一个新字符串，它是此字符串的一个子字符串。该子字符串从指定的 beginIndex 处开始，一直到索引 endIndex - 1处的字符。因此，该子字符串的长度为 endIndex-beginIndex。
示例：
 "hamburger".substring(4, 8) returns "urge"
 "smiles".substring(1, 5) returns "mile"
参数：
beginIndex - 开始处的索引（包括）。
endIndex - 结束处的索引（不包括）。
返回：
指定的子字符串。
```











































