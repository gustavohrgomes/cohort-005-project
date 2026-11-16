# Course Platform

An online course platform where Students buy Courses, watch Lessons, and can ask for their money back.

## Language

### People

**Student**:
A person who buys and takes Courses.
_Avoid_: Learner

### Buying and refunding

**Purchase**:
A Student paying for a Course.

**Enrollment**:
A Student's access to a Course.

**Refund Request**:
A Student asking for their money back on a Purchase, in their own words. It is **Requested** until someone reviews it, then an Admin marks it **Approved** or **Declined**. A Purchase gets at most one Refund Request, and a Declined one is final.
_Avoid_: Cancellation, cancel my purchase, Reversal, Chargeback, pending, raised, rejected, denied

**Refund**:
The money given back to a Student when a Refund Request is Approved. A Refund also ends the Student's Enrollment in that Course, but their lesson progress is kept.
_Avoid_: Cancellation, Reversal, Chargeback

**Refundable Amount**:
What the Student would get back: always the amount they actually paid for the Purchase.

**Refund Window**:
The 14 calendar days after a Purchase in which a Refund Request may be made.

**Refund Eligibility**:
Whether a Student may make a Refund Request right now. They must be inside the Refund Window, have watched under 2 hours and completed under half the Lessons, not hold a claimed team seat, and have made no earlier Refund Request on this Purchase.

**Chargeback**:
A card dispute that the Student's bank starts, outside the Refund flow. This term is reserved for that and is never used for a Refund.

## Open questions

- Refunds on team licence purchases (seats that haven't been claimed) are not defined yet.
