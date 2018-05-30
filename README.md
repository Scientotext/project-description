# Sciento-text
## Goal of the Project
Design of a Sciento-text Computational Framework for Retrieval and Contextual Recommendations of High Quality Scholarly Articles.

## Project Member
* Department of Computer Science - Banaras Hindu University - Varanasi
* GESIS - Leibniz Institute for the Social Sciences - Department of Knowledge Technologies - Cologne

## Scientific objectives and individual components of the joint project:
The project aims to design a computational framework for retrieval of high quality scholarly articles and obtaining recommendations in a given research/ semantic context. The broader idea is to bring together concepts from Information Retrieval and Scientometrics to identify scholarly articles relevant to a given information need (or a context) and rank them based on their relevance to the information need as well as their scholarly quality. 

More precisely the project will have following components:
*	Identifying the information need of a researcher either directly or from the contextual environment. A researcher/ learner may specify his/ her information need in form a query directly. Alternatively the system will have to be trained to identify research context of the user by text mining of research articles that s/he may be reading. This will involve implementing sophisticated natural language processing and information extraction algorithms and techniques.
*	Retrieving Relevant Documents. The second component of the system is retrieval of relevant documents (scholarly articles) corresponding to the learned information need. This would require design of conceptual representation of text documents (scholarly articles), computing semantic similarity and identifying suitable matches. Unlike a traditional search engine which measures relevance largely by syntactical similarity measures, the proposed system will incorporate techniques derived from Scientometrics filed (such as bibliometric and network models, co-word and co-citation analysis) for improved semantic matches and retrieval. 
*	Ranking Scholarly Articles for User Recommendation. The third component of the system will deal with ranking candidate articles retrieved based on their scholarly quality and importance. This would involve methodologies from Informetrics, such as exploiting Scientometric indicators (publication source, age, citations and citation potential etc.), percentile measures and Bradfordian zones etc.; and algorithms from information retrieval domain (applied to scholarly article domain).

The proposed framework can generate two kinds of results. First, it can retrieve high quality scholarly articles for a given search query. Second, it can generate contextual retrieval and recommendations by identifying articles semantically similar to a given article being pursued by the reader. In both cases, the retrieved results would comprise of articles ranking high on scholarly quality. A suitable measure of scholarly quality of an article would be developed. The proposed framework would be capable of both retrieval and contextual recommendations.
