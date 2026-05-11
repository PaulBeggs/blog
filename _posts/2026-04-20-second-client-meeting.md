---
layout: post
categories: misc
author:
- Paul Beggs
comments: true
---

## My Role in the Final Project

Following the second meeting, I came to the conclusion that we would have to majorly scale down the size of our project if we want to get it done by the deadline. This was a hard reality, but I knew that we were biting off more than we could chew, so it needed to be revised. My role as backend main and some frontend as well has not changed. I am still trying my best to be communicative with my teammates, and present at each meeting. In terms of the second meeting, my role was to take notes and try to guide the conversation. Jays helped a lot here, as he also had some prepared questions to ask. The next section is just a blob of the notes that I took.

### Notes from Second Meeting

The committee needs to be able to see the students information and the evaluator information.
Committee members need to track if the letter has been confirmed yet.
	- Need a way to assign committee members
Basically, anything on the committee side is extra. 
Right now for committee members, they pass the students around and mark who knows the student the best. After every student is marked, Nora does the rest.
Dr. Kett will assign committee members to a list of 10 students, for example.
So, for committee members, its usually self-selection for students.

Students have the right to view the letter of recommendation and the evaluation from the professor. The letter will have to be manually uploaded for each student by the committee after they finish writing it.

Committee members should be able see all students instead of only a select few. That is, instead of assigning each committee member only 10 students to see, they can view all of them, and write a letter for each.

Uploading letters:
3 processing systems: all medical schools.
Each website has a login for Nora, and each student has an ID and an optional letter ID, for each processing system. That ID and letter ID is then appended to the top of the recommendation letter for each processing system, so 3 letters per student. We can save the template recommendation letter as a .docx file, so she can download, edit, and save it for each student.

This makes me think we need another database for processed students. That is, each student should have a row for their ID, letter ID, and their completed letter of rec for easy export to those websites. 

Add a deletion after 3-4 years for recommendation letters, as 4 years+ they are not required to write a letter.

Students should be able to view past applications. Maybe, keep the form entries on autosave and auto populate the entry. That is, when the student logs back in, their responses are auto populated in the text boxes that they last filled out. Could slow down the website with constant querying, but will need to do testing.

Every evaluator has a Hendrix ID. No need to worry about anyone outside the college accessing the form.

Use students to write the evaluator's email with the evaluator's database. Nora says she can populate that initial database of evaluators. 

UI committee view:
pros: loves the stars system from the evaluator's form, and the display of evaluators in row form; comments from the students is also a bonus; the comments from evaluators is also important.

Landing page needs to have information about the program so when students or evaluators log in, they know what they are supposed to do.