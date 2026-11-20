# Product Requirements Document (PRD)

## Optimizing Digital Payment & Transaction Success in India's UPI Ecosystem

**Product concept:** UPI Transaction & Resolution Tracker  
**Primary feature:** Transparent Refund Tracking and Resolution  
**Document type:** Industry-level product proposal  
**Status:** Initial PRD — ready for review

---

## 1. Product Overview

The UPI Transaction & Resolution Tracker is a proposed customer-facing experience designed to improve transparency across failed, pending and delayed UPI payment journeys.

It helps customers understand what happened to their payment, view their refund progress, see the latest confirmed status and find the appropriate next steps when a refund is delayed.

The product focuses on improving communication and resolution visibility. It does not independently control bank settlement or payment processing.

## 2. Problem Statement

UPI customers and merchants face uncertainty when payments are pending, failed, or debited without confirmation.

Lack of clear transaction-status communication, guidance and refund tracking can lead to repeated payment attempts, disputes and reduced trust.

We aim to improve payment transparency and resolution guidance across the UPI payment journey.

## 3. Target Users

**Primary users:**
- UPI customers who experience failed, pending or delayed payments.
- Customers whose accounts are debited but whose transactions are not confirmed.

**Secondary users:**
- Merchants who need clarity about payment confirmation.
- Customer-support teams handling payment and refund-related queries.

## 4. Product Goal

Help customers understand their refund status, applicable resolution timeline and available actions without repeatedly contacting customer support for basic updates.

### Business objective

Reduce unnecessary refund-related support contacts while maintaining customer satisfaction and reliable complaint resolution.

## 5. Proposed Solution

An integrated transaction and resolution experience with a central Refund Tracking Dashboard.

The dashboard will provide:
- Original transaction information.
- Current confirmed payment status.
- Refund amount and status.
- Refund journey and latest update.
- Applicable expected resolution timeline.
- Guidance and escalation options for delayed refunds.

## 6. User Story

As a UPI customer, I want to view my transaction details and refund status, so that I can understand what happened to my payment, track my refund progress and know when to expect my money back.

## 7. MVP Scope and Prioritization

### Must-have — First release

1. **Transaction details and payment status**
   - Transaction amount and ID.
   - Date and time.
   - Merchant or recipient details where available.
   - Current confirmed payment status.

2. **Refund information and journey tracking**
   - Refund amount.
   - Refund status.
   - Refund initiation information where available.
   - Confirmed refund progress.
   - Last-updated timestamp.
   - Applicable expected resolution date.

3. **Delayed refund handling and escalation**
   - Identify refunds that exceed their applicable resolution timeline.
   - Clearly communicate the delay.
   - Explain available next steps.
   - Provide an escalation or complaint-registration option.

### Early follow-up release

- Proactive notifications for important refund-status changes.
- Detailed complaint tracking, including complaint ID, status and latest update.
- Expected complaint response timeline where reliable information is available.


## 8. Functional Requirements

**FR-01: Transaction Details**

The product must display relevant transaction information, including amount, transaction ID, date, time, merchant or recipient where available, and payment status.

**FR-02: Refund Information**

The product must show the refund amount, current refund status, relevant initiation details and applicable resolution timeline.

**FR-03: Refund Journey**

The product must show confirmed refund stages, the latest update and the applicable expected resolution date.

Only verified events should be displayed as completed stages.

**FR-04: Refund Notifications**

The follow-up release should notify customers when important refund-status changes are confirmed. Notifications must avoid duplicates and misleading updates.

**FR-05: Delayed Refund Handling**

The product must identify refunds that exceed their applicable timeline, explain the delay where known and provide guidance and an escalation option.

**FR-06: Complaint Tracking**

The product should provide complaint ID, registration date, current status, latest update and an expected response timeline where reliable information is available.

## 9. Non-functional Requirements

- **Reliability:** Display accurate, verified transaction and refund information.
- **Security:** Protect customer and transaction information.
- **Performance:** Provide a responsive dashboard experience.
- **Availability:** Make tracking accessible whenever the service is operational.
- **Consistency:** Keep dashboard information and notifications aligned.

