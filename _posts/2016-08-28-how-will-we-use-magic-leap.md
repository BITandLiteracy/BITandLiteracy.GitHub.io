---
layout: post
title: 我们将如何使用 Magic Leap？
categories: VR
---

*VR 和 AR 不仅是显示技术上的一场革命，更是交互技术上的一场创新。讨论完 Magic Leap 所用的显示技术，[JONO MACDOUGALL](http://gpuofthebrain.com/?author=57693419cd0f6883c0e01c34) 又专门写出一篇文章来讨论交互技术的未来：[The Interface of the Future: How will we use Magic Leap?](http://gpuofthebrain.com/blog/2016/7/28/interface-post) 基于对鼠标、键盘的类比，本文全面分析了 Magic Leap 基于眼神、手势、语音以及脑电波等形式的交互设想，值得一读。*

***

新技术的出现往往会带来新的交互范式。这种基本层面的范式不会经常改变，本质上它们是绑定在硬件的性能上的。随着技术的发展，我们倾向于选出一个核心的交互界面，然后在此基础上来把我们所喜爱的产品开发出来。在早期的计算中，我们是用打印机和穿孔卡片。而后，[“演示之母”](https://www.youtube.com/watch?v=yJDv-zdhzMY)把未来的样子示范给我们看：屏幕、鼠标和键盘。这几个概念的影响力是如此之强大，以致于将近半个世纪之后我们仍旧在使用它们。最近，触摸屏，特别是电容式触摸屏，已在推动整个的智能手机革命。[Wayne Westerman 和 John Elias](https://en.wikipedia.org/wiki/FingerWorks) 把这项技术带给全世界，并为苹果和 Google 这样公司打造出现代化的智能手机铺平了道路。

当前，我们正处在一个能够亲眼见证越来越接近的下一代技术变革的罕见时刻。除却电子游戏领域的任天堂差不多每5年都会做出某种古怪的东西之外，很难想象近期内我们还能见证另一场此种程度的技术变革，同时还能在它来临之前就能对它有过反复的思考。

混合现实即是这场变革中的一项技术。在本文中，我想疯狂地猜测一下该技术的核心交互范式的可能方式。我将如何选择自己所关心的信息？我们将如何来输入文本？我们将如何来浏览用户界面的不同部分？当然，我将会专注在 Magic Leap 上面，但我想先用别的产品作为开头。即 Hololens。

## Hololens

先等一下。它不是一项正在接近的技术变革。它已经是一项现成的技术了。你花3000美元就能买来开发者版的 Hololens，并且现在就能开始去研究它。这样我们在混合现实技术上就有了一个切实可用且深思熟路的交互界面来供我们进一步讨论。

<img src="http://geekview.cn/ueditor/php/upload/image/20160828/1472378690230641.gif" alt="" />
`期望未来能看到更多这样的交互`

某种程度上吧…

Hololens 还不是一款消费级产品。它是一项尚在进行中的工作。看一看相关的文章、视频，似乎连微软自己都承认，尽管该技术的前景是惊人的，但其产品尚未成熟到足以面向消费者发售。这就是说，其交互界面看起来是经过深思熟虑的，而我觉得 Magic Leap 也将以类似的方式进行操作。

Hololens 是以用户头部的位置和方向来确定他们的视线方向的，而非通过他们的眼睛。

Hololens 有三种不同的[交互](https://developer.microsoft.com/en-US/windows/holographic/development_overview)途径：眼神、手势和语音。为把它们同我们如今所用的技术广泛地联系起来，我们可以把眼神想象成鼠标，把手势想象成鼠标按键，同时再把语音视为键盘输入。

说实话，我比较担心这样的交互范式。我们都清楚语音交互用起来有多烦人。我们都尝试过 Siri 和 Google Now，紧接着就决定不会再用它们了，除非是某些有利于语音输入的特定情况。如果 Wii / Kinect / Playstation Move 的存在能够证明出一点什么的话，那就是基于动作感应的输入方式到底能有多糟糕。我们对使用语音输入和动作手势感到不快的原因，是在于其在交互反馈上的毛病。语音输入用起来总是很慢。直到把话说完，你才能知道系统是否正确地识别出了你所说出来的话。即便它在90%的情况下都能正确工作，那10%令你沮丧不已的使用情况就足以让你彻底放弃掉它。动作手势也有着同样的问题。你很难去判定系统到底是真能识别出你的动作，还是它只是在缓慢地加载这次识别的结果。如果鼠标和键盘也是如此之不可靠的话，我们就将面临同样的问题，但它们事实上是计算机上面相应最为灵敏的一部分。想象一下，如果你的打字速度比字符被显示出来速度还要快的话，那你使用电脑的过程就极为挣扎了。而被证明最少的眼神，或许是最具潜力的一个。

## Magic Leap

那么，我们还能怎么做？说实话，我也不知道。眼神、手势和语音是目前解决交互问题的最明显办法，我期待 Magic Leap 能优化好它们。也许他们唯一所能做的，就是尝试让这些输入手段尽可能像鼠标或键盘那样可靠。我们已经看到了这样的迹象。Magic Leap 需要做到帧与帧之间高精度的眼球追踪才能实现完整的光场显示。而这里面的技术刚好可用于交互界面中的眼神部分。我能想象的是，在你很简单地浏览界面的同时，就能以某种方式选取其中的可交互部分。如今，我们早已实现了这一点。有一个叫 [Tobii](http://www.youtube.com/watch?v=p4KXAMKvy1E) 的公司已经在为你的笔记本做眼球追踪。

<img src="http://geekview.cn/ueditor/php/upload/image/20160828/1472380220593134.gif" alt="" />

它所展示的是消费者今天所能买到的眼球追踪技术，尽管是以一种相当不同的实现形式。而鉴于 Magic Leap 离眼睛的距离，相比 Tobii 要近上很多，不难猜测出它们的效果要好上很多。如果它确实能做到高度精确的话，它在可靠性上也有可能做到跟鼠标一样，从而减轻我们对于交互界面的眼神部分的一切担忧。

当然，你是不会想一下子选取自己所看到的一切东西的，于是眼神就必须同类似于 Hololens 的“隔空点击（airtap）”的动作手势结合起来使用。这在 Magic Leap 的专利文件中已得到确认，下图就是专利文件中所列的一些交互手势。

<img src="http://static1.squarespace.com/static/5769341bf7e0ab978ac733a5/t/579e8f35d482e9b11598d98f/1470009146395/" alt="" />

手势和语音输入是许多公司都已投入了大量的资源所致力于解决的问题。我不会想象 Magic Leap 独自就能极大程度地改善该问题的现状。事实上，他们反倒有可能在初代产品上解决该问题的效果会比其他公司更差。我觉得即便是那样也没多大问题，只要他们起码能处理好其中的一个手势就行。他们亟需可用的隔空点击（airtap）手势。可以想象，这将是我们在增强现实场景中同周围物品进行交互的主要方式。如果无法确保这一点足够可靠的话，该系统无论做成什么样子都将是令人沮丧的。

上面的专利图中还展示出了另一项极为重要的交互，也就是 Home 键。被交互界面搞混是很容易的，所以像 Windows 的开始菜单或智能手机的 Home 键，就成了你找回熟悉界面所必不可少的方式。

## Totems 

Magic Leap 的[专利文件](http://appft.uspto.gov/netacgi/nph-Parser?Sect1=PTO1&Sect2=HITOFF&d=PG01&p=1&u=%2Fnetahtml%2FPTO%2Fsrchnum.html&r=1&f=G&l=50&s1=%2220150016777%22.PGNR.&OS=DN/20150016777&RS=DN/20150016777)广泛谈论了一种名为图腾（totem）的概念。

> “（图腾是）用户用以操作的实体物品，用以在 AR 系统中进行输入或交互。这样的实体物品在这里被称为图腾（totem）。有的图腾可能是些无生命的物品，例如，一块金属或是塑料、一面墙，以及桌子的一面。或者，有的图腾可能就是生命体，例如用户的手。”

从这一描述可以看出，Magic Leap 所指的图腾可以是它所能识别出来的任何东西。它描述过的很多图腾都是空白板。径直在普通物品上投射全息影像就能给予它们生命。其中的一个例子就是在一块空白矩形上投影一个键盘。另一个例子则是空白鼠标。既然图腾的维度与属性都是已知量，从属于图腾的简单手势识别应该也是可以的。

<img src="http://static1.squarespace.com/static/5769341bf7e0ab978ac733a5/t/57a0de33c534a57eb079e408/1470160448432/" alt="" />
`软键盘图腾示意图。值得一提的是，这里的按键可能并非是实体的，而只是投射在一块软垫上的全息图。`

图腾的关键似乎是把实体物品上交互传递给全息图的能力。它们被描述为空壳、无用的形体，只有当全息环境投射到上面时它们才真正有用。一个特别有趣的例子是，专利文档给出了一份如何把空白铝板变成智能手机的概述。

> “该 AR 系统可以把安卓手机的用户界面渲染到一块铝板的表面。系统还可以检测所渲染出来的虚拟用户界面上的交互动作，例如通过前置摄像头来实现出针对这些交互动作的功能。”

所以，你是从这里第一次听说到此事：你的下一台智能手机很有可能是块铝板。

## 更为狂野的想象

Magic Leap 所选的是一条少有人走的路。所以，回顾一下我们不断从他们那里所听到的说法，他们正在做的事情究竟能有多疯狂？专利文件中有一段话暗示了一种跟迄今所描述过的交互方式完全不同的交互。他们正在做一种不一样的头戴设备。这可能是有史以来第一次有公司以某种合理的方式来把脑电波用在其产品中。相关专利内容如下：

> “该系统可测量神经信号，并以其来作为系统的输入信号。该系统配有可追踪大脑信号的传感器，并将该信号同相应的命令映射表进行比对。换句话说，用户所输入的正是他自己的想法，该想法可通过用户的大脑信号测量出来。这可被视为某种默读感知技术。这一系统还包括一套能够感知脑电波数据的设备，用来把用户的“想法”翻译成系统已破译好的大脑信号。”

该内容是列在专利文件最后，差不多是一个作为事后想法的位置。我不认为他们真会去尝试实现这一“默读感知技术”。至少，是不会出现在初代产品上。


via: [GPUoftheBrain](http://gpuofthebrain.com/blog/2016/7/28/interface-post)