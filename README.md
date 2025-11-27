# Conjugate Product Graphs for Globally Optimal 2D-3D Shape Matching 

Official implementation of [Conjugate Product Graphs for Globally Optimal 2D-3D Shape Matching](https://arxiv.org/pdf/2211.11589.pdf) (by Paul Roetzer, Zorah Lähner, Florian Bernard, CVPR, 2023).

<img src="data/teaser.png"  width="640"></img>


### Installation ⚙️
This project requires [gptoolbox](https://github.com/alecjacobson/gptoolbox) (click on link and follow instructions on how to install on your machine). 
Furthermore, follow **one** of the two options.

1️⃣ Either clone project from git:
- open terminal at desired location
- `$ git clone git@github.com:paul0noah/sm-2D3D.git`
- `$ git submodule update --init`

2️⃣ Or download zip file from git:
- Download this project and extract
- Download and extract [eigen](https://gitlab.com/libeigen/eigen)
- Copy `eigen-master` folder into `dijkstraCG/` folder of this project and rename `eigen-master -> eigen`

### Usage 🤔
The file `experiment_dijkstra.m` contains an example script on how to use this code.

### Attribution 🎓
When using this code for your own projects please cite the followig:
- Roetzer et al.: Conjugate Product Graphs for Globally Optimal 2D-3D Shape Matching, CVPR 2023
- Lähner et al.: Efficient Globally Optimal 2D-to-3D Deformable Shape Matching, CVPR 2016

### License 🚀
This repo is licensed under MIT licence.


