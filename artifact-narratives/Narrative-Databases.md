# Narrative For Category 3: Databases

The artifact I selected for this enhancement is a full-stack web application I developed in
April 2025 during CS-465: Full-Stack Development at Southern New Hampshire University. The
application, called "Travlr," is a travel booking platform designed for users to reserve vacations
at all-inclusive resorts. The original implementation utilized the MEAN stack architecture,
incorporating Angular for the frontend, MongoDB for data storage, Node.js as the runtime
environment, and Express.js for the backend framework. The initial version included core
functionality such as user authentication and administrative capabilities, allowing administrators
to add and modify trip offerings for public viewing. However, the application lacked a crucial
component: the ability for users to actually book trips, which fundamentally limited its practical
utility.
I selected this artifact for my ePortfolio because it perfectly demonstrates my ability to
enhance existing applications while adhering to software development best practices. The
enhancement showcases several key competencies that align with categories 1 (Software Design
and Engineering) and 3 (Databases). The most significant improvement involved migrating from
MongoDB to PostgreSQL to support the new booking functionality. This database migration
demonstrates my understanding of when to choose relational versus non-relational databases
based on application requirements. Since the booking feature requires establishing relationships
between users, trips, and reservations, a relational database structure provides better data
integrity and query capabilities. The key enhancements I made included designing and
implementing a new booking system with proper relational database structure, migrating from
MongoDB to PostgreSQL to support complex data relationships, adding role-based access
control by implementing an admin attribute in the User table, and creating proper foreign key
relationships between Users, Trips, and Reservations tables. This enhancement showcases my
ability to evaluate existing architectures, identify limitations, and implement appropriate
solutions while considering scalability and maintainability.
I have successfully met the course outcomes I planned to address in Module One with
this database enhancement. The migration from MongoDB to PostgreSQL demonstrates
proficiency in database design by successfully transitioning from a document-based to relational
database structure, understanding the appropriate use cases for different database technologies,
and implementing proper data modeling techniques for complex relationships. The database
restructuring shows my ability to analyze existing data requirements, plan and execute database
migrations while preserving data integrity, and design scalable database schemas that can
accommodate future feature development. Moving forward, I plan to expand the database
documentation and implement additional data validation measures and constraints. I also intend
to add database indexing strategies and query optimization techniques to further demonstrate
database performance management practices, which will strengthen this artifact's representation
of comprehensive database management skills.
The database enhancement process proved both challenging and rewarding, providing
significant learning opportunities focused specifically on database technologies and design
principles. Working with PostgreSQL for the first time required extensive research into relational
database concepts and SQL syntax. This experience reinforced the importance of understanding
different database paradigms and demonstrated my ability to quickly acquire new database
technologies through documentation and hands-on implementation. The most significant
challenge involved restructuring the existing data from MongoDB's document format to
PostgreSQL's relational structure while maintaining data integrity throughout the migration
process. This required careful analysis of the existing data patterns and thoughtful design of the
new table structures and relationships. Additionally, implementing proper foreign key constraints
and database-level validation rules requires a thorough understanding of PostgreSQL's constraint
system and transaction management. This database enhancement experience has strengthened
my expertise in database technologies and expanded my understanding of when to choose
specific database solutions based on application requirements. The process of migrating between
different database paradigms while preserving existing data will demonstrate practical database
administration skills that are highly valued in the industry.