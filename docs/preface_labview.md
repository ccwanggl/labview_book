# 什么是 LabVIEW

## LabVIEW 编程语言

LabVIEW 是美国国家仪器有限公司（National Instruments, NI）最核心的软件产品。LabVIEW 是一种编程语言，与其它常见的编程语言相比，最大的特点就在于它是一种图形化编程语言。

我们常见的编程语言如 C、Java、Python 等，都是文本编程语言。它们的使用领域和方法虽然各不相同，但都有一个共同特点：即都是使用字母构成单词，用单词表示某个数据或对数据的某种操作；再由单词构成语句，用语句表示对某个数据的赋值、计算等操作。这几种计算机语言都借鉴了人类的自然语言，尽管它们比自然语言要简略、死板、严谨，但是它们的词法、语法等概念和自然语言是相同的。

文本编程语言是一种高度抽象的语言。它的优点是效率高，用简短的文字就可以表达丰富的含义。它的缺点也很明显，文本不够直观，也不容易学习。在使用文本语言编程之前，必须花费较长的时间学习并熟记其关键字、数据的表示方法、语法等等。字母构成的关键字和函数是不容易记忆和阅读的，对于中国人来说，记住这些英文单词也许更加费劲。文本语言的上下文相关性也比较紧密，仅仅阅读程序中的某一段代码往往无法理解其意义，必须从头到尾阅读整段代码才能了解其逻辑关系。比如说，代码中使用了一个变量，但这个变量中的数值是从哪里来的？接下来又会在哪里被使用？文本语言往往并不能直观地给阅读者提供类似的信息。只有通篇阅读完、并弄懂全程序之后才会了解这些数据变化的过程。

与计算机交互，人们普遍更喜欢图形化的交互方式。比如程序的界面，早期的 DOS 系统下的应用程序，使用的都是文本方式在人机间交互。在屏幕上显示出一行提示文字，再等用户输入相关的命令或数据。而后来的 Windows 系统下的应用程序则采用了图形化界面，用户主要通过拖拽和点击鼠标与计算机进行交互。这两种方式受欢迎程度的差别是非常明显的 —— 如今，除去专业领域，大众普遍使用的应用程序都是图形化界面的。

很多高级编程语言在进行程序界面设计时，都引进了可视化设计的方式，或者叫所见即所得的设计方式。编程者不需要敲入文本命令，直接使用鼠标就可以选择和调整应用程序的界面，直接看到程序运行时的效果。但是，这样的编程语言仍不能被称为图形编程语言，因为它们在设计界面时虽然采用了图形方式，但程序功能依然需要通过文本编程来实现。

LabVIEW 不仅在界面设计中采用图形化方式，连程序功能的实现也通过图形化操作完成。打开 LabVIEW 的程序，看到的不是一行行的文本，而是由一条条彩色线段连接起来的、各式各样的小图形块。这是一种完全不同的编程方式。由于图形比文字更为直观，LabVIEW 比其它编程语言更适合初学者学习。一个对计算机软件完全不了解的初学者，通常只需学习两三天的时间，就可以随心所欲地编写一些简单的程序了。这是其它编程语言学习者无法想象的。

LabVIEW 的编程效率之高也是文本编程语言所无法比拟的。LabVIEW 拥有丰富的工具包，尤其是针对测控、仿真等领域，这些工具包往往可以为编程者提供其所需的大部分功能。因此，在 LabVIEW 程序中，有时几个简单的图形和连线，就能够完成文本语言中几十行甚至上百行代码才能完成的功能。

## G 语言

G 语言是图形化编程语言（Graphical Programming Language）的缩写。LabVIEW 不是唯一的图形化编程语言，但它是当今最完善、功能最强大的一种图形化编程语言。因此，LabVIEW 几乎成为了图形化编程语言的代名词 —— LabVIEW 有时也被称为 G 语言。我们可以这样理解，LabVIEW 是一种开发环境（类似的，Visual Studio 也是一种开发环境），在这个环境下编写的代码就是 G 语言代码（类似于在 Visual Studio 下写出的 C 代码）。

