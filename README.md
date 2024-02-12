# Public Sphere Technologies

## Introduction:
Why, when humanity can work together to meet and exceed our wildest dreams, do we continue to behave as petty tribes? 
Our hypothesis is that, even while humanity has developed abundant means to feed and to shelter herself, we have yet to develop the necessary infrastructure to enunciate a shared story for who we are, and for what we should be doing with one another.
Absent such a shared outlook and the means for developing it, we exist in a perpetual state of individualist anarchy -- violating each other for the sake of artifically scarce resources. 
Fortunately, the current era of telecommunications, AI, and the internet affords humanity with all that we require to finally talk through our differences, and reify our shared outlooks. 

## Hypothesis
From this perspective, universal peace and prosperity is, at it's base, a networking problem -- one having evident engineering solutions.
Figure 1 displays this concept in the abstract. 
As we move from left to right across the figure, interpersonal networks leverage improved communications devices (dashed and dotted lines) to incrementally build a more fully inter-connected and collaborative species. 
The leftmost panel depicts the state of nature, wherein physical co-location allows vocal communication to establish tribes. 
The center panel describes any of several high-utility/high-cost communications systems that facilitate long-range connections between tribes.
Examples of these communications systems include, e.g.: printing presses, telegraph and rail lines, congressional seats, social media servers, etc.
Owing to the high costs of building these systems, the few individuals who govern them will act as hubs, mediating interactions for non-hubs.
These types of networks are termed "small-world."
The term denotes the proliferation of local clustering (the tribes), alongside the existence of key long-range connections between clusters (the hubs).
Critically, if the hubs themselves are clustered together, the small-world network posesses a "rich-club." <>
The rightmost panel leverages high-utility/low-cost communications systems -- e.g., digital networks -- which allow all people to coordinate, at will, with any and all other persons.
This type of network may be considered "fully connected," albeit, with two provisions: 1) individuals communicate with one another via a mutually-accessible digital I/O communications backbone, and 2) individual interest/attention filters information flow between persons.

| ![Social hieararchies are directly established by certain social network architectures.](/images/Dots_ABCsystems.png "Social hieararchies are directly established by certain social network architectures.") |
|:--:| 
| *Figure 1* displays three kinds of social network topologies. Part A features four disconnected tribes (blue, red, green, and magenta). Each tribe's internal connections are produced through person-to-person contact and communication (solid lines). Part B includes several long-range connections (dashed lines) between certain members (black diamonds) of each tribe. Each well-connected tribal member is a hub, filtering communication between their own tribal members and the hubs of other tribes. Critically, the high degree of connectivity among tribal hubs creates a "rich-club" montage that may devolve into collusion among the individuals who act as hubs. Rich-club network topologies are the current configuration of most long-range social networks -- i.e., representative democracies, the UN, OPEC, and others. Part C depicts a network model in which all participants may communicate with any other member in just two steps (dotted lines) via a common database (circumferential ring).|

## Long-term Goal: Detailing the Global Public Sphere
Transitioning from a small-world to a fully-connected global civil society can be done quickly, should we make it a priority.
Indeed, an expanding ecosystem of grassroots efforts is already under development to effectuate scalable "collective intelligence."
The most critical of these efforts has constructed a distributed I/O network layer, i.e., distributed ledger technologies, on top of which are built distributed applications.
These systems establish a high-utility/low-cost I/O network, via which any and all persons may interact with one another.
Owing to their distributed nature, these networks are resistent to corruption at the scale of proportionally few people/groups.
And, information accepted by very many people has a greater chance of being addressed by the broader population.

One problem faced by any growing network is effective knowledge management.
Figure 2 displays one approach for organizing and analyzing scalable networks.
Here, persons and entities are represented as nodes in a graph, while the relationships between persons/entities are represented as edges.
This knowledge management system has the equivelent representation of a simple ledger, called a knowledge database, wherein each entry comprises a subject-predicate-object statement.
Recomposing the ledger into a graphical format, called the knowledge graph, allows for a host of tools -- from machine learning and AI (especially Large-Language Models (LLMs)) -- to be recruited to analyze the network.
This is in addition to being able to recruit standard tools for filtering and performing queries on the database (e.g. SPARQL).

