---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

In this post, we would like to introduce *Liberum Oratio*, our uncensorable alternative to Patreon that's running on the Ethereum blockchain.


## What is it?

*Liberum Oratio* brings the core functionality of sites like Patreon and SubscribeStar to the Blockchain. Our goal is to enable independent content creators to be crowdfunded by their fans via regular payments. It is open to anyone, without restrictions, and is built to be maximally censorship resistant.

The system consists of two parts: The core part is a [smart contract](https://en.wikipedia.org/wiki/Smart_contract) running on the [Ethereum Blockchain](https://en.wikipedia.org/wiki/Ethereum). It implements the core functionality of the system: All relevant data is saved on the Blockchain and all the money flow is handled by the Blockchain. We stand by the principle *your money is your money*. On our system, you and only you can decide to deposit, pledge, revoke or withdraw at any time. Since you interact with the Blockchain directly, we never touch *any* of your money.

The second part is a website. [Blockchain technology](https://en.wikipedia.org/wiki/Blockchain) is as of yet very limited in terms of user experience. In fact, the technical know-how required to interact with a smart contract is huge. That's why we have built a website that makes this as easy as possible. It can show you what's happening on the Blockchain and let you use all the features of our smart contract with a few button clicks. Think of it like a front-end that takes data from somewhere else and displays it in a pretty way. Two points are important: First, if you go through our website, we still don't have any control over your money (or your private keys). Any action you do still goes directly from you to the Blockchain. Second, because the Blockchain is completely open, *anyone* can build their own front-end website to the same smart contract. Thus, at no point do we hold any authoritative power over the system.

Also we don't charge fees :)

## What can I do on your system?

If you are a content creator, you can use our system to:
- Create and maintain a profile
- Define ways for your supporters to fund you (e.g. "Once per month" or "Once per video I upload to YouTube"), as many as you want, each with configurable minimum amount.
- Charge your supporters according to what you've defined.
- Receive one-time donations from supporters.
- Withdraw money to your crypto wallet at any time.
- Interact with your supporters via features such as community feed, supporter-only chat or Q&A.

If you are a content consumer, you can use our system to:
- Browse and find your favorite creators.
- Deposit money from your crypto wallet to the platform (it remains under your full control).
- Pledge money to creators by selecting any of the funding types they have defined.
- View, cancel and update your pledges and withdraw money at any time.
- Give one-time donations to creators.
- Interact with creators via supporter-only chat or Q&A.

## Demo Video
[![Demo Video](https://img.youtube.com/vi/jeOj2Wy3GFc/hqdefault.jpg)](https://www.youtube.com/watch?v=jeOj2Wy3GFc)

## Why should I use it?

While classic websites like Patreon can work well, they are inherently centralized, which means that there is someone in the system (usually the company that built the website) that has authoritative power over everything that's happening. A centralized service with a set of vague terms of service can decide on a whim to restrict, demonetize or outright ban any creator for whatever reason they want. Most of these services start out with laudable goals (such as "creators first"), but when media pressure starts to rise or money runs short, those priorities inevitably shift. In short, *relying on a centralized system for your money flows will almost surely go wrong*. We are here to fix this.

*Liberum Oratio* was built from the ground up to be censorship resistant. Every part of the system is designed such that no matter what happens, the system keeps functioning, money keeps flowing and open participation is guaranteed. This starts by building on top of peer-to-peer Blockchain technology, which guarantees openness at a core level, and it ends with making sure that nobody, not even we, can gain any authoritative power over anyone else using the system. This relentless focus on guaranteeing neutrality is what differentiates us from any other crowdfunding system, even from those that make use of Blockchain themselves.

So if you want to be part of a system that is not subject to the political affiliations of a trust & safety team, you might just be interested.

## Wait... Zero Fees?!

Too good to be true? Of course. As good as it gets? Definitely! Let us explain:

There are two kinds of fees in a crowdfunding system. First are *transaction fees*. Those are fees that have to be paid to move money from A to B. These are charged by your bank, credit card issuer and services like PayPal. This is no different on the Blockchain. For every action on the Blockchain, you have to pay transaction fees. The difference is that on the Blockchain, they are not dependent on the amount of money you send, but simply a function of how much work you're causing for the system. These fees go to the Blockchain miners, in return for the fundamental task of guaranteeing the security of the Blockchain via the [proof of work algorithm](https://en.wikipedia.org/wiki/Proof-of-work_system). For a typical user of our system, we expect these fees to be well below a dollar a month, maybe even a dollar a year. It is slightly more for creators, especially if they have lots of supporters, but nowhere near the level of centralized services.

The second type of fees are fees that the platform itself charges. For example, Patreon and SubscribeStar both take a certain percentage cut off whatever money creators get from their supporters. *We don't do that*. Why? Part philanthropy, part marketing, part to eliminate competition, but most importantly, because if we did take a fee (and maybe even built in a mechanism to adjust that), then we'd essentially have authoritative power over the system. (For example, we could just shut it down by raising the fees to 100%.) Since our core principle forbids any party in the system from gaining *any* special status, fees just don't make the cut. That's how far we go to guarantee neutrality!

## What is censorship resistance?

Censorship resistance is the core principle upon which our system is built. To us, it means specifically that the system can be used by anyone for any purpose without anyone else being able to interfere. This includes other participants, financial processors, governments, hackers and even us, the makers of the system. And this is not guaranteed by us giving our word, but instead this is built into the system at its core. Yes, that's right, not even we will have the ability to restrict transactions, ban people or shut the system down. Every engineering decision while building Liberum Oratio has been made with this in mind. In a section below we'll have a look at each possible attack against our system and how our design mitigates it.

## What's the difference to...

### ...other Blockchain Patreon alternatives?

We are not the first ones to create a crowdfunding service based on cryptocurrency, nor do we have the largest set of features. What is unique to us is that we can offer these features while being completely censorship resistant. None of these other systems has that. Oh and did we mention zero fees?

### ...things like [minds.com](https://www.minds.com/) or [BAT (Basic Attention Token)](https://basicattentiontoken.org/)?

First of all, we love minds.com! Check it out, it's awesome. Luckily, we provide a different service. In fact, there are two main differences between Liberum Oratio and things like Minds and BAT: First, we do not use a special token. On our system, what flows is directly money (Ether). Think of a Poker game. Minds and BAT are like a casino, where you have to exchange money for chips (tokens) first, then you play for these chips. At the end, you have to exchange them again for money. We are more like a backroom home-game between suburban dads. What gets put on the table and played for is money. At any point, you can get up and walk away, no need to exchange anything. By not using a token, we remove an entire layer of complicated indirection, which means it's more transparent and easier to use for everyone.

The second major difference is in the way money flows. On these platforms, money (or tokens) flow when there is direct and active interaction of a supporter with a creators content. I.e. you might watch a creator's video or read their post and by doing that you'll transfer a bit of value to them. Our model is different, much more passive. We enable any supporter to establish a pledge to a creator, agreeing to transfer money to them automatically in a regular fashion, whether they actively consume their content or not. This provides the creator with a much more stable and predictable income. Both systems have their place and we see ours very much as a complement to the others.

## Why Ethereum? Why not Bitcoin?

[Ethereum](https://en.wikipedia.org/wiki/Ethereum) is the second largest cryptocurrency behind Bitcoin. In terms of use as money, decentralization, openness, neutrality and security, Ethereum matches Bitcoin feature by feature. The reason we use Ethereum is because other than Bitcoin, it has the ability to run Turing-Complete [smart contracts](https://en.wikipedia.org/wiki/Smart_contract). A smart contract is essentially a piece of software that runs on the Blockchain, and thereby runs in a decentralized fashion. Our system is such a smart contract. This is why we are able to say that *all relevant operations happen directly on the Blockchain*. We have no influence over them. Once the smart contract is deployed (and it is right now), there is no way to change or remove it. Its code is open source, so once you're satisfied that it does what we claim it does, you will be able to use the system without anyone ever being able to stop you. Even when we want to upgrade the system, we can only provide a second, new smart contract and then each person will be able to choose whether to migrate to the new one or stick with the old one. The ability of Ethereum to run smart contracts is essential to our core mission.

And before the geek squad rolls in: Yes we know that Bitcoin also has smart contracts, but Ethereum smart contracts can be much more complex and flexible, a feature of which we make full use in order to provide the largest set of features possible.

## Why do the creators have to charge manually? Can't you do this automatically?

Our system follows the [pull payment](https://consensys.github.io/smart-contract-best-practices/recommendations/#favor-pull-over-push-for-external-calls) model. This means that the people receiving payments (the creators) have to actively "pull" those payments on the system by clicking the charge button. There are two reasons why we do not perform this automatically. First, this allows funding types to be very flexible. Say you want to charge your supporters each time you upload a video to YouTube or Vimeo. There is no way for our system to automatically know that you have now uploaded a video without introducing an [Oracle](https://blockchainhub.net/blockchain-oracles/) and therefore a centralized authority, which we want to avoid. Second, it is actually very hard to schedule complex transactions on the Blockchain for a time in the future. There are initiatives such as [Ethereum Alarm Clock](https://www.ethereum-alarm-clock.com/), but they do not solve the problem completely.

## How do you make money?

We hope that the creators making money on our system are willing to kick back part of it on a voluntary basis. We also have some ideas of offering additional features that are unrelated to money flow. But at the end of the day, we're not profit-oriented.

## When and how does money flow?

There are four types of events where money flows on our system: Deposits, withdrawals, one-time payments and charges. Deposits and withdrawals simply transfer money from your wallet to your balance on the system and vice-versa. One-time payments transfer money from one user's balance to another user's balance. All simple. *Charges*, however, is where the magic happens.

When a user creates a pledge to a creator, no money actually flows yet. Remember that a pledge is always done to a particular funding type, which is defined by the creator. Examples of funding types are "once a month" or "once per video". In order for money to flow, the creator needs to select the particular funding type and then click "charge". At that point, the pledges from all pledgers to that funding type will be collected. So, for our "once a month" example, the creator would do this on the first of each month, while for the "once a video" example, they would do this every time they upload a new video. We protect against creators abusing this by letting pledgers specify the maximum amount per month that they are willing to be charged via a particular pledge.

## So you claim this is secure...

Let's have a look at how our system could be attacked.

- ### You can be shut down.
  No we can't. Anything that's deployed on the Blockchain will stay there forever. This includes our smart contract. Sure, our website could get shut down, but anyone can just build their own website to interact with the smart contract. With advanced tooling, this can even be done automatically.

- ### You could get hacked.
  Our website could get hacked, but that wouldn't help an attacker. The website is just a front-end for the smart contract, it doesn't hold or control any money or private keys. The smart contract itself cannot be hacked, as it is deployed on an unhackable Blockchain. *(Let's be clear: If the Ethereum Blockchain itself gets hacked or attacked successfully, we have bigger problems.)*

- ### You could have a bug.
  The code for the smart contract is open source and documented. So anybody can assure themselves that there is no bug before using it. We could have bugs in the website, but those will lead at maximum to an annoying UI glitch and can be fixed. Money flow will never be affected.

- ### You could get DoS'd.
  Denial of Service (DDoS) attacks are not really a problem for decentralized systems like the Blockchain, but the analogous would be an attack that targets the contract's gas limit, but as you can verify in the code, we made sure that every possible attack of this type can be mitigated. In fact, we are not susceptible against any [known attack](https://consensys.github.io/smart-contract-best-practices/known_attacks).

- ### You could become tyrannical ideologues.
  Yes we could. Maybe we already are. It doesn't matter. The smart contract is designed such that no user has any special power. Every individual controls their own money. Established pledges can only be cancelled by the pledger or the creator. Creators can set minimum amounts, pledgers can set maximum amounts. Any profile can only be edited by its owner.

- ### Someone could lose their private keys
  Indeed. And with it, access to their account on our system. Even worse, we will be completely unable to retrieve or restore it. With power and security comes responsibility. On the upside, if a creator loses their private keys, they won't be able to withdraw money, but also their supporters won't be charged due to how money flows on our system. So worst case you'll have to tell everybody to switch their pledges to your new profile.

- ### What if someone impersonates a famous creator?
  Since anyone can create a profile, this is possible. And we have no way of stopping it, because our system guarantees open participation. But we've built in a way to mitigate this as well. A creator can deposit on their profile an external link, for example a link to their YouTube channel. Then, on their YouTube channel (in the "about" section), they can post a special token containing their public address (from our system). This two-way link between a profile on our system and an external site proves that the owner of the external account is the same as the owner of the profile on our system.

- ### What if bad people use your system?
  There's nothing we can do about that. We can merely hide them on the front-end, but since anyone can build a front-end to our system, this can't be stopped. But safe to say, bad people will always find a way to do bad people things.

- ### A creator could maliciously charge their pledgers many times and drain their accounts.
  That's why every pledger sets a maximum amount that can be charged from a particular pledge each month. So maybe a creator can get away with this once and cause limited damage, but they will quickly run out of pledgers to scam, which makes this wildly unprofitable.

## I'm a creator and I'd like to try

We have a [test instance running on the Ropsten testnet](https://ropsten.liberat.io).
Once you're happy, sign up on the [main network](https://www.liberat.io).
Get in contact with us via [Email](mailto:teamliberatio@gmail.com) or [Twitter](https://twitter.com/TeamLiberatio), we're happy to help.

## I'm a developer and I'd like to help

Check out our [Github](https://github.com/liberat-io) and contact us via [Email](mailto:teamliberatio@gmail.com).

