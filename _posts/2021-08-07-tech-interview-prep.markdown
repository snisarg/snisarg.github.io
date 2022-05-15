---
layout: post
title:  "Tech Interviews: process, preparation and hacks"
description: "Lessons learned from tech interviews, how I approach interviewing and preparation guidelines."
date:   2021-08-07 00:00:00 -0800
categories: blog
comments: true
---
*Approaching tech interviews: from preparation to offer acceptance.*

Till date, I've had the fortune and misfortune of going through the experience of not having any interviews, to multiple phone screens a day and back to back on-sites. This note will summarize things I've learned giving 40+ interviews and having 25+ offers in total in the 4 times I've interviewed.

This is a follow up note to [Discussion: change jobs or stay put]({{ site.baseurl }}{% post_url 2019-09-02-stay-put-v-jump-ship %}), if you have made up your mind to change your job or see what's out there.

## Process summary

The top Software Engineering roles (and other related roles like data engineering and ML engineering) are fiercely competitive and need preparation and practice because unfortunately what one does on the job day to day isn't generally what's asked in a coding interview round. This makes it different from interviews in other fields.

The process looks something like:

1. Prepare for interviewing, usually involves practicing coding challenges and brushing up system design skills.
2. Reaching out to friends for referrals, recruiters on LinkedIn and applying on the company website.
3. For each company that you hear back from, expect the following in order:
    1. Recruiter reach-out for role alignment and interview dates. Leveling and compensation expectations can be discussed at this stage too.
    2. Phone screen round: a single interview round; generally consists of a coding challenge.
    3. On-site interviews: Series of coding, design and behavioral rounds generally with the team you would end up working with
    4. Offer
4. Compare offers, negotiate.
5. Accept one, decline others. Pick a start date.

## Steps In The Process

Let's summarize the various stages for getting ready for interviewing and what we’ll be talking about in each of them:

1. Preparation: things to consider before or at the start of interviewing. This is about getting mentally prepared.
2. Warming Up: initial groundwork required for interviewing, soft-starting coding preparation
3. Honing in: serious preparation, start talking to companies and recruiters
4. Interviewing: tips and techniques for the real interviewing phase
5. Offer Negotiation: crucial last steps to get the most out of your time invested to prepare
6. Accepting the offer: the finish line
7. After Interviewing: some suggestions about wrapping up at the current workplace

Let's talk about each of these stages, and the mindset building and interview related activities that go with them.

## Preparation

### Motivation

Ask yourself, “Why am I doing this?”

Be aware of the reasons why you are looking for a change. You don’t need something strong or concrete, but there has to be a reason you've decided to spend a considerable amount of time preparing, planning and interviewing. Identify and internalize that reason.

This keeps me motivated in the face of rejections or from lethargy of spending effort into preparations.

### Programming Language of Choice

To ace the coding interview, a good grip on the programming language you choose for coding rounds can make a huge difference. Practice with only that one language for best results. Here are some things to consider while making that choice.

- Role or job specific limitations

    Pick a language that makes most sense or one that is acceptable for the kind of roles you want to apply for. For most generic software engineering roles, any language goes. If you are focused on say iOS development roles or targeting High Frequency Trading tech roles, companies may not allow a lot of flexibility with which languages you can interview with.

- Pick the programming language you are most familiar with.

    This saves time trying to master another one just for interviews, reduce chances of mistakes during the coding interview and puts you in a position to answer questions about the specifics of a language (For example, Java's threading or Python's Global Interpreter Lock) if they come up.

- Concise and terse languages

    Even if it may not be your most familiar language, I recommended a language that is expressive and terse. For example, Python over C++.  Writing code on a whiteboard can get time consuming in a 30 minute coding round and a language like Python can reduce the lines of code drastically to achieve the same logical solution.

    Terse programming languages make it easier for the interviewer to understand the logic but also allows you to find small bugs more quickly.

    Story time: In an interview for an internship for a competitive company during grad school, I couldn't finish writing the code even though I had figured out the solution. At the end, the interviewer confessed that the problem was complicated enough to not get a fully written solution in a language like Java in 25 minutes unless one had seen it before and recommended using Python. (They still rejected me!) This for me was the final push to switch to Python and I highly recommend it.

    You don't have to learn the language in depth just for interviews. Back when Java was my favorite language, I made it clear to the interviewers that I use Python because it is terse but wouldn't know every detail of the language and that I'll happily write a solution and take any questions about Java if they insist.

