---
title: Linux系统
---
# **Linux系统**
## **什么是Linux系统?**
Linux是一套免费使用和自由传播的类Unix操作系统。

---
## **Linux系统的特点**

1. 模块化程度高

           Linux的内核设计非常精巧，分成进程调度、内存管理、进程间通信、虚拟文件系统和网络接口五大部分;其独特的模块机制可根据用户的需要，实时地将某些模块插入或从内核中移走，使得Linux系统内核可以裁剪得非常小巧，很适合于嵌入式系统的需要。

2. 源码公开(多用户、多任务、支持多线程和多CPU)(支持32位和64位硬件)

           由于Linux系统的开发从一开始就与GNU项目紧密地结合起来，所以它的大多数组成部分都直接来自GNU项目。任何人、任何组织只要遵守GPL条款，就可以自由使用Linux 源代码，为用户提供了最大限度的自由度。这一点也正投嵌入式系统所好，因为嵌入式系统应用千差万别，设计者往往需要针对具体的应用对源码进行修改和优化， 所以是否能获得源代码 对于嵌入式系统的开发是至关重要的。加之Linux的软件资源十分丰富，每种通用程序在Linux上几乎都可以找到，并且数量还在不断增加。这一切就使设 计者在其基础之上进行二次开发变得非常容易。另外，由于Linux源代码公开，也使用户不用担心有“后闸”等安全隐患。同时，源码开放给各教育机构提供极大的方便，从而也促进了Linux的学习、推广和应用。

3. 广泛的硬件支持

           Linux能支持x86、ARM、MIPS、ALPHA和PowerPC等多种体系结构的微处理器。目前已成功地移植到数十种硬件平台，几乎能运行在所有流行的处理器上。由于世界范围内有众多开发者在为Linux的扩充贡献力量，所以Linux有着异常丰富的驱动程序资源，支持各种主流硬件设各和最新的硬件技术，甚至可在没有存储管理单元MMU 的处理器上运行，这些都进一步促进了Linux在嵌入式系统中的应用。

4. 安全性及可靠性好

           linux内核高效稳定。Linux内核的高效和稳定已在各个领域内得到了大量事实的验证。Linux中大量网络管理、网络服务等方面的功能，可使用户很方便地建立高效稳定的防火墙、路由器、工作站、服务器等。为提高安全性，它还提供了大量的网络管理软件、网络分析软件和网络安全软件等。

5. 具有优秀的开发工具

           开发嵌入式系统的关键是需要有一套完善的开发和调试工具。传统的嵌入式开发调试工具是在线仿真器(In Circuit Emulator，ICE)，它通过取代目标板的微处理器，给目标程序提供一个完整的仿真环境，从而使开发者能非常清楚地了解到程序在目标板上的工作状 态，便于监视和调试程序。在线仿真器的价格非常高，而且只适合做非常底层的调试。如果使用的是嵌人式Linux，一旦软硬件能支持正常的串口功能，即使不 用在线仿真器，也可以很好地进行开发和调试工作，从而节省了一笔不小的开发费用。嵌入式Linux为开发者提供了一套完整的工具链(Tool Chain)，能够很方便地实现从操作系统到应用软件各个级别的调试。

6. 有很好的网络支持

           Linux文件系统支持Linux从诞生之日起就与Internet密不可分，支持各种标准的Internet网络协议，并且很容易移植到嵌入式系统当中。目前，Linux几乎支持所有主流的网络硬件、网络协议和文件系统，因此它是NFS的一个很好的平台。另一方面，由于Linux有很好的文件系统支持(例如，它支持Ext2、FAT32、romfs等文件系统)，是数据各份、同步和复制的良好平台，这些都为开发嵌入式系统应用打下了坚实的基础。

7. 与UNIX完全兼容（基于POSIX和UNIX)(Unix以网络为核心的设计思想)

           目前，在Linux中所包含的工具和实用程序，可以完成UNIX的所有主要功能。但由于Linux不是为实时而设计的，因而这就成了Linux在实时系统中应用的最大遗憾。不过，目前有众多的自由软件爱好者正在为此进行不懈的努力，也取得了诸多成果



*备注：严格来讲，Linux这个词本身只表示Linux内核，但实际上人们已经习惯了用Linux来形容整个基于Linux内核，并且使用  GNU 工程各种工具和数据库的操作系统。*






