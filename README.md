
[In Finnish / suomeksi](https://github.com/OssiGalkin/Master-s-Thesis/blob/master/LUEMINUT.md)

# Master's Thesis

My master's thesis in LaTeX. PDF version can be founded in [Aaltodoc](https://aaltodoc.aalto.fi/) archive. It is also backed up [here](sci_2019_galkin_ossi.pdf) on GitHub.

## Abstract of “Enterprise Application Integration Architecture Recovery” 

Large and medium-sized enterprise has multiple business applications, such as customer relations management (CRM) and enterprise resource planning (ERP) software. Business applications need data from each other, but they rarely communicate with each other out of the box. An enterprise application integration (EAI) platform is used to tie them together. Automating communication between business applications is called orchestration. As EAI is used to implement communication between business applications, in theory, it could be used to map the architecture of the orchestration layer. As companies evolve, so does the software they use. Either documentation is never done, or it is not updated. Overall, the frequent problem is that the company loses track of what software systems it has and how they are used. 

This work studies the feasibility of building software that can automatically recover orchestration architecture. The orchestration architecture is then represented as a network to enable further analysis and visualization. This research investigates whether it is possible to use that network to detect business applications that are being used and whether the production environment is separate from the testing environment. In addition, those nodes connecting the testing, and production environments are determined.

The results suggest that it is possible to detect orchestration architecture automatically. Because of a unique characteristic of orchestration layer implementation, such a model can outperform more general architecture recovery models. With a recovered architecture, it is possible to detect whether the production environment is separate from the testing environment and to identify connecting nodes. However, used applications were not discovered using modularity optimization.
