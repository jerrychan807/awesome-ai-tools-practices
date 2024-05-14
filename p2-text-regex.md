# 需求:

对一大段文本做格式化处理,取其中部分文本

初始文本:
```js
P1
001 Start Here First (Important Course Details)
03:30
P2
002 Meet Your Instructors
01:40
P3
003 Sneak Peak of What's to Come!
01:23
P4
001 What We'll Learn About Using ChatGPT
04:17
P5
002 ChatGPT vs. Google
04:19
...
```

目标文本:
```js
001 Start Here First (Important Course Details)
002 Meet Your Instructors
003 Sneak Peak of What's to Come!
001 What We'll Learn About Using ChatGPT
002 ChatGPT vs. Google
...
```

# 一般思路:

处理文本一般都会想到正则表达式，例如使用网站:https://regex101.com/

# 工具:

ChatGPT

# 示例:

![20240515033437](https://raw.githubusercontent.com/jerrychan807/imggg/master/image/20240515033437.png)    
输入文本后,要求ChatGPT对以上内容,过滤出只含英文的行。

# 效果:

![20240515033448](https://raw.githubusercontent.com/jerrychan807/imggg/master/image/20240515033448.png)

# 启发:

可替代,正则表达式