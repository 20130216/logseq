- 参考视频：{{video https://www.bilibili.com/video/BV1qq4y1k7fN?p=14&vd_source=e13b46e9b43415aab34a87e9281703c7}} 【基础篇】31集 | 零基础学笔记软件logseq
-
- ## **第0部分：快捷键**
	- 调用chatGPT最最核心的快捷键：
	  background-color:: red
	  id:: 66bf51c8-e562-444a-9193-09b061acb12e
	  **/gpt-block ：mod+j**
	  **/gpt popup ：mod+g**
	- 调用[[#red]]==ollma核心的快捷键==
	  id:: 66c9eae4-66f3-409a-a7ee-0090e55323f2
	  **/ollma popup ：shift+mod+o**
	- 调用[[#red]]==面板上所有命令==的快捷键：shift+mod+P
	  id:: 66c9eae4-5147-4686-ae96-99f8448a1d99
	- 最常用的5个快捷键：
	  background-color:: green
	  id:: 66bf51c8-2a00-4b0e-8653-4c363b121f9a
	  1.  待办事项 **切换NOW——>DONE ：mod+Enter**（设置中可以更改默认值为：**TODO——>DOING**）
	  2. **侧边栏打开  向上箭头Shift+Click**
	  3. tab切换：Tab ；反切换：**向上箭头Shift+Tab**
	  4. 在同一个栏目下换行：**向上箭头Shift+Enter**
	  5.**[[#red]]==cmd+句号==  == 点击 块的小圆点** 进入下一级block：细粒度笔记；[[#red]]==cmd+逗号== 回到上一级block；
	  6.[[#red]]==cmd+点击 块内容的任何部分==：选择该块
	  7. [[template和prompt-template]] 通过[[#red]]==[[]]==进入某个页面后，[[#red]]=='cmd+]'==进入页面，[[#red]]=='cmd+['==回退页面
	- 搜索：
	  [[#red]]==搜索块 (())==  ------两个英文小括号     （点击进去后，后面的数字显示被引用的数量）
	  [[#red]]==搜索页面[[]]==
	- / 后的多种状态：
	  /LATER
	  /NOW
	  /DOING
	  /DONE
	  /WAITING
	  /CANCELED
	- /TODO
	  background-color:: red
		- /Deadline
		  /Scheduled
	- 待办事项可以直接先输入TODO，再按shift+Enter内部换行，
	  
	  然后方可执行：Scheduled ；Deadline；
	- [[#red]]==属性的句法 property:: value==
	  id:: 66c9ebec-b2e4-4edb-9664-06cdded284b8
		- [[#green]]==如果不想让链接生效==（只想显示纯文本），加英文双引号
		  id:: 66c9ec44-ff4b-4c29-bcf0-5eff9104267d
		  `句法: 属性名称:: [[页面]]`
	- 动态变量（[[#red]]==百分号和关键词之间有英文空格==）
		- <% 关键词 %>
		  比如：<% today %>
		  常见的动态变量：Today, Tomorrow, Yesterday, Last Friday
			- today => [[Today's journal page]]
			- yesterday => [[Yesterday's journal page]]
			- tomorrow => [[Tomorrow's journal page]]
			- time => Current time，例如 22:44
			- current page => [[Current page]]
			  -自然语言日期（官方文档中提到，一些自然语言也支持动态变量）
			- 17 August 2013 - 19 August 2013
			- This Friday from 13:00 - 16.00
			- 5 days ago
			- 2 weeks from now
			- Sat Aug 17 2013 18:40:39 GMT+0900 (JST)
			- 2014-11-30T08:15:30-05:30
		-
	- `{{embed ((66c9eae4-2c4c-45ab-92e1-73d1f0061a0f))}}`[[#red]]==复制内嵌块==和 [[#green]] ==\/Block embed==,然后[[#green]]==把块引用放到( )==作用一样
	  页面别名：allias:: （可供引用）
	  id:: 66c9eae4-9067-4745-8565-eb38b05689b9
	- 以HTML格式导出页面   pubulic::true
	  id:: 66c05739-993d-49bd-b238-3ba3f95e4271
- ## Markmap related
  collapsed:: true
	- `shift+1`: Switch back to page view.
	- `shift+2`: Switch to hierarchy view.
	- `shift+3`: Switch to linked references view.
	- `space`: fit window in center in case you move or zoom it.
	- `0`: hide all except the central one.
	- `9`: show all.
	- `1`: expand to level 1.
	- `2`: expand to level 2.
	- `3`: expand to level 3.
	- `4`: expand to level 4.
	- `5`: expand to level 5.
	- `+`: zoom in.
	- `-`: zoom out.
	- `h`: level up.
	- `l`: level down.
	- `j`: expand step by step.
	- `k`: collapse step by step.
	- `.`: focus in to children level.
	- `b`: focus out to parent level.
	- `,`: reset to original tree.
	- `n`: focus to next sibling.
	- `p`: focus to previous sibling.
	- `mod+b`: reset theme according to Logseq theme.
	- `ESC` & `q`: close the mindmap.
	- `UP`: move mindmap up.
	- `DOWN`: move mindmap down.
	- `LEFT`: move mindmap left.
	- `RIGHT`: move mindmap right.
	- [[#red]]==`cmd+[`==: go backward.
	- [[#red]]==`cmd+]`==: go forward.
	- `/`: popup keybindings help model.
-
- ## 以下主要来自这个视频：
	- `{{video https://www.bilibili.com/video/BV1qq4y1k7fN?p=14&vd_source=e13b46e9b43415aab34a87e9281703c7}}`  【基础篇】31集 | 零基础学笔记软件logseq（更新ing）
	- `{{video https://www.bilibili.com/video/BV1eq4y1N7Su/?spm_id_from=333.788&vd_source=e13b46e9b43415aab34a87e9281703c7}}`  Logseq 中的查询（2） Query 命令
-
- ## **第0.1部分：有关页面操作**
	- [[#red]]==直接回到目录==：
	  \[[contents]]
	-
	- 新建页面，不要用. / \ 符号
		- 1.0text .../1/0text pages
	- 导入附件 不要带. / \ 符号
		- PDF文档，•2.2xxxxx，edn文件
		- 修改办法：到asserts文件中修改
-
- ## **第0.2部分：query命令**
	- and
	  (and \[[page 1]]\[[раgе 2]])
	  (and (todo now later done) \[[page]])
	- or
	  (or \[[page 1]]\[[page 2]])
	- not
	  (not\[[page 1]] \[[page 2]])
	- between
	  The format (between start end) will only support blocks on the
- 案例：[[research pannel example]]
-
-
-
- ## **第一部分：标题/标签**
  id:: 66cbf313-180d-4131-a3cf-057433a7a53f
- \# 一级标题  \#\# 二级标题   \#\#\# 三级标题  最多支持6级标题；中间有空格
- \#标签名：[[#green]]==中间无空格==，标签和其他内容用空格分割
-
-
- ## **第二部分：针对文字的格式****
  id:: 66bec117-e90f-4be6-b6a7-4b2bf8decbe7
  **加粗**    **  ****
  加粗快捷键**  （command+B）*
  *斜体*    *   *
- ~~删除线~~      ~~  ~~
- ==高亮==      == 紧凑的两边等号，用下滑黄线表示 ==
- ***加粗且斜体***        \***    \***
- ==**加粗且高亮**==      \==**      \**==
-
- ## **第三部分 引用格式**
  > 引用的文字    >引用文字  （加不加空格都行）
  >>>二级引用        >>>二级引用
- >引用1
- > 引用2
-
-
- ## **第四部分 列表**（实践情况：按enter键不会自动生成后续序列）
- 无序列表（*+空格）
- * 项目
  * 项目1
  * 项目1.1
  * 项目1.1
-
- + 项目2
  + 项目2
-
- 有序列表（1.+空格）
- id:: 66bec4f1-f3f4-4a88-a318-9a7c73990c51
  1. 项目1
  2. 项目2
  3. 项目3
-
- ## **第五部分 markdown语法1:代码**
- \`行内代码,比如instance of\`     （esc案件下方，英文格式下\`\`）`instance of`(灰色高亮的展示形态)
- ```
  多行代码
  pubulic void main(String arg[]){
  
  
  }
  ```
- （连续输入3次``    同时第一行和最后一行的` `都要换行）
-
-
- ## **第六部分 markdown语法2:分割线/表格/图片链接/引用**
- **分割线**   （[[#green]]==---==；[[#green]]==***==；[[#green]]==___==）
	- ---
	  分割1
	  ***
	  分割2
	  ___
	  分割3
-
- **表格:  英文的 |**
  id:: 66bec6c3-3b57-48a5-a9ed-5ef88f994693
	- |A|B|C|
	  |1|2|3|
- 网页链接和图片链接  英文[]()   分别填写：网页名称  网页地址
	- [网页名称](www.sina.com.cn)
	-
- 图片名称    ![]() 分别填写：图片名称 图片地址
	- ![图片名称](图片地址)
	-
- 嵌套引用
	- >一级引用            >一级引用
	  >>二级引用        >>二级引用
	  >>>二级引用        >>>二级引用
- 上标 下标 下划线
	- 文字<sup>上标</sup> 
	  文字<sub>下标</sub>    （这两个测试下来不行！）
	-
	- 下划线<u></u>
		- <u>下划线</u>
		-
	- 转义字符        \    \**
	-
	-
	-
- ## **第七部分 < 尖括号的应用 **
- 英文<    Quote
- #+BEGIN_QUOTE
  这是一条笔记
  讲述了湖北恩施的整体布局
  #+END_QUOTE
-
- #+BEGIN_QUOTE
  引用文字
  #+END_QUOTE
-
- 英文<    Tip   Important  Cation Pinned Warning  Center
	- #+BEGIN_NOTE
	  这是一条笔记信息
	  #+END_NOTE 
	  
	  #+BEGIN_TIP
	  这是一条提醒信息
	  #+END_TIP
	  
	  #+BEGIN_IMPORTANT
	  这是一条重要的信息
	  #+END_IMPORTANT
	  
	  #+BEGIN_CAUTION
	  这是一条注意信息
	  #+END_CAUTION
	  
	  #+BEGIN_PINNED
	  图钉标识（要点）
	  #+END_PINNED
	  
	  #+BEGIN_WARNING
	  警告信息
	  #+END_WARNING
	  
	  
	  #+BEGIN_EXPORT latex
	  f(x)=3*x+5
	  #+END_EXPORT
	  
	  
	  代码信息 
	  ``` 
	  begin
	  end
	  
	  ```
	  
	  
	  #+BEGIN_CENTER
	  文字居中
	  #+END_CENTER
	-
	-
	- 行内公式 $a=b$
	  
	  跨行公式 $$a=b$$
	  
	  上标 $$a^2$$
	  
	  $$a^2x+y$$
	  
	  下标 $$a_2$$
	  
	  下标$$a_2x+y$$
	  
	  根号 $$\sqrt{3}$$
	  
	  n次方根 $$\sqrt[n]{3}$$
	-
- 单个字符向量
  id:: 66bb40d4-279a-4f4c-853b-d40f2e28a68d
  $$\vec{a}$$
  
  多个字符向量
  $$\vec{ab}$$
  
  多个字符箭头向右向量
   $$\overrightarrow{abc}$$
  
  多个字符箭头向左向量
   $$\overleftarrow{abc}$$
-
-
-
-
- ## **第八部分：图片**
- 背景图片
  collapsed:: true
	- background-image::     https://q2.itc.cn/q_70/images01/20240807/653cb43fe2cd4aaeb5b86a2c5d906821.jpeg
-
- 图片链接
  collapsed:: true
	- ![image](https://q2.itc.cn/q_70/images01/20240807/653cb43fe2cd4aaeb5b86a2c5d906821.jpeg)
-
- ## **第九部分 在线PDF** （必须是公开可访问的）(不知道怎么回事，可能没有找准pdf的地址，一直都是外链打开)（去他娘的，找到一个正确的PDF地址再说吧）
- \![PDF名称]\(网络地址)
- ![大模型原理与训练过程 - 百度文库 (baidu.com)](https://wenku.baidu.com/view/c36db2c1f31dc281e53a580216fc700aba685215.html?fr=income3-doc-search&_wkts_=1724507805057&wkQuery=%E5%A4%A7%E6%A8%A1%E5%9E%8B){:height 34, :width 335}
-
-
- ![建筑材料在能源领域的应用.pptx_淘豆网 (taodocs.com)](https://www.taodocs.com/p-1090659866.html)
-
-
- [大模型训练流程 - 百度文库 (baidu.com)](https://wenku.baidu.com/view/4fbb5b94f9b069dc5022aaea998fcc22bdd14312?aggId=c36db2c1f31dc281e53a580216fc700aba685215&fr=catalogMain_text_ernie_recall_feed_index%3Awk_recommend_main3&_wkts_=1724508090918&wkQuery=%E5%A4%A7%E6%A8%A1%E5%9E%8B)
-
- \![PDF名称]\(网络地址) 是logseq中上传在线pdf的格式吗？
	- #gpt4o:
	  在 Logseq 中，上传在线 PDF 的格式为 `![PDF名称](网络地址)`。这样可以通过指定的 URL 直接链接并显示 PDF 文件。确保所提供的链接是有效的，并且 PDF 文件可以公开访问。
-
-
-
-
-
-
-
-
-
-
-
-
- logseq中如何用符号来实现无序列表？
	- [[gpt4o-mini]]:
	  在Logseq中，可以使用短横线（`-`）、星号（`*`）或加号（`+`）来实现无序列表。每个符号后面需要跟一个空格。以下是几个示例：
	  
	  使用短横线：
	  ```
	  - 列表项1
	  - 列表项2
	    - 子项1
	    - 子项2
	  ```
	  
	  使用星号：
	  ```
	  * 列表项1
	  * 列表项2
	    * 子项1
	    * 子项2
	  ```
	  
	  使用加号：
	  ```
	  + 列表项1
	  + 列表项2
	    + 子项1
	    + 子项2
	  ```
	  
	  只需在所需的地方输入这些符号和对应的内容，就可以创建无序列表。
-
-
-
-
-
-
-
-
-
-
- logseq在mac中高亮如何显示
	- [[gpt4o-mini]]:
	  id:: 66bebef5-512d-4452-b99f-cd226278053d
	  在 Logseq 中高亮文本的方法如下：
	  
	  1. **使用 Markdown 语法**：在 Logseq 中，可以使用 Markdown 语法来实现高亮。将要高亮的文本用 `==` 包围，例如：`==高亮文本==`。保存后会显示为高亮效果。
	  
	  2. **使用快捷键**：在编辑模式下，选择要高亮的文本后，可以使用快捷键（通常是 `Command + Shift + H`）来快速高亮。
	  
	  3. **调整样式**：如果需要自定义高亮的颜色或样式，可以通过修改 Logseq 的 CSS 配置来实现。找到 Logseq 的设置，进入“主题”或“自定义 CSS”部分，修改相应的样式即可。
	  
	  确保在使用高亮功能时，你处于编辑模式，这样才能正确应用高亮效果。
-
-
-
-
-