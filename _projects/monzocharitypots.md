---
name: Monzo Charity Pots
tools: [Sketch, Prototyping]
image: /img/monzoHero.jpg
description: How do you make it easy for Monzo customers to donate to charity straight from the Monzo app on iPhone and Android? That's the problem I'm trying to solve.
---

How do you make it easy for Monzo customers to donate to charity straight from the Monzo app on iPhone and Android? That's the problem I'm trying to solve.

### Identifying the Problem

This problem was brought to my attention via [a tweet by Stevie Buckley](https://twitter.com/StevieBuckley/status/971724116310089729), who was looking for an easy way to donate to charity from his Monzo account.

<center>
  <blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Yo <a href="https://twitter.com/monzo?ref_src=twsrc%5Etfw">@monzo</a>. Sort me out with a function that lets me arrange a direct debit that takes the contents of my Coin Jar and donates it to a charity of my choosing on a monthly basis. Cheers.</p>&mdash; Stevie Buckley (@StevieBuckley) <a href="https://twitter.com/StevieBuckley/status/971724116310089729?ref_src=twsrc%5Etfw">March 8, 2018</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
</center>

Because the contents of a Coin Jar/Pot in Monzo can be variable, this is a problem that cannot currently be solved by Direct Debits, as they involve the transfer of a fixed amount each month to the charity.

A [quick search of the Monzo Community](https://community.monzo.com/search?q=charity) forums found other Monzo customers wanted a way to easily donate to charity. And [research into the methods](https://www.statista.com/statistics/420137/charitable-donation-giving-uk-england-by-means/) of donation showed that approximately 25% of people currently donate to charity through Direct Debit.

### Introducing Charity Pots

Charity Pots are the easiest way to donate to charity from your Monzo bank account. Once you've chosen the charity you want to donate to, the total value of your Pot is donated straight to them every month. No direct debits to worry about, just donate what you can each month.

### The Process

I spent an hour or so working on the initial prototype, entirely in Sketch 49. Using screenshots from the iOS app itself as the basis, I was able to recreate and extend the current Pot creation flow to inform about Charity Pots and add simple functionality on the customer's side to enable a Charity Pot and choose a charity.

### Assumptions

- Monzo customers would like to have a pot that automatically donates its contents to a charity of their choice each month
- That the full contents of the pot will be donated each month
- That the contents of all pots will be aggregated and donated on the same day each month, to save any potential charges to Monzo
- As donations are made from the Pot, and not from the account itself, a set date for transfer can be used, as the whole value of the pot will be transferred, meaning no shock when money “disappears” from your account.
- Creating a Charity Pot uses the same flow as creating a standard Pot, with an additional option on the set up screen.

### Initial Prototype

Based on the above assumptions and the current visual design of the Monzo application on iOS, I’ve put together the following prototype to click through to show the flow.

Link to prototype: [https://sketch.cloud/s/j4v1a/all/design/account-view-add-pot/play](https://sketch.cloud/s/j4v1a/all/design/account-view-add-pot/play)

### Initial Community Feedback

I posted my initial prototype and assumptions to the Monzo Community forum. You can read the thread here: https://community.monzo.com/t/pots-improvement-charity-pots/34270.

Feedback on the feature suggestion and prototype was mainly positive, [with one or two people](https://community.monzo.com/t/pots-improvement-charity-pots/34270/21?u=smutchings) even thinking that this was a product feature Monzo was about to work on. Oops!

### Potential Future Improvements

- Add option to add a custom charity, in case there are smaller or lesser-known charities that are not on the list
- Add option for a certain amount (fixed £ or % based on income/balance) to be transferred to the Charity Pot each month.
- Add way to calculate aggregate total donation values across the network, so Monzo and their customers can see how much is being donated where.
- Bring in improvements suggested by the Monzo community.

### Support This Feature

If you think this feature is a good idea, you can like it and feed back on it over on the Monzo Community Forums. I'm active in the thread, so will reply to any and all suggestions.

Link: [https://community.monzo.com/t/pots-improvement-charity-pots/34270?u=smutchings](https://community.monzo.com/t/pots-improvement-charity-pots/34270?u=smutchings)
