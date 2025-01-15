# SFU CMPT 303 Operating Systems

This is an experimental course on operating systems. The basic goal is to learn operating systems by
studying the source code of an operating system and developing a small operating system from
scratch. Consequently, the focus is much more on student activities rather than lectures. Lectures
mainly serve as an enforcement mechanism to make sure that students finish the required activities.
Students are expected to take the ownership of their own learning.

Rust is the main language for the course. It is considered the frontrunner in replacing C/C++ as a
safer systems programming language. Thus, it makes sense to use it for a new operating systems
course.

## Course Structure and Schedule

The first part of the course focuses on learning the Rust language itself using the famous [Rust
Book](https://doc.rust-lang.org/book/title-page.html). The second part of the course focuses on
developing a minimal Rust kernel using Philipp Oppermann's excellent blog series on [Writing an OS
in Rust](https://os.phil-opp.com/). The last part of the course is TBD as there are a few options
and decisions will be made later depending on the progress of the first two parts.

Each week generally has one quiz & two submissions. A quiz tests the course material from the
previous week. A submission is due at midnight on the day of class. Students need to submit the work
they do as they follow the Rust Book and Philipp Oppermann's blog series. There will be other types
of submissions, but this is TBD.

Lectures review the material from each submission and study the source code of the Sixth Edition
UNIX Operating System. We use the historically significant [Lions' Commentary on UNIX 6th
Edition](http://www.lemis.com/grog/Documentation/Lions/). The goal is to deepen the understanding of
basic OS concepts and UNIX's foundational design principles.

The following is a preliminary schedule. It is likely that this will change as the semester
progresses.

| Date | Week | Lecture # | Lecture (Submission)                                    | Quiz      |
|------|------|-----------|---------------------------------------------------------|-----------|
| 1/7  | 1    | 1         | Intro & TRB Ch. 1                                       |           |
| 1/10 |      | 2         | TRB: Ch. 2-6 (S0)                                       |           |
| 1/14 | 2    | 3         | TRB: Ch. 7-9 (S1)                                       | Ch. 2-6   |
| 1/17 |      | 4         | TRB: Ch. 10-13 (S2)                                     |           |
| 1/21 | 3    | 5         | TRB: Ch. 14-16 (S3)                                     | Ch. 7-13  |
| 1/24 |      | 6         | TRB: Ch. 17-20 (S4)                                     |           |
| 1/28 | 4 | 7 | WOR: A Freestanding Rust Binary, A Minimal Rust Kernel, & VGA Text Mode | Ch. 14-20 |
| 1/31 |      | 8         | WOR: Testing & CPU Exceptions                           |           |
| 2/4  | 5    | 9         | WOR: Double Faults & Hardware Interrupts                | Yes       |
| 2/7  |      | 10        | WOR: Introduction to Paging                             |           |
| 2/11 | 6    | 11        | WOR: Paging Implementation                              | Yes       |
| 2/14 |      | 12        | WOR: Heap Allocation & Allocator Designs                |           |
| 2/18 |      |           | Reading break                                           |           |
| 2/21 |      |           | Reading break                                           |           |
| 2/25 | 7    | 13        | WOR: Async/Await                                        |           |
| 2/28 |      | 14        | TBD                                                     |           |
| 3/4  | 8    | 15        | TBD                                                     | Yes       |
| 3/7  |      | 16        | TBD                                                     |           |
| 3/11 | 9    | 17        | TBD                                                     | Yes       |
| 3/14 |      | 18        | TBD                                                     |           |
| 3/18 | 10   | 19        | TBD                                                     | Yes       |
| 3/21 |      | 20        | TBD                                                     |           |
| 3/25 | 11   | 21        | TBD                                                     | Yes       |
| 3/28 |      | 22        | TBD                                                     |           |
| 4/1  | 12   | 23        | TBD                                                     | Yes       |
| 4/4  |      | 24        | TBD                                                     |           |
| 4/8  | 13   | 25        | Review                                                  | Yes       |

## Grading

We use [GitHub Classroom](https://classroom.github.com/) for all submissions. This assumes that you
are familiar with [Git](https://github.com/git-guides) and [GitHub](https://github.com), and have a
[GitHub account](https://github.com/join) already.

Quizzes and submissions are the main graded components. There is no midterm. We plan to have a final
exam but this is also subject to change.

The following is a possible grade distribution (subject to change).

* Quizzes: 10 * 4% = 40%
* Submissions: 14 * 2% = 28%
* Final + TBD: 32%

## Time and Location

### Lectures

* Tu 10:30AM - 12:20PM (WMC3260)
* Fr 10:30AM - 11:20AM (WMC3260)

### Instructor

* Steve Ko <<steveyko@sfu.ca>>

### TAs

* Mohammad Omidvar <<m_omidvart@sfu.ca>>
* Shishir Gopinath <<shishir_gopinath@sfu.ca>>

### Office Hours

* Steve Ko: Fri 11:30PM - 12:30PM at TASC1 8019
* Shishir Gopinath: Mon 2:30PM - 3:30PM at ASB 9812
* Mohammad Omidvar: Wed 09:00AM - 10:00AM at ASB 9812

## Course Policies

### Pull Request Policy

* If you see that you have a pull request, please merge it. Pull requests contain updates to the
  assignments.
* In order to do it, go to your repo's webpage, check if your `Pull requests` tab shows a number. If
  it doesn't show a number, you don't need to do anything as there is no pull requests.
* If it does show a number, click the tab, click a pull request, scroll all the way down, and click
  `Merge pull request` (green button). If there are more than one pull request, please merge each
  and every one.

### Grading Policy

* All submissions should be done on GitHub Classroom and/or CourSys. Email submissions are not
  accepted.
* Submissions that do not follow the instructions down to the letter receive a zero.
* Late submissions are not accepted.
* All members of the same group receive the same grade (if there is a group).
* Students must attain an overall passing grade on the weighted average of exams
  (quizzes/midterms/final) in the course in order to obtain a clear pass (C- or better).

### Re-grading Policy

* A *private Piazza post* is the *only* way to request a re-grading. Make sure you add all
  instructors (i.e., post to `Instructors`). If you do not post to all instructors, we will not
  accept the request.
* We will not accept email requests either.
* Before requesting a re-grading for an assignment, make sure you run the checker/grader/test cases
  and see the output. Request a re-grading only when the grade is different from your expectation
  based on the output.
* In your re-grading request, clearly tell us the assignment name, your SFU ID, your GitHub
  username, and how your grade is different from what you expect from the checker/grader/test cases
  output.
* Lastly, you have one week to request a re-grading from the time your grade is released.

### Piazza Policy

* In this course, Piazza is mainly for you to help each other. If you know how to answer a question,
  please provide your answer and help out others.
* If no sensitive information is involved, always consider posting a question as a public question,
  not as a private question. It could be beneficial for other people in class.
* Depending on the volume of questions, the teaching staff may not be able to answer all questions
  in a timely fashion.
* The teaching staff monitors Piazza only during regular work days (Mon-Fri, excluding holidays) and
  regular work hours (9 am - 5 pm).
* For coding questions, it is most likely necessary to examine your code carefully and perhaps run
  it as well. This means that most of the times, it is much better to use the office hours than
  Piazza.
* For a followup discussion, always come back and mark it as resolved if the answer has been
  provided.

### Academic Integrity Policy

* All submitted work should be your own. For example, if you copy code from the Internet or from
  your peers, it is not your own work.
* You should not allow others to copy your code either. For example, your peer should not copy your
  code and you should not post your code on the Internet.
* Any violations of academic integrity receive an F for the course.
* We generally follow [the academic integrity policies from the
  university](http://www.sfu.ca/students/academicintegrity.html).
