# [literature note 001] Nanochannel-Assisted Perovskite Nanowires: From Growth Mechanisms to Photodetector Applications

## Tags

`Perovskite Nanowares`,`Growth Machnism`

## Main Content

这篇文章主要是对在纳米沟道诱导下 MAPbI3 纳米线生长机理的研究，他们希望能够藉由这种 `MNFFT`（micro/nanofluidic fabrication technique）方法获得生长精确控制的纳米线，并且用这种方法得到的纳米线制备了高灵敏的光探测器。

文章中花了很大的篇幅来讨论 MAPbI3 生长过程中的动力学。

文中所使用的纳米沟道是通过 `PDMS` 模板来实现的，如图中所示，由两个微米级的沟道一上一下构成，两者中间有一条微米级的沟道连接两者，共同构成了沟道网络。模板覆盖在衬底上，通过上方的孔注入前驱体溶液来生长钙钛矿纳米线。

![Schematic of the PDMS device](https://s2.loli.net/2022/10/27/87fmuxJUFpX2bSw.png)

>[!NOTE]
>值得注意的是，为了保证前驱体溶液中的 MAI 和 PbI2 恰好完全反应，他们是将析出的 MAPbI3 晶体用 `IPA`（异丙醇）清洗之后再重新溶解于 `DMF` 中来>获得前驱体溶液。

经过实时观察 MAPbI3 纳米线的生长，并且用紫外-可见光光谱进行分析，关于纳米线的生长机理，他们所得出的结论是：

前驱体溶液从一侧进入纳米沟道后，纳米沟道与没有溶液的一侧的交接点处溶液与气体环境的接触面积增大，`DMF` 的挥发速度加快，形成了最初的成核位点，加上 PbI2 在 `DMF` 中的低溶解度，`PbI2·DMF-related crystal` 沿着纳米沟道从下向上生长，甚至扩展到上方的微沟道中。PbI2 的消耗被 `DMF` 的消耗和持续挥发所补偿，使得 `PbI2·DMF-related crystal` 能够持续生长下去。同时，由于 PbI2 的消耗使得 MAI 在 `PbI2·DMF-related crystal` 前驱体周围富集，使得 MAPbI3·DMF 能够沿着它成核生长。之后在纳米沟道的引导下，`PbI2·DMF-related crystal` 转化为 MAPbI3·DMF 纳米线。

>[!NOTE]
>MAPbI3·DMF NW 进一步转化为 MAPbI3 NW 还需要进一步的加热退火以除去多余的 `DMF`。

一些实验上的细节：

向上方的微沟道中滴入溶液，下方保持为空的，溶液很快注入到中间的纳米沟道，纳米沟道与下方微沟道的接触点处溶液的接触面增大，溶液挥发加快，加上 PbI2 在 `DMF` 中的低溶解度，在纳米沟道中形成最初的 `PbI2·DMF-related crystal` 作为成核位点，随后MAPbI3·DMF 纳米线沿着纳米沟道从下往上生长，一直生长到微沟道中，但微沟道中的 `DMF` 也在挥发，微沟道中也开始有纳米线生成，最终集结成纳米线束。

改变沟道的尺寸，当沟道尺寸较大时（500 nm deep，4 µm wide），溶液从纳米沟道流入下方的微沟道，成核位点的位置不好控制，纳米线无法按照既定路线生长，从图中可以看到纳米线生长到了底部的微沟道中；当沟道尺寸较小时（200 nm deep，1 µm wide），液体无法流入到纳米沟道中，纳米线也无法生长。只有当沟道尺寸合适时（~350 nm deep，2 µm wide），纳米线才正常生长。显然，这说明最初的 `PbI2·DMF-related crystal` 作为成核位点对纳米线的生长是重要的，因为不论是当沟道尺寸大时难以控制成核位点的位置，还是沟道尺寸小时溶液无法流过去形成不了成核位点，纳米线都无法正常生长。

把溶液换成 PbI2 的 `DMF` 溶液，观察 PbI2 纳米线的生长，在纳米沟道中的生长并没看出明显的区别，而当纳米线生长到微沟道中时，除了轴向的生长，还发生了径向上的生长，这和 MAPbI3 纳米线的生长显然是不同的。如果认为 PbI2·DMF 纳米线驱使了 MAPbI3·DMF 纳米线的生长，那么 PbI2·DMF 向 MAPbI3·DMF 转化的过程中，径向的生长是被抑制的。

观察生长过程中的紫外-可见光吸收光谱，发生了吸收边从 432 nm 到 602 nm 的红移，这对应的是 `PbI2·DMF-related crystal` 向 MAPbI3·DMF 的转变，这一过程的光谱变化与向 PbI2 薄膜上滴 MAI 溶液是类似的。观察了 PbI2·DMF 纳米线生长过程中的紫外-可见光光谱，并没有发生明显的变化，这一点和 MAPbI3·DMF 纳米线生长的早期是类似的。

降低前驱体溶液的浓度，会观察到纳米线先生长后溶解之后重新生长的现象。显然，当前驱体溶液较低时，由于只有纳米沟道入口处的局部浓度较高，所以当纳米线一开始沿着纳米沟道生长出来进入微沟道后，纳米线很快就溶解了。随着溶液的挥发浓度进一步提高，纳米线才又重新生长出来。

以上。

## Evaluation

在纳米线生长的过程中，除了显微镜的观察，也仅仅只是做了紫外-可见光光谱的表征，`PbI2·DMF-related crystal` 是个混沌的描述，无从得知它具体的结构与组成，也不清楚它和 PbI2·DMF 之间的关系，而 `PbI2·DMF-related crystal` 到 MAPbI3·DMF 纳米线这个转化过程是如何发生的更是无从谈起，仅仅是知道大概发生了这件事而已。还是希望有更清晰的研究吧。

## Reference

[Zhou, Q., Park, J. G., Nie, R., Thokchom, A. K., Ha, D., Pan, J., ... & Kim, T. (2018). Nanochannel-assisted perovskite nanowires: from growth mechanisms to photodetector applications. ACS nano, 12(8), 8406-8414.](https://pubs.acs.org/doi/10.1021/acsnano.8b03826)