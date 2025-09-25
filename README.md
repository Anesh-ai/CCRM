CCRM-Campus Course and Record Manager

Name: Anesh
Registration Number: 24BCE10373
Course: Programming in Java
Institution: Vellore Institute of Technology (VIT)

Table of Contents:
(1)Project Overview
(2)Evolution of Java
(3)Java Architecture
(4)Installation & Setup
(5)Project Structure
(6)Features
(7)How to Run
(8)Screenshots
(9)Acknowledgments

*Project Overview:
Campus Course & Records Manager (CCRM) is a comprehensive console-based Java SE application designed for educational institutions to efficiently manage:

-Student Management: Create, update, enroll/unenroll students in courses
-Course Management: Create, update, list, search, and assign instructors to courses
-Grades & Transcripts: Record marks, compute GPA, and generate transcripts
-File Operations: Import/export CSV data, backup and archive course data

This project demonstrates advanced Java concepts including OOP principles, design patterns, exception handling, NIO.2 file operations, Stream API, and modern Java features.

*Evolution:
-1991: The journey begins at Sun Microsystems with "Project Oak," led by James Gosling. The initial goal was to create a simple, platform-independent language for consumer electronics.
-1995: The language is renamed Java and re-focused on the emerging World Wide Web. The core philosophy of "Write Once, Run Anywhere" (WORA) is established, powered by the Java Virtual Machine (JVM).
-1998: The release of Java 2 (J2SE 1.2) marks a huge step. It introduces the Collections Framework and the Swing GUI toolkit. The platform is also split into Standard (J2SE), Enterprise (J2EE), and Micro (J2ME) editions.
-2004: Java 5.0 is a landmark release that adds fundamental features still critical today, including Generics, Annotations, and Enums.
-2014: Java 8 revolutionizes the language by introducing functional programming with Lambda Expressions and the Stream API, changing how developers write modern Java code.
-2017-Present: Java moves to a faster six-month release cycle starting with Java 9. This new model includes Long-Term Support (LTS) versions (like Java 11, 17, and 21), which are recommended for enterprise applications requiring stability.

*Java Architecture:

(1)JDK (Java Development Kit)
Complete development environment for Java applications
Includes: JRE + development tools (javac, javadoc, jar, debugger)
Used by: Developers to compile, debug, and package Java applications
Size: Largest component (~100-300 MB)

(2)JRE (Java Runtime Environment)
Runtime environment required to execute Java applications
Includes: JVM + core libraries + supporting files
Used by: End users to run Java applications
Size: Medium component (~50-100 MB)

(3)JVM (Java Virtual Machine)
Abstract machine that provides runtime environment for Java bytecode
Responsibility: Load, verify, and execute Java bytecode
Platform-specific: Different implementations for different operating systems
Key features: Garbage collection, memory management, security

Interaction Flow: Java Source Code (.java) → javac compiler → Bytecode (.class) → JVM → Machine Code

*Installation & Setup:

Windows Java Installation Steps=

(1)Download JDK
-Visit Oracle JDK download page or OpenJDK
-Download JDK 11 or higher for Windows x64

(2)Install JDK
-Run the installer with administrator privileges
-Choose installation directory (e.g., C:\Program Files\Java\jdk-11.0.x)
-Complete installation wizard

(3)Set Environment Variables JAVA_HOME = C:\Program Files\Java\jdk-11.0.x PATH = %PATH%;%JAVA_HOME%\bin

(4)Verify Installation java -version javac -version

Eclipse IDE Setup:
(1)Download Eclipse IDE for Java Developers
(2)Extract and launch Eclipse
(3)Create New Java Project:
-File → New → Java Project
-Project name: CCRM
-JRE version: Java 11+
-Module settings: Don't create module-info.java
(4)Configure Build Path:
-Right-click project → Properties → Java Build Path

*Features:

Core Functionality
✅ Student Management: CRUD operations with validation
✅ Course Management: Advanced search and filtering using Stream API
✅ Enrollment System: Business rule validation (credit limits, prerequisites)
✅ Grading System: Automated GPA calculation with enum-based grades
✅ Transcript Generation: Polymorphic reporting with formatted output
✅ File Operations: CSV import/export with NIO.2 Path API
✅ Backup System: Timestamped backups with recursive directory operations

Advanced Java Features Implemented
-Design Patterns: Singleton (AppConfig), Builder (Course creation)
-Exception Handling: Custom exceptions with comprehensive error handling
-Stream API: Filtering, mapping, and aggregation operations
-Lambda Expressions: Functional interfaces for comparisons and predicates
-Date/Time API: Modern temporal handling for all date operations
-NIO.2: Path-based file operations with atomic moves and copies
-Generics: Type-safe collections and service interfaces
-Nested Classes: Static nested classes and inner classes
-Ensure correct JRE is selected

*How to Run:

Prerequisites=
-Java JDK 11 or higher
-Eclipse IDE or any Java IDE
-Windows/Linux/macOS

Compilation & Execution=

-Clone the repository

git clone https://github.com/yourusername/-CCRM_Project

-cd CCRM
-Compile (if using command line) javac -cp src src/edu/ccrm/cli/CCRMApplication.java
-Run java -cp src edu.ccrm.cli.CCRMApplication
-Enable assertions (recommended) java -ea -cp src edu.ccrm.cli.CCRMApplication

Eclipse IDE=
-Import project: File → Import → Existing Projects into Workspace
-Right-click CCRMApplication.java → Run As → Java Application
-Follow console menu prompts

<img width="1178" height="472" alt="1" src="https://github.com/user-attachments/assets/6782852f-9d66-4a89-aab2-afa98e2fa345" />
<img width="1244" height="1118" alt="2" src="https://github.com/user-attachments/assets/d7b74d0f-c035-4460-9c0d-75a2bb9a8453" />
<img width="1564" height="1132" alt="3" src="https://github.com/user-attachments/assets/51ab6e58-855b-47a9-bcd4-3bb76283ac4c" />
<img width="1920" height="1020" alt="4" src="https://github.com/user-attachments/assets/3b5e28e9-d455-4998-a983-51df33e820e2" />

Acknowledgments:

(1)Java Documentation: Oracle official Java tutorials and documentation
(2)Design Patterns: Gang of Four Design Patterns reference
(3)Stream API: Java 8 functional programming concepts
(4)NIO.2: Modern Java I/O best practices


