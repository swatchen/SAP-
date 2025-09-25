# SAP (Selection at Percentile) - EXISTING FILES FOR THIS PROJECT are linked here.

Meta-median version of tool - https://docs.google.com/spreadsheets/d/1ldDuYz3FVlA1poR_iuMUhkZyVUM6-qa_jbPyBQ7-hzU/edit?usp=sharing

Fixed Budget version of tool - https://docs.google.com/spreadsheets/d/18HAnYBAo1aNbEFkzfHqsU0sVPEd14wo8lTS8W4zxCV8/edit?usp=drive_link

The following documents are the thinking behind this tool and where I want to take it: 

SAP- https://docs.google.com/document/d/1y7nwiWpUE9j0ftko5QDzk8lvdr_roXYUfNBhIJynXaM/edit?usp=drive_link

SAP Evolution - https://docs.google.com/document/d/1vll0qH3kTsY-a3FVc1yfQwGLADyaZJ-6-JeTl9_latI/edit?usp=drive_link

BELOW IS THE FUNCTIONAL SPEC FOR THE HACKATHON:

https://docs.google.com/document/d/1bUithwQvw_ZKA8XJQi3Dvh0nn3pbhDJFpir2iWbgkQc/edit?tab=t.0#heading=h.b9dsxl518moe

**Vision and Core Concepts:**
The fundamental vision of this project is to create a robust, secure, and intuitive web application for collaborative resource allocation. This application represents an evolution of the "Selecting at Percentile" (SAP) methodology, a class of algorithms designed to parse the numerical votes of a group to arrive at collective decisions. The project's purpose extends beyond creating a simple budgeting tool; it aims to build a platform that embodies principles of fairness, transparency, and manipulation resistance, addressing critical shortcomings in existing collective decision-making systems, particularly within the context of Distributed Autonomous Organizations (DAOs) and other collaborative enterprises.

Traditional governance models, such as those relying on a simple 50.1% majority vote, can lead to fractious outcomes and are vulnerable to being captured by "whales"—participants with a disproportionately large number of voting shares. This can undermine the very principle of decentralization. Similarly, using a simple average to determine allocations is easily skewed by outliers. The SAP methodology, by contrast, is founded on the use of the median (or other percentile determined by median vote) as its default selection mechanism. The median represents a value that exactly half the participants feel is too high and half feel is too low, providing a definition of fairness that is inherently resistant to manipulation by extreme outliers.

A core principle underpinning the entire system design is that of "incentive compatibility." The system is designed such that a participant's optimal strategy is to vote for the outcome they genuinely believe is best. **It is mathematically impossible for any single participant to change their vote in a way that decreases the expected distance the outcome will have from their true position.** This encourages honest participation and allows the collective to more confidently weigh its true priorities.
**This project will transform an existing Google Sheets proof-of-concept tool into a multi-user web application.** It will not only replicate the core budgeting functionality but also introduce a suite of sophisticated enhancements, including secure user accounts, collaborative groups, flexible budget finalization mechanisms, and a novel approach to weighting abstentions. The ultimate goal is to provide a platform that facilitates a more nuanced, democratic, and effective process for collective budgeting and resource allocation.
