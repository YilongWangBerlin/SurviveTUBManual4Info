本项目旨在更好的帮助ersti以适应工大学业, 并提供了一份**选课指南**以供参考, 该项目将被长期维护，希望能给未来的工大在读和入学新生同学带来微小的帮助. 

For the **English version of this guide**, please refer to **[English README](./README_EN.md)** in the **same directory** of this repository.

同时本项目尚处于初始阶段, 在科研, 找工作, 选导师, 海外交换, 奖学金申请等部分尚未完成, 因此本项目迫切的需要更多的贡献者的力量来加以完善. 若同学们想在其他领域分享自己的经历与资源, 或是贡献一门新的课程, 请直接在项目中提出 [Pull Request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork)

由于个人水平有限,本文难免有笔误和错误之处,或是课程有了新的变化,也请各位不吝赐教,在 issue 中提出来。
# Altklausur导航
- https://docs.freitagsrunde.org/Klausuren/ 
- studydrive
- studoc


# iv系学生常用交流平台:
- Telegram: https://t.me/+SZHL9ILi4lUxNWZi
- WhatsApp: https://chat.whatsapp.com/Grk9sTI04HlCclHgcxAa92 and https://chat.whatsapp.com/BXtZwZOi5zpIRMzfdZUwwt
- Discord: https://discord.gg/Ekb6WUMF
- Matrix (多为master使用)

FYI: Discord是tutor们最常出没的地方, 你能在这里了解到许多学校少为人知的辛集, 他们也非常乐意去回答你提出的问题并偷偷嘲笑你,以theoretische informatik的课最甚(forsa,ds,beko,logik等等), theoretische informatik的课以极好的nerd氛围, 极高的难度与极低的通过率而闻名. 


# 学业情况统计: 
FYI: 有往年课程的通过率和平均分数据,这些数据仅供参考，每年课程的难度可能变化很大。近年来普遍有越来越难的趋势。
https://tubcloud.tu-berlin.de/s/6oiqpSgyZgf6Dse?path=%2F2024-02-16


# 一些人生的经验
## 关于大作业
1. **early start**: 尽管我校通常给了充足的时间来完成大作业,通常是一个月的时间,不管是latex写证明也好,还是编程大作业,都需要花费相当长的时间来完成,尽早开始能有更多的容错空间
3. **find the problem**: 当你拿到一个问题的时候最困难的可能不是如何解决这个问题,而是我们应该怎样提出问题. 比如,当你看到5页的背景介绍后才开始出现题目,脑子一片空白,对背景介绍的定义/算法仍一知半解,在观看了许多youtube视频后你有了一定了解,可是对于题目仍不知道怎样开始,这时不妨我们先提出一些问题,比如,这个问题对应着vorlesung的哪些内容? 我们可能需要用到哪些数学工具来解决? 我们是否可以使用外部的库? 我们应该用到哪些库来解决哪些可能出现的问题?(特别是rnvs和sysprog,他们从不教代码,连要用到什么库都不告诉你),这些都需要大量的时间成本去了解 
4. **solve problem**:在大部分的大作业中通常prof不会直接用vorlesung里介绍的概念或定义来考你,他可能在某篇论文里发现了新东西就拿来出题了,而你需要用在vorlesung里用到的知识去解决它,我们要做的,就是将vorlesung里的ansatz映射到这个问题里,通常可能需要将一个大问题拆分成数个小问题来解决.

## 关于Klausur
其实人脑和Machine learning很像,本质上他们都是一个guessing machine, 给定一个输入得到一个输出,学习的过程正是一个训练模型的过程,而在训练模型的过程中我们可以用一些小trick

- *梯度下降前期进度太快，后期可能乏力*

在适当的时间开始复习, 复习的太早,战线拉的太长后期可能乏力,反而可能更快的形成思维定势,漏掉许多细小的内容.复习的太晚则可能造成训练量不够,泛化能力差

- *模型的拓扑结构越复杂,其泛化能力越强*

在第一轮复习阶段我们需要对所有内容进行一个梳理,了解整个知识体系是怎样的,这样我们在遇到问题的时候,能够很快分析出究竟需要运用哪一个模块来解决它. 在第二轮复习的时候我们就可以开始写altklausur了,我们可以试着将80%的altklausur当作训练集,20%当作测试集

- *overfitting: 模型过于复杂反而降低了泛化能力*

