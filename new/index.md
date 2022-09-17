# 软件工程笔记1


# 软件工程笔记

1. 软件工程无处不在  
  &ensp;&ensp;&ensp;软件工程分为软件和工程两个部分。 软件是软件工程研究的对象，也是软件工程的产品形态与客观存在。*工程*是将理论和知识应用于实践的科学，其目的是经济有效地解决实际问题。软件工程是为了解决开发成本效益和软件质量的问题而产生的。倡导以工程的原理和原则进行软件的开发，用系统的可控的和有效的方式构建高质量的软件产品。

2. 软件的本质特性  
   &ensp;&ensp;&ensp;软件的定义:&ensp;软件 = 程序 + 数据 + 文档
  - 程序 ：计算机可以接受的一系列指令


3. 软件具有复杂性、一致性、可变性、和不可见性等固有的内在特性，这是造成软件开发困难的根本原因

  - 复杂性：&ensp;软件可以说是人类创造的最复杂的物体.

  - 一致性：

  - 可变性：

  - 不可见性：

4. 软件工程的产生与发展

  - 软件开发面临哪些主要的问题:
  
&ensp;&ensp;&ensp;正是因为软件开发的过程中会遇到很多的困难，因此软件工程应运而生

软件工程致力于探索软件开发问题的解决之道

5. 软件工程的发展史

&ensp;&ensp;&ensp;1968年，北大西洋公约组织（NATO）召开国际会议， 提出“软件工程”概念和术语。

 

6. 软件工程的基本概念

  - 工程的含义:
    &ensp;&ensp;&ensp;⼯程是将理论和知识应用于实践 的科学，以便经济有效地解决问题。

  - 什么是软件工程

    &ensp;&ensp;&ensp;软件工程是 ① 将系统性的、规范化的、可定量的方法应用于软件的开发、运行和维护， 即工程化应用到软件上；② 对①中所述方法的研究

  - 软件⼯程的目标 —— 创造“⾜够好”的软件

  - 软件工程的过程

  - 软件工程方法

    &ensp;&ensp;&ensp;面向服务：在应用表现层次上将软件构件化，即应用 业务过程由服务组成，而服务由构件组装而成。 OOD OMT UML SASD

    &ensp;&ensp;&ensp;面向过程：以算法作为基本构造单元，强调自顶向下 的功能分解，将功能和数据进行一定程度的分离。

    &ensp;&ensp;&ensp;面向对象：以类为基本程序单元，对象是类的实例化， 对象之间以消息传递为基本手段。

    &ensp;&ensp;&ensp;面向构件：寻求比类的粒度更大的且易于复用的构件， 期望实现软件的再工程 。

   - 软件工程工具

   - 软件开发的基本策略

```软件开发的基本策略有软件复用，分而治之，逐步演进，优化折中
软件复用：构造一个新的系统不必从零做起，直接复用已有的构件进行组装构件是经过反复使用验证的，由其组成的新系统具有较高的质量。

软件复用不仅仅是代码复用，还包括 库函数、类库、模板（文档、网页等）、 设计模式 、组件 、 框架

分而治之：将一个复杂的问题分解成若干个简单的问题，然后逐个解决来源于人们生活与工作的经验，完全适合于技术领域

逐步演进：软件更像一个活着的植物，其生长是一个逐步有序的过程。软件开发应该遵循软件的 客观规律，不断进行迭代式增量开发，最终交付符合客户价值的产品。

优化折中：软件工程师应当把优化当成一种责任，不断改进和提升软件质量；但是优化是一个多 目标的最优决策，在不可能使所有目标都得到优化时，需要进行折中实现整体最优。```

优化：优化软件的各个质量特性，如运行速度、资源利用、用户体验

折中：通过协调各个质量特性，实现整体质量的最优

1.6业界人士谈软件工程

业界人士如何看待软件工程

在软件开发的过程中遇到的最大的困难是如何让大家并行地一起工作和一起解决，这就是软件工程涉及到的项目管理和项目协同地概念。

软件工程的开发不是一个人的工作，是很多人把自己的智慧和代码集合在一起，软件工程让很多人把自己的使用习惯都归结成一些规则，让每个人写出来的代码都是同样的思维，同样的思路，看起来像一个人写出来的代码，这就是设计模式。

业界人士认为程序员最重要的四个素质

1、拥有极强的代码的阅读和理解的能力，以及书写代码的能力

2、有极强的责任心和责任感，对整个软件产业的敬畏之心（对前人和用户的体验的敬畏，自我反省，自我提升）

3、有职业道德，对代码的品质的保证和对整个公司秘密的保护

4、需要有和其他程序员协同的能力，人与人之间的相处，人与人之间如何交换自己的代码，开发的心得，开发的经验

小结

第一章主要是学习软件工程的基本概念，听下来对最后一节颇有感触，结合我之前惨痛的组队经历，我认为程序员还应该具有以下几个素质。

首先是有抗压的能力。软件作为目前人类历史上最复杂的工程，不可能是一蹴而就的，开发的过程中肯定会遇到许许多多没有见过的问题的，这种时候我们更应该迎难而上，而不是遇到问题就开始自暴自弃，这不光光是对自己写的代码的不负责任，还是对其余组员的不负责任。

其次还需要有规律的作息。这一点看似非常的无厘头，但是却非常的重要，在软件开发的过程中，团队的协作，沟通是非常重要的，我们有固定的工作时间可以进行讨论，但是如果有人的作息和别人不同，那会大大增加合作的难度。比如说有一些夜猫子可能晚上比较精神，凌晨5点睡觉，然后上午醒来基本就到了饭点，吃完午饭再睡一个午觉，那基本就失去了面对面沟通进度，交流合作的机会了。

此外还需要有积极的学习的态度。对于一个程序员而言，某些知识没有掌握其实并不可怕，毕竟人无完人，没有人可以什么都会，只要有活到老学到老的精神，给他一点时间总能学会的。但是如果一个人开始摆烂，没有积极的学习的态度，那他就被这个行业淘汰了。再之前的组队经历中，另一位同学的代码基础较差，但是却没有上进心，每天都在打游戏，大好的时光就这么被挥霍了，令人痛心。

最后是需要对别人的代码有敬畏之心。如果说上述的三点素质没有的话，那也就算了，但这最后一点是必不可少的。如果说实现自己的模块需要修改别人的代码，还是希望能够仔细阅读或者询问写下这段代码的人，而不是随意修改别人的代码，导致别人的模块无法使用，出现新的bug。

以上这四点全部来源于我的亲身经历，可能写的有些偏激了，希望大家都不会碰到上述的情况，也希望大家的软件工程能够越学越好。