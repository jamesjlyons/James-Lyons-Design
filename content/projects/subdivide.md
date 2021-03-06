---
# slug: subdivide-metronome
title: Subdivide
company: Tap Five
website: http://subdivide.io
description: An advanced metronome app
role: Product Design, Frontend Development
thumbnail: /subdivide-img/subdivide-thumbnail.svg
hero: /subdivide-img/subdivide-hero.png
mockuptype: mobile
mockupimage: /subdivide-img/mockup-mobile.png
mockupimagetwo: null
casestudy: yes
order: 1
---

#### How Subdivide Began

Subdivide is a side project that developed out of the clear need for a better metronome with features specifically designed for the marching arts. With the industry standard being a clunky hardware metronome that costs \$200, my developer friend and I saw an opportunity to upgrade the experience of using a metronome during practice via a user friendly app. Subdivide has gone through a few iterations now, and is currently in the process of being designed and developed for iOS too.
<br /><br /><br />

#### The Features

The idea of having a metronome as an app isn't a new one, so, there were already a handful of standard features required for an MVP. These included the ability to quickly set a tempo, change the time signature (what we call Beats per Bar), set accent patterns, and set subdivisions for the beats. In Subdivide, these all reside in the main metronome screen, along with the ability to save configurations as presets for easy access. Beats per bar, accent patterns, subdivisions, and presets are all located in a bar at the bottom of the screen for easy thumb access because these are the options most likely to be changed on-the-fly while the metronome is running. Changing tempo on-the-fly is possible through the buttons by the tempo indicator, but our main differentiating feature, Tracks, solves the most common use case of that need.
<br /><br /><br />

<!-- ![](/subdivide-img/metronome.png) -->

<iframe src="/prototypes/subdivide-bottomsheet-prototype/index.html" width="320" height="640" frameborder="0"></iframe>
<br />
<p class="center" style="font-style: oblique;">Bottomsheet prototype with clickable spots in the bottom bar</p>
<br /><br /><br />

##### Tracks

The Tracks feature allows users to string together a series of sections with different tempos, subdivisions, and accent patterns. For smooth tempo changes, a transition section can be added that accelerandos or deccelerandos between two different tempos over a set number of beats. While making a click track is possible on a hardware metronome, it's almost impossible to make and edit on-the-fly because the functionality is hidden behind secondary actions of the buttons with labels that don't correspond. Plus, if the 9-volt battery dies, all of the click tracks are erased. Subdivide allows users to make quick edits to a track through an interface that gives clear feedback on what is being created. It also provides the ability to start playing a track from any individual section within it, removing the need to make redundant tracks for smaller sections of a large piece of music. Plus, tracks are backed up through Google's built-in data backup for Android, so users won't lose their tracks even if they lose their phone.
<br /><br />
![tracks screens](/subdivide-img/tracks.png)
<br />

We leveraged Android's Nearby API to allow users to quickly share tracks without the need for file management or an account. If two users enter Subdivide’s share mode, a list of tracks from the other device will show up on both devices. A quick tap will copy the selected track to the other device.

##### Remote

When it comes to getting musicians to play together over a distance, such as a marching band or drum corps practice, sound seems to move surprisingly slow. Having a metronome playing from the front of the field would result in the musicians in the back of the field playing behind the beat from the audience's perspective. Because of this, many bands and corps have a person standing in the back of the field with the sole responsibility of manually controlling a hardware metronome.

The Remote feature allows users to control an instance of Subdivide running on another device by pairing the two devices together over a wifi network. This removes the need for a person to be in the back of the field controlling the metronome. A band can plug a device into a speaker in the back of the field, and instructors can control a track or normal metronome from a device in the front of the field. Not only is this more convenient, but it also gives instructors greater control over the pace of rehearsal. It also minimizes the number of mistakes that happen during practice due to a person missing a tempo change with a hardware metronome.
<br /><br />
![remote screens](/subdivide-img/remote.png)
<br />

##### The App Icon

This is the second iteration of Subdivide's icon. It was made to support the adaptive icon feature on Android. It evolved from exploring a combination of the mathematical division symbol and a musical repeat symbol while playing off of the visual design of the different states of the metronome dots. The result was simple enough to scale down to small sizes, hold its ground when surrounded by other app icons, and provide some branding elements to work with.
<br /><br />
![subdivide icon](/subdivide-img/icon.png)
<br />

#### Project Takeaways

This app was one of my first attempts at tackling an entire product design from scratch--from the UX to the UI to the branding--so it continues to mature as my design skills mature. It's been a project that pushes me to learn new things and continues to have new needs, like a better pricing model and a marketing strategy. Subdivide stemmed out of frustrations and need from the marching arts community. Being heavily involved with it as an instructor, it was easy to get feedback on ideas and quickly test interfaces with other people. It has been rewarding to see a small side project turn into something real with a small but loyal user-base.

Check out Subdivide [here](https://subdivide.io).
