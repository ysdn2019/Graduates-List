# Graduates List

All graduates information will be stored in markdown files. <br>
Markdown is a lightweight markup language with plain text formatting syntax.<br>
The filename extension for markdown: `title.md` where `md` stands for markdown. 
<br>

***
### **File Format Cheat Sheet:**
```
---
path: /graduates/first-last
name: First Last
portfolio:
linkedin:
twitter:
instagram:
medium:
dribble:
behance:
interestArea:
where:
relocation:
---
```

***

### **File Format Convention:**
```
firstname-lastname.md

Examples:
caitlin-lewis.md
zilin-deng.md
```
**If graduates have a preferred name:** <br>
`Daniel (Do-Hyun) Kim` becomes: `daniel-kim.md`

**If graduates have a middle name:** <br>
`Joel Lou Louzado` becomes: `joel-louzado.md`

***

### **Inside the Markdown file:**
At the top of the file,
1. The data is encapsulated within three (3) open and close hyphen's `-`
2. The format: `property: attribute` (the property is in lowercase)

**The path property is required! It lets us know where to look when creating the profile page. <br>
Make sure it is the first entry listed in the Markdown file.** <br>
Please follow this format:
`path: /graduates/firstname-lastname`
```
---
path: /graduates/zilin-deng
name: Zilin Deng
portfolio: http://zilindeng.co/
etc.
---
```
**Links:** <br>
In order for the links to route to their destination, they must be formatted correctly. <br>
`portfolio: zilindeng.co` becomes: `portfolio: https://zilindeng.co` <br>
`instagram: @zilindeng` becomes: `instagram: https://www.instagram.com/zilindeng/`

**Missing Information:** <br>
If a property is missing an attribute, do not remove the property. <br>
Leave the property blank.
```
Example: Daniel Kim doesn't have a portfolio website
---
path: /graduates/daniel-kim
name: Daniel (Do-Hyun) Kim
portfolio:
etc.
---
```
**Creating a new branch and start a pull request**
When it's time to commit changes made to a file
1. Select `Create a new branch for this commit and start a pull request`
2. Name the branch after yourself, you will be working off of your own branch. `firstname-branch eg. caitlin-branch`
3. Hit `Propose file change`

