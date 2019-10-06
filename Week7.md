# Week 7

## Weekly Goals

1. Build a front-end app in Javascript
2. Work competently in Javascript
3. Reason about asynchronous behaviour in Javascript

#### Plans to achieve:

1. Use Notes/News/Chitter challenges to improve understanding.
2. Focus on process rather than completion. Completion absolutely not important. Understand concepts and go to lots of process workshops
3. Read more on asynchronous behaviour

#### Evidence:

1. Built single-page [Notes App](https://github.com/DanGyi23/wk7-notesapp) and [News App](https://github.com/DanGyi23/news-summary-challenge) using front-end JS only, no JQuery. I actually compared the two methods in the final challenge, and whilst I see the merits of using front-end JS, I find it preferable to use JQuery in almost all instances, whilst understanding the limitations of using such a library, of course.
2. The above challenges demonstrate proficiency in Object-Oriented design, following good TDD process and maintaining a separation of concerns in JS, which I actually find much harder than in Ruby.
3. Calling various APIs and waiting for a response, wrapping responses in JSON objects, and using event listeners, for instance, have really improved my understanding of asynchronicity in JS.

## Daily Goals

#### Monday 30th September
- GOAL: Improve understanding of JS obj/prototype framework
- PLAN: Work through JS Objects and Prototypes Practical
- EVIDENCE: Completed these [here](https://hackmd.io/nb1VZarCTGicD6dMOo43Ww), and read up online.

#### Tuesday 1st October
- GOAL: Reinforce understanding of module pattern
- PLAN: Use module pattern in Notes App and do lots of console.logging!
- EVIDENCE: In the [Notes App](https://github.com/DanGyi23/wk7-notesapp) I started to create whole constructor functions within modules, exporting them so that functions/variables within the module & outside of the constructor were kept 'private'.

#### Wednesday 2nd October
- GOAL: Create own testing library to TDD front-end JS
- PLAN: Develop as simple-as-possible syntax to evaluate boolean and give visibility
- EVIDENCE: Created in [News App](https://github.com/DanGyi23/news-summary-challenge/blob/master/FrontEndJavaOption/tests/testing-library.js) and to a lesser extent, the [Notes App](https://github.com/DanGyi23/wk7-notesapp/tree/master/test)

#### Thursday 3rd October
- GOAL: Understand how hashchanges work, and don't refresh page
- PLAN: Work through NotesApp examples and write code that displays on-screen the hash change result.
- EVIDENCE: [Notes App Controller](https://github.com/DanGyi23/wk7-notesapp/blob/master/controller/note-controller.js) uses a hashchange event listener, takes the new id param from the clicked link URL, and displays a given note.

#### Friday 4th October
- GOAL: Refactor Notes App so that the Index/Controller are as lean as possible.
- PLAN: Move any dynamic tag creation etc. into the model layer, keep controller skinny and easy to read!
- EVIDENCE: [Skinny!](https://github.com/DanGyi23/wk7-notesapp/blob/master/controller/note-controller.js)

