# Product Manager

Given pharmacy must bill invoice for all prescription dispenses to patient or insurance company.
And patient invoices are completed upon deliver (before hand over) when invoice is the patient.
And invoices to insurance company are sent on the first day of the month.

When dispenses are delivered to a patient with an insurance policy, the patient doesn't receive any invoice. Instead, it is added to the reimbursement request statement.
On the first day of the month, a reimbursement request is dispatched to the insurance company.

It is possible that the insurance company rejects the statement due to technical reasons.
It is also possible that after processing the statement, the insurance company accepts it but partially rejects some items based on pricing policies, or fully rejects some items for other reasons.
At this point, the pharmacy can choose to resubmit the rejected items with a new code in the next reimbursement request statement or pass them to the accounting department as costs.


**Deliveries**
Based on Above 
1. Sequence Diagram [must deliver]:
   A sequence diagram will illustrate the interactions and order of events between the different entities involved in the prescription dispense and reimbursement process, such as the pharmacy, patient, and insurance company.

2. Domain Model (Class/Object Diagram) [nice to deliver]:
   A domain model diagram will showcase the key classes or objects related to the prescription dispense and reimbursement process, including their relationships and attributes.

3. Gherkin Scenarios [must deliver]:
   - Scenario 1: Successful Reimbursement Request
   - Scenario 2: Partial Rejection of Reimbursement Request
   - Scenario 3: Complete Rejection of Reimbursement Request


