---
layout: post
title: 《rules of play》笔记 1-13
date: 2019-1-28
Author: Zafara
tags: [学习笔记]
comments: true
toc: true

---

## 第一部分：Core concept

### 第一章:what is this book about.

 建立术语表。
 反对泛游戏定义与试图给出无比精确的定义。作者指出，游戏作为一种culture phenomenon应该从多个角度来评判，如游戏设计、文化意义、娱乐价值等等。
  此后，作者提出用3个Schema来分析游戏：rules、play、culture。用MDA模型来说，前两者分别是机制（系统）与动态（玩家体验）。culture含有部分美学，也有更多层次的社会文化意义。 
  游戏的设计基础包含很多，摘抄一句话：

They include the powerful connection between the rules of a game and the play that the rules engender，the pleasure games invoke，the meaning They construct，the ideologies They embody，and the stories They tell.
 

### 第二章：the design process

 迭代设计思想（iterative design）：原型、测试、分析、修改。不断迭代循环改进。
 大学几年的软件工程思想熏陶，以及亲自设计桌游的经历，深深明白这种设计思想重要性并已运用在实际中。
 整章用了一个设计师设计魔戒桌游（没在bgg找到对应名字的桌游）的过程，由于亲自体会过设计桌游且没玩过这款，基本没啥收获。
  不过强调测试时要尽可能尝试各种套路，一方面提高游戏鲁棒性和保证平衡性，另一方面则需要让专家玩家和新手玩家都有玩的乐趣。 

 

### 第三章：meaningful play

the goal of successful game design is meaningful play.

 虽然提到了胡伊青加的理论，这里的meaningful play偏向于机制上的理念，meaningful应该被理解为「游戏内行为意义」，而非「游戏」的意义。

 在这个基础上，meaningful play有两种方式定义。从单纯的性质定义，可以大概简略为：从玩家行为和系统反馈中浮现的一种抽象存在。

 从分析比对角度，即一款游戏的play有多meaningful，可以从两个角度：discernablity（明晰性）和integrated（整体交互性）。前者强调玩家行为反馈的及时、明确、清晰性质。后者强调玩家行为在游戏整体角度中存在功用，并与其他系统机制交互有关联。

 就个人理解，这里的meaningful play主要指代玩家在游戏中行为是否有游戏内意义（高层文化意义在这个定义下不作为重点探讨，虽然会涉及）。例如辐射4的建造系统，由于和其他系统交互较差，和主线关系不大，所以意义较低。

 



### 第四章：Design

 Design is a process by which a Designer creats a context to be encountered by a participant，from which meaning emerges.
 the context of a game takes the form of spaces、objects、narratives、behaviors.
 
 人们追求意义，而符号学是构筑意义的重要理论。符号学本质是研究意义产生的学科。（索绪尔的著作）
 基于charles pierce的理论，符号有四个基础性质
 \1. 符号代表着非它之外的某种事物
 \2. 符号需要被解读
 \3. 符号解读后应产生有意义结果
 \4. 上下文影响解读
 
 1- 游戏设计基于符号为游戏产生意义的行动（action）和反馈（outxome）赋予可理解的意义。游戏的单元机制和交互内容可被符号化理解（例如填词游戏中，nigger只是个无意义但有游戏内在价值：可得分的有序字母串，但在游戏环境外：context的不同下，就是种人种侮辱性词语），游戏自身整体也可被视为一种符号。
 
 2- 基于索绪尔理念，符号的意义是被赋予的，尤其语言中词汇意义是约定俗成而来。换句话说，游戏内也可以强制设定符号意义。
 
 3- 在一个系统中，符号只有被解释后存在系统内意义，这个符号本身才有意义。
 
 4- 符号所处的环境会影响如何被解读
 
 一个符号的意义源于它所在的系统
 所以总结来说，游戏设计师设计的是什么（design的内容）：系统（游戏的context）

 

### 第五章：systems

  a system is a set of parts that interrelate to form a complex whole. There are many ways to frame a game as a system：a mathematical system，a social system，a representational system，ect.
  系统理论涉及到控制论思想。
  系统四要素：objects、attributes、internal relationship、Environment
  基于对某个系统的定义和frame不同，四要素也有所不同。对于游戏来说，有三种主要的：formal（游戏自身规则系统）、experiential（游戏参与人在游戏中的动态体验系统）、culture（具体游戏在整个大文化系统）。三个层次环环嵌套，前者被后者包含。在进行分析时，虽然三层系统同时存在，但在具体分解决某个设计问题时最好聚焦于某个层次。并且设计游戏时，尤其需要理解这三个系统层次之间怎么交互。
  系统可以是开放和闭合两种属性的系统，区别在于系统是否和外界环境存在交互。formal是闭合系统，culture是开放系统，而experiential可闭合可开放。

 

