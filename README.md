# ncc-1701-enterprise-code
NCC-1701: Working "code" repository for active development on the [USS Enterprise](https://www.startrek.com/database_article/enterprise).  

- Contains issues &amp; epics batch-transferred from the "upstream" [spec repository](https://github.com/dpcunningham/ncc-1701-enterprise-specs) according to the planned releases in the [timeline project board](https://github.com/dpcunningham/ncc-1701-enterprise-specs/projects).  

- Populates an associated [build project board](https://github.com/dpcunningham/ncc-1701-enterprise-code/projects) to manage assignments by "swim lanes" across the available crew.  

- Also contains bug issues discovered during testing and in production.


---

### Purpose

This fictional project is a benchmark for a _"leanest possible"_ workflow process tied as closely as possible to a developer's day-to-day toolset and workflow within the GitHub ecosystem, according to the following premises:

- Top-notch development talent is a very constrained resource.  
- Typical "top down" project management tools inflict a heavy toll on developer focus & energy due to forced mental context switching.  
- Organizations can avoid this unnecessary friction by adopting management practices which seek to leverage the existing toolsets already in use by experienced developers.  
- Flipping the typical project management process on its head provides welcome relief to busy developement teams, and can yield additional unanticipated benefits. 
- Finally, an understanding of the bigger "business landscape" around the BitHub ecosystem shows why using tools external to Github is (in the longer term) a non-viable approach

Details of this argument are provided in the associated [project wiki](https://github.com/dpcunningham/ncc-1701-enterprise-specs/wiki/A-Lean-Project-Management-Workflow-Based-Entirely-Within-GitHub) (bulletin board), which demonstrates another valuable tool (i.e. organized knowledge collection) for project management in this lean workflow based entirely within GitHub.

---

### Organization -- Four basic components:

1. A partnered "upstream" [**spec repository**](https://github.com/dpcunningham/ncc-1701-enterprise-specs): collects the various features (as issues and epics);
2. ...uses its own associated [**timeline project board**](https://github.com/dpcunningham/ncc-1701-enterprise-specs/projects): to batch the features into staged releases;
3. _This_ **code repository**: periodically accepts batches of features (as issues & epics) based on the timeline project board. Also contains bug issues discovered during testing and in production;
4. ...uses an associated [**build project board**](https://github.com/dpcunningham/ncc-1701-enterprise-code/projects): to assign specific issues to available crew. 
5. Each repository has an associated wiki (bulletin board) which can be used to organize a [project knowledge base](https://github.com/dpcunningham/ncc-1701-enterprise-code/wiki).


...created in this order (GitHub-specific workflow):
  1. Create the spec repository
  2. Within the spec repository, create:
     1. The timeline project
     2. Tie it back to the spec repository
  3. Create the code repository
  4. Within the code repository, create:
     1. The build project
     2. Tie it back to the code repository

--- 

### Resources

- The "md" suffix on this `README.md` file indicates it's a ["markdown"](https://en.wikipedia.org/wiki/Markdown) file. Here is a useful "beginner's guide" to the [specific markdown dialect](https://help.github.com/en/articles/basic-writing-and-formatting-syntax) (i.e. the "flavor" of markdown) used on GitHb.
- Here is a collection of useful GitHub guides for the various processes in this lean workflow:
  - [About Project Boards...](https://help.github.com/en/articles/about-project-boards)
  - [Creating a Project Board...](https://help.github.com/en/articles/creating-a-project-board)
  - [Adding notes to a project board...](https://help.github.com/en/articles/adding-notes-to-a-project-board#converting-a-note-to-an-issue)
  - [Converting a note to an issue...](https://help.github.com/en/articles/adding-notes-to-a-project-board#converting-a-note-to-an-issue)
  - [Transferring an issue to another repository...](https://help.github.com/en/articles/transferring-an-issue-to-another-repository)