## **Linux相对于Windows有什么区别?**
* **使用体验的区别**
   * **开源性和软件质量较差**

          windows平台:数量和质量的优势，不过大部分为收费软件；由微软官方提供重要支持和服务。

          linux平台：大都为开源自由软件，用户可以修改定制和再发布，由于基本免费没有资金支持，部分软件质量和体验欠缺；有全球所有的Linux开发者和自由软件社区提供支持。
    * **安全性更高**

          Windows平台：三天两头打补丁安装系统安全更新，还是会中病毒木马什么的，各位用户自己感受。 

          Linux平台：要说linux没有安全问题，那当然是不可能的，不会中病毒什么的，也不可能，这一点仁者见仁智者见智，相对来说肯定比Windows平台要更加安全，使用linux你也不用装杀毒软件了。
* **工作方式的区别**
       
         1. 文件格式不同:windows 操作系统内核是NT，而linux 是 shell；

         2. windows 硬盘文件格式是fat32或NTSF，而linux 需要的文件格式是ext2或ext;

         3. 用户界面不同；

         4. 硬件配置要求不同。你的硬件如果太新或太旧，建议你还是装Windows吧，因为Linus的软件/硬件兼容性还有待提高。


## **Linux的组成部分**
       linux一般由 **内核、shell、文件结构和实用工具** 4个主要部分组成。内核是所有组成部分中最为基础、最重要的部分。


### **1.linux内核**
       内核（Kernal）是整个操作系统的核心，管理着整个计算机的软硬件资源。内核控制整个计算机的运行，提供相应的硬件驱动程序、网络接口程序，并管理所有程序的执行。内核提供的都是操作系统最基本的功能。linux内核源代码主要是用C语言编写的，linux内核采用比较模块化的结构，主要模块包括存储管理、进程管理、文件系统管理、设备管理和驱动、网络通信和系统调用等。linux内核源代码通常安装在/usr/src/linux目录下，可供用户查看和修改。

### **2.linux shell**
       shell是系统的用户界面，提供了用户与内核进行交互操作的一种接口。它接收用户输入的命令并把它送入内核去执行。实际上，shell是一个命令解释器，它解释由用户输入的命令并且把它们送到内核。shell还有自己的编程语言用于命令编辑，它允许用户编写由shell命令组成的程序。shell编程语言具有普通编程语言的很多特点，比如它也有循环结构和分支控制结构等，用这种编程语言编写的shell程序与其他应用程序具有同样的效果。

### **3.linux文件结构**
       文件结构是文件存放在磁盘等存储设备上的组织方法，主要体现在对文件和目录的组织上。目录提供了管理文件的一个方便而有效的途径。我们能够从一个目录切换到另一个目录，而且可以设置目录和文件的权限，设置文件的共享程度。使用linux，用户可以设置目录和文件的权限，以便允许或拒绝其他人对其进行访问。linux目录采用多级树结构，用户可以浏览整个系统，可以进入任何一个已授权进入的目录，访问那里的文件。

### **4.linux实用工具**
       标准的linux系统都有一套叫做实用工具的程序，它们是专门的程序，如编辑器、执行标准的计算操作等。用户也可以产生自己工具。实用工具可分为3类。
1. 编辑器：用于编辑文件。linux的编辑器主要有Ed、Ex、Vi和Emacs。Ed和Ex是行编辑器，Vi和Emacs是全屏幕编辑器。
2. 过滤器：用于接收数据并过滤数据。linux的过滤器（Filter）读取用户文件或其他地方的输入，检查和处理数据，然后输出结束。
3. 交互程序：允许用户发送信息或接收来自其它用户的信息。交互程序是用户与机器的信息接口。



## **Linux都应用在哪些领域?**

1. IT服务器Linux系统应用领域　
 
          如今的IT服务器领域是Linux、UNIX、Windows三分天下，Linux系统可谓是后起之秀，尤其是近几年，服务器端Linux操作系统不断地扩大着市场份额，每年增长势头迅猛，并对Windows及UNIX服务器市场的地位构成严重的威胁。　　
          Linux作为企业级服务器的应用十分广泛，利用Linux系统可以为企业构架WWW服务器、数据库服务器、负载均衡服务器、邮件服务器、DNS服务器、代理服务器(透明网关)、路由器等，不但使企业降低了运营成本，同时还获得了Linux系统带来的高稳定性和高可靠性。　　
 　　

2. 嵌入式Linux系统应用领域　

         　由于Linux系统开放源代码，功能强大、可靠、稳定性强、灵活，而且具有极大的伸缩性，再加上它广泛支持大量的微处理器体系结构、硬件设备、图形支持和通信协议，因此，在嵌入式应用的领域里，从因特网设备(路由器、交换机、防火墙、负载均衡器等)到专用的控制系统(自动售货机、手机、PDA、各种家用电器等)，Linux操作系统都有很广阔的应用市场。特别是经过这几年的发展，它已经成功地跻身于主流嵌入式开发平台。例如，在智能手机领域，Android Linux已经在智能手机开发平台牢牢地占据了一席之地。

