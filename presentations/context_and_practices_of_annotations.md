% Evaluating Practices and Context of Annotations
% Niels-Oliver Walkowski - @cutuchiqueno
% 29th of October 2015

# Goal

- context solidified in annotation functions
- practice as annotations within research activity 

<div class="notes">

I am not presenting work of my own today, but I want to outline 2 approaches  which I think are useful for the topic of this workshop and which wouldn't be presented otherwise today

More  precisely, I want to speak about the work of Chia-Ning Chiang and the recently published Scholarly Domain Model by Stefan Gradmann

</div>
 
# "A Multi-Dimensional Approach to the Study of Online Annotation"

- Chiang, Chia-Ning, 2010
- compares historical and digital annotations
- asks for the benefit of digital annotations
- conducts an empirical study
- defines a functional classification scheme for annotations

<div class="notes"> 

In 2010 Chiang did a quiet comprehensive dissertation in which she tries to answer the question if thereis a benefit of digital annotations compared to historical annotations?

Her course of action includes:
an evaluation of research literature which focus on the classification of annotations
an empirical study on annotation usage on web annotations in literature studies
and finally an **Annotation Function Coding Scheme**

</div>

# Dimensions of Annotations

1. form
2. function
3. role
4. value

<div class="notes">

On the top level she argues that annotations can be evaluated within in 4 dimensions.

- Form refers to the appearance of annotations like highlighting, underlining but also shape, color and so forth
- Function is defined by Chiang as 'users cognitive states of annotating' which sounds a bit mystical but refers to the intention that lead to the creation of the annotation. In Open Annotation it is called motivation.
- Role tackles the intended audience or the scope of dissemination which is intended for the annotation. Maristella Agosti more clearly labels this aspect visibility

Finally, the value dimension. This dimension is specifically proposed by Chiang. It describes the quantity and quality of the  reuse of an annotation.

It looks like this dimension is kind of inconsistent because it can only be analyzed a posteriori. However, in the empirical part of her research Chiang shows that the intended role and the measerable value correlates so that there also seems to be an a priori aspect in the dimension of value

</div>

# Binaries

| Form            | Function              | Role              | Value                 |
| --------------- | --------------------- | ----------------- | --------------------- |
| formal/informal | as writing/as reading | published/private | often/rarely used     |
| explicit/tacit  | extensive/intensive   | global/personal   | high/low rated        |
|                 | permanent/transient   |                   | easy/difficult to use |

<div class="notes">

by following Catherine Marshall she argues that each facet holds certain binaries and Annotations can be evaluated on a scale between them.

For instance writin/reading can be read metaphorically as annotations which facilitate the creation of output or annotations which process input

The binarie of extensive and intensive annotations refer to something at the surface of the resource and those which refer to abstract or interpretative things.

</div>

# Relations Between Aspects of Analysis

- form and content does not consistently define annotation function
- role is crucial for meaning in annotations
- meaning of annotations depend on its position in an annotation network (Agosti, 2007)

<div class="notes">

On the basis of this framework Chiang analyzes the results of her empirical research and defines her "Annotation Function Coding Scheme"

However, the fundamental insight from her research is another one. On the way to the scheme she investigates that:

- a function of an annotation does not consistently correlate with its form and content
- the same content, function and form may have different meaning influenced by role

at this point we might alsoadd Maristella Agosti's claim that the meaning of an annotation depends on its position in relation with other annotations in an annotation process. She calls this the dialogical dimension of annotations

In short, to fully understand concrete annotations we need to consider all of their dimensions. And this is what makes the great challenge from an infrastructure and standardisation point of view which focus on the archiving, reuse, sharing and interoperability of annotation data.

</div>

# Annotation Function Coding Scheme

| to remember                                   | to think                        | to clarify       | to communicate                  |
| --------------------------------------------- | ------------------------------- | ---------------- | ------------------------------- |
| to signal                                     | to record interpretation        | to clarify       | to write a personal note        |
| to place mark                                 | to work on a problem in context | to recapitulate  | to share annotation with others |
| to mark the logical structure of the document | to identify connecting ideas    | to differentiate |                                 |
|                                               | to record incidental reflection |                  |                                 |

<div class="notes">

