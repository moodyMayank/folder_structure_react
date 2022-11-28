# React Folder Structures

- All the files present in the directory are empty and are just used for sample purposes.
- Here we are only talking about src folder setup.
- Other files are general fixed and depends more on the projects.

### Beginner

- Components : all the componenets are inside this
  - direct component files
- hooks : Easy to reference these in components
  - direct hook files
- tests : All the tests are present at one place only
  - components : tests for all the components
  - hooks : tests for all the hooks
- Rest of the files are in src folder itself.

  - util files
  - Context files

- Difficult when project starts to scale up but ok for small projects.
- From Components section , it will be hard to know which are pages , small components , statefull components , presentational components.
- Other Methods formatDate , formatCurrency are all in src folder , instead they should be some Utility folder instead.
- All the tests are present in 1 folder only. Its hard to know which tests are associated with which file. Tests are no-where to the components.

### Intermediate

- Components
-

### Advanced
