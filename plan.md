make a specific version of datashare for legal research.. get a grant to work on it. 

1. Add topics to it
2. Update the db
3. make it possibile to search by relationships
4. Get a chatbot set up baby. 
5. Make it scalable




I might just be able to use the front end and the database structure.
I might copy some of the pipeline code


I can the create any number of entity types and relationships via new pipelines that can work on the data index


1. documents
    * citations
    * title
    * Justices
    * Pro
    * Con
    * doctrine
    * volume
    * Organizations
    * States
    * Sentiment..
    * Etc.  


    So for the consumer I 
    
    * I need a postgesdb
    * elastic search
    * a frontend 

    For processing i need
    * Redis
    * nlp pipelines
    
    Redis
    Elastic Search
    Frontend 


# real plan

use the indexing capabilities of this software poroject


Features I'd like to add.   

Entity linking

Entity relationships 


So i might skip the existing nep workflow.  I want to extend it with the relik flow to an extent. 

It is not really just good enought o extractentities.   It is more importnat to link those entities. 


So to do this.. what is necessary.. 

A new Entity linking pipleine to get the candiditates.  those candidates will bea dded to the 


I will need to breakdown each document into sentences./ I will then parse each sentence within each document for subject, object, relationship triplets





Document > Sentences > Subjects > Objects > Relationship > Per document 




Entities

We can have subjects and objects


And the subjects and objects can have other types as well



entites

entity id > entity type id > label id > 

subjets

objects



sentences

doc id > sentence

Subjects

Docid > subject 


Relationships

docid > subjectid > relationship


Objects

dockid > subjectid > relatinoshipid > object 





So my first is to coopt the parsing flow. 

I need documents to entities 



So i will have 

entities related to other entities (or to themselves tbh)



Steps

1. Structure the db
2. Structure the parser
   1. document
   2. sentence
   3. entities
   4. relationships


I will try to keep a similiar framework but add the linking capabiliites to it      