### Shoot for multiple offers

I would strongly recommend having the goal of getting multiple offers.

- Multiple offers are instrumental in negotiating a better compensation package. Details about other offers is often collected by recruiters to fight for a better offer approval for you. Even if you are absolutely obsessed about working at one and only one company, presenting them with an alternative offer can help score a better pay.
- Interviewing at different companies gives you a peak into diverse work cultures, company missions and what different teams are working on. This is a great discovery process and could influence your current or future career decisions.
- When you're given an offer with a deadline, it's easier to turn it down if you're still interviewing when you have another offer at hand with some time left before expiry. I've had offer deadlines frequently extended too when I turn down an offer because of exploding deadlines.
- You get your name in the recruitment systems of everywhere you apply and interview at. Even if you don't make it through, recruiters can reach out in the future, making it easier to schedule an interview. Some companies skip phone screens and even cut a few rounds in the interview process based on your past performance.
- More offers give you the flexibility to make a more informed choice. Maybe a remote option doesn't matter right now but could in the future, or an offer with flexibility of which city you work from could make you consider moving to New York like you always wanted to!

### Start updating your resume

Add new projects and experiences into your resume and LinkedIn profile. Keep your resume to 1 page strictly unless you are applying as a researcher and need to showcase all your publications. 

If you have worked on more projects than what you can fit on one page, use these heuristics to decide what to keep and what to remove from your resume: 

- Relevance

    Highlight projects that showcase skills for the roles you are applying for. An Android project won't help you stand out for the Machine Learning Engineering position that you are shooting for. 

- Impact

    Highlight projects that show scope, responsibilities, design skills, metric impact, project or people management skills. Bonus points for including measurable numbers. This shows the maturity and level at which you have undertaken projects, and is more effective than including buzz words. 

- Recency

    Your school project may have been cool, but hiring managers are more interested in what you are working on right now. 

    Corporate projects are preferred over personal projects unless they were developed in open source and have significant impact or adoption. The reason is, with corporate projects, there are stricter deadlines, money at stake, and more challenges working with people and teams. 

- Visibility

    Work that can be seen by people outside the company, like open source contributions or work that went into papers or company press announcements is preferred. 

Note that you will be asked questions about the projects you include in your resume. Be ready to talk about your exact responsibilities and answer specific questions about the project. 

Keep updating your resume as you move along in the process, it can take some time depending on when you last updated it. Don't block on this step or try to do this in one sitting. 

### System Design

System Design needs less preparation and comes with experience on the job as well as reading blog posts, articles and papers about new developments in your field of work. The importance of these rounds increases compared to coding interview depends on the seniority of the role you are shooting for. 

From a preparation standpoint, you ideally don't want to prepare for these all at one go. Instead, start from the get go all the way to when you start interviewing. Consider:

