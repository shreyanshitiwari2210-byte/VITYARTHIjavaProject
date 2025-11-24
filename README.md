# VITyarthi-Java-project
# Campus Course & Records Manager (CCRM)
This is a console-based Java SE project implementing a small Campus Course & Records Manager suitable for submission.

## What's included
- Java source in `src/edu/ccrm/...`
- Runnable main: `edu.ccrm.cli.Main`
- README, sample CSVs, and a basic export/backup flow.

## How to run
1. Install JDK 11+ and set JAVA_HOME.
2. Compile: `javac -d out $(find src -name "*.java")`
3. Run: `java -cp out edu.ccrm.cli.Main`

## Features demonstrated (mapping to syllabus)
- OOP: Encapsulation, Inheritance, Abstraction, Polymorphism (see domain classes). 
- Enums: `Grade`, `Semester`.
- Builder pattern: `Course.Builder`, `Student.Builder`.
- Singleton pattern: `AppConfig`.
- Custom exceptions: `DuplicateEnrollmentException`, `MaxCreditLimitExceededException`.
- NIO.2 file ops: `ImportExportService`, `BackupService`.
- Streams & lambdas used in services and export.
- Recursion in `BackupService.recursiveSize()`.
- CLI with switch (enhanced) in `Main`.

## Notes
- Add screenshots to `/screenshots` and update README.
- Academic integrity: ensure this is your own submission per instructions.