LabVIEW 常常被误认为是一种仅应用于工业测控领域的应用软件，而不算作是一种编程语言。误解的原因有两个：首先是因为它和其它常见的编程语言完全不同。初次见到 LabVIEW，人们很容易联想到电路板布线、工业总线配置等应用软件；其次，LabVIEW 主要被使用在测控领域，很多用户对它还缺乏了解。

既然是一门编程语言，在使用 LabVIEW 的时候，就应该按照程序设计的思维来考虑。使用 LabVIEW 开发软件与使用其它语言的开发过程是相同的。一般来说，都需要经历以下五个步骤：收集需求、设计、编码、测试、发布及维护。如果有其它计算机语言的使用经验，是会对学习 LabVIEW 语言有一定帮助的。但是，在学习 LabVIEW 的时候，需要格外注意图形化编程语言与文本编程语言的差异之处，有些文本语言的使用经验不能直接套用在 LabVIEW 上。本书在介绍 LabVIEW 时，会提及 LabVIEW 区别于其它文本编程语言的独特之处，并将它与其它文本编程语言进行对比，以帮助文本编程语言的程序员注意到这些区别。

对于那些把 LabVIEW 作为第一门计算机编程语言学习的读者而言，今后再继续学习其它语言时，也可参照这些区别之处。

## LabVIEW 的应用领域

LabVIEW 编程语言有很多优点，尤其在某些特定领域，它的优势更加明显。因此，当需要在这些领域开发计算机软件时，可以优先考虑 LabVIEW。

测试测量：LabVIEW 最初就是为进行测试测量而设计的，因而测试测量也就成为了当前 LabVIEW 被应用得最为广泛的领域。经过多年的经营，LabVIEW 在测试测量领域获得了广泛的支持。至今，大多数主流的测试仪器、数据采集设备都拥有专门的 LabVIEW 驱动程序，使用 LabVIEW 可以非常便捷地控制这些硬件设备。同时，用户也可以方便地找到各种适用于测试测量领域的 LabVIEW 工具包，这些工具包几乎覆盖了用户所需的所有功能。用户在这些工具包的基础上再开发程序就容易多了。有时甚至于只需简单地调用几个工具包中的函数，就可以组成一个完整的测试测量应用程序。

控制：控制与测试是两个相关度非常高的领域，从测试领域起家的 LabVIEW 自然而然地首先拓展至控制领域。LabVIEW 拥有专门用于控制领域的模块：LabVIEW
DSC。除此之外，工业控制领域常用的设备，数据线等通常也都带有相应的 LabVIEW 驱动程序。使用 LabVIEW 可以非常方便地编写各种控制程序。

仿真：LabVIEW 包含了多种多样的数学运算函数，特别适合进行模拟、仿真、原型设计等工作。在设计机电设备之前，可以先在计算机上用 LabVIEW 搭建仿真原型，验证设计的合理性，找到潜在的问题。在高校教育领域，有时受条件限制，无法完成课程中提及的与某些硬件相关的实验。这时如果使用 LabVIEW 进行软件模拟，几乎可以达到同样的效果，使学生不致失去实践的机会。

儿童教育：由于图形外观漂亮且容易吸引儿童的注意力，同时图形比文本更易于被儿童接受和理解，所以 LabVIEW 非常受少年儿童的欢迎。对于没有任何计算机知识的儿童而言，可以把 LabVIEW 理解成是一种特殊的 "积木"：把不同的原件搭在一起，就可以实现自己所需的功能。著名的可编程玩具 "乐高积木"，使用的就是 LabVIEW 编程语言。经过短暂指导，儿童可以用乐高积木搭建各种模型，并用 LabVIEW 编写程序控制它们的运动和行为。除了应用于玩具，LabVIEW 还有专门用于中小学生教学使用的版本。

快速开发：根据我对自己所参与的一些项目的统计，完成一个功能类似的大型应用软件，熟练的 LabVIEW 程序员所需的开发时间，大概只是熟练的 C 程序员所需时间的五分之一左右。所以，如果项目开发时间紧张，应该优先考虑使用 LabVIEW，以缩短开发时间。

