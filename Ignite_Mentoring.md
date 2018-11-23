# Ignite Mentoring Allocation System

### Client:

__Club/~~Organisation~~:__ Ignite Mentoring\
__Name:__ Harry Sanderson\
__Position:__ President\
__Email:__ president@ignitementoring.org\
__Website:__ www.ignitementoring.org


### Background:

Ignite mentoring are a student volunteer group that run a number of mentoring classes every semester. Mentoring classes are semester-long, and involve students going to unprivileged schools in areas of low socio-economic status once a week, and running mentoring sessions for a class of students. A mentoring ‘class’ comprises a time and place (i.e. a day and time, at a specific school, held weekly, 10 times per semester). When a mentor is assigned to a class, they commit to performing all 10 sessions for that class. Currently, every semester, volunteer students will enter their preferences for the classes being run that semester, and the Ignite Mentoring committee will then allocate students to each classes. Each class has between 5-10 mentors, normally. There will also be effort made to balance the strength, the gender distribution, and the number of returning vs. new mentors running a class. This is currently all done manually, which is both time-consuming and unsustainable for larger scales.

### Description:

The project involved automating the above allocation process. The system designed will allocate students to classes, attempting to maximize the preferences entered by the students. On top of this, other factors will need to be considered:
* Balancing gender distribution (at least 2 males per class).
* Balancing strength of mentors (Ignite Mentoring can provide a metric/number for each student, representing their ‘strength’).
* Balancing the number of returning/new mentors in a class.

Additionally, every class also has 2 coordinators. The coordinators are assigned by Ignite Mentoring before any allocations take place. However, the system may need to account for the strength of the coordinators when performing allocations. For example, a stronger coordinator in a class may mean that the class can have more new mentors allocated to it. Also, each class will need a specific number of mentors in it. For example, some classes may require 5-7 mentors, while others may require 10-12. These figures (i.e. how many mentors per class) will be decided by Ignite Mentoring ahead of the allocation, but the system will need to take the numbers into consideration when performing the allocations. There will need to be support for re-allocation of individual mentors after the first round of allocations has been run. For example, if allocations are run, and a student volunteer’s available hours change, they may need to change into another class. The system may need to support re-allocating such students into new classes.

### Skills:

The project needs to be either a Desktop application (cross-platform compatible) or a Website (preferably one hosted on GitHub pages to keep costs to minimum). The choice is up to the members of the group. Apart from these, members would also need to know how to use source control effectively (either through the CLI or GitHub Desktop).

If the group decides to build a desktop application, languages such as Java, Python or C# is recommended.

If the group decides to create a web application, the group will need to use HTML, CSS, and JavaScript.

    The required skills with be taught to you over the course of the project if you do not have experience with the required languages.