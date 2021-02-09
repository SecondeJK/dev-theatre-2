+++
title = "Running and speaking at Online Events: what we’ve learned"
description = "I started DevRel up at Jump24 during the height of COVID: what was it like?"
author = "James Seconde"
date = "2021-02-09"
tags = ["culture","community","devrel"]
categories = ["culture","community","devrel"]
[[images]]
  src = "img/online-events/j24.webp"
  alt = "Jump24 Offices"
  stretch = "Vertical"
+++
**This article was written for my employer Jump24, you can read the original source article ![here](https://jump24.co.uk/journal/running-and-speaking-at-online-events-what-weve-learned/).

My start at Jump24 was never going to be straightforward – the United Kingdom was in full COVID-19 lockdown, bringing down tech meetups and conferences worldwide at the point when I was fully launching into a Developer Relations role, which would immediately have to be redefined to make our developer outreach work. But: we currently have a talk and live code demo session currently on tour – so how did we do it, and what experience have we gained? But first: some observations about the impact of COVID-19 on our communities.

## Slow to adapt: how tech got caught napping

![Screenshot of events being cancelled on meetup.com](https://dev-to-uploads.s3.amazonaws.com/i/8jxazabxwnzmn7znj66f.png)

It’s hardly a surprising outcome with what happened after the Prime Minister announced full lockdown on 24th March. 34 tech events happened in the first two months in the West Midlands region in the UK, including regulars from DevOps, AWS, Ruby, Javascript, Xamarin/.NET, Docker and ProductTank. After lockdown in April and May, just 6 of the regular meetups happened after switching online, almost all of them Zoom calls. 

This was only for our region of course: the unexpected overhead of suddenly needing to organise and promote on entirely digital platforms meant that grassroots meetups dropped off all over the world and conferences got cancelled with no time to arrange alternative online setups.

## Speaking: Turbocharged development with Xdebug, Docker & PhpStorm

![Screenshot of James Seconde giving Xdebug talk](https://dev-to-uploads.s3.amazonaws.com/i/a4dsgxtgtzan4u5w1llv.png)

So, the first question we had to ask was that if some usergroups were being continued online, should we go ahead with the idea of delivering a talk we’d prototyped internally? First, we’d have to solve the elephant in the room: this was due to be a live code demo. So, to deliver this talk we’d need:

* A speaker, me
* Google Slides, using Chrome
* A bash terminal
* PhpStorm
* Firefox

How do you juggle all this in virtual form, and how do you make it presentable? Step forward Jump24’s Ollie Matthews: Operations Manager and avid gaming streamer.

## Lessons from the gaming world

![Photo of our streaming setup](https://dev-to-uploads.s3.amazonaws.com/i/inpaul9j17hjsllqvqzb.jpg)

Multiple input sources to create a slick streaming platform, you say? Well, it came as no surprise that professional gamers have had this mastered for quite some time. Ollie outlined the equipment needed, so here’s how we built the home studio for streaming:

## The office streaming setup

### Macbook Pro 2016 (Touchbar)

https://everymac.com/systems/apple/macbook_pro/specs/macbook-pro-core-i9-2.3-eight-core-15-mid-2019-touch-bar-specs.html

In the field of web application development, particularly in the realms of PHP, Javascript/Node and Ruby, the dominant Operating System on a user level tends to be skewed towards macOS. We use Macs for developing in Laravel, so it’s worth noting that our experience in putting together a streaming setup is already going to differ from the gaming world, where Windows is by far the dominant platform.

### Elgato Stream Deck

https://www.elgato.com/en/gaming/stream-deck

![Photo of our Stream Deck](https://dev-to-uploads.s3.amazonaws.com/i/nh8hmb8cyyt8aaporzop.jpg)

Elgato’s Steam deck is really the keystone feature of the setup – the ability to create a custom setup that can control lighting, desktop applications (so this tackled the quick switch between terminal, IDE, Firefox and Google Slides on Chromium), Twitch, and OBS (in particular scenes & transitions) is a gamechanger. This bit of kit is no stranger to the gaming world: streamers use it regularly for Twitch (and other socials integration such as Twitter), recording and scene control. Elgato has recently opened up the button marketplace, adding new control sets such as integration for VSCode.

### Elgato Key Light

https://www.elgato.com/en/gaming/key-light

![Photo of our Key Light](https://dev-to-uploads.s3.amazonaws.com/i/r75xtzksz8jt8j53r0ej.jpg)

Despite many people’s beliefs, lighting is one of, if not the most important part of any streaming setup. So, the next thing we went for in the Elgato family is the Key light. Yes, this may seem a little expensive compared to other LED panels or ring lights but this particular light seamlessly integrates into the rest of our setup – including the Stream Deck.

With its sleek design it can fit into any space or desk setup, and hooking it up to your PC via wifi allows you to tweak the brightness and temperature to best suit your needs.

Despite the premium nature of this product, the setup wasn’t all plain sailing. The Key Light requires a 2.4ghz banded Wifi and doesn’t work with 5ghz. I have a dual band router, so when I switched on 2.4ghz it firstly had a weak signal despite not being far away (common with poor routers dished out by providers). Secondly, my new TV fights with the Key Light over who gets to be connected to the network.

For more advanced colour options, you might want to consider the Elgato Ring Light, but still has the same potential burden regarding control.

### Rode NT-USB with boom or Elgato Wave:3

https://www.rode.com/microphones/nt-usb

https://www.elgato.com/en/wave-3

![Photo of our Elgato Wave 3](https://dev-to-uploads.s3.amazonaws.com/i/gw8npf3xaluzff3qnm48.jpg)

Originally I’d purchased the Blue Yeti on the back of many recommendations, but it shipped broken. Rode’s USB mic might not have the multi pattern recording modes that the Yeti does, but it does come with a decent pop filter and reasonable price tag. In the office setup we use the Elgato Wave:3 with a boom and filter.

### Logitech Streamcam

https://www.logitech.com/en-gb/products/webcams/streamcam.960-001281.html

![Photo of our Streamcam](https://dev-to-uploads.s3.amazonaws.com/i/jvwzuqdd1zyoxq4p8xq0.jpg)

Choices for HD streaming are vast, and so sifting through the pages of 1080p cameras can be daunting. The important bit here is to answer the glaring question: “do I need a 1080 webcam?”. Well, what we wanted at Jump24 was as professional a setup as we could get, which included a 1080 cam. However, it’s worth pointing out that if your scenes are mostly a small corner box with a slide deck taking centre stage (or on a live demo like ours – a terminal, browser etc.) then realistically any cam will likely be sufficient.

### Elgato Green Screen

https://www.elgato.com/en/gaming/green-screen

This is something new we have added to our setup but yet to implement. Using a green screen will allow us to expand our Overlay options when doing events, from branded backdrops, animations to simply removing a messy background. 

A green screen can be something that eliminates issues; add a chrome key filter in your broadcasting app of choice and, just like magic: the background has disappeared.

### OBS Studio

https://obsproject.com/

Open Broadcaster Studio has been at the forefront of game streaming for at least five years. It’s ability to take almost any media input and generate an output for streaming, and for free as Open Source Software makes it an industry standard of sorts. There are disadvantages, however – the majority of its users tend to be on Windows platforms, so if you’re using the MacOS or Linux ports it can be a little more buggy. In order to hook up OBS to various hosting platforms where no integration with OBS is possible, it needs the ‘Virtual Camera’ feature, that will take the OBS output and pipe it into a virtual device. The likelihood is that if you are in control of your stream, you can hook up OBS to YouTube or Twitch with API keys directly and thus won’t need to use the Virtual Camera, but when you are being hosted and control is out of your hands it will be needed.

## Being Hosted: your meetup’s tech stack

### Zoom / Skype

Zoom capitalised on their new found advantage by offering unlimited free tier calls. It’s probably not that much of a surprise then that Zoom seems to have become the default. I’ve done the talk a couple of times now on Zoom with OBS’s Virtual Camera output and not found any issues with it.

### Jitsi

Jitsi would absolutely not play ball with the OBS Virtual camera output – problems included output resolution and “flipping” the output image. What made Jitsi unusable for us, however, is that there is a tendency for meetups using it to have the free tier (for understandable reasons). Unlike the resource Zoom has to throw at free tier usage, it was clear that the servers were heavily throttling the connection. That’s not a problem if you’re doing a brief meeting, but presenting and pulling down docker containers? Nope.

### Streamyard

Streamyard is a popular option, and from a speakers’ perspective has decent features: a backstage broadcasting area and a screenshare perspective that takes care of the scene layout for you. There is, however, a disadvantage to this (as we discovered) in that you can’t use OBS’s virtual camera output. The image resolution is cropped awkwardly, but more importantly with OBS you’re trying to replicate a feature that Streamyard is designed for. This is where there’s a big difference in Streamyard between speaking and hosting: as a speaker, you don’t have control whereas when hosting you can include backdrops with branding.

![Jitsi, Zoom and Streamyard logos](https://dev-to-uploads.s3.amazonaws.com/i/kif1rjugg1tr1zctkpg3.png)

## Hosting: Tech stack options with Kevin Lewis

![Preview of Jump24 tweet about forthcoming events](https://dev-to-uploads.s3.amazonaws.com/i/wt7h7gm5kwwpffyvl28i.png)

So, we’ve covered being the speaker in virtual meetups, but what about hosting your own? Before COVID hit, we were planning to launch a new tech, art & culture event in the city, BrumTech Tapas.

![BrumTechTapas design banner](https://dev-to-uploads.s3.amazonaws.com/i/vwxzps2dcwk5n3jk6yti.png)

With the switch to virtual, we needed to think about our options from an organisers’ view. Rather than go into this foray blindly, I spoke to Vonage’s [Kevin Lewis](https://twitter.com/_phzn), whom I knew had a mountain of experience in this area due to his events work with the *You Got This Conference* Series, *Women of React* and *Vonage’s Developer Day*.

---

Online events provide some really exciting opportunities to build experiences that just wouldn’t be possible in a physical space, for the affordances that tech brings. When organizing events, you can try and emulate offline events complete with networking setups, work towards an Apple WWDC-style highly-produced live TV show, or create more novel experiences such as Roguelike Celebration. 

When choosing your setup, there are five core considerations:

1. Complexity of Operation – how confident is your team to use more complex tooling?

2. Creative Flexibility – how customized do you need the output to be? 

3. Moderation Bandwidth – how much people-power do you have for moderation, and how does the choice of platforms impact this?
    
4. Attendee Experience – what is an ideal experience for attendees? Do you want to facilitate networking? Should it all be in one platform?
    
5. Speaker Experience – how involved or complex can your speaker experience be while still being appropriate for who you have invited?

Some of these items are inextricably linked – having more creative flexibility is likely to increase complexity, for example. 

My first full-scale online conference was Women of React back in April. We used Skype (with NDI) and OBS for managing the stream, YouTube for hosting the stream and Discord for community interactions. We got a really lovely set of custom scenes and full control over what was seen or heard, but it was a pain to keep on top of. The speakers and MC had to really work through all of the technical quirks (which they did fantastically), but it was difficult. 

Using a video call, piping data into OBS via the NDI protocol and pushing out a completed stream to your host means your one device will be doing lots of computationally-expensive operations, and if it fails to deliver the whole event will suffer. There are contingencies to this – such as renting a more powerful cloud-hosted machine and completing the work on it, but this comes at an additional cost and setup time.

My team at Vonage chose to use a platform called Remo for Vonage Developer Day – which has a networking component aiming to emulate offline events. Attendees can gather and move around tables – each a small video call between groups. 

Through all the events I’ve run, I still believe Streamyard provides the best overall setup for publishing livestreams. While you are creatively limited to just the 7 pre-set layouts provided, they are designed with care and almost every use case in mind. 

Also consider the need for networking in the long, long year that is 2020. I am a fan of giving people spaces to meet, but nothing will replace being in the same room. Many folks have screen fatigue, and many will be motivated only by consuming the organized content. Consider if this is true in your community and whether you can place somewhat-forced networking efforts aside for a happier time. 

If you want to find out more about the considerations and outcomes around Women of React, Vonage Developer Day and You Got This From Your Couch – you can [watch my talk](https://www.youtube.com/watch?v=56rvtjZ9x3g) from DevRelCon Earth earlier this year.

## Event Branding – design considerations

The new branding for Brum Tech Tapas along with the website had just been completed before we went into the first lockdown. The idea was to keep it simple and not focus solely on the tech community. A lot of this was achieved by building the website and the photography we used to represent the diverse cultural scene in Birmingham. 

The next design aspect we had to tackle was moving the talks over to Twitch. Something as designers we had no experience in. We started taking a look at other Twitch coder accounts and noticed that the aesthetics weren’t always a priority, something we wanted to avoid. As this was something relatively new for tech talks in Birmingham we wanted to make sure we put our best foot forward, using our branding to create something aesthetically pleasing whilst allowing for multiple speakers to be shown and live coding to be clear and visible.

## Virtual means more accessible options

The equipment we put together and time invested in designs etc. comes at a cost. The decisions that we made are based on the notion that you don’t have to invest much to get a polished, professional setup that looks no different from international tech firms’ branding and content delivery.

While that’s certainly the conclusion for what we were looking for, it’s important to bear in mind that to speak at a meetup or to host one, you technically don’t need any of this. This is vital to know if you’re starting out speaking and need some exposure, or you’re booting up a new usergroup (or transitioning online for the first time). All you actually need is an internet connection, a webcam and people to join. As with most things, the end goals of what you want to achieve dictate the requirements.

## Virtual meetups and conferences: advantages and disadvantages

So, given that we’ve gone through planning, let’s have a bit of a postmortem on the key things to think about when it comes to running virtual tech events. As we approach tech events from a Developer Relations perspective – raising awareness of our work and doing developer outreach for education, it’s now very apparent what can run smoothly and what snagging points you can encounter.

### Advantages

#### Speaker Pools

The rules have now been redefined – you can officially contact someone elsewhere on the planet and ask if they want to speak at your meetup. It’s worth noting that, while there is an element of truth to that sentence, many of the meetups I have spoken at have very much stuck to a pool of speakers already within their network. While it might have potentially opened more doors to speakers, it’s also worth considering that it doesn’t give you an immediate ‘yes’ from everyone.

#### Cost

The cost of what you’re looking at has pretty much been outlined in the article. In-person meetups require spaces, the oh-so-stereotypical “Pizza for 30 developers” and drinks sponsorships. If you’ve got a fancier meetup, you might have catering. The cost of running a meetup can be £0 if you want it to be; even the price of a conference is suddenly astonishingly low considering the speakers you might have been able to virtually pull in.

#### Potential Reach

The point of a local usergroup is that you form smaller communities around common themes – the convenience of opening it up without a physical form means that your attendance might well spike. In the usergroups we’ve spoken at on our current talk, it’s noticeable how the attendance is actually higher. In the PHP world this does however have a drawback – one of the reasons you’ll see more one some of the events is because PHP developers are aware of other local usergroups. There is a scenario playing out right now that we’ve seen. A point Raised by one of the usergroups we spoke at stated that the same talks are going round the circuit and thus someone from Bristol might not want to watch a talk on at PHPSW: because they already saw it at PHPMiNDS in Nottingham.

### Disadvantages

![Cartoon by Tom Fishburne on standard Zoom meeting nightmares](https://dev-to-uploads.s3.amazonaws.com/i/he2g3e5lqioqdxejbjuw.png)

#### Loss of 1-2-1 interaction

Developer Relations still thrives on in-person 1-2-1 interactions – from my experience personally this is still the best way to network and create a hub of people with similar interests to get feedback and opinions off. Without that, the hardest part of expanding your network has pretty much gone. Yes, in speaking to event organisers, recreating this part of outreach has been attempted, but as of yet not many that I’ve spoken to have reported a successful method for doing it.

#### Internet speeds

This one stands out by a country mile. If COVID has shown us anything, it’s how reliant in the tech world we are for the Internet for software development beyond the obvious limitations of CI pipelines and Docker pulls. 

Your speaker’s connection goes down 5 hours before the event because someone drilled through a pipe. Your speaker’s connection goes down during the event while speaking because geese have attacked the exchange. What do you do?

That’s only from the speakers’ perspective. During the tour of our current talk, my internet speed was fairly poor, and an unexpected need to pull an nginx container resulted in my best Minecraft look. But what if you encounter this when you’re on StreamYard and hosting the whole event? Well, then you’ve not really got any options. But you can prepare by making sure you host from a high speed connection, especially if you have speakers from across the globe, and especially if they’re not in the standard Western world tech bubble.

#### The curse of remote working

This is one of the biggest issues with moving virtual. You’ve just spent eight hours of your day on Zoom calls, JIRA and your IDE open in front of you, barely moving apart from the get the occasional coffee which is also now done in silence.

Come 6:30pm, is opening up a Zoom call with 30 people in to have a virtual tech talk (that, in some cases, is being recorded and will be available at any point in the future you choose anyway) really how you want to spend your evening?

#### Losing outreach: Slack/Discord

This is Developer Relations. Marketing people might well not see the problem with throwing out “for discussions, sign up to our Slack/Discord!”, but we know the pain of being told for the 10th time in a month to sign into a new social media platform for one event that will be used once.

This particular subject has been covered recently by [Joe Nash](https://twitter.com/jna_sh), offering to open up discussions as to why _Let’s Just Create a New Slack_ really isn’t the one-size-fits-all solution.

![Screenshot Joe Nash's Twitter feed saying please don't create another slack](https://dev-to-uploads.s3.amazonaws.com/i/gik66mw5qe0nht33uua3.png)

Source: https://twitter.com/jna_sh/status/1326514552251568130

For more fitting options, specifically around the biggest sticking point of live feedback/community comms – moderation – check out Joe’s tweets and subsequent discussions on why certain platforms have advantages over Slack. What’s interesting is that Discord comes up time and time again in conversations – another crossover from the gaming world.

## Conclusion: A more versatile outreach

So, what are the results of what we did? Well, like most people I expect, we’re ready for physical events again for sure. But for now, I’ll put it this way: we’re now equipped and experienced in hosting and delivering virtual content. This is something we certainly couldn’t do before, and besides: without the COVID crisis many large tech companies did have the ability to create content in this way. So, by preparing for virtual content and calling in advice across disciplines both internally and externally – Jump24 has a far more versatile outreach capability. Which, after all, is the point of Developer Relations, isn’t it?

_With thanks to Ollie Matthews, Anneka Mistry, Kevin Lewis and Joe Nash._