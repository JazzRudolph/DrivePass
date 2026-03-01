# DrivePass

Project Summary

The DriverPass project involved designing a comprehensive management system for a driving school client. The goal was to create a streamlined platform that handles user registration, instructor scheduling, lesson bookings, and progress tracking. The client required a system that could differentiate among user roles, including Students, Instructors, and Admin staff, while maintaining a secure, efficient workflow for scheduling driving lessons.

Reflections

What I did particularly well: I feel that I excelled at the structural organization of the system. In my UML Class Diagram, I implemented an Abstract User class to support inheritance across roles such as Secretary, Owner, and IT Admin. This ensured that common attributes like names and contact information were centralized, which promotes cleaner code and easier database management.

Areas for Revision: If I were to revise one part of my work, I would add more granular multiplicity labels to the associations between classes. For example, explicitly defining the one-to-many relationship between a Customer and their Payments would provide even more clarity for the development team during the database implementation phase.

Interpreting User Needs: I interpreted the user’s needs by breaking down the functional requirements into specific entities and methods. For instance, knowing that the system needed to track student progress led me to include classes for PracticeTest and Lesson status. Considering the user's needs is vital because a system that is technically sound but fails to address the actual workflows of the students and instructors will ultimately be rejected or underutilized.

Design Approach and Future Strategies: My approach to software design is centered on egoless programming and thorough documentation. I believe that receiving feedback on designs is a tool for improvement rather than a personal critique. In the future, I plan to continue using UML modeling as a primary strategy because it serves as a visual "blueprint" that prevents misunderstandings between designers and developers. I also intend to use tiered maintenance models, such as categorizing requests into "Corrective" or "Perfective" tickets, to ensure a system remains healthy long after the initial design phase.
