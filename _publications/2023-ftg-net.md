---
title: "FTG-Net: Hierarchical Flow-to-Traffic Graph Neural Network for DDoS Attack Detection [Submitted]"
collection: publications
permalink: /publication/2022-ftg-net
excerpt: 'Distributed Denial of Service (DDoS) is one of the most common cyber-attacks and caused several damages in recent years. Such attacks can be executed either through the orchestration of multiple devices that synchronously send requests or through specific patterns followed by a single device to force the victim to keep resources overrun. It becomes crucial to develop robust techniques to promptly detect those two kinds of DDoS attacks and mitigate their consequences. Most of the existing Machine Learning (ML) methods are based on flow and traffic information aggregations expressed in the form of independent vectors of statistical data, ignoring topological connections. Few recent solutions try to exploit the structural information of the network to improve the classification results. In particular, Graph Neural Network (GNN) based models can process traffic-level or flow-level relationships, represented as graphs, to detect malicious patterns.
The objective of this paper is to combine the relationships at both traffic-level and flow-level by developing a two-level hierarchical graph representation and a GNN model able to process it, maximizing the information brought by the traffic structure and removing the necessity of stateful features. Experiments on the CIC-IDS2017 dataset show that the performance are comparable to the state-of-the-art solutions even using only the traffic structure. The code can be accessed at https://github.com/lucabarsellotti/FTG-Net'
date: 2022-11-01
venue: 'IEEE International Conference on Communications 2023 (ICC) (Submitted)'
paperurl: 'http://lucabarsellotti.github.io/files/ftg-net.pdf'
citation: 'Not available'
---
Distributed Denial of Service (DDoS) is one of the most common cyber-attacks and caused several damages in recent years. Such attacks can be executed either through the orchestration of multiple devices that synchronously send requests or through specific patterns followed by a single device to force the victim to keep resources overrun. It becomes crucial to develop robust techniques to promptly detect those two kinds of DDoS attacks and mitigate their consequences. Most of the existing Machine Learning (ML) methods are based on flow and traffic information aggregations expressed in the form of independent vectors of statistical data, ignoring topological connections. Few recent solutions try to exploit the structural information of the network to improve the classification results. In particular, Graph Neural Network (GNN) based models can process traffic-level or flow-level relationships, represented as graphs, to detect malicious patterns.
The objective of this paper is to combine the relationships at both traffic-level and flow-level by developing a two-level hierarchical graph representation and a GNN model able to process it, maximizing the information brought by the traffic structure and removing the necessity of stateful features. Experiments on the CIC-IDS2017 dataset show that the performance are comparable to the state-of-the-art solutions even using only the traffic structure. The code can be accessed at https://github.com/lucabarsellotti/FTG-Net