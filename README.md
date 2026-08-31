# Probability and Statistics - MATH 360

## Cody Carroll

**Email**: cjcarroll [at] usfca [dot] edu

**Class Time**: MWF 10:30-11:35a in LM-244A

**Office Hours**: Mon 2:30-3:30p in the Hive (Harney Engineering area); Tue 2:30-3:30p on Zoom (link on Canvas)

**Text**:
Course lecture notes (*MATH 360 Lecture Notes*, distributed via Canvas) are the primary text and are self-contained. A formula and table packet is distributed with the notes; it is the same packet provided with every exam, so work from it all semester.

One optional supplement, keyed by chapter to the schedule below:

 **[W]** Probability and Statistics for Engineers and Scientists (Ninth Edition). Walpole, Myers, Myers & Ye.

## Schedule
*subject to change; any changes are announced in class and posted on Canvas
|Week | Dates | Topics | Reading [W] | Notable Events |
| :---:  | :---:  | :---:  | :---:  | :---: |
|Week 1| 8/26-8/28 | Course overview; sample spaces and events; operations on events and De Morgan's laws | Ch. 2 |  |
|Week 2| 8/31-9/4 | The axioms of probability; inclusion-exclusion; counting; conditional probability and the total probability theorem | Ch. 2 |  |
|Week 3| 9/9-9/11 | Bayes' theorem; independent events | Ch. 2 | **Build Day 1: Fri 9/11**; **HW1 due Fri 9/11**; no class Mon 9/7 (Labor Day) |
|Week 4| 9/14-9/18 | Random variables, p.m.f. and c.d.f.; continuous random variables; expectation, variance, and quantiles; the binomial, geometric, and Poisson distributions (the board's model: B(10, 0.5)) | Ch. 3-5 |  |
|Week 5| 9/21-9/25 | The normal distribution and standardization; the gamma and exponential distributions; chi-square and the F distribution | Ch. 6, 8 | **Build Day 2: Fri 9/25**; **HW2 due Fri 9/25** |
|Week 6| 9/28-10/2 | The uniform distribution; joint distributions: joint p.d.f.s and marginal distributions | Ch. 6, 3 | **Build Day 3: Fri 10/2** |
|Week 7| 10/5-10/9 | Conditional distributions and conditional expectation; correlation, independence, and the variance of a sum | Ch. 3-4 | **HW3 due Fri 10/9**; catch-up & exam review that day |
|Week 8| 10/12-10/16 | Random samples and sums; the law of large numbers and the CLT; simulation (the board is a physical CLT) | Ch. 8 | **Midterm Exam 1: Mon 10/12** |
|Week 9| 10/21-10/23 | Statistical models and the method of moments; maximum likelihood | Ch. 9 | **Build Day 4: Fri 10/23**; **HW4 due Fri 10/23**; no class Mon 10/19 (Fall Break) |
|Week 10| 10/26-10/30 | Bias, variance, and mean squared error; confidence intervals: z- and t-intervals and intervals for proportions | Ch. 9 | **Build Day 5: Fri 10/30** |
|Week 11| 11/2-11/6 | Hypothesis testing: the logic of a test, test statistics and p-values, power, one- and two-sided alternatives | Ch. 10 | **Build Day 6: Fri 11/6, board complete**; **HW5 due Fri 11/6** |
|Week 12| 11/9-11/13 | Two-sample t-tests (pooled, Welch, and paired); categorical data: the chi-square goodness-of-fit and independence tests, run on the class's own drop data | Ch. 10 | **Midterm Exam 2: Mon 11/9** |
|Week 13| 11/16-11/20 | Simple linear regression: least squares, inference for the slope, R², prediction, and residual diagnostics | Ch. 11 | **HW6 due Fri 11/20** |
|Week 14| 11/23-11/25 | Multiple regression and the general linear F test | Ch. 12 | No class Fri 11/27 (Thanksgiving) |
|Week 15| 11/30-12/4 | Logistic regression: the model, interpretation, inference, prediction, and classification | Ch. 12 | **HW7 due Fri 12/4** |
|Week 16| 12/7-12/9 | Course wrap-up & final project work | - | Last day of classes Wed 12/9 |
|Finals| Mon 12/14 | **Final project due** | - | First day of finals week |

## Build Days

Six class meetings this term are **build days**: we construct a Plinko board (a Galton board)
from scratch, 45.5" wide and 7'11" tall on a rolling base, with 2.5" pucks on a 4" peg pitch.
That board is then the source of the data for the final project. Build days
replace lecture on those dates.

| Day | Date | Work |
| :---: | :---: | :--- |
| 1 | Fri 9/11 | Design review, plywood sheet layout, frame cuts |
| 2 | Fri 9/25 | Frame assembly and rolling base; laying out the peg grid |
| 3 | Fri 10/2 | Drilling the 105-hole peg grid |
| 4 | Fri 10/23 | Installing pegs and bin dividers |
| 5 | Fri 10/30 | Front panel; drop comb and centre mark; calibration drops |
| 6 | Fri 11/6 | **Board complete**; full drop test and class data collection |

The board is a physical model of the material: 10 staggered peg rows are 10 independent
Bernoulli deflections, so a puck's landing bin is B(10, 0.5), and the bin counts are a physical
illustration of the CLT.

Build days are graded as participation. **Closed shoes are required on build days**; safety
glasses and hearing protection are provided. If you cannot take part in the physical build,
see me in the first two weeks; there is an equivalent role (measurement, data logging, and
running the drop protocol) on every build day.

## Course Learning Outcomes

By the end of this course, students will be able to:
- Convert descriptions of real-world engineering situations with uncertainty into probability models, and compute with conditional probability, Bayes' rule, and independence.
- Work with discrete and continuous random variables via mass/density functions and distribution functions, and summarize them with expectation, variance, and quantiles.
- Recognize when a named distribution (binomial, geometric, Poisson, exponential, normal, ...) models a physical situation, and compute probabilities from it, including with tables.
- Use joint distributions, covariance, and correlation to describe how two quantities vary together, and compute the mean and variance of sums and linear combinations.
- State and apply the Central Limit Theorem to sums and averages, and explain what it does and does not claim.
- Estimate model parameters by the method of moments and maximum likelihood, and assess estimators via bias, standard error, and mean squared error.
- Construct and correctly interpret confidence intervals, and carry out one- and two-sample hypothesis tests, including the errors, power, and p-value logic behind them.
- Analyze categorical data with chi-square goodness-of-fit and independence tests.
- Model a physical device as a probability experiment, collect data from it, and assess how well the idealized model fits, including where and why it fails.
- Fit, assess, and interpret simple and multiple linear regression models, and use logistic regression for binary responses.

## Course Content

The course is a single-semester path from probability to applied statistics for engineers. Topics include:
- Sample Spaces, Events, Axioms of Probability, and Counting
- Conditional Probability, Bayes' Rule, and Independence
- Random Variables: Distribution Functions, Densities, Expectation, Variance, and Quantiles
- Named Distributions (Binomial, Geometric, Poisson, Uniform, Exponential, Gamma, Normal, Chi-Squared, F)
- Joint Distributions, Covariance, and Correlation
- Sums of Random Variables, Sampling Distributions, and the Central Limit Theorem
- Point Estimation: Method of Moments, Maximum Likelihood, Bias and Standard Error
- Confidence Intervals and Hypothesis Tests (one- and two-sample)
- Chi-Square Tests: Goodness of Fit and Independence
- Simple and Multiple Linear Regression; Logistic Regression and Classification

## Course Tenets:

When in doubt, rely on the following:
- Put the work in & ask for help when stuck.
- Ask questions before spiraling.
- When confused, work with a partner & zoom into details.
- When you understand, teach others & zoom out to debrief.
- Use common sense whenever possible.

## Course Website
The class will be using Canvas & Github to distribute all resources. The full syllabus is posted on Canvas; the most important policies are summarized below.

## Grading

Your grade in this course will be computed according to the following weights:

**Homework: 20%**

- There will be seven problem sets, each covering about two weeks of material, submitted as file uploads on Canvas. Due dates will be announced in class and posted on Canvas.
- Students are encouraged to discuss and work together on assignments, but each student must turn in their own original work. **If there is evidence that the work turned in is not original work, which includes copying another student's homework or using any solutions found online, all credit for that homework set will be forfeited. Homework is not to be posted to online help sites. These sites will be checked frequently.**
- _No late homework will be accepted._

**Midterm Exams: 40% (20% each)**

- Two midterm exams, tentatively scheduled for **Monday 10/12** and **Monday 11/9**. Coverage of each midterm will be announced in class in advance of the exam.
- Midterm exams are closed-book. The course formula and table packet is provided with every exam; no other notes are permitted.
- No make-up or early exams will be given in order to ensure fairness and integrity of the class. Missing an exam without proper documentation of a personal illness or family emergency will result in a score of zero for that exam. Any documentation must be submitted to the instructor before the exam in question at the earliest possible date.

**Final Project: 20%**

- There is **no final exam**. In its place there is a **final project**, due **Monday, December 14**, the first day of finals week.
- **Data is collected by build team.** Each of the six teams runs **100 drops from the centre position** on the board we build this term (see **Build Days** below) and records its own bin counts. All six datasets are posted, so every student works from the same 600 drops.
- **The write-up is individual.** From the data: estimate the deflection probability *p* and give a confidence interval for it; test your own team's counts against B(10, 0.5) with a chi-square goodness-of-fit test (pooling the tail bins so every expected count is at least 5); repeat the test on the pooled 600; **repeat it once more against the normal distribution the CLT predicts**, N(5, 2.5) with a continuity correction, and say whether your data can tell the two models apart; test the six teams against one another for homogeneity; and argue from those results whether the board is biased, including where the idealized model breaks down (wall reflections, peg bias, release variation) and what each test did and did not have the power to detect.
- The full rubric will be posted on Canvas well before the end of the term.

**In-Class Participation: 20%**

- Every 4 weeks you will receive an assessment of your engagement and participation in class, scored on a 0-5 rubric. Full marks reflect consistent attendance, participating in class activities, offering questions and answers during lecture and at the board, attending office hours, and working with classmates outside of class.

**Regrade Policy**

You have **7 days** after a graded assignment is returned to contest a grade. After this time, the item may not be considered. If the 7-day period extends beyond the final project due date, the grade must be contested before that date.

**Course Grade Cutoffs**

| A+ | A | A- | B+ | B | B- | C+ | C | C- | F |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 97+ | 93+ | 90+ | 87+ | 83+ | 80+ | 77+ | 73+ | 70+ | <70 |

*Grading scheme and cutoffs are approximate. The instructor reserves the right to adjust the grading scheme and to raise or lower any grade cutoffs; final decisions will not be made until all assignments have been turned in and graded.*

## On Cheating

As a Jesuit institution committed to *cura personalis*, the care and education of the whole person, the University of San Francisco has an obligation to embody and foster the values of honesty and integrity. The university upholds standards of honesty and integrity from all members of the academic community, including faculty, students, and staff. All students are expected to know and to adhere to the university's honor code. You can find the full text of the code online [here](https://myusf.usfca.edu/academic-integrity/honor-code). Refer to the Homework section above for details regarding student collaboration. Plagiarism consists of copying *any* material from *any* source and submitting it as your own original work, regardless of where that material was sourced: the Internet, a book, textbook, or from deliverables previously submitted by other students. All students involved in any cheating or plagiarized deliverables, i.e., the cheater as well as the person(s) who willfully enabled or facilitated the act of cheating, will be reported through the university's academic integrity process. If you ever have questions about what constitutes plagiarism, cheating, or academic dishonesty in this course, I am happy to discuss these topics with you.

## On Disability

If you are a student with a disability or disabling condition, or if you think you may have a disability, please contact USF Student Disability Services (SDS) at 415.422.2613 within the first week of class, or immediately upon onset of the disability, to speak with a disability specialist. If you are determined eligible for reasonable accommodations, please meet with your disability specialist so they can arrange to have your accommodation letter sent to me, and we will discuss your needs for this course. For more information, please visit [this link](http://www.usfca.edu/sds/) or call 415.422.2613. **Accommodations are not retroactive.**

## On Behavioral Expectations

All students are expected to behave in accordance with the Student Conduct Code and University policies (see [here](https://myusf.usfca.edu/fogcutter/student-conduct)). Open discussion and disagreement is encouraged when done respectfully and in the spirit of academic discourse. There are also a variety of behaviors that, while not against a specific University policy, may create disruption in this course. Students whose behavior is disruptive or who fail to comply with the instructor may be dismissed from the class for the remainder of the class period and may need to meet with the instructor or Dean prior to returning to the next class period. If necessary, referrals may also be made to the Student Conduct process for violations of the Student Conduct Code.

## On Illnesses and Emergencies

If you fall ill or have an emergency (personal or otherwise) that significantly affects your ability to complete an assignment or take an exam, you must notify the instructor before the task is due. Do not simply skip an exam or an assignment and say you were sick after the fact. Always make arrangements with the instructor beforehand, rather than declaring illness or emergency later. **Accommodations are not retroactive.** Illness and emergency related situations must be disclosed to the instructor in writing. Illness-related issues must be accompanied by a doctor's note.

## On the Learning, Writing, and Speaking Centers

The Learning, Writing, and Speaking Centers (LWSC) provide free assistance to all USF students in pursuit of academic success. Peer tutors provide regular review and practice of course materials across a wide range of subjects, and trained consultants offer writing and speaking support. Services are available in person (Gleeson Library, Lower Level G03) and via Zoom. To schedule an appointment, use the [online scheduler](https://usfca-student.my.site.com/studenthub/USF_AppointmentScheduler). For more information about these services contact the LWSC at 415.422.6713, LWSC /at/ usfca /dot/ edu, or visit the [LWSC website](https://myusf.usfca.edu/lwsc).

## On Counseling and Psychological Services

Our diverse staff offers individual, couple, and group counseling to student members of our community. Services are confidential and free of charge. Call 415.422.6352 for an initial consultation appointment. Telephone consultation after hours (5:00 PM to 8:30 AM) is available by calling the same number and pressing 2, and the CAPS All Hours line at 855.531.0761 is available 24/7.

## On Confidentiality, Mandatory Reporting, and Sexual Assault

As an instructor, one of my responsibilities is to help create a safe learning environment on our campus. I also have a mandatory reporting responsibility related to my role as a faculty member. I am required to share information regarding sexual misconduct or information about a crime that may have occurred on USF's campus with the University. Here are other resources:
- To report any sexual misconduct, students may contact the Title IX Office (Lone Mountain 145, 415.422.4563) or file a report online; see the [Title IX reporting page](https://myusf.usfca.edu/title-ix/reporting) for all options.
- Students may speak to someone confidentially, or report a sexual assault confidentially, by contacting Counseling and Psychological Services at 415.422.6352.
- For an off-campus resource, contact San Francisco Women Against Rape at 415.647.7273 or [www.sfwar.org](https://www.sfwar.org).
