

### I work on replicating in artificial systems how we as humans ***learn***, ***represent*** and ***use*** language
<br/>
## Embodied language learning

<div style="float: left;">
<iframe width="230" height="170" src="https://www.youtube.com/embed/wJjdu1bPJ04?rel=0&amp;controls=0&amp;showinfo=0;start=6&autoplay=1" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</div>

<div style="float: left; margin-left: 20px;">
<iframe width="230" height="170" src="https://www.youtube.com/embed/9vY8D4wuEV0?rel=0&amp;controls=0&amp;showinfo=0;start=45&autoplay=1" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</div>
<div style="clear:both;"></div>

Children learn to understand language while learning to [perceive, interact-with, explain and make predictions about the world around them](http://psycnet.apa.org/record/1973-30971-000). Our linguistic knowledge depends critically on [sensory-motor and perceptual processes](https://www.tandfonline.com/doi/abs/10.1080/17470210701623605), which in turn are influenced and shaped by our language. My work simulates this process of acquiring language jointly with perceptual and motor processes as a path to realistic language understanding in fully embodied systems. With many brilliant collaborators at Deepmind, I have developed [agents that can learn the meaning of words and short phrases as they pertain to perceptual stimuli and complex action sequences](https://arxiv.org/pdf/1706.06551.pdf) in continuous [3D worlds](https://github.com/deepmind/lab). These agents naturally compose known words to successfully interpret never-seen-before phrases, a trait that matches the productivity of human language understanding. Further analysis showed that learning is much more efficient if agents [exploit multiple complementary learning algorithms](https://arxiv.org/abs/1710.09867), another property of [human language learning](https://www.ncbi.nlm.nih.gov/pubmed/7624455). We developed [AGILE](https://arxiv.org/pdf/1806.01946.pdf), an algorithm that jointly learns a instruction-conditioned reward function and a policy for realising that instruction. This provides a solution to a critical challenge for training agents to follow language commands; that the truth conditions of most linguistic expressions are typically [very hard to express formally](https://en.wikipedia.org/wiki/Philosophical_Investigations) (e.g. in a programmed reward function). 

<br/>
## Perception, abstraction and analogy

<img align="left" src="matrices-opt.gif" width="200" hspace="20">

A child might learn what *growing* means by observing a sibling, a pet or a plant get physically bigger, but once understood, the same idea of growing can be applied to pocket money, a tummy ache or Dad’s age. This ability to represent relations, principles or ideas like *growing* with sufficient abstraction that they can be flexibly (re-)applied in disparate, and potentially unfamiliar, contexts and domains is [central to human cognition, analogical reasoning and language](https://www.youtube.com/watch?v=n8m7lFQ3njk). My work has shown that neural networks that combine raw perception from pixels, together with components for reasoning across discrete sets of images, can exhibit strong analogical reasoning and impressive generalisation [if trained in a particular way](https://openreview.net/pdf?id=SylLYsCcFm). Similar models can also be trained to solve visual reasoning tasks [that challenge even the most able humans](https://arxiv.org/abs/1807.04225); our dataset of these problems is available for further research [here](https://github.com/deepmind/abstract-reasoning-matrices).

<br/>
<br/>
## Measuring generalisation in neural networks
I don't think it makes sense to attribute good or bad generalisation to a particular model, model class or functional form. Models with strong inductive bias suited to a particular problem can exhibit impressive generalisation on domains related to that problem. On the other hand, more general architectures with greater variance may be effective on a wider range of problems, but may need a [specific curriculum of training experience](https://openreview.net/pdf?id=SylLYsCcFm) in order to exhibit strong generalisation. Hybrid approaches, such as our [Neural Arithmetic Logic Unit](https://arxiv.org/abs/1808.00508), can represent the best of both worlds; the unit itself introduces a strong inductive bias suited to the extrapolation of numerical quantities, but models that include NALUs alongside conventional architectural components can retain general applicability to non-numerical problems as well.

<br/>
<br/>
## Language understanding from text

![alt text]({{ site.url }}/dictionary.png)

During my PhD, I worked with [Anna Korhonen](http://www.cl.cam.ac.uk/~alk23/) on ways to extract and represent meaning from text and other language data in distributed representations. I developed FastSent and Sequential Denoising Auto-Encoders, ways to learn [sentence representations from unlabelled text](http://www.aclweb.org/anthology/N16-1162). With [Yoshua Bengio](http://www.iro.umontreal.ca/~bengioy/yoshua_en/) and [Kyunghyun Cho](http://www.kyunghyuncho.me/home), I noticed you can train a network on [dictionary definitions](http://www.aclweb.org/anthology/Q16-1002) to [solve general-knowledge crosswords clues](https://docs.google.com/gview?url=http://www.cl.cam.ac.uk/~fh295/crossword.pdf). With [Jase Weston](https://research.fb.com/people/weston-jason/) and [Antoine Bordes](https://research.fb.com/people/bordes-antoine/) I applied neural networks with external memory components to answer questions about [passages in books](https://arxiv.org/pdf/1511.02301.pdf). I also made [SimLex-999](simlex.html) a way to measure how well distributed representations of words reflect human semantic intuitions, and recently helped to develop the [GLUE benchmark](https://gluebenchmark.com/) for evaluating models of language understanding.    

<br/>
## [Teaching](teaching.md)


With [Steve Clark](https://sites.google.com/site/stephenclark609/) I taught a Master's course [Deep Learning for NLP](teaching.md) at the Computer Laboratory, Cambridge University in 2018. If you follow that link you can find the synopsis, lecture slides and [Tensorflow code for training neural networks on dictionary definitions](https://github.com/fh295/Cambridge_DL4NLP). We got nice feedback, and hope to do the course again (somewhere) soon. 

<br/>
## Recent talks

* Kenote address, First [Mexican International Meeting on Artificial Intelligence](https://riiaa.org/transmision/) (in Spanish), August 2018.

* Kenote address, 39th [TabuDag](https://www.let.rug.nl/tabudag/keynotes.php) meeting of linguists, Groningen, Netherlands, June 2018. 

* Video talks @ MSR Redmond (2016) and ICLR 2016, San Juan, Puerto Rico.
<div style="float: left; margin-left: 5px;">
<iframe width="230" height="180" src="https://www.youtube.com/embed/a0BVuPCjqyg?start=10" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</div>
<div style="float: left; margin-left: 20px;">
<a href="http://videolectures.net/iclr2016_hill_goldilocks_principle/">
<img border="0" alt="W3Schools" src="http://videolectures.net/iclr2016_hill_goldilocks_principle/thumb.jpg" width="230" height="180"></a>
</div>
<div style="clear:both;"></div>

<br/>
### Other stuff

I started doing [cognitive science](https://onlinelibrary.wiley.com/doi/abs/10.1111/cogs.12076) before I did any computational linguistics. And before that, I got Bachelors and Masters degrees in [pure maths](https://www.ox.ac.uk/admissions/undergraduate/courses-listing/mathematics-and-philosophy?wssl=1).

See [Google Scholar](https://scholar.google.com/citations?user=4HLUnhIAAAAJ&hl=en) for a list of publications.

When not working, things I like to do include football, running, yoga, [travelling](http://www.roadjunky.com/2078/backpackers-behind-bars-a-morning-in-quito-prison/) (but [not arriving](https://felix-india2009.blogspot.com/2009/06/paranoia-of-solo-travel.html)) and [relaxing](http://www.roadjunky.com/2087/zen-at-work-vipassana-an-indian-meditation-bootcamp/).


