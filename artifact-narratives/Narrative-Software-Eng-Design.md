# Narrative For Category 1: Software Engineering & Design

The artifact I selected for this enhancement is a full-stack web application I developed in
April 2025 during CS-465: Full-Stack Development at Southern New Hampshire University.
This is the same artifact I used for my Databases category. The application, called "Travlr," is a
travel booking platform designed for users to reserve vacations at all-inclusive resorts. The
original implementation utilized the MEAN stack architecture, incorporating Angular for the
frontend, MongoDB for data storage, Node.js as the runtime environment, and Express.js for the
backend framework. The initial version included core functionality such as user authentication
and administrative capabilities, allowing administrators to add and modify trip offerings for
public viewing. However, the application lacked a crucial component: the ability for users to
actually book trips, which fundamentally limited its practical utility.
I selected this project because it perfectly represents the kind of real-world development
challenges I want to tackle professionally. When I first built the application, it was limited, it
only had basic admin features where administrators could add and edit trip listings, but regular
users couldn't actually book anything. That's a pretty common scenario in software development
where you build the foundation first and add user features later. This gave me a great opportunity
to show how I can take an existing codebase, identify what's missing, and build out the features
that actually make it useful for end users. What really showcases my skills here is how I handled
the complete transformation from a basic admin tool to a fully functional booking platform. I
implemented user authentication so people can create accounts and log in securely, built a
role-based system that treats admins and regular users differently, created the entire booking
workflow from start to finish, and designed a user dashboard where people can manage their
reservations.
When I started working on the enhancements, the application had some significant issues.
The code was disorganized, there was no way for users to actually sign in, no security measures,
and most importantly, no booking functionality at all. Users could look at trips but couldn't
reserve them, which defeats the whole purpose of a travel booking site. I approached the
improvements, starting with the foundation and building up. First, I reorganized the entire
codebase with a proper folder structure that follows industry standards. This makes the code
much easier to maintain and update later. The role-based authorization system was particularly
interesting to develop because I needed to ensure that regular users and administrators see
different interfaces and have access to different features. Admins can still add and edit trips like
before, but now regular users have their own dashboard and booking capabilities. The biggest
challenge was creating the complete booking workflow. This involved designing new database
structures to store reservation information, writing the logic to handle bookings with proper error
checking, and creating an intuitive interface that guides users through selecting and confirming
their trips. I also added a personal dashboard where users can see all their reservations.
I definitely achieved the course outcomes I planned for in Module One, and honestly
went beyond what I initially expected. The project demonstrates my ability to design computing
solutions that solve real problems using solid programming principles. Building the booking
system required me to think carefully about data flow, user experience, and system architecture,
all key aspects of software engineering. I also implemented proper authentication, authorization,
and data validation throughout the application. The most challenging part was probably
debugging authentication flows, particularly when implementing the role-based features that
needed to work seamlessly for both user types. Despite the challenges, transforming this
incomplete application into something that actually solves a real problem was incredibly
rewarding. It gave me practical experience with the kind of maintenance and enhancement work
that's common in professional development environments. Most importantly, it showed me how
thoughtful software engineering can take a basic prototype and turn it into something users
would actually want to use. My original outcome-coverage plans are still on track!