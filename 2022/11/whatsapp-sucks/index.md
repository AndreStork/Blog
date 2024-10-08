---
layout: post
---
# WhatsApp sucks. Why? And what should be done about it?
If you live outside the U.S., there's a very high chance that WhatsApp is the main messaging application that you and every other person uses, but I have a question:

## Why is WhatsApp a thing?
See, the way people used to send messages in the 90s and the early 2000s was SMS. Almost every phone had an SMS client, and if you wanted to hang out with a friend you just had to open your SMS client, and send the message, simple but very effective; there was a problem tho: back then, SMS had a cost, we're talking about ~0,50€ per message if your carrier plan didn't cover them, and the simple mention of MMS would strike fear into any phone user (I tried that too, I still consider it the best way to waste 48 cents, per message of course).
It was a carrier problem, but it was so big that in a lot of countries (including Italy) people considered the action of sending an SMS "risky".
So in 2009 WhatsApp was released, and it was still a paid service, but a lot of people preferred to spend a yearly-fee, and it eventually got free with the acquisition from Meta in 2014.
Because carriers didn't lower fees until 2017, and because WhatsApp grew, it started to cause a vendor lock-in that is so big that nowadays people don't even notice it.

## Advantages
With this question being answered, WhatsApp had and still has a lot of advantages.
- **No fees, just your internet data:** as already said, you don't need to worry about SMS/MMS fees, because everything works using an internet connection
- **It's made with multimedia in mind:** not only people didn't have to pay for MMS fees, they could also send photos and videos with an higher resolution

## Problems
But WhatsApp also has big problems that you shouldn't underestimate.
- **It creates a vendor lock-in:** by using messaging apps people create a big lock-in, both for yourself and for the others; to send or receive messages people just use WhatsApp and if you don't have a WhatsApp account they can't text you until they change client (pretty much every messaging app can't send and receive SMS messages, doesn't it sound intentional?), and this forces you to install WhatsApp, which can be very uncomfortable and in some cases even impossible if, for example, you don't have a smartphone. Nowadays people just take for granted that you have WhatsApp, and usually when they see that you don't have an account or don't use it, they assume that you aren't reachable in any case instead of using SMS which should be the last resort for everyone.
- **It's centralized:** what does it mean? Well, when you send a message it goes into a WhatsApp datacenter that delivers the message for you. Not only it's unreliable, but you also can't know what happens in the process, and I wouldn't be surprised if the data will eventually get sold, because that's what Meta does afterall (some people got surprised and even scared when in 2021 a Privacy Policy update announced that WhatsApp data was going to be shared with Facebook, as if they didn't fucking do this already).
- **Third-party clients? Fuck that:** if you want to use WhatsApp you have to use the official application. Wanna use something else? You get banned. Why is this a problem? Because 1) the clients, especially the Android one, have a lot of problems, and considering that you can't fix them, it can be really frustrating; 2) OS and hardware support is completely on the hands of Meta, meaning that they can decide whether if to keep supporting an operating system on a certain version or discontinue it and cause a lot of phones to become e-waste in the process: that's what happened with Nokia S40, Blackberry, Symbian, Windows Phone, KaiOS and that's still happening time to time when older Android or iOS versions become obsolete. All the builds also have timebombs in them which makes using older versions basically impossible.
- **Never give to a big company your messaging infrastructure:** Meta can always add a backdoor, stop supporting your OS, restrict you or spy on you at any given moment and you probably can't do anything about it. Wanna leave? Good luck at not missing a lot of contacts and your group chats. Giving your messaging infrastructure to a big company is very dangerous.

## What should we use?
What if there's an open protocol, that can send high-resolution medias, doesn't have fees (apart from your data plan) and has all the advantages that WhatsApp has. That's right, the answer is RCS.  
It's an open protocol and isn't managed by a big company. With RCS being just a protocol, there are various versions of it. It can be implemented by your carrier or, the variant that you will probably use is Google's Jibe. What? You told me that giving the messaging infrastructure to a big company can be dangerous, and now you suggest me a Google server? Well, yes but no. Jibe is just a platform and while it's mainly used on Google servers it can be also implemented by carriers or other OEMs, and messages get sent **directly** to the recipient in any case (fun fact: if both you and the recipient have supported clients you can use e2e encryption in 1-to-1 chats).
- **It's a standard protocol:** no corporate servers involved in sending/receiving.
- **Has no fees:** by working via IP, you just need to have a data plan, no SMS/MMS fees if RCS is enabled on your chat.
- **It's cross-compatible:** your recipient doesn't have RCS? No problems. Every RCS client switches back to SMS if needed. RCS can also use hubs to comunicate with different servers if needed.
- **Third-party client support:** Google Messages, Samsung Messages, Windows Phone's Messaging app. You can use the client that you want and nothing can prevent you from doing so.
- **Don't want to have RCS? No problem:** RCS can always be disabled and your contacts can still talk to you via SMS on the same client.

## Conclusion
So here's why WhatsApp sucks, if anyone asks you "Why don't you just install WhatsApp?" or "Why do you send me an SMS instead of using WhatsApp?", send them this article and, maybe, they will understand why and move on, or maybe not, but at least you've tried.
