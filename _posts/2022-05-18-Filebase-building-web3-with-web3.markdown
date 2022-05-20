---
layout: post
title: Filebase is Building Web3 with Web3
description: Filebase: Building Web3 with Web3
date: 2022-05-20 15:01:35 +0530
image: '/images/filebase.png'
tags: [Dnet, Web3, IPFS]
---
Decentralized storage offers a different way of thinking about how to store and access your information. In this model, data is distributed across nodes that are geographically distributed and connected through a peer-to-peer network. This is very different from a traditional cloud model where data is siloed into regions that are prone to outages, and failure. By contrast, peer-to-peer networks are resilient to catastrophic events such as natural disasters, fires, or infrastructure compromise.

Filebase is the world’s first object storage platform powered by decentralized storage networks, unifying multiple networks under a single S3-compatible API to make decentralized storage accessible and easy to use. Its proprietary edge-caching technology achieves industry-leading performance when writing and fetching data to and from Web3, making it a highly-secure, geo-redundant alternative to traditional cloud storage at a fraction of the costs.

<h2>The Story of Filebase</h2>

CEO Joshua Noble and COO Zac Cohen both come from backgrounds in the cloud computing world. In their careers, they had been exposed to AWS and the cost of centralized cloud storage, despite the weaknesses that the centralized cloud faces, such as security holes and crippling outages.

In 2019, they co-founded Filebase with the vision of unifying multiple networks under a single S3-compatible API to make decentralized storage simple, accessible, and as easy to use as Amazon. By building a bridge that makes it possible for anyone to leverage the unique qualities of decentralized networks, Filebase is an easy on-ramp (Layer-2) for users of all skill levels and knowledge backgrounds to be able to utilize and build with blockchain-based solutions.

Filebase has put in years of steady work to simplify all of the complexities of blockchains and cryptocurrency to make an object storage platform that is as familiar as Amazon S3, but with a completely different type of backend architecture. It manages all aspects of the data storage layer on behalf of its users such as minimum file or sector sizes, data retention issues, or requiring special software, skill sets and tokens required to utilize decentralized networks.

<h2>IPFS Pinning Services</h2>

Within the IPFS ecosystem, there are a variety of public gateways available for uploading files, but due to the IPFS garbage collection process, unless a file is explicitly pinned it will be removed the next time the garbage collection process runs. To solve this problem, numerous pinning services have emerged.

<h2>Bridging the Gaps</h2>

Filebase spent a lot of time researching and analyzing these other pinning services. Since its flagship S3-compatible API has processed over 1 billion files through the platform, the project started engineering work around how to offer a dramatically different type of IPFS pinning service. Here is what it found:

<li>Most IPFS pinning providers use Amazon S3 and other Web2 centralized object storage services under the hood. The "data store" of an IPFS server can be pointed to S3 using a simple plugin.</li>
<li>Because AWS S3 is being used, providers are charging upwards of ~$150 per TB.</li>
<li>If AWS goes down, IPFS servers go down too. Unless the data has been cached somewhere, user’s IPFS CID links are no longer accessible.</li>

Source : [IPFS blog](https://blog.ipfs.io/2022-04-14-filebase/)
