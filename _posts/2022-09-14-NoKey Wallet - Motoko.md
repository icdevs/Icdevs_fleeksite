---
layout: post
title:  "Bounty - ICDevs.org NoKey Wallet - Motoko"
date:   2022-09-14 00:00:00 -0600
categories: "Bounties"
author: Austin Fatheree
---

# Motoko NoKey Wallet - #27a

## Current Status: Assigned

* Discussion (10/21/2022)
* Ratification 
* Open for application
* Assigned 
* In Review 
* Closed 

[Forum Link - Discussion](https://forum.dfinity.org/t/icdevs-org-bounty-27a-nokeywallet-motoko-up-to-10k/16054)

## Bounty Details

* Bounty Amount: $5,000 USD of ICP at award date - $5000 USD of ICP Match Available
* ICDevs.org DFINITY Foundation Grant Match Available: $2000 USD of ICP at award time - (For every ICP sent to 6e8afebab59f703356e189297e3f49fbe18ace5150ccc43f74f30ceb3f6b5ece, ICDevs.org will add $40 USD of ICP at award date to the bounty, up to the first 125 ICP donated, After 125 ICP, donations to the above address will add .25 ICP to this issue and .75 ICP to fund other ICDevs.org initiatives)
* Project Type: Team
* Opened: 09/05/2022
* Time Commitment: Weeks
* Project Type: Library
* Experience Type: Intermediate - Motoko;

## Description

This motoko class is allows for canisters to hold assets on other EVM based chains.

This bounty gives the opportunity to

* learn motoko
* learn about signing transactions
* learn about evm transactions
* learn about t-ecdsa
* learn about managing nonces

The NoKey wallet is a stable class that any Motoko canister can add that will allow it to act as a wallet for Evm-based chains.  It should implement the following features:

* Derive a t-ecdsa key according to a consistent derivation scheme.
* Save that derivation for the user in a (Nat,Text) pair.
* Sign Evm-based transactions with a t-ecdsa key selected by the wallet owner. The transaction will be passed in as part of the sign function sign(rawtrx, {#derivation([Nat], #named(id)}, nonce, other Info?, saveHistory)
* Keep a history of signed transactions.
* Enable clearing the history
* Provide an upgrade strategy, preferably using stable vars.
* Suggest and follow a safe nonce generation/management scheme that protects the user.

## To apply for this bounty you should:

* Include links to previous work writing tutorials and any other open-source contributions(ie. your github).
* Include a brief overview of how you will complete the task. This can include things like which dependencies you will use, how you will make it self-contained, the sacrifices you would have to make to achieve that, or how you will make it simple. Anything that can convince us you are taking a thoughtful and expert approach to this design.
* Give an estimated timeline on completing the task.
* Post your application text to the Bounty Thread

## Selection Process

The ICDevs.org developer's advisors will propose a vote to award the bounty and the Developer Advisors will vote.

## Bounty Completion

Please keep your ongoing code in a public repository(fork or branch is ok). Please provide regular (at least weekly) updates.  Code commits count as updates if you link to your branch/fork from the bounty thread.  We just need to be able to see that you are making progress.

The balance of the bounty will be paid out at completion.

Once you have finished, please alert the dev forum thread that you have completed work and where we can find that work.  We will review and award the bounty reward if the terms have been met.  If there is any coordination work(like a pull request) or additional documentation needed we will inform you of what is needed before we can award the reward.

## Bounty Abandonment and Re-awarding

If you cease work on the bounty for a prolonged(at the Developer Advisory Board's discretion) or if the quality of work degrades to the point that we think someone else should be working on the bounty we may re-award it.  We will be transparent about this and try to work with you to push through and complete the project, but sometimes, it may be necessary to move on or to augment your contribution with another resource which would result in a split bounty.

## Funding

The bounty was generously funded by the DFINITY Foundation. If you would like to turbocharge this bounty you can seed additional donations of ICP to 6e8afebab59f703356e189297e3f49fbe18ace5150ccc43f74f30ceb3f6b5ece.  ICDevs will match the bounty $40:1 ICP for the first 125 ICP out of the DFINITY grant and then 0.25:1 after that.  All donations will be tax deductible for US Citizens and Corporations.  If you send a donation and need a donation receipt, please email the hash of your donation transaction, physical address, and name to donations@icdevs.org.  More information about how you can contribute can be found at our [donations page](https://icdevs.org/donations.html).


## FYI: General Bounty Process

### Discussion

The draft bounty is posted to the DFINITY developer's forum for discussion

### Ratification

The developer advisor's board will propose a bounty be ratified and a vote will take place to ratify the bounty.  Until a bounty is ratified by the Dev it hasn't been officially adopted. Please take this into consideration if you are considering starting early.

### Open for application

Developers can submit applications to the Dev Forum post.  The council will consider these as they come in and propose a vote to award the bounty to one of the applicants.  If you would like to apply anonymously you can send an email to austin at icdevs dot org or sending a PM on the dev forum.

### Assigned

A developer is currently working on this bounty, you are free to contribute, but any splitting of the award will need to be discussed with the currently assigned developer.

### In Review

The Dev Council is reviewing the submission

### Awarded

The award has been given and the bounty is closed.

# Matches

DFINITY Foundation Grant: - $5000 USD of ICP at award date


[Other ICDevs.org Bounties](https://icdevs.org/bounties.html)

