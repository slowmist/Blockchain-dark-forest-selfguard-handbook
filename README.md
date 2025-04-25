Blockchain dark forest selfguard handbook<br>
*Master these, master the security of your cryptocurrency.<br>*

:fire:Website: https://darkhandbook.io/<br>
:cn:中文版: [《区块链黑暗森林自救手册》](README_CN.md)<br>
:jp:日本語版: [ブロックチェーンのダークフォレストにおける自己防衛のためのハンドブック](README_JP.md)<br>
:kr:한국어 버전: [블록체인 다크 포레스트 셀프가드 핸드북](README_KR.md)<br>
:saudi_arabia:اللغة العربية: [دليل النجاة في الغابة المظلمة للبلوكتشين](README_AR.md)<br>
:indonesia:Versi Indonesia：[Buku Panduan menjaga diri didalam "dark forest"](README_ID.md)<br>

Author: Cos@SlowMist Team<br>
Contact me：Twitter([@evilcos](https://twitter.com/evilcos))、Jike(@余弦.jpg)

Translator: 
>[Alphatu](https://twitter.com/Alphatu4) | C. | [CJ](https://twitter.com/0xnjars) | [JZ](https://twitter.com/scorpionzhang) | [Lovepeace](https://twitter.com/lovepeace_53) | [Neethan](https://mobile.twitter.com/neethanverse) | [pseudoyu](https://twitter.com/pseudo_yu) | [SassyPanda](https://twitter.com/sassypandacap) | ss | [XL](https://twitter.com/leixing0309)

Proofreader:
>[SassyPanda](https://twitter.com/sassypandacap) | [JZ](https://twitter.com/scorpionzhang) | [Neethan](https://mobile.twitter.com/neethanverse) | [Alphatu](https://twitter.com/Alphatu4) | [pseudoyu](https://twitter.com/pseudo_yu)

![alt this](res/this.png)

:anchor:**Contents**
- [Prologue](#prologue)
- [A Diagram](#a-diagram)
  - [Create A Wallet](#create-a-wallet)
    - [Download](#download)
    - [Mnemonic Phrase](#mnemonic-phrase)
    - [Keyless](#keyless)
  - [Back up your wallet](#back-up-your-wallet)
    - [Mnemonic Phrase / Private Key](#mnemonic-phrase--private-key)
    - [Encryption](#encryption)
  - [How to use Your Wallet](#how-to-use-your-wallet)
    - [AML](#aml)
    - [Cold Wallet](#cold-wallet)
    - [Hot Wallet](#hot-wallet)
    - [What is DeFi Security](#what-is-defi-security)
    - [NFT Security](#nft-security)
    - [BE CAREFUL With Signing!](#be-careful-with-signing)
    - [Be CAREFUL With Counter-intuitive Signatures Requests!](#be-careful-with-counter-intuitive-signatures-requests)
    - [Some Advanced Attacking Methodologies](#some-advanced-attacking-methodologies)
  - [Traditional Privacy Protection](#traditional-privacy-protection)
    - [Operation System](#operation-system)
    - [Mobile phone](#mobile-phone)
    - [Network](#network)
    - [Browsers](#browsers)
    - [Password Manager](#password-manager)
    - [Two-Factor Authentication](#two-factor-authentication)
    - [Scientific Internet Surfing](#scientific-internet-surfing)
    - [Email](#email)
    - [SIM Card](#sim-card)
    - [GPG](#gpg)
    - [Segregation](#segregation)
  - [Security of Human Nature](#security-of-human-nature)
    - [Telegram](#telegram)
    - [Discord](#discord)
    - ["Official" phishing](#official-phishing)
    - [Web3 Privacy Issues](#web3-privacy-issues)
- [Blockchain Shenanigans](#blockchain-shenanigans)
- [What to do If Your Computer Gets Infected](#what-to-do-if-your-computer-gets-infected)
- [What to do When You get hacked](#what-to-do-when-you-get-hacked)
  - [Stop Loss First](#stop-loss-first)
  - [Protect The Scene](#protect-the-scene)
  - [Root Cause Analysis](#root-cause-analysis)
  - [Source Tracing](#source-tracing)
  - [Conclusion of Cases](#conclusion-of-cases)
- [Misconception](#misconception)
  - [Code Is Law](#code-is-law)
  - [Not Your Keys, Not Your Coins](#not-your-keys-not-your-coins)
  - [In Blockchain We Trust](#in-blockchain-we-trust)
  - [Cryptographic Security is Security](#cryptographic-security-is-security)
  - [Is it humiliating to be hacked?](#is-it-humiliating-to-be-hacked)
  - [Immediately Update](#immediately-update)
- [Conclusion](#conclusion)
- [Appendix](#appendix)
  - [Security rules and principles](#security-rules-and-principles)
  - [Contributors](#contributors)
  - [The Tools](#the-tools)
  - [Official Sites](#official-sites)

# Prologue

First of all, congratulations for finding this handbook! No matter who you are - if you are a cryptocurrency holder or you want to jump into the crypto world in the future, this handbook will help you a lot. You should read this handbook closely and apply its teachings in real life.

Additionally, to understand this handbook completely requires some background knowledge. However, please do not worry. As for beginners, do not be afraid of the knowledge barriers which can be overcome. If you encounter something that you don't understand, and need to explore more, Google is highly recommended. Also, it is important to keep one security rule in mind: Be skeptical! No matter what information you see on the web, you should always seek out at least two sources for cross-reference.

Again, always be skeptical :) including the knowledge mentioned in this handbook.

Blockchain is a great invention that brings about a change in production relations and solves the problem of trust to some degree. Specifically, blockchain creates many "trust" scenarios without the need for centralization and third parties, such as  immutability, execution as agreed, and prevention of repudiation. However, the reality is cruel. There are many misunderstandings about blockchain, and the bad guys will use these misunderstandings to exploit the loophole and steal money from people, causing a lot of financial losses. Today, the crypto world has already become a dark forest.

Please remember the following two security rules to survive the blockchain dark forest.

1. **Zero Trust**: To make it simple, stay skeptical, and always stay so.
2. **Continuous Security Validation**: In order to trust something, you have to validate what you doubt, and make validating a habit.

*Note: The two security rules above are the core principles of this handbook , and all the other security principles mentioned in this handbook are derived from them.*

Okay, that's all for our introduction. Let's start with a diagram and explore this dark forest to see what risks we will encounter and how we should deal with them.

# A Diagram

![](res/web3_hacking_map.jpg)

You can skim through this diagram before taking a closer look at the rest of the handbook. It is all about the key activities in this world (whatever you want to call it: blockchain, cryptocurrency or Web3), which consists of three main processes: creating a wallet, backing up a wallet and using a wallet.

Let's follow these three processes and analyze each of them.

## Create A Wallet

The core of the wallet is the private key (or seed phrase).

Here's how the private key looks like:

>0xa164d4767469de4faf09793ceea07d5a2f5d3cef7f6a9658916c581829ff5584

In addition, here's how the seed phrase looks like:

>cruel weekend spike point innocent dizzy alien use evoke shed adjust wrong

*Note: We are using Ethereum as an example here. Please check out more details of private keys/seed phrase yourself.*

The private key is your identify. If the private key is lost/stolen, then you lost your identify. There are many well-known wallet applications, and this handbook won't cover all of them. 

However, I will mention some specific wallets. Please note, the wallets mentioned here can be trusted to some degree. But I cannot guarantee they will have no security issues or risks, expected or not, during use (I won't repeat more. Please always keep in mind the two main security rules mentioned in the prologue)

Classified by application, there are PC wallets, browser extension wallets, mobile wallets, hardware wallets and web wallets. In terms of internet connection, they can be mainly divided into cold wallets and hot wallets. Before we jump into the crypto world, we must first think about the purpose of the wallet. The purpose not only determines which wallet we should use, but also how we use the wallet.

No matter what kind of wallet you choose, one thing is for sure: after you have enough experience in this world, one wallet is not enough.

Here we should keep in mind another security principle: isolation, i.e., don't put all your eggs in one basket.The more frequently a wallet is used, the more risky it is. Always remember: when trying anything new, first prepare a separate wallet and try it out for a while with a small amount of money. Even for a crypto veteran like me, if you play with fire, you are more easily to get burned.

### Download

This sounds simple, but in fact it is not easy. The reasons are as follows:

1. Many people cannot find the real official website, or the right application market, and eventually install a fake wallet.
2. Many people do not know how to identify whether the downloaded application has been tampered or not.

Thus, for many people, before they enter the blockchain world, their wallet is already empty.

To solve the first problem above, there are some techniques to find the correct official website, such as

* using Google(Exercise caution with the advertised entries in search results, as they are often unreliable.)
* using well-known official websites, such as CoinMarketCap
* asking trusted people and friends

You can cross-reference the information obtained from these different sources, and ultimately there is only one truth:) Congratulations, you have found the correct official website.

Next, you have to download and install the application. **If it is a PC wallet**, after downloading from  the official website, you need to install it yourself. It is highly recommended to verify whether the link has been tampered before installation. Although this verification may not prevent cases where the source code was altered completely (due to insider scam, internal hacking, or the official website may be hacked, etc.) However, it can prevent cases such as the partial tampering of the source code, man-in-the-middle attack, etc.

The method to verify whether a file has been tampered is the file consistency check. Usually there are two ways:

* **Hash checks**: such as MD5, SHA256, etc. MD5 works for most cases, but there is still a tiny risk of hash collision, so we generally choose SHA256, which is safe enough.
* **GPG signature verification**: this method is also very popular. It is highly recommended to master GPG tools, commands, and methods. Although this method is a bit difficult for newcomers, you will find it very useful once you get familiar with it.

However, there are not many  projects in the crypto world that provides verification. So, it is lucky to find one. For example, here is a bitcoin wallet called Sparrow Wallet. Its download page says "Verifying the Release", which is really impressive, and there are clear guidelines for both of the methods mentioned above, so you can use for reference:

>https://sparrowwallet.com/download/

The download page mentioned two GPG tools:

* GPG Suite, for MacOS.
* Gpg4win, for Windows.

If you pay attention, you will find the download pages for both GPG tools give some instructions on how to check the consistency of both methods. However, there is no step-by-step guide, that is to say, you need to learn and practice yourself:)

**If it is a browser extension wallet**, such as MetaMask, the only thing you have to pay attention to is the download number and rating in the Chrome web store. MetaMask, for example, has more than 10 million downloads and more than 2,000 ratings (though the overall rating is not high). Some people might think that the downloads numberand ratings may be inflated. Truth to be told, it is very difficult to fake such a large number.   

**The mobile wallet** is similar to the browser extension wallet. However, it should be noted that the App Store has different versions for each region. Cryptocurrency is banned in Mainland China, so if you downloaded the wallet with your Chinese App Store account, there is only one suggestion: don't use it, change it to another account in a different region such as the US and then re-download it. Besides, the correct official website will also lead you to the correct download method (such as imToken, OneKey, Trust Wallet, etc. It is important for official websites to maintain high  website security. If the official website is hacked, there will be big problems.).

**If it is a hardware wallet**, it is highly recommended to buy it from the official website. Do not buy them from online stores. Once you receive the wallet, you should also pay attention to whether the wallet is intact. Of course, there are some shenanigans on the packaging that are hard to detect. In any case, when using a hardware wallet, you should create the seed phrase and wallet address at least three times from scratch. And make sure that they are not repeated.

**If it is a web wallet**, we highly recommend not to use it.Unless you have no choice, make sure it is authentic and then use it sparingly and never rely on it.

### Mnemonic Phrase

After creating a wallet, the key thing that we deal with directly is the mnemonic phrase/seed phrase, not the private key, which is easier to remember. There are standard conventions for mnemonic phrases (e.g., BIP39); there are 12 English words in general; it could be other numbers  (multiples of 3), but not more than 24 words. Otherwise it is too complicated and not easy to remember. If the number of words is less than 12, the security is not reliable. It is common to see 12/15/18/21/24 words. In the blockchain world, 12-word  is popular and secure enough.However, there are still hardcore hardware wallets such as Ledger that starts with 24 words. In addition to English words, some other languages are also available, such as Chinese, Japanese, Korean and so on. Here is a 2048 words list for reference:

>https://github.com/bitcoin/bips/blob/master/bip-0039/bip-0039-wordlists.md

When creating a wallet, your seed phrase is vulnerable. Please be aware that you are not surrounded by people or webcams or anything else that can steal your seed phrase. 

Also, please pay attention to whether the seed phrase is randomly generated. Normally well-known wallets can generate a sufficient number of random seed phrases. However, you should always be careful. It's hard to know whether there's something wrong with the wallet. Be patient  because it can be very beneficial to develop these habits for your security. Lastly, sometimes you can even consider disconnecting from the Internet to create a wallet, especially if you are going to use the wallet as a cold wallet. Disconnecting from the Internet always works.

### Keyless

Keyless means no private key. Here we divide Keyless into two major scenarios (for ease of explanation. Such division is not industry standard)

* **Custodial**. Examples are centralized exchange and wallet, where users only need to register accounts and do not own the private key. Their security is completely dependent on these centralized platforms.
* **Non-Custodial**. The user has a private key-like control power, which is not an actual private key (or seed phrase). It relies on well-known Cloud platforms for hosting and authentication/authorization. Hence the security of the Cloud platform becomes the most vulnerable part. Others make use of secure multi-party computing (MPC) to eliminate single point of risk, and also partner with popular Cloud platforms to maximise user experience.

Personally, I have used various kinds of Keyless tools. Centralized exchanges with deep pockets and good reputations provide the best experience. As long as you are not personally responsible for losing the token (such as if your account information was hacked), centralized exchanges will usually reimburse your loss. The MPC-based Keyless program looks very promising and should be promoted . I have good experience withZenGo, Fireblocks and Safeheron. The advantages are obvious:

* MPC algorithm engineering is becoming more and more mature on the well-known blockchains, and only needs to be done for private keys.
* One set of ideas can solve the problem of different blockchains having vastly different multi-signature schemes, creating a consistent user experience, which is what we often call: universal multi-signature.
* It can ensure that the real private key never appears and solve the single point of risk through multi-signature calculation.
* Combined with Cloud (or Web2.0 technology) makes MPC not only secure but also creates a good experience.

However, there are still some disadvantages:

* Not all open source projects can meet the accepted standards of the industry. More work needs to be done.
* Many people basically only use Ethereum (or EVM-based blockchain). As such, a multi-signature solution based on smart contract approach like Gnosis Safe is enough.

Overall, no matter which tool you use, as long as you feel safe and controllable and have a good experience, it's a good tool.

So far we have covered what we need to be aware of regarding the creation of wallets. Other general security issues will be covered in later sections.

## Back up your wallet

This is where many good hands would fall into traps, including myself. I did not back up properly and I knew it would happen sooner or later. Luckily, it was not a wallet with a large amount of assets and friends at SlowMist helped me recover it.  Still, it was  a scary experience which I don't think anyone would ever want to go through. So buckle up and let's learn how to back up your wallet safely.

### Mnemonic Phrase / Private Key

When we talk about backing up a wallet, we are essentially talking about backing up the mnemonic phrase (or the private key. For convenience, we will use the mnemonic phrase in the following). Most mnemonic phrases can be categorized as follows:

* Plain Text
* With Password
* Multi-signature
* Shamir's Secret Sharing, or SSS for short

I will briefly explain each type.

**Plain Text**, Plain text is easy to understand. Once you have those 12 English words, you own the assets in the wallet. You can consider doing some special shuffling, or even replace one of the words with something else. Both would increase the difficulty for hackers to hack into your wallet, however, you would have a big headache if you forget about the  rules. Your memory isn't bulletproof. Trust me, your memory will tangle up after several years. A few years ago, when I used the Ledger hardware wallet, I changed the order of the 24-word-mnemonic phrase. After a few years, I forgot the order and I wasn't sure if  I had replaced any word. As mentioned earlier, my problem was solved with a special code breaker program that uses brute force to guess the correct sequence and words. 

**With Password**, According to the standard, mnemonic phrases can have a password. It's still the same phrase but with the password, a different seed phrase will be obtained. The seed phrase is used to derive a series of private keys, public keys and corresponding addresses. So you should not only back up the mnemonic phrases, but also the password. By the way, private keys can also have a password and it has its own standards, such as BIP 38 for bitcoin and Keystore for ethereum.

**Multi-Signature**, As the name suggests, it requires signatures from multiple people to access wallets. It's very flexible as you can set your own rules. For example, if there're 3 people have the key (mnemonic words or private keys), you can require at least two persons to sign to access the wallets. Each blockchain has its own multi-signature solution. Most well-known Bitcoin wallets support multi-signature. However, in Ethereum, multi-signature is mainly supported through smart contracts, such as Gnosis Safe. Furthermore, MPC, or Secure Multi-Party Computation is becoming more and more popular.. It provides an experience similar to the traditional multi-signature, but with different technology. Unlike multi-signature, MPC is blockchain agnostic and can work with all protocols.

**SSS**, Shamir's Secret Sharing, SSS breaks down the seed into multiple shares (normally, each share contains 20 words). To recover the wallet, a specified number of shares has to be collected and used. For details, refer to the industry best practices below:

>https://guide.keyst.one/docs/shamir-backup<br>
>https://wiki.trezor.io/Shamir_backup

Using solutions such as multi-signature and SSS will give you peace of mind and avoid single-point risks, but it could make management relatively complicated and sometimes multiple parties will be involved. There is always a compromise between convenience and security. It is up to the individual to decide but never be lazy in principles.

### Encryption

Encryption is a very, very broad concept. It doesn't matter if the encryption is symmetric, asymmetric or uses other advanced technologies; as long as an encrypted message can be easily decrypted by you or your emergency handling team easily but nobody else after decades, it is good encryption.

Based on the security principle of "zero trust", when we are backing up wallets, we have to assume that any step could be hacked, including physical environments such as a safe. Keep in mind that there is no one other than yourself who can be fully trusted. In fact, sometimes you can't even trust yourself, because your memories may fade away or misplaced. However, I won't make pessimistic assumptions all the time, otherwise it would lead me to some unwanted results. 

When backing up, special consideration must be given to disaster recovery. The main purpose of disaster recovery is to avoid a single point of risk. What would happen if you are gone or the environment where you store the backup is down? Therefore, for important stuff, there must be a disaster recovery person and there must be multiple backups.

I won't elaborate too much on how to choose the disaster recovery person because it depends on who you trust. I will focus on how to do the multi-backups. Let's take a look at some basic forms of backup locations:

* Cloud
* Paper
* Device
* Brain

**Cloud**, Many people don't trust backup on Cloud, they think it is vulnerable to hacker attacks.  At the end of the day, it is all about which side - the attacker or the defender - put in more effort, in terms of both manpower and budgets. Personally, I have faith in cloud services powered by Google, Apple, Microsoft, etc., because I know how strong their security teams are and how much they have spent on security. In addition to fighting against external hackers, I also care a lot about internal security risk control and private data protection. The few service providers I trust are doing a relatively better job in these areas. But nothing is absolute. If I choose any of these cloud services to back up important data (such as wallets), I will definitely encrypt the wallets at least one more time.

I strongly recommend mastering GPG. It can be used for the  "signature verification", and provides strong security of encryption and decryption in the meantime. You can learn more about GPG at:

>https://www.ruanyifeng.com/blog/2013/07/gpg.html

Okay, you have mastered GPG :) Now that you have encrypted  related data in your wallet (mnemonic phrase or private key) with GPG in an offline secured environment, you can now throw the encrypted files directly into these cloud services and save it there. All will be good. But I need to remind you here: never lose the private key to your GPG or forget the password of the private key...

At this point, you might find this extra level of security is quite troublesome: you have to learn about GPG and back up your GPG private key and passwords. In reality, if you have done all the aforementioned steps, you are already familiar with the process and won't find it as difficult or troublesome. I will say no more because practice makes perfect.

If you want to save some effort, there is another possibility but its security may be discounted. I can't measure the exact discount but sometimes I would be lazy when I would use some well-known tools for assistance. That tool is 1Password. The latest version of 1Password already supports direct storage of wallet-related data, such as mnemonic words, passwords, wallet addresses, etc., which is convenient for users. Other tools (such as Bitwarden) can achieve something similar, but they are not as convenient.

**Paper**, Many hardware wallets come with several high-quality paper cards on which you can write down your mnemonic phrases (in plaintext, SSS, etc.). In addition to paper, some people also use steel plates (fire-resistant, water-resistant and corrosion-resistant, of course, I have not tried those). Test it after you copy over the mnemonic phrases and if everything works, put it in a place where you feel secure, such as in a safe. I personally like using paper a lot because if properly stored, paper has a much longer lifespan than electronics.

**Device**, It refers to all kinds of equipment; electronics are a common type for backup, such as a computer, an iPad, an iPhone, or a hard drive, etc, depending on personal preference. We also have to think about the secure transmission between devices. I feel comfortable using peer-to-peer methods such as AirDrop and USB where it is difficult for a middleman to hijack the process. I am just naturally uneasy about the fact that electronic equipment may break down after a couple of years, so I maintain the habit of checking the device at least once a year. There are some repeated steps (such as encryption) which you can refer to the Cloud section.

**Brain**, Relying on your memory is exciting. In fact, everyone has their own "memory palace". Memory is not mysterious and can be trained to work better. There are certain things that are indeed safer with memory. Whether to rely solely on the brain is a personal choice. But pay attention to two risks: firstly, memory fades away as time goes and could  cause confusion; the other risk is that you may have an accident. I will stop here and let you explore more.

Now you are all backed up. Don't encrypt  too much, otherwise you will suffer from yourself after several years. According to the security principle of  "continuous verification", your encryption and backup methods, whether excessive or not, must be verified continuously, both regularly as well as randomly. The verification frequency depends on your memory and you do not have to complete the whole process. As long as the process is correct, partial verification also works. Finally, it is also necessary to pay attention to the confidentiality and security of the authentication process.

Okay, let's take a deep breath here. Getting started is the hardest part. Now that you are ready, let's enter this dark forest :)

## How to use Your Wallet

Once you have created and backed up your wallets, it comes to the real challenge. If you don't move around your assets frequently, or you barely interact with  any smart contracts of DeFi, NFT, GameFi, or Web3, the popular term referred to frequently these days, your assets should be relatively safe.

### AML

However, "relatively safe" doesn't mean "no risk at all". Cause "you never know which comes first, tomorrow or accidents", right?. Why is it? Think about it, where did you get the cryptocurrency? It didn't just come from nowhere, right? You may encounter AML (Anti Money Laundering) on all the cryptocurrencies you get any time. This means that the cryptocurrency you're holding at the moment may be dirty, and if you're not lucky, it may even be frozen directly on the chain. According to public reports, Tether once freezed some USDT assets  as per request from law enforcement agencies. The list of frozen funds can be found here.

>https://dune.xyz/phabc/usdt---banned-addresses

You can verify if an address is  frozen by Tether from the USDT contract.

>https://etherscan.io/token/0xdac17f958d2ee523a2206206994597c13d831ec7#readContract

<img src="res/usdt_isblacklisted.png" width="700">

Use the target wallet address as input  int isBlackListed to check. Other chains that take  USDT have similar verification way.

However, your BTC and ETH should never ever get frozen.  If this does happen one day in the future, the belief of decentralization would crash as well.  Most cryptocurrency asset frozen cases we have heard today actually happened in centralized platforms (such Binance, Coinbase, etc.) but not on the blockchain. When your cryptocurrency stays in Centralized Exchange platforms, you don't actually own any of them. When the centralized platforms freeze your account, they are actually revoking your permission to trade or withdraw. The concept of freezing could be misleading to newbies in the area.  As a result, some reckless self media would spread all kinds of conspiracy theories about BitCoin.

Though your BTC and ETH assets won't be frozen on the blockchain, centralized exchanges might freeze your assets according to the requirement of AML once your assets get transferred into these platforms and they are involved in any open cases that law enforcements are working on.

To better avoid AML issues, always choose platforms and individuals with a good reputation as your counterparty. There are actually a few solutions  for this type of problem. For example, on Ethereum, almost all bad guys and people who care a lot about their privacy  use Tornado Cash for coin mixing. I won't dig any more into this topic since most methods here are being used for doing evil.

### Cold Wallet

There are different ways to use a cold wallet. From a wallet's perspective, it can be considered as a cold wallet as long as it's not connected to any network. But how to use it when it's offline?  First of all, if you just want to receive cryptocurrency, it's not a big deal. A cold wallet could provide excellent experience by working with a Watch-only wallet, such as imToken, OneKey, Trust Wallet, etc. These wallets could be turned into watch-only wallets by simply adding target wallet addresses.

If we want to send cryptocurrency using  cold wallets, here are the most commonly used ways:

* QRCode
* USB
* Bluetooth

All of these require a dedicated app (called Light App here) to work with the cold wallet. The Light App will be online along with the aforementioned Watch-only wallet. Once we understand the underlying essential principle, we should be able to understand these approaches. The essential principle is:  eventually, it's just a matter of figuring out how to broadcast signed content onto the blockchain. Detailed process is as follows:

* The content to be signed is transmitted by the Light App to the Cold Wallet by one of these means.
* The signature is processed by the cold wallet that has the private key and then transmitted back to the Light App using the same way
* The Light App broadcasts the signed content on the blockchain.

So no matter which method is used,  QR code, USB or Bluetooth, it should be following the above process. Of course, details might vary from different methods . For example, QR code has a limited information capacity, so when the signature data is too large, we would have to split it up.

It seems to be a bit troublesome, but it becomes better when you  get used to it. You would even feel a full sense of security. However, don't consider it 100% secure because there are still risks here, and there have been many cases of heavy losses because of these risks. Here are risk points:

* The target address of  the coin transfer was not checked carefully, resulting in the coin being transferred to someone else. People are lazy and careless, sometimes . For example, most of the time they only check the beginning and ending few bits of a wallet address instead of fully checking the whole address. This leaves a backdoor to bad guys.They will run programs to get the wallet address with the same first and last few bits as your desired target address and then replace your coin transfer target address with the one under their control using  some tricks.
* Coins are authorized to unknown addresses. Usually authorization is the mechanism of the Ethereum smart contract tokens, the "approve" function, with one argument being the target authorization address and the other being the quantity. Many people don't understand this mechanism, so they may authorize an unlimited number of tokens to the target address, at which point the target address has permission to transfer all those tokens away. This is called authorized coin theft, and there are other variants of the technique, but I won't expand on it here.
* Some signatures that seem not important actually have huge traps in the back, and I won't dig into it now, but will explain the details later.
* The cold wallet may not have provided enough necessary information, causing you to be careless and misjudged.

It all boils down to two points:

* The user interaction security mechanism of "What you see is what you sign" is missing.
* Lack of relevant background knowledge of the user.

### Hot Wallet

Compared to a cold wallet, a hot wallet has basically all the risks that a cold wallet would have. Plus, there is one more: the risk of theft of the secret phrase (or private key). At this point there are more security issues to consider with hot wallets, such as the security of the runtime environment. If there are viruses associated with the runtime environment , then there is a risk of getting stolen. There are also hot wallets that have certain vulnerabilities through which the secret phrase can be directly stolen.

In addition to the regular coin transfer function, if you want to interact with other DApps (DeFi, NFT, GameFi, etc.), you either have to access them directly with your own browser or interact with the DApps opened in your PC browser via the WalletConnect protocol.

*Note: References of DApps in this handbook refer by default to smart contract projects running on the Ethereum blockchains.*

By default, such interactions do not lead to secret phrase theft, unless there is a problem with the wallet security design itself. From our security audits and security research history, there is a risk of wallet secret phrases being stolen directly by malicious JavaScript on the target page. However, this is a rare case, as it is actually an extremely low-level mistake that no well-known wallet is likely to make.

None of these are actually my actual concerns here, they are manageable for me (and for you too). My biggest concern/concern is: how does each iteration of a well-known wallet ensure that no malicious code or backdoor is planted? The implication of this question is clear: I verified that the current version of the wallet has no security issues and I'm comfortable using it, but I don't know how secure the next version will be. After all, I or my security team can't have that much time and energy to do all the verifications.

There have been several incidents of coin theft caused by malicious code or backdoors as described here, such as CoPay, AToken, etc. You can search for the specific incidents yourself.

In this case, there are several ways of doing evil:

* When the wallet is running, the malicious code packages and uploads the relevant secret phrase directly into the hacker-controlled server.
* When the wallet is running and the user initiates a transfer, information such as the target address and amount is secretly replaced in the wallet backend, and it is difficult for the user to notice.
* Corrupting the random number entropy values associated with the generation of secret phrases, which makes them relatively easy to decipher.

Security is a thing of ignorance and knowledge, and there are many things that could be easily ignored or missed. So for wallets that hold important assets, my security rule is also simple: no easy updates when it's enough to use.

### What is DeFi Security

When we talk about DApp, it could be DeFi, NFT or GameFi etc. The security fundamentals of these are mostly the same, but they will have their respective specifics. Let's first take DeFi as an example to explain. When we talk about DeFi security, what exactly do we mean? People in the industry almost always only look at smart contracts. It seems that when smart contracts are good, everything will be fine. Well actually, this is far from true.

DeFi security includes at least the following components:

* Smart Contract Security
* Blockchain Foundation Security
* Frontend Security
* Communication Security
* Human Security
* Financial Security
* Compliance Security

**Smart Contract Security**

Smart contract security is indeed the most important entry point for security audit, and SlowMist's security audit standards for smart contracts can be found at:

>https://www.slowmist.com/service-smart-contract-security-audit.html

For advanced players, if the security of the smart contract part itself is controllable  (whether they can audit themselves or understand security audit reports issued by professional organizations), then it doesn't matter if the other parts are secure. Controllable is a tricky concept, some of which depends on the player's own strength. For example, players have certain requirements in respect of the risk from excessive smart contract authority. If the project itself is strong and the people behind it have a good reputation, complete centralization would not matter. However, for those less well-known, controversial or emerging projects, if you realize that the project's smart contracts possess excessive permission risk, especially if such permissions can also affect your principal or earnings, you will certainly be reluctant.

The risk of excessive permission is very subtle. In many cases, it is in place for the admin of the project to conduct relevant governance and risk contingency. But for users, this is a test on human nature. What if the team decides to  do evil? So there is a trade-off practice in the industry: adding Timelock to mitigate such risks of excessive permission, for example:

> Compound, an established and well-known DeFi project, the core smart contract modules Comptroller and Governance, both haveTimelock mechanism added to their admin permission:<br>
> Comptroller(0x3d9819210a31b4961b30ef54be2aed79b9c9cd3b)<br>
> Governance(0xc0da02939e1441f497fd74f78ce7decb17b66529)<br>
> The admin these 2 modulesis<br>
> Timelock(0x6d903f6003cca6255d85cca4d3b5e5146dc33925)

You can directly find out on chain that the Timelock (delay variable) is 48 hours (172,800 seconds):

<img src="res/compound_timelock.png" width="700">

That is to say, if the admin of Compound needs to change some key variables of the target smart contract, the transaction will be recorded after it is initiated on the blockchain, but 48 hours must be waited before the transaction can be finalized and executed. This means that if you would like, you can audit every single operation from the admin, and you will have at least 48 hours to act. For example, if you are unsure, you can withdraw your funds within 48 hours. 

Another way to mitigate the risk of excessive permission of admin is to add multi-signature, such as using Gnosis Safe for multisig management, so that there will at least be no dictator. It should be noted here that multisig can be "the emperor's new clothes". For example, one person may hold multiple keys. Therefore, the multisig strategy of the target project needs to be clearly stated. Who holds the keys, and the identity of each key holder must be reputable. 

It is worth mentioning here that any security strategy may lead to the problem of "the emperor's new clothes", which the strategy may appear to be well done, but in reality is not, resulting in an illusion of security. Take another example, Timelock looks good on paper. Actually, there have been cases where Timelock deployed by some projects has backdoors. Generally, users don't look into the source code of Timelock, and they would not necessarily understand it even if they do, so the admin puts a backdoor there, and no one would really notice for a long enough time. 

In addition to the risk of excessive permission, other elements of smart contract security are also critical. However, I will not expand here, in consideration of the prerequisites for understanding. Here is my advice: you should at least learn to read the security audit report, and practice makes perfect.

**Blockchain Foundation Security**

Blockchain foundation security refers to the security of the blockchain itself, such as consensus ledger security, virtual machine security etc. If the security of the blockchain itself is worrisome, the smart contract projects running on the chain would suffer directly. It is so important to choose a blockchain with sufficient security mechanism and reputation, and better with a higher probability of longevity.

**Frontend Security**

Frontend security is really the devil. It is too close to the users, and it is especially easy to fool users into deception. Perhaps everyone's main focus is on the wallet and smart contract security, resulting in frontend security being easily overlooked. I want to  emphasize again that frontend security is the devil! Allow me to dig deeper. 

My biggest concern regarding frontend security is: How do I know that the contract I am interacting with from this specific frontend page is the smart contract that I'm expecting?

This insecurity is mainly due to two factors:

* Inside job
* Third party

It is straightforward to understand the inside job. For example, the devs secretly replaces the target smart contract address in the frontend page with a contract address that has a backdoor, or planting an authorization phishing script. When you visit this rigged frontend page, a series of subsequent operations involving cryptos in your wallet may be done in a trap. Before you realized, the coins would be already gone.

The third party mainly refers to two types:

* One is that the dependencies chain is infiltrated. For example, the third-party dependency used by  the frontend page  has a backdoor which gets sneaked into  the target frontend page along with the packaging and release.  The following is the package dependency structure of SushiSwap (for illustration only, it doesn't necessarily mean that the project in the screenshot has such issue):<br>
    <img src="res/sushiswap_3rd.png" width="500">

* The other example is third-party remote JavaScript files imported by  the frontend page. If this JavaScript file is hacked, it's possible that the target frontend page gets affected as well, such as OpenSea (for illustration only, it doesn't necessarily mean that the project in the screenshot has such an issue):<br>
    <img src="res/opensea_3rd.png" width="800">

The reason why we said it's just possible but not certainly is that the risk could be mitigated if devs refer to a third-party remote JavaScript file on the frontend page in the following way:

><script src="https://example.com/example-framework.js" integrity="sha384-Li9vy3DqF8tnTXuiaAJuML3ky+er10rcgNR/VqsVpcw+ThHmYcwiB1pbOxEbzJr7" crossorigin="anonymous"></script>

The key point here is a nice security mechanism of HTML5: integrity attribute in tags (SRI mechanism). integrity supports SHA256, SHA384 and SHA512. If third-party JavaScript files do not meet the hash integrity check, the files will not be loaded. This can be a good way to prevent unintended code execution. However, utilizing this mechanism requires the target resource to support CORS response. For details, refer to the following:

>https://developer.mozilla.org/zh-CN/docs/Web/Security/Subresource_Integrity

**Communication Security**

Let's focus on HTTPS security in this section. First, the target website must use HTTPS, and HTTP plaintext transmission should never be allowed. This is because HTTP plaintext transmission is too easy to be hijacked by man-in-the-middle attacks. Nowadays HTTPS is very common as a secure transmission protocol. If there is a man-in-the-middle attack on HTTPS, and attackers have injected malicious JavaScript into the web application's front-end, a very obvious HTTPS certificate error alert will be displayed in the user's browser.

Let's use the MyEtherWallet incident as an example to illustrate this point.

MyEtherWallet used to be a very popular web application wallet, and up till now it's still very well known. However it's no longer just a web application wallet. As mentioned before, I strongly discourage the use of web application wallets due to security reasons. In addition to various issues in front-end security, HTTPS hijacking is also a big potential risk.

On April 24, 2018, there was a major security incident of HTTPS hijacking in MyEtherWallet. The recap of the incident can be found here:

>https://www.reddit.com/r/MyEtherWallet/comments/8eloo9/official_statement_regarding_dns_spoofing_of/<br>
>https://www.reddit.com/r/ethereum/comments/8ek86t/warning_myetherwalletcom_highjacked_on_google/

![](res/myetherwallet_https_hijack.png)

In the attack, the hacker hijacked the DNS service (Google Public DNS) used by a large number of MyEtherWallet users via BGP, an ancient routing protocol, which directly led to the display of HTTPS error alerts in every user's browser when they tried to visit MyEtherWallet website. In fact, users should stop when they see this alert, as it basically indicates that the target web page has been hijacked. In reality however, many users just quickly ignored the alert and proceeded to continue with their interactions with the hijacked site, because they didn't understand the security risk behind the HTTPS error alert at all. 

Since the target web page had been hijacked and the hacker had injected malicious JavaScript in there, upon users' interaction, the hackers would have successfully stolen their plaintext private key and transferred away their funds  (mostly ETH). 

This is definitely a classic case where hackers used BGP hijacking techniques to steal crypto. It's just overkill. Ever after this there have been several similar cases, and I won't mention them in detail here. To the user there is only one thing that really needs attention: if you ever decide to use a web application wallet, or try to interact with a DApp, always make sure you stop and close the page whenever you see a HTTPS certificate error alert! And your funds will be fine. There is a cruel reality in security: when there is a risk, don't give users any choices. As if you do, there will always be users falling into the trap for whatever reasons. In fact, the project team needs to take up the responsibility. As of today, there are already very effective security solutions to the HTTPS hijacking issue mentioned above: the project team needs to properly configure HSTS. HSTS stands for HTTP Strict Transport Security; it is a web security policy mechanism supported by most modern browsers. If HSTS is enabled, in case of a HTTPS certificate error the browser will force users to stop accessing the target web applications and the restriction can't be bypassed. Now you get what I mean?

**Human Nature Security**

This section is easy to understand. For example the project team is evil minded and acts in a dishonest way. I have mentioned some relevant contents in previous sections, so here I won't go into more details. More to be covered in later sections.

**Financial Security**

Financial Security should be deeply respected. In DeFi, users pay utmost attention to token price and return. They want superior, or at least steady return on investment. In other words, as a user, I play the game to win and if I lose, at least I need to be convinced that it is a fair game. This is just human nature.

Financial security in DeFi is susceptible to attacks in the forms of:

* Unfair launch practices such as pre-mining or pre-sale;
* Crypto whale attack;
* Pump and dump;
* Black swan events, like sudden market waterfall; or let's say when one DeFi protocol is nested or interoperated with other DeFi/Tokens, its security/reliability will be highly depending on other protocols
* Other technical attacks or what we refer to as scientific techniques such as front running, sandwich attack, flash loan attacks, etc

**Compliance Requirements**

Compliance requirement is a very big topic, the previously mentioned AML(Anti Money Laundering) is just one of the points. There are also aspects like KYC(Know Your Customer), sanctions, securities risks, etc. In fact for us users these are not something under our control. When we interact with a certain project, as it may be subject to relevant regulations in certain countries, our privacy information might get collected. You might not care about such privacy issues, but there are people who do. 

For example, in early 2022 there was a small incident: some wallets decided to support Address Ownership Proof Protocol(AOPP) protocol:

I took a look at the protocol design, it turned out that wallets supporting AOPP might leak user privacy. Regulators might get to know the interconnection between a regulated crypto exchange and an unknown external wallet address.

>https://gitlab.com/aopp/address-ownership-proof-protocol

No wonder many privacy-oriented wallets are so concerned about user's feedback and quickly removed AOPP support from their products. But to be honest: The protocol design is quite interesting. I have noticed that some wallets have no plans to remove support for AOPP, such as EdgeWallet. Their opinion is that AOPP doesn't necessarily expose more user privacy, on the contrary it helps to enhance the circulation of cryptocurrency. In many regulated crypto exchanges, users are not allowed to withdraw to a particular external wallet address, before he can prove his ownership to it.

At first, the well-known hardware wallet Trezor refused to remove AOPP support. But later it was forced to compromise and did so due to pressures from the community and users on Twitter. 

As you can see, it's such a small incident but to some people, privacy is really important. This is not to say that we should go against regulations, and totally ignore compliance requirements. As a matter of fact I do believe it's necessary to have a certain level of compromise to compliance requirements. We won't continue to deep dive into this topic, feel free to digest the contents in your own ways. 

So far, we have covered the majority of content in the DeFi Security section. 

What's more, there are also security issues introduced by future additions or updates. We often say "security posture is dynamic, not static". For example nowadays most project teams do security audits and show clean security audit reports. If you ever read the good-quality reports carefully you will notice that these reports will clearly explain the scope, timeframe, and the unique identifier of the audited contents (e.g. the verified open source smart contract address, or the commit address on GitHub repo, or the hash of the target source code file). This is to say, the report is static, but if in a project you have observed any deviations from what is mentioned in the report, you can point it out.

### NFT Security

All the previously mentioned contents on DeFi security can be applied to NFT security, and NFT itself has a few very specific and unique security topics, for example:

* Metadata security
* Signature security

Metadata refers mainly to the embedded picture, motion pictures and other contents. It's recommended to refer to OpenSea on the specific standards:

>https://docs.opensea.io/docs/metadata-standards

There are two main security concerns that may arise here:

* One is that the URI where the image (or motion picture) is located might not be trustworthy. It can just be a randomly selected centralized service, on one hand there is no guarantee of availability, on the other hand the project team can modify the images at will, thus the NFT will no longer become an immutable "digital collectible". Generally it's recommended to use decentralized storage solutions such as IPFS, Arweave, and select a well-known URI gateway service.
* Another is the potential for privacy leakage. A randomly selected URI service might capture user's basic information (such as IP, User-Agent, etc)

Signing security is another big concern here, and we will illustrate it below.

### BE CAREFUL With Signing!

Signature security is something that I want to mention specifically as there are SO MANY pitfalls and you should be careful all the time. There have been several incidents, especially on NFT trading. However, I have noticed that not too many people understand how to prepare for and deal with such security problems. The underlying reason is few people have ever made the problem clear enough.

The NO.1 and most important security principle in signature security is: **What you see is what you sign**. That is, the message in the signature request you received is what you should expect after signing. After you sign it, the result should be what you expected instead of something you would regret.

Some details of signature security have been mentioned in the "Cold Wallet" section. If you can't recall, I would suggest you revisit that section. In this section, we will focus on other aspects.

There were several well-known NFT hacks on OpenSea around 2022. On Feb 20th, 2022, there was a major outbreak. The root causes are:

* Users signed NFT listing requests on OpenSea.
* Hackers phished to obtain relevant signatures from users.

It is actually not hard for hackers to obtain the relevant signature. The hacker needs to 1). construct the message to be signed, 2). hash it, 3). trick the target user to sign the request (this would be a blind signing, which means users don't actually know what they are signing), 4). get the signed content and construct the data. At this point, the user has been hacked.

I will use Opensea as an example (in reality, it could be ANY NFT marketplace). After the target user authorizes the NFT listing operation in the marketplace, the hacker would construct the message to be signed. After hashing it with Keccak256, a signature request would pop up on the phishing page. Users would see something like the following:

<img src="res/metamask_sign.jpg" width="360">

Look closely. What kind of information can we get from this MetaMask popup window? Account Info and account balance, the source website where the signature request comes from, the message that users are about to sign and...nothing else. How could users suspect that the disaster is already on the way? And how could they realize that once they click the "Sign" button, their NFTs would be stolen.

This is actually an example of blind signing. Users are not required to sign within the NFT marketplace. Instead, users can be tricked into any phishing website to sign the message without fully understanding the actual meaning and consequence of these signatures. Unfortunately, hackers know. As a user, just keep in mind: NEVER BLIND SIGN ANYTHING. OpenSea used to have the blind signing problem, and they fixed it by adopting EIP-712 after Feb 20th 2022. However, without blind signing, users could still be careless and hacked in other ways.

The most essential reason why this is happening is that the signing isn't restricted to follow the browser's same-origin policy. You can simply understand it as: the same-origin policy can ensure that an action only happens under a specific domain and will not cross domains, unless the project team intentionally wants domain crossing to happen. If signing follows the same-origin policy, then even if the user signs a signature request generated by the non-target domain, hackers can't use the signature for attacks under the target domain. I will stop here before going into more details. I have noticed new proposals on security improvement at the protocol level, and I hope this situation can be improved as soon as possible.

We have mentioned most of the major attack formats that could occur when signing a message, but there are actually quite a few variants. No matter how different they look, they follow similar patterns. The best way to understand them is to reproduce an attack from beginning to end by yourselves, or even create some unique attack methods. For example, the signature request attack mentioned here actually contains a lot of details, such as how to construct the message to be signed, and what is generated exactly after signing? Is there any authorization methods other than "Approve" (yes, for example: increaseAllowance). Well, it would be too technical if we expand here. The good thing is you should already understand the importance of signing a message.

Users can prevent such attacks at the source by canceling the authorization/approval. The following are some well-known tools that you could use.

* Token Approvals
    >https://etherscan.io/tokenapprovalchecker<br>
    >This is the tool for authorization check and cancellation provided by Ethereum's official browser. Other EVM compatible blockchains have something similar as their blockchain browsers are basically developed by Etherscan. For example:<br>
    >https://bscscan.com/tokenapprovalchecker<br>
    >https://hecoinfo.com/tokenapprovalchecker<br>
    >https://polygonscan.com/tokenapprovalchecker<br>
    >https://snowtrace.io/tokenapprovalchecker<br>
    >https://cronoscan.com/tokenapprovalchecker

* Revoke.cash
    >https://revoke.cash/<br>
    >Super old school with good fame &Multi-chain Supporting with increasingly power

* Rabby extension wallet
    >https://rabby.io/<br>
    >One of the wallets that we have collaborated with a lot. The number of EVM compatible blockchains where they provide "authorization check and cancellation" function is the most that I have ever seen

:warning:**Note**: If you want a more comprehensive and in-depth understanding of SIGNATURE SECURITY, please check the extensions in the following repository additions as a reference:

>https://github.com/evilcos/darkhandbook<br>
>It is true that the knowledge of SIGNATURE SECURITY is quite challenging for beginners. The repository compiles relevant content, and carefully reading through it will help you grasp the security knowledge. Thus, you will no longer find it difficult. (If you can read and understand everything, I believe that security knowledge will no longer be tough for you :)

### Be CAREFUL With Counter-intuitive Signatures Requests!

I would like to particularly mention another risk: **counter-intuitive risk**.

What is counter-intuitive? For example, you are already very familiar with Ethereum, and have become an OG of all kinds of DeFi and NFTs. When you first enter the Solana ecosystem, you probably would encounter some similar phishing websites. You may feel so well prepared that you start to think "I have seen these a thousand times in the Ethereum ecosystem and how could I get fooled?"

In the meantime, hackers would be happy as you already got fooled. People follow their intuitive feelings which makes them careless. When there's a counter-intuitive attack, people would fall into the trap.

Ok, let's take a look at a real case that took advantage of counter-intuitiveness.

<img src="res/solana_nft_phishing.jpg" width="800">

First of all, a warning: Authorization phishing on Solana is way more cruel. The example above happened on March 5th, 2022. The attackers airdropped NFTs to users in batches (Figure 1). Users entered the target website through the link in the description of the airdropped NFT (www_officialsolanarares_net) and connected their wallets (Figure 2). After they clicked the "Mint" button on the page, the approval window popped up (Figure 3). Note that there was no special notification or message in the pop up window at this time. Once they approved, all SOLs in the wallet would be transferred away.

When users click the "Approve" button, they are actually interacting with the malicious smart contracts deployed by the attackers:
*3VtjHnDuDD1QreJiYNziDsdkeALMT6b2F9j3AXdL4q8v*

The ultimate goal of this malicious smart contract is to initiate "SOL Transfer", which transfers almost all of the user's SOLs. From analysis of on-chain data, the phishing behavior continued for several days, and the number of victims kept increasing during the period of time.

There are two pitfalls from this example that you need to pay attention to:
1. After the user approves, the malicious smart contract can transfer the user's native assets (SOL in this case). This is not possible on Ethereum. The authorization phishing on Ethereum can only affect other tokens but not the native asset of ETH . This is the counter-intuitive part that would make users lower vigilance.
2. The most well-known wallet on Solana, Phantom, has loopholes in its security mechanism that it doesn't follow  the "what you see is what you sign" principle (we haven't tested other wallets yet), and it doesn't provide enough risk warning to users. This could easily create security blind spots that cost users' coins.

### Some Advanced Attacking Methodologies

Actually, there are many advanced attacking methodologies, but they are mostly regarded as phishing from the perspective of the public. However, some are no normal phishing attacks. For example:

>https://twitter.com/Arthur_0x/status/1506167899437686784

Hackers sent a phishing e-mail with such an attachment:
>A Huge Risk of Stablecoin(Protected).docx

To be honest, it is an attractive document. However, once opened user's computer will be implanted with a Trojan (generally through Office macro or 0day / 1day exploit), which usually contains the following functions:

* Collecting all sorts of credentials, for example, browser related, or SSH related, etc. In this way, hackers can extend their access to other services of the target user. Therefore, after infection users are generally advised not only to clean up the target device, but also relevant account permissions as well.
* Keylogger, in particular targeting those temporarily appearing sensitive information such as passwords.
* Collecting relevant screenshots, sensitive files, etc.
* If it is ransomware, all files in the target system would be strongly encrypted, and waiting for the victim to pay for the ransom, usually by bitcoin. But in this case it was not ransomware which has more obvious & noisy behavior and straightforward intentions.

In addition, Trojans targeting the crypto industry will be specially customized to collect sensitive information from well known wallets or exchanges, in order to steal user's funds. According to professional analysis, the above mentioned Trojan would conduct a targeted attack on Metamask:

>https://securelist.com/the-bluenoroff-cryptocurrency-hunt-is-still-on/105488/

The Trojan will replace user's MetaMask with a fake one with back doors. 
A backdoored MetaMask basically means that any funds you store inside are no longer yours. Even if you are using a hardware wallet, this fake MetaMask will manage to steal your funds by manipulating the destination address or amount information. 

This approach is specially crafted for well known targets with known wallet addresses. What I have noticed is that many such people are too arrogant to prevent themselves from getting hacked. After the hack, many would learn from the lesson, conduct full reviews, have significant improvements, and also form  long term cooperation and friendship with trusted security professionals or agencies. However, there are always exceptions in this world. Some people or projects keep getting hacked again and again. If each time it is because of something no one has encountered before, I would highly respect them and call them pioneers. High chance they will be successful as time goes on. Unfortunately many of the incidents are the results of very stupid and repetitive mistakes that could be avoided easily. I would advise staying away from these projects.  

Comparingly, those mass phishing attacks are not comprehensive at all. Attackers would prepare a bunch of similarly looking domain names and spread the payloads by buying accounts, followers, and retweets on Twitter or other social platforms. If managed well, many will fall into the trap. There is really nothing special in this kind of phishing attack,  and normally the attacker will just brutally make the user authorize tokens (including NFT) in order to transfer them away.

There are other kinds of advanced attacks, for example using techniques like XSS, CSRF, Reverse Proxy to smoothen the attack process. I won't elaborate on all of them here, except one very special case (Cloudflare Man-in-the-Middle attack) which is one of the scenarios in Reverse Proxy. There have been real attacks that caused financial loss utilizing this extremely covert method. 

The problem here is not Cloudflare itself being evil or getting hacked. Instead it's the project team's Cloudflare account that gets compromised. Generally the process is like this: If you use Cloudflare, you will notice this "Worker" module in the dashboard, whose official description is:

>Building serverless applications and deploying them instantly around the world, achieving excellent performance, reliability and scale. For details, please refer to
>https://developers.cloudflare.com/workers/

I made a test page a long time ago:

>https://xssor.io/s/x.html

When you visit the page there will be a pop-up window saying:

>xssor.io, Hijacked by Cloudflare.

In fact, this pop-up, and even the whole content of x.html, doesn't belong to the document itself. All of them are provided by Cloudflare. The mechanism is shown below:

<img src="res/cloudflare_worker.png" width="800">

The indication of the code snippet in the screenshot is very simple: If I were the hacker and I have controlled your Cloudflare account, I can use Workers to inject arbitrary malicious script to any web page. And it's very difficult for the users to realize that the target web page has been hijacked and tampered with, as there will be no error alerts (such as HTTPS certificate error). Even the project team won't easily identify the problem without having to spend a huge amount of time checking the security of their servers and personnel. By the time they realise it is Cloudflare Workers, the loss could already be significant. 

Cloudflare is actually a good tool. Many websites or web applications will use it as their web application firewall, anti DDoS solution, global CDN, reverse proxy, etc. Because there is a free version, they have a big customer base. Alternatively, there are services like Akaimai etc. 

Users must pay attention to the security of such accounts. Account security issues arise with the rise of the Internet. It's such a common topic in the world that almost everyone is talking about it everywhere, but still many people are getting hacked because of it. Some root causes might be they don't use a unique strong password for important services (Password managers like 1Password isn't that popular anyway), some might be they don't bother to turn on 2 factor authentication (2FA), or maybe they don't even know of the thingy. Not to mention for some certain services, passwords should be reset at least annually.

All right, this will be the end of this section. You only need to understand that this is indeed a dark forest, and you should know about as many attacking methodologies as possible. After seeing enough on paper, if you have at least fallen into the traps once or twice, you can consider yourself as an amateur security professional (which will benefit yourself anyway). 

## Traditional Privacy Protection

Congratulations, you've made it to this part. Traditional privacy protection is an old topic: 
Here's the article I wrote in 2014.

>You've got to learn a few tricks to protect yourself in the age of privacy breaches.<br>
>https://evilcos.me/yinsi.html

Rereading this article, although this was an entry level article in 2014, however, most of the advice in it is not outdated.After reading the article again, I' ll introduce something new here: in fact, privacy protection is closely related to security.  Traditional privacy is the cornerstone of security. This section includes your private keys are part of privacy. If the cornerstones are not secure, the privacy of the cornerstones are meaningless, then the superstructure will be as fragile as a building in the air.

The following two resources are highly recommended：

>SURVEILLANCE SELF-DEFENSE<br>
>TIPS, TOOLS AND HOW-TOS FOR SAFER ONLINE COMMUNICATIONS<br>
>https://ssd.eff.org/

SURVEILLANCE SELF-DEFENSE is short for SSD. Launched by the well-known Electronic Frontier Foundation (EFF), which has specially issued relevant guidelines to tell you how to avoid big brother watching you in the monitoring Internet world, of which including several useful tools (such as Tor, WhatsApp, Signal, PGP, etc.)

>Privacy Guide: Fight Surveillance with Encryption and Privacy Tools<br>
>https://www.privacytools.io/

The above website is comprehensive listing a number of tools. It also recommends some cryptocurrency exchanges, wallets, etc. However, it should be noted that I don't use very many tools listed on the website, because I have my own way. Thus, you should also develop your own way, with comparing and improving continuously.

Here are some highlights of the tools that I suggest that you should use.

### Operation System

Windows 10 Edition (and higher) and macOS are both secure options. If you have the ability, you can choose Linux, such as Ubuntu, or even extremely security & privacy focused ones like Tails, or Whonix.

On the topic of Operation System, the most straightforward security principle is: pay close attention to system updates, and apply them asap when available. The capability to master the Operating System comes next. People might ask, what on earth do you need to learn in order to master an Operating System like Windows or MacOS? Isn't it just clicking around? Well it's actually far from being enough. For novice users, a good antivirus software, like Kaspersky, BitDefender, is a must, and they both are available on MacOS.  

And then, don't forget about download security, which I mentioned before. You will have eliminated most of the risks, if you don't download and install programs recklessly.  

Next, think about what you are gonna do, if your computer got lost or stolen. Having a boot password is obviously not good enough. If disk encryption is not turned on, bad actors can just take out the harddisk and retrieve the data inside. Thus my advice is that disk encryption should be turned on for important computers.

>https://docs.microsoft.com/en-us/windows/security/encryption-data-protection<br>
>https://support.apple.com/en-us/HT204837

We also have powerful and legendary tools such as VeraCrypt (the former TrueCrypt), feel free to try it out if you are interested:

>https://veracrypt.fr/

You can go one step further to  enable BIOS or firmware password. I have done it myself but it's totally up to your own choice. Just remember: if you do, remember the password very clearly, or else no one can ever help you out. I am lucky enough to have fallen into the rabbit hole myself before, which cost me a laptop, some crypto, and a week's time. On the other hand, it's a very good learning experience too.

### Mobile phone

Nowadays iPhone and Android are the only two mainstream mobile phones categories. I used to be a big fan of BlackBerry, but its glory faded away with time. In the past, the security posture of Android phones worried me a lot. On one hand it was still in the early stage, on the other hand the versions were very fragmented, each brand would have its own forked Android version. But now things have improved a lot.

On mobile phones we also need to pay attention to security updates and download security. In addition, pay attention of the following points:

* Do not jailbreak/root your phone, it's unnecessary unless you are doing relevant security researchIf you are doing it for pirated software it really depends on how well you can master the skill.
* Don't download apps from unofficial app stores.
* Don't do it unless you know what you are doing. Not to mention there are even many fake apps in official app stores.
* The prerequisite of utilising the official Cloud synchronization function, is that you have to make sure your account is secure, otherwise if the Cloud account gets compromised, so will the mobile phone.

Personally I rely more on the iPhone. And you will need at least two iCloud accounts: one China and one overseas. You will need them to install apps with different regional restrictions. (which sounds pretty weird but welcome to the reality)

### Network

Network security issues used to be a pain in the ass, but there are already significant improvements in recent years, especially since the mass adoption of HTTPS Everywhere policy. 

In case of an ongoing network hijacking (man-in-the-middle attack) attack, there will be  corresponding system error alerts. But there are always exceptions, so when you have a choice use the more secure option. For example, don't connect to unfamiliar Wi-Fi networks unless the more popular & secure 4G/5G network is not available or not stable.  

### Browsers

The most popular browsers are Chrome and Firefox, in crypto fields some will use Brave too. These well known browsers have a strong team and there will be timely security updates. The topic of browser security is very broad. Here are some tips for you to be aware of:

* Update as quickly as possible, don't take chances.
* Don't use an extension if not necessary. If you do, make your decisions based on user's reviews, number of users, maintaining company, etc, and pay attention to the permission it asks for. Make sure you get the extension from your browser's official app store.
* Multiple browsers can be used in parallel, and it is strongly recommended that you perform important operations in one browser, and use another browser for more routine, less important operations.
* Here are some well-known privacy focused extensions (such as uBlock Origin, HTTPS Everywhere, ClearURLs, etc.), feel free to try them out.

In Firefox in particular, I will also use the legendary ancient extension NoScript, which had a  proven record of fending off malicious JavaScript payloads. Nowadays browsers are becoming more and more secure as they add support for things like  same-origin policy, CSP, Cookie security policy, HTTP security headers, extension security policy, etc. Thus the need of using a tool such as NoScript is becoming smaller and smaller, feel free to take a look if interested.

### Password Manager

If you haven't used a password manager yet, either you don't know the convenience of using one, or you have your own strong memory palace. The risk of brain memory has also been mentioned before, one is that time will weaken or disrupt your memory; the other is that you may have an accident. In either case, I still recommend that you use a password manager to go with  your brain memory, use a well-known one like 1Password, Bitwarden, etc.

I don't need to cover this part too much, there are so many related tutorials online, it's easy to get started without even needing a tutorial.

What I need to remind you here is:

* Do not ever forget your master password, and keep your account information safe, otherwise everything will be lost.
* Make sure your email is secure. If your email is compromised, it might not directly compromise the sensitive information in your password manager, but bad actors have the capability to destroy it.
* I have verified the security of the tools I mentioned (such as 1Password), and have been closely watching the relevant security incidents, user reviews, news, etc. But I cannot guarantee that these tools are absolutely secure, and no black swan events are ever gonna happen in the future to them.
 
One thing I do appreciate is the introduction and description of 1Password's security page, for example.
>https://1password.com/security/
  
This page has security design concepts, relevant privacy and security certificates,  security design white papers, security audit reports, etc. This level of  transparency and openness also facilitates the necessary validation in the industry. All project teams should learn from this. 

Bitwarden goes one step further, as it is fully open source, including the server side, so anyone can validate, audit, and contribute. Now you see? The intention of 1Password and Bitwarden is very clear: 

>I am very secure and I am concerned about privacy. Not only do I say it myself, third party authorities say so as well. Feel free to audit me, and in order to make it easy for your audits, I spend a lot of effort to be open wherever possible. If what I do doesn't match what I say, it's easy to challenge me. And this is called Security Confidence.

### Two-Factor Authentication

Speaking of your identity security on the Internet, the first layer relies on passwords, the second layer relies on two factor authentication, and the third layer relies on the risk control ability of the target project itself. I can't say that two factor authentication is a must-have. For example, if you are using a decentralized wallet, one layer of password is annoying enough (now they basically support biometric identification such as facial recognition or fingerprint to improve user experiences), no one wants to use the second factor. But in a centralized platform, you have to use 2FA. Anyone can access the centralized platform, and if your credentials get stolen, your account is breached and your fund will be lost. On the contrary, the password for your decentralized wallet is just a local authentication, even if the hacker gets the password, they still need to get access to the device where your wallet is located.

Now you see the differences?Some well-known two-factor authentication (2FA) tools include: Google Authenticator, Microsoft Authenticator, etc. Of course, if you use a password manager (such as 1Password), it also comes with a 2FA module, which is very handy. Always remember to make backups, because losing 2FA can be a hassle.

In addition, two-factor authentication can also be a broader concept. For example, when an account identifier and a password are used to log in to the target platform, our account identifier is normally an email or mobile phone number. At this time, the mailbox or mobile phone number can be used as  2FAto receive a verification code. But the security level of this method is not as good. For example, if the mailbox is compromised or the SIM card gets hijacked, or the third-party service used for sending emails and text messages is hacked, then the verification code sent by the platform will also be revealed.

### Scientific Internet Surfing

For policy reasons, let's not talk too much about this, just pick one of the well-known solutions. Things will be more under control if you can build your own solution.After all, our starting point is to surf the Internet scientifically and securely.

If you are not using a self-built solution, you can't fully rule out the possibility of a man-in-the-middle attack. As mentioned earlier, the Internet security situation is not as bad as it used to be, especially after the mass adoption of HTTPS Everywhere policy. However, some of the peace may be just the surface of the water, and there are already undercurrents beneath the surface that are not easily noticeable. To be honest, I don't really have a silver bullet for this. It's not easy to build your own solution, but it's definitely worth it. And if you can't, make sure you check using multiple sources and choose a reputable one that has been around for a long time.

### Email

Email is the cornerstone of our web based identity. We use email to sign up for a lot of services. Almost all of the email services we use are free. It seems like air, and you don't think it would disappear. What if one day your Email service is gone, then all the other services that depend on it will be in a rather awkward situation.  This extreme situation is really not impossible if there're wars, natural disasters, etc. Of course, if these extreme situations occur, Email will be less important to you than survival.

When it comes to Email services providers, you should choose from tech giants, such as Gmail, Outlook, or QQ Email. It happens that my previous security researches cover this area. The security posture of these mailboxes is good enough. But still you have to be careful about Email phishing attacks. You don't need to deal with every single Email, especially the embedded links and attachments, where Trojans may be hidden.

If you come across a highly sophiscatedattack on your Email services providers, you're on your own.

Besides the email services of these tech giants, if you are very concerned about privacy, you can take a look at  these two well-known privacy-friendly email services: ProtonMail and Tutanota. My suggestion is to separate  these private-friendly mailbox from daily usage, and only use them for services that requires special attention to privacy. You also need to regularly use your free Email services to prevent yout accounts from being suspended due to long time inactivity.  

### SIM Card

SIM card and mobile phone number are also very important basic identities in many cases, just like email. In recent years, the major operators in our country have done a very good job in the security protection of mobile phone numbers. For example, there are strict security protocols & verification processes for canceling and re-issuing SIM cards, and they all happen on site. On the topic of SIM card attacks , let me give you an example:

In 2019.5, someone's Coinbase account suffered a SIM Port Attack (SIM card transfer attack), and unfortunately lost more than 100,000 US dollars of cryptocurrency. The attack process is roughly as follows:

The attacker obtained the privacy information of the target user through social engineering and other methods, and tricked the Mobile phone operator to issue him a new SIM card, and then he easily took over the target user's Coinbase account  through the same mobile phone number. The SIM has been transferred, which is very troublesome. It's very troublesome if your SIM card got transferred by the attacker, as nowadays, many of the online services use our mobile phone number as a direct authentication factor or 2FA. This is a very centralized authentication mechanism, and the mobile phone number becomes the weak point.

For detailed analysis, please refer to:
>https://medium.com/coinmonks/the-most-expensive-lesson-of-my-life-details-of-sim-port-hack-35de11517124

The defence suggestion for this is actually simple:enable a well-known 2FA solution.

The SIM card has another risk:that is, if the phone is lost or stolen, it will be embarrassing that the bad guy can take out the SIM card and use it. Here is what I did: Enable the SIM card password (PIN code), so every time when I turn on my phone or use my SIM card in a new device, I need to enter the correct password. Please ask Google for detailed howtos.  Here's the reminder from me: don't forget this password, otherwise it will be very troublesome.

### GPG

Many contents in this part have been mentioned in previous sections, and I woud like to add more basic concepts here.: Sometimes you will encounter similar-looking names such as PGP, OpenPGP, and GPG. Simply distinguish them as follows:

* PGP, short for Pretty Good Privacy, is a 30-year-old commercial encryption software now under the umbrella of Symantec.
* OpenPGP is an encryption standard derived from PGP.
* GPG, the full name is GnuPG, is an open source encryption software based on the OpenPGP standard.

Their cores are similar, and with GPG you are compatible with the others. Here I strongly recommend again: In security encryption, don't try to reinvent the wheel; GPG, if used in a correct way, can improve security level significantly!

### Segregation

The core value behind the security principle of segregation, is the zero trust mindset. 
You have to understand that no matter how strong we are, we will be hacked sooner or later, no matter if it's by external hackers, insiders or ourselves. When hacked, stop loss should be the first step. The ability to stop loss is ignored by many people, and that's why they get hacked again and again. The root cause is that there is no security design, especially straightforward methods such as segregation

A good segregation practice can ensure that in case of security incidents, you only lose those directly related to the compromised target, without affecting other assets.

For example:
* If your password security practice is good, when one of your accounts gets hacked, the same password will not compromise other accounts.
* If your cryptocurrency is not stored under one set of mnemonic seeds, you will not lose everything if you ever step into a trap.
* If your computer is infected, luckily this is just a computer used for casual activities, and there is nothing important in there So you do not have to panic, as reinstalling the computer would solve most of the problems. If you are good at using virtual machines, things are even better, as you can just restore the snapshot. Good virtual machine tools are: VMware, Parallels.
* To summarize, you can have at least two accounts, two tools, two devices, etc. It is not impossible to completely create an independent virtual identity after you are familiar with it.

I mentioned a more extreme opinion before: privacy is not for us to protect, privacy should be controlled.

The reason for this viewpoint is that: in the current Internet environment, privacy has actually been leaked seriously. Fortunately, privacy-related regulations have become more and more widely adopted in recent years, and people are paying more and more attention. Everything is indeed going in the right direction. But before that, in any case, when you have mastered the knowledge points I have listed, you will be able to control your privacy with ease. On the Internet, if you are used to it, you may have several virtual identities that are almost independent of each other.

## Security of Human Nature

Human is always at the highest and eternal risk. There's a quote from The Three-Body Problem: "Weakness and ignorance are not barriers to survival, but arrogance is."

* Don't be arrogant: If you think you're already strong, you're fine with yourself. Don't look down on the whole world. In particular, don't be overly proud and think you can challenge global hackers. There is no end to learning, and there are still many obstacles.
* Don't be greedy: Greed is indeed the motivation to move forward in many cases, but think about it, why is such a good opportunity just reserved for you?
* Don't be impulsive: impulsiveness is the devil which will lead you to traps. Rash action is gambling.

There are endless things  in human nature to talk about and you can't be more careful. Please pay special attention to the following points, and see how bad actors take advantage of the weakness in human nature, utilizing various convenient platforms.

### Telegram

I've said before that Telegram is the biggest dark web. I have to say that people like Telegram for its security, stability, and open design features. But the open culture of Telegram also attracts bad guys: huge numbers of users, highly customisable functionality,  easy enough to build all kinds of Bot services. Combining with cryptocurrency, the actual trading experiences are far beyond those dark web marketplaces in Tor. And there are too many fishes in it.

Normally, the unique identifier of social media accounts is only something like a username, user id, but these can be completely cloned by the bad actors. Some social platforms have account validation mechanisms, such as adding a blue V icon or something. Public social media accounts can be validated through some indicators, such as the follower's number, the contents posted, interaction with fans, etc. The non-public social media accounts are a bit more difficult. It's nice to see that Telegram released the function of "Which Groups we are in together".

Wherever there are loopholes that can be exploited and the gains are considerable, a bunch of bad guys must be already there, that's human nature.

As a result, social media platforms are full of phishing traps. For example: In a group chat, someone who looks like the official customer service suddenly appeared and started a private chat (any2any private chat is the feature of Telegram, there is no need for friend request), and then out of the classic tactics of spam, fish will bite  one after another.

Or attackers might go one step further, and add you into another group. All participants buy you are fake, but to you it looks so realistic.   We refer to this technique as Group Cloning in underground society.

These are just the basic methods of manipulating human nature, the advanced techniques will be combined with vulnerabilities and thus are more difficult to prevent.

### Discord

Discord is a new and popular social platform/IM software raised in the past two years. The core function is community servers (not the concept of traditional server), as the official statement says:

Discord is a free voice, video, and text chat app that's used by tens of millions of people ages 13+ to talk and hang out with their communities and friends. 

People use Discord daily to talk about many things, ranging from art projects and family trips to homework and mental health support. It's a home for communities of any size, but it's most widely used by small and active groups of people who talk regularly.

It looks great but requires a quite strong security design standard. Discord has specific security rules and policies as in:

>https://discord.com/safety

Unfortunately, most people will not bother to read it carefully. What's more, Discord won't always be able to illustrate certain core security issues clearly, because they will have to put on an attacker's hat which is not always feasible.

For instance:

With so many NFT thefts on Discord, what are the key attack methods? Before we figure this out, Discord security advice is useless.

The key reason behind many  project  Discordhacks is actually the Discord Token, which is the content of the authorization field in the HTTP request header. It has existed in Discord for a very long time. For hackers, if they can find a way to get this Discord Token, they can almost control all the privileges of the target Discord server. That is to say, if the target is an administrator, an account with administrative privileges or a Discord bot , the hackers can do anything they want to. For example by announcing a NFT phishing site, they make people think it's the official announcement, and fish will bite the hook.

Some might ask, what if I add two-factor authentication (2FA) to my Discord account? Absolutely a good habit! But Discord Token has nothing to do with your account 2FA status. Once your account is breached, you should change your Discord password immediately to make the original Discord Token invalid.

For the question of how the hacker can get the Discord Token, we have figured out at least three major techniques, and we will try to explain it in detail in the future . For normal users, there are a lot that can be done, but the core points are: don't rush, don't be greedy, and verify from multiple sources.

### "Official" phishing

The bad actors are good at taking advantage of role playing, especially the official role. For example we have mentioned the fake customer service method before. Besides that, in April 2022, many users of the well-known hardware wallet Trezor, received phishing emails from trezor.us, which is not the official Trezor domain trezor.io. There is a minor difference in the domain name suffix. What's more, the following domains were also spread via phishing emails.

>https://suite.trẹzor.com

<img src="res/trezor_phishing.jpg" width="800">

This domain name has a "highlight spot", look closely at the letter ẹ in it, and you can find that is not the letter e. Confusing? It is actually Punycode, the standard description is as below:

>A Bootstring encoding of Unicode for Internationalized Domain Names in Applications (IDNA)
>is an internationalized domain name encoding that represents a limited set of characters in both Unicode and ASCII codes.

If someone decode trẹzor, it looks like this: xn-trzor-o51b, which is the real domain name!

Hackers have been using Punycode for phishing for years, back in 2018, some Binance users were compromised by the same trick.

These kinds of  phishing sites can already make many people fall, not to mention those more advanced attacks such as official mailbox getting controlled, or mail forgery attacks caused by SPF configuration issues. As a result, the source of the email looks exactly the same as the official one.

If it is a rogue insider, the user can do nothing. project teams should put a lot of effort into preventing insider threats. Insiders are the biggest Trojan horse, but they very often get neglected.

### Web3 Privacy Issues

With the growing popularity of Web3, more and more interesting or boring projects appeared: like all kinds of Web3 infrastructures, social platforms, etc. Some of them have done massive data analysis and identified various behavioral portraits of the targets, not only on the blockchain side, but also on well-known Web2 platforms. Once the portrait comes out, the target is basically a transparent person. And the appearance of Web3 social platforms may also aggravate such privacy issues.

Think about it, when you play around with all these Web3-related things, such as signature binding, on chain interactions, etc., are you giving away more of your privacy? Many might not agree, but as many pieces come together there will be a more accurate & comprehensive picture: which NFTs you like to collect, which communities you joined, which whitelists you're on, who you're connected with, which Web2 accounts you're bound to, what time periods you're active in, and so on. See, blockchain sometimes makes privacy worse. If you care about privacy, you will have to be careful with everything newly emerged and keep the good habit of segregating your identity.

At this point, if the private key is accidentally stolen, the loss is not as simple as just money, but all the carefully maintained Web3 rights and interests. We often say that the private key is the identity, and now you have a real ID problem.

Never test human nature.

# Blockchain Shenanigans

Blockchain technology created a whole new industry. Whether you call it BlockFi, DeFi, cryptocurrency, virtual currency, digital currency, Web3, etc, the core of everything is still the blockchain.  Most hype centered on financial activities, such as crypto assets, including non-fungible tokens (or NFT, digital collectible). 

Blockchain industry is highly dynamic and fascinating, but there are just too many ways to do evil. The special characteristics of blockchain give rise to some rather unique evils, including and not limited to crypto theft, cryptojacking, ransomware, dark web trading, C2 attack, money laundering, Ponzi schemes, gambling, etc. I made a mind map back in 2019 for reference.

>https://github.com/slowmist/Knowledge-Base/blob/master/mindmaps/evil_blockchain.png

Meanwhile, the SlowMist team has been maintaining and updating SlowMist Hacked - an growing database for blockchain-related hacking activities.

>https://hacked.slowmist.io/

This handbook has introduced many security measures, and if you can apply them to your own security, then congratulations. I won't elaborate too much on the blockchain shenanigans. If you are interested, you can learn it on your own, which is definitely a good thing, especially since new scams and frauds are continuously evolving. The more you learn, the better you can defend yourself and make this industry better.

# What to do If Your Computer Gets Infected

Several hacker groups employ computer poisoning, often not through advanced zero-day techniques (like browser zero-days) but via social engineering induction. Examples include posing as investors, journalists, HR, etc., to trick users into installing fake conference software. Other methods involve impersonating "Telegram Safeguard" or requiring "Cloudflare human verification" to trick users into pasting malicious code locally.

Examples of such tactics can be found here:
> https://x.com/SlowMist_Team/status/1899713751625969997<br>
> https://x.com/SlowMist_Team/status/1880520294496104827<br>
> https://x.com/SlowMist_Team/status/1888879128172241000

If you fall victim to such an attack, adopting a cautious approach and avoiding putting yourself in a precarious position is recommended. You should take the following steps:

1. If you have wallets in use on your computer (including private key/mnemonic phrase backup files), you should promptly and securely transfer the funds from them. Don't assume having a password is sufficient.
2. Change the passwords and 2FA for important accounts on your computer, such as Telegram/X/email/exchange accounts etc. (including saved passwords/logged-in accounts in browsers), and check these accounts for unknown device logins. Do not rely on luck.
3. Install reputable antivirus software such as AVG/Bitdefender/Kaspersky/Malwarebytes etc., and thoroughly scan your computer. Decide which one to use, ideally a paid version. If you are still concerned, consider purchasing two and using them alternately.
4. If you are still worried, back up your important files etc., and then you can reset your computer... Afterward, return to the previous step (step 3) and scan your backup files with antivirus.

It's worth noting that these poisoning attacks target not only Windows but also Mac computers, and are sometimes compatible with parts of Linux.

# What to do When You get hacked

It is only a matter of time before you eventually get hacked. So what to do then? I'll simply cut straight to the chase. The following steps are not necessarily in order; there are times when you have to go back and forth, but the general idea is this.

## Stop Loss First

Stop loss is about limiting your loss. It can be broken down to at least two phases.

* The Immediate Action Phase. Act immediately! If you see hackers are transferring your assets, think no more. Just Hurry up and transfer the remaining assets to a safe place. If you have experience in front running trades, just grab and run. Depending on the type of asset, if you can freeze your assets on the blockchain, do it as soon as possible; if you can do on-chain analysis and find your assets are transferred into a centralized exchange, you can contact their risk control department.
* The Post-Action Phase. Once the situation is stabilized, your focus should be on making sure there would not be secondary or tertiary attacks.

## Protect The Scene

When you find that something is wrong, stay calm and take a deep breath. Do remember to protect the scene. Here are a few suggestions:

* If the accident happens on a computer, server or other devices connected to the Internet, disconnect the network immediately while keeping the devices on with power supply. Some people may claim that if it is a destructive virus, the local system files will be destroyed by the virus. They are right, however shutting down only helps if you can react faster than the virus...
* Unless you are capable of handling this by yourself, waiting for security professionals to step in for analysis is always the better choice.

This is really important as we have encountered quite a few times that the scene was already in a mess by the time we stepped in to do the analysis. And there were even cases when key evidence (e.g. logs, virus files) appeared to have been cleaned up. Without a well-preserved crime scene, it can be extremely disruptive to the subsequent analysis and tracing.

## Root Cause Analysis

The purpose of analyzing the cause is to understand the adversary and output the hacker's portrait. At this point, the incident report is very important, which is also called Post Mortem Report. Incident Report and Post Mortem Report refer to the same thing.

We have met so many people who came to us for help after their coins were stolen, and it was very difficult for many of them to clearly tell what happened. It's even harder for them to produce a clear incident report. But I think this can be practiced and it would be helpful by referring to examples.  The following can be a good starting point:

* Summary 1: Who was involved, when did this happen , what has happened, and how much was the total loss?
* Summary 2: The wallet addresses related to the loss, the wallet address of the hacker, the type of the coin, the quantity of the coin. It could be much clearer with the help of just a single table.
* Process description: this part is the most difficult. You will need to describe all aspects of the incident with all the details, which is useful to analyze various kinds of traces related to the hacker and eventually get the hacker portrait from them (including the motivation)

When it comes to particular cases, the template will be much more complex. Sometimes human memory can also be unreliable, and there is even a deliberate concealment of key information which can lead to wasted time or delayed timing. So in practice, there would be a huge consumption and we need to use our experience to guide the work well. Finally we produce an incident report with the person or the team who lost the coins, and continue to keep this incident report updated.

## Source Tracing

According to Rocca's Law, where there is an invasion, there is a trail. If we investigate hard enough, we will always find some clues. The process of investigation is actually forensic analysis and source tracing. We will trace the sources according to the hacker portrait from the forensic analysis, and constantly enrich it, which is a dynamic and iterative process.

Source tracing consists of two main parts:

* On-chain intelligence. We analyze the asset activities of the wallet addresses, such as going into centralized exchanges, coin mixers, etc., monitor it and get alerts of new transfers.
* Off-chain intelligence: this part covers the hacker's IP, device information, email address and more information from the correlation of these associated points, including behavioral information.

There is plenty of source tracing work based on this information, and it would even require the involvement of law enforcement.

## Conclusion of Cases

Of course we all want a happy ending, and here are some examples of publicly-disclosed events that we have involved which have good results:

* Lendf.Me, Worth of $25 million
* SIL Finance, Worth of $12.15 million
* Poly Network, Worth of $610 million

We have experienced many other unpublished cases that ended in good or okay results. However most of them had bad endings, which is quite unfortunate. We've gained a lot of valuable experiences in these processes and we hope to raise the ratio of good endings in the future.

This part is briefly mentioned as above. There is a huge amount of knowledge related to this area and I'm not quite familiar with some of it. Thus, I'm not going to give a detailed explanation here. Depending on the scenario, the abilities we need to master are:

* Smart Contract Security Analysis and Forensics
* Analysis and forensics of on-chain fund transfers
* Web Security Analysis and Forensics
* Linux Server Security Analysis and Forensics
* Windows Security Analysis and Forensics
* macOS Security Analysis and Forensics
* Mobile Security Analysis and Forensics
* Malicious code analysis and forensics
* Security analysis and forensics of network devices or platforms
* Insider security analysis and forensics
* ...

It covers almost every aspect of security and so does this handbook. However, those security points are only briefly mentioned here as an Introductory guide.

# Misconception

From the very beginning, this handbook tells you to stay skeptical! This includes everything mentioned in here. This is an extremely vibrant and promising industry, full of all kinds of traps and chaos. Here let's take a look at some of the misconceptions, which, if taken for granted as truth, can easily make you fall into the traps and become part of the chaos itself.

## Code Is Law

Code is law. However, when a project (especially smart contract related ones) gets hacked or rugged, no single victim would ever wish for "Code Is Law", and it turns out they still need to rely on the law in the real world.

## Not Your Keys, Not Your Coins

If you don't own your keys, you don't own your coins. As a matter of fact, many users failed to properly manage their own private keys. Due to various security mispractices they even lose their crypto assets. Sometimes you will find that it's actually more secure to put your crypto asset in big and reputable platforms.

## In Blockchain We Trust

We trust it because it's blockchain. In fact, blockchain itself does have the capability to solve many of the fundamental trust issues, since it's tamper-proof, censorship-resistant, etc; if my asset and related activities are on chain, I can trust by default that no one else will be able to take away my asset or tamper with my activity without authorization. However the reality is often harsh, firstly not every blockchain is able to achieve these fundamental points, and secondly human nature always becomes the weakest link. Many of the hacking techniques nowadays are beyond the imagination of most of us. Though we always say that attack and defense is the balance between cost and impact, when you don't own a big asset no hacker will waste time to target you. But when there are multiple targets like yourself, it will be very profitable for the hackers to launch the attack. 

My security advice is very simple: Distrust by default (that is, question everything by default), and conduct continuous verification. Verify is the key security action here, and continuous verification basically means that security is never in a static state, it's secure now doesn't mean it's secure tomorrow. The capability to properly verify is hereby the biggest challenge for us all, but it's quite interesting, as you will get to master a lot of knowledge in the process. When you are strong enough, no one can easily harm you. 

## Cryptographic Security is Security

Cryptography is powerful and important. Without all the hard work of cryptographers, all the solid cryptographic algorithms & engineering implementations, there will be no modern communications technology, Internet, or blockchain technology. However, some individuals consider cryptographic security as absolute security. And thus a bunch of weird questions arises: 

Isn't blockchain so secure, that it took trillions of years to break a private key? How come the FBI could decrypt Dark Web Bitcoin? Why on earth could Jay Chou's NFT get stolen?

I can bear with these novice questions... what I can't bear with is the fact that many so-called security professionals use cryptographic security concepts to fool the public, they are mentioning terms such as military-grade encryption, world's best encryption, cosmic-level encryption, absolute system security, unhackability, etc. 

Hackers? They don't give a shit...

## Is it humiliating to be hacked?

It is true that getting hacked can bring mixed feelings, and there will be a sense of shame sometimes. But you need to understand that getting hacked is almost  100% guaranteed so there is nothing to be ashamed of. 

Once getting hacked, it doesn't matter if you are only responsible for yourself. However, if you are responsible for many others, you have to be transparent and open when you are dealing with the incident. 

Although people may question or even accuse you of staging the hack by yourself, a transparent and open updated process will always bring good luck and understanding.

Think of it this way: if your project isn't well-known, no one will hack you. The shame is not being hacked; the shame is your arrogance.

From a probability point of view, getting hacked is a common phenomenon, normally, the majority of the security issues are just small problems, which could help your project grow. However, the severe big problems still have to be avoided as much as possible.

## Immediately Update

For many times this handbook suggests to pay attention to updating. If there is a security update available, apply it immediately. Now think carefully, is this a silver bullet?

Actually, in most cases, "update now" is the right thing to do . However, there have been times in history when an update solves one problem but introduces another. An example is iPhone and Google Authenticator:

There is a risk of the new iOS 15 update, that is, the information in Google Authenticator may be wiped or doubled after the iPhone upgrade. In this case, never delete the duplicate entries if you find that they are doubled, as it may cause the loss of all the information in Google Authenticator after reopening.

For those who have not upgraded to the iOS 15 system and are using Google Authenticator, it is highly recommended to back it up before upgrading.

Later, Google has updated the Authenticator app, solving this problem permanently.

Besides, I don't recommend updating wallets frequently, especially for asset-heavy wallets, unless there is a major security patch, or a very important feature that leads to an inevitable update.  in which cases you will have to do your own risk assessment and make your own decision.

# Conclusion

Recall that this handbook starts with this diagram :)

![](res/web3_hacking_map.jpg)

Have you noticed that I have marked in red the person in the diagram?, I do so to remind everybody again that humans are the foundation of all (referred to as "anthropic principle" in cosmology). No matter if it's human nature security, or the ability to master security skills, it all depends on you.  Yes, when you are strong enough, no one can easily harm you. 

I started to expand based on the diagram, and explained many security key points in the three processes, creating wallet, backing up wallet and using wallet. Then I introduced traditional privacy protection. I stated that such traditional ones are the cornerstones and the building blocks for us to stay secure in blockchain ecosystems. The human nature security part cannot be overdressed. It's good to understand more about the various ways of doing evil, especially if you step into a few pits, the security awareness on paper may eventually become your security experience. There is no absolute security, so I explained what to do when you get hacked. I don't want an unfortunate event to happen to you, but in case it happens, I hope this handbook could help you. The last thing is to talk about some misconceptions. My intention is very simple, I hope you can build up your own critical thinking, because the world is both beautiful and terrible. 

I have not written so many words for a long time. I think the last time was 10 years ago when I wrote the book "*Web 前端黑客技术揭秘*".  It was quite bittersweet. After many years in web security as well as cybersecurity, I led a team to create ZoomEye, a cyberspace search engine. Within cybersecurity, I have dabbled in many fields, only a few of which I can say that I am skilled at. 

Now in blockchain security, SlowMist and myself are considered to be pioneers . There are so many cases we have encountered in these years that you can almost think we are in a state of trance every single day. It's a pity that many insights are not recorded and shared. And as a result, at the urging of several friends, this handbook was born. 

When you have finished reading this handbook, you must practice, become proficient and draw inferences. When you have your own discovery or experience afterwards, I hope you will contribute. If you feel there is sensitive information you can mask them out, or anonymise the information.

Finally, thanks to the global maturity of security and privacy-related legislation and enforcement; thanks to the efforts of all the pioneering cryptographers, engineers, ethical hackers and all those involved in the creation of a better world, which includes Satoshi Nakamoto.

# Appendix

## Security rules and principles

The security rules and principles mentioned in this handbook are summarized as follows. Quite a few rules are being incorporated into the above text and will not be specifically refined here.

Two major security rules:

* **Zero trust**. To make it simple, stay skeptical, and always stay so.
* **Continuous validation**. In order to trust something, you have to validate what you doubt, and make validating a habit.

Security principles:

* For all the knowledge from the Internet, refer to at least two sources,  corroborate each other, and always stay skeptical.
* Segregate. Don't put all the eggs in one basket.
* For wallets with important assets, don't do unnecessary updates.
* What you see is what you sign. You need to be aware of what you are signing, and of the expected result after the signed transaction is sent out. Don't do things that will make you regret afterwards.
* Pay attention to system security updates. Apply them as soon as they are available.
* Don't download & install programs recklessly can  actually prevent most risks.

## Contributors

Thanks to all the contributors, this list will continue to be updated. If you have any ideas, please contact:

>Cos, Twitter([@evilcos](https://twitter.com/evilcos))、Jike  App(@余弦.jpg)

Contributors:
```
My wife
SlowMist, Twitter (@SlowMist_Team), e.g. Pds | Johan | Kong | Kirk | Thinking | Blue | Lisa | Keywolf...
English translator, e.g. Alphatu | C. | CJ | JZ | Lovepeace | Neethan | pseudoyu | SassyPanda | ss |
Japanese translator, e.g. Jack Jia | Mia
Korean translator, e.g. Sharon | Jeongmin
Arabic translator, e.g. Ahmed Alsayadi | Gabr Alsayadi
Indonesian translator, e.g. Finball
Jike App
Some Anonymous friends...
More info: https://darkhandbook.io/contributors.html
```

**As long as there is help that is adopted and included in this handbook, such as: providing specific defense suggestions and cases; translation work; correction of major errors, etc.**

## The Tools

This handbook, commonly referred to as the "Dark Handbook," has been available for over two years, and I'm delighted to observe its helpful impact on many individuals. Its influence continues to expand, with a growing number of supporters advocating for updates. Typically, these updates to the Dark Handbook primarily consist of [expanded readings](https://github.com/evilcos/darkhandbook). The challenge with these extended readings is that they are technically complex and not very accessible for beginners. Additionally, I recognize that not everyone is keen to invest substantial time in mastering the nuances of blockchain security. Originally, this section aimed to recommend some beginner-friendly tools, such as wallets, security extensions, and scripting tools. However, after much deliberation, I have decided against endorsing specific products due to the swift pace of change within the industry. Although this manual has highlighted several reliable tools, it's uncertain whether they will remain effective or relevant in the future. Given my responsibility towards all readers, I must admit, I'm not sure.

As I've stated previously, when recommending a tool, I strive to describe it as objectively and neutrally as possible. Additionally, for enhanced security, every reader should bear in mind the following:

　*　Absolute security does not exist. Adopting a zero-trust approach with continuous verification is essential in navigating this complex landscape. Should any of these tools develop a bug, encounter a security issue, or, in a worse scenario, include a backdoor in a new update, the risk is yours to manage. I encourage you to think independently and critically before using these tools.
  
　*　My research skills are well-honed, and I have a broad network, so rest assured that I will recommend quality tools when it seems appropriate. There is no need to rush; if a tool proves reliable and earns widespread trust, I will naturally endorse it.
 
　*　Everyone has their unique approach, and this is mine.
 
　*　Stay away from the influence of coin prices.
 
　*  Trust is hard to build, but it can collapse in an instant, so please cherish it.

Although I do not make any specific tool recommendations in this section, I would like to share a valuable mindset: the firewall mindset. The previously emphasized concepts of "zero trust" and "continuous verification" are actually part of this firewall thinking.

For example, in the use of wallets, signing is a major area of concern for fund security, with various sophisticated phishing methods related to signing, such as:

- The exploitation of native signing with eth_sign/personal_sign/eth_signTypedData_*, where eth_sign has been increasingly blocked by wallets.
- The exploitation of authorization functions like approve/permit for Tokens/NFTs.
- The utilization of powerful functions like Uniswap’s swapExactTokensForTokens/permit2.
- The exploitation of protocol functions from OpenSea/Blur and others (which are very diverse).
- The exploitation of TX data 4byte, such as for Claim Rewards/Security Update.
- Using Create2 to pre-create funding receiving addresses, bypassing related checks.
- A single signature on Solana phishing away all assets in a target wallet address.
- Bitcoin inscription for one-click mass phishing, utilizing the UTXO mechanism.
- Switching phishing across various EVM chains/Solana/Tron, etc.

If your wallet, when prompting for signature confirmation, sends out the signature right after a single click—whether due to FOMO or a shaky hand—then this method of using the wallet does not embody the firewall mindset. A better practice is to require at least two clicks; each additional click adds a layer of security (of course, not too many layers, as people can become desensitized...). For example, I use browser extension wallets like Rabby, MetaMask, and OKX Wallet, and except for test wallets, I always pair these with a hardware wallet (preferably one with a larger screen to easily review the content about to be signed).

At this point, the extension wallet’s signature confirmation popup will perform the first layer of security analysis, such as identifying phishing sites, risky wallet addresses, what-you-see-is-what-you-sign, and high-risk signature recognition. These are crucial for user interaction security. The hardware wallet provides a second layer of security analysis. If you then add a browser wallet security extension like Scam Sniffer, Wallet Guard, or Pocket Universe, you add another layer to your firewall. However, it’s essential to remember, even if there are no risk alerts for the action you are undertaking, you must still be vigilant and recognize that ultimately, you are your own last line of defense...

Once accustomed to the firewall mindset, the impact on efficiency is minimal, but the sense of security is greatly enhanced. Let’s generalize this approach to other scenarios.

That’s all,Thank you!

## Official Sites
```
SlowMist https://www.slowmist.com
CoinMarketCap https://coinmarketcap.com/
Sparrow Wallet https://sparrowwallet.com/
MetaMask https://metamask.io/
imToken https://token.im/
Trust Wallet https://trustwallet.com/
TokenPocket https://www.tokenpocket.pro/
Gnosis Safe https://gnosis-safe.io/
ZenGo https://zengo.com/
Fireblocks https://www.fireblocks.com/
Safeheron https://www.safeheron.com/
Keystone https://keyst.one/
Trezor https://trezor.io/
OneKey https://onekey.so/
imKey https://imkey.im/
Rabby https://rabby.io/
OKX Wallet https://www.okx.com/web3
EdgeWallet https://edge.app/
MyEtherWallet https://www.myetherwallet.com/
Phantom https://phantom.app/
Tornado Cash https://tornado.cash/
Binance https://www.binance.com/
Coinbase https://coinbase.com
Compound https://compound.finance/
SushiSwap https://www.sushi.com/
OpenSea https://opensea.io/
Revoke.cash https://revoke.cash/
Scam Sniffer https://www.scamsniffer.io/
Wallet Guard https://www.walletguard.app/
Pocket Universe https://www.pocketuniverse.app/

Jike App https://okjike.com/
AVG https://www.avg.com/
Bitdefender https://www.bitdefender.com/
Kaspersky https://www.kaspersky.com.cn/
Malwarebytes https://www.malwarebytes.com/
Cloudflare https://www.cloudflare.com/
Akamai https://www.akamai.com/
SURVEILLANCE SELF-DEFENSE https://ssd.eff.org/
Privacy Guide https://www.privacytools.io/
OpenPGP https://www.openpgp.org/
GPG https://gnupg.org/
GPG Suite https://gpgtools.org/
Gpg4win https://www.gpg4win.org/
1Password https://1password.com/
Bitwarden https://bitwarden.com/
Google Authenticator https://support.google.com/accounts/answer/1066447
Microsoft Authenticator https://www.microsoft.com/en-us/security/mobile-authenticator-app
ProtonMail https://protonmail.com/
Tutanota https://tutanota.com/
VMware Workstation https://www.vmware.com/products/workstation-pro.html
Parallels https://www.parallels.com/
```
