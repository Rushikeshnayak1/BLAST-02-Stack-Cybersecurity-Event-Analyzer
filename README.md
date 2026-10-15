# BLAST 02 — Stack and Cybersecurity Event Analyzer

**Student:** Rushikesh Pareshkumar Nayak  
**Professor:** Dr. Victor Govindaswamy  
**Language:** C++  
**Topic:** Stack (LIFO) and Cybersecurity

## About this project
This is a simple menu-driven C++ program that uses a stack to store sample security events such as failed logins, password changes, and unauthorized access attempts. The newest event is at the top of the stack. This is a classroom demonstration of **Last In, First Out (LIFO)**, not a real security monitoring or permanent audit logging tool.

## What the program does
- Add an event (Push)
- View the newest event (Peek)
- Remove the newest event (Pop)
- Display the event history from newest to oldest
- Check stack status and count stored events
- Clear the temporary history with confirmation
- Handle overflow, underflow, and invalid input

The stack uses a fixed-size array with a maximum of **five events**.

## Compile and run (Ubuntu)
From the repository root, run:

```bash
g++ -std=c++17 Source-Code/SecurityEventAnalyzer.cpp -o SecurityEventAnalyzer
./SecurityEventAnalyzer
```

## Files
- `Source-Code/` — C++ application
- `Research-Report/` — Stack and cybersecurity research report
- `UML-and-Flowchart/` — design document and flowchart
- `Presentation/` — PowerPoint presentation
- `Screenshots/` — Ubuntu test outputs
- `Video-and-LinkedIn-Links.md` — video and post links (add when available)

## Complexity
Push, Pop, Peek, empty/full checks, and event count are **O(1)**. Display is **O(n)**. The fixed-capacity array reserves five event slots; generalized stack storage for capacity n is **O(n)**.

## Limitations
Events are entered manually and are not saved after the program closes. This is not an intrusion detection system or a secure long-term log store.

## Acknowledgment
Thank you to **Dr. Victor Govindaswamy** for the BLAST 02 assignment and guidance.
