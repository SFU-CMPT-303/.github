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

The first part of the course will focus on learning the Rust language itself using the famous [Rust
Book](https://doc.rust-lang.org/book/title-page.html). The second part of the course will focus on
developing a minimal Rust kernel using Philipp Oppermann's excellent blog series on [Writing an OS
in Rust](https://os.phil-opp.com/). The last part of the course is TBD as there are a few options
and decisions will be made later depending on the progress of the first two parts.

Each week will generally have one quiz & two submissions. A quiz will ask questions regarding the
course materials from the prior week. A submission will have a deadline of a day before class.
Students will submit the work they do as they follow the Rust Book and Philipp Oppermann's blog
series. There will be other types of submissions, but this is TBD.

The following is a tentative schedule. It is likely that this will change as the semester
progresses.

| Date | Week | Lecture # | Lecture                                      |
|------|------|-----------|----------------------------------------------|
| 1/7  | 1    | 1         | Intro & [The Rust Book (TRB)](https://doc.rust-lang.org/book/title-page.html) Ch. 1 |
| 1/10 |      | 2         | TRB: Ch. 2-6                                 |
| 1/14 | 2    | 3         | TRB: Ch. 7-9 & Quiz                          |
| 1/17 |      | 4         | TRB: Ch. 10-14                               |
| 1/21 | 3    | 5         | TRB: Ch. 15-17 & Quiz                        |
| 1/24 |      | 6         | TRB: Ch. 18-20                               |
| 1/28 | 4    | 7         | [Blog OS (BOS)](https://os.phil-opp.com/): A Freestanding Rust Binary & Quiz |
| 1/31 |      | 8         | BOS: A Minimal Rust Kernel                   |
| 2/4  | 5    | 9         | BOS: VGA Text Mode & Quiz                    |
| 2/7  |      | 10        | BOS: Testing                                 |
| 2/11 | 6    | 11        | BOS: CPU Exceptions & Quiz                   |
| 2/14 |      | 12        | BOS: Double Faults                           |
| 2/18 |      |           | Reading break                                |
| 2/21 |      |           | Reading break                                |
| 2/25 | 7    | 13        | BOS: Hardware Interrupts & Quiz              |
| 2/28 |      | 14        | BOS: Introduction to Paging                  |
| 3/4  | 8    | 15        | BOS: Paging Implementation & Quiz            |
| 3/7  |      | 16        | BOS: Heap Allocation                         |
| 3/11 | 9    | 17        | BOS: Allocator Designs & Quiz                |
| 3/14 |      | 18        | BOS: Async/Await                             |
| 3/18 | 10   | 19        | TBD & Quiz                                   |
| 3/21 |      | 20        | TBD                                          |
| 3/25 | 11   | 21        | TBD & Quiz                                   |
| 3/28 |      | 22        | TBD                                          |
| 4/1  | 12   | 23        | TBD & Quiz                                   |
| 4/4  |      | 24        | TBD                                          |
| 4/8  | 13   | 25        | Quiz & Review                                |

## Grading

Quizzes and submissions are the main grading components. There is no midterm but final is a
possibility. This will be announced later.

* Quizzes: 12 * 3% = 36%
* Submissions: 23 * 2% = 46%
* TBD: 18%
