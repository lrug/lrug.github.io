---
layout: default
title: Maintaining the LRUG community
---

Part of our [organising](/organising) documentation.

# Maintaining the community

> Note that this documents our current procedures during the COVID-19 pandemic where we're running remote meetings.  It'll be slightly different when we return to in-person meetings.

Although we're focussed mostly on the meetings, we do need to maintain the community outside the meetings, this means:

1. [Moderating the mailing list](#moderating-the-mailing-list)
2. [Replying to ad-hoc email requests](#replying-to-adhoc-email)
3. [Keeping an eye on twitter](#keeping-an-eye-on-twitter)
4. [Populating the speaker backlog](#populating-the-speaker-backlog)

## Moderating the mailing list

The [mailing list][mailing-list] is a [Mailman](https://www.gnu.org/software/mailman/) instance.  We don't have full control of the list software as it's not installed in our shared hosting, it's a service run by our hosting provider on our behalf.  What this means is we don't have access to the code or database directly, but do have full access to [the admin interface][mailing-list-admin].

The list is configured so that new members are set to require moderation, but existing members are able to post without requiring moderation.  This probably means about 50% of the list members require moderation.  When we turned moderation on in 2013 there were ~1,000 members; at time of writing there are ~1,500 but I expect that more than 500 people require moderation due to people unsubscribing.  The list will also hold emails for moderation if the size of the email is greater than 100kb (usually because of an attachment).

When someone requires moderation an email is sent to the organisers by mailman with a copy of their email and a link to the moderation interface.  This is also sent to [Harmonia][harmonia] which will pick one of the organisers to deal with the email.  Feel free to ignore the email if harmonia doesn't choose you to handle it.

### What to look out for when moderating

Most emails requiring moderation are from people new to the list posting jobs.  Our role is not to fully moderate the list; we're not checking for typos, or avoiding people from making fools of themselves.  We are however looking for obvious [code of conduct][coc] infractions and people breaking the rules of [job ads][posting-jobs-rules].  We also check for people who have clearly replied to the list when they meant to reply just to the poster (usually in reply to a job ad).

If in doubt, talk to the other organisers in our [mailing-list slack channel][slack-mailing-list-channel] and get a second opinion.

To moderate you use the mailman interface and choose to accept, defer, delete, or reject.  Usually we accept or reject.

* __accept__ - lets the mail through to the list
* __defer__ - leaves the mail in the moderation queue
* __delete__ - silently deletes the mail from the moderation queue without posting it
* __reject__ - deletes the mail from the moderation queue and sends a message to the sender.

If you decide to reject the email you should write a message to the sender explaining why and give them steps to re-write their email so it'll get through moderation a second time.

The rejection messages are only sent to the sender, so it can be useful to give a summary of your rejection notice in the slack channel to keep everyone up to date.  It's likely that harmonia will pick someone else to deal with their 2nd attempt.  If the author replies quickly, and you're already in moderation mode feel free to do the harmonia victim a favour and handle the reply yourself rather than leaving it for someone else.

Note that sometimes we get an email saying something needs moderation, but the admin interface doesn't show anything.  The email author is sent an email letting them know they have been held for moderation, and they are able to self-reject their email so this _may_ be what's happened.

## Replying to ad-hoc email

We currently only use [Harmonia][harmonia] to handle moderation requests.  This means that all other email to the group addresses needs someone to handle it.  All the emails are piped into our [organisers slack channel][slack-organisers-channel] to let us know about it.  We haven't quite worked out a good system for picking who will respond to these emails, but if you're the chosen main organiser for the next meeting, then you could take point on these, but ddo share the load!  We should try to reply to emails within a few days.  Everything is visible in the [shared inboxed][shared-inbox], but it can be useful to mention the gist of your responses in the [organisers slack channel][slack-organisers-channel] to keep everyone up to speed.

There are 4 main email addresses with separate inboxes in the [shared inbox][shared-inbox]:

* talks@lrug.org - intended for people who want to volunteer a talk, or find out about how to do that
* sponsors@lrug.org - intended for people who want to sponsor a meeting or giveaway or something
* complaints@lrug.org - the address in our [code of conduct][coc] that we suggest people use to get in touch
* organisers@lrug.org - general address for other queries

Ideally people use the specific addresses for things, but as you imagine, people often just email organisers@lrug.org directly.  It's all shared anyway so not a huge problem.

The [shared inbox][shared-inbox] lets you reply as the @lrug.org address and see the whole email thread.  Which means you can pick up where another organiser left off.  Feel free to sign off the email as yourself, so the person you're emailing knows who they are talking to.

### Common email topics

#### I posted to the list but can't see it

The mailing list software is set so that only members can post to it.  Emails sent from addresses that are not signed up to the list are silently deleted by the list.  This can cause confusion when someone is signed up using one email address (their personal one for example) and they try to post from another one (their work one) and it doesn't come through.  First thing to do is check the member list to see if you can find them, if not reply along these lines and suggest they sign up again, or post from their alternate address.

#### TODO: more common topics not covered by the speakers and sponsors sections above

### TODO: template responses

## Keeping an eye on twitter

People sometimes talk to us via the [LRUG twitter account][twitter] so we should keep an eye out for it.  We've set up a [slack][slack] integration to feed all tweets that mention us (or that we send) directly into the [organisers channel][slack-organisers-channel].  If we spot something that we feel we should reply to, then you can hop onto twitter to do so as @lrug.

Other than this, we normally only use twitter to talk about the meetings.  Something like:

1. A tweet (or thread) announcing a meeting once we've [written it up](/organising/organising-a-meeting#announce-the-meeting) and inviting people to sign up
2. A tweet (or thread) on the morning of the meeting reminding people that it's that evening
3. A series of tweets during the meeting with a screengrab / photo of each speaker
4. A follow-up tweet for each speaker once we publish their videos

Sometimes we use twitter to [ask for speakers](#populating-the-speaker-backlog) or any other questions we have for the community.  Occasionally we retweet things that seem relevant for the community - we could do better at this for sure.

## Populating the speaker backlog

LRUG is 90% about the meetings, so without people volunteering to give talks we've nothing to fill those meetings.  This is probably the most important part of LRUG, and, unfortunately, the hardest.

### What do we want from speakers?

A lot of this is covered in our [main readme](/#talks), but we repeat it here with an "organisers twist".

#### Length

As mentioned in [our organising a meeting section on full agendas](/organising/organising-a-meeting#a-full-agenda) we have 80 minutes to fill every meeting.  To make it easier for ourselves we suggest people give talks that fit into 10, 25, or 40 minute slots.  For each meeting we aim for a mix of lengths to fill the agenda.  Ideally we have a backlog of speakers who are generally available for any future meeting, and between them are willing to speak across all our timeslots.  This makes it easy to fill the agenda when it's time [to confirm the speakers for a meeting](/organising/organising-a-meeting#confirm-the-speakers).

These slots _are_ a convenience for us to make it easy to work out when a meeting is full.  It is not important that a speaker actually fill their slot, but it is a problem if they're going to run over.  When arranging a talk with a speaker stress to them that they can talk for as long as they like as long as it fits in one of those slots.  We will keep time on the night and stop them if they run over.  Let them know that we'd prefer they take a longer slot and not fill it than take a shorter slot and fail to say everything they wanted.

#### Topics

We are a ruby user group, and most obviously care to hear about things people are doing with the ruby programming language, but that's not all we care about.  There are plenty of other ruby-adjacent topics we could hear about so our standard mantra is "if it's something you, a ruby programmer, want to talk about, chances are other ruby programmers will find it interesting too".

If in doubt about the suitability of a given volunteer's topic, ask the rest of the organising team.  We can also give the volunteer feedback on some changes they could make to their proposed talk to make it more relevant or interesting to a crowd of ruby programmers.

#### Presentation style

It's easiest to give a standard "lecture" style talk where the speaker has some slides and talks for their allotted time before opening up for Q&A at the end.  We're open to other things so you should remind volunteers that they don't just have to give a talk.  They can run a workshop, or chair a panel discussion, or facilitate some kind of practical event, or host a quiz, or any number of other ways of filling the time we have for them.

#### Target audience level

We should remind volunteers that it's a mixed ability group, with people fresh from a bootcamp all the way up to people who've been using ruby for years.  It's hard to target a mixed group, but as long as they don't talk down to their audience, or assume too much knowledge they should be able to let everyone walk away having learned something new from their talk.

Equally, we don't expect that only experts will talk.  We love for people new to ruby or programming to talk to us about their experiences.  Their fresh perspectives can be eye opening for those of us who haven't questioned the way things are done for a while.

### Offering to help

We have a standing offer to help people interested in talking at LRUG to shape their talks.  We can help at all stages from helping people come up with a topic to talk about, to turning that topic idea into a concrete proposal, to giving a detailed outline a once-over, to running a rehearsal on a draft of a talk.  We want their talk to be great, and we're willing to put in any effort that's needed to help make it so.

### How do we find speakers?

An excellent question.

Mostly just by asking on [the mailing list][mailing-list] and [twitter][twitter].  Increasingly desparately as we get closer to a meeting date without any confirmed speakers.

We reach out to our own networks to invite people to speak too.  We know we have a much better hit rate with a targeted "hey you've been workin on that specific ruby recently, why not talk about it at LRUG" than we do with a general "hey, we need some talks for next month".  This requires us to know what people are working on though, so a bigger network is really helpful with doing this.

It can be useful to see who has spoken at some of other user groups recently and see if those people could be enticed to come and speak to LRUG too.

### Keeping track of volunteers

We keep track of our speakers on [a google spreadsheet](https://docs.google.com/spreadsheets/d/13RNjhOF1elxSA8yaCLsEZOLf5DnwBuVQehfHJJWLB_E/edit#gid=460069181).  Ideally there are about 2 to 3 meetings worth of volunteers on this list so we are comfortably able to fill a meeting when the time comes.  We use the [shared inbox][shared-inbox] to communicate with our speakers so that all the organisers can see what's going on.  If someone does email you directly, cc your reply to `talks@lrug.org` and it'll be captured by the software and then you can reply from there.

It can be useful to edit the subject line to add a potential meeting date if a volunteer has indicated a preference.  This helps the next organiser quickly scan through to chase up people who are already primed for the meeting they're due to organise.

Filling in the spreadsheet with details of each speaker, their talk, and confirmation status will also help keep other organisers up to date.  In particular the "Length", "Offered?", and "Confirmed?" columns are summarised on the "Meetings" sheet to list the speakers for each meeting, and the total runtime.

### Email templates

#### Replying to an offer of a talk

> Hi `<human>`,
>
> Thanks for volunteering your talk on `<topic>` for LRUG. `<something positive about their talk suggestion - maybe offer some tips if they've asked for them, or pointers to talks we've had recently on similar topics to guide them away from the obvious repetitions>`
>
> In terms of timings at LRUG we give speakers a choice of slot timings; 10 minutes, 25 minutes, or 40 minutes.  The slot time is all the time you’d get in front of the group so think about whether or not you want to take Q&A at the end when picking your slot.  It’s not important that you actually fill the slot though - pick the one that fits your talk best.  It’ll be a problem if you need more time than your slot though - we’d rather you took the longer slot and didn’t fill it, than take a shorter slot and rush through things.
>
> Let me know what you think about all this and we’ll get you pencilled in.  Please do take a look at http://readme.lrug.org/ while preparing your talk.  There’s our code of conduct which would apply to your talk, but also tips about colour schemes that work well with our projector and lighting, resolutions for the projector, etc...

If we're not desparate for talks and have a backlog adding something like the below can be useful to set expectations:

> Looking at the volunteer stack it’s probably 2 months before there’s a free slot.  We offer slots in a first-come, first-served basis, if someone passes we offer it to the next person on the list.  We’re usually in touch with people about 5-6 weeks before the event to confirm details.  `<some details about the stack to set expectations>`
>

or, if you want to give more specific detail something like:

> Looking at our list we think there’s a slim chance that there’d be a slot for you in August (8th) but Sept (12th) looks promising.  Failing that the October (10th) meeting is definitely free.  If you needed something booked in right now I could confirm you for Oct now, otherwise I’ll just put you on the list and get in touch when there’s a slot available.  If it was August we’d probably be in touch in the next week or so as folk pass on the slots we offer them.

Sometimes a speaker is suggesting a talk on a topic we've already covered recently, so it can be useful to add something letting them know this.  Ideally we're not trying to put them off, but more to suggest they might be able to rely on some knowledge folk have gained from those talks, or help them work out what they no longer have to cover in theirs.  Something like:

> We’ve had a couple of talks about deploying with AWS and docker recently, so it’d be good to review those and work out how yours could be different.  There’s this talk on convox from May: https://lrug.org/meetings/2016/may/#convox-painless-deployment-of-docker-on-aws, this talk on docker for development from Feb: https://lrug.org/meetings/2016/february/#fareed-dudhiahttpstwittercomfmdud---rails--docker-for-development-no-mess-no-fuss, and this one on containers from Sept: https://lrug.org/meetings/2015/september/#containers-patterns-for-rails.  The first two are short talks, and the last one is longer, but hopefully not too onerous to skim through.
>
> If you still think there’s something in your topic that we’ve not seen recently then let me know and we can schedule you in.  We’re sure there is something in your topic though: it’s a fairly broad subject and we’ve not had anything about Elastic Beanstalk specifically.

##### Offering someone a slot when you know how long they're gonna talk for

> Hi `<human>`,
>
> There's a `<length>` minute slot at the `<month>` meeting on Monday `<date>` available if you want it for the talk you offered LRUG.
>
> If you’re happy to take this slot what I need from you to write it up with Skills Matter and on lrug.org is:
>
> * Talk title
> * Talk description - a sentence or two is all we need - feel free to include any links you think might be useful too if you’d like
> * Talk length `<length>`
> * Preferred URL to link your name to - e.g. twitter, github, linkedin, personal blog, etc...
>
> You should also take a look at http://readme.lrug.org/ while preparing your talk.  There’s our code of conduct which would apply to your talk, but also tips about colour schemes that work well with our projector and lighting, resolutions for the projector, etc…  Feel free to get in touch with any questions you have too.
>
> Reminder: `<length>` minutes is the total time you’ll get on the stage; you don’t have to fill it, but it’ll be a problem if you need more time than that.  If you think your talk will take less than `<length>` minutes and would fit in a shorter slot (25 or 10) then let me know, but I’d rather you kept the longer slot and didn’t fill it than take a shorter slot and rush through things.
>
> If for whatever reason you’re unavailable for `<month>`, that’s totally fine.  Just let me know if it’s a “not `<month>`” or “not ever” so I know if I should get in touch again when a slot becomes available at a future meeting.
>
> Either way, I’d appreciate hearing back from you as soon as possible (particularly if it’s a no) so I have plenty of time to give other speakers the opportunity to take the slot."

##### Offering someone a slot when you don't know how long they'll talk for

> Hi `<human>`,
>
> There's a slot at the `<month>` meeting on Monday `<date>` available if you want it for the talk you offered LRUG.
>
> If you’re happy to take this slot what I need from you to write it up with Skills Matter and on lrug.org is:
>
> * Talk title
> * Talk description - a sentence or two is all we need - feel free to include any links you think might be useful too if you’d like
> * Talk length `<length>`
> * Preferred URL to link your name to - e.g. twitter, github, linkedin, personal blog, etc...
>
> You should also take a look at http://readme.lrug.org/ while preparing your talk.  There’s our code of conduct which would apply to your talk, but also tips about colour schemes that work well with our projector and lighting, resolutions for the projector, etc…  Feel free to get in touch with any questions you have too.
>
> In terms of timings at LRUG we give speakers a choice of slot timings; 10 minutes, 25 minutes, or 40 minutes.  The slot time is all the time you’d get in front of the group so think about whether or not you want to take Q&A at the end when picking your slot.  It’s not important that you actually fill the slot though - pick the one that fits your talk best.  It’ll be a problem if you need more time than your slot though - I’d rather you took the longer slot and didn’t fill it, than take a shorter slot and rush through things.
>
> If for whatever reason you’re unavailable for `<month>`, that’s totally fine.  Just let me know if it’s a “not `<month>`” or “not ever” so I know if I should get in touch again when a slot becomes available at a future meeting.
>
> Either way, I’d appreciate hearing back from you as soon as possible (particularly if it’s a no) so I have plenty of time to give other speakers the opportunity to take the slot."


{% include organising-links.md %}
