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

abstract class CShsape 
{
//CShape父類別
protected String color;
public void setcolor(String str){
color = str;
}
public abstract void show();

}

class CTriangle extends CShape{
    protected double bottom,height,hypotenuse;
    
    public  CTriangle (a,b,c){
        if(Math.pow(a,2) = Math.pow(b,2) + Math.pow(c,2)){
            b = height;
            c=  bottom;
            a = hypotenuse;
        }else if(Math.pow(c,2) = Math.pow(b,2) + Math.pow(a,2)){
            b = height;
            a = bottom;
            c = hypotenuse;
        }else if(Math.pow(b,2) = Math.pow(a,2) + Math.pow(c,2)){
            a = height;
            c = bottom;
            b = hypotenuse;
        }else{
        System.out.println("這不是直角三角形");
           }
           
        public void show(){
            System.out.print("color="+color+", ");
            System.out.print("area = "+ (bottom*height)*0.5);
        }
        
        
        public class app11_1{
            public static void main(String agrs[]){
                CTriangle t1 = new CTriangle(3,4,5);
                t1.setcolor("Red");
                t1.show();
            }
        }
    }
```
