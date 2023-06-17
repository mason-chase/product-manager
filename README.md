# Product Manager

Important note: Do not use ChatGPT to create or generate any content of below asignment!

Given pharmacy must bill invoice for all prescription dispenses to patient or insurance company.
And patient invoices are completed upon deliver (before hand over) when invoice is the patient.
And invoices to insurance company are sent on the first day of the month.

When dispenses are delivered to a patient with an insurance policy, the patient doesn't receive any invoice. Instead, it is added to the reimbursement request statement.
On the first day of the month, a reimbursement request is dispatched to the insurance company.

It is also possible that after processing the statement, the insurance company accepts it but partially rejects some items based on pricing policies, or fully rejects for two reasons:
1. Patient is not insuranced, in this case pharmacy must issue invoice to the patient.
2. Patient is insured a different insurance company, in this case pharmacy can resubmit the reimbursement request at another insurance company on the first day of the next month. 
3. For partially rejected items, pharmacy must absorb the cost differences in its accounting.

Notes:

- Pharmacy directly sends invoices to insurance company, patient reimbursement is not in the scope of the product.
- If insurance refuses reimbursement request due to the fact that patient is not insured, then patient has to pay for it.
- If insurance refuses to pay because insurance of the patient at the time of approved dispense was for a different insurance company, then invoice must be routed to new insurance company
- If insurance reject the items for all other reasons it will become the cost of pharmacy

**Deliveries**

Based on Above description please deliver below items in **LucidChart, Visio, FigJam or Diagrams.net (draw.io)** format only in a new Github repository shared with username `mason-chase`

1. Sequence Diagram [must deliver]:
   A sequence diagram will illustrate the interactions and order of events between the different entities involved in the prescription dispense and reimbursement process, such as the pharmacy, patient, and insurance company.

2. Domain Model (Class/Object Diagram) [nice to deliver]:
   A domain model diagram will showcase the key classes or objects related to the prescription dispense and reimbursement process, including their relationships and attributes.

3. Gherkin Scenarios [must deliver]:
   - Scenario 1: Successful Reimbursement Request
   - Scenario 2: Partial Rejection of Reimbursement Request
   - Scenario 3: Complete Rejection of Reimbursement Request

