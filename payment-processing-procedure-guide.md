# How to Process a Customer Payment Over the Phone

## Purpose and Scope

**Purpose:** This guide walks you through processing a customer payment by phone — from greeting the caller to closing the call — accurately, securely, and in compliance with call-recording and PCI DSS payment regulations.
**Scope:** This guide covers phone payments only. It does not cover payments made through the web portal, in a branch, or by mail, nor does it address refunds, disputes, or chargebacks.
**Audience:** New customer service representatives taking live payment calls, as well as experienced representatives who want a refresher.
**Before you begin:** You should be logged into your account management system, ready to take calls, and familiar with your employer's verification and payment policies.

---

## Greeting

* Introduce yourself by first name only.
* State the name of your employer.
* Ask the purpose of the call.
* Speak clearly and calmly. This helps assure the customer that you are competent and ready to assist them.

**Example:**

> "Hello, this is Adam at Stone Bank. How can I help you today?"

---

## Recording Disclosure

* Ask the caller for their name.
* Thank them for their call, using their name.
* Inform the customer that the call is being recorded and explain the reason. The exact wording will vary depending on company policy.
* Stating the disclosure at the outset of the call:

  * Ensures transparency and helps build trust.
  * Helps you comply with state and federal regulations regarding consent to record a phone conversation.
  * Protects your employer from potential legal issues if a caller later raises a complaint about something that happened during the call.
  * Informs the caller that the recording may be reviewed for quality assurance and training purposes.

**Example:**

> "Thank you for your call, Mr. Williams. I just need to inform you that this call will be recorded for quality and training purposes."

### If the Customer Declines to Be Recorded

* Politely explain that you cannot proceed without recording the call.
* Empathize with their objection.
* Offer alternative payment options.
* If they still decline, thank them for their call and wish them a good day before disconnecting.

**Example:**

> "I apologize, Mr. Williams. I understand that you don't want to be recorded. Unfortunately, I'll be unable to proceed without the call being recorded. You can always make payments through our web portal, at your local branch, or via mail. Thank you for calling Stone Bank, and have a good day."

### If the Customer Agrees to Be Recorded

* Thank them for their understanding and cooperation.

**Example:**

> "Thank you for your understanding, Mr. Williams. I appreciate your cooperation, and I'm here to help you with your payment today."

* Proceed to the next step and access their account.

---

## Accessing the Account

Depending on your employer's account management system, you may be able to locate the account using:

* Account number
* Phone number
* Date of birth

---

## Verifying the Caller

Depending on company policy, you will typically need three to five pieces of information to verify the caller.

Possible verification information includes:

* Account number
* Phone number
* Date of birth
* Last four digits of the Social Security number
* Address
* Amount of the last payment

Some employers require the exact amount of the last payment, while others are more flexible.

* Count any information already collected earlier in the call toward verification. Do not ask for it again, as this may make the customer think you were not paying attention.
* If the caller's name differs from the account holder's name, check for authorized users on the account.
* If the caller is the account holder or an authorized user, continue to the next step.
* If the caller is not an authorized user, company policy may still allow you to accept a payment. However, you may not be able to disclose account information such as balances, payment history, or prior transactions.

### If You Cannot Verify the Caller

* Politely explain that you are unable to verify their identity and therefore cannot assist them with a payment over the phone.
* Empathize with their situation.
* If they ask why, explain that these security measures protect the account from unauthorized access and fraud.
* Reassure them that these measures exist for their protection.
* Offer alternative payment options, such as:

  * Web portal
  * Local branch
  * Mail
* Thank them for their call and wish them a good day before disconnecting.

---

## Determining the Payment Method

* Ask the caller which payment method they want to use.
* In most cases, you can accept:

  * ACH payments
  * Debit card payments

### ACH Payments (Automated Clearing House)

* Ask for the 9-digit routing number.
* Repeat the routing number to verify it.
* If your system displays the associated bank name, verify that information as well.
* Ask for the bank account number.
* Verify the account number.

### Debit Card Payments

* Ask for the 16-digit debit card number.
* Verify the card number.
* Ask for the card's expiration date.
* Verify the expiration date.
* Ask for the three- or four-digit CVV number. Some cards may refer to it as a "security code."
* Verify the CVV.

> Card numbers and security codes (CVV) are subject to PCI DSS regulations and generally cannot be retained in call recordings. Most systems handle this automatically; follow your employer's specific procedures for capturing card details.

---

## Taking the Payment

* Ask the customer how much they would like to pay.
* Verify the amount.

### If the Customer Wants to Pay Less Than the Minimum Payment

* Inform them of the minimum payment amount.
* Ask whether they would like to pay that amount instead.
* If they still want to pay less than the minimum payment, process the payment as requested after confirming they understand the remaining balance is still due by the due date to avoid late fees and potential negative impacts on their credit score.


### If the Customer Wants to Pay More Than the Total Balance

* Inform them of the total balance.
* Ask whether they would like to pay that amount instead.
* If they confirm, proceed with the lower amount as you would any standard payment.
* If they still want to pay more than the balance, check whether your system allows overpayments.
    * If it does, process the payment as requested. Inform the customer that the excess amount will be applied as a credit to their account.
    * If it does not, inform the customer that the system cannot accept a payment exceeding the balance, and ask if they'd like to proceed with the balance amount instead.

---

## Payment Confirmation

Some employers require a specific script. If so, follow it exactly.

The confirmation typically includes:

1. Repeating the customer's name.
2. Giving the payment date.
3. Giving the payment amount.
4. Confirming the last four digits of the customer's account number.
5. Confirming the payment method and the last four digits of the bank account or debit card.
6. Asking the customer to verify the information and authorize the payment.

**Example:**

> "Just to confirm, Mr. Williams, you're requesting on June 1st, 2026, to make a payment of $150.00 to your account ending in 1234, using your debit card ending in 5678. Is that correct? Would you like to proceed with this payment?"

This recap serves two purposes:

1. It allows the customer to catch mistakes before the payment is processed, helping prevent declines or payments being applied incorrectly.
2. It protects you and your employer if a customer later disputes the payment or claims they did not authorize it.

* If the customer confirms the information, process the payment.
* If not, identify and correct any errors before proceeding.

---

## Processing the Payment

After confirming the payment details, follow your employer's procedures for processing the transaction.

1. Enter the payment information into the system.
2. Submit the payment.
3. Wait for confirmation.

### If the Payment Is Declined

1. Inform the customer.
2. Verify the payment information again.
3. Attempt the payment a second time if appropriate.
4. If the payment is declined again, advise the customer to use another payment method or contact their bank.

### If the Payment Is Successful

1. Inform the customer that the payment has been received.
2. Explain when the payment will be applied to the account, usually within one to three business days.
3. If your employer provides confirmation numbers, follow company policy on whether to offer one proactively or only provide it if asked.

---

## Closing the Call

* Ask whether there is anything else you can help them with. This demonstrates attentiveness and a willingness to assist with additional concerns.
* If the customer has no further questions, thank them for their payment and for calling.
* Use their name to personalize the interaction.
* Follow your employer's closing script if one exists.

**Example:**

> "Thank you for your payment, Mr. Williams. We appreciate your business and thank you for calling Stone Bank. Have a great day!"

* Allow the customer to disconnect first.
* After the customer hangs up, disconnect the call on your end.
