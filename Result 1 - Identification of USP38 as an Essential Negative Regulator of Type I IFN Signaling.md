# Result 1 - Identification of USP38 as an Essential Negative Regulator of Type I IFN Signaling

Summary中提到：

> Here we report that USP38 negatively regulates type I IFN signaling by targeting the active form of TBK1 for degradation in vitro and in vivo.

那么，Result 1就是要确认USP38识别是一个重要的负调节I型干扰素的信号。

为了确定去泛素化酶在抗病毒免疫性中的角色，研究者运用生物信息学方法进行了数据分析，找到了一种去泛素化酶——USP38：

> we screened 81 genes encoding deubiquitinases（DUBs）and identified USP38 as a negative regulator of type I IFN signaling.

运算得来终觉浅，还是得做点实验

> USP38 potently inhibited the activation of IFN-b by treatments of ...(lots of pathogen-associated molecular patterns) (Figure 1A).

也就是说，USP38可以强效抑制IFN-b的激活。

因为IFN-b激活时，需要合作激活 IRF3 和 NF-kB，于是我们想检验USP38是否直接影响IRF3信号。

> we used an IFN- stimulated response element (ISRE) luciferase（荧光素酶） reporter to test whether USP38 directly affects IRF3 signaling.

结果发现 USP38 同样抑制 ISRE-luc 活性。接下来，

> We assessed phosphorylation of IRF3 in 293T cells, expressing USP38 together with RIG-I(N), MDA5, MAVS, STING-cGAS, or TRIF.

并发现 USP38 抑制所有这些先天免疫受体和接头蛋白诱导的 IRF3 活化。

进一步的 qPCR 分析表明，

> the mRNA levels of IFNa4, IFNb, IFIT1, IFIT2, and ISG15 in USP38 ectopic expression cells were markedly reduced during VSV infection (Figure S1B)，

也就是 USP38 抑制干扰素刺激基因（ISGs）的表达。

为了确定生理条件下 USP38 的作用，

> we efficiently knocked down USP38 in 293T cells, THP-1 cells, or human peripheral blood mononuclear cells (PBMCs，外周血细胞) (Figure S1C）.

荧光素酶测定分析表明，

> USP38 knockdown could enhance the IC poly(I:C)-, poly(dA:dT)-, or VSV-EGFP-induced ISRE activation (Figure 1C).

与这一结果相一致，我们发现敲除 USP38 显著增强 IRF3 的磷酸化 (Figure 1D)。

为了证实这些发现，

> we knocked down USP38 in THP-1 cells, 293T cells, A549 cells, or PBMCs, and we found that USP38 knockdown significantly increased the IFN-a4 and IFN-b expression, as well as IFN-b secretion induced by VSV-EGFP or HSV-1 infection (Figures 1E–1G and S1D–S1F).

进一步我们表明在这些细胞中的 USP38 敲除使他们抵抗 VSV EGFP 感染（Figure 1H,  1I, S1G, S1H）。

这些结果共同表明，USP38 负调节I型干扰素信号以及在人体各种细胞类型中的抗病毒免疫。

思考题：

```
这里用了哪几个验证 USP38 负调节I型干扰素信号？
```
