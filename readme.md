
Target Certificates: 

ADM 201 - For Consultants 

Salesforce Platform Dev 1 - Dev Focused ( Basics )

App Builder - For Architects 



Notes: 

Table / Object / Entity 

Column / Fields / Attributes 

Rows / Records / Tuples 

Types of Objects 

Standard VS Custom Objects 


Relationships in Salesforce 

Data Redundancy AND Data Inconsistency 

4 types of relationships 

One to One
One to Many 
Many to One 
Many to Many


Master-Details: 
	Child record cannot exist without relating to parent record 
	Delete child records when parent record is deleted 
	Create relation on child object as a field 
	Child record gets sharing and security setting from parent record 
	Can allow re-parenting of child records 
	Can recover all deleted child records if parent record is recovered

*** Standard Object cannot be on the detail side of the master details relationship ***
	
	
*** Expect Lead OR User All Standard Objects can be on the master side of the master detail relationship. ***





Types of Relationships : 

1. Master Detail 
2. Lookup Relationship 
3. Self-Relationship ( when a student refers another student / Lookup relation to the same object ) 
4. Hierarchal relationship ( Self Relationship on the User Object )


Many to Many Relation Can be implemented with an intermediary table w/ Id of both matching records as foreign keys - Junction Object As TWO Master Detail Relations w/ the 2 parent objects

Primary Master Object VS Secondary Master Object 

Whichever relation is created first in the Junction object becomes the Primary Master Object 

Security Settings ( Inherited from both the parents ) 
Look and Feel ( Inherited from the Primary Master Object ) 
Owner field ( Inherited from Primary Master Object )


Number of Master relations on a single Object
No. Of Lookup relations on a single object 




Salesforce Admin Playlist - 32 Videos 
https://www.youtube.com/watch?v=bOzlOkPU0cI&list=PLdYQMTciVWO9xjvh1J7SXjhzpnzWvLih4&index=2&t=0s


Trail Head Notes 

cunning-fox-fibjf7-dev-ed.my.salesforce.com

Salesforce Platform Basics - Completed. 