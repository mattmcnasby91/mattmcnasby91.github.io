# Algorithms & Data Structures Enhancement

##  Artifact Overview
This enhancement focused on optimizing how the dashboard builds and processes search filters. The original version used hard-coded queries and repetitive logic for each radio-button option.

##  Enhancement Summary
I improved algorithmic efficiency and maintainability by adding:

- A parameterized `build_query()` function
- A `normalize_filters()` validation method
- A single reusable `fetch_animals()` function instead of repeated CRUD calls
- Safe DataFrame creation that avoids crashes if data is missing
- Logic that scales as new filters are added

These changes eliminated redundancy and reduced query logic to a single source of truth, improving performance and testability.

##  Skills Demonstrated
| Skill | Evidence |
|---|---|
| Algorithmic thinking | Consolidated repeated logic into reusable builders |
| Input validation | Prevented invalid or inverted age ranges |
| Data structure reasoning | Clean DataFrame processing instead of ad-hoc operations |

##  Reflection
This enhancement taught me how small algorithmic changes can significantly improve structure and scalability. The biggest challenge was reorganizing functionality without breaking UI callbacks. In the end, the logic became cleaner and dramatically easier to maintain.

**CS Outcomes Demonstrated:** Algorithmic design, data handling, performance-aware thinking.