在我们做完大量的altklausur后可能会出现overfitting的问题,比如在过去数年的klausur都用的一个pattern,题型范围都差不多,可是突然今年题型和考试范围全变了,这时候我们可能会用到dropout

- *Dropout: 我们随机忽略掉一些神经元和神经联结 , 是这个神经网络变得不完整. 用一个不完整的神经网络训练一次.*

我们在vorlesung中(随机)选择内容复习(特别是不熟悉的内容),这样一旦出现新的pattern,我们有着更强的泛化能力以及更小的test error

- *训练集太小也可能造成overfitting*

而overfitting的另一种可能原因是你的训练集太小,可能存在着一种情况: altklausur的题目可能只是一个pattern的部分情况,你并没有考虑到所有的Corner case,这时候我们可以试着增加数据量,比如找其他学校的altklausur做

最后呢,大家要是有兴趣,可以看看沐神的一些人生经验,看完受益匪浅: https://zhuanlan.zhihu.com/p/414009313

--- 
# 选课指北I - 必修

## Analysis I und Lineare Algebra für Ingenieurwissenschaften 
- 考试形式: hausaufgabenkriterium (每周都有gruppenaufgaben,拿到schein才能参加考试)
- 难度: 容易拿1.x  和probklausur很像

## Einführung in die Programmierung
- 头两周的每天都有课, 很多人在这个时候ab了,但请一定要坚持下去
- memery leak永远的噩梦
- 难度: 很难说,2022年课改,很难很难,2023年变简单了

## Rechnerorganisation 
- 考试形式: 2次mc test, 1次大作业(mips汇编), 以及abschlussklausur
- 老邪为数不多反复看大黑书的课, 不管是书还是folien都写的十分晦涩,推荐视频: https://www.bilibili.com/video/BV1oK4y187Tk/?share_source=copy_web&vd_source=e073e2ca381d9aa0501f2979568fa828
- uebung要记得去哦,因为rorg的team不发答案
- 难度: 因为是portfoli,前面mc test的大作业就能拿很多分了,所以过不难,但高分很难,2022年2.0内只有个位数

## Informatik Propädeutikum 
- 水课, 考前看就行

## Systemprogrammierung
- 半个杀手课
- 考试形式: mc test + 两次编程作业 + klausur
- 第二次编程作业很恶心,总任务代码量在600到1000之间, 最主要是因为上课不教代码,所以一开始很迷茫
- 作业请一定一定要early start!!! 不要小瞧他的工作量
- 难度: 努力点的话拿1.x没问题, 因为klausur不难,很多algo题都是送风的,只不过这几年开始用theorie frage来增加点区分度了

## Algorithmen und Datenstrukturen 
- 很有用的课, 特别是对于找工而言
- 考试形式: 自2024年起algodat变成schriftliche klausur了
- 难度: 很难说, 不过有一点可以肯定,2024年是最难的一年

## Informationssysteme und Datenanalyse 
- 考试形式: 3次编程作业 + klausur
- tutorium记得去哦,因为isda team不给答案,最好去上线上的,这样你可以截屏
- 3次编程作业都需要花相当时间去完成, 需要大量的时间去debug, 老邪平均花了2到3天完成
- 难度: 考试也变难了起来,具体体现在题量巨多,因为疫情时间这门课是出了名的水课,2023年课改就变得很难
![](attachment/截屏2024-10-11%2002.53.22.png)

## Formale Sprachen  und Automaten
- 考试形式: 2024年起变4小时笔试了,通过mc test拿到schein
- 难度: 只要好好复习,过不难,就是复习内容相当之多

## DS, Beko, logik
- ds和logik: mc test + 大作业(用latex完成) + klausur
- ds 2024年由新prof接任,增加了group theory的内容, mc test和klausur较往年难度陡增, forum里声讨ds team的学生已近50人
- beko从2024年变笔试,并且prof weller也离开tub了,由新教授上课,具体措施尚未可知,但我想应该不会比wellr出题更难
- 推荐tutor: alex!!!!!

## Rechnernetze und Verteilte Systeme 
- 和sysprog很像
- 考试形式: mc test + 3次编程大作业 + klausur
- 3次大作业都是循序渐进的,后面的作业是基于前一次作业的基础上写的
- 上课也不教代码,大作业给你一本书自己研究,那本书就得琢磨好几天
- 难度: 2023年klausur首次线下,题目较往年大有不同,有更多的theorie frage和更难的计算题.(疫情时代这门课online klausur一点也没变过,线下考大家考的都很差)

