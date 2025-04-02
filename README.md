# 5X-Crypto-Security-Guide

Inspired by the [10x Bitcoin Security Guide](https://btcguide.github.io), this is the advice I find myself giving over and over in a semi-prescriptive guide. You don't need to follow it exactly, and very few people will.

It is written for tech literate crypto holders who have mostly normal lives, a family, relatives, etc. Someone who got involved in a TGE, or got lucky on Kraken a few times, and isn’t ready to cash out yet.

We’re only trying to cover your “treasury”. The funds you don’t trade, and access every other month or so.

I am not rich enough to need this. This is how I wish my wealthy friends would get themselves organised. If people like it, I'll expand it and offer properly worked out variations.

## Assumptions

- That you don’t want, or cannot have, others operating wallets for you. (If you can, also look at [how Vitalik manages his Ether](https://x.com/VitalikButerin/status/1785562273433387320).)
- Not overly worried about the State seizing assets.
- You’d like to preclude casual wrench attacks. But are not concerned by coordinated attacks involving multiple locations.
- Access to assets within 24 hours while not travelling.
- You do care about what happens if you are dead or incapacitated.
- $150k to 5m in assets to protect

## Required Knowledge

To start this guide you should know:-

* How to use a hardware wallet
* What a seedphrase is
* That one wallet can have an infinite number of addresses
* That everything you do on-chain is visible
* Using DApps with Metamask or similar
* Some familiarity with [Safe Vault](https://safe.global/), but you can just read their docs before you start this guide.

## First Things First

* Pay taxes suitable to your home, standard of living, etc. In most countries, they **will** eventually get around to you.
* Secure your phone and laptop. Do the Apple and Facebook privacy checks. All that good stuff you've been putting off.
* Have a will. It's inevitable :(
* Put in place a Power of Attorney so that someone you trust can look after your affairs if you are incapable.

## Day to Day

When a 5X Security Implementoor, decides to access their funds. That day will look roughly like this.

Get up, shower, get dressed, have breakfast. Take out a normal laptop and grab a hardware wallet, setup a transaction on a multisig wallet. Read the newspaper.

Go to the living room. Retrieve a second hardware wallet and a dedicated little laptop from a desk safe, scrutinise and sign the earlier transaction.

Cycle to their co-working office. Pull a second little laptop from their locker. Get the last hardware wallet. Give it one last look, and finally execute it.

Not something to do every day or for small amounts. But a perfectly acceptable ritual every other month.

Sound acceptable? Read on!

## Hygiene and Holdings 

Take a passphrase protected spreadsheet or similar, and then record all your crypto assets.

These should divided into Holdings. Each Holding will be funds you are happy to have publicly linked and want to manage together. Most people will only have one Holding.

In doing this you should consider..
- KYC status. Who knows it’s yours?
- Tax
- Visibility
- Taint from an hack / impropriety

## Passphrases

A passphrase is an optional, advanced security feature that allows you to create a new wallet by adding an additional word to a 12-24 seed phrase.

With passphrases you can have one single seed with multiple different wallets. Each wallet would be designated by a different passphrase.

We use one passphrase for each wallet to deny the **Guardians** (more on that later) of the back-up plates the ability to use them independently

We will use two different passphrases:
- **Personal**, this will be lost with you if you die or are lying in a coma.
- **Static**, which will go to whoever needs to deal with your assets if you are dead or lying in a coma.

Don't confuse passphrases with the PIN to unlock your hardware wallet. PINs just control their own individual bit of hardware. 

## Big Things

These are the “life prerequisites” of the 5X security model.

### Locations

#### Safety Deposit Box

A rented box in a professionally secured vault. Available from many providers, your bank probably does this.

In most jurisdictions, the existence of this box will be disclosed to the authorities. However the upside is that you can make arrangements for access to this box in the event of you death or incapacity.

You won’t need to visit this very often, so why not place it a good distance from your home. If you are worried about over-aggressive authorities, why not rent a box in another country you like to visit?

Or a deep hole in the local forrest that's described to your heirs. Do what works for you, but don't complain if a treasure hunter digs it up in a few years.

#### Home
Just where you wake up every day. Try to keep its location off the internet. You'll be keeping a **Home Safe** there and a **Desk Safe**.

#### Office

Somewhere you can work which is available during normal hours and has some independent security. Mostly it should have CCTV and be 20 minutes plus from your **Home**. It will need a **Desk Safe**.

#### Legal
Someone who will hold your Will. and your Letter of Wishes/Instruction, and see to that they are passed to the correct people after your death or unfortunate accident.

You don't need to engage a blue-ribbon law firm. The consumer charity Which? runs [an online service](https://whichwills.which.co.uk) in the UK. Have a look around for what's available to you.

### Safes

#### Home Safe
A safe place in (or very near) your home. Ideally a properly installed safe if you have time and money to install one. A hidden floor safe encased in concrete is a great investment if you have a lot of valuables to protect. But there's a huge variety of affordable options, including, wall safes, lock boxes, even fake wall sockets, plants, and books

Or, you could seal everything in a mason jar to bury on your land :)

#### Desk Safes
A safe place that is easy to access while working at a desk. A lock box or a desk draw safe. Something that can’t be taken or tampered without raising an alert. A laptop or office locker would do.

Ideally a place you can fix a hardware wallet to with a chain. If you can't chain an item in place, you can always AirTag the items and put them in a draw.

## People

### Guardians

Have two trustworthy independent friends. They will each hold one of your steel backup plates.

They should know the circumstances under which they should hand them over, eg. to you in person, not distressed nor intoxicated, or to your heirs if you are dead, or your trustee if you are incapable. They do not need to be technical at all.

They should **not know** your **Static** passphrase nor who the other one is. Choose people from different spheres of your life, perhaps even living in different countries. They should not be your lawyer or the person who has a Power of Attorney.

### Letter of Wishes/Instruction

These letters are private documents held by a legal professional that are given to whoever executes your will, or takes charge of your affairs if you are incapacitated. (Note that Wills and Power of Attorney are usually public documents, and so a poor place to pass along secrets.)

Include the following in your Letter of Wishes
* Static passphrase
* Identity of your two **Guardians**
* The location and process for opening your **Safety Deposit Box**. Remember they are not you, and the **Safety Deposit Box** service will not know what to do with them unless you tell them.

These sit in your **Legal** location.

## Shopping List

### Wallets
- [Trezor Safe 5](https://trezor.io/trezor-safe-5-black-graphite)
- [Ledger Shift](https://shop.ledger.com/products/ledger-flex/graphite)
- [Keystone Pro](https://shop.keyst.one/products/keystone-3-pro)
- 6 x **Steel Plates** (pick [something from here](https://jlopp.github.io/metal-bitcoin-storage-reviews/?ref=blog.lopp.net), but they're all Steel Plates 🙂)
- 1 x Android Tablet
- 1 x Small iOS device

### Stuff
- AirTag
- Keyring hoops
- Long chains
- Keyring toy
- Super Glue / Epoxy
- Single six-sided casino dice
- Cheap 2nd hand Android
- [Tamper evident bags](https://en.wikipedia.org/wiki/Security_bag)
- Sticky Labels

## Setup Guide

Every time you use something for the first time, **label it clearly**.

1. Pick your two passphrases
2. Include your **Static** passphrase in a Letter of Wishes alongside your Will.
3. Include your **Static** passphrase in a Letter of Instruction for your Power of Attorney.
4. Mark the iOS device as **Home**, and the Android Tablet as Office. **Use** them only with their associated location's hardware wallet from now.
5. Set-up Keystone wallet using **Personal** passphrase.
6. Epoxy a keychain with the small toy and Airtag to the Keystone.
7. Use the Keystone Dice Mode and **Static** passphrase to set up one more wallet, called **Guardian** A. (Keystone allows for up to 3 independent wallets.)
8. Use [Keystone Dice Mode](https://guide.keyst.one/docs/dice-roll) and the **Static** passphrase, to make a wallet called **Guardian** B and restore that as your third Keystone Wallet.
9. Set up Trezor as your **Office** wallet.
10. Set up Ledger as your **Home** wallet.
11. Install [Rabby Wallet](https://rabby.io) on your Android Wallet
12. Install on your iOS ...
	1. [Metamask Mobile](https://metamask.io/en-GB/download)
	2. [Safe Wallet Mobile](https://help.safe.global/en/articles/40805-connect-external-signer-key) app
13. For each Holding…
	1. Takes the next available Ethereum address from each wallet.
	2. Fund them with suitable coins, usually ETH.
	3. Use one of them to create a 5/5 [Safe Vault multisig](https://safe.global/).
	4. Record the address of the multisig, and add it to all the address books in your other devices.
	5. Set it to a 3/5 multisig.
	6. Do whatever extra testing you need to feel confident.
14. **Wipe the Guardian wallets from your Keystone.**
15. You can now bag each of your backup plates in a tamper proof bag. They'll have numbers on the seals, write them down somewhere.
16. Put the backup plate for your **Day to Day** in your **Home Safe.**
17. Attach your **Home** wallet, eg. the Ledger, to a desk using the chain, preferably out of sight in a **Desk Safe** of some sort.
18. Take your **Office** wallet, and the Android Tablet to your **Office** location and do similarly there.
19. Gather up the **Office** and Home **backup** plates and take them to your Safety **Deposit Box. Make** sure they have your contingency plans for death or incapacity on file.
20. Deliver each of the **Guardian** backup plates to their respective **Guardians**.
21. Collect the spare materials including the cheap phone and put them somewhere safe.

## Failure and Recovery

### Single Wallet Loss

If you lose a device, it's best to replace it if you don't know where it is. It's extremely expensive to extract the data from most hardware wallets, but also hardware wallets are fairly cheap.

1. Order a new hardware wallet of the same type.
2. Retrieve the appropriate back-up plate, and clearly label it as "Void".
3. Install Metamask Mobile (or suitable crypto wallet app) on the **Spare Phone**.
4. Use the phone as a replacement for the lost wallet
5. When the new wallet arrives, set it up as a new wallet, using your spare steel plate for the backup.
6. Replace your old wallet (now on your phone), with the new wallet (on your new hardware wallet) on each of your holding's multisigs.
7. Send spare assets from the old wallet on your phone into the multisig.
8. Put the *new backup plate* in the location of the old one.
9. Put the old backup plate in draw somewhere. It doesn't really matter any more.
10. Wipe the **Spare Phone** and store it away.

### Loss of all hardware wallets

This is if your **Home** and **Office** locations, plus your **Day to Day** hardware wallet are unavailable. This is also the scenario that your agent (either your heirs or your attorney) will face.

Try to be a bit careful about bringing all your signing wallets together in the same place.

1. Buy new hardware wallets.
2. If you are able, retrieve your backup steel plate from your Home safe. If not, contact one of your **Guardians**.
3. Retrieve the steel plates from your **Safety Deposit Box**.
4. If you took the steel plate from your **Home** safe. You can simply restore everything back to normal.
5. If you used a **Guardian**'s backup steel plate, you should restore *that* wallet to the spare phone, and then treat your Day to Day as a Single Wallet Loss.
6. If the lost hardware wallets are "secure", ex. the person with the PIN is not there, then you can stop here.
7. If the lost hardware wallets are an unknown places, they'll each need to be treated as a **Single Wallet Loss**. Sorry :(
8. Put all the **current** backup steel plates and hardware wallets back where they should be.

### Loss of Safety Deposit Box

1. Get a new **Safety Deposit Box** (or at least a new mason jar in your garden for the time being)
2. Treat **Home** as a **Single Wallet Loss**
3. Treat **Office** as a **Single Wallet Loss**

## Variants

### Bitcoin only

Trezor and Keystone have Bitcoin-only firmware. You might also want to consider the Bitcoin-only [ColdCard wallet](https://coldcard.com). You might find [creating a multisig more challenging](https://medium.com/@1700constantino/protect-your-bitcoin-with-an-electrum-multi-sig-wallet-with-coldcard-ledger-and-trezor-96397e4ce287), but [Electrum wallet](https://electrum.org) software and a few others have offered this for a while. You should definitely read [10x Bitcoin Security Guide](https://btcguide.github.io).

There is also [Casa](https://casa.io), which I'd recommend for less technical Bitcoin users.

### I have no heirs. My death will deflationary.

Ignore the bits about Wills then, and just bury your "Safety Deposit Box". You could even throw them out all together.

But have a think about the Power of Attorney. We all have accidents and get sick.

### Small organisation

Day to Day becomes CEO.
Home becomes CFO.
Office becomes COO.

#### HODL Forever

You can simply wipe all the hardware wallets after set-up. Although in this case it might be better to use a [Shamir Secret Sharing scheme](https://cryptotag.io/blog/shamirs-secret-sharing-backup/) since you are only planning to access the assets once.