The long-term goal of these efforts is to help detail and analyze a social graph network until it is a (sufficiently) complete representation of the global political economy. 
The near-term goals described below serve to build incremental solutions to the engineering challenges of detailing and analyzing scalable social graph networks.

| ![cGraph networks offer a means to express and analyze political economies.](/images/pAlpha_system.png "vSocial hieararchies are directly established by certain social network architectures.") |
|:--:| 
| *Figure 2* displays a sample social graph network. The network is built from three types of interacting features: _p_ are persons, _e_ are non-person entities, and _x_ are relationships between persons and/or entities. Hypothetically, this kind of graph network structure is flexible enough to account for any and all aspects of political economies. (A complete picture would be much more detailed than the example shown.) One useful feature of representing political economies as a graph network is that this representation is exactly that utilized in knowledge databases/knowledge graphs, wherein entities are connected via predicate relationships. Graph networks may be analyzed in a variety of ways. The most straightforward is via graph-query languages such as SPARQL. An alternate method considers that knowledge graphs are geometric objects. Thus, knowledge graphs support a wide variety of analytical tools from ML and AI.|

## Near-term Goals
*Public Sphere Tech* (PST) comprises a suite of applications to facilitate scalable coordination. 
Each application, described in the milestones below, builds towards the long-term vision of a "global public sphere," wherein a global citizenry auto-generates and, as self-interested individuals, assents to a set of equitable and sustainable norms.

### Milestone 1: I/O Systems Foundations: OriginTrail + SingularityNET (Month 1)
A natural place to begin is with the integration of high-accessibility data storage systems and low-cost data analysis tools into a common framework.
Whereas the ultimate goal of PST is to build trustless and scalable information I/O tools, it makes sense to utilize distributed information systems as a core design feature.
The state-of-the-art in distributed information I/O tools includes 1) OriginTrail Distributed Knowledge Graphs (DKG), and 2) SingularityNET Decentralized Applications (DApps) for AI/ML data analytics.
Thus, Milestone 1 installs, configures, and tests OriginTrail + SingularityNET to host a downstream suite of user-facing information I/O tools.
To verify the I/O framework, Milestone 1 launches a ready-made information analytics tool from a partner organization, namely, the Collective Human SuperIntelligence (CHSI) app from radish.org. 
#### Part 1.1: General system configuration
The foundation of Public Sphere Tech is robust, on-chain, I/O infrastructure. 
To this end, the following steps install and configure state-of-the-art distributed I/O tools onto a bare-metal node.
This node will be used to test and to launch user-facing public sphere applications.
  ##### &nbsp; &nbsp; Step 1.1.1: Configure OriginTrail Node
  ##### &nbsp; &nbsp; Step 1.1.2: Configure SingularityNet Node
  ##### &nbsp; &nbsp; Step 1.1.3: Test local communication between OriginTrail data and SingularityNet analysis
  ##### &nbsp; &nbsp; Step 1.1.4: Test on-chain communication between OriginTrail data and SingularityNet analysis
  ##### &nbsp; &nbsp; Step 1.1.5: Refactor configuration and testing steps into a reusable repository
  
#### Part 1.2: Integration with CHSI (Collective Human SuperIntelligence)
CHSI is an independent project built by Victor Piper and Jaemen Shen. 
The aim of the application is to connect individuals with shared interests to catalyze the proliferation of those interests.
At root, the application transforms vocal conversations into a knowledge graph describing the topics of those conversations.
These knowledge assets may be compared to each other in order to recommend groups of participants who share similar interests.
  ##### &nbsp; &nbsp; Step 1.2.1: Ingest spoken conversation uploads
  ##### &nbsp; &nbsp; Step 1.2.2: Convert spoken conversation into text transcriptions
  ##### &nbsp; &nbsp; Step 1.2.3: Convert transcripts into knowledge graph
  ##### &nbsp; &nbsp; Step 1.2.4: Add conversation knowledge graph to DKG 
  ##### &nbsp; &nbsp; Step 1.2.5: Analyze knowledge assets for commonalities via key-word search
  ##### &nbsp; &nbsp; Step 1.2.6: Create front-end-interface through which users may find others having shared interest. 