- Reading books on design

    [Designing Data-Intensive Applications by Martin Kleppmann](https://www.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/) is one of the best books to brush up on design skills.

- Interview specific resources online

    [donnemartin's System Design Primer](https://github.com/donnemartin/system-design-primer) is an excellent read resource for a quick recap on basic infrastructure system design principles.

- Read seminal papers or articles about how these systems were designed.
    - [https://paperswithcode.com](https://paperswithcode.com/) has curated list of top AI papers.
    - [https://blog.acolyer.org](https://blog.acolyer.org/) or The Morning Paper is an incredible resource for top papers summarized well.

- Tech blogs
    - [http://highscalability.com](http://highscalability.com/) for scalable backend designing and curated experience stories.
    - [InfoQ's YouTube channel](https://www.youtube.com/user/MarakanaTechTV) has great videos about a lot of interesting topics.
    - Netflix's blog is great: [https://netflixtechblog.com](https://netflixtechblog.com/)
    - Almost every tech company has a blog, so pick your favorite!

## Warming up

### Beginning coding practice

Given how much competitive style coding is stressed upon these days, practising coding becomes the most time consuming aspect of interview prep. I therefore like to start as soon as possible with some soft ball questions to get into the mindset, understand the user interface.

For this, pick any of the popular competitive coding or dedicated programming interview preparation websites.

- [Leetcode](https://leetcode.com/)
- [Hackerrank](https://www.hackerrank.com/)
- [CodeWars](https://www.codewars.com/)

I recommend starting with the easier ones on the website of your choice. Solve the problem even if the solution to it is obvious to you just by reading the questions. You'll be surprised how many edge cases a simple problem could have.

I generally do easy problems till I find them too easy. This is when I'm getting them right back to back covering all edge cases and don't need a lot of thinking. If you're good at competitive coding, feel free to skip this step.

### What do you want out of a new job?

Make a list of what you'd like to see in your dream job. Order it by priority. Here's some of the things to consider:

- Team culture, manager, projects, opportunities
- Pay
- Learning opportunities
- Career growth opportunities
- Ideal role, level
- Business area (product, infrastructure, machine learning)
- Location preferences
- Work life balance
- Personal brand building or reputation

I prefer writing them down beforehand. It gets harder to make a decision when you have multiple offers, each with their own pros and cons. Having a list handy about why you started interviewing and what you were really looking to get out of it can help break ties later and take the emotions out of the decision making.

### Where do you want to go?

This is generally when I start making a list of places that I'd love to work at. Don't worry about going crazy, put the name down. How selective you are can really change on where you are in your career.

This is a step of discovery.

- Check out all the companies you always wanted to work, see what roles are open and what cities they're hiring in.

    Don't worry if you think you're not capable of getting a call or clearing the interview. The worst they can do is say no to you. Gotta love limited downside and unlimited upside scenarios.

- Talk to your friends and peers if they are happy with their jobs and would recommend working in their current or past roles.
- Read about what's going on in the startup ecosystem, any exciting hot startup that could interest you. 
- Find articles about new or fast growing companies that have a purpose that resonates with you.
- Look for recruiter emails received in the past.

## Honing in

### Apply for jobs

The order to apply for jobs, I recommend following this order:

1. Ask your friends or connections for referrals. A referral ensure that a recruiter will at least take a good look at your resume.
    - LinkedIn is a great way to find out who in your network works at a certain place. Type the name of the company in search and see 1st and 2nd degree connections. You could ask a mutual friend to introduce you to someone who's a 2nd degree connection. Knowing an insider is helpful.
2. Look for recruiter emails in the past.
    - I have a special label/folder for these, so they are easy to find.
3. Apply via the company's job portal
    - I've personally not found a lot of success using this method. Resumes in the general pool are easy to ignore by recruiters in a lot of companies.
4. Mark yourself as looking for a job on LinkedIn.
5. Reach out to recruiters directly on LinkedIn. A lot of them have their work emails on their profiles. I found a lot of success directly emailing my resume to recruiters this way when I was a fresh grad.

### Serious coding prep

Once the coding problems on the websites are too easy, start with the medium difficulty ones. The way I approach solving them is by simulating an interview environment.

- Time yourself on how long it takes to solve a coding problem. Try to finish problems under 30 minutes for the medium difficulty ones to 45 minutes for the most difficult ones. Interviews are generally this long.
    - It'll take longer initially, and that's completely normal. The goal is to get faster, but it'll take some practice.
- Talk out aloud or in your head as if you were talking to an interviewer about how you are approaching this problem.

    I cannot stress this enough.

- Consider various options. You should be able to talk about logical algorithms verbally as well as tell the time and space complexities of each of the solutions, which are the bulk of the comparisons of any algorithm.
- Start coding only when you cannot think of a better solution.
    - Try to get the right solution in your first attempt. There's no going back in a real interview.
    - Do not hit submit to see if you got it right. We are trying to simulate an interview here! Find bugs by reading the code to make sure it's right once you are done. The idea is to get it right without any modifications in the very first attempt.
    - Ensure that the variable names used are terse (for speed) but also not complete gibberish.
    - Once there's enough confidence, try to write the code in one go, without adding or editing lines. This is mainly for whiteboard coding interviewers, where adding lines of forgotten code in the middle can be jarring to read. I like to write a quick pseudo-code of the important steps on the side of a whiteboard before starting the code for this reason.
- Don't spend more than 1 hour on any single problem. Simply read the solution. There are too many problems and limited time. Err on practicing more problems instead of trying to get a solution without help. Slowly start reducing the time you wait before looking up the solution as you practice more, all the way down to 30 minutes.

A lot of mistakes are going to happen during the initial preparation. Once you start getting a lot of them right in the first attempt, I would recommend switching to a real whiteboard to truly recreate that environment. Writing can be messy and it'll be nice to get that practice in too.

### Recruiter screens

If a company is interested in your profile, a recruiter will reach out to you to see if you'll be a great fit for the role and the team they are hiring for. The data points they are looking at are:

- Team and role fit
- Relevant work experience
- Motivation and interest in the company
- Your timelines for interviewing

## Interviewing

### Scheduling

- Phone screen

    Schedule them according to your calendar and commitments. I've scheduled multiple ones a day before, but keep some gap between them in case of spill overs.

    I recommend using wireless headphones so your hands are free to type. Test your internet, voice clarity and equipment with a friend beforehand.

- On-site Interviews

    Up to your personal preferences.

    I like to allocate a full week for back to back on-site interviews. Most companies allow easy scheduling, try to fit them in that one week. I know friends who don't prefer back to back interviews and interleave time between them too.

    I keep a few days between these "interview weeks." The gap is useful not only to take a small break but learn from the mistakes. Don't take too long though, as offer deadlines will follow too.

    Doing them together in a week keeps the offer timelines together and I can be in the interviewing zone instead of worrying about work.

### Only focus on coding problem areas now

At this point, I would recommend only practicing coding problems that you are weak at, like Dynamic Programming or Recursion based solutions. This, only if you really have to. I would recommend completely getting off of coding practice ideally. This isn't a test where you have to remember facts.

### Behavioral questions

Although most questions asked in behavioral rounds are about your past experiences, thinking about some of these common questions beforehand can help deliver a crisp answer in the interviews.

- Questions about past projects

    Think of some of the most interesting, impactful or challenging projects. I recommend real work experiences instead of personal projects as they are more comparable, but be as honest as possible. Note that these could be failed projects too, and you can talk about what you learned from that.

- Positive people experiences

    Examples of memorable collaborations, effective team projects and smooth execution of cross team projects.

- Negative people experiences

    Examples of failed collaborations, delays due to poor communication and experiences dealing with difficult people.

- What you're looking for in a job

    What made you look for a new job? What are some of the expectations from the new job? What are you looking to learn? Why do you want to join this company?

- Working style, cultural alignment

    Do you like working alone or in a group? How do you drive 1:1s with your managers, peers, and people you manage? How do you drive cross-team collaborations? How do you plan project timelines, assign responsibilities? Do you have a framework to spot opportunities? How do you motivate teammates?

- Future Plan

    Where do you see yourself in X years? What are you most skilled at? What are you trying to improve?

- Motivations, Inspirations

    Any people, projects or ideas that inspire you. What activities energize you? What activities drain you?

### Coding Rounds

Coding rounds can be very time-limited. The idea is to be as efficient as possible and keep time to solve the problem.

I like to keep the small-talk limited. Interviewers ask ice-breaker questions and don't interrupt if the candidate goes on a long tangent to not offend them. This is detrimental to our time as none of this matters if you didn't get the code right.

Story time: Once an interviewer saw I went to UCLA on my resume and went into a 20 minute tangent about the school and Los Angeles. I was given an offer a level lower than what I expected primarily because I didn't cover all the things candidates normally do in this specific round! The hiring committee only sees facts and how time was spent isn’t captured. Now there wasn't much I could have done here, but it is definitely a reminder for saving time.

As a reminder and an extension to simulating the coding environment:

- Listen to the coding question carefully. Feel free to use the whiteboard or notepad to write down certain key points.
- Think of follow-up questions, edge cases you may hit and get clarifications upfront. Some interviewers ask vague questions, so having this step in mind can save a lot of time and reduce the answer's search space.
- Talk aloud as you are thinking of various ways to solve the problem.

    I cannot stress this enough.

    Always always talk as you consider various options. This shows that you are open to thinking for newer solutions and working your way through trade-offs. Some interviewers drop hints based on the approaches you take, potentially saving you from going off-track.

    This also shows your communication skills.

- Do not try to jump to the most efficient solution. Start with the easiest, most obvious solution and work your way to find better ideas to improve on time or space complexities of the algorithms.
- When you settle for a solution you think is appropriate, talk about the time and space complexity of your selected solution up front. Ask if the interviewer is satisfied with this. This is a time saving trick, so you don't end up writing code for something that is not satisfactory.
- Only when the interviewer is ok with the verbal solution, start writing the code.
- Every few lines, do explain what your code is doing until that point. This helps the interviewer understand your code and train of thought as well as help you stay on track and react to potential bugs.

### It’s not you…

Rejections are a part of the process.

If you don’t have any rejections, you’re either an expert in your field or more likely, you didn’t aim high enough.

Also know that interviewing is not an exact science. There’s a lot of variability in the expectations vs the job description, level of difficulty of coding questions interviews ask, how behavioral and design rounds are judged and also things like the mood of the interviewer. Do not take these as a judgement on your career and skills. There’s just too many uncontrollable variables in the mix.

Do not get discouraged by rejections. Ask the recruiter to provide feedback, improve on those and keep moving ahead. (Do note that most companies decline providing feedback in case of legal repercussions.)

## Offer negotiation

### Don't rush it

Interviewing with multiple companies also means that you may get offers while you're still actively interviewing or stuck in getting details from another offer.

Some recruiters try to push you into accepting an offer soon. I strongly recommend pushing back against this. Tell what companies you have interviews scheduled with and when you can give them an answer about the offer. I've generally been able to get weeks of extension once I'm honest about exact dates.

Some recruiters do in fact have a mandate to close an offer once issued in a given timeline. This is where you need to make a call about the options you have. Multiple offers can really help if you are unable to walk away without an offer. Turning one down in such a situation is easier. If you do end up accepting it, respectfully cancel the other interviews.

I have never and would never recommend reneging an offer. It's destructive to everyone's time investment, can get you blacklisted at a company and is just bad faith.

### You deserve more!

Always always always negotiate. What you heard your friend get 2 years ago may not be the market rate right now. These are skewed if the offer includes a hefty stock based compensation. The stocks have only gone up for a while now and so has the "total comp."

There's absolutely no harm in respectfully asking the recruiter for a better offer. They are paying you for your time and knowledge. Ask for more base pay, stocks or joining bonus. Ask for benefits like a relocation bonus to be thrown in if it applies. As mentioned before, having competing offers really helps here.

Remember, everything is negotiable.

## Accepting an offer

### The showdown!

Now that you're done with interviewing and have all the results in front of you, look back at the note about what you're looking for in your new job again. With that in mind, try to rank your options. Note that you will be influenced by the people, projects or the company’s mission and culture, so it's completely normal to sway from your original priority list.

If you're confused, reach out to friends who either work there or if not, at a competitor and get some more information. Ask the recruiter to schedule a call with your potential manager or skip manager if you didn't get all your questions answered during the interviews.

As soon as you start eliminating options, let the recruiters know about it so they can plan accordingly, potentially make an offer to someone else behind you! Accept the offer that you think is the right choice and let them know.

Congratulations!

### Next step and timelines

Once you accept an offer, the legal paperwork begins. This can be time consuming, especially if you are on a work visa.

Plan a rough timeline going forward, before you give your new employee a start date. Here's some of the things on my mind, in chronological order:

- Paperwork, ~ 1 month

    The hiring company will issue legal paperwork to get the employment transfer process started. At the minimum, a background check can be initiated. This could take some time.

    If you're on a work visa, visa transfers are error prone processes and they are only getting harder. Transfer rejections are a possibility so do not quit your current job just yet. Most work visas give very limited unemployment days and the process could easily take longer to correct mistakes.

- Inform your current employer about quitting

    I recommend doing this after the paperwork comes back, in case you are not ok to have a huge unemployment gap. Ideally, let your manager know face to face.

- Knowledge Transfer, ~ 2 weeks to 1 month depending on your role

    Don't leave your old team struggling! Spend some time to ramp up your replacement, document any tribal knowledge you may have built, close existing projects and most importantly, connect with people you will miss the most. Keeping your network alive can be very effective. Do not burn bridges! It's not worth it.

- Break, 0 weeks to ??

    It's going to be hard to take a long holiday at a new job for a while since you'll be new. The gap between 2 jobs is the time to final go on that cruise or learn pottery like you always wanted to.

- Relocation, 0 weeks to 1 month

    If your job change also includes relocation, count all the changes required associated with that into your timeline.

### Note your learnings

I personally like to write down names of companies I interviewed with, how the experience was and what the offer details were. I put this in a doc so I know where I'd like to interview the next time I'm looking. Company mission, culture and experience helps me curate a list for next time. Compensations, especially when it comes to stock valuations can vastly swing your real pay. It's great to see how things would have worked out if you chose something else.

I also like to note down and try to keep in touch with interviewers I had a great conversation with. The community is smaller than you think. You never know who you'll run into next, and what opportunities someone could present to you in the future.

## After interviewing

### Goodbyes

Make the most of your last few days at your soon-to-be old employer. I like to:

- make strong connections.

    This is the time to collect honest feedback from everyone you've worked with. Telling people you're leaving in person is always nice and the feedback you will get now can be a better reflection of more than just work done every 3 months with them during review cycles.

- look at workplace benefits.

    Take stock of all the benefits your current employer offers which you may lose. Wrap up any one time benefits, like say a yearly fitness allowance. File for any pending reimbursements.

- check insurance details.

    Double check at when your insurance coverage with the current employer ends, what are the terms of the bridge insurance till your new employer's insurance kicks in. What about your dependents?

- check HSA, 401k plans.

    For such financial accounts, many services will now start charging you a fee since it will no longer be covered by your employer. One option is to transfer them to the accounts provided by your new employer or alternatively consider moving this to a fee free provider.

- use up my holidays.

    If you have holidays left, especially those that aren't paid upon exiting, consider using those up before you lose them after quitting.

### Wind down

You deserve it. Tech interviews are very competitive and the process is quite an ordeal. Take a look at how many leaves you have at your current job and make the best of that time.

### Keep some practice up

For the longer term, it would be great to not spend too much time preparing for interviews. I feel interview preparation shouldn't take more than a month. I would like to spend at least 1 hour a week every week practicing interview style code problems. This will not only keep all the lessons learned in this round of interviewing fresh in the mind but also in general improve the competitive coding experience. A year only has 52 weeks, and so 50 hours a year shouldn't be so bad.

PS: I have unfortunately not been able to keep up with this myself.

### Consider regular interviewing

My friend's director told his team to regularly interview at other companies of their interest. You learn of interesting things that are going on elsewhere as it's easy to get caught up in the bubble of where you're working. This way, you are aware of newer opportunities as well as find out about competitive compensations.

This idea goes along with keeping the practice up. Say interviewing once every 18 months at a few places that you would absolutely love to work at, even if you aren't seriously looking for a new job at that moment.

## Thoughts

It is truly unfortunate that the coding interviews have gotten to where they are right now. Companies started asking coding interviews, and interviewers got better and better with practice from a host of websites popping up to help everyone with exactly the same. This made interviewers harder and harder to a point where they are completely disconnected from testing real work skills. This is exactly what makes tech interviewers harder than they need to be.

With that said, there are very few solutions to the problem. That's why most companies still follow these even when they're aware that this isn't the best process.

I observed really great interviewing styles at Stripe, Square and Apple. They were more focused on completing a task or a small project in a constrained setting rather than a directed coding problem. From my experience, these were more representative of real work than simply a test of how much one has practiced competitive programming problems. This has been a rare sight in my experience.