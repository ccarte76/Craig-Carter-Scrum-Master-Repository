# Product Backlog — E-Commerce Checkout Improvement

## Product Goal

Improve the e-commerce checkout experience by making payment, shipping, and order confirmation simpler, clearer, and more reliable for customers.

---

## Backlog Prioritization

The Product Owner prioritizes the Product Backlog based on customer value, business needs, dependencies, and the overall Product Goal.

Story points represent the Developers' relative estimate of the size, complexity, effort, and uncertainty associated with each User Story.

Story points are not hours.

---

## Product Backlog

| ID    | User Story                                                                                                           | Priority | Story Points | Status |
| ----- | -------------------------------------------------------------------------------------------------------------------- | -------- | -----------: | ------ |
| US-01 | As a customer, I want to save my payment method so I don't have to enter it every time I check out.                  | High     |            5 | Ready  |
| US-02 | As a customer, I want to receive a clear confirmation after placing an order so I know my purchase was successful.   | High     |            3 | Ready  |
| US-03 | As a customer, I want to edit my shipping address during checkout so I can correct mistakes before placing my order. | High     |            5 | Ready  |
| US-04 | As a customer, I want to use a digital payment option during checkout so I have more ways to pay.                    | High     |            8 | Ready  |
| US-05 | As a customer, I want to receive a clear message when my payment fails so I know what to do next.                    | High     |            3 | Ready  |
| US-06 | As a customer, I want checkout to work effectively on my mobile device so I can complete purchases from my phone.    | Medium   |            8 | Ready  |
| US-07 | As a customer, I want to review my order before submitting payment so I can catch mistakes before purchasing.        | High     |            5 | Ready  |
| US-08 | As a customer, I want my cart items to remain available if I leave checkout temporarily.                             | Medium   |            5 | Ready  |
| US-09 | As a customer, I want to see estimated taxes and shipping costs before payment so I understand my total cost.        | High     |            5 | Ready  |
| US-10 | As a customer, I want to remove an item from my order during checkout so I can adjust my purchase.                   | Medium   |            3 | Ready  |
| US-11 | As a customer, I want to change the quantity of an item during checkout so I can adjust my order.                    | Medium   |            3 | Ready  |
| US-12 | As a customer, I want to receive an estimated delivery date so I know when to expect my order.                       | Medium   |            5 | Ready  |
| US-13 | As a customer, I want my payment information to be handled securely so I can confidently complete my purchase.       | High     |            8 | Ready  |
| US-14 | As a customer, I want checkout error messages to clearly explain what went wrong so I can correct the problem.       | High     |            5 | Ready  |
| US-15 | As a customer, I want to return to my cart from checkout without losing my information.                              | Medium   |            3 | Ready  |
| US-16 | As a customer, I want the checkout process to load quickly so I don't have to wait.                                  | Medium   |            8 | Ready  |
| US-17 | As a customer, I want to receive an email receipt after completing my order.                                         | Medium   |            5 | Ready  |
| US-18 | As a customer, I want to select from multiple shipping options so I can choose the option that works best for me.    | Medium   |            5 | Ready  |
| US-19 | As a customer, I want to apply a valid promotional code during checkout so I can receive my eligible discount.       | Medium   |            5 | Ready  |
| US-20 | As a customer, I want the checkout process to clearly show which step I'm currently completing.                      | Low      |            3 | Ready  |

---

# Detailed User Stories

## US-01 — Save Payment Method

### User Story

> As a customer, I want to save my payment method so I don't have to enter it every time I check out.

**Priority:** High
**Story Points:** 5

### Acceptance Criteria

* Customer can choose to save an eligible payment method.
* Saved payment methods are available during future checkout sessions.
* Customer can select a previously saved payment method.
* Customer can remove a saved payment method.
* Sensitive payment information is handled according to the application's security requirements.

---

## US-02 — Order Confirmation

### User Story

> As a customer, I want to receive a clear confirmation after placing an order so I know my purchase was successful.

**Priority:** High
**Story Points:** 3

### Acceptance Criteria

* Customer sees a confirmation after a successful order.
* Confirmation includes the order number.
* Confirmation displays the order summary.
* Confirmation indicates that payment was successfully processed.
* Customer can access the confirmation after completing checkout.

---

## US-03 — Edit Shipping Address

### User Story

> As a customer, I want to edit my shipping address during checkout so I can correct mistakes before placing my order.

**Priority:** High
**Story Points:** 5

### Acceptance Criteria

* Customer can edit the shipping address before payment is submitted.
* Required address fields are validated.
* Customer receives feedback when required information is missing.
* Updated address is reflected in the order summary.
* Customer cannot submit an incomplete address.

---

## US-04 — Digital Payment Option

### User Story

> As a customer, I want to use a digital payment option during checkout so I have more ways to pay.

**Priority:** High
**Story Points:** 8

### Acceptance Criteria

* Eligible customers can select the digital payment option.
* The payment option is displayed during checkout.
* Successful payment results in an order being created.
* Failed payment produces an appropriate error message.
* The order is not duplicated if payment processing fails.

---

## US-05 — Payment Failure Message

### User Story

> As a customer, I want to receive a clear message when my payment fails so I know what to do next.

**Priority:** High
**Story Points:** 3

### Acceptance Criteria

* Customer receives a clear message when payment fails.
* Message explains that payment was unsuccessful.
* Customer can attempt payment again.
* Customer's order information is preserved when possible.
* A failed payment does not create a duplicate order.

---

## Definition of Ready

Before a User Story is considered ready to enter a Sprint, the Scrum Team should have enough information to understand and discuss the work.

A story should generally have:

* A clear User Story statement
* Clear acceptance criteria
* A defined business purpose
* Sufficient understanding for estimation
* Identified dependencies when known
* A size that allows the team to reasonably plan the work

---

## Backlog Refinement

The Product Backlog is continuously refined throughout the project.

During refinement, the Scrum Team may:

* Clarify User Stories
* Discuss acceptance criteria
* Identify dependencies
* Break down large stories
* Re-estimate work when new information becomes available
* Identify stories that are ready for Sprint Planning

The Product Owner remains accountable for Product Backlog management and ordering.

The Developers provide technical insight and estimates.

The Scrum Master facilitates effective collaboration and helps the team maintain a healthy refinement process.

---

## Initial Backlog Summary

**Total User Stories:** 20

The Product Owner will use the Product Goal, customer value, dependencies, and other relevant considerations to determine which items should be considered for upcoming Sprints.

The Scrum Team will not automatically attempt to complete the entire Product Backlog within a single Sprint.

Sprint scope will be determined during Sprint Planning based on the Sprint Goal, the team's understanding of the work, and its capacity.

> **Portfolio Project:** This Product Backlog is part of an independently created Scrum simulation and does not represent professional employment experience.