## Softwaretechnik und Programmier- paradigmen 
- 考试形式: mc test + 编程大作业(haskel) + klausur(包含prolog)
- 难度: 容易过, haskel可用chatgpt
- 无聊

## Wissenschaftliches Rechnen , Stochastik  für Informatik 
- hausaufgabenkriterium
- wr 用python
- 容易拿高分

## Informatik und  Gesellschaft 
- 水课
- 抱课人多,记得早点an哦
- 要做汇报



# 选课指北II - 选修

## operations research
- 包含了几乎所有algodat的算法
- 每学期都开
- 只有theorie没有编程
- 如果之前没有接触过graph theory,那么or是一个很好的开始!

## Cognitive Algorithms
- 主要涉及到一些传统机器学习的算法
- 需要额外上一门ml group提供的课才能去参加ca的考试(推荐上math,因为水,或者上seminar也可以,因为info系学生毕业要求有一门seminar)
- 考试这几年也变难了,但和theoretische info比还是容易的

## python for ml
- 老邪上过的课中考试最难最难的一门!! 没有之一!!!
- 只持续半学期
- 一周两节lecture,一周拉完基本python语法,然后上一些numpy还有一些算法的运用
- 2.termin 比1.termin简单!!!!!
- 2.termin删掉了三分之一的题,并且更简单一些
- 考试在fu线下机考
- 但其实这门课还是好过的,因为他出的太难了,导致如果按照程序是否输出正确的output来给分大家都挂了,所以这门课是tutor手动改,只要你写的多tutor就敢给你分,甚至有人一道题都没跑出来都拿了70分

## integraltransformationen und partielle Differentialgleichungen für Ingenieurwissenschaften
- 拉普拉斯变换,傅立叶变换,常微分方程,偏微分方程
- hausaufgabenkriterium
- 如果是Robert Beinert代课,run!!!! (这位是2年半博士毕业的大佬,出题和altklausur完全不同)
- 如果是其他人带,放心大胆的去! 1.x就在眼前!
- 推荐tutor: lucie!!!

## Signale und System
- 和itpdg很像,这两可以一起学
- 推荐tutor: Yura姐!!!!!

## Digitale Systeme
- 出名的水课

## Betriebssystempraktikum
- 听说相当之难
- 如果你喜欢rnvs和sysprog,或者对system感兴趣推荐选

## Webtechnologien
- 为数不多前端的课,上课用vue
- 考试很考细节,,,

## Einführung in die IT Sicherheit 
- 只有选择题
- 3lp

---
***to be continued***

# 后记
光阴荏苒,岁月如梭,本文完成时老邪已度过2年的tu本科生涯, 还记得在第一二学期的时候,意气风发, 那种勃勃生机万物竞发的境界犹在眼前, 那时候我和想哥周一到周日都在图书馆或tel楼学习,晚上11点在回家的公交上,我能感觉到自己在前进,似乎未来仍可期. 而现在只觉得自己一事无成,一没有做出开创性的工作,二不清楚未来的发展方向,三也没有好好享受生活,简直就是是柏林的Madao嘛! 不管怎样努力,不管继续在那该死的肖申克同款监狱学多久,我再也没有两年前觉得自己在前进的感觉了

这学上到现在其实已经没什么意思了,仔细想想自己涉猎这么多课别人真的care嘛?或者十年后的我会care嘛?好像也不怎么care,不管是工业界还是学术界大家看的都是成果,没有谁会因为你学的多或考的好而高看你一眼,peter scholze闻名世界是因为他对arithmetic geometry的贡献,而不是一年半读完bonn数学本科.emmm 好吧,这个例子举的不好,任何只用一年半读完自然科学的人当值得另眼相待,anyway, you know what i mean.

所以如果要我说一些关于学业的建议的话,大概是,对于我等凡夫俗子而言,实在没必要太努力,人一生要工作五十年,花点时间去追求梦想,还有那诗和远方岂不痛哉! 慢一点并不比快一点差,或许快一点能很快找到局部最优,但也限制了自己的眼界而看不见全局最优,慢一点或许能走的更远,才能看得到一个更优解!

最后祝大家生活愉快,学业顺利,happy coding!

