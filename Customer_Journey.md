# Customer Journey Map
## UPI Transaction & Resolution Tracker

### Scenario

A customer makes a UPI payment of ₹2,000. The amount is debited from their bank account, but the merchant does not receive payment confirmation. The transaction subsequently fails, and the customer waits for a refund.

### 1. Payment Initiation

**Customer action:**
- Opens a UPI application.
- Selects a merchant or recipient.
- Initiates a payment of ₹2,000.

**Customer expectation:**
- Payment should be completed successfully.
- Confirmation should be received.

**Product opportunity:**
- Display transaction details and confirmation status.

### 2. Amount Debited, Confirmation Missing

**Customer experience:**
- ₹2,000 is debited.
- Merchant confirmation is missing.

**Customer concerns:**
- Did the payment succeed?
- Has the merchant received the money?
- Should I try paying again?

**Product response:**
- Display the latest confirmed transaction status.
- Explain that confirmation is pending or unavailable.
- Provide appropriate guidance to avoid unnecessary duplicate payments.

### 3. Transaction Failed

**Customer experience:**
- The transaction is marked as failed.
- The customer is unsure about the money debited.

**Customer concerns:**
- Will my money be refunded?
- How much will I receive?
- When should I expect it?

**Product response:**
- Display the transaction details.
- Explain the applicable refund process.
- Show the refund amount and relevant timeline.

### 4. Refund Processing

**Customer experience:**
- The customer waits for the refund.

**Customer concerns:**
- Is my refund being processed?
- Has the process stopped?
- Has anything changed?

**Product response:**
- Display the last confirmed refund status.
- Show the refund journey.
- Display the latest update and applicable expected resolution date.

### 5. Refund Delayed (Exception Journey)

**Customer experience:**
- The applicable resolution timeline has passed.
- The customer has not received the refund.

**Customer concerns:**
- Why is my refund delayed?
- What should I do now?
- How can I contact support?

**Product response:**
- Clearly identify the delay.
- Explain the next steps where information is available.
- Provide an escalation or complaint-registration option.
- Allow the customer to track the complaint.

### 6. Refund Credited

**Customer experience:**
- The refund is credited to the customer's account.

**Customer expectation:**
- Confirmation that the refund is complete.

**Product response:**
- Display the confirmed refund completion status.
- Show the credited amount and relevant timestamp.
- Make the original transaction and refund details accessible.

---

## Overall Customer Journey

Payment Initiated → Amount Debited → Confirmation Missing → Transaction Failed → Refund Processing → Refund Credited

**Exception path:**

Refund Processing → Applicable Timeline Exceeded → Escalation → Complaint Tracking → Refund Resolution

## Main Customer Pain Points

1. Uncertainty about payment status.
2. Lack of clarity about the refund process.
3. No clear visibility into refund progress.
4. Uncertainty when the refund is delayed.
5. Difficulty tracking complaints and resolution.

## Product Opportunity

The UPI Transaction & Resolution Tracker aims to reduce these pain points through accurate transaction information, transparent refund tracking, clear guidance and accessible escalation.

**Important boundary:** The product improves the customer-facing experience. Actual payment processing and refund settlement remain dependent on the relevant banks and payment-system partners.