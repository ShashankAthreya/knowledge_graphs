[[Shi_et+al_LearningPathRecommendationModelBased_2020]]

# [A learning path recommendation model based on a multidimensional knowledge graph framework for e-learning](https://doi.org/10.1016/j.knosys.2020.105618)

## [[Daqian Shi]]; [[Ting Wang]]; [[Hao Xing]] et al.

## Abstract
Abstract E-learners face a large amount of fragmented learning content during e-learning. How to extract and organize this learning content is the key to achieving the established learning target, especially for non-experts. Reasonably arranging the order of the learning objects to generate a well-defined learning path can help the e-learner complete the learning target efficiently and systematically. Currently, knowledge-graph-based learning path recommendation algorithms are attracting the attention of researchers in this field. However, these methods only connect learning objects using single relationships, which cannot generate diverse learning paths to satisfy different learning needs in practice. ==To overcome this challenge, this paper proposes a learning path recommendation model based on a multidimensional knowledge graph framework==. The main contributions of this paper are as follows. Firstly, we have designed a multidimensional knowledge graph framework that separately stores learning objects organized in several classes. Then, we have proposed six main semantic relationships between learning objects in the knowledge graph. Secondly, a learning path recommendation model is designed for satisfying different learning needs based on the multidimensional knowledge graph framework, which can generate and recommend customized learning paths according to the e-learner’s target learning object. The experiment results indicate that the proposed model can generate and recommend qualified personalized learning paths to improve the learning experiences of e-learners.

# Participants and statistics
Analysis of experiment results. The experiment included 251 participants and generated 2440 qualified experiment result records; 1470 records were from the test group, and 970 records were from the control group. Figs. 6.2 and 6.3 show some basic information about the 251 participants, we can find that participants are balanced distributed in gender and location
The experiment included 251 participants and generated 2440 qualified experiment result records; 1470 records were from the test group, and 970 records were from the control group. Figs. 6.2 and 6.3 show some basic information about the 251 participants, we can find that participants are balanced distributed in gender and location. It is worth to mention that all participants were randomly divided into two groups with a similar gender ratio and the ages of all participants are between 19 to 26 years old
[object Object]

## Key concepts
#finding/#learning_object; #learning_object; #finding/#knowledge_graph; #knowledge_graph; #ontology; #adaptive_learning; #ontologies

## Quote
> We presented a learning path recommendation model based on a multidimensional knowledge graph that resulted in e-learners that are more satisfied with the learning paths recommended for his learning needs

## Key points
- With the popularity and improvement of information search technology, increasingly more learners choose self-learning through the Internet, which is a well-known method for elearning [^1]
- This section describes how we evaluate the learning path recommendation model, which includes a description of the experiment process and the experiment data analysis
- Results analysis: Based on the data collected from the feedback, we will evaluate our learning path recommendation model through a data analysis
- We presented a learning path recommendation model based on a multidimensional knowledge graph that resulted in e-learners that are more satisfied with the learning paths recommended for his learning needs
- Based on our knowledge graph, we proposed a learning path generation algorithm which can generate the learning path by the target learning object
- This paper introduced a method for efficiently recommending suitable learning paths for e-learners that can be expanded and used in any other e-learning knowledge field

## Synopsis
A learning path recommendation model based on a multidimensional knowledge graph framework is proposed.
It can generate and recommend customized learning paths according to the e-learner’s target learning object.
Researchers have proposed various methods for improving learning efficiency.
This paper proposes a learning path recommendation model based on the knowledge graph (KG) to satisfy diverse learning needs.
The authors have built a knowledge graph based on machine learning field knowledge as the use case.
This paper introduced a method for efficiently recommending suitable learning paths for e-learners.
Based on the knowledge graph, they proposed a learning path generation algorithm which can generate the learning path by the target learning object.
This paper can be expanded and used in any other e-learning knowledge field.<br/><br/>251 participants were included in the analysis. <br /><br />Some of the researchers’ findings claim to substantiate prior work in this area: “The procedure of manually proofread mainly includes 2 annotators determine whether the learning objects and relationships are correct in raw data.
The ‘incorrect data’’ is checked and annotated by a super-annotator which is the expert.
Cohen’s kappa coefficient is 0.63 which means the annotations are substantial agreement,” Shi argued. <br /><br />However, “There are still some limitations to the model to be applied to another knowledge field.
Future research can focus on how to improve the success rate of generating learning paths with complex relationship constraints,” observe the investigators. <br /><br />The team advocate that when applying this model to another knowledge field, the quality of data collection will affect the results.
Future research can focus on how to improve the success rate of generating learning paths with complex relationship constraints.<br /><br />


