###Dynamic Prioritization
**_Learning to manage your shifting day_**
*by Joe Zobkiw*

---

Unless you are an entry level engineer, in your first month on the job, focused on one very specific task, you will almost certainly have multiple, shifting concerns throughout the day, competing for your time and attention.

At any one time, you may have 3 items in your queue, one of which is actively being focused on, another that is in a holding pattern waiting for stakeholder feedback, and another waiting in the wings for your attention. But what happens when yet another issue, for example, a production issue in your code base, appears out of nowhere and requires your immediate attention? What do you do? How to do manage this 4th thing under the pressure of your customers being unable to use your app or access your web site?

The simple answer is: you just do it. You put the other things aside and you focus on this new item, which clearly has become the top priority, even if unexpectedly. You may have sat at your computer this morning, knowing your plan for the day, but the best laid plans can be upended by an errant deploy, feature toggle change, a server or database corruption, or a hacker. You may have little to no control over those things, but when they arise, you need to be involved in the response to repair them.

####Managing the tangible

First and foremost - focus on ceasing the issue - stop the bleeding. This may mean tracking down the cause and reverting the deploy or flipping the feature toggle back - maybe restarting the server or database. Whatever it takes to get your system back to a usable and non-alerting state. If the problem started at 7:35AM and someone flipped a toggle at 7:34AM you might be on to something - but be sure you've found the cause before looking for the fix.

After the initial fire is out, you can re-group to figure out how to re-build and truly fix the issue properly - adding monitoring and other checks to ensure it doesn't happen again. The prioritization of the work in this phase may not (or may be) as urgent. Regardless, ensure that you document everything you know so, when you do come back to it, you can pick up where you left off with a deep understanding of the details. Get others involved to help you document the timeline - crowd-sourcing is a great way to keep yourself honest and gain accurate and complete data on an issue.

####Managing the intangible

The stress of this type of situation can be real. Experienced managers know this and will support your efforts, helping you to manage the re-prioritization appropriately. This may include getting others to assist (either on your original work or the issue at hand) or simply running blocker for you so you can focus on said issue and not worry about any fallout with stakeholders and business partners.

Experienced stakeholders will also understand the risks of software development and support and will understand that things happen that can cause shifting priorities and delays. When scheduling a project, if you know your day-to-day environment well enough, you can easily build-in buffers to help make these "side excursions" something that are planned-for and have minimal impact on the overall project timeline.

Sometimes people will be freaking out - try to ignore this - your job here is to resolve the issue - not deal with a tantrum. Focus on what is needed at the time, you can come back to the rest later.

####What about non-emergencies?

There are plenty of times when something comes out of nowhere. Maybe you find out in your daily standup, or in a 1:1 with your manager, that you now have to pause your current work and attend to something else that has been deemed more critical. In these cases, it's important for you to understand the reasoning behind this. There is nothing more annoying than to be handed work, told it's the new top priority, but not understand the "why" of it all.

Take the time to ask your manager what makes this the top-priority. Understanding the thinking that went into this decision can go a long way to allow you to buy into the decision and mentally manage the context-switch and interruption from your other work. You may not have the influence to change the decision, but having the context into why it is now your number one is important.

For example, maybe it was just learned that there is a promotion or sale coming up in 2 weeks and this code needs to make it out before then so customers can take full advantage. Maybe this was a miss, but it doesn't change the reality that this needs to get done in a specific amount of time. You can continue to ask questions as to why it was a miss, it's your right (and obligation) to understand the whole story - as much as possible. Knowing these things may allow you to expose a concern that could (once again) change the trajectory of the work. For example, what about that other change that was done last week for this promotion - won't that conflict? Oops! No one thought of that!

####Mentally preparing for shifting priorities

If you enter each day with your personal plan for making the most of your time, that's a great first step. However, allow yourself some flexibility. You don't need to plan for every possible interruption or change, but simply allow it to occur when it needs to. This will help to lower your stress about change in general.

Look at change as an opportunity to learn something new - to increase your knowledge - and practice the art of allowing it to simply occur. You'll get through it - you have before - and you will again.

Practice putting things on the shelf. Document where you are, commit your work in progress, create the closure you need. This way, when you come back to it, you can pick right up where you left of. Make it easy on yourself in these situations.

Generally speaking, work is an endless stream of floating rubber ducks. You pluck a duck from the water, work on it, then pluck the next duck. Some ducks will pass you by, and that's OK. That's why you have teammates - they pick up those ducks. The work will never end but, once in awhile, you will get a short break of no ducks floating down the stream. Use that time to rest and refresh yourself.

####But _how_ do I prioritize?

Sometimes you will be told what to prioritize, but other times you may need to figure it out yourself, or you may be the one doing the telling. In these cases, you want to look at multiple vectors to determine prioritization. Things to consider include:

- What is important now?
- What needs to be done first?
- What has the closest due date?
- How long will something take?
- What is the importance?
- What are the risks?

The goal is almost always to have a thing done by a date or time. Knowing how long something will take, with enough room built in for risk, can help you determine if other things need to be dropped to take this on or if other things can be completed first and THEN this new item falls into line. The goal is balance and accomplishing the tasks that need to be accomplished, on time.
