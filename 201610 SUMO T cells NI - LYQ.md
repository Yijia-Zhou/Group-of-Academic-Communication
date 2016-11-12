# 李迎秋老师主讲文献阅读会回顾

先说声抱歉，因为老师ppt损坏过了好一阵才发过来，结果就撞上了负责写这篇回顾的辣鸡要连着考好几场考试，于是一拖再拖，姗姗来迟…… ╮(╯＿╰)╭ 

再次重复一下，本次文献阅读会主题文献为我院李迎秋老师在**Nature Immunology**上发表的论文*TCR-induced sumoylation of the kinase PKC-θcontrols T cell synapse organization and T cell activation*, 链接为[http://www.nature.com/ni/journal/v16/n11/full/ni.3259.html](http://www.nature.com/ni/journal/v16/n11/full/ni.3259.html) ，如无全文权限可以到*链接: https://pan.baidu.com/s/1c86S0m密码: 57gm* 下载pdf

篇幅有限且水平不足，回顾相比起老师的讲授可谓简陋，不过主要的内容还是基本都覆盖到了的，请放心

（直到你看到最后一句，哼哼

---

阅读会一开始，李老师非常照顾姿势水平还不够高的同学们，直接帮大家复习了一下T细胞和B细胞的知识，由于实在找不到高中教材上那张经典的图，这里就放张类似的吧，相信大家都还能想起这是哪部分内容吧

![img](http://www.pep.com.cn/gzsw/jshzhx/jxyj/kchjc/201306/W020130606347132899672.gif)

体液免疫中，B细胞的激活需要抗原/抗原呈递细胞和辅助性T细胞(Th cell, or T helper)的帮助，今天我们的主角就是其中一种，TH2细胞。

---

B细胞的激活需要Th细胞的帮助，不过Th细胞本身也是要在被激活状态才会去激活B细胞的（免疫系统的调控无比复杂而精密）。负责激活Th细胞的还是我们可爱又可敬的抗原呈递细胞，Th细胞和抗原呈递细胞会形成一个“突触”(synapse)，膜蛋白互相识别、作用，最终导致Th细胞被激活。而这个突触，又是个结构灰常复杂、非常难搞的家伙，为T细胞综合处理上游信号立下了汗马功劳。不多说，看图

![Curr top microbiol immunol, 2010l](http://upload-images.jianshu.io/upload_images/3072722-7b690494f7f421a1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

诶诶，先别晕，看到那个在最中间那一圈(c-SMAC, c for central, SMAC是指这个结构是由多个分子组成的用来激活的装置)里的PKCθ了吗？这篇文章的故事，就是从它开始的。不过讲故事之前，先看看PKC的身世

![Paste_Image.png](http://upload-images.jianshu.io/upload_images/3072722-8d9b44642b970e5a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

Protein Kinase C, 简称PKC, 是一种蛋白质激酶，负责根据上游指示给靶蛋白加上磷酸基团，使它们被激活或失活。而PKCθ是PKC的一种，在T细胞中大量表达，喜欢待在T细胞突触里，并且在T细胞表面受体(TCR)被激活后会去激活下游的一些转录因子之类的蛋白，最终导致T细胞被激活。

好了，背景补完了，我们可以讲故事了～

---

话说李老师当年，有一次拿PKCθ跑电泳，结果发现——诶，好像有点不对啊

![Fig. 1A](http://upload-images.jianshu.io/upload_images/3072722-24c4ab149d9059a9.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

怎么个不对法呢？PKCθ的分子量应该是70kDa左右，可是跑出来发现出现了一大堆83kDa以上的条带。当时泛素化（把一种叫做泛素的小蛋白连接到目标蛋白质上，是一种重要的蛋白质修饰）已经被发现在免疫系统调节中起到非常重要的作用，可是与之类似的SUMO化（有多类似呢？SUMO就是Small Ubiquitin-like Modifier的意思，而Ubiquitin就是泛素，名字的意思就是和泛素很像─.─||）还没有相关研究，而SUMO蛋白分子量正是12kDa左右，这不正好吗？于是回国之后（当时李老师在美国）老师顺理成章地开始研究PKCθ是否受到SUMO化调控。

---

首先要严谨地证明一下PKCθ确实被SUMO化了（前面只是推测），这时候就要用到针对SUMO蛋白的特异性抗体来检测PKCθ跑出来的胶（就是所谓图里写的'IB'技术）

![Sumoylation of PKC-θ in primary human CD4+T cells under stringent conditions](http://upload-images.jianshu.io/upload_images/3072722-431ad2bb2e7070e6.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

当然科学研究嘛，总是不嫌更小心严谨一点的，IB检测有时会出现假阳性，也就是明明没有的东西偏偏被“检测”出来了。假阳性产生的原因多种多样，不过我们应对的手段就是一个——我们要检测啥，耍点手段把它干掉，然后在同样条件下再检测一次，如果信号是真的，这时候它就该销声匿迹了，而如果是假阳性的话，可就要路出马脚了。

这里我们用一种SUMO蛋白酶把SUMO蛋白水解了再跑一次

![SENP1 decreased TCR-induced PKC-θ sumoylation](http://upload-images.jianshu.io/upload_images/3072722-be09b46ba204b55c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

嗯，那条带果然不见了，真醒目<(￣3￣)> 

---

现在我们知道了PKCθ会被SUMO化，不过PKCθ有那么多氨基酸残基，SUMO化究竟发生在哪呢？找蛋白质修饰位点最主流的方法就是用质谱技术，这里也不例外，不过打质谱前先要用一些化学方法处理一下，让连接了SUMO蛋白的地方生成一个容易被质谱检测出来的基团

![Identification of sumoylated residues of PKC-θ by tandem mass spectrometry (MS)](http://upload-images.jianshu.io/upload_images/3072722-bd3edff9c89c1d16.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

于是我们找到了5个SUMO化位点，都是赖氨酸残基（赖氨酸三字母简写为lys, 单字母简写为K），按照它们在肽链上的顺序分别编上号就成了K***(见上表)。

可是五个位点是不是都很重要呢？把它们一个个突变成别的不能被修饰的氨基酸试试看(R for remove)

![Lys325 and Lys506 are major PKC-θ-sumoylation sites](http://upload-images.jianshu.io/upload_images/3072722-1a3cc51af91157e9.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

好像把第325位和第506位的赖氨酸去了就整个蛋白都不好了（不能被SUMO化了），特别是俩一起干掉(2KR), 跑出来基本上一点带都没有了，而另外三个似乎影响不大。说明这两个才是关键的修饰位点，另外三个就比较路人了。

---

不知道你意识到没有，前面的研究都只是说PKCθ会被SUMO化，但是SUMO化和它的生理功能到底有没有关系就不知道了。不过上面的2KR兄为我们提供了一个完美的研究材料，把T细胞里的PKCθ换成2KR~~高清重置~~版，然后看看功能还正常否，不就一切都解决了？(此处使用的是敲除了PKCθ的细胞，用质粒把它转回去。EV, 空质粒，啥也没有，用来空白对照；WT, wild type, 野生型，也就是正常型的意思)

![PKC-θ(2KR) did not restore  T cell activation in Prkcq−/− primary mouse CD4+ T cells](http://upload-images.jianshu.io/upload_images/3072722-f37222da9b4b96f5.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

图里很明显啦，转了俩主要位点都被干掉了的2KR版的PKCθ的细胞跟没转差不多，都没法被激活，而转了正常PKCθ的细胞则很正常的生龙活虎。

（此处好几个实验都是验证这个结论的，就略过不表了。）

---

看过了上面的结果，估计大家正常的思维都会觉得SUMO化对PKCθ的活性很必要，没SUMO的PKCθ没有酶活，可是真的是这样吗？实验发现，有没有被SUMO化的PKCθ的催化活性并没有什么区别，而且都能被正常招募到免疫突触中，但是嘛

![Sumoylation of PKC-θ was not required for its recruitment to immunological synapse but was required for its localization to the cSMAC, as well as the localization of CD28 to the cSMAC](http://upload-images.jianshu.io/upload_images/3072722-38e257fbecf31002.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

这张图是用荧光显微镜拍的，绿色荧光标记的是PKCθ, 红色则是免疫突触中也是待在中心位置的一种重要膜受体CD28, 正常PKCθ和CD28聚是一团火，而2KR版、没法被SUMO化的PKCθ和CD28就聚少离多了（还好没到散是满天星的地步）。原来SUMO化影响的是PKCθ和其它蛋白在免疫突触中的共定位。

![PKCθ-2KR was significantly more diffuse than wild-type PKC-θ in the immunological synapse](http://upload-images.jianshu.io/upload_images/3072722-8a76a29240b91c82.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

这张图里的点表示的是PKCθ散开的程度，一目了然，不言而喻。

为了避免氨基酸突变本身对PKCθ带来的影响，换成敲除掉一些SUMO化相关的酶再来一次

![Knockdown of PIASxβ altered PKC-θ immunological synapse localization](http://upload-images.jianshu.io/upload_images/3072722-3c2e04c943583eb6.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

嗯，一样一样的。

---

那么这种区别是如何出现的呢？还是让抗体发挥一下威力

![2KR mutation impaired the PKC-θ’s association with CD28 and filamin A](http://upload-images.jianshu.io/upload_images/3072722-7672bd407a0afa6c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

红圈圈出来的地方，IP是免疫沉淀，用这种蛋白的抗体去把这种蛋白及和它一起玩耍不愿分开的蛋白一起拉下了，然后用前面提到的IB(免疫印迹)技术显色（不过这里是用YFP标记了PKCθ然后再上抗YFP的抗体，因为YFP抗体是标准化的，比较便宜……）。APC + SEE就是一些激活T细胞表面那些受体的东西(APC就是抗原呈递细胞啦)，可以看到正常的PKCθ在用这些处理5分钟后都会和CD28和filamin A在一起，而2KR版的PKCθ可就没朋友了。

等等，filamin A又是什么鬼？

记得科学研究是站在巨人(/前人)的肩膀上，以前的研究已经发现filamin A是一种对免疫突触的正确组装非常重要的细胞骨架蛋白，于是试试看是不是和它也有关系，哎，一试就准。

接着就是套路，把用2KR PKCθ改成敲除SUMO化相关酶再来一次，这里就不放啦，还是看张好看的荧光显微镜的图

![T cells expressing PKC-θ(2KR) displayed a disorganized immunological synapse with impaired pSMAC localization of filamin A.](http://upload-images.jianshu.io/upload_images/3072722-6283c5a404abe932.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

老情况，正常PKCθ聚是一团火，2KR版的……这回真是散是满天星了。

---

当然李老师真正讲的时候不止说了这些写在纸上的东西，还有一开始没有细胞房时数据难看，投*Molecular Cell*被非常干脆地拒收，后来痛定思痛，一步步把整个实验平台建起来了之后拿着漂亮的数据直接去投更好的*Nature Immunology*的故事等等。提问环节问题一个接一个，老师感叹了一阵大家读文献如此认真将来必成人才，而大家对李老师的讲授也评价非常高。可是来的同学总共才十几个，真是叫好不叫座，本来老师还讲了Result的*PIASxβ is a SUMO E3 ligase for PKC-θ*部分的，反正比较独立、跟其它部分关系不那么密切，不写了，想知道的自己看文献去吧，叫你们不来，哼<(‵^′)>