## Summary

### Introduction
With the popularity and improvement of information search technology, increasingly more learners choose self-learning through the Internet, which is a well-known method for elearning [^1].
Other work [^9],[^10],[^11],[^12] used knowledge graphs for applying these dependencies to the learning path recommendation model and has achieved some success
They only built the simplest relationship to link learning objects but did not explore further by building more complex semantics in the relationship.
This paper proposes a learning path recommendation model based on the knowledge graph (KG) to satisfy diverse learning needs.
To improve the learning path recommendation model by using semantic relationships, an innovative knowledge graph framework is designed for storing and presenting learning objects.
The authors have constructed more complex and logical semantic relationships between these learning objects
Based on this framework, the authors have introduced a learning path generation algorithm and a learning path recommendation algorithm in the model.

### Related work
Researchers have proposed various methods for improving learning efficiency; constructing systems [^13],[^14],[^15] for recommending learning materials to e-learners is a leading-edge research field.
For systematic and efficient e-learning, individuals should study learning objects in the suggested learning path order to achieve their learning target
Based on this context, researchers have tried to explore the dependency of learning content in e-learning systems.
Some researchers [^19],[^20],[^21] tried to obtain concept prerequisite relation from course dependencies by novel approaches like directed graphs
These works show great potential in exploring the dependency on learning content in the e-learning environment.
Hsieh and Wang [^26] developed an e-learning system using a data mining approach that can create a relationship hierarchy of learning materials to generate a suitable learning path
With these data-mining-based methods, learners no longer need to waste time organizing the learning content, but there are still some problems: (1) Updating new data in this type of learning system will be difficult because these systems are not self-adaptive, so the learning path has to be generated every time data updates are performed.
Based on the related studies described above, the authors will design a specific knowledge graph for the learning path recommendation model, and try to recommend logical learning paths that satisfy the diverse learning needs of individuals

### Knowledge graph design
The authors have designed a knowledge graph framework in order to better organize learning objects and to logically express semantic relationships between learning objects.
The authors build a knowledge graph that has been applied to the learning path recommendation model by taking partial machine-learning knowledge as a use case

### Definition of terminology
To better explain the content that follows, the authors have defined some relevant terminology that will be used in this paper.
In which: LO is the set of all the learning objects in the knowledge graph, and RE is the set of all the relationships in the knowledge graph.
When the authors have the target learning object ‘‘Region_Based_CNN’’, ‘‘what is the prior knowledge of Region_Based_CNN’’ and ‘‘how to achieve Region_Based_CNN by basic knowledge’’ are two different learning needs.
The authors use labels to represent different learning needs.
Requesting the learning path from algorithm to target.
Requesting the learning path from basic knowledge to target

### The framework of the knowledge graph
The authors proposed a multidimensional knowledge graph framework for representing knowledge.
The authors decided to separate different learning objects into three classes: Basic Knowledge
This class contains all the necessary basic knowledge learning objects for supporting algorithms, such as ‘‘naïve Bayes’’ and ‘‘Bayesian statistics’’, which is the bottom level of this knowledge graph framework.
E-learners can understand what practical tasks they can achieve/solve after they have learned the basic knowledge/algorithm.
The hierarchy represents the knowledge structure of the current class, while the learning objects are the meta-learning materials that are inserted into the hierarchy and connected by semantic relationships.
Interclass relationships provide connections between learning objects from different classes.
The authors' knowledge graph provides multiple classes for learning objects and strengthens the connections between interclass learning objects.
The knowledge graph is able to show how to practically apply the learned knowledge, which can expand the e-learners’ understanding of the learned knowledge and enable them to grasp the practical use of theoretical knowledge

### Data collection
The authors have built a knowledge graph based on machine learning field knowledge as the use case.
A named entity recognition model was trained using this list to recognize basic knowledge in algorithms and to extract the relationship between the target basic knowledge and the current algorithm.
To this point, raw data with all the learning objects and relationships has been obtained.
Since the data from the network is not always reliable, the data need to be processed using expert knowledge
In this step, the authors manually proofread the information about learning objects and corrected wrong relationships.
A knowledge graph was built that contained 225 basic knowledge objects, 361 algorithm objects, 89 task objects, and 1033 relationships.

