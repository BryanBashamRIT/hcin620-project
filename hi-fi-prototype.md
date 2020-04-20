# CATA: Hi-Fi Prototypes

This page provides a describption of hi-fidelity prototype for the College Algebra Tutorial App (CATA) project.
These are organized by three general use cases.

* See the video here: [Video Demonstration of CATA](https://drive.google.com/a/g.rit.edu/file/d/1FRUUtqb_wY7iGtLzqbqb51zBZ3Hsf0z4/view?usp=sharing)
* Navigate to the Figma project here: [Figma iFrame](./cata_prototype/index.html)

## Video Script Introduction

This is the video demonstration of the high-fidelity prototype for the project called: College Algebra Tutorial Application;
or CATA for short.  The project team members are: Roshni, Shannon, Ed and Bryan.

The CATA project is loosely based upon the MyCourses learning management system but with a focus on creating content and
assessments that are designed to teach mathematics concepts and skills.  This video demonstrates three distinct use cases.

* _A student views his grades_
* _A student reads a lesson_
* and _A student takes a quiz_

## Use Case 1: Student Views Grades

In the first use case, Andrew wants to view his grades in the _College Algebra_ course.  He starts at the Global Home
page and selects the _College Algebra_ course card; the system navigates to the Class Home page.  We are using an ease-in
transition for all of our page navigation.

The Class Home page provides a Dashboard for this class tuned specifically to this student.  The student can view
their progress across
all lessons and navgiate to specific lessons that he is working on.  He can also see a calendar of up-coming tasks
such as quizzes and homework assignments.

To view his grades, Andrew clicks on the profile button to view a class-specific Student Profile page.  This page provides
a few details about Andrew on the left, his quiz scores using a line chart and the set of badges his has earned.  He notices
that he has recieved another badge so he navigates to the Leaderboard page to see his status relative to his fellow classmates.
He's excited that he moved up a notch.

## Use Case 2: Student Takes a Lesson

In the second use case, Andrew wants to get a head start on the next lesson.  So he navigates back to the _College Algebra_
Class Home page.  There he clicks on the _Zeros of Polynomial Functions_ lesson card.  The system navigates to that
page for that specific lesson.

On this page, Andrew can gets an introduction to the lesson, plus a list of learning objectives for this topic.
The page also provides a list of related lessons in case he wants to review any foundational concepts.
There is a list of external resources for additional exploration of this lesson.

The side navigation bar shows the complete set of lessons for this class as well as the related lessons that are starred
and the current lesson, which is circled.  This side-nav bar can be open or closed on any of the lesson content pages.

To start reading the lesson Andrew clicks on the "Start lesson" button in the Introduction section.  The system navigates
to the first content page.  This page discusses the _Rational Zeros Theorem_ that is used to determine a set of possible
zeros for any polynomial function with integer coefficients.  Any content page may contain any number of content elements
such as a heading, paragraphs or images.  We also added content types that are unique to mathematics classes such as
statements of theorems, examples of using the technique, as well as activities embedded directly on the page.  This makes the
content more interact and enjoyable.

The left region of the page is used to highlight certain important features.  The relevant learning objective is always
included at the top of the page.  There is also a panel called "Ask the Instructor", which provides a place for frequently
asked questions.

The two buttons at the bottom of the page provide navigation forward and backward.  Clicking on the _Next_ button tells
the system to navigate to the second learning objective for this lesson: _Using the quadratic formula_.  Please note that
I used a few snapshots from the textbook to simplify the development of these prototype pages; please pardon the inconsistency.

The next page provides the final topic of this lesson bringing together the first two topics into a unified procedure
for finding the zeros of integer-based polynomial equations.  On this page you will find an additional content type
called a _Procedure_.  Also notice that in place of the _Next_ button we see the _Start homework_ button.  This provides
an easy link to start the homework activity.  This is not part of our demonstration.

## Use Case 3: Student Takes a Quiz

In the final use case, Andrew needs to catch up on a previously assigned quiz from lesson one.  He navigates back to the
Class Home page.  There he clicks on the _Quiz 2_ task card.  The system navigates to the Start Quiz page.  Here the student
is given instructions about how to take the quiz and how much time is offered.  When he's ready Andrew clicks on the _Start
Quiz_ button and the system navigates to the quiz content page.  This page provides rich support for taking assessments for
algebra-based problems.

For example, you can see in the first question that the system provides graphs as well as plain text.  And in the second
question the student can use multiple text lines to show their work in great detail.  This ability to "show your work" was
a critical requirement from our instructors during the contextual inquiry interviews.

At the end of the quiz Andrew clicks the _Submit Quiz_ button, which submits the quiz answers and returns him to the Class
Home page.

## Wrap-up

This concludes our video demonstration of the CATA project.  I hope you enjoyed it.
