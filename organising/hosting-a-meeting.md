---
layout: default
title: Hosting an LRUG meeting
---

Part of our [organising](/organising) documentation.

# Hosting a meeting

> Note that this documents our current procedures during the COVID-19 pandemic where we're running remote meetings.  It'll be slightly different when we return to in-person meetings.

As host you are the face of the meeting for that month.  It may be your one hundredth LRUG, but it's likely at least one attendee's first LRUG so don't assume that everyone in the room, or the speakers, will have heard everything before or understand what is going on.  You'll need to do things:

* [Before the meeting starts](#before-the-meeting)
* [To open the meeting](#opening-the-meeting)
* [For each talk](#for-each-talk)
* [To close the meeting](#closing-the-meeting)

## Before the meeting

1. __be on zoom from 6pm__ - we invite speakers to turn up between 6 and 6:20 to run through AV check, keep an eye on the `participants` tab in zoom and admit the speakers as they arrive
2. __test the setup with each speaker__ - make sure they have actually gone into presenter mode for their talk and shared the right window etc...
3. __make each speaker a co-host for the meeting__ - this gives them some extra power on the night, like letting them unmute themselves and share their screens
5. __confirm the running order__ - check if any of the speakers particularly want to go first or last, and make sure they're all comfortable with the running order.  There's no right or wrong order, but if you have different length talks, it's often nice to have the shorter ones as breaks between the longer ones.
6. __remind speakers of their timings__ - let them know they can do Q&A but it should fit inside their timeslot (unless the agenda is actually full we can be a bit more lax about this, but it's best not to let things run over too much).
7. __open the "doors" at about 6:20pm__ - (or whenever the AV check is done), do this by disabling the waiting room in zoom and admitting everyone currently in it.  Do make sure people at this point people can unmute if they want to.  It can be useful to share some kind of "hey, welcome to LRUG, the meeting's not started yet" image.  Let people know that they can chat if they want, but equally they can leave their mic + video off and just watch.  Let people know the meeting will start at 6:30pm or thereabouts.
8. __turn on the zoom recording__ - recording the meeting lets us get videos out really quickly.  You can toggle the recording on and off between each speaker so we only record the actual talks, but that can be distracting (particularly with zoom's new robot voice "this meeting is being recorded" announcement) and easy to forget, so it's up to you if you want to do this, or just record the whole thing.

## Opening the meeting

1. __start the meeting just after 6:30pm__ - I usually gauge the participants count to see how many folk have turned up vs. how many tickets we've "sold" in eventbrite.  Drop off can be pretty high, so start as close to 6:30pm as you can, but it's ok to give it a few minutes if you think more folk might turn up.
2. __mute everyone__ - we don't want the speakers to be interrupted so mute everyone and set it so they can't unmute themselves.
3. __"welcome"__ - kick off the meeting with the admin announcements:
   * "welcome to the `<%= monthname %>` LRUG meeting"
   * "we have `<%= talk_count %>` talks lined up for you this evening"
   * "first we have `<%= first_speaker_name %>` with a talk about `<%= first_talk subject %>`" (repeat for each speaker, obvs)
   * "But before you get to hear those some admin from me..."
     * remind people about the readme, highlighting the code of conduct
     * let people know about the websites, that they're github repos if people want to help out
     * let people know about the mailing list and twitter for keeping in touch outside the meetings
     * tell them the dates of the next few meetings, and any pencilled in talks
       * "and I know this meeting isn't even started yet, but our _next_ meeting is..."
     * plea for more speakers, talking up how we don't need experts and are happy to help people shape their talks
   * but make it should less templatey?
4. __mention the sponsors__ - (if there are any) they might want to say something if they're actually in attendance. Make sure they know to keep it quick.
5. __throw it open to announcements from the floor__ invite people to use the "raise hands" function in zoom and you'll let them unmute to say their thing.
   * it can be useful to do this inbetween talks too in order fill the silence while the speakers get ready

## For each talk

1. __introduce them__ - pretty much "our next speaker is `<%= their_name %>` and they'll talk to us about `<%= their_title_slide %>`" - then you get to do weird zoom single person applause to welcome them to the stage
2. __tweet a screenshot__ - try to grab a screenshot of the speaker and their title slide so you can post a "up next is @`<%= whomever %>` talking about `<%= things %>`" tweet.  You can chain these together in a thread, perhaps starting from the original meeting announcement.
3. __be mindful of the code-of-conduct__ - be watchful for anything during the talks that might be a bit off-colour.  Speakers are pre-seeded several time with the code of conduct so nothing should happen in this regard, but you never know.  If anything does seem off - it’s up to you, either call a halt to it if it’s super-bad, or just mention it to them afterwards and suggest they apologise and change it when/if they post their slides somewhere.
4. __facilitate Q&A__ - if the speaker indicates they want to do Q&A you can facilitate it.  Ask people to use "raise hands" in zoom - it's an actual button, currently lurking in the "reactions" UI element, we don't want them to literally raise their hand on video.  The "participants" tab will sort people in the order they raised their hands, so you can ask them to unmute in turn to say their piece.  Mute them again afterwards - but be mindful if it looks like a back-and-forth to let them reply.  Keep an eye on time and don't let the Q&A run on too long, particularly if there are other speakers.  Sometimes there are no questions even if the speaker asks for them.  That's ok, but feel free to ask your own question if you think it would be less awkward.
5. __thank the speaker__ - time for more awkward zoom applause, then invite the next speaker to share their screen and start again!

## Closing the meeting

1. __thank everyone for coming__ - good to remind people LRUG exists for them
2. __remind them of the next meeting date__ - include any talk details we have and/or a plea for more speakers
3. __invite people to hang out__ if you'll be available to hangout on zoom after the fact, let people know they can stick around to chat, otherwise let people know the meeting will be ending
4. __say bye__ - you can come up with your own closing catchphrase, but I like "thanks for coming, byeeeeee!" with a half-hearted wave.
5. __turn off the recording__ - no need to record the post-meeting chats
6. __allow attendees to unmute themselves__ - can't really have a post-meeting chat if everyone is muted.
