#Markdown基本语法

>*Markdown 是一种方便记忆、书写的纯文本标记语言，用户可以使用这些标记符号以最小的输入代价生成极富表现力的文档.*

### 1. 粗体和斜体(文字两边均添加`**`和`*`分别代表文字粗体和斜体)

语法：`**粗体**` 
效果： **效果**

语法：`*斜体*`
效果： *斜体*

----------

### 2. 分级标题

使用 === 表示一级标题，使用 --- 表示二级标题。

示例语法：

```
这是一个一级标题
===

这是一个二级标题
---

### 这是一个三级标题
```

效果：

这是一个一级标题
===

这是一个二级标题
---

### 这是一个三级标题


你也可以选择在行首加井号表示不同级别的标题 (H1-H6)，例如：# H1, ## H2, ### H3，#### H4, 以此类推。

----------

### 3. 外链接

使用 `[描述](链接地址)`为文字增加外链接。

示例：

这是去往 [Markdown在线编辑器](https://www.zybuluo.com/mdeditor) 的链接。

----------

### 4. 无序列表

使用 *，+，- 表示无序列表。

示例语法：

```
* 第一行
* 第二行
* 第三行
+ 第四行
+ 第五行
- 第六行
```

效果：

* 第一行
* 第二行
* 第三行
+ 第四行
+ 第五行
- 第六行

----------

### 5. 有序列表

使用数字和点表示有序列表。

示例语法：

```
1. 有序列表第一行
2. 有序列表第二行
3. 有序列表第三行
```

效果：

1. 有序列表第一行
2. 有序列表第二行
3. 有序列表第三行

----------

### 6. 文字引用

使用 > 表示文字引用。

示例语法：

`> 你是我的小呀小苹果`

效果：
> 你是我的小呀小苹果

----------

### 7. 行内代码块

使用 \`代码` 表示行内代码块。

示例：

让我们聊聊 `html`。

----------

### 8.  代码块

使用 四个缩进空格 表示代码块。

示例：

    这是一个代码块，此行左侧有四个不可见的空格。

----------

### 9. 高亮代码(用三个连续的\`来将代码内容包括起来)
示例语法：
\```
代码
\```

效果:

```python

import datetime


def Hello():
    print "Hello, world!"
    return datetime.datetime.now()
```

或者插入log神马的：

```
I/VOLOG   (32481): 17:59:48.533 @@@VOLOG,   Info, 08040000, 4006AFFC, voCMediaPlayerInit.cpp, SetParam, 826, VOMP_PID_DRAW_VIEW old 0x00000000, new 0x80B4ABF0
I/VOLOG   (32481): 17:59:48.533 @@@VOLOG,   Info, 08040000, 4006AFFC, voCMediaPlayerInit.cpp, SetParam, 1341, VOMP_PID_VIDEO_RNDNUM 6
I/VOLOG   (32481): 17:59:48.534 @@@VOLOG,   Info, 09030000, 4006AFFC, COSNdkVomePlayer.cpp, SetParam, 370, @@@## SetParam nID 0X00000010 pValue 0xbeb8ae0c
I/VOLOG   (32481): 17:59:48.534 @@@VOLOG,   Info, 09030000, 4006AFFC, COSNdkVomePlayer.cpp, Init, 135, Finish Init
I/VOLOG   (32481): 17:59:48.534 @@@VOLOG,   Info, 09030000, 4006AFFC, OnStreamjni.cpp, onstream_player_nativeOnLog, 1254, @@@voVideoRender, setStatus - , status is 0 .
I/VOLOG   (32481): 17:59:48.534 @@@VOLOG,   Info, 09030000, 4006AFFC, OnStreamjni.cpp, onstream_player_nativeOnLog, 1254, @@@voVideoRender, setStatus + , mStatus is 0 .
I/VOLOG   (32481): 17:59:48.535 @@@VOLOG,   Info, 09030000, 4006AFFC, OnStreamjni.cpp, onstream_player_nativeOnLog, 1254, @@@voAudioRender, voAudioRender Construct
I/VOLOG   (32481): 17:59:48.535 @@@VOLOG,   Info, 09030000, 4006AFFC, voAudioRenderjni.cpp, NativeAudioRender, 124, ENCODING_PCM_8BIT is 3
```

### 10. 插入表格
示例：
```
| V2         | Ericsson  | TVB     |
| --------   |  -----:   |  :----  |
| Sony C6833 | OK(3/3)   | NG(3/3) |
| S5         | OK(3/3)   | OK(3/3) |
| Tab S      | OK(3/3)   | OK(3/3) |
```

效果：

| V2         | Ericsson  | TVB     |
| --------   |  -----:   |  :----  |
| Sony C6833 | OK(3/3)   | NG(3/3) |
| S5         | OK(3/3)   | OK(3/3) |
| Tab S      | OK(3/3)   | OK(3/3) |