# Building a branched curriculum progression

Starting with 2 stacked classes with about 65% overlap, build a curriculum graph that can accommodate both and include opportunities for individual variation.

## Approach

1. Note that this is an overview course for non-majors, but still engineers. MET and SSE students learning about electricity, circuits, and related topics.  

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

4. Content merging from syllabi will depend on the conceptual granularity, which has to be decided first!   

5. Apart from generally personalized paths through the curriculum with identified curricular targets, variation of content selection, depth, and specialization (e.g. MET or SSE on EET curriculum) relevance can be achieved by tuning the Study, Apply, and Present sections. For full variational compositionality:
   1. (STEMGraph) Highest conceptual granularity has to underly the curricular materials, with full 360° progressional connectivity.    
   2. (LPs) Compositionality will be achieved by specialization-specific selection of the curricular targets. The natural connecitvity between targets will serve as the personalized path variational space.  
   3. (depth control) The high granularity will also allow depth-sensitive target selection. There can be different Apply requirements depending on the depth. The difference may be of the kind between a straighforward hands-on applicative exercise on a concept, and a general proof of the concept, these two defining different levels of local density of the knowledge space in the vicinity of the concept. For example, if the concept is Thevenin's equivalence theorem, the former may be solving a circuit and the latter a [proof](https://spinningnumbers.org/a/thevenin-proof.html).  
   
6. Experiment:
   1. Start from two syllabi separately.  
   2. For each syllabus, build STEMGraph and drive reduction to maximum conceptual granularity, with prerequisites, goals, and extensions.  
   3. Match, merge, overlay, and visualize.  
   4. [Design spike] Redesign process from syllabi. Goal is to merge an arbitrary set of syllabi, with arbitrary overlaps. No curriculum element should be left out for lack of a way to integrate. Integration might require realignment, stretching for smoothness and cognitive load, and various structural adjustments.      
   5. [Discover] Create progression happy paths for LABOT.  

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
      
### Notes on circuits

1. Motivate.  
2. Show examples.  
3. Exercise the ability to identify the function of a circuit from general knowledge and applied analysis.  
4. Exercise the ability to build a circuit given a blueprint.  
5. Exercise the ability to design a circuit given a functional specification.  

#### Composition of Apply sections

1. Employing first-look unaided analysis, formulate hypothesis.  
2. Employing a simulator, capture the circuit and test hypothesis. Amend if necessary.  
3. Employing lab kit and measurement equipment (multimeter, function generator, oscilloscope), built circuit and perform definitive analysis.  
4. Based on experience, extend the circuit with a given useful set of features and/or parameters.  
5. Based on the extended experience, design and build an advanced related circuit with a given functional definition.  
6. Employing an exhaustive technical narrative, including visual aids and cited sources, discuss the range of applications. (Wikipedia assignment.)  

### Notes on environment

1. Simulation.  
   1. [NI Multisim](https://www.google.com/search?q=multisim&oq=multisim&aqs=chrome..69i57j0l6j69i65.1688j0j7&sourceid=chrome&ie=UTF-8):
      1. Based on original Berkeley SPICE.  
      2. MSUD has license? (**TODO: Ask Kate**)  
2. Oscilloscope.  
   1. Digilent Discovery 
   2. [Instructables DPScope](https://www.instructables.com/DPScope-Build-Your-Own-USBPC-Based-Oscilloscope/).  
   3. Other even simpler.
      1. **TODO:** Compose a multi-part project for the course and weave in with the curriculum!!!  
