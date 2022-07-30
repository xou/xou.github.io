---
layout: mod_post
title: I Looked Into 34 Top Real-World Blockchain Projects So You Don’t Have To
date: 2022-07-30 0:21:46 -0400
categories: blockchain
permalink: /34-blockchain-projects.html
description: I looked at 34 projects listed by the top Google result for "real-world blockchain projects". 33 of these are either dead, pivoted away from Blockchain, use Blockchain in a (sometimes dangerously) bad way, or are have no real-world utility.
acks: Thanks to David Gerard, u/Siccors and Stephen Diehl for their input
published: true
---

**TL;DR**: The top #1 Google result for “blockchain production users” (and related
queries) lists 34 individual “real world blockchain” projects. One would expect some
actual functioning projects that have an impact on every-day consumers — outside of
cryptocurrency & NFTs. Looking into all 34, I found that 13 are already dead (including
one that has been killed by the SEC), 6 are only useful within the crypto & NFT
ecosystems and not in the “real world” and 14 use Blockchain in a way where removing the
blockchain would not impact functionality at all, or make the product better. The
remaining project is Chainalysis, which has real-world impact by helping law enforcement
de-anonymizing blockchain users.

{:toc}
* TOC

# Overview and Scope

If you ask people without, or with limited background in tech about Blockchain (or
Distributed Ledger Technology, “**DLT**”), the general understanding is that, even
though the Cryptocurrency and NFT ecosystem is plagued by scams, Blockchain is the
‘Future of IT’. [Deloitte compares](
https://www2.deloitte.com/us/en/pages/consulting/articles/future-of-blockchain.html) it
to the arrival of the postal services or the internet. [“Forget Bitcoin: Blockchain is
the Future”](https://www.investopedia.com/tech/forget-bitcoin-blockchain-future/) blogs
Investopedia, “How Blockchain will change [everything]” writes [Nasdaq](
https://www.nasdaq.com/articles/how-blockchain-will-change-the-way-we-work-play-and-stay-healthy-in-the-future-2021-08-26).
Even within the IT industry, plenty of people bought the hype:

>   “Blockchain will be as important to the next generation of internet
>   applications as the public cloud,
microservice architectures, and devops are to the current generation”
\[[infoworld](
https://www.infoworld.com/article/3657635/why-blockchain-is-the-future-of-the-internet.html#:~:text=Blockchain%20will%20be%20as%20important,for%20current%20and%20future%20applications.)\]

> “Blockchain is ideal for delivering that information because it provides
> immediate, shared and completely transparent information stored on an
> immutable ledger that can be accessed only by permissioned network members.”
> \[[IBM](
https://www.ibm.com/topics/what-is-blockchain)\]

But while the **13 years** of blockchain’s existence certainly had no shortage of
prototypes, promises and PR, outside of cryptocurrencies, darknet markets and money
laundering use cases, it is hard to find news articles or an overview about real-world
use cases of Blockchain technology. So I decided to dig myself.

> ![](assets/34_blockchain/intro_search.png)

The top search result for “blockchain real-world applications” on Google is [this
builtin.com article](https://builtin.com/blockchain/blockchain-applications), titled
“**34 Blockchain Applications and Real-World Use Cases Disrupting the Status Quo**“.
Quote:

> We've rounded up **34 examples of real-world blockchain use cases for this
    pragmatic yet revolutionary technology.** It's far from an exhaustive list,
    but they're already changing how we do business.

Apart from being the top #1 result, and a reasonably recent article, Builtin.com has
300+ employees ([per linkedin](https://www.linkedin.com/company/built-in)), and is a
company built around the tech startup community. Part of their business seems to be
maintaining a database of startup companies, including the ones mentioned in the
*Blockchain* article — so they have some business incentive for the data to be accurate.

Additionally, the majority of the following results did not list actual projects or
products, but rather high-level ideas like “Supply chain management”, “Healthcare”,
“Food Safety” etc. — usually with a 2-3 sentence high-level description, but no concrete
examples[^marr].

[^marr]: In fact, the only other comparable list I could find was
    [this one](https://bernardmarr.com/35-amazing-real-world-examples-of-how-blockchain-is-changing-our-world/).
    Spot-checking some of the entries, it seems to suffer from exactly the same
    problems as the Builtin list.

So I figured the *Builtin* list would be a good starting point to find & check
out some real-world use cases.

For the purposes of this article, I am making the assumptions that the projects should
be
* **Not just crypto**: As the point of this article is to find applications outside of
  cryptocurrency, I'm categorically excluding anything where the only effect of the
  application is in the user’s cryptocurrency wallet.
* **Not Dead**: Projects should have had a sign of life in the last ~12 months or so.
* **Not Bad**: Uses Blockchain, and in a way that makes sense
    * They do use a Blockchain/DLT, and
    * The DLT adds some form of value to the users, and
    * The value add comes at reasonable tradeoffs: the product is still somewhat usable and
  does not cause (obvious) legal problems.

It turns out, these are sufficient to cross out 33 of the 34 projects from the list. I
have listed those in the next section, in the order in which they appear in the original
article.

# The Dead, the Bad & the Ugly

## Smart Contract Use Cases
Smart Contracts as a concept have their own set of problems, but luckily that doesn’t
affect any of the projects Builtin listed in this category — because none seem to use
them.

### BurstIQ: Not Blockchain, Bad Blockchain, Prototype
Bad use of Blockchain, unfinished Prototype, and likely does not use DLT at all. The
website is full of marketing buzzwords, and apparently they seem to have pivoted back
and forth to IoT at some stage, and now to web3. Completely lacking is any technical
description on how the system works, beyond a few high-level buzzword-filled boxes.

Their careers page mentions blockchain only in passing, nothing blockchain-related in
the skills/qualifications sections for any engineering role — AWS & SQL [everywhere](
https://burstiq.com/senior-software-developer/), though.

> ![](assets/34_blockchain/burstiq.png)

The word “blockchain” appears only twice in their whitepaper, both times in the last
sentence:

> “The BurstIQ platform connects any data from any source in a global network
> of businesses, researchers and people, through a full end-to-end blockchain
> enablement system with blockchain-based big data management, consent and data
> sharing, cognitive computing, monetization and global data exchange.”.

*This is also the only sentence describing the platform's functionality in the
whole whitepaper.*

There is a “Tell me more” link to sign up for a 60-day free trial for BurstIQ. The link
doesn’t work.

### Mediachain: Dead
Dead: Acquired by Spotify in 2017. Website and Twitter last updated then. There has been
no mention of any progress on Mediachain’s core proposition within Spotify ever since.
In 2022 though, Spotify [is recruiting people to work on early-stage Web3 projects](
https://www.pymnts.com/nfts/2022/spotify-may-add-blockchain-nfts-to-streaming-service/)
— they are starting another prototype.

### Propy Inc: Bad
In 5 years, they seem to have sold only 2 properties: One in [Kyiv (2017)](
https://propy.com/browse/propy-nft/) and one in [Tampa, FL (2022)](
https://propy.com/browse/first-us-real-estate-nft/). The article is somewhat ambiguous
what rights you own with the NFT — it’s either “access to the paperwork” or some
“ownership rights”. I reached out to Propy and asked what happens when you lose your
keys. The answer was, in effect, *“we’ll give you new login information*”(!). In other
words, you don’t actually own or manage the NFT, Propy does. All the advantages you are
supposed to get with NFTs, access to the DeFi ecosystem for example, or easier
transfers, obviously can’t happen in this case. What happens if Propy runs out of
funding and shuts down? Do you still own your house? All Blockchain does here is muddy
the waters w.r.t. legal responsibilities & adding more complexity to the purchase
process.

Whereas earlier this year, [“NFT” was all over their homepage](
https://web.archive.org/web/20220330000138/https://propy.com/browse/), as of mid 2022,
they seem to be pivoting away from NFTs — they seem to be focusing on being a real
estate sales management platform, maybe a title and escrow company, neither of which has
anything to do with blockchain; they also seem to be taking zillow (or similar) listings
and offering to pay for the listings with cryptocurrency — which, in essence, makes them
an exchange.

## Internet of Things
The Blockchain is supposed to secure “everything from an Amazon Alexa to a smart
thermostat.” by it’s “transparency and virtual incorruptibility”. This did not make
sense to me in the first place, and apparently it did not make sense to Builtin’s
featured projects either.

### Filament: Dead
According to their [website](https://filament.com/), they have pivoted to automotive.
Their [LinkedIn](
https://www.linkedin.com/company/filament-networks?challengeId=AQHWmZyYtLGFEQAAAYBh6YQCpbksfZUZIeEehCjO1_gfuft3Cltbcf2oBJYPH8kRFUZKVYzaWMabT3tukuI5QKAqo4vDadNboA&submissionId=e5022653-0536-e916-0ceb-396c3d197c3c)
and [Twitter](https://twitter.com/FilamentHQ) have both been dead for 2+ years, and the
only change their website has seen [since 2019 is that the series A investors (Verizon
Ventures, Bullpen Capital) have pulled out.](
https://web.archive.org/web/20191224210251/https://filament.com/).

> ![](assets/34_blockchain/filament.png)

### HYPR: Not Blockchain
The Builtin article claims that HYPR makes “IoT devices virtually unhackable” by “By
taking passwords off a centralized server”. It is hard to find any references to IoT on
their website, their Blog barely mentions IoT anymore — in fact, [since Jan 2020](
https://www.google.com/search?q=site%3Ablog.hypr.com+IoT&biw=1463&bih=780&sxsrf=ALiCzsbWmp4VKcWG_B-FpVuV2OUlrwvKfQ%3A1659128128033&source=lnt&tbs=cdr%3A1%2Ccd_min%3A1%2F1%2F2020%2Ccd_max%3A&tbm=),
only [one article](
https://blog.hypr.com/best-practices-to-secure-authentication-for-energy-and-utilities)mentions
it — in passing.

Searching their website for “blockchain” yields only [8 results](
https://www.google.com/search?q=site%3Ahypr.com+%22blockchain%22)([of over a thousand
pages](https://www.google.com/search?q=site%3Ahypr.com)). All of these are either only
tangentially related “encyclopedia” articles, and/or updated 2017 or earlier. There is
no indication that HYPR has used anything blockchain related for at least 4 years.

> ![](assets/34_blockchain/hypr.png)

### Xage Security: Not Blockchain
Not DLT: Last mention of “blockchain” on their site in September 2020. A partnership
with the US Space Force, no less.

> ![](assets/34_blockchain/xage_spaceforce.png)

Similarly, their Twitter
account — which tweets daily –- has [last mentioned “blockchain” in July 2020](
https://twitter.com/search?q=from%3Axageinc%20blockchain&src=typed_query&f=live).

> ![](assets/34_blockchain/xage_most_recent_blockchain_twitter.png)

They seem to be pivoting to “zero-trust”, away from
blockchain. In fact that’s in the title of the main [whitepapers](
https://info.xage.com/resources) at the time of writing, whereas any mention of
Blockchain is completely absent.

Trying to access the actual whitepapers requires you to provide an abnormal amount of
personal data — not a good look for a security-focused company to harvest PII. Most of
the documents can be found with a [filetype google search](
https://www.google.com/search?q=site%3Axage.com+filetype%3Apdf+blockchain) — also not a
good look if it’s that easy to bypass their “security”.

Still, after downloading and going through the whitepapers, it remains fundamentally
unclear what they were actually trying to do with their blockchain system — even high
level information like “what kind of data is stored on the blockchain” is completely
absent. . They keep talking about Xage being tamper-proof due to blockchain in virtually
every document they reference blockchain in. This is plainly false, Blockchains are
tamper-**evident** and maybe tamper-**resistant**, but not tamper-**proof**[^tamper-proof]. Bad start.

[^tamper-proof]: A tamper-proof system would be one where you could not, in any
    way, change the bytes. But that’s clearly false here, you can simply go into
    the underlying storage engine — [for example, PostgreSQL or RocksDB for
Hyperledger Iroha](
https://iroha.readthedocs.io/en/develop/maintenance/migration-rocksdb.html?highlight=rocks#migration-to-rocksdb)
    — and change the values there. Arguably, given that this is a private blockchain that
    has no external parties verifying the blocks, it would be hard to even call a private
    blockchain tamper-resistant.

The little information that is available raises way more questions than it answers. In
their [NIST Cybersecurity compliance analysis doc](
http://xage.com/wp-content/uploads/2020/06/Xage-Enables-NIST800-Compliance-1.1.pdf),
they claim that their encryption scheme somewhat benefits from blockchain. There’s two,
and both are messy:
* > *Data stored in Xage Fabric is encrypted on a per publisher and subscriber basis
  end-to-end.*

  If all data between all participants on the network is end-to-end
  encrypted with per-channel keys, how exactly do you get a readable presentation in the
  audit log? Are the keys centrally managed? Clearly this encryption scheme is
  orthogonal to any blockchain use, but since we *are* using blockchain: What happens if
  the key material of one node gets compromised and you need to rotate the keys, how are
  you going to re-encrypt past entries without breaking the blockchain/merkle-tree?
* > Data stored in the Xage Fabric is encrypted using a threshold based
  > encryption technique called Shamir Secret Sharing.

  > Compromises on Fabric will require simultaneous access to multiple
  > (threshold) Xage Fabric nodes to provide their shares
  > making data leaks substantially more difficult compared to central databases
  > and not exploitable.

  This makes no sense to me, whatsoever. The only interpretation that I can get
  out of this is that the data at rest (on disk) is encrypted with a secret-sharing
  scheme, and that each blockchain node holds a chunk of the key. You’d need M-out-of-N
  chunks to decrypt the data.

  That sounds nice for 5 seconds, until you realize that there must be
  mechanisms for participants to read the data — for which the participant has
  a valid reason to contact those M nodes. At that point the participants
  obtain the “*simultaneous access” *to the key material. The encryption scheme
  offers protection only when some (less than M) **database** nodes are compromised, but
  not against compromise of any of the **other** (e.g. desktops, IoT) devices in
  the network.

  Assuming this system makes sense, it can just as well be implemented without
  a blockchain, but with a central database and separated keyservers. It can be
  reasonably assumed that this would actually be more secure:
  Separating Database and Keyservers would mean that there is fewer software
  running on each node, which would mean fewer security concerns; and the key
  server code could be much smaller (compared to a node also containing the
  blockchain and database logic) and can be audited better.


## Personal Identity

It should go without saying that putting anything ID-related on a public ledger is a
privacy and GDPR nightmare[^right-to-erasure]. I have talked extensively
about the combination of DID and Blockchain in [my previous article](
https://weh.wtf/ssi.html), which contains even more dead projects.

[^right-to-erasure]: GDPRs right to erasure applies to pseudonymous
    data, too. Pseudonymous data is anything that can be linked to a single individual by
    someone who has additional data. [There is good reason to believe that this includes
    even (hashed) public keys](
    https://www.europarl.europa.eu/RegData/etudes/STUD/2019/634445/EPRS_STU(2019)634445_EN.pdf),
    i.e. bitcoin addresses, as well as transactions between them. As far as i know, this
    hasn’t been tested in court, because nobody has sued — yet.


### Ligero: Dead
The company was founded in 2018. Their [website](https://ligero-inc.com/) has no
information on the platform, or on any activity. There doesn’t seem to be a twitter or a
company Linkedin profile. I was unable to find the CEO on LinkedIn, the CTO has no
mention of Ligero [in their LinkedIn profile](
https://www.linkedin.com/in/muthuramakrishnan-venkitasubramaniam-79a9029b), and neither
does [the company president](https://www.linkedin.com/in/sjcatlin).

### Illinois Blockchain: Dead
The “Final Report” was published [to their website](
https://www2.illinois.gov/sites/doit/Pages/BlockChainInitiative.aspx) in 2018, and the
“Illinois Department of Innovation & Technology” twitter account has [not mentioned
Blockchain since 2019](
https://twitter.com/search?q=from%3Aillinoisdoit%20blockchain&src=typed_query&f=live)

### Civic: Bad
Doesn’t use DLT at all: This company [provides ID verification](
https://www.civic.com/solutions/) and MFA login services, specifically targeted at
blockchain and NFT companies — they don’t sell a product that utilizes blockchain
itself.

### Evernym: Bad
While the [whitepaper from 2016](
https://www.evernym.com/wp-content/uploads/2017/07/The-Technical-Foundations-of-Sovrin.pdf)
talk about a distributed ledger, none of the two [case](
https://www.evernym.com/case-studies-travelpass/)[studies](
https://www.evernym.com/case-studies-memberpass/) talk about their use of blockchain —
in fact, the infographic in the former makes it pretty explicit that no blockchain is
involved. The second one seems to use the same on-phone storage for credentials, without
blockchain. I have discussed Sovrin, which is the creator of Evernym, in my [previous
article](https://weh.wtf/ssi.html) — I reached out to them, and apparently, for a single
project, they write to a private Hyperledger instance — but their client doesn’t read
from it. They did not clarify why that hyperledger is even there. They did mention that
they are exploring non-blockchain solutions.

### Ocular: Dead
The website ends with the registration form for the affiliate partnership program, which
has the note “Please note this is in early beta stages and estimated to **start high
volume testing early September 2019**.” The copyright is from 2020. There are no
technical specs whatsoever. The [Twitter account @ocularkyc](
https://twitter.com/ocularkyc) has a Manowar profile picture, and limits its post to
central-bank conspiracy theories.

> ![](assets/34_blockchain/manowar.png)

## Healthcare

As with identity, what was really missing from the healthcare system is that all that
privacy sensitive data is on a publicly accessible ledger.

### WholeCare: Bad, Likely Dead
There is virtually no information at all on their website. The most detailed technical
facts are

> ![](assets/34_blockchain/wholecare.png)

> “Resources to orient new caregivers”, “HIPAA-compliant record keeping”, “Integrated
  scheduling tools & alerts”, “Cross-device compatibility”.

That’s it.

There is no mention of blockchain or DLT on their website. Their [twitter account](
https://twitter.com/WholeCareHub) retweets a WaPo article every few months.


### Patientory: Bad, Likely Dead

The app seems to mainly be focused on tracking exercise, water, body photos — nothing
that fitbit & co can’t do today. Hardly “requires blockchain”. There is some talk about
storing patient data in the PTOY Blockchain (which seems to be the token associated with
the chain). [https://ptoy.org/](https://ptoy.org/) There’s a [Whitepaper](
https://patientoryassociation.org/wp-content/uploads/2018/11/patientory_whitepaper.pdf)
from 2017, which shows a wonderfully centralized architecture:

> ![](assets/34_blockchain/patientory1.png)

This graph could be stripped down to 3 nodes, with the same exact functionality, but
less complex, cheaper, and more performant. It even explicitly says that all the storage
work is done by a “HIPAA Compliant Database”, so blockchain doesn’t add anything here.

This is a classic 2017 ICO boom project that somehow manages to still occasionally write
tweets.

**Bonus:** The “App Store” and “Play Store” links actually lead to a “subscribe” page,
not an app store page. I doubt that is in compliance with Apple’s and Google’s
respective policies. For example, the [play store guidelines](
https://play.google.com/intl/en_us/badges/#:~:text=Any%20online%20use%20of%20the,is%20space%20in%20the%20creative.)
state: *“Any online use of the badge must link to the Google Play store.“* The badge
images are also clearly altered, prohibited by both Apple and Google’s TOS.

> ![](assets/34_blockchain/patientory2.png)

Pretty obvious trademark infringement on your homepage, for a company in a
compliance-heavy industry – that bodes well.

### Nebula Genomics: Bad

This company claims to allow people to buy their DNA sequencing kit anonymously via
bitcoin. Which makes these pop-ups particularly fun:

> ![](assets/34_blockchain/nebula_notification.png)

Of course, the checkout process does not accept crypto at all.
![](assets/34_blockchain/nebula_checkout.png)

There is some whitepaper that claims they can store and share genomics data in a
privacy-preserving way. [https://www.biorxiv.org/content/10.1101/799999v1](
https://www.biorxiv.org/content/10.1101/799999v1). As dumb as the idea is in general,
the whitepaper at least seems somewhat technically interesting. But that doesn’t really
matter, because the data is sequenced in Hong Kong, or “in Europe”, so who knows who has
copies of your data. And even if nobody stored the data: “However, under certain
circumstances your genetic information may be subject to processing pursuant to laws,
regulations or judicial or governmental orders, warrants or subpoenas. “ — in other
words, whatever technical locks they have in place, Nebula has a master key.
([Wikipedia](https://en.wikipedia.org/wiki/Nebula_Genomics))

### Medicalchain: Dead
The Whitepaper is from 2018, the [roadmap ends in 2021Q1](
https://medicalchain.com/en/roadmap/). Their [Twitter](
https://twitter.com/medical_chain) has been dead since March ‘21.

## Logistics
Are logistics companies, and the businesses they work with, interested in broadcasting
their business activity to their competitors — by putting reports, receipts & manifests
on a public ledger?

… Let's find out.

### DHL: Dead
Dead and/or never left prototype phase: The last [press release](
https://www.dhl.com/us-en/home/press/press-archive/2019/dhl-and-hewlett-packard-enterprise-take-aim-at-invoice-process-improvement.html)
is from 2019, about a MvP they tested with Hewlett-Packard Enterprise. There is no
technical description, no details, no further updates. They did provide an [overview PR
document](
https://www.dhl.com/content/dam/dhl/global/core/documents/pdf/glo-core-blockchain-trend-report.pdf),
and it’s an entertaining read, especially section 2 ”Blockchain Examples across the
Industry”: Every single example is “experimenting with”, has “built a prototype” or is
“testing”. None deployed a prod product.

The exception is Powerledger where they *claim* to have deployed the product —
but spot-checking a few of their 30 clients, all of those are either
small-scale deployments (e.g. prototypes w/ 30 kWh) or in planning/prototyping
stage.

Powerledger is an interesting one though, as it mixes both a fake blockchain approach
([Per the whitepaper](
https://www.powerledger.io/company/power-ledger-whitepaper): private blockchain
in section 5.3, off-chain channels in section 5.4, and an off-chain trading engine in section 5.5.) with what looks like a 2017 “ICO scam”
($[POWR](https://coinmarketcap.com/currencies/power-ledger/)) --- to build an energy
market, which already has working real-world non-blockchain implementations.

Hewlett-Packard Enterprise’s
Blockchain Solutions page has issued [their last “News” in 2018](
https://www.hpe.com/us/en/solutions/blockchain.html).

### Block Array: Dead

The link on the Builtin.com article links directly to [their Facebook page](https://www.facebook.com/blockarray), which hasn’t
been updated since March 2018. Their actual website (blockarray.com) is gone.

> ![](assets/34_blockchain/blockarray.png)

### Maersk: Bad
Bad DLT: I actually spent a serious amount of time looking at Maersk — this is a
platform that actually seems to work, is used by customers, and they seem to be using a
Hyperledger internally.

The problem arises when you look at what that blockchain actually does. Virtually every
component in the system is gated by an IBM.com login, there are multiple disconnected
blockchains with nodes operated by only a few participants, nodes can only be accessed
through APIs hosted by IBM (ACL’d off, of course), data is (by necessity — GDPR)
mutable, and not all data is shared by all participants.

The blockchain only seems to be used to store hashes, which you (if you have access) can
then compare against a separately stored document (if you have it). This does, of
course, not preclude existence of other, conflicting documents in the blockchain, nor
does anything really stop the few node operators to collude and re-write history — for
which there might be legal reasons, like GDPR, which one node might not even be at
liberty to disclose to other parties.

In essence, this is a working system, with a blockchain slapped on the side for PR
reasons. Blockchain integration probably does not make the system (much) worse –
especially given that it seems to affect only a tiny part of a (presumably) massively
complex shipping management system.

But it doesn’t add value either: At the end of the day, “trust in the data” is
established through the IBM logo on the login screen[^https], not through the blockchain.

[^https]: and a good old-fashioned centrally managed HTTPS connection

### ShipChain: Extra Dead

Extra dead:
[https://web.archive.org/web/20210619020901/https://shipchain.io/settle.html](
https://web.archive.org/web/20210619020901/https://shipchain.io/settle.html)

In the offer of settlement, ShipChain, Inc. offered, among other things, its payment to
the SEC of $2,050,000 [...] Unfortunately, ShipChain, Inc. is now without sufficient
resources to continue its business. Consequently, ShipChain, Inc. has made the difficult
decision to cease operations and is now in the process of closing its affairs.

It should be noted that this was in 2020, and it’s still listed when google searching
for “blockchain production users”

## Government
This is a category where, at least in theory, you’d expect the ‘everything is public’
aspect of the blockchain might add some transparency use cases. Unfortunately, in the
projects listed, it doesn’t.

### Voatz: Very, Very Bad
Bad DLT: Now, e-voting is obviously a really bad idea ([EFF has tons of material](
https://www.eff.org/issues/e-voting),[OpenPrivacy on Swiss elections](
https://openprivacy.ca/work/swisspost-scytl-evoting/) ‘19, [CCC on Germany 2020](
https://media.ccc.de/v/rc3-11440-hacking_german_elections#t=893)). There’s a principle
in democracies that every person needs to be able to understand how the result was
calculated, and why it is anonymous and secure. With that, I invite you to read the
“Technology” [on Wikipedia](https://en.wikipedia.org/wiki/Voatz), in particular:

> “The blockchain infrastructure of Voatz includes 32 identically arranged
> verifying servers that are distributed across Amazon's AWS and Microsoft's
> Azure.[16] Each server runs an identical copy of Hyperledger, an open source
> blockchain software.[17]

> Once a user downloads the Voatz app, they verify their phone number, provide
> a photo ID, as well as a "selfie". Facial recognition and voter rolls are
> used to verify identity and confirm a match between the picture and ID
> submitted. After the user is offered a secure token (activated through the
> use of a fingerprint) applicable to eligible elections, the user's biometric
> information is removed from the Voatz system.[18] After all votes are
> submitted to Voatz, votes are printed on a paper ballot and fed into a
> machine.”

Also, the intro and “Security Assessment” and “FBI Investigation” sections are
entertaining.

Now with that out of the way,
* Voatz uses paper ballots as the source of truth. The votes are apparently printed out,
  fed into a machine, where they are then counted. Why is there a blockchain system in
  the middle, at all?
* Voatz uses a replicated, permissioned hyperledger which (apparently) can only be
  accessed through their APIs. How does blockchain provide auditability here? So what
  exactly does the blockchain do here again?

A 2020 [security review by researchers at MIT](
https://internetpolicy.mit.edu/wp-content/uploads/2020/02/SecurityAnalysisOfVoatz_Public.pdf)
came to a similar conclusion:

> We further find [...] that the system’s use of the blockchain is unlikely to
> protect against server-side attacks (§5.2).

The whole article, but in particular Section 1, is downright scary.
Particularly worth pointing out is that Voatz **refuses to give a detailed
description of how their election system works**, citing IP
concerns[^voatz-reply]. So much for the whole idea of “transparency”.

David Gerard has [covered Voatz extensively](
https://davidgerard.co.uk/blockchain/tag/voatz/).

[^voatz-reply]: In fact, large chunks of Voatz [attempt to address the
    researchers' criticism](
    https://voatz.com/wp-content/uploads/2020/07/V-Analysis-of-MITresearchers-claims.pdf)is
    based on the argument “We’re not telling anyone how our voting
    infrastructure works, so how could they possibly know. The remaining
    arguments are a mix of “oh we have fixed this a looong time ago, no we’re
    not going to tell you when that was” and inadvertently admitting that the
    situation is even worse — in Section 2.4, trying to address the fact that
    biometric information is sent to a third party, they admit that that data
    is additionally transmitted to Voatz for manual inspection.

### State of Delaware: Dead

> ![](assets/34_blockchain/delaware_governor.png)

Dead: Via [technically](
https://technical.ly/civic-news/delaware-blockchain-initiative/):

> It’s been four years since that episode, and while corporations have the
> state’s authorization to use blockchain for record keeping, it’s unknown how
> many Delaware corporations are using it for stock ledgers.[...]

> Technical.ly has reached out to the governor’s office and several individuals
> directly involved with the evolution of the initiative and has not yet
> received a response. It’s also unclear what came of the Symbiont
> proof-of-concept.

### Follow My Vote: Very Bad, Almost Dead
Dead (-ish): Founded 2012. Virtually every article covering this project (from their
‘press’ section) was written in 2017 or earlier. Their [Twitter](
https://twitter.com/FollowMyVote/with_replies) account has not posted this year.

This seems to be mostly equivalent to Voatz, with the same privacy & security problems
of the “one blockchain transaction per vote” approach. Sure, you may need to hop on a
VPN, that you paid for anonymously, **and** you need to make sure that there’s no CCTV
cameras watching you vote – otherwise people, corporations or governments could
de-anonymize your vote. Small price to pay for a blockchain based system.

As with Voatz, there is basically no technical documentation. They have an infographic
on how[ their cryptographic process works](
https://followmyvote.com/cryptographically-secure-voting-2/). Can an average person
understand how this is secure & privacy-preserving? ![](assets/34_blockchain/follow_my_vote_crypto.png)

In early 2021, they apparently [scrapped](
https://followmyvote.com/introducing-pollaris/) the approach they have been working on,
to build a new fundamental platform called “Pollaris”. A year later, they uploaded [one
commit to Github](https://github.com/FollowMyVote/Pollaris-Contract). There has been no
activity since, nor was I able to find any documentation on this system. It is unclear
whether the posts above refer to the pre-Pollaris, or the post-Pollaris system (but then
again, it wouldn’t really matter either way).

## Media

Per builtin:

> “Blockchain’s strength in the media industry is its ability to prevent a
digital asset, such as an mp3 file, from existing in multiple places”.

Wait what

### MadHive: Bad & Mostly Dead.
The company's core business (Adtech) actually looks alive — but not the Blockchain part.
With the sparse information available, it looks like they had two previous attempts to
do *‘something with blockchain’*, AdLedger and MadNetwork.

The last post on [AdLedgers](https://www.adledger.org/standards#)’s[Medium](
https://medium.com/adledger) page is from 2019, so that’s almost certainly dead. The
whitepaper assumes a permissioned Ethereum blockchain:

> ![](assets/34_blockchain/adledger_paper1.png)

They do explain why this is *required*: 

> ![](assets/34_blockchain/adledger_paper2.png)

But they do not explain why using an immutable ledger, when you need to be able to
delete, makes *sense*.

They then talk about the need for “real time updates”, without the need of a
“blacklist”, and somehow the “distributed state machine” of a blockchain is a way to
achieve that. They don’t actually explain why.

The other DLT attempt seems to have been a thing called “MadNetwork”.

> “**MadProduction's** MadNetwork will allow for the mining of MadBytes and
> minting of
> MadTokens which need to be managed through an accessible user interface.”.

The above quote is from a job posting that exited when I started researching
for this article, but has since been pulled ([cached version](
https://startup.jobs/lead-solidity-engineer-madproductions-3500236)).

Assuming that this is the same as [https://www.madnetwork.com/](
https://www.madnetwork.com/#team), their last big update --- still featured
prominently at the top of the page --- is from 2020, announcing that they are
[working on a prototype with Verizon](
https://www.verizon.com/about/news/verizons-full-transparency-launches-blockchain-verification).

There is no indication that “MadNetwork” is anywhere close to even being in a
prototype
stage. It is unclear even whether this is supposed to be a distributed PKI, or a
fraud-detection network for adtech. MadHive’s own [“resources” section](
https://www.madhive.com/resources/) only lists documents from 2019.

### Steem: Dead & Bad

Steem.it is a reddit-ish social media platform. It is very close to dead these days: Per
[dapp radar](https://dappradar.com/steem/social/steemit), its usage has dropped from 33k
users / day to about 35, making this project 99.9% dead. Justin Sun took over the chain,
and the community left for a project called Hive.io.

However, if you do consider the few remaining users as a “real world use case” (or
include Hive), there’s plenty of bad DLT to go through here, too.

The big and obvious problem is how an “uncensorable” platform would deal with illegal
content (CSAM is the obvious example). The answer is apparently: [they don’t, they
can’t, they just hope nobody will ever upload anything illegal](
https://steemit.com/steemit/@sethlinson/how-can-steem-deal-with-child-pornography).[GDPR
is of course a problem](
https://medium.com/@davethepitt/ive-literally-just-found-out-that-you-can-only-edit-and-delete-content-in-steemit-and-dtube-in-the-8c1fc8a33d3e)
too. Steemit responds to legal requests by [censoring the content in the app](
https://en.cryptonomist.ch/2019/01/09/steemit-blockchain-based-social-media/),
apparently hoping that nobody will look into the Steem block-explorer — where the
content remains. **Social Media on Blockchain creates a worst of both worlds**
situation: You need a content moderation team, just like existing social media platforms
— but they can’t actually delete the content form the database, so node operators are
still broadcasting it.

SteemIt also has all the classic cryptocurrency traits: a history of [stealing funds
through soft & hard forks, threats of class-action lawsuits](
https://www.lexology.com/library/detail.aspx?g=78eebc6d-3b24-47af-8a81-d9c7c8ff37ad),
[hacks](
https://news.softpedia.com/news/steem-social-network-hacked-user-funds-stolen-ddos-attack-followed-after-506417.shtml),
and the [earning model being a pyramid scheme](
https://roselandj.medium.com/is-steemit-a-scam-93d302a44632) (with the twist that early
investors make money not only from later investors, but also from creators).

A similar project DTube, which is a youtube-esque social media platform, requires you to
refresh [the IPFS cache every few days](
https://hive.blog/witness-update/@quochuy/your-previous-d-tube-videos-don-t-play-anymore-how-to-prevent-this-from-happening-again-without-technical-skills)
to keep your videos alive:
[https://hive.blog/witness-update/@quochuy/your-previous-d-tube-videos-don-t-play-anymore-how-to-prevent-this-from-happening-again-without-technical-skills](
https://hive.blog/witness-update/@quochuy/your-previous-d-tube-videos-don-t-play-anymore-how-to-prevent-this-from-happening-again-without-technical-skills)

Reddit exists, micropayments in social media have been tried over and over again before
DLTs came around ([Flattr](https://en.wikipedia.org/wiki/Flattr),[Google Contributor](
https://en.wikipedia.org/wiki/Google_Contributor)). Steemit does censorship internally,
thus the key argument for “uncensorable posts and transactions” is not valid. Blockchain
has no reason to be integrated here, and makes things worse.

### Open Music Initiative: Dead
Dead: [Last blog posts in 2018](
https://medium.com/the-open-music-initiative/tagged/open-music-initiative), most about
hackathons, conference attendance, no actual products. Seemed to have [tweeted](
https://twitter.com/openmusic) about industry-related things until October 2020, and
only tweeted twice since.

# Not The Real World

## Money Transfer Use Cases

Money transfer use-cases would fall directly in the category of “crypto-only”. For as
long as Bitcoin has existed, this has been touted as a great use-case — but it never
really materialized.

### Chain.io: Not Blockchain

According to the Builtin article, Chain.io’s “cryptographic ledgers help financial
institutions safely and efficiently handle the transfer of cryptocurrencies.” There is
no mention of this on their homepage. It looks like they have now completely pivoted
from being a blockchain-financials company to being a logistics-on-cloud platform.
Their careers page summarizes their company as

> Chain.io is a cloud based integrations platform that connects partners across
> the global supply chain.

The [last mention of DLT in their blog](https://blog.chain.io/tag/blockchain)
is from 2018.


### Algorand, Gemini & Circle: Crypto only
Not real-world projects. As discussed in the introduction, I am only discussing projects
that have real-world effects outside of cryptocurrency balances. Gemini, Circle as
exchanges, and Algorand as a Blockchain implementation, don’t qualify here – they don’t
actually add real-world utility other than moving tokens around.

## NFTs

### Candy, Pixura, Dapper Labs [not real world, bad dlt]

As a whole, NFTs violate both the “real world” requirement, but they are also a really
bad engineering solution for the “non fungibility”

In particular — see the *Propy* use-case above — when real-world ownership law meets
stolen or lost keys, real-world wins. This also seems to be the case with the [copyright
law & Seth Green’s stolen ape](https://twitter.com/NeerajKA/status/1529176080879329285)
— a stolen NFT is unlikely to give you rights. Ownership does, but that is not the same
as possession. So the “NFTness” of the Ape doesn’t add any better management or
transferability of ownership, the exact opposite is the case: it [muddies the waters](
https://news.bloomberglaw.com/ip-law/seth-greens-stolen-bored-ape-muddles-nft-legal-ownership),
adds another layer of complexity.

But not only are there complications unifying “ownership” with the real world and the
crypto world; even within crypto “uniqueness” (and thus the “ownership over the thing”)
is far from guaranteed.
1. If Ethereum forks (again), each NFT would be duplicated, and can be sold individually
   on each chain. Of course, OpenSea might just declare one of the two forks the
   canonical one, but other platforms might disagree. From a purely technical (“code is
   law”) perspective, both forks are equally valid.
2. It is of course possible to just clone the whole contract and plug the same images
   (or URIs) in. This exists as a service, e.g. with [CloneMyNFT.com](
   https://www.prnewswire.com/news-releases/worlds-first-nft-cloning-system-launches-on-clonemynftcom-301483563.html)
   (“which allows you to keep a copy of your NFT in your wallet even after selling the
   original”),
3. It is of course also possible to just clone the NFT on a completely separate
   blockchain, like Candy does — they [run on a DLT called Palm](
   https://explorer.palm.io/token/0xCAFFA4b5F72a44C75F796E94F22dEBd6369F04FC/token-transfers),
   which uses “proof of authority (PoA) consensus, with network validators being run by
   key stakeholders” — in other words, it’s completely centralized, and if the key
   stakeholders decide to take your ape, or a majority loses interest and shut down the
   chain, your stuff is gone and you can’t get it back — except with a hard fork, see
   problem (1.).

As [Cointelegraph writes](
https://cointelegraph.com/magazine/2022/05/31/you-can-now-clone-nfts-as-mimics-heres-what-that-means):

> “**Just as in the traditional art market**, NFTs can be faked through Mimics.
> And just like in traditional art markets, this fact challenges users to take
> responsibility for tracing the provenance of what they’re buying. Identifying
> vulnerabilities is how infrastructure is strengthened.”

So, how does this improve on things then?

More generally, through labeling which NFT collection’s hash is the “true” BAYC, which
fork of the blockchain is the “true” ETH fork, which collections can even be displayed
and traded — OpenSea & co are the true gatekeepers and de-facto owners. If they want
your ape to be gone, they can pull the plug. So again, you’re left with a central
instance virtually controlling your apes, so the NFTs add practically nothing to the
real world, other than a (very expensive) layer of indirection.

So I will be excluding this category as a whole, Candy & Dapper Labs are just generic
NFT companies. Pixura deserves honorable mention for the phrase “*[Pixura] helps
non-technical users to create, track and exchange NFTs*” — because what we really needed
was to make it easier to create useless tokens.

# And The Winner Is…

**Chainalysis** helps the government track down [tax evasion](
https://www.chainalysis.com/customer-story-irs-ci/),[darknet markets](
https://www.google.com/search?q=chainalysis+darknet+markets) and [CSAM providers &
consumers](
https://www.wired.com/story/tracers-in-the-dark-welcome-to-video-crypto-anonymity-myth/).
You can make an argument that they fundamentally require cryptocurrencies to work, but
the impact they are having extends far outside the crypto ecosystem into branches of law
and tax enforcement.

They also provide mechanisms to automatically block transactions:

> Use KYT to detect patterns of high risk activity and prevent transactions
> with
> addresses identified on OFAC’s sanction list, freeze deposits from hacks or
> ransomware, screen ETH accounts, and more

It is certainly ironic: The only live real-world Blockchain use case in this
list, is an application that de-anonymizes and censors transactions in the
context of ‘uncensorable’ & ‘anonymous’ cryptocurrencies.

# Closing Words

There have been overly hyped tech products before — Cloud, Machine Learning, Internet —
where people promised more than what the product actually delivered. But these products
clearly delivered *something*. This is not the case with Blockchain technology.

The statements “Blockchain is the Future” and the more moderate “there are use-cases for
Blockchain outside of cryptocurrency” seem to always fall apart when you look at any
proposed use-case from an engineering, privacy and legal perspective.

Blockchain advocates have been spending 13 years convincing people of those statements,
could they not have spent an hour or two to find facts to back them up?

Given how many investors and members of the general public lose time and money
on this, I believe it is somewhat irresponsible that the software engineering
community is not pushing back harder. As a member of this community, I also find it
somewhat embarrassing.



