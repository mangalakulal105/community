---
title: SparkLend Gnosis - Update sxDAI Oracle Onboarding Parameter - April 15, 2024
summary: Update the "Oracle" parameter for onboarding sxDAI (Savings xDAI).
discussion_link: https://forum.makerdao.com/t/apr-4-2024-proposed-changes-to-sparklend-for-upcoming-spell/24033
parameters:
    input_format: single-choice
    victory_conditions:
        - { type : plurality }
    result_display: single-vote-breakdown
version: v2.0.0
options:
   0: Abstain
   1: Yes
   2: No
start_date: 2024-04-15T16:00:00
end_date: 2024-04-18T16:00:00
---
# Poll: SparkLend Gnosis - Update sxDAI onboard parameters - April 15, 2024

The Governance Facilitators have placed a Governance Poll into the voting system on behalf of Spark Protocol and the Stability Facilitators. This Governance [Poll](https://manual.makerdao.com/governance/governance-cycle/weekly-governance-cycle#weekly-governance-cycle-definitions-mip16c1) will be active for three days beginning on Tuesday, April 15 at 16:00 UTC.

**This is a binary vote.**
- **You may vote for a single option.**
- **You should vote for the option which you prefer.**
- **If you would accept either option, you should vote 'Abstain'.**

## Review

This poll allows the MakerDAO governance community to signal their support or opposition to updating the "Oracle" parameter for sxDAI (Savings xDAI) onto SparkLend on Gnosis. The onboarding will occur with the parameters below:

### Spark Parameters

* Token: sxDAI
* Token Address: [0xaf204776c7245bF4147c2612BF6e5972Ee483701](https://gnosisscan.io/address/0xaf204776c7245bF4147c2612BF6e5972Ee483701)
* Oracle: Set to a fixed rate of 1 USD
* Oracle Provider: N/A
* Borrow Enabled: No
* Collateral Enabled: Yes
* [Efficency Mode](https://docs.spark.fi/defi-infrastructure/sparklend#efficiency-mode-emode): No
* [Isolation Mode](https://docs.sparkprotocol.io/developers/features/isolation-mode) Enabled: No
* Isolation Mode Debt Ceiling: N/A
* Loan To Value: 70%
* Liquidation Threshold: 75%
* Liquidation Bonus: 6%
* Liquidation protocol fee: 10%
* [Supply cap](https://docs.spark.fi/defi-infrastructure/sparklend#supply-and-borrow-caps): 40,000,000 sxDAI

Please review the proposal [thread](https://forum.makerdao.com/t/apr-4-2024-proposed-changes-to-sparklend-for-upcoming-spell/24033) for more information about this proposed onboarding.

A risk evaluation has been provided by BA Labs and can be found [here](https://forum.makerdao.com/t/apr-4-2024-proposed-changes-to-sparklend-for-upcoming-spell/24033/6). 

## Outcomes

**If the votes for the 'Yes' option exceed the votes for the 'No' option then the following actions will be taken:**
* sxDAI (Savings xDAI) will be onboarded to SparkLend Gnosis with updated parameters via a future executive vote.
* It is expected that this executive vote will take place within 30 days of this poll passing, absent external factors.
* If the executive vote passes, then these changes will become active in Spark Protocol after the [GSM Pause Delay](https://manual.makerdao.com/parameter-index/core/param-gsm-pause-delay) has expired.

**If the votes for the 'No' option equal or exceed the votes for the 'Yes' option then no further action will be taken at this time.**

---

## Resources

Further information about Spark Protocol can be found at its [Documentation Hub](https://docs.sparkprotocol.io/hub/).

If you are new to voting in the Maker Protocol, please see the [voting guide](https://manual.makerdao.com/governance/voting-in-makerdao/on-chain-governance) to learn how voting works.

Additional information about the Governance process can be found in the [Maker Operational Manual](https://manual.makerdao.com).

To add current and upcoming votes to your calendar, please see the [MakerDAO Governance Calendar](https://manual.makerdao.com/makerdao/calendars/governance-calendar).