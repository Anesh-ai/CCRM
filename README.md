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
(7)Technical Implementation
(8)How to Run
(9)Screenshots
(10)Syllabus Mapping
(11)Sample Usage
(12)Acknowledgments

Project Overview:
Campus Course & Records Manager (CCRM) is a comprehensive console-based Java SE application designed for educational institutions to efficiently manage:

-Student Management: Create, update, enroll/unenroll students in courses
-Course Management: Create, update, list, search, and assign instructors to courses
-Grades & Transcripts: Record marks, compute GPA, and generate transcripts
-File Operations: Import/export CSV data, backup and archive course data

This project demonstrates advanced Java concepts including OOP principles, design patterns, exception handling, NIO.2 file operations, Stream API, and modern Java features.

Evolution of JAVA:
-1991: The journey begins at Sun Microsystems with "Project Oak," led by James Gosling. The initial goal was to create a simple, platform-independent language for consumer electronics.
-1995: The language is renamed Java and re-focused on the emerging World Wide Web. The core philosophy of "Write Once, Run Anywhere" (WORA) is established, powered by the Java Virtual Machine (JVM).
-1998: The release of Java 2 (J2SE 1.2) marks a huge step. It introduces the Collections Framework and the Swing GUI toolkit. The platform is also split into Standard (J2SE), Enterprise (J2EE), and Micro (J2ME) editions.
-2004: Java 5.0 is a landmark release that adds fundamental features still critical today, including Generics, Annotations, and Enums.
-2014: Java 8 revolutionizes the language by introducing functional programming with Lambda Expressions and the Stream API, changing how developers write modern Java code.
-2017-Present: Java moves to a faster six-month release cycle starting with Java 9. This new model includes Long-Term Support (LTS) versions (like Java 11, 17, and 21), which are recommended for enterprise applications requiring stability.

Java Architecture:
(1)JDK (Java Development Kit)
-Complete development environment for Java applications
-Includes: JRE + development tools (javac, javadoc, jar, debugger)
-Used by: Developers to compile, debug, and package Java applications
-Size: Largest component (~100-300 MB)

(2)JRE (Java Runtime Environment)
-Runtime environment required to execute Java applications
-Includes: JVM + core libraries + supporting files
-Used by: End users to run Java applications
-Size: Medium component (~50-100 MB)

(3)JVM (Java Virtual Machine)
-Abstract machine that provides runtime environment for Java bytecode
-Responsibility: Load, verify, and execute Java bytecode
-Platform-specific: Different implementations for different operating systems
-Key features: Garbage collection, memory management, security

Interaction Flow: Java Source Code (.java) → javac compiler → Bytecode (.class) → JVM → Machine Code

Installation & Setup:
-Windows Java Installation Steps
-Download JDK

-Visit Oracle JDK download page or OpenJDK
-Download JDK 11 or higher for Windows x64
-Install JDK

-Run the installer with administrator privileges
-Choose installation directory (e.g., C:\Program Files\Java\jdk-11.0.x)
-Complete installation wizard
-Set Environment Variables JAVA_HOME = C:\Program Files\Java\jdk-11.0.x PATH = %PATH%;%JAVA_HOME%\bin

Verify Installation java -version javac -version

Eclipse IDE Setup:
-Download Eclipse IDE for Java Developers
-Extract and launch Eclipse
-Create New Java Project:
-File → New → Java Project
-Project name: CCRM
-JRE version: Java 11+
-Module settings: Don't create module-info.java
-Configure Build Path:
-Right-click project → Properties → Java Build Path
-Ensure correct JRE is selected

Features
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

