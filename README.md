# React Folder Structures

- All the files present in the directory are empty and are just used for sample purposes.
- Here we are only talking about src folder setup.
- Other files are general fixed and depends more on the projects.

### Beginner

- A simple structure where all the files are in same folder itself.
- Easy to make and good for very small projects.

##### Folder Structure

- Components : All the componenets are inside this folder.
  - Direct component files
- Hooks : Easy to reference these in components
  - Direct hook files
- Tests : All the tests are present at one place only.
  - Components : tests for all the components
  - Hooks : tests for all the hooks
- Rest of the files are in src folder itself.
  - Util files
  - Context files

##### Points

- Difficult to manage when project starts to scale up.
- From Components section , it will be hard to know which are pages , small components , statefull components , presentational components.
- Other Methods formatDate , formatCurrency are all in src folder , instead they should be some Utility folder instead.
- All the tests are present in 1 folder only. Its hard to know which tests are associated with which file. Tests are no-where to the components.

### Intermediate

- A more cleaner src folder by separating the files.

##### Folder Structure

- Assets :
- Components :
- Context :
- Data :
- Hooks :
- Pages :
- Utils :
- Rest of the files are

##### Points

- Lot more folders than the beginner folder structure.
- Lot less files in direct src folder itself.
-
-

### Advanced

##### Folder Structure

- Assets :
- Components :
- Context :
- Data :
- Features :
- Hooks :
- Layouts :
- Lib :
- Pages :
- Services :
- Utils :

##### Points
