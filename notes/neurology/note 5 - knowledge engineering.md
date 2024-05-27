# 1. Ontology Engineering

## 1.1 Chapter 1

1. Knowledge Representation:

$$
Lion\sqsubseteq \forall eats.Herbivore\sqcap \exists eats.Impala
$$

Natural language description:

- Each lion eats only herbivore and eats some impala.

Graphical Representation:

<img src="C:\Users\Micro\AppData\Roaming\Typora\typora-user-images\image-20240527084704358.png" alt="image-20240527084704358" style="zoom:42%;" />

**Ontology artifacts must obey the forms that a logic machine can process.**

+ RDF/XML representation 

<img src="C:\Users\Micro\AppData\Roaming\Typora\typora-user-images\image-20240527084842175.png" alt="image-20240527084842175" style="zoom:33%;" />



**ontologies** (knowledge bases) include the **representation of the knowledge explicitly**, by having **rule included**, by using **automated reasoning** to **infer implicit knowledge and detect inconsistencies** of the knowledge base They usually operate under the Open World Assumption.

> Important: "explicitly" is important.
>
> 在用于知识表示的形式逻辑系统中，开放世界假设是假设一个陈述的真值可能是真的，而不管它是否已知为真。它与封闭世界的假设相反，封闭世界的假设认为任何真实的陈述也被认为是真实的。



<img src="C:\Users\Micro\AppData\Roaming\Typora\typora-user-images\image-20240527085509430.png" alt="image-20240527085509430" style="zoom:33%;" />

Some definitions of ontology:

**Def 1.1** ([Gru93]). An ontology is a specification of a conceptualization.

**Def 1.2.** An ontology is a formal, explicit specification of a shared conceptualization.

**Def 1.3.** An ontology is a **logical theory accounting for the intended meaning of a formal vocabulary**, i.e. its **ontological commitment to a particular conceptualization of the world**. The intended models of a logical language using such a vocabulary are constrained by its ontological commitment. An ontology **indirectly reflects this commitment (and the underlying conceptualization) by approximating these intended models.**

**Def 1.4** An ontology being equivalent to a Description Logic knowledge base.



2. **Philosophy**

一个争论是关于本体论作为概念化的表征:你正在思考的事物，作为现实的表征。

错误的表示会导致错误的推论，从而导致错误的治疗，这些治疗要么无效，要么甚至有害。

+ 普遍主义 (Universalism)

普遍是一类独立于心灵的实体，通常与个体相对立。

哲学的其他方面也会影响本体论中表征的是什么以及如何表征。例如，它可以在建模阶段提供帮助，比如你是谁与你扮演的角色之间存在差异，参与事件与成为事件的一部分之间存在差异，并有助于澄清你可能对世界的假设，这些假设可能会渗透到本体中，比如你是否确信花瓶和粘土是相同的还是两个不同的东西。

+ 概念主义 (Conceptualism)

+ 经验主义 (Empiricism)



3. Ontology points of attention.

Ontology can be **good**, **bad** and **error**.

Ontology should obey grammars.

More complex situation: a ontology can be better than another ontology.

+ For the same knowledge, we could have different representation for it, and each of these representation could be associated with a goodness.
+ 当我们想要表征的东西已经在本体论中被表征了，但实际表征的东西非常接近，只比意图稍微多一点时，我们就有了一个好的本体论;也就是说，我们有很高的精度和最大的覆盖率。当本体论所代表的东西比它应该代表的多得多时，我们的本体论就不那么好了;也就是说，我们有低精度和最大覆盖。



基于本体驱动的基于模式的数据集成的思想

<img src="C:\Users\Micro\AppData\Roaming\Typora\typora-user-images\image-20240527093951901.png" alt="image-20240527093951901" style="zoom:50%;" />

本体为应用程序之间的互操作性提供了共享的公共词汇表。

![image-20240527094527702](C:\Users\Micro\AppData\Roaming\Typora\typora-user-images\image-20240527094527702.png)

4. Applications

本体已被证明在无数其他应用场景中是有用的;其中，软件服务之间的协商，软件代理之间的中介，将更多的质量标准引入概念数据建模以开发更好的模型。

+ e-learning

需要对学习材料、问题、答案、学生属性、学习方法进行知识表示，并进行自动推理，对使用模式和学生进行分类，并对内容进行注释，即使用本体和知识库，使其牢固地工作，并以可重复的方式工作。

+ Digital Humanities

+ Semantic scientific workflows
+ Deep question answering with Watson
  + 该系统的开发不能以线性方式从自然语言到知识管理，而必须使用各种技术的集成，包括本体，才能制作成功的工具。

<img src="C:\Users\Micro\AppData\Roaming\Typora\typora-user-images\image-20240527095931957.png" alt="image-20240527095931957" style="zoom:50%;" />

本体论不是作为工程基础设施中众多可能的“工具”之一，而是作为旨在发现有关自然的新信息和知识的科学研究方法的必要组成部分。