### 第六章：interactivity

 interactivity is closely linked to the concepts of design，system，and meaningful play. When a player interacts with the designed system of a game，meaningful play emerhes.
  交互性可以用四个模式的交互来定义，而非用一个单一概念概述所有。
  cognitive interactivity：玩家心理、情感、思想与系统的交互
  functional interactivity：物理配件、GUI、外界系统与玩家的交互
  Explicit interactivity：游戏内系统机制交互
  beyond the object interactivity：例如游戏进行这个行为自身与在整个文化系统上的交互
  虽然存在四种交互，不过大多时候它们同时作用。在游戏设计中，格外关注第三种交互，也一般把它默认为核心设计的交互内容。
  并非所有交互都是designed interaction.当一个interaction被设计时，它具有内在结构和在系统上下文中含有独特意义。例如单纯扔出沙包这个交互行为不是designed interaction，但如果设定投掷的目标、需求和评判标准（例如某条线后投掷，得分为垂直距离这条线的距离米数），这个行为就被赋予了系统的含义。
  交互内容常伴有选择（choice），选择可以是宏观和微观，并且完全可以是二者不同程度的结合。
  交互意义的基础是「行动— 结果」单元。基于这种基础单元，游戏设计师从而设计出更大层次的交互系统。
  每个「行动— 结果」基础单元通过五个步骤构筑选择：
  \1. 玩家进行选择前拥有的信息
  \2. 选择可能的结果如何传达给玩家
  \3. 玩家如何进行选择
  \4. 选择的结果
  \5. 选择结果如何传达给玩家
  其中134为系统内部的机制设计内容，25则属于需要和玩家交互的内容。
  游戏设计师设计的是可能性空间（the space of possibility），而非具体的游戏过程（play）。
 The space of possibility is designed (it is a constructed space, a context), it generates meaning (it is the space of all possible meanings), it is a system (it is a space implied by the way elements of the system can relate to each other), and it is interactive (it is through the interactive functioning of the system that the space is navigated and explored). 
 
 
 关于为何只是看别人玩游戏，没有资格对游戏进行整体评价。
 
 One of our disappointments with current writing on games and interactivity is that much analysis occurs not from the point of view of the player, but from the point of view of an outside spectator. This style of over-the-shoulder journalism fails to recognize that interactivity is something to be experienced, rather than observed. 

 

### 第7章：defining Games

 别的书中已经学的比较详细，这里只摘下总结
 The words play and games have a unique relationship in the English language. There are two ways to frame their relationship, both of which are useful: 
 
 Games are a subset of play: The category of play represents many kinds of playful activities. Some of these activities are games, but many of them are not. In this sense, games are contained within play. 
 
 Play is a subset of games: Games are complex phenomena and there are many ways to frame them and understand them. RULES, PLAY, and CULTURE are three aspects of the phenomena of games. In this sense, play is contained within games. 
 
 A game is a system in which players engage in an artificial conflict, defined by rules, that results in a quantifiable outcome. The key elements of this definition are the fact that a game is a system, players interact with the system, a game is an instance of conflict, the conflict in games is artificial, rules limit player behavior and define the game, and every game has a quantifiable outcome or goal. 
 
 A puzzle is a special kind of game in which there is a single correct answer or set of correct answers. All puzzles are games. 
 
 Multiplayer Role-playing games (RPGs) do not clearly possess a quantifiable outcome. Whether or not they fit the definition of a game depends on how they are framed. As with other open-ended game-like experiences such as Sim City, RPGs have emergent quantifiable goals but usually no single overriding outcome. 

 

 

### 第8章：defining digital games

 There are four traits that summarize the special qualities of digital games. These traits are also present in non-digital games, but digital games generally embody them more robustly: 
 
 Trait 1: Immediate but narrow interactivity 
 
 Trait 2: Manipulation of information 
 
 Trait 3: Automated complex systems 
 
 Trait 4: Networked communication 

 

### 第9章：the magic circle

 任何一个游戏存在一个由时空组合的边界，并通过边界确定一个玩家是否真正在玩一个游戏
 魔法圈（the magic circle）是游戏发生的抽象空间，在魔法圈内玩家搁置质疑，并认同游戏规则和虚构空间下的一切事物意义。
 魔法圈的重要性在于我们难以划分「玩」的边界，但通过明确的魔法圈定义，可以辅助进行设计和思考
 作为一个系统，游戏基于不同看待的视角，可被视为开放或闭合系统
 lusory attitude是一种愿意进入游戏的状态，在这个状态下参与人愿意以非效率的方式达成某件事情，并得到基于此产生的乐趣。

 

### 第10章：The primary schemas

 schemas可以视为一种知识体系和框架，用来承载和系统化联系知识，而非定义。
 The conceptual framework for this book provides three ways to frame or understand games: RULES, PLAY, and CULTURE. Each of these primary schemas contains a number of more specialized schemas. 
 
 RULES contains formal game design schemas （游戏内部系统化结构和可用数学语言分析）
 
 PLAY contains experiential game design schemas （游戏动态过程和营造的体验，都以玩家的角度来谈，即玩家与游戏和经过游戏与其他玩家的交互）
 
 CULTURE contains contextual game design schemas（游戏与整个文化系统的联系，文化对游戏的影响和游戏对文化的影响）
 
 （culture（play（rules）））3者的包含嵌套关系

 

