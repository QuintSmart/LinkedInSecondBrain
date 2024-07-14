# All fleeting notes
``` dataview
List WITHOUT ID "[["+file.folder+"]]" FROM "" where startswith(file.name,"Fleeting")  
SORT file.name ASC

```
# All projects
``` dataview
List file.folder FROM "" where contains(file.folder,"Project") and contains(file.name,"Project")  
SORT file.name ASC

```