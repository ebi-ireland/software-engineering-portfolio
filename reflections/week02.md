# Week 2 Portfolio
This document evaluates suitable software development models—such as Waterfall, RAD, and Incremental development—for different project briefs based on criteria like risk, timeline, and requirements. It also analyzes a student scholarship website project to justify using an incremental approach.   
.  

## TASK 1


### Brief A  
| Criterion | Level | Analaysis |
| -- | -- | -- |
| Requirement stability | Very High | Engineering analysis defines the failure modes and warning behaviors before coding starts, these features are unlikely to change. |
| Risk / safety | Very High | A single defect could endanger lives, every stage must be completed, reviewed, and approved before moving to the next. |
| Timeline | Flexible | The timeline depends on a 12-18 month certification processes, the slower pace of the Waterfall model is not a problem. |
| Customer involvement | Frequent | Communication is formal rather than frequent. The client's QA team requires documentation at each stage, which fits well with Waterfall’s document-focused approach. |
| Documentation / audit | Required | Certification requires complete tracking from initial requirements to the code and test results. The Waterfall model naturally creates these exact documents throughout the process. |


__Justification__  
Waterfall is ideal because the requirements are well understood, unlikely to change, and require detailed documentation. Although the project is "High-risk", the risks are already clear and the changes are small. Since the timeline is not under intense pressure, adding the extra cost of repeated risk analysis in the Spiral model is unnecessary.

__Risk of This Model__  
A major risk of Waterfall is that testing occurs late in the process. For example, finding a warning issue late in development would be costly and could delay certification. However, because the project operates at an unhurried pace, the team has plenty of time to write test cases during the requirements phase and thoroughly review each document before sign-off to mitigate this risk.  
.


### Brief B  
| Criterion | Level | Analaysis |
| -- | -- | -- |
| Requirement stability | Low | The owner is unsure about the visual style and often changes her mind after seeing a draft. However, the core functions are small and clear. |
| Risk / safety | Very Low | There are no legal or safety regulations to follow, and the project is technically simple. |
| Timeline | Tight | The website must be launched within three weeks to be ready for the food festival. |
| Customer involvement | High | The owner is available to provide daily feedback on the design. |
| Documentation / audit | Required | Producing detailed reports would cost more than building the website itself. |


__Justification__  
RAD is ideal because it uses quick prototypes and reusable parts to deliver small projects fast. The team can use a website template to build the layout and contact form quickly. This allows them to show working pages to the owner every few days. Since she only knows what she wants after seeing it, showing real designs is much more effective than asking her to sign off on a written document.

__Risk of This Model__  
A key risk of this model is scope creep. Since revisions are straightforward, the owner may constantly ask for minor aesthetic updates and potentially threatening the festival launch date. To mitigate this risk, feedback rounds must be time-boxed, and requirements should be categorized using the MoSCoW method to guarantee that 'must-have' features are deployed first, leaving minor visual adjustments for post-launch updates.  
.


### Brief C  
| Criterion | Level | Analaysis |
| -- | -- | -- |
| Requirement stability | Very High | The founders only have a basic idea for the app and expect many changes after real students start using it. |
| Risk / safety | Medium | There are no strict industry rules, but protecting students' personal data is important. |
| Timeline | Moderately Busy | The team needs a working app within a month before the new term starts, especially because a rival might launch first. |
| Customer involvement | Very High | The founders work directly with the developers, and real students will give feedback on every update. |
| Documentation / audit | No Need | Since the small team of four works in the same room, they can easily share ideas without writing long reports. |


__Justification__  
Incremental development is the best choice because it delivers working features step by step. For example, the first release can just focus on browsing clubs and signing up for events within a month. Later features, like an in-app chat, can be added after seeing how students use the app. This approach also fits a small team working closely together.

__Risk of This Model__  
An incremental approach is ideal because it allows the team to launch a simple, working version very quickly. The first release can include key features like event RSVPs within a month. After that, the team can add new functions based on real user feedback. This flexible method works especially well for a small team working in the same location.  
.




## TASK 3
A project I have chose is a website that helps students find domestic and international scholarships for studying in university. Users can search scholarships by their domestic country and countries as international students, subject and deadline, and save the ones they are interested in.

Firstly, the requirement are only partly clear. The core feature is a searchable list. 

Secondly, the risk is low. There is no safety issue, although personal data in user accounts must be protected. 

Thirdly, scholarship deadlnes follow the academic year, so a basic version should go live quickly and then improve. 

Finally, real students can test each increment. The first increment would be a simple search page, followd by saved list and email reminders. The main risj is reworking the data model later, so I would design it carefully at the start.  
