- my thought on [[paper]] A is: #research
	- it's awesome!
	- it can be connected with [[paper]] B #idea
-
- ## AND
  id:: 66cc7b79-8346-4a97-a11f-25a2098e57b6
	- {{query (and [[research]] [[idea]])}}
	  collapsed:: true
-
- ## OR
	- {{query (or [[research]] [[idea]] )}}
	  collapsed:: true
-
- ## AND (NOT)
  id:: 66cc81c2-fec9-4e63-9cc2-24d6fcc205f6
	- {{query (and (not[[research]]) [[idea]])}}
	  collapsed:: true
-
- ## AND(between)：
  collapsed:: true
  (between -2d, 0d)；     (between [[Aug 27th, 2024]] [[Aug 27th, 2024]])
  如果\#idea 放在SCHEDULED: 后面，是查不出来的，必须放在块内容标题后面；
	- {{query (and (between -2d, 0d)[[research]] [[idea]])}}
	- {{query (and [[research]] [[idea]] (between [[Aug 27th, 2024]] [[Aug 27th, 2024]]))}}
	-
- logseq query命令中的between有哪些可选项？
  collapsed:: true
	- 在Logseq中使用`logseq query`命令时，你可能会想要查询满足特定条件的节点。`query`命令允许你根据不同的属性来筛选和查找信息。
	  
	  `logseq query`命令的一个重要部分是其语法允许你在查询参数中使用多种逻辑操作符，包括`between`。在Logseq中，`between`用于过滤节点，要求它们的某一个属性值在一个指定的范围之内。
	  
	  `between`关键字通常会与`prop:`结合使用来表示你想要查询的是哪个属性的值。语法可能类似于：
	  
	  ```bash
	  logseq query "prop:status between 1 and 3"
	  ```
	  
	  在这个例子中，我们假设`status`是节点的一个属性，我们可以用它来描述某个任务的状态（比如：待办、进行中、已完成）。这个命令会返回所有状态在1到3之间的记录。
	  
	  请注意：
	  
	  - `between`操作符需要两个参数作为其范围的边界值。你可以根据你的需求选择整数值或日期时间等。
	  - `and`, `or`和`not`等逻辑运算符可以与`between`和其他查询条件一起使用，以构建更复杂的过滤表达式。
	  
	  确保检查Logseq官方文档或社区指南，了解所有可用的操作符、属性名以及如何在不同的场景中正确应用它们。这些资源通常会提供详细的示例和推荐的用法，帮助你更有效地进行信息检索和管理。
-
-
-
-
-
-
-