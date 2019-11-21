# 0624018 **黃崇祐**

## 0624018 黃崇祐

### ~~0624018~~ *黃崇祐*

#### 0624018 黃崇祐

##### 0624018 黃崇祐

:chicken:

:chicken:

:chicken:

`小區塊`

```大區塊```

> 多行123,

> 多行,

> 多行

>台灣
>>高雄市

* 1
* 2
* 3

1. 1
2. 2
3. 3

***

[外部超連結](https:\\tw.yahoo.com)

|   left  |   midddle  |   right  |
|:--------|:----------:|---------:|
|123456|123|123|
|123456|123|123|
|123456|123|123|

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello! World!");
    }
}
```


![NKUST](nkust.png)

[![AAA](DONDON.jpg)](https://www.youtube.com/watch?v=AhMhjkYMU5k)


```java
//父子類別作業

//CShape父類別
abstract class CShape 
{
protected String color;
public void setcolor(String str){
color = str;
}
public abstract void show();

public static void main(String agrs[]){
       CTriangle t1 = new CTriangle(3,4,5);
       t1.setcolor("Red");
       t1.show();
     }
}



//另一類別CTriangle
class CTriangle extends CShape{
    protected double bottom,height,hypotenuse;
    
    public  CTriangle (double a,double b,double c){
        bottom = a;
        height = b;
        hypotenuse = c;
    }
    
     @Override
         public void show(){
            System.out.print("color="+color+", ");
            System.out.print("area = "+ (bottom*height)*0.5);
        }       
    } 
    
```
