---
title: CDS ORF UTR TFgene
date: '2023-06-04'
summary: 
---
## ORF与CDS
ORF：open reading frame（开放阅读框）
理论上的蛋白编码区，一般是先在DNA序列中寻找起始密码子（AUG）对应的序列ATG，然后按每3个碱基一组向后延伸，一直到出现终止密码子（UAG、UGA、UAA）对应的序列。

CDS:coding sequnece（编码区）
与蛋白序列一一对应的DNA序列，并且序列中不存在其他与蛋白无关的序列。

CDS可以是一个ORF的**subset**

![CDS ORF](https://upload-images.jianshu.io/upload_images/9376801-e3539c76781d5787.png)
>ORFs:
The region of the nucleotide sequences from the start codon (ATG) to the stop codon is called the Open Reading frame.

>Gene finding in organism specially prokaryotes starts form searching for an open reading frames (ORF). An ORF is a sequence of DNA that starts with start codon “ATG” (not always) and ends with any of the three termination codons (TAA, TAG, TGA). Depending on the starting point, there are six possible ways (three on forward strand and three on complementary strand) of translating any nucleotide sequence into amino acid sequence according to the genetic code .These are called reading frames.

>While eukaryotic gene finding is altogether a different task as the eukaryotic genes are not continuous and interrupted by intervening noncoding sequences called ‘introns’. Moreover organization of genetic information in eukaryotes and prokaryotes is different.



>CDS:
The Coding Sequence (CDS) is the actual region of DNA that is translated to form proteins. While the ORF may contain introns as well, the CDS refers to those nucleotides(concatenated exons) that can be divided into codons which are actually translated into amino acids by the ribosomal translation machinery.

**Mainly: CDS means only that the sequence is known to be transcribed and, therefore, it is coding for something -- neither gene nor protein has to be known. Any full mRNA sequence (obtained from cDNA sequencing) will have a full coding sequence. ORF is usually predicted based on DNA sequence and not proven to be transcribed.**

### Sources:

http://www.biology-online.org/biology-forum/about13035.html
http://www.scfbio-iitd.res.in/tutorial/bioinformaticstutorial.htm

## CDS与UTR
 UTR（Untranslated Regions）即非翻译区，是信使RNA（mRNA）分子两端的非编码片段。
 
 >5'-UTR从mRNA起点的甲基化鸟嘌呤核苷酸帽延伸至AUG起始密码子，3'-UTR从编码区末端的终止密码子延伸至多聚A尾巴（Poly-A）的前端。


A typical CDS starts with ATG and ends with a stop codon, it doesn't have any introns, 5'- and 3'-UTR

## 启动子和终止子
**启动子** promoter
- DNA分子上能与RNA聚合酶结合并形成转录起始复合体的区域

- 与RNA聚合酶结合并能起始mRNA合成的序列。做生信分析时，有的选择上游1 kb，下游 500 nt，也有选上下游各1 kb的

**强启动子**（strong promoter）：对RNA聚合酶有很高亲和力的启动子，可以指导合成大量的mRNA

**终止子** terminator

- 转录过程中能够终止RNA聚合酶转录的DNA序列
- 终止子可分为两类：一类不依赖于蛋白质辅因子就能实现终止作用。另一类则依赖蛋白辅因子才能实现终止作用

## 转录因子和结合位点

转录因子(transcription factor)

- 一群能与基因5`端上游特定序列专一性结合，从而保证目的基因以特定的强度在特定的时间与空间表达的蛋白质分子，这些蛋白质能调控其基因的转录。

- 调控方法是转录因子可以调控核糖核酸聚合酶（RNA聚合酶，或叫RNA合成酶）与DNA模板的结合

**TF结合位点** transcription factor binding site，TFBS

转录因子调节基因表达时，与基因模板链结合的区域。一般应该分布在基因前端。*【但：人21和22号染色体上，只有22%的转录因子结合位点分布在蛋白编码基因的5'端】*

关于转录因子，cell有一篇非常经典的大综述。
>Lambert SA, Jolma A, Campitelli LF, Das PK, Yin Y, Albu M, Chen X, Taipale J, Hughes TR, Weirauch MT. The Human Transcription Factors. Cell. 2018 Feb 8;172(4):650-665. doi: 10.1016/j.cell.2018.01.029. Erratum in: Cell. 2018 Oct 4;175(2):598-599. PMID: 29425488.

## 增强子
增强子(Enhancer) 又可译为强化子，是DNA上一小段可与蛋白质结合的区域，与蛋白质结合之后，基因的转录作用将会加强。增强子可能位于基因上游，也可能位于下游。且不一定接近所要作用的基因，甚至不一定与基因位于同一染色体。这是因为染色质的缠绕结构，使序列上相隔很远的位置也有机会相互接触。

### 增强子和启动子
增强子能大大增强启动子的活性。增强子有别于启动子处有两点:增强子对于启动子的位置不固定，而能有很大的变动;它能在两个方向产生相互作用。一个增强子并不限于促进某一特殊启动子的转录，它能刺激在它附近的任一启动子


![DNA mRNA Protein](https://upload-images.jianshu.io/upload_images/9376801-baf83a073bb5deea.png)

![enhancer](https://upload-images.jianshu.io/upload_images/9376801-6c22cb873bf1a822.jpg)


## ref
https://www.jianshu.com/p/2ba85c5306e7
https://www.biostars.org/p/47022/


