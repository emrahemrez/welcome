### TODO.md format

- TODO.md can have multiple columns.
- Each column has tasks that start with a checkbox sign `- [ ]` or just a hyphen `- `
- Completed column name must contain `✓` or `[x]`.
- There are "2 spaces" at the end of every task title to serve as line breaks on Github pages.
- Tags, mentions, estimates, date time, ticket id, etc. can be entered at the end of the task title.
- A task with 2 space indentation in the title is a sub-task or description. 

```
# Project Name
Project Description

### Column Name
- [ ] Task title ~3d #type @name yyyy-mm-dd  
  - [ ] Sub-task or description  

### Completed Column ✓
- [x] Completed task title  
```

- Checkboxes are used as described in [GFM - GitHub Flavored Markdown - Task Lists](https://guides.github.com/features/mastering-markdown/#GitHub-flavored-markdown) but they are optional.
- A task list without checkboxes look like this:

```
### Column Name
- Task title ~3d #type @name yyyy-mm-dd  
  - Sub-task or description  

### Completed Column ✓
- Completed task title  
```

# Example of TODO.md

This is an example of TODO.md

View the raw content of this file to understand the format.

### Todo

- [ ] Work on the website ~3d #feat @john 2020-03-20  
- [ ] Fix the homepage ~1d #bug @jane  
  - [ ] Sub-task or description  

### In Progress

- [ ] Work on Github Repo [JIRA-345]  

### Done ✓

- [x] Create my first TODO.md  
