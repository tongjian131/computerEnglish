# computerEnglish
[link to next.md](https://github.com/tongjian131/computerEnglish/blob/main/next.md)
# head
## head
### head
*I'm* tongjian.

**I'm** tongjian.

~~I'm~~ tongjian.


---

>I'm a student of JLU.

[学习通](http://www.chaoxing.com)

* title1
* title2
* title3 
  * next title1
  * next title2
  * next title3
 
1. lable1
2. lable2
3. lable3   

<p>I'm tongjian.</p >

### 图片
![dog](https://t7.baidu.com/it/u=4162611394,4275913936&fm=193&f=GIF)

```python
def bubble_sort_flag(list):
    length = len(list)
    for index in range(length):
        # 标志位
        flag = True
        for j in range(1, length - index):
            if list[j - 1] > list[j]:
                list[j - 1], list[j] = list[j], list[j - 1]
                flag = False
        if flag:
            # 没有发生交换，直接返回list
            return list
    return list
```

```c
#include<stdio.h>
int main(){
print("hello world!");
return 0;}

```
|  左  |  右  |  居中  |
| :-----| ----: | :----: |
|  A1  |  A2  |  A3  |
|  B1  |  B2  |  B3  |
* [x] task1
* [x] task2
* [ ] task3
