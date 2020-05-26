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
Once the text on the top right says "Connected!", you are connected to the server and may login, until then, the textfields are inaccessible. You can log in and register using the same textfields. There is no verification process or email link implemented yet, only username and password. No re-entering the password to verify it yet, so be cautious. A proper registration process will be implemented in near future (within next week).
#
2. Main Menu
![loqin screen](https://i.imgur.com/VBk4JZf.png)
Temporarily only buttons.
- "Add Map" allows you to register a new map by its name to the database
- "Profile" shows you currently kind of irrelevant data about your profile
- "Add Node" will let you input data that is nessecary to register unregistered quality resource spots
- "Map View" projects the graphic of any map with all registered nodes to it, allowing you to see where quality spots on that map are
- "Quit" closes the program, this also logs you out as of now
- "Help" brings you to this exact webpage (chances are, this is how you got here)
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

# Contact

Email: m16a1@live.de

# Changelog
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
