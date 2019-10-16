
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
Index To Learning Objectives 

Salesforce Identity Basics 
Describe how Salesforce Identity helps administrators.
Understand how Salesforce Identity can benefit a business.
Distinguish the difference between single sign-on (SSO) and social sign-on.
Describe the benefits of My Domain.Describe how employees benefit from Salesforce Identity.
Describe how customers and partners benefit from Salesforce Identity.
Describe what’s important when setting up user registration.
Know which features of Salesforce Identity benefit employees, which benefit partners and customers, and which benefit both.
Identify the industry standards used for identity and access management.
Know how SAML is related to XML.
Know the difference between an identity provider and service provider.

Company wide Org Setting 

Describe how configuring your company settings affect your end users.
Translate the company’s business requirements into your company settings.
Implement changes to your company information and fiscal year.
Update your personal locale settings.
Add new currencies to your org.
Summarize the impact of using single currency versus multiple currencies.
Set up Advanced Currency Management.
Edit conversion rates, and enable users to select personal currencies.

User Management

Describe a user account and the type of information it contains.
Add a single user or multiple users.
Use the Salesforce mobile app to manage users on the go.
Describe the difference between object and field level security
Describe how to set org–wide default sharing settings


