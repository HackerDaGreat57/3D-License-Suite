# The Three-Dimensional License Suite
The 3D License Suite is a collection of custom licenses that have three dimensions<sup id="a6">[6](#f6)</sup>:
1. Granting the licensee freedom to do almost anything with the licensed intellectual property, as in free beer <ins>and</ins> free speech
2. Encouraging tinkering & modification (and then sharing your work so the original may be made better)
3. Keeping free works free - <ins>*NO ONE*</ins> can incorporate free works in nonfree works in any way

We found it a bit of a burden to write all the licenses all at once, so **only the Software License (3dSL) exists right now.** The others will be created as soon as 3dOS Developers Group actually requires them (there's still a long way to go before we start designing hardware and creating 3dOS release videos).

In this README, names of companies and products are slightly altered to avoid legal trouble. We don't mean to make fun of y'all; it's just that we don't feel it's a smart idea to take real names.

Works licensed with the 3D licenses can also be called "free" works, however this may clash with others' definitions of free works.

## Licenses included in this set
There are multiple types of content that can be licensed with these licenses. The "gists" (basic summaries) of the licenses are below. But beware that the gists don't use language as precise as in the actual license documents, which is why they might be slightly off the real meanings. We've made sure that the gists retain the true meaning of the licenses, but to be sure you can always consult the actual documents.

**The only license that exists right now is the 3dSL. Others will be added at a later date, or you can open a [pull request](https://github.com/HackerDaGreat57/3D-License-Suite/pulls) if you have ideas.**

### Software (3dSL)
You have a perpetual license to use the software to its full potential without having to pay, provide details, be related to someone<sup id="a2">[2](#f2)</sup>, or login to a service. You may modify it as you wish, but if you are publicly distributing object/binary or documentation files of your modifications, then you need to also distribute source code of your modifications. And all modifications which you distribute must be available to users without them having to pay, provide details, be related to someone, or login to a service. It is mandatory to give credit to the people who made the original version of the software; we don't like plagiarism 'round here.

If you wish to use<sup id="a3">[3](#f3)</sup> and/or include binary/object, source code, and/or documentation files of the software in other software, the other software must pass the following criteria:

1. Anyone must be able to obtain the other software, its source code, and its documentation without having to pay, provide details, be related to someone, or login to a service.
2. The other software should continue working to its full potential indefinitely. There should be no "free trial" period or "registration" or "activation" function which requires the user to pay, provide details, be related to someone, or login to a service.

#### Use Cases (hypothetical situation shown)
There is a popular C multithreading API named SuperFast licensed under the 3dSL. All software which uses it is also licensed under the 3dSL or is private (not publicly distributed).

So if *Tragfax Inc.* wanted to use SuperFast in their proprietary product, *Turnstile*, they would either have to relicense Turnstile under the 3dSL or suck it up and use alternative techniques to accomplish the same task.

## But why?
### Software
A prime example of one area of computer content that's slowly getting out of hand today is software. *Muddybricks* has always asked you for your wallet in order to use most software they make; we're all familiar with that. But you may not realize that in itself is a bad thing, because let's ask ourselves again: ***What is a computer?***

A computer is one of the greatest inventions of man, a tool that's *supposed* to let <ins>anyone</ins> with access to one manipulate data and perform many computational operations very, very fast. When programmed correctly, you get a computer with a full-fledged operating system and applications which you can use to work, play, communicate via network connections, and almost anything else. [Back in the dawn of the digital era, people used to make software and distribute it and its source code for free, no questions asked.](https://en.wikipedia.org/wiki/Proprietary_software#Origin) But then *IBN* standardized selling software and hiding source code from the general public so people can't modify it so it fits their needs (and so that IBN makes more $$$). This set the new standard for most software companies: putting source code behind lock & key and charging users to use the software after the "free trial" (or sometimes charging just to give customers access to software installer files).

**These days, Muddybricks among many other major software companies have moved to a subscription-based model. *That means that you never truly 'own' the software and you have to keep paying for it indefnitely until you stop using it.*** Now, if you're as bewildered as I was when I discovered this, I'm afraid this is the truth as of today. And it just gets worse as I keep explaining. Let's say you purchased a Muddybricks Creative Thundercloud license and you currently pay them monthly. You're a full-time photographer on a 3-month trip in Africa to get some shots of the wildlife, and you won't have time for editing your photos after you get back. However the spots you'll be going are known for having no Internet connection in *any* form. But who needs the Internet when you already licensed your photo editing software, right?? [Well, good luck even getting Photocrop to even open.](https://shallowsky.com/blog/gimp/non-free-software-surprises.html) Good luck finding a new job.

Proprietary, closed-source software is a ticking time bomb, and it can blow up in your face when you least expect it as mentioned in the link above. The party/company who makes the software have the upper hand over the people who use it. And someday <ins>when</ins> (not *if*) the creators make changes to their product which users don't like, there's no way out because the people cannot modify it themselves to make it better; and many closed-source programs these days purposefully use binary-encoded proprietary file formats so you can't switch to FOSS. Many people know this and yet they don't bother moving to more open and "democratic"<sup id="a4">[4](#f4)</sup> ecosystems, where the product is built *by the users*.

Take *Winbows*, for example. Nearly everybody uses it because the company that created it has a monopoly, and because most of its users are easily scared by the command line (which isn't needed much in that OS). The programmers who work on Winbows decided to program their OS so that it would randomly ask the user to purchase the company's subscription-based office software suite when the user's computer started up. This kind of thing really shouldn't be done. Imagine getting ready and heading out to lunch, minding your own business. Then a random guy sitting in your car jumpscares the hell out of you as you open the door. He starts talking in a strangely familiar monotonic voice, advertising a 50% discount on typewriters while staring at you with eerie unblinking eyes. All you want is for him to shut up and get on with your day because you don't need a typewriter and probably never will. Well, I'm sorry to say that the kind of boot-up advertisements present in Winbows are similar to the situation described. As soon as you see the blue box pop up (when the guy starts talking) all you want is for it to just STFU and you're waiting for the "No thanks" button to fade in. I'm sorry if you haven't realized, Micro$oft, but nobody just randomly decides to buy Offise when their computer boots up. [LibreOffice is many leagues ahead anyway.](https://wiki.documentfoundation.org/Feature_Comparison:_LibreOffice_-_Microsoft_Office)

**The hellish concept incorporating endless payment is not what software was *meant to be***. Software should not have annoying nag screens tempting users to spend their hard-earned money on something they don't need<sup id="a5">[5](#f5)</sup>. Software is not something that is manufactured, shipped, and put on a shelf for a customer to pick up. Software is not a service powered by thousands of tiny workers in your computer who need food and healthcare. **Software is merely a sequence of virtual bits and bytes that *you own* which can run on physical hardware which *you own* to produce an output *<ins>you own</ins>,* and it's supposed to be very transparent to anyone who pries it open to see what makes it tick.** That is our definition of "software". No other popular software licenses define it that way, which is why we created the 3dSL.

## Footnotes
1. <b id="f1"></b>*[Back to source](#a1)* | Anything qualifies as "private use" as long as there is no public distribution of assets.
2. <b id="f2"></b>*[Back to source](#a2)* | "Related" as in employee, coworker, etc. Pretty much anyone.
3. <b id="f3"></b>*[Back to source](#a3)* | An example of using software without including it is programming a GUI for an otherwise console-based application licensed under the 3dSL v2 (which the user would have to download separately).
4. <b id="f4"></b>*[Back to source](#a4)* | "Democratic" as in "power to the people".
5. <b id="f5"></b>*[Back to source](#a5)* | Donations don't count as 'unnecessary expense'. It's perfectly fine to donate to something or someone as long as you aren't forced or nagged to do so.