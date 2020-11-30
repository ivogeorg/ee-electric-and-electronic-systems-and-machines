# Building a branched curriculum progression

Starting with 2 stacked classes with about 65% overlap, build a curriculum graph that can accommodate both and include opportunities for individual variation.

## Approach

1. Note that this is an EE overview course for engineering students from mechanical and sustainable systems programs, learning about electricity, circuits, and related topics. After a common core of electromagnetics and analog circuits (R, RC, RL, RLC), MET students diverge toward motors, while SSE students toward electronics and computers.    

2. From curriculum paths:
   1. Identify level of general preparation (for effectiveness during progression). 
   2. Establish reasonable expectations (of learning capacity and work ethic).  
   3. Concrete prerequisites (for attachment points and, if necessary, rapid introduction and/or review).  
   4. Select target forward attachment points (for creating a solid basis for follow-on curriculum elements).  

3. Content general matter:
   1. Prerequisites should be independent progressions. These include:  
      1. Prerequisite courses. Should have been covered before the beginning of course, but may need to be incorporated to create contact points.    
      2. Prerequisite topics. Should be covered during course before application.  
   2. Common curriculum should from the backbone of the course.  
   3. Branches should fork off the backbone.  
   4. This is engineering, so:
      1. Study.  
      2. Apply.  
      3. Present.  
      4. Knowledge, _know-how_, skill.  
         1. Experiment with new names for the step sections:
            1. Know-what = Study.  
            2. Know-how = Apply.  
            3. Know-why... => Richer representation of knowledge and beginning of classification of multi-modal conceptual links!  
      
