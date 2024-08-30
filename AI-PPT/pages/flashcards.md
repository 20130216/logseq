- [[#red]]==background-image::==空格后+图片链接（必须是网上的链接，不能是本地图片链接），是本页幻灯片播放的背景图
- background-image:: https://q2.itc.cn/q_70/images01/20240807/653cb43fe2cd4aaeb5b86a2c5d906821.jpeg
-
-
-
- 输入：\/cloze，然后填入隐藏答案，形式呈现为 \{{cloze 隐藏答案}}
  background-color:: red
- 测试flashcards的第一个问题 #card
  card-last-score:: 5
  card-repeats:: 1
  card-next-schedule:: 2024-08-30T09:13:49.093Z
  card-last-interval:: 4.14
  card-ease-factor:: 2.6
  card-last-reviewed:: 2024-08-26T06:13:49.093Z
	- 第一个问题的答案
- 这个是 {{cloze 第二个问题的}} 完整 {{cloze 有效}} 答复 #card
  card-last-score:: 5
  card-repeats:: 1
  card-next-schedule:: 2024-08-30T09:13:52.426Z
  card-last-interval:: 4.14
  id:: 66c038c7-4b4c-4268-a5dd-11695da57b44
  card-ease-factor:: 2.6
  card-last-reviewed:: 2024-08-26T06:13:52.426Z
- id:: 66c03b33-0d72-4a35-95dd-2b9dc9c35d1e
-
- 子块中输入隐藏答案
  background-color:: red
- 测试flashcards中的分类的第一个问题#flashcards分类测试 #card
  card-last-interval:: 4
  card-repeats:: 2
  card-ease-factor:: 2.22
  card-next-schedule:: 2024-08-26T08:04:07.637Z
  card-last-reviewed:: 2024-08-22T08:04:07.637Z
  card-last-score:: 3
	- 第一个分类问题的答案
- 这是 {{cloze  第二个分类问题的}}答复#flashcards分类测试 #card
  card-last-interval:: 4.14
  card-repeats:: 1
  card-ease-factor:: 2.6
  card-next-schedule:: 2024-08-30T09:13:55.194Z
  card-last-reviewed:: 2024-08-26T06:13:55.195Z
  card-last-score:: 5
-
- \{{cards }} 呈现所有闪卡(作用相当于点击左侧：记忆卡片)；
  background-color:: red
  选择所有闪卡后左上角可以点击选择具体页面的闪卡：
	- {{cards }}
	-
-
-
-
- \{{cards [[PDF及flashcards]] }} 呈现这个页面的闪卡：
  background-color:: red
- 格式为：{{cards [[#green]]==标签名或页面名==}}
- {{cards [[PDF及flashcards]] }}
-
-
-
-
-
-
- 图片闪卡制作见：[[PDF及flashcards]]
-
- #+BEGIN_NOTE
  \/cloze    “完形填空”命令，把要遮掩的内容放在命令后；
  
  \/cards[[类别]]        
  注意：
  1）/命令后是cards；
  2）标签\#命令后是card (相当于点击块中的“Make a FlashCard”)
  
  #+END_NOTE