# Numerical Computation

## Syllabus

CU Boulder: CSCI 3656 (Spring 2019)

Meeting Time: TR 12:30-1:45pm in FLMG 157

#### Instructor

[Jed Brown](https://jedbrown.org), [<tt>jed.brown@colorado.edu</tt>](mailto:jed.brown@colorado.edu), ECOT 824

Office Hours: Mon/Fri 10-11am, Thu 2-3:15pm, or by appointment.

### Overview

Covers development, computer implementation, and analysis of numerical methods for applied mathematical problems. Topics include floating point arithmetic, numerical solution of linear systems of equations, root finding, numerical interpolation, differentiation, and integration.

### Target audience

Core option for Computer Science BS and BA students.

Required prerequisites (all minimum grade C-):

* Introductory programming: CSCI 1300 or CSCI 1310 or CSCI 1320 or ECEN 1310
* Calculus 2: APPM 1360 or MATH 2300
* Linear Algebra: CSCI 2820 or MATH 2130 or APPM 2360 or APPM 3310

### Outcomes

Upon completion of this course, students will possess the following traits as applied to the topics in scope (see below).

1. *Formulation*: proficiency at formulating real-world problems as instances of well-posed numerical problems
2. *Choice*: an ability to choose appropriate numerical methods for solving mathematical models arising in science and engineering
3. *Critique*: an understanding of the merits and limitations of those numerical methods
4. *Tradeoffs*: an understanding of accuracy vs cost tradeoffs in the key algorithms of continuous mathematics
5. *Creation*: an ability to write effective numerical programs, taking into account stability, accuracy, and cost
6. *Software*: familiarity with numerical libraries that provide production-grade implementations of state of the art numerical methods

### Scope

Students will be introduced to the formulation and solution of numerical problems of the following types

1. Rootfinding (solving nonlinear algebraic equations)
2. Numerical linear algebra
3. Interpolation
4. Regression
5. Numerical optimization
6. Numerical differentiation
7. Numerical integration
8. Numerical solution of ordinary differential equations

and will be familiar with these cross-cutting themes which are essential to robustness and to diagnosing failures:

* Stability of numerical algorithms
* Conditioning of physical problems and mathematical formulations

### Evaluation

* 20% class participation and in-class activities -- please bring a computer so you can complete activities using nbgrader or Moodle.  These will be short and you'll be able to finish during class.

* 30% midterms -- two in-class midterms

* 30% homeworks -- nbgrader homework assignments for which you will have at least a week

* 20% final project -- work in groups, lightning presentations and peer evaluation

#### Exams

The two midterm exams will be cumulative and use an open neighbor/open internet format with randomized seating.

* Midterm 1: February 28 (changed from Feb 21)
* Midterm 2: April 11

#### Git and GitHub

Homework assignments and in-class activities will be submitted via Git.  This class will use GitHub classroom.

To follow along with lectures, you can fork the [class repository](https://github.com/cucs-numcomp/numcomp-class).  Homeworks will be completed by cloning GitHub repositories, completing coding and analysis activities using Jupyter, and pushing completed assignments back to GitHub.

You will complete assignments using [Jupyter](https://jupyter.org/), which is available on the [Coding CSEL Hub](https://coding.csel.io/) and can be installed locally on most operating systems.

It is notoriously difficult to predict the time required to produce quality code, so please start early to give yourself plenty of time.  You are welcome to work together on all assignments, but must give credit to collaborators (at the top of each notebook).  You should ensure that each assignment you submit contains some significant intellectual contribution of your own.

### Programming languages and environment

I will use Python with [Jupyter notebooks](https://jupyter.org/) in class and for homeworks.  This environment is convenient to work with, general purpose, and has extensive library support.  Native Python code is not high performance, however, so the scientific Python stack depends on numerical libraries written in other languages, such as C, C++, or Fortran.  MATLAB is also popular for numerical computing, though it is a proprietary environment and lacks general-purpose libraries.  Octave is a free MATLAB clone and Julia is a modern language that preserves much of the syntactic convenience.

Most high-performance computing (HPC), data science, and cloud resources use a Linux operating system.  You can use any environment for your local development environment, but I recommend the [Coding CSEL Hub](https://coding.csel.io/) because it includes a complete software environment and you can access it from any machine.

### Moodle

Moodle will be used to maintain grades.  Please enroll yourself at https://moodle.cs.colorado.edu.

### Resources

This course will follow a collection of Jupyter notebooks.  The notebooks are intended to be self-contained.  There is no required textbook, but the following resources may be helpful.

* [Greenbaum and Chartier (2012), **Numerical Methods Design, Analysis, and Computer Implementation of Algorithms**](https://press.princeton.edu/titles/9763.html) -- an excellent, comprehensive book.
* [Sauer (2012), **Numerical Analysis**](https://www.pearson.com/us/higher-education/program/Sauer-Numerical-Analysis-2nd-Edition/PGM223463.html) -- used for this course in other semesters.
* [Boyd and Vandenberghe (2018), **Introduction to Applied Linear Algebra**](https://web.stanford.edu/~boyd/vmls/) -- practical introduction to linear algebra for computer scientists; free PDF
* [Trefethen and Bau (1997), **Numerical Linear Algebra**](http://bookstore.siam.org/ot50/) -- fantastic, but limited to numerical linear algebra and covers more advanced topics.
* [Eijkhout (2017), **Introduction to High-Performance Scientific Computing**](http://pages.tacc.utexas.edu/~eijkhout/istc/istc.html) -- includes introductory numerical linear algebra from a performance standpoint; free PDF.
* [Scopatz and Huff (2015), **Effective Computation in Physics**](http://physics.codes/) -- Python language, data science workflow, and computation.

A [SIAM Membership](http://www.siam.org/students/memberships.php) is free for CU students and provides a 30% discount on SIAM books.

### Disability Accommodations

If you qualify for accommodations because of a disability, please submit to your professor a letter from Disability Services in a timely manner (for exam accommodations provide your letter at least one week prior to the exam) so that your needs can be addressed. Disability Services determines accommodations based on documented disabilities. Contact Disability Services at 303-492-8671 or by e-mail at dsinfo@colorado.edu. If you have a temporary medical condition or injury, see the Temporary Injuries guidelines under the Quick Links at the Disability Services website and discuss your needs with your professor.

### Religious Observances

[Campus policy regarding religious observances](http://www.colorado.edu/policies/fac_relig.html) requires that faculty make every effort to deal reasonably and fairly with all students who, because of religious obligations, have conflicts with scheduled exams, assignments or required assignments/attendance. If this applies to you, please speak with me directly as soon as possible at the beginning of the term. See the [campus policy regarding religious observances](http://www.colorado.edu/policies/observance-religious-holidays-and-absences-classes-andor-exams) for full details.

### Classroom Behavior

Students and faculty each have responsibility for maintaining an appropriate learning environment. Those who fail to adhere to such behavioral standards may be subject to discipline. Professional courtesy and sensitivity are especially important with respect to individuals and topics dealing with differences of race, color, culture, religion, creed, politics, veteran's status, sexual orientation, gender, gender identity and gender expression, age, disability,and nationalities. Class rosters are provided to the instructor with the student's legal name. I will gladly honor your request to address you by an alternate name or gender pronoun. Please advise me of this preference early in the semester so that I may make appropriate changes to my records. For more information, see the policies on [classroom behavior](http://www.colorado.edu/policies/student-classroom-and-course-related-behavior) and the [student code](http://www.colorado.edu/osc/sites/default/files/attached-files/studentconductcode_16-17-a.pdf).

### Discrimination and Harassment

The University of Colorado Boulder (CU Boulder) is committed to maintaining a positive learning, working, and living environment. CU Boulder will not tolerate acts of sexual misconduct, discrimination, harassment or related retaliation against or by any employee or student. CU's Sexual Misconduct Policy prohibits sexual assault, sexual exploitation, sexual harassment,intimate partner abuse (dating or domestic violence), stalking or related retaliation. CU Boulder's Discrimination and Harassment Policy prohibits discrimination, harassment or related retaliation based on race, color,national origin, sex, pregnancy, age, disability, creed, religion, sexual orientation, gender identity, gender expression, veteran status, political affiliation or political philosophy. Individuals who believe they have been subject to misconduct under either policy should contact the Office of Institutional Equity and Compliance (OIEC) at 303-492-2127. Information about the OIEC, the above referenced policies, and the campus resources available to assist individuals regarding sexual misconduct, discrimination, harassment or related retaliation can be found at the [OIEC website](http://www.colorado.edu/institutionalequity/).

### Honor Code

All students enrolled in a University of Colorado Boulder course are responsible for knowing and adhering to the [academic integrity policy](http://www.colorado.edu/policies/academic-integrity-policy) of the institution. Violations of the policy may include: plagiarism, cheating,fabrication, lying, bribery, threat, unauthorized access, clicker fraud,resubmission, and aiding academic dishonesty.  All incidents of academic misconduct will be reported to the Honor Code Council (honor@colorado.edu; 303-735-2273). Students who are found responsible for violating the academic integrity policy will be subject to nonacademic sanctions from the Honor Code Council as well as academic sanctions from the faculty member. Additional information regarding the academic integrity policy can be found at http://honorcode.colorado.edu.
