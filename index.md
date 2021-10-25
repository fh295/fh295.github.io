
# Grounded language understanding

<div style="float: left;">
<iframe width="450" height="315" src="https://www.youtube.com/embed/iuihBGAGI3M?controls=0&amp;start=5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

My work aims to build computational models that exhiibit human-like understanding of language and its relationship to perception and action. 

<br/>

## Recent work from the Grounded Language group at DeepMind

### [Multimodal few-shot learning with frozen language models](frozen.md)
Click on the link above to donwload the evaluation datasets from our [recent paper](https://arxiv.org/abs/2106.13884).

[The systematicity and generalization of situated agents is enhanced by their rich learning experience](https://arxiv.org/abs/1910.00571); in particular their egocentric, first-person perspective.

With [a dual-coding episodic memory system](https://arxiv.org/abs/2009.01719), situated language agents can learn new word-object bindings in a single shot, and integrate this knowledge into policies that lift and place those objects as instructed.

Large text-based language models can be adapted to exhibit similar fast visual binding (aka *multimodal few-shot learning*) using [a simple Frozen method](https://arxiv.org/abs/2106.13884).

With a [hierarchical memory system](https://openreview.net/forum?id=wfiVgITyCC_&referrer=%5BAuthor%20Console%5D(%2Fgroup%3Fid%3DNeurIPS.cc%2F2021%2FConference%2FAuthors%23your-submissions)), agents can extend this ability in many ways, solving and generalizing over long-horizon binding tasks.

Situated language agents learn faster by [exploiting multiple complementary learning algorithms](https://arxiv.org/abs/1710.09867), a notion inspired by [human language learning](https://www.ncbi.nlm.nih.gov/pubmed/7624455). 

Flexible spatio-temporal reasoning across three challenging tasks with [a simple neural architecture based on soft-object embeddings, self-attention and self-supervised learning](https://openreview.net/forum?id=lHmhW2zmVN&referrer=%5BAuthor%20Console%5D(%2Fgroup%3Fid%3DNeurIPS.cc%2F2021%2FConference%2FAuthors%23your-submissions)).

[AGILE](https://arxiv.org/pdf/1806.01946.pdf), an algorithm that jointly learns a instruction-conditioned reward function and a policy for realising that instruction. This provides a solution to a critical challenge for training agents to follow language commands; that the truth conditions of most linguistic expressions are typically [very hard to express formally](https://en.wikipedia.org/wiki/Philosophical_Investigations) (e.g. in a programmed reward function). 

<br/>

## Why situated language learning?

Children learn to understand language while learning to [perceive, interact-with, explain and make predictions about the world around them](http://psycnet.apa.org/record/1973-30971-000). Our linguistic knowledge depends critically on [sensory-motor and perceptual processes](https://www.tandfonline.com/doi/abs/10.1080/17470210701623605), which in turn are influenced and shaped by our language. 

Our team at DeepMind has pioneered research into [agents that learn the meaning of words and short phrases as they pertain to perceptual stimuli and complex action sequences](https://arxiv.org/abs/1910.00571) in [3D worlds](https://github.com/deepmind/lab). These agents naturally compose known words to successfully interpret never-seen-before phrases, a trait that matches the productivity of human language understanding. 

## Understanding through perception, abstraction and analogy

<img align="left" src="matrices-opt.gif" width="200" hspace="20">

A child might learn what *growing* means by observing a sibling, a pet or a plant get bigger, but once understood, the same idea of growing can be applied to pocket money, a tummy ache or Dad’s age. This ability to represent relations, principles or ideas like *growing* with sufficient abstraction that they can be flexibly (re-)applied in disparate, and potentially unfamiliar, contexts and domains is [central to human cognition, analogical reasoning and language](https://www.youtube.com/watch?v=n8m7lFQ3njk). 

Colleagues and I have shown that neural networks that combine raw perception from pixels, together with components for reasoning across discrete sets of images, can exhibit strong analogical reasoning and impressive generalisation [if trained in a particular way](https://openreview.net/pdf?id=SylLYsCcFm). Similar models can also be trained to solve visual reasoning tasks [that challenge even the most able humans](https://arxiv.org/abs/1807.04225); our dataset of these problems is available for further research [here](https://github.com/deepmind/abstract-reasoning-matrices).

<br/>
<br/>
## Generalisation in neural networks
Models with strong inductive bias suited to a particular problem can exhibit impressive generalisation on domains related to that problem. On the other hand, more general architectures with greater variance may be effective on a wider range of problems, but may need a [specific curriculum of training experience](https://openreview.net/pdf?id=SylLYsCcFm) in order to exhibit strong generalisation. Hybrid approaches, such as our [Neural Arithmetic Logic Unit](https://arxiv.org/abs/1808.00508), can represent the best of both worlds; the unit itself introduces a strong inductive bias suited to the extrapolation of numerical quantities, but models that include NALUs alongside conventional architectural components can retain general applicability to non-numerical problems as well.

<br/>
<br/>
## Language understanding from text

![alt text]({{ site.url }}/dictionary.png)

During my PhD, I worked with [Anna Korhonen](http://www.cl.cam.ac.uk/~alk23/) on ways to extract and represent meaning from text and other language data in distributed representations. I developed FastSent and Sequential Denoising Auto-Encoders, ways to learn [sentence representations from unlabelled text](http://www.aclweb.org/anthology/N16-1162). With [Yoshua Bengio](http://www.iro.umontreal.ca/~bengioy/yoshua_en/) and [Kyunghyun Cho](http://www.kyunghyuncho.me/home), I noticed you can train a network on [dictionary definitions](http://www.aclweb.org/anthology/Q16-1002) to [solve general-knowledge crosswords clues](https://docs.google.com/gview?url=http://www.cl.cam.ac.uk/~fh295/crossword.pdf). With [Jase Weston](https://research.fb.com/people/weston-jason/) and [Antoine Bordes](https://research.fb.com/people/bordes-antoine/) I applied neural networks with external memory components to answer questions about [passages in books](https://arxiv.org/pdf/1511.02301.pdf). I also made [SimLex-999](simlex.html) a way to measure how well distributed representations of words reflect human semantic intuitions, and recently helped to develop the [GLUE benchmark](https://gluebenchmark.com/) for evaluating models of language understanding.    

<br/>

## What about compositionality?

I think natural language is interesting because, unlike formal languages, mathematics or logic, it is isn't in general *compositional*. Many people, on the other hand, say that language is interesting because it *is* compositional. My micro-blog [NonCompositional](noncompositional.md) that discusses some of these issues.

<br/>

## [Teaching](teaching.md)


With [Steve Clark](https://sites.google.com/site/stephenclark609/) I taught a Master's course [Deep Learning for NLP](teaching.md) at the Computer Laboratory, Cambridge University in 2018. If you follow that link you can find the synopsis, lecture slides and [Tensorflow code for training neural networks on dictionary definitions](https://github.com/fh295/Cambridge_DL4NLP). We got nice feedback, and hope to do the course again (somewhere) soon. 

<br/>
## Videos and lectures


* [Deep Learning for NLP](https://www.youtube.com/watch?v=8zAP2qWAsKg) as part of the DeepMind UCL Lecture series. 

* [Humans of AI Interview with Dhruv Batra](https://youtu.be/qmV2mLHuvMU).

* Kenote address, [Mexican International Meeting on Artificial Intelligence](https://riiaa.org/transmision/) (in Spanish), August 2018.

<br/>
### Other stuff

I started doing [cognitive science](https://onlinelibrary.wiley.com/doi/abs/10.1111/cogs.12076) before I did any computational linguistics. And before that, I got Bachelors and Masters degrees in [pure maths](https://www.ox.ac.uk/admissions/undergraduate/courses-listing/mathematics-and-philosophy?wssl=1).

See [Google Scholar](https://scholar.google.com/citations?user=4HLUnhIAAAAJ&hl=en) for a list of publications.

When not working, things I like to do include football, running, yoga, [travelling](http://www.roadjunky.com/2078/backpackers-behind-bars-a-morning-in-quito-prison/) and [relaxing](http://www.roadjunky.com/2087/zen-at-work-vipassana-an-indian-meditation-bootcamp/).