At the end of this section just a quick overview about the first two levels of Chiang's scheme which organises annotation function in a three-dimensional hierarchical way.

</div>

# Summary Chiang

- the benefit of formal approaches is to participate computationally framed discourse that is going on
- many theoretical enquiries on digital annotation work on common annotation scenarios in digital environments

<div class="notes">

Approaches like the one of Chiang despite any issues that could be raised like usability and expressiveness are still important in my perspective.

The general question is not so much how usable these schemes are in everyday research. The issue is that in fields like Digital Humanities and e-science these activities take place now. Open Annotation has defined a vocabulary for contextual function oriented metadata of annotations - and I argued else where that it is insufficient.

Projects like DARIAH or the Humanities Data Center structurally define what we will know about annotation data in case it becomes more an more common to share them in these environments.

Finally, we need such approaches to use them as discursive tools which can be used computationally to demonstrate the complexity of annotation practices in the Humanities to infrastructure projects or sciences. From an EUDAT Workshop 2 years ago in which I participate I can tell that this is not particularly easy.

On the other hand too many of these activities do not include a comprehensive overview of all the new scenarios in which annotations are used. Chiang asks about the benefit of digital annotations but her use case is the well settled example of text reading and interpretation in the browser.

</div>

# Pelagios {.bgvideo data-background-video="resources/pelagios.mp4"}

<div class="notes">

In this respect I might quickly give the example of Pelagios which produce annotations as a primary research output to map resources of the ancient world from cultural heritage organisations to places

</div>

# YUMA {.bgvideo data-background-video="resources/yuma.mp4"}

<div class="notes">

another project is Yuma from EUROPEANA which uses annotations to calibrate and geo-reference historical maps on the fly

Dirk Roorda, who will present later on propose to create queries as annotations, thus annotations which potentially have a dynamic body

</div>

# Bélanger: Annotations and the Digital Humanities (2010)

> Annotation, a type of information work primitive, functions as an articulation device, aligning the different levels, activities and indeed, the different phases of work necessary to the completion of a project.

<div class="notes">

So let's go now from context as function to practice. 

Marie-Eve Bélanger in her summary on "Annotations and the Digital Humanities" defines Annotations as QUOTE

Accordingly she proposes to evaluate annotations in the context of the structure of a research processes

There are 2 initiatives which do this within the Humanities at the moment - generally, but also for annotations - the NeMO and SDM

</div>

# Scholarly Domain Model - SDM

- Gradmann, Stefan et al.. “Beyond Infrastructure! Modelling the Scholarly Domain,” (2015).
- EUROPEANA, DM2E
- goal: a conceptual tool to monitor research activity to keep infrastructure informed

<div class="notes">

Since NeMO will be presented later on, I will focus on SDM. SDM was developed in the EUROPEANA associated DM2E project.

It was created in an infrastructure project, but the title with which it was published is 'beyond infrastructure'. Accordingly, its Goal is to have a conceptual tool to continuously analyse research activity to keep infrastructure informed and to enable its dynamic adaptation.

</div>

# Layers

![SDM Layers](resources/layers.png "SDM Layers")

<div class="notes">

Primarily SDM models scholarly practice in 4 levels of abstraction
These levels are Areas, Scholarly Primitives, Scholarly Activities and Scholarly Operations

There are two important remarks to make:

- there is neither a fixed nor a one2one relation between elements in the different layers
- additionally there is a logical distinction between the first 3 layers and the last one

this distinction is inspired by an idea of Clifford Geertz who distinguished between modeling-for and modeling-of
modeling-for are models which are used to realize a goal, like a working plan
modeling-of are models that should represent something, in our case the research process
we come back to this issue when we look at operations

</div>

# Areas

![Areas](resources/areas.png "Areas")

<div class="notes">

Areas are the upper most layer
they are not a general classification of research activities but of spheres in which activities take place or which  influence these activities.
Arease are: input, output, documentation, social and of cause research itself
Just some clarification on the social and the documentation are
social activities can be activities like the ones emphasized by Actor-Network-Theory, but also very mundane ones like the style of citation
documentation can be things like progress reports but also code documentation, version control in DH projects which of cause are also all outputs that comply with certain social demands

