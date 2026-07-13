---
layout: ../../layouts/MarkdownPageLayout.astro
title: Now
---

# Now

I am the author of the Solana Changelog weekly newsletter on [X](https://x.com/solana_devs/articles) and on [Solana.com](https://solana.com/news/category/developers). And I am also the host of the weekly Solana Changelog stream on X and [Youtube](https://www.youtube.com/@readylayer1). I am always looking for new engineering work to feature and interesting Solana projects. DM me on [@readylayerone](https://x.com/readylayerone).

## Projects

#### 1. Handshake (Web, CLI)

<a class="project-link" href="https://github.com/datasalaryman/handshake" target="_blank" rel="noreferrer">
  <img src="https://opengraph.githubassets.com/1/datasalaryman/handshake" alt="Handshake repository preview" loading="lazy" />
  <span>github.com/datasalaryman/handshake</span>
</a>

This is an attempt to learn [Vector](https://github.com/blueshift-gg/vector) a project by [Dean](https://x.com/deanmlittle) from [Blueshift](https://x.com/blueshift). Vector is program that allows for offchain signing without durable nonces. Butchering it simply, it turns the actions by all previous signers as cryptographically signed actions on escrow accounts. The latest signer ultimately executes the transaction that runs all the actions.

I used Vector to build a peer-to-peer swaps platform where makers can set swap rate arbitrarily. Makers also have the option to revoke a swap offer if the counterparty no longer wants to swap.

This project is available both on the web and as a CLI. The cool thing about this is that swap offers are completely stateless, and only requires the maker to send a hash containing the offer details to the taker offchain. The hash iteself is encrypted so that only the maker and the taker can see the swap offer details.

#### 2. Solana Changelog Dashboard (Web)

<a class="project-link" href="https://github.com/datasalaryman/solana-changelog" target="_blank" rel="noreferrer">
  <img src="https://opengraph.githubassets.com/1/datasalaryman/solana-changelog" alt="Solana Changelog repository preview" loading="lazy" />
  <span>github.com/datasalaryman/solana-changelog</span>
</a>

Inspired by tooling I've built to make my research for Solana Changelog easier, I've decided to build a companion dashboard application to the newsletter. Here you'll be able to see all the pull requests of all the Solana projects I cover. It requires a Github sign-in to allow for fetching of Github data without reaching API limits.

#### 3. Interdash (Web, Mobile and CLI coming soon!)

<a class="project-link" href="https://github.com/datasalaryman/interdash" target="_blank" rel="noreferrer">
  <img src="https://opengraph.githubassets.com/1/datasalaryman/interdash" alt="Interdash repository preview" loading="lazy" />
  <span>github.com/datasalaryman/interdash</span>
</a>

I use an RSS reader called [Newsboat](https://newsboat.org/) for my daily news reading. The problem is that when I want to check on updates on my phone or on the web, I have to go back to the TUI in order to see if there are feed updates.

The goal of interdash is to support multi-platform RSS viewing while pointing to the same state - i.e. a Postgres database I control. That way, any change I make on the Web gets reflected on the CLI and Mobile app.

It's a passion project of mine that I care deeply about and hope to release by the end of the year.
