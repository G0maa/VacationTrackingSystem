# Vision
1. A Vacation Tracking System (VTS) will provide individual employees with the capability to manage their own vacation time, sick leave, and personal time off, without having to be an expert in company policy or the local facility’s leave policies.

# Functional requirements
1. One manual approval by the immediate manager.
2. High-level employees may not require manager approval.
3. Implements a flexible rules-based system for validating and verifying leave time requests
4. Enables manager approval (optional)
5. Provides access to requests for the previous calendar year, and allows requests to be made up to a year and a half in the future
6. Uses e-mail notification to request manager approval and notify employees of request status changes
7. Uses existing hardware and middleware
8. Is implemented as an extension to the existing intranet portal system, and uses the portal’s single-sign-on mechanisms for all authentication
9. Keeps activity logs for all transactions
10. Enables the HR and system administration personnel to override all actions restricted by rules, with logging of those overrides
11. Allows managers to directly award personal leave time (with system-set limits)
12. Provides a Web service interface for other internal systems to query any given employee’s vacation request summary
13. Interfaces with the HR department legacy systems to retrieve required employee information and changes

# Non-functional requirements
1. System must be easy to use.
2. Improve internal business processes of the organization (with respect to vacation time tracking).
3. Save time & Money for HR Department.

# Constraints
1. Web Application
2. Extend existent intranet
3. Use existing hardware
4. Apply company policies for vacations

# Domain (Define Problem)
1. Employees work on many different projects
2. Said projects have different managers
3. Managers do not know when an employee has a vacation.

# Actors
1. Employees
2. Mangers
3. Clerk
4. System Admin

# Use-cases

## Manage Time
1. For ERD, Flowcharts, Sequence diagrams and Pseudocode, refer to `.diagrams` directory.

# Resources
1. Object Oriented Analysis and Design (OOAD) Chapter - 12