---
title: "Thoughts on Dynamic Island"
date: 2022-09-24T13:22:32+05:30
draft: false
description: "This will be copied!"
---

It's September, and Apple is back with its Annual Event. Held in Steve Jobs Theater, Apple announced its new series of iPhones and Apple Watches. Apple introduced a new feature called **Dynamic Island** in their Pro line-up of iPhones.

{{< rawhtml >}} 
<video width=95% muted loop autoplay>
    <source src="/video/dynamic-island.mp4" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

The term Dynamic Island is so cheesy that it has left me in splits, but hold your horses - the implementation is cool. Dynamic Island kind of vaccums anything we throw at it. And in classic Apple fashion, the animations make the feature more fun to use and eye-candy.

## Diving deep

The iPhone 14 Pro (and Pro Max) have two notches. One resides the Face ID hardware, and other, the front camera. Dynamic Island stays on top of both the notches by filling up the space between them with black pixels. It wakes up as soon as there's any activity that calls for a real-time notification on your phone. Things like booking a cab, checking directions on Maps, seeing SharePlay status, what music is playing, and so on. Simply touch the notification, and you'll be taken to the app that's powering the notification.Touch and hold, and the Island will expand itself to show additional details. Apple has also engineered the Island to expand when iPhone is performing a Face ID authentication.

{{< image src="/img/dynamic-island.png" alt="Dynamic Island" position="center" style="border-radius: 10px" >}}

I've experienced it only once in-person, and that's to say that I don't own an iPhone, but here are some of the features that I've noticed:

- Music Status
- Active Timers
- Accessorices Connect
- Face ID Authentication
- Silent Mode Status
- Power Status (Low Battery, Device Plugged-In, etc.)

Features also include:
- Apple Maps Navigation
- SharePlay
- Voice Memos
- Screen Recording

## Perception

For a debut implementation, I will cut Apple some slack - I think they've made it pretty useful. They could've absolutely obliterated a useful opportunity by including 'fun' stuff there like Memoji and what not. But still, the Island doesn't come without its cons.

You see, the iPhone 14 Pro's screen size is 5.78" and that of Pro Max is 6.33". While my palm is big enough to reach until the top of the screen on the Pro Max, not eveyone's is, and Apple hasn't thought about it. Two alternative solutions to this can be:

a. Make the Island non user-interactive - which isn't too good an idea.

b. Make the island accessible from the bottom of the screen.

The latter will call for an innovative approach since the camera hardware is housed at the top of the screen.

{{< image src="/img/dynamic-island-sunlight.jpg" alt="Dynamic Island pictured in sunlight, photo from TechCrunch" style="border-radius: 10px" >}}

Apart from the reachability problem, in situations where your hand is dirty, they can easily smudge the front camera of the iPhone. In sunlight though, it loses its charm, since these black pixels are no longer able to blend in with the Face ID hardware, thus, making it easy for anyone to clearly differentiate between the two notches up top.

Overall, I like the Dynamic Island, its a cool feature - but I wouldn't recommend buying an iPhone just for it.