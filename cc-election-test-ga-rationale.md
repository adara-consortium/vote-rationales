# Project Nova Funding Proposal

## Summary 

The Adara Consortium votes the treasury withdrawal action (“931a13c62bd2645feaff143302170b41a49dd3bc9527bee00b3e646fbd50ca41”) for Project Nova to be unconstitutional.

## Rationale Statement

This treasury withdrawal action is in direct contravention of Article III Section 5 of the Cardano Blockchain Ecosystem Constitution whereby it is stated that, “the content of every on-chain governance action must be identical to the final off-chain version of the proposed action”. The off-chain part of the proposal, that is the metadata file containing the rationale, that is displayed on governance pages like GovTool and Tempo details a treasury withdrawal request of 146,000,000 ada. However, the on-chain submission contains a withdrawal request of 149,000,000 ada, representing a 3 million ada discrepancy between the on-chain and off-chain proposal.

## Precedent Discussion

While there have been instances in past where governance action proposals have had mismatching hashes between the on-chain and off-chain proposal metadata, this is the first instance where the on-chain and off-chain hash of a proposal metadata has matched but the on-chain proposed change has differed. Treasury withdrawal and parameter change submissions on-chain require additional input fields specifying the on-chain change being proposed, in this case, the value of the proposed withdrawal in lovelaces (149,000,000,000,000). Whether intentional or not in this instance remains unknown, however, it is a potential attack vector that CC members and DReps should be aware of.

## Counterargument Discussion

With the exception of the standout violation of Article III Section 5, the proposal does meet all other constitutional requirements. As per other parts of Article III Section 5, it follows “a standardized and legible format including a URL and hash of all documented off-chain content” and includes “at a minimum, a title, an abstract and a reason for the proposal”, although absent any relevant supporting materials. While not a constitutional requirement, the metadata is hosted on IPFS, and it is acknowledged that utilising a more immutable method of storage provides stronger guarantees regarding the content of the proposal not changing during the governance action lifetime and beyond.

At the time of the proposal there is a 350 million ada net change limit in effect of which 114 milllion ada has already been withdrawn, leaving 236 million ada remaining. The proposal, whether intended to be for 149,000,000 or 146,000,000 is within the remaining net change limit and so it does fall within the TREASURY-02a, TREASURY-03a and TREASURY-04a Guardrails. This similarly applies to Article IV Section 3, “withdrawals from the Cardano Blockchain treasury that would cause the Cardano Blockchain treasury balance to violate the then applicable net change limit shall not be permitted”. In this instance, it is not the case.

## Conclusion

The Adara Consortium consider this proposed governance action to be unconstitutional. Whether or not the discrepancy between on-chain and off-chain ada values was intentional or not is not the concern of the Constitutional Committee. At best, it demonstrates a lack of thoroughness in the application process, at worst, it represents a malicious attempt to undermine the governance process and an attempt to access additional funds through an act of deception. When assessed next to Constitution, this is a failure to adhere to Article III Section 5, plain and simple.

## Internal Vote

- Constitutional: 0
- Unconstitutional: 4
- Abstain: 0
- Did Not Vote: 2
- Against Voting: 0

## References

Cardano Blockchain Ecosystem Constitution
ipfs://bafkreiazhhawe7sjwuthcfgl3mmv2swec7sukvclu3oli7qdyz4uhhuvmy

Project Nova Treasury Withdrawal Proposal Metadata
ipfs://bafkreiew3wxdtgytkrtg3h7jzlspgfiktpxz7x3onz2yaa345ekrg7jz5q

Governance Action on the SanchoNet Explorer
https://sancho.cardanoconnect.io/govern/gov_action_proposal/19

## Authors

Adara Consortium

