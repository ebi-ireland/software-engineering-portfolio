# Week 1 Portfolio

This repository will contain my weekly research lab write-ups, code artifacts, and reflections for the Software Engineering module throughout the semester.



## Task 1 — First Reflection

### Question1:
In reflections/week01.md, write your first entry (150-200 words): what is 'software', and what does 
'engineering' add to that? Draw on software you personally use that has worked well, and software that 
has frustrated or failed you 

### My Answer:  
Software is more than just a programme which includes the programmes themselves, such as applications and scripts, as well as the data, configuration files and documentation that allow them to run and be used. The operating system is also software, since it manages the computer's hardware resources, including the CPU, memory, storage, input/output devices and networking.
Engineering adds a professional and systematic approach to building software. Software engineering applies suitable theories, methods and tools to solve real problems while taking organisational and financial constraints into account. It covers every stage of production, not only coding, but also project management and the tools that support it. Whereas computer science asks what is computable, software engineering asks how to deliver a working, maintainable system on time and on budget.



### Question 2: 
Note two concrete examples (successes or failures) you’ve personally experienced, and, for each, a first 
guess at what the developers might have done differently 

### My Answer:
**Success:**  
Will Abroad is a full-stack platform for education and admissions consulting that I built and operate on my own. It succeeded mainly because its purpose was clear from the beginning: to help students find suitable universities and scholarships. This clear goal made it easier to decide which features to build and how to design the database. 

**Fail:**  
An aircraft game failed because the planning was not concrete. Since there was no fixed goal, the purpose of the game changed almost every time I wrote new code. As a result, I often had to rewrite existing parts, and the project never reached a finished state. A better approach would have been to define the requirements and the main goal of the game before coding, and to keep the first version small. Any new ideas could then have been added in later versions without changing the core design.



## Task 2 — Applying the Four Process Activities

**Stage 1** — Kickoff (Week 1)   
The IT director held a single one-hour meeting with the lead developer to describe 'roughly what was needed'. No written requirements document was produced. The developer felt confident he understood the brief and began 
designing a database schema that same afternoon. 


**Stage 2** — Development (Months 1-5)   
The team of three developers worked largely independently, each taking a module (stock intake, stock transfer, reporting) with minimal coordination between them. There were no shared coding standards and no code review process — each developer pushed code directly to a shared folder on a network drive, occasionally overwriting a colleague's changes without noticing. Warehouse staff were not consulted during this period; the developers assumed their understanding of 'how a warehouse works' from the kickoff meeting was sufficient. 


**Stage 3** — A Change of Plan (Month 4)   
Midway through development, the IT director mentioned in passing that the system would also need to support the company's new second warehouse, which used a different shelving and barcode scheme. This had not been part of the original (unwritten) brief. The lead developer estimated this would 'probably add a few weeks' and did not revisit the existing design, instead patching the second warehouse's requirements on top of the existing schema. 


**Stage 4** — Testing (Month 6)   
With the original deadline approaching, the team ran the application themselves for two days, fixed the crashes they personally encountered, and declared it 'basically working'. No warehouse staff tested the system before golive. No test cases had been written down anywhere during development. 


**Stage 5** — Go-Live (Month 9)   
On the first day of live use, warehouse staff found the stock-transfer screens did not match how transfers actually happened on the floor, the second-warehouse barcode format was rejected by the scanner integration, and two staff members using the system simultaneously caused stock counts to become corrupted. The system was pulled from use within a week while the team scrambled to fix it, ultimately extending the project by a further three months. 



## The Four Process Activities: RetailSync Case Study

| Stage | Specification | Development | Validation | Evolution |
|---|---|---|---|---|
| 1. Kickoff | Weak | Started too early | Missing | N/A |
| 2. Development | Missing | Weak | Missing | N/A |
| 3. A Change of Plan | Weak | Weak | Missing | Weak |
| 4. Testing | Missing | Present | Weak | N/A |
| 5. Go-Live | Missing | Weak | Weak | Weak |

- **Kickoff:** Requirements were given verbally in a one-hour meeting and never written down. The developer began designing the database on the same day, before the requirements had been checked or agreed.

- **Development:** Code was produced, but with no coding standards, no version control and no code review, so developers overwrote each other's work. Warehouse staff were never consulted, so the requirements were never refined.

- **A Change of Plan:** A major new requirement arrived informally and was not recorded. Instead of reviewing the design, the team patched it onto the existing schema, which shows that change was handled badly.

- **Testing:** Only the developers tested the system, for two days, with no written test cases. There was no user acceptance testing, so validation was very weak.

- **Go-Live:** The real validation happened in live use, where users found wrong transfer screens, rejected barcodes and corrupted stock counts. The fixes that followed were reactive rather than planned evolution.


### The most damaging failure
In my view, the most damaging failure was the lack of a written specification at the kickoff stage. Almost every later problem can be traced back to it. Without documented requirements, the developers had nothing to share or coordinate around, and they never checked their assumptions with warehouse staff. The second warehouse was treated as a small addition because there was no original scope to compare it with. Testing was also weak partly because no test cases could be written without clear requirements. Finally, the problems found at go-live, such as the incorrect transfer screens and the lack of support for simultaneous users, were all requirements that a proper specification process should have identified early, when they would have been much cheaper to fix.