# Week 3 Portfolio
Summary of week 3.  
.

## TASK 1
__Mid-Project Change Request — CampusEats__  
__Map out, step by step, what re-work is triggered in a waterfall process (docs, sign-offs, re-testing)__
| Step | What has to happen | Re-work triggered |
| -- | -- | -- |
| Change Request | The client submits a formal chage request. The team stops and carries out an impact analaysis, and the project estimates cost and time again. | Implementation slows down or pauses while the change is analysed. |  
| Requirement | Update with new requirements for split orders, split payments, partial refunds and notifications. | The catering office must review and approve the requirements again. |  
| Design | The order data model, the payment design, the notification design, and the affected UI sreen designs. | The design review and approval must be done again. |  
| Implementation | Comments that are already build must be changed for the database schema and order data model, the order service, the payment module, the kitchen notification system, and the finished cart, checkout and order-status screens. Also, these unit tests must be written. | Several weeks of already finished work are partly thrown away and rebuilt. |  
| Test Planning | The system test plan for Month 5 is updated with new test cases. For example, when one restaurant rejects its part of an order or when only part of a payment is refunded. | Test documents must be rewritten, and the plan may need approval again. |  
| Test | All changed componets need full regression testing, because the data model change affects almost every part of the system. | Because waterfall tests late, any mistakes in the change are only found in Month 5. |  
| Schedule and Contract | Implementation runs longer, so system testing and go-live move back. The contract, budget or scope may need to be renegotiated. | The client must approve the new plan and cost. |

    
.  




__Assume the same team was working in 2-week increments — re-trace the impact__
| Step | What has to happen | Re-work triggered |
| -- | -- | -- |
| Discovery | The need for split orders would probably appear earlier because the client gives feedback every two weeks, for instance, the clients saw the checkout demo in Month 2.  | If it is found early, much less code has been built on the old data model. |  
| Backlog | The request is written as new user stories with acceptance criteria and added to the product backlog. There is no large document to rewrite. | Only a few user stories are written. |  
| Prioritisation | At the next meeting for building plan, the client decides its priority using MosCow. To keep the go-live-date, lower-priority stories can be moved out. | The client agrees on the priorities in the meeting. |  
| Implementation | The order data model, payment logic, notifications and screens still need to change.The rivise code does not disapper, but it is planned into one or two increments. | Real work on the same components, but in small and controlled steps. |  
| Test | Automated tests from earlier increments help to show quickly what the change has broken. The new feature is tested within the same increment. | Problems are found within two weeks, not at the end of the project. |  
| Acceptance | The client checks the feature at the end of increment demo and accepts it, or asks for small adjustment. | Feedback goes straight into the next increment. |  

.



__Compare the cost/effort of the change under each approach__
| Aspect | Waterfall | 2-week increments |
| -- | -- | -- |
| Documents to update | Requirements specification, design documents, test plan | A few user stories |
| Sign-offs repeated | Requirements, design, new schedule | None |
| Re-testing | Test plan rewritten: problems found late in Month 5 | Tested within the same increment |
| Schedule | Go-live in Month 6 at risk | Absorbed in 1–2 increments |
| Extra effort | High: several weeks of re-work plus overhead | Moderate: 2–4 weeks, little overhead |
  
.


## TASK 2