#### Impact:
Milestone 1 creates a robust and reusable framework for the production, interpretation, and analysis of scalable social graphs.
Beyond making this framework available for later milestones and for the broader development community, Milestone 1 provides hosting services for CHSI, a simple collective intelligence DApp.

### Milestone 2: Sustainable Business: AI-assisted Proposal Generation and Review (Months 2-5)
The focus of Milestone 2 is to build a sustainable business, while also furthering our group's capacities to facilitate multi-agent negotiations.
Markets of small groups engaged in very detailed negotiations are an obvious community to orient towards: i.e., the market of grant (or proposal) authorship and review.
This community faces several key hurdles which are well-served by more adept information I/O:
- Hurdle 1: Once a good idea is conceived, proposals are time consuming to format to meet review criteria.
- Hurdle 2: Once a proposal is submitted, the review process is also time consuming.
- Hurdle 3: Once reviews are submitted, it is not always the case that proposal authors will immediately understand the importance of reviewer critiques.  

Authors and reviewers, alike, are increasingly turning towards large-language models to assist them in the proposal process.
However, the tendency for LLM's to hallucinate makes their routine use in mission-critical communications hazardous.
Milestone 2, therefore, aims to formalize the use of LLM's in proposal authorship and review by treating the proposal as a deterministic data object that constrains the LLM's generative output.
The most natural way of accomplishing this goal is to translate proposals into a data object that both humans and LLM's can understand, i.e., into a graph database.
The technical term for leveraging external graph databases to constrain LLM generative outputs is "Neuro-Symbolic Artificial Intelligence" (NSAI).

NSAI leverages external Knowledge Bases (KB) and Knowledge Graphs (KG) to fine-tune generative responses. 
With NSAI, proposers would be asked to (use an LLM to) restructure their proposal into a knowledge graph, as in: 
"Work plan e1 meets review criteria R1. Deliverables e1.1, e1.2, and e1.3 are parts of work plan e1. 
Deliverable e1.1 has challenge C1. 
Challenge C1 is addressed by methods m1.1, m1.2, m1.3," etc. 
Immediately, reviewers and AI would have a more structured way of consuming proposals. 
Additionally, challenges observed by reviewers (w/wo AI assistance) may be added to the graph, as in: "Method m1.1 faces the unmet challenge C2." 
Given an iterative review process, the KB could be reviewed until all challenges and review criteria are satisfactorily resolved.

#### Part 2.1: Translate proposal text into KG
##### &nbsp; &nbsp; Step 2.1.1: Test Neo4j's off-the-shelf techniques for text-to-KG translation (Project NaLLM by Neo4j), assessing features and limitations.
##### &nbsp; &nbsp; Step 2.1.2: Evaluate translation performance using a Text-to-KG benchmarking tool (https://github.com/cenguix/Text2KGBench).
##### &nbsp; &nbsp; Step 2.1.3: Dig into NaLLM source code to improve, as needed.
##### &nbsp; &nbsp; Step 2.1.4: Develop front-end to support manual editing of KG, as needed.

#### Part 2.2: Translate KG into long-form proposal
##### &nbsp; &nbsp; Step 2.2.1: Explore vanilla KG-to-text procedure using prompt engineering (as suggested by https://arxiv.org/abs/2307.07312)
##### &nbsp; &nbsp; Step 2.2.2: Explore off-the-shelf KG-to-report methods from Neo4j (Project NaLLM) 
##### &nbsp; &nbsp; Step 2.2.3: Evaluate the performance of KG-to-text translation using the the Data-to-Text-Evaluation-Metric (https://github.com/wenhuchen/Data-to-text-Evaluation-Metric/) 
##### &nbsp; &nbsp; Step 2.2.4: Develop front-end to support manual editing of generated text, where needed.

