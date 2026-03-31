# Development Log

## Instructions
Document your development process as you work on the assignment. Add entries showing:
- What you worked on
- Problems you encountered
- How you solved them
- Time spent

**Requirements**: Minimum 5 entries showing progression over time.

---

## Example Entry Format:

### Entry 1 - [April 1, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**: 
- Created GitHub account with university email
- Forked the starter repository
- Changed student ID on line 92 to my actual ID (441234567)
- Compiled and ran the program successfully

**Challenges**: Had to install JDK first because javac wasn't recognized

**Solution**: Downloaded JDK 17 from Oracle website and set PATH variable

**Time spent**: 30 minutes

---

## Your Development Log:

### Entry 1 - [March 29, 2026, 2:00 AM]
**What I did**: 
Started the assignment, forked the repository, and set up the project.
**Details**: 
- Forked the repository to my GitHub account
- Opened the project and understood the basic structure
- Changed the student ID to my actual ID
- Ran the program to check the initial output
**Challenges**: 
Understanding how threads are used and how they connect with the queue.
**Solution**:
Reviewed lecture notes and simple examples.
**Time spent**: 1 hour

---

### Entry 2 - [March 30, 2026,8:04 PM]
**What I did**: 
Worked on Feature 1 (priority).
**Details**: 
- Added priority variable to Process class
- Updated constructor
- Displayed priority in output
**Challenges**: 
I had difficulty linking my code changes with GitHub. I wasn’t sure how to commit and
 push each feature correctly, and I didn’t understand how to organize my updates.
**Solution**: 
I watched a few YouTube tutorials and followed the steps until
I understood how to commit and push my changes properly.
**Time spent**: 
3 hours
---

### Entry 3 - [March 30, 2026, 10:51 PM]
**What I did**: 
Implemented Feature 2 (context switch counter).
**Details**: 
- Added a static counter
- Incremented it before each process execution
- Printed the total at the end
**Challenges**: 
I was confused about where exactly a context switch happens in the program.
 At first, I only added the counter in one place, but I realized that it should be counted in more than one situation.
**Solution**: 
I reviewed the loop carefully and tested the program multiple times until the counter worked correctly.
**Time spent**: 
  3 hours
---

### Entry 4 - [March 31, 2026 , 12:26 AM]
**What I did**: 
Worked on Feature 3 (waiting time tracking).
**Details**: 
- Added variables for waiting time and queue entry time
- Updated waiting time before execution
- Stored processes in a list for the final summary
**Challenges**: 
It was difficult to understand how to calculate the waiting time correctly.
I wasn’t sure when exactly to start and stop measuring the time for each process.
**Solution**: 
I focused on tracking when the process enters the queue and used the time difference before execution.
**Time spent**: 
1.5 hours
---

### Entry 5 - [March 31, 2026, 2:30 AM]
**What I did**: 
Tested the program and checked all features.
**Details**: 
- Ran the program multiple times
- Verified priority, context switches, and waiting time
- Fixed small output issues
**Challenges**: 
Some values didn’t look correct at first.
**Solution**: 
I rechecked the logic and corrected the calculations.
**Time spent**: 
1 hour
---

### Entry 6 - [March 31, 2026, 10:00 AM]
**What I did**: 
Finished documentation and answers.
**Details**: 
- Answered assignment questions
- Organized code and comments
- Did a final review
**Challenges**: 
Making sure answers match the program behavior.
**Solution**: 
I connected answers with the actual output.
**Time spent**: 
1 hour
---

## Summary

**Total time spent on assignment**: [Around 7–8 hours over 3 days]

**Most challenging part**: 
Calculating waiting time and understanding thread execution
**Most interesting learning**: 
Understanding how scheduling works step by step
**What I would do differently next time**: 
Start earlier and test each feature step by step
