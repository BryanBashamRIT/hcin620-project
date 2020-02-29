# CATA: Project Scope

This page details the scope of the College Algebra Tutorial App (CATA) project.

## Concept
Build a working prototype of a mathematics e-learning platform/tutorial app that specifically covers college (pre-calculus) mathematics disciplines including algebra.

## Stakeholders
The primary stakeholders are the college instructors and their students.  Secondary stakeholders include the HCIN-620 class and the team itself.

## Learning Theory Model

This project is one part user experience design and one part learner experience design.
These are a few of the learning theory techniques we plan to employ:

* _self-directed learning_: The student uses the CATA platform to explore areas of college algebra
at their own pace.
* _story telling_: Where appropriate we will use story telling to deliver the learning content.
For example, word problems for the topic of **Exponential Growth and Decay** can be illustrated by
telling a story about the origins of the word problem.
* _engage an emotional response_: Learning is enhanced when the learner has an emotional response
to the content.  Story telling can be an effective tool of eliciting an emotional response in the learner.
* _multi-modal representation_: This technique applies multiple forms of representation to the topic
being learned.  Modes such as: textual, graphical, procedural, story-telling and so on.
* _content chunking_: This technique breaks complex topics into smaller chunks with activities that
break up the content and let each sub-topic time to "settle in" before tackling the next sub-topic.
* _cognitive scaffolding_: Each lesson will contain an explanation of how this topic relates to other
topics in the course.  For example, **Rational Expressions** relate to **Polynomials**, which also
relates to **Exponents** and **Variable**, and so on.

## Goals

* The algebra tutorial app will be delivered as a web application accessible both from desktop and mobile device, such as a smartphone or table
* To construct a working prototype of an established feature set, including a small set of connected learning modules and a separate (timed) quiz module
* Implementation of a reward system to reinforce learning in a positive way (gamification)
* _Stretch goal_: Act as a replacement for the textbook
* _Stretch goal_: instructor-reward badges

## Plan

* A module may include pre-class learning content
* A module will not replace the instructor’s lecture
* A module will include options for both in-class and post-class (homework) activities
* A module will include a practice exam that is timed
* The app will include an overview of the course’s module
* The app will include a cross-module navigation system
* The app will include an instructor view page that shows:
  * Individual student progress for each module
  * Individual student’s scores on activities and practice exams
  * A statistical summary of the class’ success (average distribution) with a module
* “Top Student” scoreboard (top three) per module (or by the practice exam?)
* “Top Student” scoreboard (top three) for the whole class
* A “badge” for least number of hints needed
* A “badge” for one or more “top score” achievers?

## Concerns

* “Scope creep” with too many requested features and not enough time for production
* Not enough funding provided for app production
* Compromise on feature sets to stay within budget
* Finding/incentivising experienced talent (software engineers/designers/product team)
* There won’t be an opportunity to interview NYS regulators or an appropriate accrediting body so we are eliminating them from the stakeholder list.

## Ideas

* E-learning platform prototype focused on college algebra
* Instructor supplies a list of students for a specific class (aka: course section)
* App must include email and password authentication
* App should promote gamified reward system
* App should include faculty reporting on student’s quiz scores
* App should outline student curriculum in chronological order
* Students are allowed to work ahead of the regular class schedule but instructor controls when module are unlocked
* App should reveal correct answers so students can address mistakes
* App could possibly offer limited hints for questions (and rewards for not using them)
* In-class activities provide immediate feedback
* Homework activities provide feedback after a due-date
* App should provide a class-level “profile” page:
  * Each student is listed with badges
* App should provide a student’s profile page:
  * Visible only to that student and instructor
  * Page includes complete module scores and badges
  * List of completed and up-coming modules
* App should keep track of quiz deadlines set by faculty/administrator
* Should students be permitted to retake quizzes (with randomized question sets)?
* For in-class activities there should be different tiers of question sets (difficulty level) that the app determines based upon the success of previous activities with the same module/lesson
* App could include mock quizzes (where users can reference learning modules) that do not count against GPA
* Learning modules should be locked once quizzes are started
* Unit and practice exams should be timed with progressive and final warnings issued

## Out of Scope

* No cross-user communication, neither email, SMS nor in-app chat.
* No integration with any other Leaning Management System such as MyCourses.
* We will limit the scope of our prototype to two or three lessons because a complete course would require dozens of lessons (aka modules) but that would not be feasible.
* Any administration screens beyond explicitly defined in the **Goals** and **Ideas** sections.

## Stakeholder Communication

Stakeholders should be continuously informed of development progress. They should intervene if they feel the app’s progression does not with their goals. Stakeholders should be notified when certain features are running behind schedule. Developers should expect extra scope added due to additional/revised designs and features. A prompt feedback system should be implemented so the product owner can be the single point of contact between the stakeholders, the development team and the designers. It should be stressed to the team that the stakeholders represent the clients, and that design changes should be expected and accommodated as development progresses. All client communications should be funneled through the product owner.

## Stakeholder Notification

Stakeholders should be notified regularly via email with a scheduled team demo or web link to the prototype. Feedback should be early and often to prevent the implementation of unwanted features. The design should be communicated as realistically as possible with an incremental progression of addressed stakeholder feedback. Larger features should be broken down into smaller feature sets so that the stakeholders can make important decisions and inform design and development of any changes as soon as possible.
