
# My Week 1 Journal

<details>
<summary>16th Oct 2024</summary>
<br>

Today I looked at Trac and tried to find a ticket. It really brought it home to me how intriciate the whole system is and how many people know parts of it very deeply. The descriptions of the issues that have made it to a status where it is considered worth investigating are mentioning aspects that will be difficult to replicate. Will I find something to work on that will start me off into the process of investigating?

Some tickets I lingered on longer than others...

#35791 - relates to css something I am familiar with with a recent css upgrade in work - has an owner, is assigned
#34976 - must ask Sarah about the comments on this one, she has written comments re accessibility - relates to the startapp commands - has an owner, is assigned
#18543 - https://code.djangoproject.com/ticket/18543 - what does 'new Bug' mean? 'Non image file can be saved to ImageField' - open 12 years ago, last modified 18 months ago - no owner - sent question to Paolo Melchiorre on team-saturn channel

In relation to that question 'new bug'. Paola said that 'new' is the status and it is not time-based, but more an indication that no one is working on it.
He suggested keeping track of the questions for create FAQs for new Contributors. Created QuestionsAsked.txt file and added this first question for future reference.

Nice also to see our Team photo taken at our first Team Saturn meeting by Paolo. We all look nicely enthusiastic!
https://discordapp.com/channels/1114005656937177168/1290084064573001778/1296215141263872030

</details>


<details>
<summary>17th Oct 2024</summary>
<br>
Saw a member of the team had a question on Discord (https://discordapp.com/channels/1114005656937177168/1290084064573001778/1296474011286638693) about a failed test in his PR (we use GitLab in work so I'm more used to calling it an MR there!) and had a quick look while I was working. It was to do with formatting and I waded in with my tuppence worth. Nice to get involved in a conversation and learned that Django has a pre-commit check on the formatting https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/coding-style/#pre-commit-checks

</details>




<details>
<summary>20th Oct 2024?</summary>
<br>
Went on the train to Cork on 18th Oct as a present for my birthday. Excellent time to continue browsing for tickets!
These few are ones where I thought I would be able to recreate the issue and will look again in more detail:

https://code.djangoproject.com/ticket/9373
https://code.djangoproject.com/ticket/12044
https://code.djangoproject.com/ticket/12246
https://code.djangoproject.com/ticket/12627
https://code.djangoproject.com/ticket/13224

Some of these are old, but have no patch. They do talk about things that I have used when making my projects, but mainly, I think I can recreate.

A cool article I found, written by a previous djangonaut, was just what I needed to read to calm down the rising worry in my stomach that I had when thinking about setting things up.
https://discordapp.com/channels/1114005656937177168/1260986020275556414/1284098589399846946

</details>




<details>
<summary>22nd Oct 2024  (pre-call)</summary>
<br>

Spent a few hours on Sunday trying to recreate the issue on ticket 9373 (https://code.djangoproject.com/ticket/9373) and it was interesting because there were two code examples in the comments and both produced warning complile errors/issues when I was making migrations due to using the most recent version of Django and not the version used in the comments. I need to investigate further to see if the ticket issue is still an issue or if the recent updates makes the issue redundant. 

Also found an issue with the docs that could maybe be an MR - a missing 'py' command when using Windows. It's in a couple of places that I've seen. Will check on next group call.
</details>