3. 个人桌面Linux应用领域　


         　所谓个人桌面系统，其实就是我们在办公室使用的个人计算机系统， 例如： Windows XP、Windows 7、MAC等。Linux系统在这方面的支持也已经非常好了，完全可以满足日常的办公及家用需求，例如：
     * 浏览器上网浏览(例如：Firefox浏览器)。　　
     * 办公室软件(OpenOffice，兼容微软Office软件)处理数据。　　
     * 收发电子邮件(例如：ThunderBird 软件)。　　
     * 实时通信(例如：QQ 等)。　　
     * 文字编辑(例如：vi、vim、emac)。　　
     * 多媒体应用。　　

              虽然Linux个人桌面系统的支持已经很广泛了，但是在当前的桌面市场份额还远远无法与Windows系统竞争，这其中的障碍可能不在于Linux桌面系统产品本身，而在于用户的使用观念、操作习惯和应用技能，以及曾经在Windows上开发的软件的移植问题。　


## **路由器中Linux系统与桌面端有何不同？**

* 路由器中的linux，是一个精简的系统，比如桌面系统用到的窗口系统（x-window）、外壳（各种shell）、应用软件都是不需要的。
* 作为专用设备，驱动程序也不需要通用。为了无头显示、24小时运行，系统配置也做了优化。
* 路由器的cpu是专用的cpu，也有用arm的，mips的等等，而pc用的是x86，所以二进制代码指令也不同。
* 路由器系统为了实现路由的功能，肯定还有很多专用的软件程序，这些程序一般pc不需要。
* 路由器的固件大约只要64MB、128MB就够了，而桌面linux的硬盘往往都是几百GB

---
# **什么是开源软件?**

一句话来说，开源指的是那些源代码或源设计可以被大众使用、修改发行的软件或设计体。

       但开源并不意味着免费，开源只是说我们做了一个好东西，把它开放给大家使用，目的是希望大家更多地使用它，并反馈使用过程中的问题或者改进方式，使得整个开源项目进步得更快，能够更好地共享给更多有需要的人，目前像 Linux、Hadoop、Spark等等，都是这么做的。但很多时候开源背后还是带有很浓厚的商业背景。

       做得比较大的开源项目背后都有商业公司在支撑，如果一个成功的开源项目背后没有商业公司，这是不健康的，我们需要开源和商业之间的互补对称来促进整个社区和技术的不断前进答，这是一方面。

         Linux 无疑是开源软件里最最成功的一个，不管是从它目前的生态建设角度，还是从业界评价来看，包括今天云计算的基础也都倚赖Linux的贡献和基石。当然，像OpenStack、Hadoop 、Spark等也非常成功，这些开源项目都属于底层技术，在支撑今天整个大数据、云计算的发展。
###     **常用的开源社区：**

http://sourceforge.net/

http://www.apache.org/

其他的有些干专项的.
比如 http://www.open-open.com/java开源大全

还有开源文档的满江红开源 http://wiki.redsaga.com/confluence/display/RSTEAM/Home

## **开源软件的五大优点和五大缺点**
 
* 优势1：花费很少（如果有的话），许可费用 　　 当然，这往往省去那些讨厌的维护费用。 　

* 优势2：易于管理 　　只要你想，你可以在尽可能多的地方安装开源软件。无需为许可证合规性计数、跟踪或监视。 　　

* 优势3 ：连续，实时改进 　　因为每个人都可以访问代码，任何人都可以主动修改BUG，使其变得更好，而不必等待下一个版本。 　
　
* 优势4：公司独立 　　如果该公司创建的软件出现故障时，代码仍然可以通过其用户社区继续存在和发展。 　　

* 优势5 ：实践的探索 　　你的IT人员可以很容易地“亲身探索”代码，以便更好地了解产品并作出改善，以最好的服务满足公司的需求。 　　

* 缺点1 ：它不是完全免费 　　开源软件可以涉及意料之外的实施、管理和支持成本。 　　

* 缺点2：学习曲线 　　你可能在开源的产品上需要聘请专家，让你的IT人员加快速度。 　　

* 缺点3：迷茫的用户 　　由于并行发展的努力在进行中，用户可能不知道哪个版本做什么或是否与你专有平台上的其他软件兼容。 　　

* 缺点4：孤立软件 　　由于关键的程序员的斗争和退出，或他们失去兴趣转移到新的项目，使一些开源项目陷于停顿和死亡。　　

* 缺点5：独立地（凭自己的力量） 　　与商业产品不同，没有人在开源社区的义务来帮助你，或回答你的任何问题。

