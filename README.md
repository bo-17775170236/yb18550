[yb18550](https://github.com/bo-17775170236)
# –讲述自己学习Markdown的过程、经历和实践，以及成果展示(各种Markdown语法的使用)
## 1.标题的展示
# 这是一级标题
## 这是二级标题
### 这是三级标题
#### 这是四级标题
##### 这是五级标题
###### 这是六级标题
## 2.字体的变化
 - **这是加粗的文字**  
 - *这是斜体的文字*  
 - ***这是斜体加粗的文字***  
 - ~~这是加删除线的文字~~  
## 3.引用的方法
>这是引用的内容
>>这是引用的内容
>>>这是引用的内容
>>>>>>>>这是引用的内容
## 4.分割线的表示方法
三个或者三个以上的 - 或者 * 都可以。
---
----
***
*****
## 5.图片的引用
![鬼灭之刃](http://a3.qpic.cn/psb?/V13fJoaH2EnU0x/WPGfjSGLb6e9FRUfy*zg1i.Khcylm5lX1hBRUjDgcro!/b/dLYAAAAAAAAA&ek=1&kp=1&pt=0&bo=6AMaAgAAAAARF9M!&tl=3&vuin=1413642083&tm=1574496000&sce=60-1-1&rf=viewer_4''鬼灭之刃'')

- 图片alt就是显示在图片下面的文字，相当于对图片内容的解释。
- 图片title是图片的标题，当鼠标移到图片上时显示的内容。title可加可不加
## 6.超链接的使用
[超链接名](超链接地址 "超链接title")
title可加可不加
### 例如：
- [谷歌](http://google.com)
- [百度](http://baidu.com)
## 7.表格的使用
表头|表头|表头
---|:--:|---:
内容|内容|内容
内容|内容|内容

第二行分割表头和内容。
文字默认居左
-两边加：表示文字居中
-右边加：表示文字居右
注：原生的语法两边都要用 | 包起来。此处省略
## 8.代码写入
语法：
单行代码：代码之间分别用一个反引号包起来
- `create database hero;`
- (```)
    function fun(){
         echo "这是一句非常牛逼的代码";
    }
    fun();
(```)
## 9.流程图写入
st=>start: Start
i=>inputoutput: 输入年份n
cond1=>condition: n能否被4整除？
cond2=>condition: n能否被100整除？
cond3=>condition: n能否被400整除？
o1=>inputoutput: 输出非闰年
o2=>inputoutput: 输出非闰年
o3=>inputoutput: 输出闰年
o4=>inputoutput: 输出闰年
e=>end
st->i->cond1
cond1(no)->o1->e
cond1(yes)->cond2
cond2(no)->o3->e
cond2(yes)->cond3
cond3(yes)->o2->e
cond3(no)->o4->e
