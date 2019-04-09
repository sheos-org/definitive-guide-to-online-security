B Security Memo

![image alt text](image_0.png)

You ARE a target

If you are reading this memo, it’s probably either because you’ve asked for it, or someone has deliberately sent it to you. 

This means you recognize you are a target. Don’t forget that. It’s super easy to become complacent and that leads to STUPID errors.

This is a memo to highlight best security practices. It’s a practice because it’s not a "one-and-done" thing you do - just like installing a lock on your door, it only works if you USE the lock and lock the door. 

This is a living document, but it is only meant as guidance and may quickly become obsolete. 

The goal here is to make it harder for attackers to gain access to your information and money and identity.

This is also written for the *average *user. If you think you are a high-risk target. Please seek expert advice! I can make some recommendations for you. Please feel free to reach out to me.

TOC

[[TOC]]

1. Physical Security

    1. Never leave your devices unattended

Please ensure your devices are either LOCKED away or on your person. DO NOT leave laptops in a bag in the corner of a conference room / meetup / bar.

    2. Activate remote wiping

Use FindMyiPhone or equivalent so that if you lose your device you can (a) see where it is and (b) remote wipe the data:  Settings > Accounts & Passwords > iCloud > Find My iPhone. 

    3. Who can see your devices?

I once sat on a plane next to a competitor in an M&A deal. By the end of the flight I knew exactly what they were going to pay for the business we were competing to buy. I won the deal. 😂