### Learning path recommendation model
Based on the knowledge graph, the authors can start designing and developing the learning path recommendation model.
This section first presents how to generate all the possible learning paths according to the specific learning need, and presents how to recommend an appropriate learning path from these possible learning paths.
The structure of the recommendation model and detailed algorithms will be introduced at the end

### Learning path generation algorithm
In order to make the proposed learning path recommendation model more user-friendly, the authors design an algorithm based.
Details of weight distributions are as follows: on the multidimensional knowledge graph to generate the possible learning path through the e-learner’s target learning object and the learning need.
This algorithm replaces the learning path generation algorithm [^10] which using the starting and ending learning objects.
Because most of the e-learners only know the target learning object but not the starting node in general
In this algorithm, the semantic relationships in the multidimensional knowledge graph will be used as constraints for generating the learning path.
Learning path generation will start with the target learning object, and search for the learning object connected by the relationship under the constraints.

### Learning path recommendation algorithm
Based on the e-learner’s input, the learning path recommendation model may generate many possible learning paths.
The model should not output multiple learning paths all at once as the result recommended to the e-learner.
The optimal learning path needs to be selected for the e-learner.
In this context, the authors have designed a learning path recommendation algorithm as shown in Eq (2).
The target of maxi=0...kScore(Pi) is to output the recommended learning path Pb with the highest score.
In Eq (2), Pi is a specific learning path which needs to be scored.
K is the total number of these learning paths.
In Eq (2), Pi is a specific learning path which needs to be scored. k is the total number of these learning paths. n is the total

### Authority
When w1 = 0, w2 = 0, w3 = 0, w4 = 0.5, w5 = 0.5, the selected learning path considers the impact of publishers and authors which represent the authority of publishers and authors.
In this context, e-learners can select learning preference to generate learning path according to their needs.
The authors propose a function for calculating the weight distribution when e-learners have multiple learning preferences, as shown in Eq (3).
W is the function for calculating corresponding weights for lpi.
According to the learning path recommendation algorithm above, the model can recommend the most appropriate learning path among multiple learning paths

### Learning path recommendation model based on knowledge graph
The main procedures of how to generate the recommended learning path according to the learner’s query are shown in algorithm 1.
E(Tp) represents the earliest publishing year for algorithms in the KG.
Min(Hp) and Max(Hp) represent the minimum and maximum H5-index value.
Min(Ha) and Max(Ha) represent the minimum and maximum H5-index value of the author.
2. The learner’s input query will be sent to the model for extracting the target learning object and learning need in algorithm 2.
The raw input query Q needs to be converted into the token set by preprocessing
This step includes removing stop words, tokenization, lemmatization and some other basic natural language preprocessing methods.
The model needs to recognize the target learning object and its class.
The learning need will be obtained from the class of the target learning object and the query keywords.
The model will output the recommended learning path with the highest score

### E-learning system design
The quality of learning content is the most important part of the learning path recommendation, the learning quality can only be guaranteed when the learning content is accurate.
Input: The knowledge graph G = (LO, RE); The learner’s query Q ; The feature set F ; Output: The recommended learning path Pb. 1.
The kernel algorithm unit will return the possible learning path set P and the recommended learning path Pb. Algorithm 2 Input processing: extract the target learning object and analyze learning need.
Input: The knowledge graph G; The target learning object Ot ; The learner’s learning need Nu; Output: The possible learning path set P; 1.
The possible learning path set P will be presented in the graph-display window, and the target recommended learning path and guidance will be presented in the text-description window.
The target learning object and its related learning object set were presented through the operable graph-display window to maximize the possibility of discovering potential learning content.
The system fully exploits the connectivity of the knowledge graph when presenting the learning content, so that e-learners can explore more potential learning content while using the learning path recommendation system

### Experiment process description
This learning path recommendation model aims to output the target learning content according to e-learner’s input query.
The test model uses the learning path generation algorithm based on the multidimensional knowledge graph; this algorithm can generate the learning path by the target learning object.
Participants will be divided into test and control groups without telling which group they are in
They will be asked to use the corresponding model to conduct 10 learning path searches based on their own learning interests.
Feedback collecting: Participants are asked to record and score their search results, in which feedbacks from the test group will be used to verify the hypothesis (ii).
Results analysis: Based on the data collected from the feedback, the authors will evaluate the learning path recommendation model through a data analysis.
The expected performance of the model will be verified in this step