## 第二部分:Rules

### 第11章: Defining rules

 规则构建游戏内部结构，与玩家体验无关（人为分割的无关）。与现实世界的规则区别在于游戏世界的规则是人为塑造且仅适用于游戏内的时间，不对外部世界产生直接影响。
 规则特性：
 \1. 限制玩家行为
 \2. 具体且不模糊
 \3. 所有玩家公认
 \4. 规则不会被轻易改动
 \5. 规则有强制性
 \6. 规则可重复
 尽管有些游戏的规则一定程度不符合某几条特性，但总体来说特性如上所说。

 

### 第12章：Rules on three levels

 一个游戏的规则由3层次组成，这三个层次互相交互并合力构成游戏规则的体验。

Constituative rules（自己补充：可以理解为底层数学模型） are the abstract, core mathematical rules of a game. Although they contain the essential game logic, they do not explicitly indicate how players should enact these rules. 

 

Operational rules（自己补充：可以理解为实际显性的，规则书字面写的规则） are the "rules of play" that players follow when they are playing a game. Operational rules direct the players' behavior and are usually the kinds of rules printed out in instructions and rulebooks for games. 

 

Implicit rules are the "unwritten rules" of etiquette and behavior that usually go unstated when a game is played. Similar implicit rules apply to many different games. 

 

 三个层次之间分界线并不明晰，分析借鉴意义较重。尤其是operational和implicit rules，需要基于用户群体和实际情况进行调整，是否指明某些implicit rules。一个operational rules建立在特定的constituative rules，然而一套constituative rules可以对应多种不同的operational rules

 

 一个游戏的formal identity可以把一款游戏与其他游戏区分开（formal层面），并且这个identity依靠Constituative和Operational rules组成。建立游戏的formal identity最重要的一步是具体化规则，清晰明确的规则是让游戏之所以成为对应这款游戏的理由。

 

 在3层规则中有translation发生，并且魔法圈是这个translation的context。优雅的规则可以让玩家集中于规则带来的体验，而非规则自身。设计出meaningful play需要3个层次上都在行动和结果上建立易辨析和完整的关系。

 

 书中给出了个例子，3字棋和3-15的关系。3-15的规则是两名玩家轮流从1~9中选择一个未被任何人选择的数字，谁先用3个数字到达15谁获得胜利。这两个游戏虽然在operational rules层面差别巨大，但是在constituative rules层面是极其相似的。因为1~9可以组成一个任意行/列/斜线和为15的幻方。如果游戏注重于数学计算和记忆，那么3-15的形式好于前者，否则就是糟糕的设计。换句话说，具体使用什么operational rules需要依据游戏想塑造什么体验和目的。

自己补充，这两个游戏即使在constituative rules也不等价，因为3子棋的棋盘上可以超过3个子并仍旧能胜利，而3-15则不可能。

 

 自己补充：另外基于implicit rules的理念，可以在设计桌游时有更清晰的思考。有些规则默认所有玩家都能遵守，而没必要无限制的详细列出。但有些规则由于对于这款游戏格外重要，需要把它具体明确说出来。比如在《银河卡车司机》中，设计师明确列出了在抢夺零件板块需要注意的细节规则。虽然没有列出所有可能性，比如没有禁止玩家攻击其他玩家，因为任何桌游玩家都能默认遵守这条规则。同时把一些可能模糊的规则明确列出，比如不允许把板块放到太远的位置或者随便选个朝向放回去。

 

### 第13章：The Rules of Digital Games

规则和代码有联系，但并不等同。整体来说，电子游戏和非电子游戏的规则共同在于指导玩家的行动和行动后的结果，因此涉及这部分内容的程序代码为游戏规则。同时内部构成游戏运行代码的也是规则。画面和音频通常不作为规则一部分，除非它们对规则机制有直接影响（而非体验）。

电子游戏的constituative rules和非电子游戏的无太大区别，同样是构成核心机制的代码，并只关注internal events(参考c6，即系统内部处理内容)。而operational rules则不仅包括internal events，还有external events（和玩家交互的内容，游戏的I/O）。至于implicit rules，和非电子游戏一样有很多模糊之处。同时玩弄一些大家默认为准则的implicit rules可以带来有趣的创新。

自己补充：例如《undertale》对存档机制的元游戏设计，通过违背存档shell意义的设计理念，来使得游戏世界被塑造的更加可信。

 

最重要的是，理解电子游戏的规则具体定义是什么，和规则三层结构如何运用在电子游戏上的目的不是具体区分它们。而是为了让设计师、玩家和游戏评论人员能够更加清楚地了解游戏的核心机制和内核系统具体是什么，也是让设计师可以用最小代价实现出最接近成品游戏核心机制体验原型的思想基础。
