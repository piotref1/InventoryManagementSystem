# InventoryManagementSystem
General inventory management system. Mainly focused on being able to get list of games, consoles and accessories for them into DB and hten displayed online via website.
Plan is to make it modular so you could decide which modules to use only for games, consoles, etc. 
Planned modules also are about storing data of general home things like tools, clothes, pantry supplies etc. And also to have some for storing info about artists that I want to download art from.

Modules planned:
1. Games - divided by the manufacturers like Nintendo, Microsoft etc. PC will be under one umbrella term with sub groups for stores like Steam, Origin, Uplay etc. Only Steam so far can be auto updated due to data being publicly available on Steam website. 
Steam (GameLibrary repo, needs work), Nintendo (GB/C/A, GC, Switch etc), PC, Sega, Sony, Microsoft, etc.
2. Consoles: Divided by manufacturer, being able to store the most important information like state, SN, Limited Edition etc.
3. Accessories: Similar to point 2. With being able to search for entries that fall under specific consoles or makers.
4. Artists: Web scraping to download and organize art from varied sources.
5. Household: Tools, Pantry stock, general things like TV etc. 


Backend: 
Python

Database is the most likely to change:
PostgreSQL 
Possible other:
GraphQL, PostgreSQL

Frontend:
Either Django or Flask
React
