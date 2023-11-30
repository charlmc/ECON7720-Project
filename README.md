# ECON7720-Project

After a debt has been legally declared "uncollectable" by a bank, the account is considered "charged-off." But that doesn’t mean the bank walks
away from the debt. They still want to collect some of the money they
are owed. The bank will score the account to assess the expected recovery amount, that is, the expected amount that the bank may be able to
receive from the customer in the future. This amount is a function of the
probability of the customer paying, the total debt, and other factors that
impact the ability and willingness to pay.


The bank has implemented different recovery strategies at different thresholds ($1000, $2000, etc.) where the greater the expected recovery amount,
the more effort the bank puts into contacting the customer. For low
recovery amounts (Level 0), the bank just adds the customer’s contact
information to their automatic dialer and emailing system. For higher
recovery strategies, the bank incurs more costs as it leverages human
resources in more efforts to obtain payments. Each additional level of
recovery strategy requires an additional $50 per customer so that customers in the Recovery Strategy Level 1 cost the company $50 more than
those in Level 0. Customers in Level 2 cost $50 more than those in Level
1, etc.


Question: does the extra amount that is recovered at the higher strategy
level exceed the extra $50 in costs? Please build a model to investigate
the cost-benefit of the strategy at Level 1 (with a threshold $1000). You
should

• Build a model to fit the scenario of the recovery strategy choice of
the bank.

• Work on the data (bank_data.csv) to get a cost-benefit result.
• Write up a report to illustrate the banking recovery strategy, e.g.,
whether it is worthy to pursue Level 1 v.s. Level 0.
