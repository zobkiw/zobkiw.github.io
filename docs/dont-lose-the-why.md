###Don't Lose the Why
**_Documenting the obvious, while it still is_**
*by Joe Zobkiw*

---

You're embroiled in a bug. You've been digging into it for hours or days. You know alot of details about what is happening and how to fix it. In order to get here, you talked (or typed) to a number of other engineers (from other teams or even companies). You have URLs to dashboards and a testbed program you wrote to reproduce the issue in isolation. You're in a position where it could be fixed...if only...all the pieces fell into place...which unfortunately, right now, they are not. There are competing priorities. The fix for this issue will have to wait.

####What now?

If you haven't been doing it all along, now is the time to document the hell out of the issue. In a document, in the issue ticket, wherever it is appropriate. So what should you document?

- an executive summary
- a technical overview
- a detailed technical deep-dive
- a list of who you discussed this with and what you leared from them
- a list of those who would be involved in the repair and testing of the issue
- links to public discussions, other code, dashboards, and anything else that helped you get to this point

####But why?

You might be wondering why you havae to spend all this extra time documenting things you already know. I mean, you already know the details. Your memory is good. It's not like you're going to forget this stuff by the time you get to the bug next month.

Unfortunately, there are other factors involved here. You might not get to the bug next month. It might be in 6 months. It might be next year. It might be never and someone else will encounter it between now and then - you don't want them having to unravel the same ball of yarn that you just had to.

There are managers (yes, those people) who may need to answer to the status of the issue at a moment's notice. Having it fully documented helps them, and other engineers, understand the issue without having to bother you while you're on vacation.

####Doing it all along

As eluded to above, you should be documenting all along. This goes for lots of things - but certainly bugs. As you find out information, document it. As you learn new information, add to your documentation. You don't even have to delete what you previously learned (even if it is now no logner useful or wrong) as this can help other engineers learn the process you took to get to this point. Leave the story in tact. You never know when those early learnings, although maybe no longer needed, could be helpful. Your teammates will thank you.
