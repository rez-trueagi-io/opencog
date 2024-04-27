## The OpenCog Project 👋
[OpenCog aims to create AGI](https://wiki.opencog.org/w/The_Open_Cognition_Project)
with a combination of exploration, engineering and basic science research.
Side quests have included robotics systems ([Hanson Robotics](https://www.hansonrobotics.com)),
financial systems (Aidiya),
genomics (MOZI and [Rejuve.bio](https://www.rejuve.bio)),
machine learning ([predicting risk from clinician notes](https://doi.org/10.1371/journal.pone.0085733)),
natural language chatbots ([virtual dog playing fetch](https://www.youtube.com/watch?v=FEmpGRLwbqE)) and more.
This project was pioneered by [Dr. Ben Goertzel](https://en.wikipedia.org/wiki/Ben_Goertzel).
Git repos fall into four categories:

### OpenCog AtomSpace
The core of the system: active, stable and supported.

* [AtomSpace](https://github.com/opencog/atomspace) (Hypergraph database and query engine)
* [CogServer](https://github.com/opencog/cogserver) and [atomspace-cog](https://github.com/opencog/atomspace-cog) (for networking, json, websockets)
* [atomspace-rocks](https://github.com/opencog/atomspace-rocks) (disk I/O subsystem based on RocksDB)
* [Proxy Nodes](https://wiki.opencog.org/w/ProxyNode) (for data routing, replaces attention bank)
* [Link Grammar](https://github.com/opencog/link-grammar) (including the learn subproject for neuro-symbolic structure learning)
* [Docker containers](https://github.com/opencog/docker) (provide system integration and demos)

### OpenCog Research
Git repos in which active resarch is being carried out:
* [Learn](https://github.com/opencog/learn) (Symbolic learning) "mature", batch-based processing
* [Agents](https://github.com/opencog/agents) (refactoring learning for an interactive environment)
* [Sensory](https://github.com/opencog/sensory) (Dataflow of graphlets to/from external world. Agents I/O system.)

### OpenCog Fossils
Older, abandoned and obsolete components. These were educational and fun, but development has
halted. These projects are no longer maintained, but they may contain useful subsystems that
might be salvageable for future use. This includes:
* PLN, URE, Attention, SpaceTime, Ghost, Relex, R2L, ROS, Hanson Robotics Eva/Sophia
* MOSES (but not as-moses, see below).
* Any repo that is marked "read-only" or "obsolete".

### OpenCog Hyperon
Being developed by [Singularity.net](https://singularitynet.io).

### OpenCog Incubator
These are the immature, incomplete, promising projects that haven't taken off yet.

* [SQL Bridge](https://github.com/opencog/atomspace-bridge) - Direct I/O between SQL and AtomSpace
* Prolog-on-Atomspace proof-of-concept
* [Chemistry](https://github.com/opencog/cheminformatics) proof-of-concept
* [agi-bio](https://github.com/opencog/agi-bio) (genomics subsystem used by MOZI and rejuve.bio)
* [visualization](https://github.com/opencog/visualization) (GUI to explore AtomSpace contents)
* [as-moses](https://github.com/opencog/as-moses) (Port of MOSES to the AtomSpace)
* [Vision](https://github.com/opencog/vision) proof-of-concept (Extracting structure from images, video)
* [Hyperon-on-top-of-atomspace](https://github.com/opencog/atomspace-metta) proof of concept (Hyperon backwards-compat)

# HELP WANTED
The above-mentioned commercial projects don't pay the bills. There are far more ideas
and possibilities than there is time or money. If you're a software developer, bored
and looking for something to do, there's a lot of great stuff here that is worthy of
attention. If you are an academic, scientist or grad student, someone who wants to do
cross-over Symbolic AI and Deep-Learning Neural Net research, and need a base toolset,
this is the place. We will work with you to make sure this stuff fits your needs and
does what you want it to do, the way you want it.
Contact [Linas Vepstas](linasvepstas@gmail.com).

### Commercial support
If you are a commercial business looking to use any of these components in your products,
we can provide full-time support, if that's what you want. We'll custom-taylor components,
systems, and API's to suit your needs. If you are an investor looking to build up a venture,
well yes, that could happen too. Talk to us. Contact [Linas Vepstas](linasvepstas@gmail.com).
