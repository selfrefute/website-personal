---

firstPublishedAt: 1444558105847
latestPublishedAt: 1444865577810
slug: as-many-others-i-didn-t-want-to-wait-the-next-6-8-months-to-receive-a-oneplus-2-invite
title: The grey area in grey import smartphones.
weight: 1

---

#### The story of how I found malware on my ‘brand new’ OnePlus 2 from Kogan

***UPDATE 13/10/2015:** I’d like to thank everyone for sharing and viewing this post. In two days, this post amassed over 70,000 views, made the Frontpage of Reddit, and was covered by numerous Tech Blogs including [Android Authority](http://www.androidauthority.com/beware-the-grey-market-retailers-648562/) and [Gizmodo](http://www.gizmodo.com.au/2015/10/the-grey-area-in-grey-imports-how-i-bought-a-oneplus-2-from-kogan-that-was-loaded-with-malware/). In light of this, Kogan have removed the sale of the OnePlus 2 from their website. However, as I alluded in the post, the problem lies with multiple devices they’ve sold and not just the OnePlus 2, so it will be interesting to hear their statement on the matte\*r.

***UPDATE 14/10/2015:** I have been contacted by Kogan and they have put the pre-installed malware down to a new supplier that they had began sourcing from. They have now ceased any dealings with this supplier, and are getting in touch with other consumers who have bought a OnePlus 2 from Kogan (and linked to this supplier) in order to offer them various options around refunds/returns, or guides on how to flash an official firmware on their devic\*e.

---

Like many others, I didn’t want to wait the next 6–8 months to receive a OnePlus 2 invite. So, when I read that my local Australian retailer [Kogan was selling the OnePlus 2 on their website](http://ausdroid.net/2015/09/03/kogan-is-now-selling-the-64gb-oneplus-2-in-australia/), I was definitely interested. Sure, the cost of the phone was about \$100 more than ordering from OnePlus directly, but the immediate availability of the device made the decision a no-brainer for me.

The majority of products that re-sellers like Kogan stock are grey imports. There are a number of similar ‘reputable’ grey-import companies in Australia, notably, DWI, eGlobal, Expansys and Mobicity. So, when buying a product from one of these companies, you can be sure that the product will not be local stock. However, these companies have a decent enough track record for warranty claims and repairs. This makes purchases from these sites a bit more reliable than the likes of an eBay seller.

When I received my shiny new OnePlus 2, I ripped opened the packaging and inside I found a Chinese wall charger. Along with this though, Kogan had added in the box an Australian adapter. Fair enough. I knew the stock was not local, however, having the adapter within the box indicated that the original packaging had been opened previously. Regardless, I booted up the device and began the setup process.

The OnePlus 2 ships with Oxygen OS, which is a near-stock experience of Android with minor changes. However, scrolling through the pre-installed apps on the device, I found a surprising amount of bloatware. Apps like ‘_Clean Master_’, [notorious for containing adware](https://nakedsecurity.sophos.com/2014/04/04/google-takes-aim-at-deceptive-advertising-of-play-store-apps/), and some others that I hadn’t previously heard of, such as ‘_Magic Photo_’, ‘_DC Share_’, ‘_KK Browser_’, and ‘_Search_’ (not Google Search, but a third party app) to name a few. I found this particularly odd, as Oxygen OS out of the box only contains the default Google Apps (Maps, Search, YouTube, Messenger, etc.) The number of third-party apps pre-installed on the device indicated something else. In addition to this, the “_System Update_” option usually in the “_About_” setting of the phone, was missing, so I could not even perform a software update.

So, I contacted Kogan about the issue on Twitter.

{{< tweet 651722488687104000 >}} 

Their reply to me was a little ill-informed.

{{< tweet 651914076386410496 >}} 

There are a number of things wrong about this tweet. Firstly, the _‘it’s normal for the telcos to preinstall apps’_ statement is not true, as the phone itself was not locked to a carrier nor did it ever belong to a carrier. It was an unlocked device which did not have any carrier information, nor did it show a carrier logo at boot-up.

Secondly, the ‘_They should easily be removed_’ statement is completely and utterly untrue, as the pre-installed apps were installed as **system apps**, which meant that they could not be uninstalled, merely ‘_disabled_’. The only way to remove the applications would mean flashing a different firmware on the device manually, something which not everyone may have the expertise to do.

I contacted Kogan again to tell them that these apps are installed on a system level, and can’t be uninstalled. Unless of course I unlock my bootloader, root my device, and void my warranty with the company.

{{< tweet 651928146535538689 >}} 

The company did not immediately reply.

I began to search on the internet to find others who faced similar issues and I posted [this](https://www.reddit.com/r/oneplus/comments/3ntv6p/op2_bloatware_kogan_australia/) thread on Reddit. Unsurprisingly, I received a number of responses from folks who had the same bloatware pre-installed on their OnePlus 2 from Kogan. One such commentor stated how his device had **adware **out of the box.

![[https://www.reddit.com/r/oneplus/comments/3ntv6p/op2_bloatware_kogan_australia/cvsawxi](https://www.reddit.com/r/oneplus/comments/3ntv6p/op2_bloatware_kogan_australia/cvsawxi)](https://cdn-images-1.medium.com/max/1150/1*Ox5jli9lzChjwuKx1q8o4g.png)

Also attached to this comment were a couple of screenshots of the adware in full action.

<iframe
                width="550"
                height="550"
                src="https://cdn.embedly.com/widgets/media.html?src=%2F%2Fimgur.com%2Fa%2F9R5vI%2Fembed&url=http%3A%2F%2Fimgur.com%2Fa%2F9R5vI&image=http%3A%2F%2Fi.imgur.com%2FVqM7jv5.jpg%3Ffb&key=d04bfffea46d4aeda930ec88cc64b87c&type=text%2Fhtml&schema=imgur"
                frameborder="0"
                allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
                allowfullscreen
              ></iframe>

Note that this is blatant adware on the overall Operating System level. **Not an in-browser ad, but within the OS itself**! Based on more replies, I found a number of other instances of nasties found on grey imports of this particular device.

Another user purchased his device from _Expert InfoTech_, and actually found **malware **on the device.

![[https://www.reddit.com/r/oneplus/comments/3ntv6p/op2_bloatware_kogan_australia/cvt95hu](https://www.reddit.com/r/oneplus/comments/3ntv6p/op2_bloatware_kogan_australia/cvt95hu)](https://cdn-images-1.medium.com/max/1132/1*432JGTweBHYN0aTU4-kXXQ.png)

![[https://www.reddit.com/r/oneplus/comments/3ntv6p/op2_bloatware_kogan_australia/cvtfzd3](https://www.reddit.com/r/oneplus/comments/3ntv6p/op2_bloatware_kogan_australia/cvtfzd3)](https://cdn-images-1.medium.com/max/1110/1*wGw7g0F3xNptA5mVryRlEQ.png)

He went on to attach screenshots of the malware, detected ironically by one of the pre-installed bloatware on the device, ‘_Clean Master_’.

![](https://cdn-images-1.medium.com/max/4424/1*crigT14HSjiQDBdCRgeZ8w.png)

![[http://imgur.com/a/7SmLN](http://imgur.com/a/7SmLN)](https://cdn-images-1.medium.com/max/4336/1*9dmbR7SNo8HQcc-B-Io1Fg.png)

Unsurprisingly, the ‘malware’ on the device _was the pre-installed apps themselves_. I ran a Malwarebytes Test myself and detected Malware on my own device, however, the app would force close immediately following a malware hit, thus, not allowing me to view the logs. I’m not entirely sure if this is a bug with the Malwarebytes application, or the malware on the device being sophisticated enough to prevent the scan from taking place. Nevertheless, I was able to grab a screenshot before the application force closed.

![](https://cdn-images-1.medium.com/max/484/1*TsDAU-i8zf0bPlgIyX9OtQ.png)

> Ironically the “Clean Master” app they pre-install has an “Antivirus”, which when you run, tells you there is malware, which can let “hackers” take control of your phone.

These are just a few of the many examples I found of people receiving modified versions of the Oxygen OS on their supposed “brand new” device. There were [other horror stories too](http://forums.whirlpool.net.au/forum-replies.cfm?t=2435998&p=24&#r477), all following the same narrative.

The solution? Well, if you have a bit of experience with flashing firmware on an Android device, the process is very simple. It’s just factory resetting the device and flashing the official signed Oxygen OS firmware through stock recovery.

But that is not the point. The point is that no one should have to go through this hassle on a brand new device. The point is that I noticed, some others noticed, but there’s countless others who may not or will not ever notice that their new device contains adware or malware which should not be there. For all the fuss manufacturers and re-sellers make about voiding your warranty if your device firmware is modified in any way, there is no excuse for receiving a phone with a modified operating system from a reputable company, containing malware.

When I contacted Kogan one final time telling them that a new phone I bought from them contained malware, this was their response.

{{< tweet 652281739059032064 >}} 

They asked me to lodge an enquiry through a form on their website. The onus should not be on the consumer, but the company itself. If anyone should be lodging an _inquiry_, it should be Kogan within their supply chain.

The sad truth of the matter is, of the tens of thousands of OnePlus 2 devices shipped from Kogan’s warehouses over the past few months, no one knows how many of them contained a modified firmware. Many users will never know what apps ‘_should_’ ship with their device, what is safe, and what is unsafe. It is the responsibility of the re-seller to ensure that the device they are selling is one which they are liable for.

This post is not meant to name and shame Kogan. As demonstrated in the entirety of the article, the problem affects many re-sellers of grey imports. I hope this post goes some way in ensuring consumers are aware of some of the dangers of purchasing grey-imports, while re-sellers step up their efforts in a bid to eliminate any form of malicious content present on the devices they sell. The point of the article is also not to put people off the OnePlus 2, (which, to be fair is a brilliant device), and purchasing directly from OnePlus would not result in the fiasco I had. However, there are a number of countries including Australia where it is not possible to get the OnePlus 2 from official channels, and so consumers like me pip their hopes in grey imports.

> Edit 13/10/2015: I’m almost certain that any pre-installed malware is not placed there by OnePlus OR Kogan, but somewhere in between. As the majority of these phones originate from China, it is also most likely that these grey imports are the OnePlus 2 devices **designed **for China (which do not require an Invite to buy, can be bought outright and run a different Operating System), which would be running the Chinese ‘Hydrogen’ Operating System. When organisations like Kogan buy these in bulk for the international market, these suppliers flash the ‘international variant’ Oxygen OS on the device. Which would go in some way to explain the pre-opened packaging, in order for them to install a firmware compatible for the international market. However, as it turns out, it is not always the official firmware provided by OnePlus, but a custom image in some cases containing malicious content.
