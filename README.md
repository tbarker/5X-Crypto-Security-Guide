# 5X Crypto Security Guide

Inspired by the [10x Bitcoin Security Guide](https://btcguide.github.io), this is the advice I find myself giving over and over, written up as a semi-prescriptive guide. You don't need to follow it exactly, and very few people will.

![Peace](images/peace.jpg)

It is written for tech-literate crypto holders who have mostly normal lives, a family, relatives, etc. Someone who got involved in a TGE (token generation event), or got lucky on Kraken a few times, and isn't ready to cash out yet. The crypto mass affluent 🙂

This is a default Ethereum guide, but it should be easy to adapt to Bitcoin or Solana, as long as the wallet format is similar to Ethereum seed phrases. 

We're only trying to cover your "treasury". The funds you don't trade, and access every other month or so.

I am not rich enough to need this. This is how I wish my wealthy friends would get themselves organised. If people like it, I'll expand it and offer properly worked out variations. Maybe vibe code an interactive wizard 😊

## Assumptions

- That you don't want, or cannot have, others operating wallets for you. (If you can, also look at [how Vitalik manages his Ether](https://x.com/VitalikButerin/status/1785562273433387320).)
- Not overly worried about the State seizing assets.
- You'd like to preclude casual [wrench attacks](https://xkcd.com/538/). But are not concerned by coordinated attacks involving multiple locations.
- Access to assets within 24 hours while not travelling.
- You do care about what happens if you are dead or incapacitated.
- $150k to 5m in assets to protect

## Required Knowledge

To start this guide you should understand:

* How to use a hardware wallet
* What a seed phrase is
* That one wallet can have an infinite number of addresses
* That everything you do on-chain is visible
* Using DApps with Metamask or similar
* Some familiarity with [Safe Vault](https://safe.global/), but you can just read their docs before you start this guide.

## First Things First

* Pay taxes suitable to your home, standard of living, etc. In most countries, they **will** eventually get around to you.
* Secure your phone and laptop. Do the Apple and Facebook privacy checks. Make sure that if someone snatches your phone, they can't get anything. All that good stuff you've been putting off.
* Have a will. It's inevitable 😞
* Put in place a Power of Attorney so that someone you trust can look after your affairs if you are incapable.

## How you will access your funds

When a 5X Security Implementer decides to access their funds, their day might look roughly like this:

Get up, shower, get dressed, have breakfast. Take out their phone and grab a hardware wallet, setup a transaction on a multisig wallet. Read the newspaper.

Go to the living room. Retrieve a second hardware wallet and a dedicated tablet from a desk safe, scrutinise and sign the earlier transaction.

Cycle to their co-working office. Pull a second little tablet from their locker. Get the last hardware wallet. Give it one last look, and finally execute it.

Not something to do every day or for small amounts. But a perfectly acceptable ritual every other month.

Sound acceptable? Read on!

## Hygiene and Holdings 

Take a passphrase-protected spreadsheet or similar, and then record all your crypto assets.

These should be divided into Holdings. Each **Holding** will be funds you are happy to have publicly linked and want to manage together. Most people will only have one **Holding**.

In doing this you should consider:
- KYC status. Who knows it's yours?
- Tax
- Visibility
- Taint from a hack / impropriety

## Passphrases

A passphrase is an optional, advanced security feature that allows you to create a new wallet by adding an additional word to a 12–24 seed phrase.

With passphrases you can have one single seed with multiple different wallets. Each passphrase unlocks a different wallet.

We use a passphrase to protect each wallet. Without it, **Guardians** or people protecting your **Stash** (explained later) cannot access your wallets using the backup plates alone.

We will use two different passphrases:
- **Personal**, this will be lost with you if you die or are incapacitated.
- **Static**, which will be shared after your death or incapacity with whoever needs to deal with your assets.

Don't confuse passphrases with the PIN to unlock your hardware wallet. PINs just control their own individual bit of hardware. 

## Overview

In the 5X model, we separate your keys into 5 locations, locked with 2 passphrases.

![Diagram showing 5 locations](images/overview.png)

We will keep your assets in multi-signature Safe Vaults, and each of these Vaults will require 3 of your 5 wallets to move any assets.

It is possible for someone else to get access to 3 out of 5 wallets, if they can retrieve backup plates from your **Stash** (2 plates) and a **Guardian** (1 plate), and they know your **Static** passphrase. This is what will happen if you pass away or get too sick to manage yourself.

## Locations

These are places to put your wallets. Some of them are physical locations, some are people, and some are services. Think of them as facilities with a certain function rather than specific buildings.

### Personal 💼

The things you carry around with you day to day. Your purse, or briefcase.

![Purse with a Ledger](images/purse.jpg)


### Stash 🏦

This is a location outside of your normal life that someone else can access with your consent.

A rented box in a professionally secured vault would be ideal. These are available from many providers, your bank probably does this. A very small safety deposit box might [only cost you $35/year](https://ridgedalefcu.org/investing/safe-deposit-boxes) from your local credit union.

In most jurisdictions, the existence of this box will be disclosed to the authorities. However, the upside is that you can make *formal binding* arrangements for access in the event of your death or incapacity. Even if your lawyer conspires with your friends to access your safety deposit box with a false will and death certificate, it is unlikely they would sign themselves in and out of the building in front of witnesses to commit fraud.

![Widow opening bank box](images/widow.jpg)

You could dig a deep hole in the local forest that's described to your heirs. Do what works for you, but don't complain if a treasure hunter digs it up in a few years 😊

You won't need to visit the **Stash** very often, so why not place it at a safe distance from your home? Worried about over-aggressive authorities? Why not choose another country?

### Home 🏡

Just where you wake up every day. Try to keep its location off the internet. You'll be keeping a **Home Safe** there and a **Desk Safe**.

![A home](images/home.jpg)


### Office 📤

Somewhere you can work which is available during normal hours. It should have independent security and be at least 20 minutes from your **Home**. It will need a **Desk Safe**. A co-working space, or your small business if you have one, or even, a gym club.

![Office](images/office.jpg)

### Guardian A/B 🫂

Have two trustworthy independent friends. They will each hold one of your steel backup plates.

They should know the circumstances under which they should hand over their steel plate, e.g., to you in person, not distressed nor intoxicated, or to your heirs if you are dead, or your attorney if you are incapable. They do not need to be technical at all.

![Friend protecting with sword](images/guardian.jpg)

They should **not know** your **Static** passphrase nor who the other one is. Choose people from different spheres of your life, perhaps even living in different countries. They should **not be** your lawyer or a person who might hold your Power of Attorney.

### Legal 👩‍⚖️

Someone who will hold Will and your Letter of Wishes/Instruction, ensuring they are passed to the correct people in the event of your death or an accident that incapacitates you. Note that Wills become public after probate, so use your Letter of Wishes for secrets.

You don't need to engage a blue-ribbon law firm. The consumer charity Which? runs [an online service](https://whichwills.which.co.uk) in the UK. Have a look around for what's available to you.

![Accident](images/accident.jpg)

Include the following in your Letter of Wishes:
* **Static** passphrase
* Identity of your two **Guardians**
* The location and process for opening your **Stash**. Remember your heirs or attorney are not you — and any people at the **Stash**, e.g. the safety deposit company, will not know what to do unless you tell them.

![Will](images/rest.jpg)

Pamela Morgan of Empowered Law, has written [a free inheritance letter template](https://empoweredlaw.com/letter-to-loved-ones-a-template-for-your-first-cryptoasset-inheritance-plan/) that is a great start for your own letters.


## Safes

The main aim is to stop anything going missing without being noticed, so there's no need to go overboard. With that said, you likely have watches, jewellery, etc, to protect too.

### Home Safe

A safe place in (or very near) your home. Ideally a properly installed safe if you have time and money to install one. A hidden floor safe encased in concrete is a great investment if you have a lot of valuables to protect. But there's a huge variety of affordable options, including wall safes, lock boxes, even fake wall sockets, plants, and books.

In Europe, the EN 1143-1 standard grades safes from 0 to VI based on burglary resistance, and in the US, Underwriters Laboratories (UL) provides ratings such as RSC (Residential Security Container), TL-15, and TL-30. So look for the lab tests.

Here are some home safes from reputable manufacturers at varying price points:

| Image | Manufacturer | Model | Description | Price |
|-------|--------------|-------|-------------|-------|
| ![Chubbsafes DuoGuard](images/DuoGuard-M60-KL-004720x720-3.png.webp) | [Chubbsafes](https://www.chubbsafes.com/) (UK, est. 1818) | [DuoGuard Grade 1](https://www.chubbsafes.com/en/products/duoguard/) | EN 1143-1 Grade 1 (£10,000 cash / £100,000 valuables) + EN 1047-1 fire (60 min). Dualite torch-resistant barrier, T200X carbide anti-drill plates, active relocker. Available 60–450 litres with key or electronic lock. | £2,000–£3,500 (~$2,500–$4,400) |
| ![AMSEC BF1716](images/2022-BF1716E1-Open1-web.png) | [AMSEC](https://americansecuritysafes.com/) (USA, est. 1948) | [BF1716](https://americansecuritysafes.com/product/bf1716/) | UL RSC with B-rated door (½" solid steel). 3 × 1" diameter locking bolts, spring-loaded relocker, carburised hardplate. UL 60-minute fire rating (1700°F) with intumescent door seal. 2.6 cu ft, 412 lbs. Lifetime fire replacement warranty. | $2,800–$3,200 |
| ![Burg Wächter Karat](images/Produktbild_BW_Tresore_MT_640_E_FP_ISO_r_open_4003482413609_b03_1280x.jpg.webp) | [Burg Wächter](https://burg.biz/) (Germany, est. 1920) | [Karat MT 640](https://burg.biz/en/products/mt-640-e-fp) | EN 1143-1 Grade 0 (€10,000 commercial / €40,000 private), ECB-S certified. Triple-walled body with stainless steel exterior. 7mm armoured door, 3-sided bolt locking. Key, PIN, or biometric lock options (only ECB-S certified biometric). AIS and Secured by Design approved. | €1,200–€1,700 (~$1,300–$1,900) |
| ![Gardall FB2013](images/FB2714-G-C_WT_LH_DSC02219.jpg) | [Gardall](https://gardall.com/) (USA, est. 1950) | [FB2013](https://gardall.com/products/view/fire-safes/u-l-one-hour-fire-burglary-safes) | UL RSC burglary + UL 1-Hour fire (1700°F). 2" thick door, 3" composite body. Glass relocker, 1¼" chrome locking bolts, S&G Group II combination lock. 2.04 cu ft with adjustable shelves. | $1,600–$1,800 |
| ![Securikey Eurograde 0](images/SFEG0015NK_03.jpg) | [Securikey](https://www.securikey.co.uk/) (UK, est. 1972) | [Eurograde 0 (015E)](https://www.securikey.co.uk/product/euro-grade-0-size-15-electronic/) | EN 1143-1 Grade 0 (£6,000 cash / £60,000 valuables). 30-minute fire protection at 750°C. VdS Class 1 electronic lock, 3-way square bolt locking, 205° door opening. Double-walled steel body with base and rear anchor points. | £870–£1,150 (~$1,100–$1,450) |

Or, you could seal everything in a mason jar to bury on your land 😊

![Mason Jar](images/mason.jpg)

### Desk Safes

Easily accessible secure storage near a workspace, such as a lock box or desk drawer safe. It should be tamper-evident and fixed in place. A laptop safe or office locker would work well.

Ideally a place you can fix a hardware wallet to with a chain. If you can't chain an item in place, you can always AirTag the items and put them in a drawer. Gun safes could be great if they are available where you are.

Here are some recommended desk safe options from reputable manufacturers:

| Image | Manufacturer | Model | Description | Price |
|-------|--------------|-------|-------------|-------|
| ![Yale Certified Laptop Safe](images/121192.jpg.webp) | [Yale](https://www.yalehome.com/) (UK/USA, est. 1840) | [YLEM/200/EG1](https://www.safe.co.uk/products/yale-maximum-security-laptop-safe.html) | Certified laptop safe for screens up to 17". Sold Secure Silver, £2,000 cash / £20,000 valuables rating. 22mm motorised locking bolts, LED interior lighting. Electronic lock with concealed key override. 25L, 18kg. | £300–£400 (~$380–$500) |
| ![Chubbsafes Air](images/Air-M15-EL-001720x720-1.png.webp) | [Chubbsafes](https://www.chubbsafes.com/) (UK, est. 1818) | [Air Laptop 25E](https://www.chubbsafes.com/en/products/air/) | Laptop safe for screens up to 15.5". £1,000 cash / £10,000 valuables rating. 4mm steel door, 2mm steel body. Electronic keypad with anti-bump technology and key override. 24L, 11kg. Base and rear fixing bolts included. | £260–£300 (~$330–$380) |
| ![SentrySafe X055](images/X055_SS_knockout_01.png) | [SentrySafe](https://www.sentrysafe.com/) (USA, est. 1930) | [X055](https://www.sentrysafe.com/product/X055) | California DOJ Certified for firearm storage. 4 live-locking bolts, pry-resistant hinge bar. Electronic keypad with key override. Bolt-down kit included. 0.58 cu ft (16L), carpeted interior. | $80–$120 |
| ![Amazon Basics Security Safe](images/amazonbasics-security-safe.jpg) | [Amazon Basics](https://www.amazon.com/) (USA) | [Steel Security Safe](https://www.amazon.com/Amazon-Basics-Security-Electronic-Keypad/dp/B00UG9HB1Q) | Budget electronic keypad safe with backup key. 0.5 cubic feet capacity. Suitable for securing cash, jewellery, and documents. Bolt-down hardware included. | $50 |
| ![TAHOE TRAILS Book Safe](images/tahoe-trails-book-safe.jpg) | [TAHOE TRAILS](https://www.amazon.com/) (USA) | [Book Safe with Key Lock](https://www.amazon.com/TAHOE-TRAILS-Tahoe-trails-safe/dp/B09BCGS4MF) | Concealment safe disguised as a book. Compact steel construction with key lock. Ideal for hiding small valuables, passports, or seed phrase backups in plain sight on a bookshelf. | $14 |


## Shopping List

### Hardware Wallets

I have picked these for the widest compatibility.

You can use any three you want, if they work with your signing tablets. They ought to be different makes to diversify risk. 

Hardware wallet companies, especially Ledger, have [repeatedly](https://www.bleepingcomputer.com/news/security/ledger-customers-impacted-by-third-party-global-e-data-breach/) [leaked](https://www.bitdefender.com/en-us/blog/hotforsecurity/hacker-publishes-stolen-email-and-mailing-addresses-of-270000-ledger-cryptocurrency-wallet-users) [customer](https://www.dlnews.com/articles/web3/ledger-payments-partner-global-e-leaks-customer-data/) [addresses](https://www.bleepingcomputer.com/news/security/trezor-support-site-breach-exposes-personal-data-of-66-000-customers/), making it easy for criminals to [find people worth robbing](https://cryptopotato.com/ledger-users-targeted-in-phishing-scam-following-global-e-data-breach/). You should consider not ordering these directly to your home address.

** Keystone because it allows a seed phrase to be generated by rolling dice. [Diceware](https://github.com/dstodolny/BIP39-diceware) is a command-line alternative for creating seed phrases with dice.

| Image | Name | Features | Price |
|-------|------|----------|-------|
| ![Keystone 3 Pro **](images/keystone-3-pro.jpg) | [Keystone 3 Pro](https://shop.keyst.one/products/keystone-3-pro) | 4-inch touchscreen; air-gapped security; open-source firmware; supports multiple crypto accounts; compatible with MetaMask and other wallets. | $149.00 |
| ![Trezor Safe 7](images/trezor-safe-7.jpg) | [Trezor Safe 7](https://trezor.io/trezor-safe-7) | 2.5" color touchscreen with Gorilla® Glass; Dual Secure Element (TROPIC01 + EAL 6+); Bluetooth & Qi2 wireless charging; IP67 water resistant; supports thousands of coins and tokens; integrates with Trezor Suite app. | $169.00 |
| ![OneKey Pro](images/onekey-pro.png) | [OneKey Pro](https://onekey.so/products/onekey-pro/) | 3.5" color touchscreen; 4× EAL 6+ Secure Elements; air-gapped with Bluetooth/USB-C/NFC; fingerprint unlock; supports 100+ chains and 30,000+ coins; open-source firmware. | $278.00 |



And an honourable mention to the [Grid+ Lattice](https://gridplus.io/products/grid-lattice1). Well worth considering for your **Office** if you have multiple wallets to manage.

(Ledger has dropped off this list due to multiple customer data breaches and imposing [extra charges for basic multisig](https://www.theblock.co/post/376083/ledgers-new-native-multisig-rollout-sparks-criticism-over-cash-cow-fee-model) functionality.)

We will also need 6 × **Steel Plates** for seed phrase backup (pick [something from here](https://jlopp.github.io/metal-bitcoin-storage-reviews/?ref=blog.lopp.net), but they're all basically Steel Plates 🙂)

![Steel plate](images/steel.jpg)


### Signing Computers

These are just for setting up and signing your transactions. Don't use them for anything else.

- 1 × Android Tablet
- 1 × Small iOS device
- 1 × **Spare Phone** (Cheap emergency backup device for wallet recovery and transactions.)

Use your phone as the signing device for the **Personal** wallet to avoid an additional device. But *only* if the wallet you use will not show any evidence of passphrase protected wallet. This is true for [Trezor Suite](https://trezor.io/guides/trezor-suite/using-a-passphrase-wallet-in-trezor-suite#access-a-passphrase-wallet-in-trezor-suite).

You don't have to use the specific software in the Setup Guide, but do not use the Safe Vault Web interface for everything. That's how [ByBit lost over a billion dollars](https://www.nccgroup.com/us/research-blog/in-depth-technical-analysis-of-the-bybit-hack/)!

Keep all your bookkeeping on your **Home** or **Office** device. Don't walk around with evidence of your holdings. ([Rotki](https://rotki.com) is great for portfolio tracking, [buy a license](https://rotki.com/checkout/pay)!)

### Other Stuff

| Name | Purpose | Cost |
|------|---------|------|
| AirTag(s) | Track the **Personal** hardware wallet in case of loss. Maybe **Home** and **Office** if you are worried about them. | $29–35 |
| Keyring hoops | Attach hardware wallets to chains and other security measures. Just get a variety bag. | $5–10 |
| Long chains | Physically secure hardware wallets to desks or safes to prevent theft or accidental/lazy removal. | $15–30 |
| Keyring toy | It will make your hardware key much much harder to lose. | $5–15 |
| Super Glue / Epoxy | Bind chains, toys and AirTags to hardware wallets and cases. | $10–20 |
| Single six-sided casino dice | Generate truly random numbers for wallets. Casino dice ensure better randomness. | $5–15 |
| Tamper evident bags | See if anyone might have looked at a **Steel Plate**. | $20–40 for pack |
| Sticky Labels | Clearly mark all items to avoid confusions. | $5–10 |

## Setup Guide

Every time you use something for the first time, **label it clearly**.

Every time you create a seed phrase, stamp it into a back up **Steel Plate**.

1. Pick your two passphrases
2. Include your **Static** passphrase in a Letter of Wishes alongside your Will.
3. Include your **Static** passphrase in a Letter of Instruction for your Power of Attorney.
4. Mark the iOS device as **Home**, and the Android Tablet as Office. Use them *only with their associated location's hardware* wallet from now on.
5. Set up Keystone wallet using **Personal** passphrase.
6. Epoxy a keychain with the small toy and AirTag to the Keystone.
7. Use [Keystone Dice Mode](https://guide.keyst.one/docs/dice-roll) and **Static** passphrase to set up a second Keystone wallet, called **Guardian** A.
8. Use Keystone Dice Mode and the **Static** passphrase to set up a third Keystone wallet, called **Guardian** B.
9. Set up Trezor as your **Office** wallet.
10. Set up OneKey as your **Home** wallet.
11. On your Android Wallet:
	1. Install [Rabby Wallet](https://rabby.io)
	2. Configure [1.1.1.1 for Families](https://one.one.one.one/family/)
12. On your iOS:
	1. Install [Metamask Mobile](https://metamask.io/en-GB/download)
	2. Install [Safe Wallet Mobile](https://help.safe.global/en/articles/40805-connect-external-signer-key) app
	3. Configure [1.1.1.1 for Families](https://one.one.one.one/family/)
	4. Turn on iOS [Lockdown mode](https://support.apple.com/en-gb/guide/iphone/iph049680987/ios).
13. For each **Holding**:
	1. Take the next available Ethereum address from each wallet.
	2. Fund them with suitable coins, usually ETH.
	3. Use one of them to create a 5/5 [Safe Vault multisig](https://safe.global/).
	4. Record the address of the multisig, and add it to all the address books in your other devices.
	5. Set it to a 3/5 multisig.
	6. Do whatever extra testing you need to feel confident.
14. **Wipe the Guardian wallets from your Keystone.**
15. You can now bag each of your backup plates in a tamper-proof bag. They'll have serial numbers on the seals, write them down somewhere.
16. Put the backup plate for your **Personal** in your **Home Safe.**
17. Attach your **Home** wallet, e.g., the OneKey, to a desk using the chain, preferably out of sight in a **Desk Safe** of some sort.
18. Take your **Office** wallet, and the Android Tablet to your **Office** location and do similarly there.
19. Gather up the **Office** and **Home** backup plates and take them to your **Stash**. Make sure they have your contingency plans for death or incapacity on file.
20. Deliver each of the **Guardian** backup plates to their respective **Guardians**.
21. Collect the spare materials including the spare phone and put them somewhere safe.

This is a public guide on the internet. If you're concerned about physical safety, you should mix it up a bit just to be sure.

![Joker card](images/joker.jpg)

Have a glitter bomb in the decoy desk safe, [a few decoy wallets](https://x.com/PixOnChain/status/1910070486907953553), or something 😄

### ENS Names (optional)

Reduce your risk of sending funds to the wrong addresses by giving an [ENS domain](https://support.ens.domains/en/articles/7900404-what-is-ens) to *each* **Holding**, with sub-domains for each address that **Holding** regularly interacts with. For example, `kraken-deposit.wibble-womble.eth`.

Remember ENS names are public on-chain.


## Failure and Recovery

Here you can see how to recover from anything short of the destruction of your city, or a large conspiracy against you by your friends and lawyers.

### Single Wallet Loss

If you lose a device, it's best to replace it if you don't know where it is. It's extremely expensive to extract the data from most hardware wallets, but also hardware wallets are fairly cheap.

1. Order a new hardware wallet of the same type.
2. Retrieve the appropriate back-up plate, and clearly label it as "Void".
3. Install Metamask Mobile (or suitable crypto wallet app) on the **Spare Phone**.
4. Use the phone as a replacement for the lost wallet.
5. When the new wallet arrives, set it up as a new wallet, using your spare steel plate for the backup.
6. Replace your old wallet (now on your phone), with the new wallet (on your new hardware wallet) on each of your **Holdings** multi-sigs.
7. Send spare assets from the old wallet on your phone into the multisig.
8. Put the *new backup plate* in the location of the old one.
9. Put the old backup plate in a drawer somewhere. It doesn't really matter any more.
10. Wipe the **Spare Phone** and store it away.

### Loss of all hardware wallets

This is if your **Home**, **Office**, and **Personal** locations are all unavailable. This is also the scenario that your agent (either your heirs or your attorney) will face.

Avoid bringing all your signing wallets together in the same place.

1. Buy new hardware wallets.
2. If you are able, retrieve your backup steel plate from your **Home Safe**. If not, contact one of your **Guardians**.
3. Retrieve the steel plates from your **Stash**.
4. If you took the steel plate from your **Home Safe**, you can simply restore everything back to normal.
5. If you used a **Guardian**'s backup steel plate, you should restore *that* wallet to the spare phone, and then treat your **Personal** as a **Single Wallet Loss**.
6. If the lost hardware wallets are "secure", e.g., we just don't have the PIN, then you can stop here.
7. If the fate of the hardware wallets is unknown, e.g., someone could eventually break into them, they should each be treated as a **Single Wallet Loss**. Sorry 😢
8. Put all the *current* backup steel plates and hardware wallets back where they should be.

### Loss of Stash Location

1. Get a new **Stash** (or at least a new mason jar in your garden for the time being)
2. Treat **Home** as a **Single Wallet Loss**
3. Treat **Office** as a **Single Wallet Loss**

## Variants

### Bitcoin only

Trezor and Keystone have Bitcoin-only firmware. You might also want to consider the Bitcoin-only [ColdCard wallet](https://coldcard.com). You might find [creating a multisig more challenging](https://medium.com/@1700constantino/protect-your-bitcoin-with-an-electrum-multi-sig-wallet-with-coldcard-ledger-and-trezor-96397e4ce287), but [Electrum wallet](https://electrum.org) software and a few others have offered this for a while. You should definitely read the [10x Bitcoin Security Guide](https://btcguide.github.io).

![Laser eyes](images/laser.jpg)

There is also [Casa](https://casa.io), which I'd recommend for less technical Bitcoin users.

### I have no heirs. My death will be deflationary.

Ignore the bits about Wills and just bury your **Stash**.

![Man blowing bitcoin seeds into the wind.](images/deflate.jpg)


But have a think about the Power of Attorney. We all have accidents and get sick.

If you really want to be the only person with access to your assets, you only need one passphrase for everything.

### Small organisation

* **Personal** becomes CEO.
* **Home** becomes CFO.
* **Office** becomes COO.

![Team](images/team.jpg)

### HODL Forever

You can simply wipe all the hardware wallets after set-up. Although in this case it might be better to use a [Shamir Secret Sharing scheme](https://cryptotag.io/blog/shamirs-secret-sharing-backup/), which creates multiple key fragments that can later be recombined, as you are only planning to access the assets once.
