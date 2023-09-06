<img src="https://github.com/SanDiegoMachineLearning/bookclub/blob/master/images/graph.jpg?raw=true" width="160">

## Machine Learning with Graphs

[Houston ML](https://www.meetup.com/Houston-Machine-Learning/) and the SDML book club started discussing *Machine Learning with Graphs*, 
based on the Stanford course CS224W, in January 2022. 

### Slides and videos
Below are the slides and direct recording links.  All of the videos are on the [YanAITalk YouTube channel](https://www.youtube.com/channel/UCihndsiX0k7uT3UXBdw0Mmg/videos)

Session 1:  **Introduction to Graphs and Their Applications** \
In the kickoff [Meetup](https://www.meetup.com/San-Diego-Machine-Learning/events/283431771/), 
we introduced graphs, talked about how they differ from images and text, 
and saw example applications of graph ML. \
Here are the [slides](./graph/01-intro.pdf), 
the [first video about why graphs](https://youtu.be/vQDMq8iahG0), and the [second video about applications of graphs](https://youtu.be/NDGHhUwlGpY).

Session 2:  **Traditional Methods for ML on Graphs** \
Meetup:  [Session 2](https://www.meetup.com/San-Diego-Machine-Learning/events/283621781/) \
We begin our journey with a look at algorithms to generate hand-crafted features for graph ML problems. \
Links for the [Slides](./graph/graphml-02-traditional-ml.pdf) and the [Jupyter notebook](./graph/traditional-ml.ipynb). 
There are three videos:  [node features](https://youtu.be/Jg1xZdHX9Xk), [link-level features](https://youtu.be/O1R2FVpvzMc), and [graph-level features](https://youtu.be/cVOQig51wqI).

Session 3:  **Node Embeddings** \
Meetup:  [Third event](https://www.meetup.com/San-Diego-Machine-Learning/events/283976180/) \
Generalized representations (shallow embeddings) learned for nodes in a graph. \
The [Stanford slides](http://web.stanford.edu/class/cs224w/slides/03-nodeemb.pdf), the [notebook](./graph/node-embeddings.ipynb) with examples,
and the [video](https://youtu.be/IRnV5LqxNfU).

Session 4:  **Link Analysis: PageRank** \
Meetup:  [Fourth session](https://www.meetup.com/San-Diego-Machine-Learning/events/284277972/) \
The PageRank algorithm, as well as variations such as personal PageRank. \
These are the [slides from the meetup](./graph/04-pagerank.pdf). 
The recording was broken into four short videos on Yan's YouTube channel:  [PageRank introduction](https://youtu.be/gKh0Du3knr8), [How to solve](https://youtu.be/DSZrkPTVIHk), [Personalization](https://youtu.be/TqIegZgCJ9Y), and [Coding example](https://youtu.be/Ez4HgtK95_c).
Here is [Yan's Colab notebook](https://colab.research.google.com/drive/1RUOMmm7QFmg8sqLVm2_yz8EcZdCOJfk0?usp=sharing) that was demonstrated.

Session 5:  **Graph Neural Networks 1: GNN Model** \
Meetup:  [Fifth webinar](https://www.meetup.com/San-Diego-Machine-Learning/events/284595271/) \
In this session, we introduce graph neural networks (GNNs), which combine node features and graph structure in learning about graphs.
This week we will introduce the GNN model, and the following session will flesh out more details about what GNNs look like. \
[Slides](./graph/graphml-05-GNN1.pdf) and [video](https://youtu.be/00N96dXw_MA)

Session 6:  **Graph Neural Networks 2: Design Space** \
Meetup:  [Sixth event](https://www.meetup.com/San-Diego-Machine-Learning/events/284891007/) \
This week, we explore various choices for designing graph neural networks (GNNs),
including choices for aggregation and update within each layer and options to stack layers. \
The [Stanford slides](http://web.stanford.edu/class/cs224w/slides/07-GNN2.pdf) and the [video](https://youtu.be/TzgDRvvXKP4).

Session 7:  **Graph Neural Network Augmentation & Training** \
Meetup:  [Seventh event](https://www.meetup.com/San-Diego-Machine-Learning/events/285143856/) \
Please note, due to scheduling conflicts, this event is **three** weeks after the previous session (not two weeks). \
[Slides](./graph/GNN-application.pdf) and [video](https://youtu.be/ILvlEbLF_oo)

Session 8:  **Community Structure in Networks** \
Meetup:  [Eighth session](https://www.meetup.com/San-Diego-Machine-Learning/events/285484986/) \
We take a brief break from GNNs to discuss how communities form in networks and to look at some community detection algorithms. \
[Slides](./graph/graphml-communities.pdf) - see the second to last slide for links to the algorithm papers.
And the [video recording](https://youtu.be/AExBGCjoIVg).

Session 9:  **Scaling Up GNNs** \
Meetup:  [Ninth webinar](https://www.meetup.com/San-Diego-Machine-Learning/events/285744577/) \
Approaches to training GNNs for extremely large graphs. \
Link to the [Stanford slides](http://web.stanford.edu/class/cs224w/slides/17-scalable.pdf) and [video](https://youtu.be/perS-mvoBDw)

Session 10:  **Deep Generative Models for Graphs** \
Meetup:  [Tenth meetup](https://www.meetup.com/San-Diego-Machine-Learning/events/286065719/) \
This session, we look at generating synthetic graphs that are realistic.

Session 11:  **Knowledge Graph Embeddings** \
Meetup:  [Eleventh session](https://www.meetup.com/san-diego-machine-learning/events/286327091/) June 18, 12:00 PDT / 2:00 CDT \
This will be the first of two sessions talking about knowledge graphs.


Remainder of the schedule:
* Knowledge Graph Embeddings
* Reasoning over Knowledge Graphs
* Specific application coding tutorial(s)


### Resources
* The main website for the Stanford course CS224W is http://web.stanford.edu/class/cs224w/.
* The primary text is [Graph Representation Learning](https://www.cs.mcgill.ca/~wlh/grl_book/) by William L. Hamilton. 
This material supports the slides, and in some cases goes into further depth.
* In our meetup, supplemental coding examples will be drawn from [Graph Machine Learning](https://www.amazon.com/dp/1800204493) by Claudio Stamile et al.
The notebooks for this book can be found at https://github.com/PacktPublishing/Graph-Machine-Learning.
* The Fall 2021 videos of Prefessor Lescovec are available from this YouTube playlist:  https://www.youtube.com/playlist?list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn
* Tutorials and Colab notebooks for PyTorch Geometric (PyG) can be found here:  https://pytorch-geometric.readthedocs.io/en/latest/notes/colabs.html
* The above PyG page includes a link to student tutorials from the CS224W class on various graph ML topics:  https://medium.com/stanford-cs224w


<br>
<br>
