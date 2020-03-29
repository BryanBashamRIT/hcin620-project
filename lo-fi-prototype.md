# CATA: Lo-Fi Prototypes

This page provides a set of lo-fidelity prototypes for the College Algebra Tutorial App (CATA) project.
These are organized by three general use cases.

## Notes about our Process

The team spent a few days analyzing both the Affinity diagram and our Project scope proposal to determine
the set of web site pages required to satisfy all of the requirements from these two sources.  When then created
a web site map (see next section) that documents these decisions.  Due to time constraints we decided to focus on
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

Here Mary can find his score on the latest quizzes graded.  She was excited to see she had won
a badge for this quiz and she is now on the leaderboard.

To view her history of grades she navigates to her private Profile page.

![alt text](lo-fi/cata_user_profile_sketch_v4.jpg "Student view their class-specific profile page.")

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
given page to navigate through the content.  Each page can contain any of the following content components:

| Content Type | Description | Sketch |
|:------------:|-------------|-------:|
| Paragraph | A general purpose paragraph of text. | ![alt text](lo-fi/CATA_ContentType_paragraph.jpg "Paragraph content type.") |
| Image | Any image. | ![alt text](lo-fi/CATA_ContentType_image.jpg "Image content type.") |
| Formula | A graphic for a mathematical formula. | ![alt text](lo-fi/CATA_ContentType_formula.jpg "Formula content type.") |
| Ask the Professor | A question and answer exchange. | ![alt text](lo-fi/CATA_ContentType_paragraph.jpg "'Ask the Professor' content type.") |

## UC3: _Student Takes a Quiz_

Quizzes can be taken either before a lesson and/or after a lesson.  The quiz subsystem is also used
for homework assignments.  Here is the proposal for a Quiz start page:

![alt text](lo-fi/CATA_QuizStartPage.jpg "The Start page for a quiz")

A quiz can contain any number of activity components, as shown here:

![alt text](lo-fi/CATA_QuizContentPage.jpg "A sample content page for a quiz")