4. From books:
   1. Digest slides and use to seed the STEMGraph.    
   2. STEMGraph should dynamically update to achieve the "best" representation. What are the _criteria_? What is the _training signal_?  
      1. Homogeneous granularity, which can be derived from:
         1. Zone of proximal development criteria.  
         2. Learning spaces criteria.  
         3. Local hypergraph connectivity. _Here, explore the non-dyadic graph theory SOTA in the context of representing multi-modal concepts._  
      2. The "learnability" signal should:
         1. Come back from interaction with human learners and may lend itself to simulational pretraining (that is, in dialog between two bots).  
         2. Provide discrimination between local graph-structure (graph-pattern) variants.  
         3. High-granularity conceptual change dynamics data is needed for such focused local graph evolution. _Here, explore the SOTA in:_ 
            1. _GNNs and connectivity evolution._  
            2. _Conceptual change research. In particular, [diSessa's latest project](https://gse.berkeley.edu/andrea-disessa), or whatever the SOTA in his thinking on high-granularity conceptual change data is (that is, which contemporary works are citing him)._  
      3. Cognitive-computational criteria: TBD (needs research!).  
   3. The slides are a very rich multi-modal medium, and seemingly a strongly established format for communication of information and teaching (and, supposedly, learning). _Here, investigate if this is a technological artifact or evidence for constrained cognitive efficiency._  
   4. STEMGraph topics will cover the domain _Electric and Electronic Systems and Machines_, with all its prerequisites (e.g. differential equations, complex numbers, positional numeral systems, Turing machines and completeness, etc.), and densely populated with visual aids and exercises.  
   5. Levels of abstraction will depend:  
      1. Conceptual density.  
      2. Summarization for _"glossing over"_ bridging without going into too much depth. Aka _"cantilevered bridging"_.   
      3. Equivalences with operational notions of _"explanation"_ and _"understanding"_.   
      4. Mechanisms of curricular progression building, including _"spiral learning"_.   

5. Content merging from syllabi will depend on the conceptual granularity, which has to be decided first, or updated dynamically per the previous point on STEMGraph!   
   1. This should be the most powerful differentiator for faculty and domain experts to rapidly assemble curricular content. _(Use case: Imagine assembling the content for the domain experts/faculty of the Mars University, so they can impose the course/curriculum structure within a couple of days!!!)_  
   2. The assembly will be a dynamic process, with faculty on one end and domain experts on the other, continually digesting new content and hyperbolic recasting for up-to-date presentation.  

6. Apart from generally personalized paths through the curriculum with identified curricular targets, variation of content selection, depth, and specialization (e.g. MET or SSE on EET curriculum) relevance can be achieved by tuning the Study, Apply, and Present sections. For full variational compositionality:
   1. (STEMGraph) Highest conceptual granularity has to underly the curricular materials, with full 360° progressional connectivity.    
   2. (LPs) Compositionality will be achieved by specialization-specific selection of the curricular targets. The natural connecitvity between targets will serve as the personalized path variational space.  
   3. (depth control) The high granularity will also allow depth-sensitive target selection. There can be different Apply requirements depending on the depth. The difference may be of the kind between a straighforward hands-on applicative exercise on a concept, and a general proof of the concept, these two defining different levels of local density of the knowledge space in the vicinity of the concept. For example, if the concept is Thevenin's equivalence theorem, the former may be solving a circuit and the latter a [proof](https://spinningnumbers.org/a/thevenin-proof.html).  
   
7. Experiment:
   1. Start from two syllabi separately.  
   2. For each syllabus, build STEMGraph (multi-modal non-dyadic conceptual graph) and drive reduction to maximum conceptual granularity, with prerequisites, goals, and extensions.  
   3. Match, merge, overlay, and visualize.  
   4. [Design spike] Redesign process from syllabi. Goal is to merge an arbitrary set of syllabi, with arbitrary overlaps. No curriculum element should be left out for lack of a way to integrate. Integration might require realignment, stretching for smoothness and cognitive load, and various structural adjustments.      
   5. [Discover] Create progression happy paths for LABOT.  
   
8. Construction grammars will probably be necessary to stitch symbolic (form) and cognitive (meaning) representation (reification?) of concepts!   
   1. Student naive understanding makes this a dynamic process (link to _conceptual change_) and not a static grammar. _Here, explore the SOTA on "dynamic construction grammars", or, more likely, identify the knowledge gap and the knowledge domains adjacent to it._   
   2. Rubin Landau's first rule of education rings true here: "Most of education is learning what the words mean; the concepts are usually quite simple once you understand what you are being told." This might well be the key to efficient learning!  

## Content 
     
1. Prime STEMGraph with backbone and major branches.  
   1. Recommended texts from syllabi.  
   2. Reasonable other sources.  
2. Mine:
   1. Syllabi & curricula (e.g. [Stanford Engineering Undergraduate Handbook materials](https://ughb.stanford.edu/plans-program-sheets/flowcharts-and-plans).  
   2. Wikipedia & other online references and encyclopaedias.  
   3. Videos, lectures, books, and courses.  
   4. OER (OpenTextbooks, LibreTexts, etc.).  
3. Build out STEMGraph (TBD). 
   1. This is a **MAJOR DEVELOPMENT ITEM**.
   2. Related to:
      1. Knowledge and Learning Space building.  
      2. Conceptual Change and progression building.  
      3. Cognitive load and efficient mental capacity utilization.  
      4. Conceptual graphs, GNNs, knowledge bases, and the whole knowledge-heavy ML ecosystem.  
   3. Digest the content into concept-level 
   4. _This will be an iterative and continous process!!!_  
   5. Discover and incorporate new sources.   
4. Adopted book.  
      
### Notes on circuits

1. Motivate.  
2. Show examples.  
3. Exercise the ability to identify the function of a circuit from general knowledge and applied analysis.  
4. Exercise the ability to build a circuit given a blueprint.  
5. Exercise the ability to design a circuit given a functional specification.  
6. Particular exercises:
   1. Construct a resistor network of target resistance given a specific selection and numbers of resistors.  

#### Composition of Apply sections

1. Employing first-look unaided analysis, formulate hypothesis.  
2. Employing a simulator, capture the circuit and test hypothesis. Amend if necessary.  
3. Employing lab kit and measurement equipment (multimeter, function generator, oscilloscope), built circuit and perform definitive analysis.  
4. Based on experience, extend the circuit with a given useful set of features and/or parameters.  
5. Based on the extended experience, design and build an advanced related circuit with a given functional definition.  
6. Employing an exhaustive technical narrative, including visual aids and cited sources, discuss the range of applications. (Wikipedia assignment.)  

### Notes on environment

1. Simulation.  
   1. [NI Multisim](https://www.multisim.com/):
      1. Based on original Berkeley SPICE.  
      2. Free license sufficient.  
2. Oscilloscope.  
   1. Digilent Discovery 
   2. [Instructables DPScope](https://www.instructables.com/DPScope-Build-Your-Own-USBPC-Based-Oscilloscope/).  
   3. Other even simpler.
      1. **TODO:** Compose a multi-part project for the course and weave in with the curriculum!!!   
