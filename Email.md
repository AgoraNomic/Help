# Mail Providers/Clients

Agora should be playable from any mail provider or client. That said, some are more agreeable than others. The web interface for many popular mail providers (such as gmail) lacks certain features that makes messages more readable. There are solutions to this.

**Consider a desktop client.** A desktop client (such as Thunderbird), will work with most mail providers (including gmail). They can make up for the deficits of the web versions of these providers by giving you access to all the features that they don't support.

Of course, a big advantage of email is choice and portability. I and other experienced players use mobile, web, and desktop clients depending on current circumstances and needs. And some players get by exclusively using gmail's web client. So don't worry too much about it.

# Mailing List Basics

Agora is played on mailing lists. The mailing lists are set up such that when you send a message to one of the lists, it sends that message to all subscribers. Each list will prefix DIS, BUS, or OFF before new
messages to the list and Re: before replies to existing messages.

To reply to a message on the mailing list, simply hit reply but look at what is filled in for the "To:" field. If you did a normal reply to Agora-Business or Agora-Official, it's likely defaulting to sending your reply to Agora-Discussion. Just change the address if you want it to go elsewhere. Different reply methods (reply, reply to list, reply to sender) and different email clients will have different default behavior, so just double check that your message is going where you want it to.

When a player sends a message intended to be an action to Agora-Discussion (where actions can't happen), another player might say "NttPF" (Not to the Public Forum). The player that made the mistake might quote their original message and send it to Agora-Business with the message "TTttPF" (This Time to the Public Forum). Doing so is generally considered enough to do those actions.

## Mailing List Ettiquette

There are certain habits that are not required by the game but help to keep the mailing list readable. Many clients will let you set these as defaults.

**Bottom-Posting.** This is pretty much what it sounds like: Put your response below what you're responding to. Unfortunately many modern email clients default to top-posting. This doesn't work very well with threads that involve multiple people adding on, or when you want to respond to different parts of the message in their own sections.

**Shortening Quotes.** One potential disadvantage to bottom-posting is that your response can end up under a mountain of text. It's generally advised that you trim down your response to just the part you're responding to. Many clients will do this automatically if you highlight some of the message before hitting reply.

**Use Plain Text Formatting.** Non-plain text formatting options will often make complex emails difficult to read.

# Message Filtering, Sorting, Management

## Setting up filters

You probably don't want Agora messages to go straight to your inbox. It's recommended to filter them to their own folder. Some clients also support tags and color coding emails. All of these things will make it easier for you to keep up and keep organized, so spending some time setting them up will pay off.

### Gmail

[Gmail's filters](https://support.google.com/mail/answer/6579?hl=en) should be configured to ensure no emails go to spam.

The following filter will capture ALL agora emails:

    list:(agora-business.agoranomic.org) OR list:(agora-discussion.agoranomic.org) OR list:(agora-official.agoranomic.org) OR list(agora@listserver.tue.nl)
    
Apply this filter and mark 'never send to spam'. You can also apply a label and skip inbox if you want all Agora emails to go to a different folder.

If you're fulfilling an office it can be useful to create filters to find emails related to it. Here's an example filter to catch votes:

    (list:(agora-business.agoranomic.org OR list:(agora-business.agoranomic.org)) AND (assessor OR promotor OR for OR against OR present OR endorse)
