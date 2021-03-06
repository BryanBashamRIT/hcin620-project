# CATA: Lo-Fi Prototypes

This page provides a set of lo-fidelity prototypes for the College Algebra Tutorial App (CATA) project.
These are organized by three general use cases.

## Table of Contents

* [Notes about our Process](#notes-about-our-process)
* [Web Site Map](#web-site-map)
* [Use Case 1: _Student Views Grades_](#uc1-student-views-grades)
* [Use Case 2: _Student Takes a Lesson_](#uc2-student-takes-a-lesson)
  * [Content Types](#content-types)
* [Use Case 3: _Student Takes a Quiz_](#uc3-student-takes-a-quiz)
  * [Activity Types](#activity-types)
* [Ancillary Pages](#ancillary-pages)

## Notes about our Process

The team spent a few days analyzing both the Affinity diagram and our Project scope proposal to determine
the set of web site pages required to satisfy all of the requirements from these two sources.  We then created
a web site map (see next section) that captures these decisions.  Due to time constraints we decided to focus on
the student experience and tabled all of the instructor pages.

Once we had a set of pages we put up a list on Slack and we negotiated assignments.  We worked independently, due
to covid-19 concerns, and used Slack to share initial sketches.  We then discussed these and members provided feedback
for improvement.  We did two or three iterations until we had a good working set.  We then crafted this web page to
document our designs, organized by use cases.


## Web Site Map

![alt text](lo-fi/CATA_Web_Site_State_Model.png "Web site state model; shows navigation paths between pages.")

## UC1: _Student Views Grades_

Mary McClemons wants to check on her quiz grades.  She logs into the Tutorial App (login page not shown) and the
system renders the App's Global Home page.

![alt text](lo-fi/CATA_GlobalHomePage_final.jpg "Student starts at the Global Home page.")

Mary selects the _College Algebra_ class and the system navigates to the Class Home page.

![alt text](lo-fi/CATA_ClassHomePage.jpg "Student navigates to the Class Home page.")

Here Mary can see her progress of various lessons.  She was excited to see she had won
a badge for the most recent quiz and she is now on the leaderboard.

To view her history of grades she navigates to her private Profile page.

![alt text](lo-fi/cata_user_profile_sketch_v5.jpg "Student view their class-specific profile page.")

This page provides additional details and a chart of her progress.

## UC2: _Student Takes a Lesson_

Andrew is ready to take the next lesson on polynomials, _Zeros of Polynomial Functions_, so he logs
into CATA and navigates to the Class Home page.  From the list of lessons on that page he selects the
_Zeros_ lesson, the system renders the Lesson page:

![alt text](lo-fi/CATA_LessonPage_final.jpg "The 'Zeros of Polynomial Functions' Lesson page.")

This page provides an introduction of the lesson, any related lessons (so he can review concepts he might
have forgotten), a list of associated quizzes and/or homework assignments, and a list of additional
resources on the web.

Andrew is eager to dive right in so he clicks on the *Start* button in the introduction section.  The system
navigates to the first of the content pages for this lesson as shown below.

![alt text](lo-fi/CATA_LessonContentPage_Intro_final.jpg "A sample Lesson Content page.")

The content delivery system supports a series of pages with a _Back_ and _Next_ at the bottom of the given
given page to navigate through the content.  

### Content Types

Each page can contain any of the following content components:

| Content Type | Description | Sketch |
|:------------:|-------------|-------:|
| Paragraph | A general purpose paragraph of text. | ![alt text](lo-fi/CATA_ContentType_paragraph.jpg "Paragraph content type.") |
| Image | Any image. | ![alt text](lo-fi/CATA_ContentType_image.jpg "Image content type.") |
| Formula | A graphic for a mathematical formula. | ![alt text](lo-fi/CATA_ContentType_formula.jpg "Formula content type.") |
| Ask the Professor | A question and answer exchange. | ![alt text](lo-fi/CATA_ContentType_AskTheProf.jpg "'Ask the Professor' content type.") |

Activities can also be embedded in the lesson content pages.  Activity types are described below.

## UC3: _Student Takes a Quiz_

Quizzes can be taken either before a lesson and/or after a lesson.  The quiz subsystem is also used
for homework assignments.  Here is the proposal for a Quiz start page:

![alt text](lo-fi/CATA_QuizStartPage.jpg "The Start page for a quiz")

A quiz can contain any number of activity components, as shown here:

![alt text](lo-fi/CATA_QuizContentPage.jpg "A sample content page for a quiz")

### Activity Types

A quiz is composed of one or more questions.  More generally, any activity has the potential to be
graded as part of an assessment.  Moreover, activities may also be embedded in lesson content pages
to make them more interactive.

Here is a simple set of activity types:

| Content Type | Description | Sketch |
|:------------:|-------------|-------:|
| Multi-Choice | A question with multiple choices but only one selection. | ![alt text](lo-fi/CATA_ActivityType_multichoice.jpg "Multi-Choice activity type.") |
| Multi-Selection | A question with multiple choices that allows multiple selections. | ![alt text](lo-fi/CATA_ActivityType_multiselect.jpg "Multi-Selection activity type.") |
| Short Essay | A question that is answered with a short essay. | ![alt text](lo-fi/CATA_ActivityType_shortessay.jpg "'Short Essay' activity type.") |
| Short Answer | A question that is answered with one or more short answers.  For example, a set of numeric answers to a polynomial factoring. | ![alt text](lo-fi/CATA_ActivityType_shortanswer.jpg "'Short Answer' activity type.") |
| Show Your Work | A mathematical problem that is solved by progressive alebraic transformations. | ![alt text](lo-fi/CATA_ActivityType_ShowYourWork.jpg "'Show Your Work' activity type.") |


## Ancillary Pages

We also created a sketch of a _Class List_ page that was not part of our original plan but I include it here for
completeness.

![alt text](lo-fi/cata_class_list_sketch_v3.jpg "The Class List page.")
