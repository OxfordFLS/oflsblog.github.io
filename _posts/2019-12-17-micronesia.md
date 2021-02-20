
---
layout: post
title:  "From Micronesia to Blockchain"
author: Irina & Vaibhav
categories: [blockchain]
image: assets/images/pink.png
---

In the Micronesian island of Yap, there is no 'money' in the conventional sense. There are only Rai stones; these are large, round stones which are used as currency, based on an oral history of ownership. In this civilization, it is known who 'owns' a Rai stone, and when the owner makes a purchase, the ownership of the stone is transferred and the information about who is the new owner circulates among the islanders. For heavy stones, no physical movement is even required; as long as it has been recorded orally (and in the memories of the islanders) that the owner has changed, the transaction is complete.

This is how blockchain works, according to Laurence Kirk of Extropy, conductor of the Blockchain for Beginners Workshop at the Oxford Foundry. Its core idea is to create a decentralized system of trust, where information about transactions goes around on the basis of a 'gossip network', rather than by using a central authority such as a bank. Just as a bank would record transactions in a ledger, the blockchain is based on the existence of a 'public shared ledger', where all transactions are recorded on the basis of consensus of all of the users on the blockchain --- much like the oral history system on Yap. This means that the transactions recorded on the blockchain have been verified by the rest of the users (consensus), and that you as a user can yourself check the history of the transactions that have occurred (e.g. the several transfers of ownership over a coin), and verify who the final owner is.

Laurence then explained the concepts of cryptography and 'hash functions', which are core to blockchain technology; transactions are encrypted by the user sending them out, and decrypted by the recipient, thus verifying the identity of the user you're transacting with and ensuring that the data you receive has not been tampered with. Although there is a verification of the user's identity, that needn't correspond with said person's real-life credentials, hence offering a pseudo-anonymity to blockchain users. And how is the system updated with new transactions in a way that guarantees consensus? While the answer differs among platforms, the most prominent method is called 'Proof of Work', and it involves a race for solving a mathematical puzzle, also known as 'mining'. To update the system, you have to produce a new 'block' to be added to the end of the 'chain'. To produce a new block, you have to gather data from the transactions that have happened since the last 'update', add them up in an equation, and make a guess about a number you need to add to that equation; the figure from this whole equation is inputted in the 'hash function', which spits out a number, and if that number is low enough (thanks to the guess that you made), you have won the race. The low number that all miners are targeting is known, so when a miner claims to succeed it is easy for all users to verify that he/she has indeed succeeded, thus achieving consensus about the new block. What's in it for the miners? The successful miner gets a small fee for every transaction he/she includes in the new block.

What about smart contracts? These can be found primarily on the Ethereum blockchain (but have spread to other blockchains as well). As Laurence described it, each 'node' on the Ethereum blockchain functions just as any other blockchain, but also has a 'virtual machine', a network of computers, which runs smart contracts. These are applications made up from pieces of code, which do not have legal weight in the 'real world' unless you provide for it (presumably with a clause in a real-life contract). They work in the same manner as any blockchain transaction: A codes a smart contract and shares it on the network; B likes the contract and 'calls' a function in the code by adding an input in the function, using her 'fingerprint' to verify that the transaction is from her. Then this information gets mined and 'gossiped' around the network, thus is confirmed as having taken place in the 'oral history' of the blockchain. Finally, a smart contract can hold Ether, the coin of the Ethereum blockchain, or other cryptocurrencies as the case may be, and thus let people transfer value through it. Usually, after creating the code for a smart contract, the creator cannot further interfere with it.

Later in the workshop, Laurence proceeded to show us how a simple smart contract is made. This was done on the 'Remix' website, which provides a compiler for code written in the Solidity language; this is the coding language designated for creating smart contracts on the Ethereum blockchain. After guiding us through a practice contract he had prepared for us, and explaining the main steps one should undertake when coding a smart contract (such as making the contract public, adding security by restricting who can modify the functions, etc.), Laurence invited us to create our own token (coin) on Remix! He helped us through the basic steps for kickstarting our new smart contract, then let us work on our laptops to refine the details and personalize the token we had created. The main idea was to create a coin, give it a name and deploy it for the world to see. The hands-on work continued until the last workshop, where we further developed our token, attempting to make it compliant with Ethereum.

Although blockchain technology isn't yet as efficient and fast as centralized systems (the blockchain's constant replication of data and transactions may take several minutes compared to the instantaneous bank transactions), it offers an enticing alternative for users seeking a decentralized approach, as well as exciting prospects for what might come ahead. Learning about it in the new facilities of the Oxford Foundry, in both an informative and then an applied fashion, was a rewarding experience, both for experienced and completely inexperienced students.

About the Author:

_Irene Tsoutsou is a Legaltech Researcher at OFLS and a Masters in Law and Finance candidate (2020), University of Oxford._

About the Editor:

_Vaibhav Manchanda is an Economics graduate from the University of Chicago, and a BA Jurisprudence candidate (2021), University of Oxford_