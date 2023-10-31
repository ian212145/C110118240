# C110118240 
# C110118240 張凱宸
## C110118240 張凱宸
### C110118240 張凱宸
#### C110118240 張凱宸
##### C110118240 張凱宸
# 😄

![NKUST](logo.png "高科大")


- [ ] to do list
- [x] 1st thing
- [ ] 2nd thing
- [ ] 3rd thing
- [ ] 4th thing

```python
s = "python highlighted syntex"
print(s)
```

```js
var s ="Javascript highlights";
alert(s)
```

---
Emphasism aka italicsm with asterisks or underscores
Strong emphasis, aka boldm with **asterisks** or **underscores**
Combined emphasis with **asterisks and underscores.**
Strikethrough uses two tildes. ~~Scratch this.~~

---

1. First ordered list item
2. Another item <br>
..*  Unordered sub-list.
4. Actual numbers don't matter, just that it's a number</br>
..1. Ordered sub-list</br>
...2. 2nd
5. And another item.</br>
...* note 1</br>
...* note 2</br>
***  note 3
   
---
Colons can be used to columns.
|Tables|Are|Cool|
|:---------|:--------:|--------:|
|col 3 is |right-aligned|$1600|
|col 2 is | centered|$12|
|zebra stripes|are neat|$1|
----
There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the raw Markdown line up prettily. You can also use inline Markdown.
| Markdown| Less    | Pretty   |
| :-------|:------- | :--------|
|*Still*  |`renders`|**nicely**|
|1        |2        |3         |
----

abstract class CShape{
    protected String color;
    public void setColor(String str){
        color = str;
    }


    public abstract void show();
}

class CTriangle extends CShape{
    double ca, cb, cc;
    public CTriangle(double a, double b, double c){
        ca=a;
        cb=b;
        cc=c;
    }
   
    public void show() {
       
        System.out.print("color="+color+"  ");
        System.out.print("area="+0.5*ca*cb);
    }
   
}

public class app11 {
   public static void main(String[] args) {
    CTriangle ct = new CTriangle(3, 4, 5);
    ct.setColor("red");
    ct.show();
}
}
