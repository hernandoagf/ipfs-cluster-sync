---
title: Ratification Poll for MIP Amendment Subproposal (MIP102c2-SP9) - June 12, 2023
summary: This subproposal incorporates the Bug Bounty Program (originally MIP64) into MIP107.
discussion_link: https://forum.makerdao.com/t/mip102c2-sp9-mip-amendment-subproposal/20640
parameters:
    input_format:
        type: single-choice
        abstain: [0]
    victory_conditions:
        - {
            type: 'and',
            conditions: [
                { type : plurality },
                { type : comparison, comparator : '>=', value: 10000 }
            ]
        }
        - {type : default, value : 2 }
    result_display: single-vote-breakdown
version: v2.0.0
options:
   0: Abstain
   1: Yes
   2: No
start_date: 2023-06-12T16:00:00
end_date: 2023-06-26T16:00:00
---
# Ratification Poll for MIP Amendment Subproposal (MIP102c2-SP9) - June 12, 2023

The Governance Facilitator has placed a ratification poll into the [voting system](https://vote.makerdao.com/polling) as part of the responsibilities defined in [MIP51](https://mips.makerdao.com/mips/details/MIP51). This Governance [Poll](https://mips.makerdao.com/mips/details/MIP51#MIP51c2) will be active for fourteen days beginning on Monday, June 12 at 16:00 UTC.

**This is a binary vote.**
- **You may vote for a single option.**
- **You should vote for the option which you prefer.**
- **If you would accept either option, you should vote 'Abstain'.**

## Review

The community may vote in this poll to express support or opposition to MIP102c2-SP9 being accepted and implemented in the Maker Protocol.

A brief summary of this proposal has been provided by the MIP Author and is shown below:

*This subproposal ensures continuity of the bug bounty program (i.e., MIP64) by incorporating it into the Scopes framework.*

Please review the links below to inform your position on this proposal before voting.
* [Canonical Proposal Version](https://github.com/makerdao/mips/blob/98a7c6f6a009fffa692ceaa7c04f0b4a8da750df/MIP102/MIP102c2-Subproposals/MIP102c2-SP9.md)
* [Latest Proposal Version](https://mips.makerdao.com/mips/details/MIP102c2SP9)
* [Proposal Discussion Thread](https://forum.makerdao.com/t/mip102c2-sp9-mip-amendment-subproposal/20640)
* [Amendment Pull Request](https://github.com/makerdao/mips/pull/898)

## Outcomes

This poll implements a **Minimum Positive Participation** value. The Minimum Positive Participation is currently set to **10,000 MKR**.

**If the votes for the 'Yes' option exceed the votes for the 'No' option AND the votes for the 'Yes' option exceed 10,000 MKR, then the following actions will be taken:**
* The Governance Facilitator will confirm its passage by marking the proposal **Accepted** on the [MIPs portal](https://mips.makerdao.com/mips/list) and across all other relevant governance mediums.
* Any further work required to implement the proposal will be tasked to the relevant [Ecosystem Actors](https://mips.makerdao.com/mips/details/MIP106#7-4-2-1a-).

**Otherwise, this proposal will be marked as rejected per [MIP51](https://mips.makerdao.com/mips/details/MIP51#mip51c2-ratification-poll).**

---

## Resources

[MIP51: Monthly Governance Cycle](https://mips.makerdao.com/mips/details/MIP51) describes this type of poll and its position and significance within the rest of the governance cycle.

If you are new to voting in the Maker Protocol, please see the [voting guide](https://manual.makerdao.com/governance/voting-in-makerdao/on-chain-governance) to learn how voting works.

Additional information about the Governance process can be found in the [Maker Operational Manual](https://manual.makerdao.com).

To add current and upcoming votes to your calendar, please see the [MakerDAO Governance Calendar](https://manual.makerdao.com/makerdao/calendars/governance-calendar).


