# Assignments

These are the tasks with deliverables that have been assigned so far:

---

### Friday, 7/14
Deliverable in repo:
- `04_unplugged.md`

Details: Dynamic Duo work, To design a CS Unplugged activity. (30 min)
1. Come up with TNPG.
2. Select a CS concept that has been covered this summer in either Programming (including the pre-work) or Data Structures.
3. Design a CS unplugged activity for your selected topic.
4. If you want, you may look at some of thses links https://github.com/hunter-teacher-cert/sedc71900-summer-2023/tree/main/resources/unplug for inspiration, but your activity must not be a copy of something already done.
4. DELIVERABLE: 04_unplugged.md
   -  Create a plan for your unplugged activity, using the template found in resources/unplug/ of the class repository (linked above)


---

### Thursday, 7/13
Deliverable in repo:
- `03_annotate.md`

Details: Dynamic Duo work
1. Come up with TNPG (Team Name Portending Greatness). Share you TNPG in slack.
2. Read CODE for understanding. Check in with your group if there is any confusion. (Note this is A solution the the problem, not THE solution).
3. Annotate CODE with the provided TEACHER PROMPTS as comments.
4. DELIEVERABLE: `03_annotate.md`: Each member should have a copy of their team's work.
TEACHER PROMPTS:
```
PROVIDE :: code snippets or comments you definitely want to provide
STUDENT-PROMPT :: a specifically-worded question you want to ask, or a general solicitation for input, etc
MUST-ANSWER-Q :: a question that must be resolved, that a majority of your class must understand before moving on
BIG IDEA :: an introduction of a new topic, a connection to prior lesson or discussion for application here in code, etc.
BEEG REVEAL :: this is gonna blow yer minds...
DELIBERATE-ERROR :: specific code snippet or a general approach that is a bad fit for the situation, is flat-out wrong, or will lead to a compile- or run-time error, etc.
FIRSTDRAFT :: code that will work for now, but which you intend to replace later

REVISION vX :: better versions of firstdraft code...
```

CODE: This method should search through `data` and return the index of the first time `value` appears in `data`. If `value` is not in `data` return -1.
```
public int linearSearch(int value, ArrayList<Integer> data) {

  int foundIndex = -1;

  for (int i=0; i < data.size(); i++) {

    int element = data.get(i);

    if (e == value) {
      foundIndex = i;
      break;
      }
    }
  return foundIndex;
}
```

---

### Wednesday, 7/12
Deliverables in repo:
- `02_pair-framework.md`

Details
- GOAL: Create a framework for explaining pair programming to a class of students.
- Take inspiration from the Rally Cross framework (you can review it on the resources page https://github.com/hunter-teacher-cert/sedc71900-summer-2023/tree/main/resources), but find a new way to root the idea of pair programming in something more tangilble to your students.
- Questions to consider when working on your framework:
  1. How does it separate the two roles of PP?
  2. How approachable/interesting/exciting is it?
  3. Why do you think it will get students to buy into the process?
  4. What aspects of PP is the framework strongest in?
  5. What areas are this framework's weaknesses?
- DELIVERABLE: 02_pair-framework.md, In a markdown document:
  - Provide an overall description of your pair programming framework. Include pictures, links and other resources as necessary.
  - Give an explantion of why you chose this framework. Include your thoughts on the guiding questions listed above in this description.


---

### Tuesday, 7/11
Deliverables in repo:
- `README.md`
- `docs/` Folder used to publish a website via gh pages at: `https://hunter-teacher-cert.github.io/methods-work-YOUR USERNAME`

Details
- Add a file called README.md to your repository. In the file provide a heading with your name and this course code.
  - Using markdown, add to this file the following:
  - A list
  - An image
  - 2 hyperlinks, one with and one without anchor text.
  - A code block.
- For help with markdown, check out the nascent resources page: https://github.com/hunter-teacher-cert/sedc71900-summer-2023/tree/main/resources

- GOAL: make meaning of documentation via reading and crowdsourced Q&A
  - Have a “scratch” area open for taking notes (pen & paper, text editor, googdoc, etc)
  - Read GitHub’s guide to publishing a website from a repo, noting anything notable as you go. <https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site>
  - DELIVERABLE: questions/comments/concerns (Q/C/C) and/or hacks/protips posted as a threaded reply to this post (as you read or once you are finished)
- GOAL: publish (stub of) website to showcase your work this summer, via a folder named docs/ in your work repository
  - TASK: Grow your site to showcase any work from this summer you would like to make more accessible to your peers.
  - DELIVERABLE: A website accessible via: https://hunter-teacher-cert.github.io/methods-work-<YOUR USERNAME>
