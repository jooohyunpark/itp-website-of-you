# itp-website-of-you

This is the repository for fall 2023 ITP class Website of You.

## Info

- Joohyun Park
- Class dates
  - TBD
- [Office hours](https://calendar.app.google/BYHgr6gMdJk75LfX7)
  - TBD


## Course Description
This course aims to provide students with skills to design and build a fully custom portfolio website from the ground up. The class will cover the full web development life cycle: prototyping idea, designing UX/UI, coding in Vue.js, and deploying the site through weekly lecture, hands-on exercise, and discussion. Students will apply the design/coding skills learned to develop a portfolio that can creatively showcase their works. 


## Course Ojbectives

At the completion of this course, the students will:

1. Practice designing UX/UI for a responsive website
2. Learn modular programming patterns in javascript using Vue.js
3. Prototype and develop custom portfolio site weekly


## Prerequisites

Please install these on your machine before the first class.

- [VS Code](https://code.visualstudio.com/) with the [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur) extension
- [Git](https://github.com/git-guides/install-git)
- [Node](https://nodejs.org/en/)
- [npm](https://www.npmjs.com/) - Comes with Node.js installation. You can also use [yarn](https://classic.yarnpkg.com/en/) if you want.
- Node version managers (optional) – Any node version manager such as [n](https://github.com/tj/n) (recommended) or [nvm](https://github.com/nvm-sh/nvm).


## Get Started

Clone this repo. It has weekly code examples in each folder.

```bash
$ git clone https://github.com/jooohyunpark/itp-wou-fall-2023.git
$ cd itp-wou-fall-2023
```

You can find different examples under `/pages` in weekly folder. To run these example, run following command from the root.

```bash
$ cd week1
$ yarn install # npm install
$ yarn dev  # npm run dev

# localhost:3000
# localhost:3000/example-1
# ...
```

## Packages
The class codebases mainly use below packages. Please make sure you're using the consistent versions. Especially, please use Vue2/Nuxt2. (Do NOT use Vue3/Nuxt3. They're unstable and not production-ready yet.)

```js
  "dependencies": {
    "bootstrap": "^5.2.1",
    "nuxt": "^2.15.8",
    "vue": "^2.6.14",
  },
  "devDependencies": {
    "sass": "^1.54.5",
    "sass-loader": "10"
  }
```


## Week 1 - Vue Intro (page)
Review portfolio website examples. Pull down nuxt boilerplate and go through Vue concept and code structure.
- Exercise: Create Home and About pages using Nuxt router

## Week 2 - Design exercise
Design exercise – break into groups and design basic portfolio site using various methods.

## Week 3 - Data / Directives
Understand vue fundamentals.
- Exercise: use v-for to loop through projects and render them. 

## Week 4 - Style / Responsive Layout
Implement responsive layout system using dvanced styling method. 
- Exercise: given desktop design comp, make layout responsive (design -> develop in a team)

## Week5 - Component
Learn modular programming pattern and practice creating reusable component.
- Exercise - create a button

## Week 6 - Advanced Script / Deploy
Explore how to install/import external libraries.

## Week 7 - Presentation
Students present their portfolio website.


## Tools

- [Vue.js](https://vuejs.org/) – Progressive javaScript framework for building UI
- [Nuxt.js](https://nuxtjs.org/) – Framework for creating Vue. js applications
- [Sass](https://sass-lang.com/) – CSS extension language for advanced styling
- [Bootstrap Vue](https://bootstrap-vue.org/) – CSS framework for responsive web development

## Additional Resources

- [Getting started with Vue](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Client-side_JavaScript_frameworks/Vue_getting_started)
- [Quick introduction to Nuxt](https://www.youtube.com/watch?v=7ITypVi-qRY)
- [Getting started with Nuxt](https://explorers.netlify.com/learn/get-started-with-nuxt)
- [Nuxt tutorials](https://nuxtjs.org/tutorials)
- [Nuxt.js Fundamentals](https://vueschool.io/courses/nuxtjs-fundamentals?friend=nuxt&utm_source=Nuxtjs.org&utm_medium=Link&utm_content=Courses&utm_campaign=nuxtjs-fundamentals)
- [Learn CSS](https://web.dev/learn/css/)
- [Material Design responsive layout grid](https://material.io/design/layout/responsive-layout-grid.html#breakpoints)
- [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [Bootstrap Grid Overlay chrome extension](https://chrome.google.com/webstore/detail/bootstrap-grid-overlay/mnlklmelflkheijccafopdohgclfefcg?hl=en-US)


## Evaluation

You are required to attend all class meetings and submit all weekly assignments and a final project.

Grading (pass/fail) will be based on a combination of factors:

- Attendance, participation in class discussion, and engagement in other students' projects (40%)
- Assignments (40%)
- Final Project (20%)

Please see ITP's statement on Pass/Fail which states that a "Pass" is equivalent to an "A" or a "B" while anything less would be considered a "Fail".

Attendance is mandatory. Please inform your teacher via email if you are going to miss a class. Two unexcused absences is cause for failing the class. (An unexcused lateness of 10 minutes or more is equivalent to 1/2 an absence.)

This class will be participatory, you are expected to participate in discussions and give feedback to other students both in class and participate with their projects. This (along with attendance) is 40% of your grade.

Class will culminate with final projects. You are expected to push your abilities to produce something that utilizes what you have learned in the class that is useful in some manner to yourself or the world. This will comprise 20% of your grade.

## Statement of Academic Integrity

Plagiarism is presenting someone else’s work as though it were your own. More specifically, plagiarism is to present as your own: A sequence of words quoted without quotation marks from another writer or a paraphrased passage from another writer’s work or facts, ideas or images composed by someone else.

## Statement of Principle

The core of the educational experience at the Tisch School of the Arts is the creation of original academic and artistic work by students for the critical review of faculty members.  It is therefore of the utmost importance that students at all times provide their instructors with an accurate sense of their current abilities and knowledge in order to receive appropriate constructive criticism and advice.  Any attempt to evade that essential, transparent transaction between instructor and student through plagiarism or cheating is educationally self-defeating and a grave violation of Tisch School of the Arts community standards.  For all the details on plagiarism, please refer to page 10 of the Tisch School of the Arts, Policies and Procedures Handbook, which can be found online at https://tisch.nyu.edu/student-affairs/important-resources/tisch-policies-and-handbooks

## Statement on Accessibility

Please feel free to make suggestions to your instructor about ways in which this class could become more accessible to you. Academic accommodations are available for students with documented disabilities. Please contact the Moses Center for Students with Disabilities at 212 998-4980 for further information.

## Statement on Counseling and Wellness

Your health and safety are a priority at NYU. If you experience any health or mental health issues during this course, we encourage you to utilize the support services of the 24/7 NYU Wellness Exchange 212-443-9999. Also, all students who may require an academic accommodation due to a qualified disability, physical or mental, please register with the Moses Center 212-998-4980. Please let your instructor know if you need help connecting to these resources.

## Statement on use of Electronic Devices

Laptops will be an essential part of the course and may be used in class during workshops and for taking notes in lecture. Laptops must be closed during class discussions and student presentations. Phone use in class is strictly prohibited unless directly related to a presentation of your own work or if you are asked to do so as part of the curriculum.