### Unavailable status handling

If the bank or payment system cannot provide an updated status:
- Display the last confirmed status.
- Show its last-updated timestamp.
- Clearly explain that the latest status is temporarily unavailable.
- Refresh the information when reliable data becomes available.
- Never invent or assume a refund status.

## 10. Success Metrics

### Primary metric

**Refund-related support contact rate**

Measures the proportion of customers with relevant refund cases who contact support for refund-status updates.

### Supporting metrics

1. Average time spent checking refund status.
2. Customer satisfaction with refund transparency.

### Measurement approach

- Establish the actual pre-launch baseline.
- Launch the MVP with a controlled pilot.
- Compare post-launch performance against the baseline.
- Set a realistic improvement target after baseline measurement.
- Monitor customer satisfaction and genuine unresolved complaints as guardrails.

A reduction in support contacts should not be treated as success if customers are unable to access support for genuine problems.

## 11. Launch Strategy

### Controlled pilot

Begin with a small group of customers who have previously experienced failed or delayed UPI payments.

**Pilot stages:**

1. Identify eligible customers.
2. Introduce the refund-tracking experience to a small group.
3. Collect feedback on clarity, accuracy and ease of use.
4. Identify and fix issues.
5. Gradually expand availability.

The feature should eventually be available to all eligible customers, not just customers who have previously experienced payment failures.

### Pilot evaluation

Evaluate three areas:

- Can customers understand their refund status without contacting support for basic updates?
- Is the displayed refund information accurate and reliable?
- Can customers successfully escalate delayed refunds?

## 12. Key Product Risks

| Risk | Mitigation |
|---|---|
| Incorrect refund status | Display only verified information and timestamps. |
| Bank/payment integration failure | Show last confirmed status and explain temporary unavailability. |
| Customers don't understand the refund journey | Use simple language, clear stages and actionable guidance. |

### Risk prioritization

Incorrect information is a major trust risk. Poorly understood information is a major usability risk. Both must be addressed before expanding the pilot.

## 13. Product Dependencies and Boundaries

The solution depends on reliable transaction and refund-status information from relevant banks and payment-system partners.

The product can improve:
- Status transparency.
- Customer communication.
- Refund visibility.
- Complaint escalation.
- Unnecessary support contacts.

The product cannot independently:
- Control bank settlement.
- Force a bank to process a refund faster.
- Guarantee a refund completion date without reliable supporting information.

Applicable refund timelines must reflect the relevant transaction type and current regulatory and payment-system requirements.

## 14. Competitor Research

The initial research considered PhonePe, Google Pay and Paytm.

The research explored publicly documented capabilities around:
- Transaction history and status.
- Pending-payment guidance.
- Refund guidance.
- Complaint registration.
- Complaint tracking.

These services already offer several transaction-support capabilities. Therefore, the proposal should not claim that refund tracking or complaint handling is entirely absent from competitors.

The opportunity to investigate is whether customers still experience uncertainty despite existing capabilities. This requires customer research and validation.

Public documentation is not equivalent to hands-on product testing or proof of a competitor's complete feature set.

## 15. ICICI Bank Implementation Perspective

The industry-level product proposal could be adapted for a bank such as ICICI Bank through its iMobile UPI experience.

A possible implementation approach:
- Introduce a refund-tracking dashboard within the existing banking app.
- Connect it to reliable transaction and refund-status information.
- Provide clear refund guidance and escalation options.
- Coordinate with relevant payment partners and internal support teams.
- Measure changes in refund-related support contacts and customer satisfaction.

This is a proposed implementation direction, not a claim about existing ICICI Bank capabilities or a confirmed partnership.

## 16. Expected Product Impact

The proposed solution aims to:
- Reduce uncertainty during failed and delayed payment journeys.
- Improve customer understanding of refund progress.
- Reduce unnecessary refund-status support contacts.
- Make complaint escalation more transparent.
- Strengthen customer confidence through reliable communication.

**Final product principle:** Do not simply tell customers that a payment failed. Help them understand what happened, what is happening now and what they can do next.