跨平台：如果同一个程序需要运行于多个硬件设备之上，也可以优先考虑使用 LabVIEW。LabVIEW 具有良好的平台一致性。LabVIEW 的代码不需任何修改就可以运行在常见的三大台式机操作系统上：Windows、macOS、Linux。除此之外，LabVIEW 还支持各种实时操作系统和嵌入式设备，比如常见的 PDA、FPGA，以及运行 VxWorks 和 PharLap 系统的 RT 设备。

## LabVIEW 的发展历史

美国国家仪器有限公司（NI）成立于 1976 年。公司创立之后，一直致力于将传统的测试测量仪器与个人电脑相连接。当时，传统仪器上最主流的 I/O 接口是 GPIB (General 
Purpose Interface Bus) 接口。而 NI 公司早年最成功的产品正是个人电脑上的 GPIB 接口卡，通过这块插卡，传统的测试测量仪器与个人电脑实现了数据通信，在个人电脑上即可以读取仪器测量到的数据，也可以发送命令控制仪器的操作。因此，NI 的工程师们很自然的就开始考虑如何开发一款软件，更方便灵活的操控硬件，同时也就有更强大的数据分析展示能力。

在公司成立的第十个年头，也就是 1986 年，NI 发布了一款名为 Laboratory Virtual Instrument Engineering Workbench（实验室虚拟仪器工作台）的软件，它的缩写名就是 LabVIEW。

LabVIEW 1.0 是在当时最时髦的个人电脑：苹果机上开发的。苹果电脑首次把图形化操作界面带到了个人电脑上，受其鼓励，NI 的工程师也把 LabVIEW 设计成了全图形化操作的方式。那时的苹果电脑 CPU 采用的是摩托罗拉 68000。LabVIEW 1 与之后的 LabVIEW 语言都不同，它是解释型语言。语法和功能都相当简单，比如：每个函数只能用于一种类型的数据；唯一的数值类型是浮点数等。

LabVIEW 1.1 中引入了 LabVIEW 的一个重要优化技术：缓存重用。LabVIEW 程序采用的数据流驱动方式，最大的效率隐患就是产生了过多的数据拷贝。采取缓存重用机制，LabVIEW 会尽量减少不必要的数据复制、利用已有的内存控件，从而大大提高的 LabVIEW 的效率。直到今天，LabVIEW 程序员在为自己的程序做内存优化时，主要考虑的依旧是如何有效利用 LabVIEW 的缓存重用机制。

LabVIEW 2.0 最重要的革命性改进是它使用编译器代替来原来的解释器，LabVIEW 从此变成编译型语言了。它首先把一段程序编译成为针对摩托罗拉 68000 CPU 机器码，然后再运行。这样执行速度就有了质的飞跃。LabVIEW 2.0 在编译程序时同时会对程序做语法检查，比如：把两个不同数据类型的控件连在一起，LabVIEW 会给出相应错误提示。LabVIEW 2.0 另外一项重大的创新是开始支持并行计算。当时的 LabVIEW 并不支持多线程，但是，它在程序内部实现了类似多线程的调度（类似文本编程语言中常见的异步调用方式）。LabVIEW 会把代码中没有先后顺序依赖的部分分成不同的 “模块”，然后快速交替执行各个模块，让它们在宏观上看起来是并行执行的。

