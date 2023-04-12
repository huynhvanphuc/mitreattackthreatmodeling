# Threat Modeling with MITRE ATT&CK Framework 
This provides a guided step by step walkthrough for threat modeling with MITRE ATT&amp;CK Framework<BR />
<img alt="GitHub followers" src="https://img.shields.io/github/followers/bvoris?style=social">
<img alt="GitHub User's stars" src="https://img.shields.io/github/stars/bvoris?style=social"><BR />
<img alt="GitHub" src="https://img.shields.io/github/license/bvoris/mitreattackthreatmodeling">
<img alt="GitHub commit activity" src="https://img.shields.io/github/commit-activity/m/bvoris/mitreattackthreatmodeling">
<img alt="GitHub All Releases" src="https://img.shields.io/github/downloads/bvoris/mitreattackthreatmodeling/total">
<img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/bvoris/mitreattackthreatmodeling">
<img alt="GitHub language count" src="https://img.shields.io/github/languages/count/bvoris/mitreattackthreatmodeling">
<img alt="GitHub issues" src="https://img.shields.io/github/issues/bvoris/mitreattackthreatmodeling">
<img alt="GitHub top language" src="https://img.shields.io/github/languages/top/bvoris/mitreattackthreatmodeling">


# Links
MITRE ATT&CK Website - this is needed to search for threat groups, techniques, and tools used by threat actors <BR />
https://attack.mitre.org/ <BR />
ATT&CK Navigator - maps out threat group techniques, allows for developing threat models <BR />
https://mitre-attack.github.io/attack-navigator/ <BR />

# What are you trying to accomplish?
We are trying to determine the matrices that show known attack techniques of threat groups and develop a model based on those techniques to help anticipate actions of those threat groups and help validate security controls.

# What do we need from here?
We need an industry. For this demonstation I've selected HEALTHCARE as the industry. <BR />

# Lets get started
Go to https://attack.mitre.org/<BR /><BR />
Click the search magnifying glass<BR />
<IMG SRC="https://github.com/bvoris/mitreattackthreatmodeling/blob/main/images/01search.png?raw=true" WIDTH=50% HEIGHT=50%><BR /><BR />
Search for "healthcare"<BR />
<IMG SRC="https://github.com/bvoris/mitreattackthreatmodeling/blob/main/images/02searchhealthcare.png?raw=true" WIDTH=50% HEIGHT=50%><BR /><BR />
For simplicity we will select two threat groups APT 40/Leviathan and APT 41<BR /><BR />
Now lets go to https://mitre-attack.github.io/attack-navigator/ <BR />
<IMG SRC="https://github.com/bvoris/mitreattackthreatmodeling/blob/main/images/03navigator.png?raw=true" WIDTH=50% HEIGHT=50%><BR /><BR />
Lets create a new layer<BR />
<IMG SRC="https://github.com/bvoris/mitreattackthreatmodeling/blob/main/images/04createnewlayer.png?raw=true" WIDTH=50% HEIGHT=50%><BR /><BR />
Select Enterprise under create new layer<BR />
<IMG SRC="https://github.com/bvoris/mitreattackthreatmodeling/blob/main/images/05selectenterpriseincreatenew%20layer.png?raw=true" WIDTH=50% HEIGHT=50%><BR /><BR />
Click on the layer and name it to the threat group<BR />
<IMG SRC="https://github.com/bvoris/mitreattackthreatmodeling/blob/main/images/06clicklayerintheupperleftandnamethelayer.png?raw=true" WIDTH=50% HEIGHT=50%><BR /><BR />
The change will be reflect in the layer name<BR />
<IMG SRC="https://github.com/bvoris/mitreattackthreatmodeling/blob/main/images/07layernamedAPT40.png?raw=true" WIDTH=50% HEIGHT=50%><BR /><BR />
Click the magnifying glass under selection controls<BR />
<IMG SRC="https://github.com/bvoris/mitreattackthreatmodeling/blob/main/images/08clickthemagnifyingglass.png?raw=true" WIDTH=50% HEIGHT=50%><BR /><BR />
Search for the Threat Group in the search field<BR />
<IMG SRC="https://github.com/bvoris/mitreattackthreatmodeling/blob/main/images/09clickselectnexttothethreatgroupname.png?raw=true" WIDTH=50% HEIGHT=50%><BR /><BR />
Click select next to the threat group<BR />
<IMG SRC="https://github.com/bvoris/mitreattackthreatmodeling/blob/main/images/09clickselectnexttothethreatgroupname.png?raw=true" WIDTH=50% HEIGHT=50%><BR /><BR />
Selected techniques should now appear highlighted<BR />
<IMG SRC="https://github.com/bvoris/mitreattackthreatmodeling/blob/main/images/10oncethethreatgrouphasbeenselectedtheywill%20behighlighted.png?raw=true" WIDTH=50% HEIGHT=50%><BR /><BR />
Now we want a bit more visibility in the techniques so we will select a color<BR />
<IMG SRC="https://github.com/bvoris/mitreattackthreatmodeling/blob/main/images/11undertechniquecontrolsselectacolor.png?raw=true" WIDTH=50% HEIGHT=50%><BR /><BR />
The attack techniques should now be colored.<BR />
<IMG SRC="https://github.com/bvoris/mitreattackthreatmodeling/blob/main/images/12allattacktechniquescolored.png?raw=true" WIDTH=50% HEIGHT=50%><BR /><BR />
Now we need to add a score to provide a value or weight to the attack techniques<BR />
<IMG SRC="https://github.com/bvoris/mitreattackthreatmodeling/blob/main/images/13clickscore.png?raw=true" WIDTH=50% HEIGHT=50%><BR /><BR />
Set the value for score to 1<BR />
<IMG SRC="https://github.com/bvoris/mitreattackthreatmodeling/blob/main/images/14score1.png?raw=true" WIDTH=50% HEIGHT=50%><BR /><BR />  

# We've added our first known threat group now we need to add more for the industry we selected.
For this exercise we will add one more, but keep in mind you can add as many as you need for your threat model.  

Lets add one more by clicking the + <BR />  
<IMG SRC="https://github.com/bvoris/mitreattackthreatmodeling/blob/main/images/15clickthe+tocreateanewtab.png?raw=true"><BR /><BR />
Lets creat a new layer<BR />
<IMG SRC="https://github.com/bvoris/mitreattackthreatmodeling/blob/main/images/16clickcreatenewlayer.png?raw=true" WIDTH=50% HEIGHT=50%><BR /><BR />
Click enterprise<BR />
<IMG SRC="https://github.com/bvoris/mitreattackthreatmodeling/blob/main/images/17clickenterprise.png?raw=true" WIDTH=50% HEIGHT=50%><BR /><BR />
<BR /><BR />
## Connect with me at

<a href="https://twitter.com/HMInfoSecViking?ref_src=twsrc%5Etfw"><IMG SRC="https://github.com/bvoris/bvoris/blob/master/twitter.jpg" WIDTH=10% HEIGHT=10%></a>

<a href="https://www.linkedin.com/in/brad-voris" target="_blank"><IMG SRC="https://github.com/bvoris/bvoris/blob/master/linkedin.png" WIDTH=10% HEIGHT=4% ALIGN=RIGHT></a>

<BR /><BR />
<BR /><BR />

<A HREF="https://www.victimoftechnology.com">Victim Of Technology<A />
<BR /><BR />
<A HREF="https://www.cyberforgesecurity.com">Cyber Forge Security, Inc.<A />
<BR /><BR />
