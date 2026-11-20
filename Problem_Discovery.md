# Problem Discovery
## Optimizing Digital Payment & Transaction Success in India's UPI Ecosystem

---

## 1. Background

UPI has made digital payments convenient and widely accessible. However, customers can still encounter situations where a transaction is pending, fails, or money is debited without successful payment confirmation.

These situations create uncertainty, particularly when customers do not know the actual transaction status or when they can expect their money to be refunded.

This case study explores how product improvements can make these experiences more transparent and easier to resolve.

## 2. Initial Problem Identification

During the initial problem exploration, three possible technical causes were identified:

1. Network issues.
2. Bank-side issues.
3. Payment-server downtime.

However, these are potential technical causes rather than the complete customer problem.

The product opportunity is to address what customers experience when such issues occur.

**Key observation:** Even when the underlying technical issue is outside the product's control, the customer experience can be improved through clear communication, reliable status information and appropriate guidance.

## 3. Problem Statement

UPI customers and merchants face uncertainty when payments are pending, failed, or debited without confirmation.

Lack of clear transaction-status communication, guidance and refund tracking can lead to repeated payment attempts, disputes and reduced trust.

We aim to improve payment transparency and resolution guidance across the UPI payment journey.

## 4. Customer Pain Points

| Pain point | Customer concern |
|---|---|
| Unclear transaction status | Did my payment succeed or fail? |
| Money debited without confirmation | Where is my money? |
| Unclear refund progress | Has my refund started? |
| Uncertain resolution timeline | When can I expect my money back? |
| Delayed refund | What should I do next? |

## 5. Root Cause Exploration

We distinguished between two types of root causes.

### A. Technical root causes

- Network connectivity problems.
- Bank-side service interruptions.
- Payment-server downtime.
- Communication failures between payment participants.

These issues may require action from banks or payment-system partners.

### B. Product-experience root causes

- Unclear or generic transaction messages.
- Lack of visibility into confirmed refund progress.
- Insufficient guidance about the next action.
- Difficulty understanding when escalation is appropriate.

**Product decision:** Focus on the product-experience problem because improving communication, transparency and resolution guidance is within the scope of the proposed solution.

## 6. Example Customer Scenario

A customer makes a UPI payment of ₹2,000.

- The customer's bank account is debited.
- The merchant does not receive successful payment confirmation.
- The customer sees a failed or pending transaction.
- The customer is uncertain about the refund process.

The customer now has several questions:

1. What happened to my payment?
2. Has the refund been initiated?
3. What is the current refund status?
4. What is the applicable resolution timeline?
5. What should I do if the refund is delayed?

The proposed product experience aims to answer these questions using reliable transaction and refund information.

## 7. Why Refund Transparency?

The problem is not limited to displaying whether a transaction succeeded or failed.

Customers also need to understand what happens after a failed payment, especially when their money has been debited.

Therefore, the product focus extends across the complete refund journey:

- Transaction initiated.
- Payment status confirmed.
- Refund process initiated, where applicable.
- Refund progress updated through confirmed stages.
- Refund credited.

If the latest status cannot be retrieved, the product should display the last confirmed status and its timestamp rather than showing an unverified update.

## 8. Business Impact

Poor refund communication can create additional customer effort and unnecessary support contacts.

The proposed solution aims to:

- Reduce avoidable refund-status enquiries.
- Improve customer understanding of payment outcomes.
- Make delayed-refund resolution easier to navigate.
- Improve confidence in the digital payment experience.

Reducing support contacts is not sufficient by itself. Genuine unresolved complaints must continue to receive appropriate support.

## 9. Key Product Decisions

| Decision | Reasoning |
|---|---|
| Focus on product-experience issues | Technical settlement problems cannot be independently controlled by this product. |
| Cover the complete refund journey | Customers need visibility beyond the initial transaction result. |
| Display only confirmed information | Incorrect status updates can damage customer trust. |
| Include delayed-refund escalation | Customers need a clear next step when applicable timelines are exceeded. |
| Prioritize transparency before notifications | Reliable information must exist before proactive communication is introduced. |

## 10. Final Problem Discovery Outcome

The problem discovery process led to the proposal of a **UPI Transaction & Resolution Tracker**, centred on transparent refund tracking and resolution.

The product aims to help customers understand what happened to their payment, follow confirmed refund progress and know what action to take when a refund is delayed.

These findings represent product hypotheses based on problem analysis. Customer interviews, surveys and pilot testing are still required to validate the frequency and severity of the identified pain points.

---

**Outcome:** A clearly defined customer problem and a focused product opportunity for improving UPI transaction and refund experiences.