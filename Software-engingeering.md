# Software Engineering & Design Enhancement

##  Artifact Overview
This enhancement is based on my CS-340 Grazioso Salvare project, a Python Dash dashboard connected to a MongoDB database. The dashboard supports CRUD operations, interactive filtering, and map-based visualization of animal rescue data.

##  Why This Artifact Was Chosen
I selected this artifact because it contained a working foundation but needed stronger design structure, resiliency, and maintainability. It provided a perfect opportunity to demonstrate software engineering principles by improving readability, modularity, and user experience.

##  Enhancement Summary
Key design enhancements included:

- **Refactored dashboard code into clearer logical sections**
- **Improved layout structure and error-handling for UI elements**
- **Created reusable helpers instead of repeated logic**
- **Replaced brittle image-loading with a fault-tolerant logo function**
- **Added safe DataFrame handling to prevent crashes on missing data**

##  Skills Demonstrated
| Skill | Evidence |
|---|---|
| Modular design | Separated logic into reusable functions |
| Defensive programming | Added safe fallbacks and try/except handling |
| UI resiliency | Dashboard no longer breaks on bad data |
| Professional code practices | Clear structure, readable sections, comments |

##  Reflection
Enhancing this artifact helped reinforce how sound design reduces bugs and increases flexibility. The main challenge was unwinding tightly coupled logic from the original student version. By restructuring the code, I made future enhancements (like the algorithm and database improvements) easier and cleaner to implement.

**CS Outcomes Demonstrated:** Software engineering, communication, and secure design mindset.
