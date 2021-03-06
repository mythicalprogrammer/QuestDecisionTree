# QuestDecisionTree 
Quest decision tree is an open source software project for training decision classification tree with Quest
algorithm proposed by Loh and Shih (1997) and stands for Quick, Unbiased, Efficient, Statistical Tree.
It is a tree-structured classification algorithm that yields a binary decision tree. A comparison study of QUEST
and other algorithms was conducted by Lim et al (2000).  The project was implemented with c++ language ,trained and 
tested successfully.

## Dependencies

Before you run the program, you need some libraries intalled in your machine. 

g++,
gsl,
cmake


## Installation

`cd /../QuestDecisionTree`

`mkdir build`

`cd build`

`cmake ../`

`make`

`cd ..`

`cp {trainingdata.csv,matadata.txt,testdata.csv} ./build/`

`cd ./build` 

`./QuestDecisionTree trainingdata.csv matadata.txt testdata.csv`

(make sure the file `trainingdata.csv matadata.txt testdata.csv` exists in your executable directory)

## Reference

[Wei-Yin Loh and Yu-Shan Shih.Split selection methods for classification tree](http://web.cs.iastate.edu/~honavar/loh-split.pdf).
