# [Project Name] — Manual Test Cases

## Overview
A structured collection of manual test cases for the [application name]
web application. This repository documents the test design and coverage
approach used during manual testing, including functional, regression,
and exploratory test scenarios.

## Purpose
This repository serves as:
- A record of test coverage and test design decisions
- A reference for future automation candidates
- Documentation of acceptance criteria validation approach

## Test Coverage Areas
| Module | Test Scenarios Covered |
|--------|----------------------|
| Login | Valid login, invalid credentials, empty fields, 
|       | password visibility, session timeout |
| [Module 2] | [what's covered] |
| [Module 3] | [what's covered] |

## Test Case Structure
Each test case follows this format:

| Field | Description |
|-------|-------------|
| Test Case ID | Unique identifier (e.g. TC_LOGIN_001) |
| Test Title | Short description of what is being tested |
| Preconditions | Setup required before executing the test |
| Test Steps | Step-by-step actions to perform |
| Expected Result | What should happen if the app works correctly |
| Actual Result | What actually happened during execution |
| Status | Pass / Fail / Blocked |
| Priority | High / Medium / Low |

## Test Design Approach
- **Equivalence Partitioning** — grouping inputs into valid 
  and invalid partitions to reduce test cases while 
  maintaining coverage
- **Boundary Value Analysis** — testing at the edges of 
  input ranges (e.g. min/max character limits)
- **Negative Testing** — validating system behaviour with 
  invalid, unexpected, or missing inputs
- **Exploratory Testing** — unscripted testing to discover 
  defects outside of documented scenarios

## Files in This Repository
| File | Description |
|------|-------------|
|MarsOnboradingIC.xlsx / .md | Test cases for login module |


## Skills Demonstrated
- Test case design and documentation
- Functional and regression test coverage
- Boundary value and equivalence partitioning techniques
- Structured defect reporting
- Requirements-to-test-case traceability

Key Thing to Remember
The README should answer three questions a recruiter asks when they open the repo:
1. What is being tested?       → Overview + Coverage table
2. How were tests designed?    → Test Design Approach section
3. What does this show me      → Skills Demonstrated section
   about this candidate?

One Tip
If your test cases are in Excel, also export one sheet as Markdown or PDF and include it in the repo — so recruiters can read them directly without downloading a file. That small step makes a big difference. 🎯
Which project has the manual test cases?You said: its for mars - added testcases for languaeg and skillsits for mars - added testcases for languaeg and skills12:51 PMClaude responded: Got it!Got it! Here's your ready-to-paste README specifically for the Mars project language and skills test cases:
Go to that repo → click README.md → click pencil icon → replace with this:

markdown# Mars — Manual Test Cases (Language & Skills Module)

## Overview
A structured collection of manual test cases for the Language and Skills
modules of the Mars web application. This repository documents the test
design, coverage approach, and validation scenarios used during functional
and regression testing of these modules.

## About the Application
Mars is a web-based portal. This repository specifically covers the
**Language** and **Skills** profile management modules, which allow
users to add, edit, and delete language and skill entries from
their profile.

## Test Coverage
| Module | Scenarios Covered |
|--------|------------------|
| Language | Add a new language, edit existing language, |
|          | delete language, add duplicate language, |
|          | empty field validation, cancel action |
| Skills | Add a new skill, edit existing skill, |
|        | delete skill, add duplicate skill, |
|        | empty field validation, cancel action |

## Test Case Structure
Each test case follows this format:

| Field | Description |
|-------|-------------|
| Test Case ID | Unique identifier (e.g. TC_LANG_001) |
| Test Title | Short description of what is being tested |
| Preconditions | Setup required before execution |
| Test Steps | Step-by-step actions to perform |
| Expected Result | What should happen if working correctly |
| Actual Result | What actually happened during execution |
| Status | Pass / Fail / Blocked |
| Priority | High / Medium / Low |

## Sample Test Scenarios

### Language Module
TC_LANG_001 — Add a new language successfully

TC_LANG_002 — Add a language with empty fields

TC_LANG_003 — Add a duplicate language

TC_LANG_004 — Edit an existing language

TC_LANG_005 — Delete an existing language

TC_LANG_006 — Cancel adding a language

### Skills Module
TC_SKILL_001 — Add a new skill successfully

TC_SKILL_002 — Add a skill with empty fields

TC_SKILL_003 — Add a duplicate skill

TC_SKILL_004 — Edit an existing skill

TC_SKILL_005 — Delete an existing skill

TC_SKILL_006 — Cancel adding a skill

## Test Design Approach
- **Positive Testing** — verifying features work correctly
  with valid inputs (add, edit, delete successfully)
- **Negative Testing** — validating system behaviour with
  invalid or missing inputs (empty fields, duplicate entries)
- **Boundary Value Analysis** — testing character limits
  on language and skill name input fields
- **Equivalence Partitioning** — grouping valid and invalid
  inputs to ensure efficient test coverage
- **Exploratory Testing** — unscripted testing to discover
  defects outside documented scenarios

## Files in This Repository
| File | Description |
|------|-------------|
| Language_TestCases.xlsx / .md | Test cases for Language module |
| Skills_TestCases.xlsx / .md | Test cases for Skills module |

## Skills Demonstrated
- Manual test case design and documentation
- Functional and regression test coverage
- Positive and negative testing techniques
- Boundary value analysis and equivalence partitioning
- Requirements-to-test traceability
- Structured defect identification and reporting