LabVIEW 跨平台是从 LabVIEW 2.5 开始的。在这个版本中，它首次开始支持 x86 架构的 CPU。此后，LabVIEW 从未放弃过对跨平台的支持。在后续的版本中，LabVIEW 陆续开始支持 PowerPC 以及其它一些主流 CPU。至今，LabVIEW 仍是支持最多平台和操作系统的编程语言之一。这也给 LabVIEW 带来了一些麻烦。最明显的就是 LabVIEW 开发环境的界面风格与一般的 Windows 应用程序有些格格不入：面板是深灰色的，按键的 3D 效果也与众不同。看惯了 Windows 的各种界面，可能会觉得 LabVIEW 有些别扭。这都是因为 LabVIEW 要考虑到对其它平台的支持，就不能简单地调用 Windows 已经实现的各种界面元素。还有一些可能不太容易被发现的差异。比如，LabVIEW 在整数存储上，即便运行于 x86 系统，也仍采用 big-endian（高字节在低地址）方式。big-endian 是早期苹果电脑 CPU 采用的数据存储顺序，但却与目前最常见的 x86 CPU 使用的格式正相反。这往往会给编写存取二进制文件的程序带来一些麻烦。

LabVIEW 3 中出现了属性节点和局部变量等新功能。这时，已经有用户开始开发多达上千个 VI 的大型程序了。 

LabVIEW 4 是笔者接触到过的最早的 LabVIEW 版本。它的发布包是一个装有十几张三寸软盘的大盒子。安装的时候要按顺序把软盘一个一个塞到计算机里。尽管当时 LabVIEW 的界面并不好看，但笔者还是非常喜欢它。真方便呐！比如要画一个开关，把控件选板上现成的控件一拖过来就好了。当时还没有任何一个文本编程语言实现了类似的可视化界面设计功能。如果要自己动手用 C 语言设计一个如此好看的开关，那得花多少时间啊！我尤其喜欢它通过连线来编程的方式，尽管很多熟悉了文本编程语言的人刚开始会对这种图形化的编程方式非常不适应。

LabVIEW 5 开始引入了一项新的模块 GenAPI，用以更有效的支持多种硬件设备。GenAPI 可以生成多种 CPU 的程序执行代码，这样一来，LabVIEW 就具备了交叉编译的能力，比如在一台 x86 的电脑上，可以编译出在 RT 设备上运行的程序。LabVIEW 5.0 的另一项重大改进是它开始支持多线程了。

LabVIEW 6  添加了立体效果控件、事件响应及网络编程支持。
LabVIEW 7 中添加了 Express VI，以及对于 FPGA、DSP 等嵌入式设备编程的支持。

LabVIEW 8 针对于编译器最主要的改进是优化了 CPU 寄存器的分配机制。在此之前，LabVIEW 采用固定的模式为数据分配寄存器，LabVIEW 8 开始采用了动态分配方式。同时 LabVIEW 8 的编译器也开始加入优化方式，比如移除无效代码分支等。LabVIEW 8 在工程管理方面添加了工程库和面向对象编程的新功能。

LabVIEW 2009 是编译器改进比较重大的一个版本。首先，它加入了 64 位的编译器，可以生成 64 位的执行程序。再有，它开始对 LabVIEW 的编译器分层化。首先细分出来的是 DFIR（Dataflow Intermediate Representation）- 位于程序框图和可执行代码之间的逻辑表达层。有了这样一层中间层，LabVIEW 编译器可以做更多的优化工作了，比如：常数合并，无效代码删除，循环内不变代码移出等。

LabVIEW 2010 中，编译器在 DFIR 与机器码之间又细化出一层：LLVM（Low-Level Virtual Machine），底层虚拟机。在这一层上，编译器可以进行如：指令调度，循环判断条件外提，指令组合，以及更复杂的寄存器分配等优化。2010 在已有的 DFIR 层上也引进了新的优化方式，比如：运算结合，公共子表达式消除，循环展开，以及子 VI 内联等。

从 2011 年开始，NI 公司逐步将开发的重心转移到了 LabVIEW NXG 上。这是一个准备用来取代 LabVIEW 的全新设计的图形化编程语言。然而 LabVIEW NXG 并没有赢得用户的支持，2020 年，NI 宣布停止开发 LabVIEW NXG。在这十年间，由于投入资源有限，LabVIEW 并没有太大的技术更新，更多的是小的修修补补。

2020 年，NI 公司推出了社区免费版 LabVIEW，极大方便了业余爱好者进行学习和研究。

2023 年，NI 公司被艾默生（Emerson）公司收购，LabVIEW 易主。