From the arrows We see that process is not meant to be linear but a circular dynamic which touches influence zones

</div>

# Scholarly Primitives

## John Unsworth: Scholarly Primitves (2000)

> Discovering, Annotating, Comparing, Referring, Sampling, Illustrating, Representing

<div class="notes">

Scholarly Primitives are taken from John Unsworth. They are very prominent within Digital Humanities and were an attempt to identify meta-activities of humanities research for what was then called Humanities Computing

</div>

# Scholarly Activities

> … citing, referring, annotating, selecting, writing, assembling, notetaking, illustrating, sharing, publishing …

<div class="notes">

Below Scholarly Primitives there are 26 so called Scholarly Activities of which I just give some examples. Activities are still abstract but a bit more substantial than Primitives. 
For example citing is a more definite concept than referring.

The important thing is, that activities do not necessarily have a one to one relation to primitives. Additionally the list provided by SDM is not meant to be complete but open

</div>

# Scholarly Operations

- operations realise the *modeling for* part of modeling
- operations are defined within research ...
- ... by referring to the other layers

<div class="notes">

So here comes the interesting part. There are no scholarly operations defined within SDM. We remember the distinction between modeling for and modeling of. Scholarly Operations belong to modeling for which means that operations are defined in a specific research process by referring to the other layers in one or multiple ways.

</div>

# the pund.it {.bgvideo data-background-video="resources/pundit.mp4"}

<div class="notes">

Let's take the pund.it example described by the SDM itself.

1. annotation is activity
2. pund.it is a tool that implements this annotation activity
3. the wittgenstein source project uses the pund.it for specific purposes on specific material, including a specific rdf vocabulary to use on the material.
4. The entanglement between aspects of areas, primitives and activities make it possible to define the operation
5. the operation that was defined in Wittgenstein Source together with the sequence of other operations outlines the state of annotation in this research project

</div>

# SDM Summary 

- the *modeling-for*/*modeling-of* distinction within the same model is a promising approach
- this approach is not worked out consistently in SDM
- the *modeling-for* layer is just an empty box
- the illustration of how the model works is a simplistic top-down approach - at least at the moment

<div class="notes">

Actually, the SDM with its two folded approach on modeling is a quiet interesting and promising approach. The evaluation of concrete research processes receive some kind of orientation while they are not stifled by the model and maintain autonomy.

Nonetheless, there are some issues which prevent to fully exploit the potential of this approach. Putting aside the complexity of the model and some inconsistencies between the layers of primitives and activities there are two weaknesses:

First point: Although the layer of operations should not be more than the playing field, it would still be useful to have something to play with. I don't mean further specifications of the upper levels but entities like actor, action, resource and so forth, which are vaguely referenced in the Primer but not really contoured. We will see later on today that this is where NeMO will step in.

Second, there is no practical guidance of how the bi-directional enrichment between the spheres of modeling-of and modeling-for may work out. The Primer is just showcasing it, using the Wittgenstein Source example. However, this example is a typical top-down application. It presupposes a pretty clear idea of annotation and outsources all the uncertainty about annotating we feel to day to a lower level and the simplistic question of what ontology you import. Thus, the example is simplistic, not representative and eliminates the creative tension between modeling approaches introduced at the beginning.

</div>

# Conclusion

> modeling is the goal, not the model (Gradmann, 2015)

## for whom and for what?

<div class="notes">

We saw two different approaches to evaluate practices and context of annotations. While concluding on Chiang I already argued that yes there are many reasons to work formally on these issues. The discursive one is again highlighted by Gradmann, saying QUOTE.

However, the issues with SDM showed that it is important to ask modeling for whom and for what purpose: For infrastructure projects and their effort to offer services, for projects which like to re-use annotation data from third-parties or for researchers on their personal track to knowledge. A sound model of annotations that is productive and usable at the same time would probably look very different in all of these cases because being productive and being usable are different things for different projects. Accordingly, we also should evaluate more which approach to modeling we need for which purpose or set-up. And with approach I don't just mean a structural type of model but the role ofmodeling itself.

</div>

# Thank you!

*presented with reveal.js*

slides and speakers notes at: <https://github.com/Cutuchiqueno/output>


