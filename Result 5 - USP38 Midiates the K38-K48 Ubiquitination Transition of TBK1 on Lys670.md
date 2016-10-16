# Result 5 - USP38 Midiates the K38-K48 Ubiquitination Transition of TBK1 on Lys670

在介绍这个result之前，回顾一下summary中的一句话

> Knockdown or knockout of USP38 increases K33-linked ubiquitination, but it abrogates K48-linked ubiquitination and degrdation of TBK1, thus enhanceing type I IFN signaling.

﻿而从题目中我们可以看出，result5正是从实验角度对summary的这一部分的阐述。现在进入正题。

------

因为之前的研究显示TBK1 和 K48-linked and K63-linked ubiquitination都有关，所以先验证了一下，发现

> USP38 markedly increased K48-linked, but not K63-linked ubiquitination of TBK1

说明USP38的作用在这里确实是只管K-48

然后

> Since the K48-linked ubiquitination of TBK1 is regulated by NLRP4, DTX4, or TRIP protiens

所以看一下是不是USP38通过调节这些因子来调节TBK1, 结果

> We did not observe any apparent differences in the protein abundance of NLRP4, DTX4, or TRIP in the process or absence of USP38 after viral infection(Figures S4A-S4C)

于是就有了第一段结尾的结果

> ﻿USP38 regulates K48-linked ubiquitination of TBK1 via a distinct mechanism.

考虑到USP38是DUB，于是他们开始思考USP38是如何通过去泛素化增加而不是减少TBK1 K48-linked ubiquitination

他们利用USP38的突变体C545A, H857A实验，发现突变体是不能使TBK1降解的，所以他们就得出了USP38的去泛素化是降解TBK1的前提这一结论。

------

基于以上实验他们开始思考USP38会移去和加上哪种ubiquitin chain，于是他们做了这样一个实验

> We performed experiments using 293T cells expressing FLAG-TBK1, Myc-USP38, and different.types of HA-tagged ubiquitin.

从Figures S4D-S4F中他们发现了K33-linked ubiquitination 被移去了。再与利用突变体不能移去K33-linked ubiquitination of TBK1这一结果对比，说明K33-linked poly-ubiquitin chain on TBK1的去除是依赖于USP38的去泛素化活性的。

另外，他们还发现TBK1在病毒感染后会经历K48-和K33-linked ubiquitination，但是K48-linked ubiquitination是被促进的，所以他们想到了这个

> USP38 may remove K33-linked ubiquitin chains and add K48-linked ubiquitin chains to TBK1 after viral infection.

------

那么K33-linked ubiquitin chains是如何被移去的？K48-linked ubiquitin chains又是如何被加上的呢？

这就不得不提到一个实验技术 - mass spectrometry analysis(质谱分析)

>  we performed mass spectrometry analysis of ubiquitinated TBK1 from 293T cells or USP38-/-293T cells by VSV infection, using a similar strategy as previously described(2014)  

并且，作为对比， the increased K33-linked ubiquitinated TBK1和 decreased K48-linked ubiquitinated TBK1 in USP38-/- cell在VSV infection过后会被mass spectrometry analysis发现

所以有了USP38 is responsible for the cleavage of K33linked ubiquitin chains of TBK1

更深一步的研究是基于 confocal microscopic analysis ，他们发现

> USP38 was colocalized with K33-linked. ubiquitin chains inside the cells, while the co-localization between USP38 and K33-linked ubiquitin chains was enhanced after HSV-1 infection.

所有上面这些研究最终得出的结论就是

> USP38 is responsible for cleaving K33-linked ubiquitin chains from TBK1

------

至于接上K44-linked poly-ubiquitination of TBK1 at Lys670的问题(从summary之前的图里面我们可以看到不论是移去还是接上都是在同一位点进行的)，首先是先前研究

> NLRP4 induced the K48-linked poly-ubiquitination of TBK1 at Lys670, leading to its proteasomal degration.

而这次更深入的研究目的是介绍发现在同一位点进行移去和连接的实验原因

> 1.neither USP38 nor TRIP can degrate TBK1(K670R) mutants
> 2.TBK1 K670R mutant abrogates not only K48-linked ubiquitination but also K33-linked ubiquitination of TBK1

(实验数据在Figures 5J-S4G 及Figures 5K and S4H)

通过这两个实验结果他们得出了

K33-和K48-linked ubiquitin chains may conjugate to TBK1 at the same amino acid position(即Lys670)

那么如何证明这两个过程只在Lys670位进行呢？

> we pulled down the WT TBK1 and TBK(K670R) mutant and checked the ratio of K33 and K48 poly-ubiquitin chains in the immunoprecitates by mass spectrometry analysis

发现没有K33和K48 poly-ubiquitin信号在TBK1(K670R) immunoprecipitates

所以！位点只有这一个

最后！他们研究了是否K33-linked ubiquitin of TBK1 is more stable than the K48-linked ubiquitinated TBK1

> 方法是we performed the cycloheximide(CHX) assay and pulled down K33-, K63-, or K48-ubiquitinated TBK1.

这样就发现他们的假设是正确的，也就是我们的结果

> USP38 inhibits type I IFN signaling by removing K33-linked and promoting K48-linked poly-ubiquitination chains of TBK1 at Lys670

以上就是这个result的实验思路和结果的叙述。

那么！传说中的思考题时间到了！

```
USP38是如何通过K33-linked ubiquitination和K48-linked ubiquitination来控制TBK1的？
为什么要采用USP38两种突变体的实验进行对比？
为了说明K38-linked ubiquitin chains被移去及K48-linked ubiquitin chains被接上是在同一位点进行的，为什么需要那么多组实验？
```