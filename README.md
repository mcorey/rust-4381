**Note:** Website is:

![](https://media.tenor.com/MRCIli40TYoAAAAi/under-construction90s-90s.gif)

In Spring 2023 I taught an introductory course on the Rust programming language at Bennington 
College. This course was largely successful: the students got a firm grounding in Rust; a number of 
them created open-source crates; and they all learned a lot. Perhapy most interestingly, one of 
the things they learned the most about was _other_ programming languages they already used. Because 
Rust requires so many things to be so explicit it made the students (and me) realize what we were 
taking for granted in our day-to-day programming languages (usually Python and JS/TS). 

I break the rest of the page up up into a few sections:

0. Examples of student work
1. The material we covered in the class
2. Examples of student output
3. Things I'd do differently

## Examples of Student Work
A handful of people in the class produced open sourced projects and I want to highlight these at the top of the doc. 

- [Ons Ali](https://www.linkedin.com/in/ons-ali-8abb18109/) contributed a [resolver back to the Rust implementation of Chickadee](https://github.com/chapinb/chickadee-rs/issues/6).
- [Mohit KC](https://www.linkedin.com/in/mohit-kc/) expanded the average project we did for our midterm into a [math crate](https://crates.io/crates/math_rust).
- [Vriska Weaver](https://github.com/henlo-birb) wrote a series of procedural macros to [make Bevy much more ergonomic](https://crates.io/crates/bevy_ergo_plugin)
- Other final projects included
  - [A crypto alert](https://github.com/Tesfa-eth/cryto-alert)
  - [A CLI program to hid folders in windows](https://github.com/mhsizar/hide-folder)
  - And a number of students working on APIs with Rust

## Material We Covered In Class
### Information To The Students
I taught the class from **The Book**, but we specifically used the version adapted by the [Cognitive Engineering Lab](https://github.com/cognitive-engineering-lab) at Brown. This book came out shortly before the class started and I chose it because of the [interactive quizzes](https://rust-book.cs.brown.edu/experiment-intro.html#1-quizzes) and [re-framing of the ownership chapter](https://rust-book.cs.brown.edu/ch04-00-understanding-ownership.html). 

Along with **The Book** each class had additional readings and videos. Some of these were suggested by the students during the class, others came from browing Hacker News, various news feeds on my phone, and my own experience learning the langauge at the [Recurse Center](https://recurse.com/). prior classes had asked me for more reading, so I tried to stay on-top of optional readings.

### Structure of the Class
The class followed a similar pattern. First, I checked in on how they were doing and if they needed anything from me (more on this below). Second, I asked them to bring up questions/comments on the readings due that day. Following that I lectured for around 40 minutes (running notes below), after which we took a break. For the final half of the class the students worked on their assignments, which included Rustlings, writing a crate to calculate mathematical averages, and eventually their final projects. During this time students would ask for help from classmates when stuck, and we'd project the code up onto the board and write over it with marker. On any given class up to 1/3rd of the students would Zoom in because of illness, quarantine, or other excusable reasons to Zoom in. Once I started bringing my dog to class Zoom attendance plummeted—I shouldn't call that causal, but I will.

### Ordering and Pacing the Class
I largely followed the order of The Book in the class. We skipped some chapters after the fundamentals. I chose not to cover multi-threading and only skim Macros and a few other topics I thought were outside the scope of an 'intro' class. I also wanted to leave a full month for the students to work on their finals. I take a very practical and vocational approach to teaching so I cared a lot that the students had practice writing their own programs and work they could put on their GitHub. 

### Syllabus

Our full syllabus is available [here](https://www.dropbox.com/scl/fi/z3jksc3g0iiyfpg0drbxh/CS-4381_-Rust-Syllabus-5.pdf?rlkey=kjzbpzkw29mtmfazie3ko3i2x&dl=0)

### Running Lecture Notes and Q&A
I include lightly edited lecture notes [here](https://docs.google.com/document/d/e/2PACX-1vSerNNc0S-_lyQUMdxXP_f1rbrOA_Fyos7ZL0g6bfYApe54rXEd-Lj5qb3azvuS-8_ZKsgZpDOi1wLr/pub).

## Information From Students
Giving information to students is only part of the teaching process. Getting information back from them is crucial to see if they are understanding the material, if the lessons are taking root, and if anyone needs help. Getting students to implement the code is also important, but my pedagogical interest in getting material back from them are the former concerns. I hope some of them were also writing Rust code I never saw during the class.

I had three main way to get information from the students on their progress.

1. They turned in Rustlings one class in arrears of the lectrue
2. They all wrote a program to calculate averages, with a new addition made for each chapter of the book, leading to a convoluted but comprehensive tour of the language at mid-term.
3. They each did a final project near or at the edge of their individual abilities. We did critique and pair-programming of these during class over the last month.

## Lessons Learned
Teaching the course included a lot of lessons for me as a teacher, some of which may also be helpful to the Rust community. These can specifically be bucketed into

1. Places students struggled with the order and content of the class
2. Externalities that effected our class
3. Assignments I wish I had given

### Where The Book Didn't Work for Newer Programmers
- Ownership preceeding Vectors was very difficult for the students, since Vecs were used heavily in the book.
- 

### Externalities That Effected Class
- Ramadan
- COVID
- Student Suicides




