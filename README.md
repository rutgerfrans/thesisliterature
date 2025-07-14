# thesisliterature
This repo contains all literature used for the background section in the thesis paper to be published. This readme will include an annotated list of each read paper. 

## Papers
### Robustness of decentralised learning to nodes and data disruption. 
In my opinion this paper is usefull to refer in the related work section. This paper talks about an extended version of federated learning, fully decentralized learning. This type of learning eliminates the need of a central parameter server that collects and aggregates model parameters. Altough this paper does not the same as what I do in the thesis project (decentralized learning with a parameter server) this is still relevant to relate to to show what other papers are working on.

### Decentralised Learning in Federated Deployment Environments: A System-Level Survey.
This a very relevant paper for taxonomy. I can use it to better back up my baseline configuration of PyTorch, TensorFlow, and the SAM implementation. Furthermore it discusses the concern of privacy instead of fault tolerance. This is an aspect that I dont discuss in the thesis paper, so this might be relevant to refer to in the related works or background section.

### DART : A Solution for decentralized federated learning model robustness analysis
This paper focusses mainly on the different kinds of poisoning attacks on Centralized and Decentralized Federated Learning systems. The paper discusses the different ways of attacks but also the different ways of defending mechanisms. It then further comes up with a system called DART to analyse the robustness of an FL system against poisoning attacks. I think this paper is good for both the background and related works section, because it discusses core concepts of FL and discusses poisoning attacks (a different form of disruption than node failures.) Now This paper led me to think that building robust systems for FL against node failures is only important when the majority of federated entities is owned by a single share holder. If one company runs a federated learning system inhouse then node failures are important to defend against. If multiple companies share their learning it might not be important if a single company in this federated system fails if and only if this company can learn by itself.