### Analysis of experiment results
The experiment included 251 participants and generated 2440 qualified experiment result records; 1470 records were from the test group, and 970 records were from the control group.
There is no significant decrease in the success rate of the test model under #3
This indicates that by using the semantic relationship, the learning path generation algorithm based on the multidimensional knowledge graph is robust and will not be affected by a missing learning object in the learning path.
Most of the successful participants in the control group have relevant learning experience
This indicates that the test model is user-friendly for inexpert e-learners who need guidance.
This suggests that the learning path recommendation model still needs to improve in its ability to generate appropriate learning paths within the complex relationship constraints and longer length

### Conclusion and future work
The authors presented a learning path recommendation model based on a multidimensional knowledge graph that resulted in e-learners that are more satisfied with the learning paths recommended for his learning needs.
Based on the knowledge graph, the authors proposed a learning path generation algorithm which can generate the learning path by the target learning object.
This paper introduced a method for efficiently recommending suitable learning paths for e-learners that can be expanded and used in any other e-learning knowledge field.
There are still some limitations to be noted
When applying this model to another knowledge field, the quality of data collection will affect the results of the learning path recommendation.
Daqian Shi: Conceptualization, Methodology, Software, Validation, Formal analysis, Data curation, Writing - original draft, Writing - review & editing.


## Study subjects

### 251 participants
- Analysis of experiment results. ==The experiment included 251 participants and generated 2440 qualified experiment result records; 1470 records were from the test group, and 970 records were from the control group==. Figs. 6.2 and 6.3 show some basic information about the 251 participants, we can find that participants are balanced distributed in gender and location

### 251 participants
- The experiment included 251 participants and generated 2440 qualified experiment result records; 1470 records were from the test group, and 970 records were from the control group. ==Figs. 6.2 and 6.3 show some basic information about the 251 participants, we can find that participants are balanced distributed in gender and location==. It is worth to mention that all participants were randomly divided into two groups with a similar gender ratio and the ages of all participants are between 19 to 26 years old

## Data analysis
- #method/cohens_kappa_coefficient

## Findings
- The accuracy of the learning object information (96.7%) and relationships (94%) proves that our knowledge graph reliably supports the learning path recommendation

##  Confirmation of earlier findings
- The procedure of manually proofread mainly includes (a) 2 annotators determine whether the learning objects and relationships are correct in raw data; (b) compare the results from annotators, we regard the agreements with correct labels as ‘‘correct data’’, agreements with incorrect labels and all disagreements as ‘‘incorrect data’’; (c) the ‘‘incorrect data’’ is checked and annotated by a super-annotator which is the expert. For the procedure (b), ==we use Cohen’s kappa coefficient [^36] to verify the reliability of the annotation from inter-annotators, the result is 0.63 which means the annotations are substantial agreement==

## Contributions
- <strong>Conclusion and future work</strong><br/><br/>In this paper, we presented a learning path recommendation model based on a multidimensional knowledge graph that resulted in e-learners that are more satisfied with the learning paths recommended for his learning needs. We designed a multidimensional knowledge graph with diverse relationships between learning objects for presenting learning content. Based on our knowledge graph, we proposed a learning path generation algorithm which can generate the learning path by the target learning object. This algorithm has been proven to be more efficient in generating suitable learning paths than previous algorithms. Furthermore, we proposed a weighted coefficient scoring method for selecting the target learning path considering the e-learner’s learning needs. In conclusion, our learning path recommendation model can generate satisfactory learning paths for e-learners and improves their learning efficiency.

## Limitations
- There are still some limitations to be noted. When applying this model to another knowledge field, the quality of data collection will affect the results of the learning path recommendation. At the same time, future research can focus on how to improve the success rate of generating learning paths with complex relationship constraints, which can improve the quality of the recommended learning path.

## Future work
- Feedback from participants was used to verify the quality of the recommended learning paths. Section 7 presents the conclusions and future research.
- When applying this model to another knowledge field, the quality of data collection will affect the results of the learning path recommendation. At the same time, future research can focus on how to improve the success rate of generating learning paths with complex relationship constraints, which can improve the quality of the recommended learning path.
