web version for the paper contained in [[Knowledge, Information and Creativity Support Systems](http://res.cloudinary.com/ontore/image/upload/c_scale,h_300/v1459274225/2016-02-02-kicss-book_moecxr.jpg)](http://www.springer.com/us/book/9783319274775)

**Abstract:**

> Do we have a scientific model of creativity as emerging from contributions of computer users, computer systems and their interaction? Such a model would require describing the creative process in general, conditions for human creativity, the added value of human-computer cooperation as well as the role and power of computing. All of these topics have been the subject of research, but they have been addressed in different research communities. Potential obstacles for combining research results from research fields such as knowledge engineering and creativity research and properties of a general model of Human-Computer Co-Creativity are discussed.

Creativity Support Tools (CST) are a relatively recent topic in Human-Computer Interaction (HCI) Shneiderman et al. (2006). But the goal of extending not just the limits of human productivity but also creativity has occupied a prominent place in the earlier history of computing. Computer-supported creativity had to be rediscovered after decades of scientific neglect. Is creativity a particularly hard challenge for computer science? On the one hand, creativity is a difficult topic in itself. On the other hand, we have developed a number of powerful computer technologies with the explicit goal of augmenting the human intellect, but we do not know whether these technologies have increased creativity. More than once, computer science has abandoned the topic of creativity as soon as a path towards extending computing power in itself was identified.

Augmenting Human Creativity
===========================

As early as 1945, aiding human creativity with computing machinery was proposed: Bush (1945) Computers were expected to increase human creativity by alleviating the routine elements of scientific work. Did we reach this goal? With data-intensive science, we now have a research paradigm that relies completely on computational support Hey, Tansley, and Tolle (2009). But has research become more creative as a result? When Chaomei Chen developed CiteSpace and assessed scientific creativity, he still had to Chen (2012). Seven decades after Vannemar Bush, scientific creativity and its relationship to computer support are still poorly understood.

In 1960, J.C.R. Licklider extended the vision of supporting creative thought beyond the domain of scientic work as a generalized goal for achieving <span>*man-computer symbiosis*</span>: “The hope is that, in not too many years, human brains and computing machines will be coupled together very tightly, and that the resulting partnership will think as no human brain has ever thought and process data in a way not approached by the information-handling machines we know today.” Licklider (1960) When Doug Engelbart followed up on the research into <span>*augmenting human intellect*</span>, he already emphasized the central role of <span>*knowledge*</span>: “The capabilities of prime interest are those associated with manipulating symbols and concepts in support of organizing and executing processes from which are ultimately derived human comprehension and problem solutions.” Engelbart (1962).

This line of research was exceptionally successful: With the comparatively recent exception of touch devices, the combination of keyboard, graphical monitor, computer mouse and hypertext have been the standard computer interface over the last three decades. One might argue that our intellect was indeed augmented and our creativity supported by these technologies. If that is the case, we should in fact call them Creativity Support Tools. Why don’t we? Because even though creativity support has been a recurrent research goal, a scientific method for identifying successful Human-Computer Co-Creativity ($$HC^3$$) was never developed. A recent systematic review of design theories for creativity support tools for instance states:

> Much work on creativity support systems provides design guidelines that inform about what set of features the class of information system should encompass in order to be successful [...] literature does not yet provide a wide range of design research efforts that test the effects of particular creativity support system design features. Voigt, Niehaves, and Becker (2012)

We can evaluate computer system properties, but we do not have a reliable method for identifying a process of creative human-computer co-operation.

Research Fields Fragmentation
=============================

![research topics for Human-Computer Co-Creativity](http://res.cloudinary.com/ontore/image/upload/v1459272462/hc3-fields_wjcixf.svg 'Label')

Human-Computer Co-Creativity is a process resulting in a creative outcome and involving one or more human individual(s) and one or more computer system(s). A model of $$HC^3$$ would therefore have to account for the role of each of these three elements as well as the relationships between them (Figure  [fig:research-fields]). HCI has recently rediscovered Creativity Support Tools. But as a computing discipline, HCI is (again) focusing its efforts on the properties of the computer <span>*tool*</span>, rather than the creative process. Computational Creativity (CC) is investigating the entire creative process, but aims for developing creative computer systems as opposed to supporting human creativity. Human creativity itself is typically investigated independent of any computer interaction in Creativity Research (CR).

$$HC^3$$ research is fractured. While there are several research communities working on some of the relevant topics, there is no research community dedicated to understanding all of them in conjunction. The obvious task would then be combining research results from these communities. But trans-disciplinary research is facing fundamental differences in research culture. CR has grown out of psychology and its methods. HCI and CC are sub-disciplines of computer science. As engineering disciplines, the latter two are primarily concerned with working towards clearly defined outcomes, while the former places more emphasis on understanding a pre-existing phenomenon. When research is synthesized across these disciplines, key notions and their meaning have to be accommodated.

Knowledge in Computer Science
=============================

CC has its roots in Artificial Intelligence (AI). As in all AI-related disciplines, <span>*knowledge*</span> plays a key role in CC. In every day language, knowledge is understood as something an individual has or does not have. Whether or how this knowledge is or can be represented or transmitted through the use of symbolic representations is secondary. This is also the way <span>*knowledge*</span> is viewed in CC.

Computers do not develop and learn like human individuals, they are constructed by computer engineers. To give computers knowledge, AI researchers have invented various types of <span>*knowledge representation*</span>, leading to extended discussions on what constitutes the best type of knowledge representation.

![computer levels according to Newell<span data-label="fig:levels"></span>](levels.eps)

Alan Newell has tried to settle this controversy within AI and his proposal is very illustrative of the content and method of AI research. He formulated a hypothesis claiming knowledge would reside in a virtual computer system level called the <span>*knowledge level*</span>. According to Newell Newell (1982) the levels in (Figure  [fig:levels]) all share the following properties: Higher levels do not have to know about the specific implementation of lower levels. Each level can be reduced to the level below. And each level has its unique medium.

According to Newell’s hypothesis, knowledge is a medium of computation just like electrons or software symbols and it consists of goals, actions and bodies, governed by the principle of rationality. By delegating knowledge to a new computer system level, Newell removed the need for deciding on the best form of knowledge representation: Any representation can implement knowledge in its own way.

But there is no knowledge without symbols, a view consistent with the earlier <span>*physical symbol systems*</span> hypothesis Newell and Simon (1976). A discussion of competing views such as <span>*subsymbolic AI*</span> would be beyond the scope of this article, but as Newell correctly points out, his levels metaphor follows the practice of AI and computer science research in general.

The primary goal of computer science is to make computers more powerful and to ensure that computed results are correct at all times. Then how is correctness verified on the knowledge level? The highest directly observable system level contains symbols that might or might not encode some specific knowledge, but knowledge itself would be removed from direct observation. Newell proposed a mechanism of indirect verification: If some (human or artificial) <span>*agent*</span> A can detect the impact of some specific knowledge in the actions of another agent B, agent A can verify the presence of such knowledge in agent B.

Objectivist/Realist World View
==============================

![how do different observing agents agree on the presence of knowledge?<span data-label="fig:3agents"></span>](3agents.pdf)

The world view underlying the computer science notion of knowledge can be described as <span>*objectivist*</span> or <span>*realist*</span>, which can be detected by discussing those aspects that authors like Newell do not discuss, and the questions that are not answered. A good example is: More than one agent could take the role of the observing agent A in Newell’s knowledge verification mechanism and the different As could come to different conclusions on whether knowledge is present in agent B (Fig.  [fig:3agents]).

Newell does not explain how the A agents would be able to come to any consistent conclusion on agent B’s knowledge, and since their symbol levels might be mutually incompatible, it is unclear how they could even communicate their different views on agent B. The only conceivable way Newell’s knowledge verification might yield consistent results is by relying on a standardized observer agent A that serves as the absolute reference on verifying knowledge. Newell implicitly assumes *objective knowledge* that would be the basis, rather than the result of attempts at creating artificial intelligence.

Such assumptions are quite common in information technology. In fact, Shannon’s definition of <span>*information*</span> Shannon (1948) only works under the assumption of an objective observer for assessing the probability of the next symbol. Shannon actually used an object in the form of the English language dictionary as a means for replacing subjective meaning with an objective type of measurement.

For good reason, the objectivist/realist view has a long tradition in computer science. Computer systems are first of all objects which are required to work correctly and independent of the subjects that created them. The assumption (or implicit goal) of objective knowledge and objective correctness is therefore in general useful for this research field. But this view is in stark contrast to the more <span>*subjectivist*</span> or <span>*constructivist*</span> view in psychology and CR. Realist and constructivist world views each have their role in science and engineering Peschl (2001), but the constructivist view is a better fit for topics such as learning or creativity. And some key notions from CR can only be fully appreciated within the constructivist view.

Divergent Thinking in Creativity Research
=========================================

The standard definition of <span>*creativity*</span> in CR is bipartite: Creativity requires both <span>*novelty*</span> (also called <span>*originality*</span>) and <span>*effectiveness*</span> Mark A. Runco and Jaegera (2012). Effectiveness is quite compatible with the realist/objectivist world view adopted in CC, but novelty poses some challenges. Where does novelty come from?

In human creativity, two different modes of thinking have been observed: <span>*Convergent thinking*</span> and <span>*divergent thinking*</span> Guilford (1950). Problem-solving as search Newell (1972) is a typical objectivist approach in AI and a good example of convergent thinking: First all relevant constraints are determined and then possible solutions are checked for their consistency with these constraints. The end result will then be the solution with the least amount of divergence from what was required.

Divergent thinking does the exact opposite: exploring multiple paths of thought seemingly irrelevant and even inconsistent with the task at hand and only later merging some of the paths into a new, potentially surprising, and eventually also consistent result. Divergent thinking temporarily ignores all the criteria of correctness and objectivity that are at the heart of computer engineering. And divergent thinking has been shown to be an integral part of human creativity Mark A. Runco and Acara (2012).

Convergent thinking is important for creativity as well. But the normal, convergent mode of thinking is reagarded as a given in CR, and the divergent mode as a special addition required for true creativity. Divergent thinking is seen at the core, divergent thinking at the periphery of creativity. The four P’s of creativity Rhodes (1961),Mark A Runco and Pritzker (1999) are a widely adopted framework of research consisting of Product, Person Process and Press. The Press portion stands for environmental and social constraints, which of course can only be accommodated with the appropriate amount of convergent thinking.

So the Press aspect of creativity can be seen as mandating a certain amount of realism/objectivism. But external constraints can also be interpreted from a radical constructivist point of view. In his highly influential study, Csikszentmihalyi Csikszentmihalyi (1997) has for instance argued, that creativity can only be evaluated against its social frame of reference, denying any realist aspect of creativity.

Radical constructivism is of course not suited for describing computer systems, since computer systems are expected to work correctly and autonomously. The kind of radical realism adopted in AI on the other hand is ill suited for understanding human creativity which relies on the subject’s ability of creating new and unexpected meaning. This does not imply that computer systems cannot be creative. It does however imply that the world view typically adopted in computing is inherently limited in its ability to describe and understand creativity. Divergent thinking is the one aspect of human creativity highlighting the shortcomings of the standard view of knowledge and meaning in computing: Any symbol, any meaning and the relevance of any information or assumption are up for re-interpretation in the divergent thinking stage of the creative process. $$HC^3$$ involves both human actors and computer systems, therefore a scientific model of $$HC^3$$ will have to accommodate both world views.

What a model could look like
============================

In spite of the objectivist/realist notions for describing computer systems, AI researchers have repeatedly argued that their models do not have to conform to the objectivist requirement of falsifiability formulated by Popper Popper (1935). Which assumptions from computing have been validated and should be incorporated in an integrated model?

Newells knowledge level hypothesis was for instance meant to be validated via the success of strong AI. Apart from rather technical implementation details on all the levels below the knowledge level, classical strong AI had only one falsifiable scientific hypothesis: That it would able to build intelligent robots and that it would be able to build them in a certain time frame. This one falsifiable hypothesis has turned out to be false and therefore the knowledge level hypothesis could be considered falsified.

But the research approach described by this hypothesis is still applied today, so his hypothesis should rather be regarded as a description of research culture. Rather than documenting all of their failures, computer engineers tend to modify their computer models until they arrive at a working prototype. Falsification has a very low priority in computing, to the degree that the criterion of falsifiability is argued to be irrelevant for instance in cognitive science Cooper (2007)

While such a form of scientific discovery might be appropriate for the development of purely artificial systems, it certainly cannot be applied to a phenomenon involving human actors. A scientific model of $$HC^3$$ has to incorporate falsifiable hypotheses.

![explicit convergent and divergent thinking roles<span data-label="fig:roles"></span>](polizei.eps "fig:") ![explicit convergent and divergent thinking roles<span data-label="fig:roles"></span>](zauberer.eps "fig:")

As opposed to the typical CC model, a model of $$HC^3$$ cannot be a computer model. The human and computer side of such an interaction are different and will have to be described in different ways. The objectivist/realist world view will be more suitable for describing the computer system, the subjectivist/constructivist view more suitable for describing the human partner. Their interaction will have to be described from both the human and computer perspective as well. The model should accommodate all the key notions from relevant research fields and describe compatible computer system properties. It should describe the interactions between humans and computers and the creative process. It should incorporate both an objectivist and a subjectivist understanding of knowledge and should explain the role of knowledge in the creative process.

I propose using an explicit description of human and computer <span>*roles*</span> as the starting point for such an integrated model. Human and computer partners might fulfill such a role in different ways, but in a creative co-operation, each partner should be able to perform identifiable roles at a given stage of the process (Fig.  [fig:roles]).

![human agent in divergent and computer agent in convergent roles<span data-label="fig:human-computer4"></span>](human-computer4.eps)

We know that humans cannot employ convergent and divergent thinking at the same time. If computers can in fact augment human creativity in the way described above, the computer partner should be able to augment the human partner by performing the matching, opposite role. The scenario described by Vannemar Bush can then be classified as the type of interaction with a human agent in the divergent and a computer agent in the convergent role (Fig.  [fig:human-computer4]).

If both agents are to operate on a joint representation of the creative task, they will have to share some sort of knowledge representation. If divergent and convergent roles are identifiable, their impact on this knowledge representation should be identifiable as well. I propose the terms <span>*diversion*</span> and <span>*consolidation*</span> for the effect of applying divergent and convergent thinking on knowledge representation. Diversion of knowledge involves selectively disconnecting symbols, meaning and information and re-creating connections irrespective of external and internal constraints. Consolidation of knowledge involves merging previously inconsistent symbols, meaning and information into a new consistency. Concept blending Pereira (2007) can for instance be seen as a type of knowledge consolidation.

![human agent in convergent and computer agent in divergent roles<span data-label="fig:human-computer5"></span>](human-computer5.eps)

In the general sense, this analysis is based on several hypotheses:

1.  $$HC^3$$ exists as a unique phenomenon

2.  Creativity as resulting from $$HC^3$$ can be measured in the same way as human creativity

3.  $$HC^3$$ is more than the sum of its parts: The creative co-operation of computer(s) and person(s) yield results that are either more creative or creative in a different way

4.  The $$HC^3$$ process has observable properties and has general properties independent of application domain

5.  the process of creative co-operation is different from other types of HCI

6.  $$HC^3$$ requires both convergent and divergent thinking

7.  divergent thinking involves the diversion of knowledge

8.  convergent thinking depends on the previous consolidation of knowledge

9.  human and computer partners can each perform the role of convergent or convergent agent, but in fundamentally different ways and never at the same time

10. Each step in the $$HC^3$$ process can be characterized by the flow of control and exchange of knowledge between human and computer partner

By such a deep integration of key research notions across disciplines, system properties such as openness or playfulness Voigt, Niehaves, and Becker (2012) can be analyzed in a systematic way, for instance as resulting from the availability of knowledge diversion tools. $$HC^3$$ is an iterative process, and in each of the process stages, human or computer can perform one of the following functions:

1.  diverge: multiple options are explored with little regard for consistency or correctness

2.  compare: intermediate results are compared against original requirements

3.  consolidate: previously inconsistent knowledge is blended into new consistent knowledge

4.  converge: consistent solutions are generated

Among other things, these hypotheses entail that a scenario opposite to those described in the previous sections should be equally feasible: The computer as divergent agent and the human as convergent partner. One scenario would be the diverging computer partner generating seemingly inconsistent material with the human partner selecting and finally merging some of this material into something new. (Fig.  [fig:human-computer5]).

If this model is correct, human and computer can be creative in very different ways. The properties for the design of creativity support systems will be different for each of these scenarios, but if these hypotheses are correct, some properties will be relevant for all of them. Neither human nor computer would have to be creative on their own. But if we want to identify Human-Computer Co-Creativity, then we should be able to identify the stages of such a process as well as the overall creative result.

Conclusion
==========

Human-Computer Co-Creativity is an old research goal which has seen renewed interest in the form of Creativity Support Tools in the last years. A general model of $$HC^3$$ would have to describe any kind of co-creativity and account for all relevant human and computer contributions as one system. Such a general model of the process of $$HC^3$$ is still missing.

Elements for such a model can be found in research fields for different aspects of $$HC^3$$. Therefore a synthesis of research results is an appropriate option for building a model. But the respective research communities are exhibiting fundamental differences in research culture and epistemology, which have to be acknowledged and considered. A unified model should include the key concept of divergent thinking and account for the processing and exchange of knowledge.

Explicit specification of roles played by human or computer partner can serve as a means for integrating these aspects. I am formulating the hypothesis that both human and computer can be the agents for either convergent or divergent thinking in the creative process. Verification or falsification of this model will depend on a mechanism for identifying these roles in an empirical setting.

Bush, Vannevar. 1945. “As We May Think.” *Atlantic Monthly*, July.

Chen, Chaomei. 2012. *Turning Points : The Nature of Creativity*. Springer.

Cooper, Richard P. 2007. “The Role of Falsification in the Development of Cognitive Architectures: Insights from a Lakatosian Analysis.” *Cognitive Science* 31 (3): 509–33.

Csikszentmihalyi, Mihaly. 1997. *Creativity - Flow and the Psychology of Discovery and Invention*. NY, USA: HarperPerennial.

Engelbart, Douglas C. 1962. *Augmenting Human Intellect - A Conceptual Framework*. AFOSR-3233. Menlo Park, CA, USA: Stanford Research Institute.

Guilford, Joy Paul. 1950. “Creativity.” *American Psychologist* 5: 444–54.

Hey, Tony, Stewart Tansley, and Kristin Tolle. 2009. *The Fourth Paradigm: Data-Intensive Scientific Discovery*. Microsoft Research.

Licklider, Joseph Carl Robnett. 1960. “Man-Computer Symbiosis.” *IRE Transactions on Human Factors in Electronics* HFE-1 (March): 4–11.

Newell, Allen. 1972. *Human Problem Solving*. Upper Saddle River, NJ, USA: Prentice-Hall, Inc.

———. 1982. “The Knowledge Level.” *Artificial Intelligence* 18 (1): 87–127.

Newell, Allen, and Herbert A. Simon. 1976. “Computer Science As Empirical Inquiry: Symbols and Search.” *Commun. ACM* 19 (3). New York, NY, USA: ACM: 113–26.

Pereira, Francisco Camara. 2007. *Creativity and Artificial Intelligence: A Conceptual Blending Approach*. Walter de Gruyter; Co. Hawthorne.

Peschl, Markus F. 2001. “Constructivism, Cognition, and Science: An Investigation of Its Links and Possible Shortcomings.” *Foundations of Science* 6 (1-3).

Popper, Karl. 1935. *Logik Der Forschung*. Springer.

Rhodes, Mel. 1961. “An Analysis of Creativity.” *The Phi Delta Kappan* 42 (7): 305–10.

Runco, Mark A, and Steven R Pritzker. 1999. *Encyclopedia of Creativity*. Elsevier.

Runco, Mark A., and Selcuk Acara. 2012. “Divergent Thinking as an Indicator of Creative Potential.” *Creativity Research Journal*.

Runco, Mark A., and Garrett J. Jaegera. 2012. “The Standard Definition of Creativity.” *Creativity Research Journal* 24 (1): 92–96.

Shannon, Claude Elwood. 1948. “A Mathematical Theory of Communication.” *Bell System Technical Journal* 27: 379–423 and 623–56.

Shneiderman, Ben, Gerhard Fischer, Mary Czerwinski, Mitch Resnick, Brad Myers, Linda Candy, Ernest Edmonds, et al. 2006. “Creativity Support Tools: Report From a U.S. National Science Foundation Sponsored Workshop.” *International Journal of Human-Computer Interaction* 20 (2).

Voigt, Matthias, Björn Niehaves, and Jörg Becker. 2012. “Towards a Unified Design Theory for Creativity Support Systems.” In *Design Science Research in Information Systems: Advances in Theory and Practice*. Springer.


