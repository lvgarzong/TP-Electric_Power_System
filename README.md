# Term-Project: Analysis of a Electric Power System using Network Science

## Project Goal and Scope

HE purpose of this project is to perform an analysis of an electric network using complex network analysis (CNA) techniques to identify key parameters, such as centrality analysis, betweenness centrality, and community detection. The goal is to determine optimal locations for deploying microgrids within electrical distribution systems and identify the most vulnerable nodes or links in the network. These findings will facilitate conducting various tests, such as loss of lines and substations, using simulators like MATPOWER or PandaPower in Python. This work utilizes the IEEE 118 bus test system, as detailed in our dataset and implemented network science approach section

**Limitations and scope**: The project’s limitations include the exclusion of analyses such as node embedding or similarity algorithms, which are not justified for the network type and application. Moreover, this analysis is not designed for networks with large numbers
of nodes and edges, as their complexity could render the applied methods inapplicable to such systems. The project focuses on analyzing the IEEE 118 bus test system and implementing complex network analysis techniques to identify optimal locations for microgrids and vulnerable network components.

## Case Study

Elements such as buses and lines are goiing to take into account. Also it includes different elements such as generators or loads, which should be ignored for this analysis. The IEEE 118-bus test case represents a simple approximation of the American Electric Power system (in the U.S. Midwest) as of December 1962. This IEEE 118-bus system contains 19 generators, 35 synchronous condensers, 177 lines, 9 
transformers, and 91 loads.
The base KV levels in the bus names are a very rough guess. “The line MVA limits were not part of the original data and are made up. As a test case, this one has a lot of voltage control devices and is quite robust, converging in 5 or so iterations with a fast decoupled power flow”. 

## Data Set Description

In this study, the IEEE 118-bus system dataset, provided by the PandaPower library is been used. This dataset is originally derived from PYPOWER and contains additional information from Washington University and Illinois University. The IEEE 118-bus system dataset represents a power transmission system with 118 buses, 186 transmission lines, and multiple generators and loads. 