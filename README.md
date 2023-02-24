## Getting more than what you've asked for: The Next Stage of Prompt Engineering 
[**Paper**](https://arxiv.org/abs/2302.08509)


Giving an LLM any interface to the outside, like a search capability, can have critical security implications. When prompt injection is used and delivered by adversaries instead of the user themself, bad things could happen- and as far as we know, this scenario has not been studied until now.

<p align="center">
  <img width="460" src="./teasers/fig1.png">
</p>

## What is this project about?
We demonstrate the potentially brutal consequences of connecting LLMs to applications (like search). We propose newly enabled attack vectors and techniques and discuss them:

- Remote control of chat LLMs

- Persistent compromise across sessions

- Spread injections to other LLMs

- Compromising LLMs with tiny multi-stage payloads

- Leaking/exfiltrating user data

- Automated Social Engineering

- Targeting code completion engines

<p align="center">
  <img width="500" src="./teasers/fig2.png">
</p>



## Demo
In the following figure, you can see how an attacker may send an email with prompt injected in it.
<p align="center">
  <img width="500" src="./teasers/fig3.png">
</p>

Then when an automated tool parses that email, it will execute the payload. As can be seen in the following figure.
<p align="center">
  <img width="500" src="./teasers/fig4.png">
</p>

This paper should be a must-read for anyone that is building a business by integrating LLMs right now.

## How to run
```
Coming soon!
```
However, if you are in hurry, you will need `langchain`, `openai` and `rich`. You will also need OpenAPI key. Finally, you can use PyCharm and run the attack you want.

## To cite our paper
```bibtex
@misc{https://doi.org/10.48550/arxiv.2302.12173,
  doi = {10.48550/ARXIV.2302.12173},
  url = {https://arxiv.org/abs/2302.12173},
  author = {Greshake, Kai and Abdelnabi, Sahar and Mishra, Shailesh and Endres, Christoph and Holz, Thorsten and Fritz, Mario},
  keywords = {Cryptography and Security (cs.CR), Artificial Intelligence (cs.AI), Computation and Language (cs.CL), Computers and Society (cs.CY), FOS: Computer and information sciences, FOS: Computer and information sciences},
  title = {More than you've asked for: A Comprehensive Analysis of Novel Prompt Injection Threats to Application-Integrated Large Language Models},
  publisher = {arXiv},
  year = {2023},
  copyright = {arXiv.org perpetual, non-exclusive license}
}
```