Be careful when using your laptop or making phone calls in public places. Use a [privacy screen](https://www.amazon.co.uk/gp/product/B07CJPPCC3/ref=oh_aui_detailpage_o00_s00?ie=UTF8&psc=1) for your laptop.

    4. External drives

DO NOT plug external drives into your computer. If someone needs to share a document with you, ask them to do so through google drives. If there is no alternative, use YOUR USB stick which you should wipe each time you use it.

USB sticks make great giveaways at conferences. (NOT!). Never put a giveaway USB drive into your computer!!

    5. Sharing your screen

If you are sharing your screen in a webinar / conference call or at a conference venue by plugging into a projector remember that whatever is on your screen is visible to others.

Close unnecessary applications / tabs / browsers and switch off alerts  (*I recently saw a tinder alert on the big screen from someone’s laptop at a conference! *😂*)*

    6. Video streams

We all regularly use video streams to have conversations with friends and colleagues around the world. When you are not using your camera - use a [camera cover](https://www.amazon.co.uk/Webcam-Privacy-Cover-TechPrivacy-Logo-less/dp/B075VYMPHW/ref=sr_1_5?s=computers&ie=UTF8&qid=1528198754&sr=1-5&keywords=laptop+camera+cover). Also helpful incase an audio call unexpectedly becomes a video call!

When you are using your camera think about what is on display. Not just you but are there any papers, notes, other screens, whiteboards, background conversations which you don’t want to be streamed too! 

    7. Paper security

Avoid using paper to write down important information unless is secured. A lost notebook cannot be remotely wiped.

    8. Location

Avoid posting on social media about your travel plans. Particularly if your house is empty when you’re away.

2. Digital Security

    9. Keep your software up-to-date

Fully reboot your laptop at least twice a week and perform a check for software updates. The eternally "sleeping" Macbook is prone to miss updates and compromise security. Ensure full disk-encryption is switched ON.

    10. Phone

* You should use an iPhone, model SE or later. Android phones are not safe to use.

* Your iPhone is the most secure device you have. Do whatever work you can on it. It is always better to read email, use Signal, and surf the web on your phone.

* Make sure you have at least a six-digit key code or passphrase.

* TouchID is safe to use, but Siri is not. Siri can reveal information about your contacts even when the phone is locked. Set timed locks!

* Make sure your settings are restrictive when the screen is locked - *Settings > Touch ID & Passcode > Passcode Lock*

    11. SIM Safety 

* Sim Jacking is increasingly dangerous. This is where someone is able to arrange a "swap" of your phone service into their own SIM by social engineering. Now, your calls and texts on your phone will no longer go to you, but to them. They normally time this while you are sleeping or traveling so that you will not realize for a few hours (or days). 

* You can protect yourself by using a private number (unknown to others, not used for any communications). You can get one on Google Voice, OnSIP, DINGTONE, FreedomPop. Do not connect this to forward to your existing phone number or that will defeat the purpose. 

    12. Computer

A mac is preferable to a windows computer which tend to be more susceptible to attacks. 

    13. Passwords 

* Never use the same password twice.

* Always use a password manager to create (randomly generate) and share passwords. Recommended length is at least 20 characters. 

* Only share passwords when absolutely necessary - it is preferable to have multiple accounts.

* [LastPass](https://www.lastpass.com/) or [1password](https://1password.com/) are my recommended password managers.

* "Remember Me" buttons are best avoided!

    14. 2FA

2FA = *something you know (password) *+ *something you have (codes)*

* Add 2-step verification (2-factor authentication) to your high value accounts: [LastPass, Google, Mailchimp, Telegram, LinkedIn, Twitter] etc. Basically anything that can be used to steal company information or impersonate you. After you have set up 2FA wipe all current logins so that you know they are protected.

* For 2FA use a combination of

    * **FIDO **

        * [Yubikey](https://www.amazon.co.uk/Yubico-YubiKey-USB-Authentication-Security/dp/B018Y1Q71M)

            * I recommend having 2 yubikeys - one that you keep with you and one kept in a safe.

        * [Google Titan](https://cloud.google.com/titan-security-key/) - an alternative to Yubikey

    * 2FA App

        * [Google Authenticator](https://en.wikipedia.org/wiki/Google_Authenticator)

        * Authy

    * Backup codes 

        * I recommend writing these on a piece of paper and storing in a safe or storing in encrypted disk images on cloud drives.

    * DO NOT USE YOUR MOBILE NUMBER  mobile numbers are easily stolen (see "2.3 SIM Safety")

![image alt text](image_1.png)

*It is a bad idea to write down your passwords and chain your 2FA device to your computer!!*

    15. Team drives

All company information should be stored in the Team Drives. Please avoid saving company information on your personal computer or personal drives.

    16. Attachments

Attachments are one of the biggest risks you face. Even attachments coming from a trusted sender are a danger; if someone you know gets their email hacked, the attacker may send you a message that looks just like a typical message (for example, an email from your colleague with a Word doc).

Here is the hierarchy of attachment safety, from safest to most risky:

* Safest is to open them on an iPhone.

* Save them directly to Google Drive from Gmail. If you hover over an attachment in Gmail, you'll see a 'save in Google Drive' icon.

* Download them to disk, and upload them to Google Drive in your browser. Make sure you delete the downloaded file, so you don't accidentally double-click it in the future.

* The least safe way to open an attachment is to double-click it on your laptop. Never do this.

Don’t send attachments. Send google drive links wherever possible.

    17. Links

Shortened URL links can make you visit websites that are BAD news. If in doubt, copy the shortened url, and then open up terminal and type "curl URL -I" which will then show the URL that the link shortener goes to, without having to actually go there.

    18. Browsers

* Use Google Chrome as your default browser on your laptop. 

* Avoid Safari and Firefox. Under no circumstances use the Tor browser (it's okay to use Tor, but do it with Chrome, and seek additional training on how to set it up).

* On your iPhone, it's okay to use Safari.

* Use the uBlock Origin and HTTPS Everywhere Chrome browser extensions. 

* Avoid using other extensions.

    19. Wifi

Where possible connect to wifi networks you trust. For unsecure networks, avoid carrying out sensitive tasks and sending and receiving sensitive information.

Unsecure wifi includes:

* Conferences

* Cafes / public places

* Airports

* Aeroplanes

If in doubt, hotspot to your mobile phone.

    20. Messaging apps

<table>
  <tr>
    <td>Good for secure conversations</td>
    <td>Okay for normal use</td>
    <td>NOT Okay</td>
  </tr>
  <tr>
    <td>Signal</td>
    <td>Whatsapp</td>
    <td>Facebook Messenger</td>
  </tr>
  <tr>
    <td>Telegram private chat</td>
    <td>Slack</td>
    <td>Twitter DMs</td>
  </tr>
  <tr>
    <td>WeChat</td>
    <td>Skype</td>
    <td>Instagram DMs</td>
  </tr>
</table>


    21. Credit Cards

Do your best to protect the privacy of your credit card numbers. If you want to use virtual cards to give out to people who shop, work, or do errands for you, I recommend using [Privacy.com](https://privacy.com/join/B53YC) - you can use this service to create custom cards for individual merchants or people, in addition, you can set limits on monthly spending or create a card for one-time use. I recommend using these for services online that require you to put your card down for a free trial, or for any subscription so you have a single place where you can turn off a subscription by just pausing your virtual credit card.

    22. Financial Information

Try to avoid putting your credit cards or account numbers into an email or into unencrypted notes on your computer or cloud storage (this includes iCloud/Apple notes). Definitely avoid storing your pin number near your ATM or debit card. I recommend avoiding writing these sort of things down. As tempting as it is to put them in your wallet in little pieces of paper, it’s probably the least secure place and easiest to be stolen/lost since you carry it around.

3. Cryptocurrency Security

[This](https://hackernoon.com/eight-simple-rules-for-protecting-your-cryptocurrency-5cdddc9f674d) is the best article I have found for keeping your crypto. It is also long and complex and isn’t for the everyday user. The steps you take should be proportionate to the amount of crypto you hold and your appetite for risk vs. security. 

Below is a short guide to what I would consider to be *reasonable* steps.

    23. Exchanges

* Do a quick google check before you use an exchange EVERY time. Exchanges are constantly subject to attack. Even an exchange you’ve used for years might become compromised. It’s worth a quick check each time you use it / log in.

* Don’t broadcast which exchanges you use!

* Use a private browser for exchanges

* When using an exchange close any browsers that are unnecessary 

* Get KYC’d on a few different exchanges so that you have flexibility incase one goes down

        1. Emails / usernames

When signing up for exchanges use an email address which is only used for this purpose and preferably one which is uncorrelated to you so that people can’t guess an email address for you. E.g. [x84ha56fkes0983@gmail.com](mailto:x84ha56fkes0983@gmail.com). Make sure there is 2FA on this email address. 

Use a username that is also uncorrelated to you e.g. x84ha56fkes0983.

        2. 2FA

Make sure there is 2FA on your exchange accounts wherever possible. As above, your phone is **NOT** a secure 2FA mechanism.

        3. Don’t keep funds on exchanges

Do not use an exchange as a place for storing your cryptocurrency. If the exchange has a problem YOU will have a problem.

Try to minimize the amount of time that you have funds (both fiat and crypto) kept in an exchange. 

    24. Storage

**If you don’t own your private keys, you don’t have control of your crypto!**

**Diversify. Holding everything you have in one wallet is NOT smart.**

There are many types of wallet. And tonnes of online resources to help you choose. Divide in terms of when you will need to exchange or spend crypto. Keep a small amount of crypto on [hot wallets](#heading=h.7aot6wlhpvi1) incase you want to send some to someone or buy something. For currency you are **HODLing**, use [cold wallets](#heading=h.acwh0mb3h4c3). 

        4. Backing up your wallet

You don’t need a lot of room to store backups of your wallets. Get a couple of memory sticks (16GB is fine). Memory sticks are not a high margin business - expect them to fail. Never back up to just one external disk and consider it done. Use encryption on your disks.

Again, make sure that you are keeping at least one backup FAR AWAY from the others. Having all your backups in your sock drawer isn’t helpful when your house burns down.

        5. Backing up Seed phrases

Some wallets are created from 12-20 word seed phrases. Seed phrases are great because if you lose everything else you can restore your wallet! They can also be really bad - if someone gets hold of your seed phrase they can STEAL YOUR CRYPTO!

* **Option 1** - Write down two copies of your wallet recovery phrases (using pen and paper). Keep them in safe places far apart from each other. For example - one in a bank deposit box and one buried in the garden (lol). Do **not** write the public key of the wallet on these pieces of paper. Come up with some sort of code so you can identify which seed phrase belongs to which wallet. Hopefully you never need these. Do **not** keep these in the same place as your hardware wallet.

* **Option 2** - If you are adverse to paper (for instance, due to it’s being flimsy and flammable), you can use encrypted drives. If you don’t know how to use encrypted drives to store things, then ask a friend who is technically inclined - or go back to paper.

        6. Hot wallets

Hot wallets are connected to the internet. These are easier to use but higher risk than cold storage. Use them for small amounts of crypto. *(unless you’re day trading in which case you shouldn’t need this memo)*. 

Tips for using hot wallets:

* Close all unnecessary applications especially anything which is connected to the internet. E.g. browsers.

* Only use a hot wallet on a secure internet connection.

            1. Mobile wallets

Mobile wallets are wallets that are stored on your mobile phone. They are a terrible idea for anything more than a few dollars worth of crypto. If you don’t already check your phone thirty times a day, you will when it also stores your money!

            2. Desktop wallets

Desktop wallets are a great solution to a small amount of crypto that you want easy access to. 

* [Electrum](https://electrum.org/#home) is a system of decentralized servers it started for bitcoin but is now the basis for a number of great wallets that also hold other coins. [Exodus](https://www.exodus.io/) and [Jaxx](https://jaxx.io/) for example have great UIs. They are created from pre-determined [seed phrases](#heading=h.841rd56115hy) which you will need to store correctly. 

* [MEW](https://www.myetherwallet.com/) is another popular way to generate wallets. You can also access a MEW wallet through [Metamask](https://metamask.io/) which has many integrations with dApps and is helpful to store a small amount of crypto that you want to use frequently.

* When using one of these wallets always make sure to [back-up your keys](#heading=h.dtf400817y57). 

* For EOS - The [eos-voter](https://github.com/greymass/eos-voter) wallet by Greymass is the best. Also, make sure your tokens are staked. You can monitor your account using the [EOS Authority tool](https://eosauthority.com/alerts). 

        7. Cold wallets

![image alt text](image_2.png)

Cold wallets **never** touch the internet. They are best for coins you want to HODL. 

            3. Hardware wallet.

* A hardware wallet is a piece of hardware, like the [Ledger Nano S](https://www.ledgerwallet.com/products/ledger-nano-s) or [Trezor,](https://trezor.io/) that you buy and it stores your private keys. Think about [physical security](#heading=h.8hsx6uavgkky) for your hardware wallet.

* Trezor supports a 25th seed word that you can add for extra protection.

            4. Cold Storage Computer 

* You may wish to use a computer that is [air gapped ](https://en.wikipedia.org/wiki/Air_gap_(networking)) (*has never been connected to the internet) *to store your wallet. Think about [physical security](#heading=h.8hsx6uavgkky) for your air-gapped computer. 

            5. Paper wallet 

* This is super secure (provided you set it up correctly) but also hardcore and should be used for people who have a very safe place to store a piece of paper (think flooding, fire and deliberate attempts to damage). See this guide from blockgeeks for more info: [https://blockgeeks.com/guides/paper-wallet-guide/](https://blockgeeks.com/guides/paper-wallet-guide/)

* Do not take a photo of your paper wallet with your phone or computer or with a digital camera, or with any camera ideally.

        8. Multi-sig

* Many protocols allow you to set up multi-signature wallets. This means that an account can be protected by multiple account signatures in order to execute any action. 

* Have you ever seen a war movie where they have to turn two keys to detonate a nuclear weapon? Every transaction on a multisig account works like that. There are many wallets and blockchains that support multisig accounts including Ethereum, EOS, and Bitcoin. 

* Electrum - http://docs.electrum.org/en/latest/multisig.html

* Gnosis - https://github.com/gnosis/MultiSigWallet

4. Conclusion

        9. Security is a way of life.

* Choose what will work for you and create systems you will follow, then expire those systems at some point and come up with new ones. Have fun with your security!

        10. The conclusion of life. 

* Please think about what happens if something happens to YOU. Does a family member or lawyer or friend (or a combination of these) know how they would go about getting your crypto if something happened to you? Do you have an [emergency access vault](https://helpdesk.lastpass.com/emergency-access) or something similar?  