#### Part 2.3: NSAI-enabled proposal review
##### &nbsp; &nbsp; Step 2.3.1: Leverage pre-existing AI-enabled graph query tools (esp. NatLangKG, and Project NaLLM) to facilitate the use of natural language to interrogate the content of KGs.

#### Part 2.4: Integrate generated KGs with OriginTrail+SingularityNET backend
##### &nbsp; &nbsp; Step 2.4.1: Provide user-oriented methods to publish KGs from Part 2.1 as knowledge assets.
##### &nbsp; &nbsp; Step 2.4.2: Provide user-oriented methods to publish reviews from Part 2.3 as linked knowledge assets.
##### &nbsp; &nbsp; Step 2.4.3: Provide user-oriented methods to convert linked knowledge assets into formatted long-form proposals, as in Part 2.2.
##### &nbsp; &nbsp; Step 2.4.3: Publish user-oriented methods as an api and as a webapp via the SingularityNET marketplace.

#### Impact: 
Milestone 2 develops NSAI into a sustainable business that facilitates the laborious process of proposal authorship and review. 
From a technical standpoint, Milestone 2 develops our capacity to flexibly detail KG from unstructured text and natural language inputs.
Moreover, we develop further capacities to work with KG by translating them into reformatted text.
These technical capacities are important to develop because, in the long term, the global political economy is a highly detailed, interconnected, and mutable network. 

### Milestone 3: Publicity and Engagement: Visual Analysis of Large-Scale Social Networks (Months 6-7)
Milestone 3 aims to drive public-interest and engagement with PST.
This, while also developing our capacities to ingest, analyze, and visualize very large knowledge graphs.
To do so, we will produce an application having both a low barrier of entry and a high degree of social stimulation.
Specifically, the application will ingest each user's pre-existing social-media data, and translate that data into a user-specific KG.
From there, the application will allow users to visually analyze areas of overlap (as well as any gaps) between their KG and the KGs of other users populating our expanding database.

Note: Copyright and GDPR concerns are at the forefront of our minds with respect to this milestone.
And whereas many major markets have stipulated that individuals own the copyrights to what they upload to social media, it is not necessarily the case that these trends apply everywhere.
Moreover, the content of data downloaded from popular social media sites may contain personal information, subject to GDPR concerns.
Thus, Milestone 3 will initially be made available only to persons existing in markets having clear copyright/GDPR laws surrounding the use of social media data.

#### Part 3.1.: Translate text-based social-media data into KG
##### &nbsp; &nbsp; Step 3.1.1: Download sample dumps from popular social media sites.
##### &nbsp; &nbsp; Step 3.1.2: Leverage techniques from previous milestones to translate data dumps into KG.
##### &nbsp; &nbsp; Step 3.1.3: Create methods to filter personally identifying information from public KGs.

#### Part 3.2.: Visualize the ensemble set of KGs
##### &nbsp; &nbsp; Step 3.2.1: Investigate the use of UMAP (Uniform Manifold Approximation and Projection) to project KGs onto 2-dimensional spaces.
##### &nbsp; &nbsp; Step 3.2.2: Investigate the use of ML/AI to filter large-scale KGs, and thereby resolve unique and information-rich 2-dimensional embeddings.
##### &nbsp; &nbsp; Step 3.2.3: Provide clustering metrics to assist people in finding common-interest groups.
##### &nbsp; &nbsp; Step 3.2.4: Explore the information-richness of path metrics between persons. The hypothesis here is that people may be connected via both mutual contacts and chains of non-person entities. The details of connecting paths may reveal avenues through which distantly connected people may find common ground.
##### &nbsp; &nbsp; Step 3.2.5: Explore the presence of holes (topological homologies) within the graph. The hypothesis here is that very long path-distances between persons may be shortened by the addition of intermediate nodes. Such "graph completion" suggestions may aid in bringing people together to find common ground.

#### Impact:
The long-term impact of Milestone 3 promises to help people realize themselves as members of a global civil society.
This impact is especially developed through Steps 3.2.4 and 3.2.5, which directly identify the degrees of disconnectivity between persons, while also suggesting how disconnected persons may better connect.
