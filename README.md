# LOQSTool - Help and Documentation
Last Oasis - Quality Spot Tool

Content:

1. Installation
2. How to use the tool
3. Quality in Last Oasis
4. Q&A
5. Contact
6. Changelog

# Installation

If you have Java installed: Download loqstool.jar and doubleclick it to open.
  
If you don't have a Java installed: Download the most recent Java version from here: https://www.java.com/en/download/. Then download     loqstool.jar and doubleclick it to open.

If you encounter any issues during the process, feel free to contact me with an explanation of your issue. While the tool is only tested on Windows, it should theoretically work with most devices that have java on it.

#
![loqstool.jar location](https://i.imgur.com/Cpn66Zi.png)
#

# How to use the tool

Note: The UI is extremely primitive as of right now, but will be redesigned in near future. This is one of my priorities at the moment. The design already exists, but the implementation might take a week or two. Please be tolerant to the current state of the design, at least its functional.

1. Login and Register
![loqin screen](https://i.imgur.com/zy4ueVD.png)
Once the text on the top right says "Connected!", you are connected to the server and may login. Until then, the textfields are inaccessible. You can log in and register using the same textfields. There is no verification process or email link implemented yet, only username and password. No re-entering the password to verify it yet, so be cautious. A proper registration process will be implemented in near future (within next week).
#
2. Main Menu
![main menu](https://i.imgur.com/VBk4JZf.png)
Temporarily only buttons.
- "Add Map" allows you to register a new map by its name to the database
- "Profile" shows you currently kind of irrelevant data about your profile
- "Add Node" will let you input data that is nessecary to register unregistered quality resource spots
- "Map View" projects the graphic of any map with all registered nodes to it, allowing you to see where quality spots on that map are
- "Quit" closes the program, this also logs you out as of now
- "Help" brings you to this exact webpage (chances are, this is how you got here)
#
3. Add Map
![register map](https://i.imgur.com/4POK4MR.png)
As simple as it gets. Enter the mapname and layout-type to enable node registration to it, if it doesn't already exist on the database. Beginner-Maps are excluded, due to lack of demand and Crater Maps are excluded, due to volatility. Changes to this and new maps will be considered at any time. Demand usually results in change.
#
4. Profile
![profile screen](https://i.imgur.com/FcJxA1v.png)
It is pretty useless at the moment and more of a placeholder.
#
5. Add Node
![add node](https://i.imgur.com/meboNEt.png)
- Map Input - Type in the name of the map you are trying to add a data node to. If it doesnt show up in the "Suggested"-section, it might just not be registered yet, in which case you will have to add it first in the "Add Map"-menu. The suggested-section is not case-sensitive, feel free to use only lower letters.

- Resource type - The name of the resource which you want to add. If it doesn't show up, it has not been implemented yet. Please contact me via my mail (found below in this readme), if you encounter this issue.

- Quality - The maximum quality of the resource node. You can get this information ingame at the top of your screen when you are directly looking at a resource node and an informationwindow pops up. The number shown will be something like "22/43+". Please insert the number after the "/", so in this case "43+" (include the plus symbol, if it exists). For more information on quality, please consider the next chapter "Quality in Last Oasis".

- Position - In Last Oasis, at the top-right of your screen, you can see your current positions' coordinates. There are plenty of numbers, but the one we are interested in, are the "L=x,x,x" - coordinates. The first 2 numbers make up for the X and Y value:
![position](https://i.imgur.com/5t6WrEg.png)
So, if your game says you're at (L=1000,-2000,3000), then insert (X=1000 and Y=-2000).

- Please make sure to only submit a node once. Duplicate nodes may result in negative contribution. This has no meaning as of right now, but will eventually turn out to be the currency you may pay with alternatively to actual money.
#
6. Map Viewer
![map viewer](https://i.imgur.com/BdIXZ0z.jpg)
- To search for nodes on a specific map, insert its name into the searchbox. Make sure to use the autofill function, whenever possible, to avoid loading errors due to spelling mistakes. The autofill also indicates, wether or not a map has already been registered, since it would only autocomplete the names of registered maps.

- To show resource nodes, check the box with the resource type of your choice and nodes will pop up on screen, if such exist. the number next to the resource type will indicate, how many registered quality-nodes there are on this specific map.

- Click on the nodes to show its information, like position, verification score and maximum quality.

- Confirm Node - Once you have seen and/or harvested a resource node, that was not submitted by you, you may "confirm" this node. as of right now, this functionality only servers the purpose to indicate, how often a node has been verified by others. In future, this will affect your score, which again, will grant you access to features alternatively to money. Your contribution matters.
# Quality in Last Oasis

I couldn't have made it better myself, so I prefer to redirect you to this online document: https://docs.google.com/document/d/1rM6Gt2k3zWGwzAbSeO1cdze2qWqe12p3dUpUdDz97z4/edit#

Props to the guys from OwO, who are responsible for creating this useful guide!

# Questions and Answers

Q: Isn't your program considered cheating?

A: No, unless you consider sharing Excel-Tables with your friends cheating aswell. LOQSTool's functionality is technically merely a more optimized shared spreadsheet.
#
Q: Is this software for free?

A: It will always be, to a certain extend. Since my tool heavily depends on cloud based traffic, which I pay out of my own pocket at the moment, I will have to implement a way to compensate for the costs, sooner or later. I consider leaving this tool entirely for free for common use and put some small pricetags on special features, like individual contracts with big clans. However, this is merely a fun project to me so I have no interest of making profit. I consider myself a non-profit-organization.
#
Q: I really don't want to pay for this, do I have to eventually, in oder to use the software to its fullest extend?

A: This software lives off of YOUR contribution. My goal is to implement a way to reward data contributions to the global network with free access to all of the softwares features. In other words: You keep contributing to the ecosystem of the tool and I will reward you for that by granting you access to my tool's features. More info on that in near future.
#
Q: Why doesn't the tool read out the resource data from the game automatically?

A: To ensure your safety, I do not implement any functionality, that interacts with the gameprocess itself, since that may lead to account suspension. As of so far, the game devs seem extremely strict when it comes to the use of external software. I am already prepared for that day, however, on which the devs might allow my software to read out gamedata automatically, either through an API or image-recognition. Once I see a green light from the devs, I will be implementing a feature to automatically add data immediately. Until then, my goal is to make the data input as smooth and comfortable as possible, while keeping my software risk-free.
#
Q: We are a clan, how exactly can we profit from contacting you directly?

A: The most requested solution would be a private realm. With this feature, all your clanmember's data submissions will only be visible to other clanmembers, while all of you have access to read out the data from both, the clan AND global network. You may also submit selected nodes to the global network, if desired. This allows for more "insider information control" on your clan controlled maps. Random players, however, may still submit resource nodes from "your map" to the global network. If you have a request on your own, may it be a clan-wide checklist or whatever, then please feel free to contact me, so we can make an arrangement.
#
Q: What are major future goals of this application?

A:
- Making this software a web-application (in addition to the java version) for easier access across different devices (and java-haters)
- Implementing a realm functionality, like a privaterealm that allows access to private maps and nodes, stored locally on your PC
- A proper monetization and reward system that ideally doesn't impair the usability and experience of this tool, while also covering for its cost
- Being greenlighted by the devs to allow my tool to collect resource data automatically, either through image recognition or an API

(There are many more goals, however, I consider these the top milestones)
#

# Contact

Email: loqstool@outlook.com

# Changelog
v0.0.5 (28.05.2020):
(last patch before UI overhaul)
- redesigned ui in backend to allow stagelayering
- effect renderer added for e.g. darken ui effects when layered
- added official email address rather than private one
- updated main ui (currently map viewer panel) partially to prepare for ui overhaul
- menuicons and layout created
v0.0.4 (28.05.2020):
- 'Help' now redirects to the "how to use"-section of this read-me page
- better registration (external panel)
- some ui refactoring
- menu data layout fix
- input validation handling
#
v0.0.3 (26.05.2020):
- input textfields are now being properly restricted to the set of characters that should be used
- unsupported resourcetypes (added later in development) are removed from the user interface
- unified access to supported regions and resourcetypes prevent errors caused by trying to add unsupported data
#
v0.0.2 (26.05.2020):
- nodes are being counted and the count is shown next to the respective resources' filterlabel
- fixed a bug that caused checkboxes to work in reverse (checking them would hide nodes on map and unchecking would show them)
- verifications added, you may now verify each node's existance to filter out incorrect node submissions
- verifications are now being displayed in each nodes' information
- slightly increased performance
#
v0.0.1 (22.05.2020):
- initial commit, super basic functionality
#
