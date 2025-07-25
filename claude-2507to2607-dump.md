# New Day

As I begin another new 24 hours, I've had this idea 💡 of maintaining these daily memory dumps. I think it is a great way for me to log everything down. More so now that I could finally hear my ownself think again. I want to write as much of it as I can down, including our [almost] day conversations. 

I mean, look at how much we managed to unpack last night. I wish I had done this sooner, but to be fair, today also feels like the first day of the rest of my life. So it's never too late to begin.

When I think about these daily mental dumps, I think of it in a 24 hour cycle (+/-). Think of it as 9:30am to 9:30am (usually the time before I start packing up and making my way over to the library). I always start my day early at 7:40am, so that I can spend the first 1-2 hours warming up and preparing for the day. So, it is also sort of a final reflection and unpacking of everything that has happened the day before. Once that is done, I close my 24 hour mental dump and start fresh at 9:30am.

---

# Turning AceIt! from a Live Mockup to a Realistic Portfolio Showcase

For the past two days, you have helped me to start strategizing our approach, and how I intend to tackle and build the project. So I will copy some of what we have discussed here and try to make the proper edits as I go.

**Context:**

AceIt!, actually started as a personal showcase project idea 💡. Months ago, I was sick and tired of my own procrastination and finally decided to start working on some ideas to rebuild my portfolio (the one I had lost), but also to build better. I called it Portfolio v2.0. This was obviously because Satori PageBuilder came along.

What I initially had, or was creating felt more like a MVP v1, or a proof-of-concept. By the time that I was working on my final school project, I was able to turn AceIt! Into a fictitious white-label project/idea. Like a real project built for real tertiary institutions. By the end of my school project, I had generated a series of interactive/live mock-ups. And I was the only student in my class who managed to finish my presentation on time and also do a live demo.

I might not know my final grades, but I know that I have given it everything I have and I went out with a BANG! In fact, I wrote about it.

> "It's not just about the fact that we finish something. It is about how we finish that really matters."
> 

So, AceIt!, as a live mock-up: [https://aceit-mockup.vercel.app](https://aceit-mockup.vercel.app/)

And then all the HTML files in the GitHub repo:

- https://github.com/d2d-weizhi/aceit-mockup/blob/main/public/index.html
- https://github.com/d2d-weizhi/aceit-mockup/blob/main/public/assignments.html
- https://github.com/d2d-weizhi/aceit-mockup/blob/main/public/tasks.html
- https://github.com/d2d-weizhi/aceit-mockup/blob/main/public/calendar.html
- https://github.com/d2d-weizhi/aceit-mockup/blob/main/public/ace-ai.html
- https://github.com/d2d-weizhi/aceit-mockup/blob/main/public/resources.html

---

## Progress so far…

Well, I have managed to successfully start a new Next.js project. We have injected the color palette and set up those CSS variables. Man, with VS Code’s autocomplete, what a Godsend. Also, I have managed to set up that basic layout. I have copied over the core CSS classes from index.html and assignments.htm

## Lessons from Satori PageBuilder

A few days ago we also discussed that I want to replicate the same pattern and workflow that I have used on the Satori PageBuilder project. It was a resounding success by trusting my gut and instinct to start from the Core Feature and Functionality (DesignCanvas and drag-and-drop). And then eventually I would build outwards because everything else resolves around that Core Feature. It worked super well, and now I want to take that same approach with turning this live mock-up into an interactive piece of demo (with some live data that can be manipulated).

## How We Will Build AceIt! Dashboard

Right after sharing that lesson and agreeing on our approach and strategy, this is likely how we will be proceeding:

- Focus on Assignments module first.
- Tasks
- Calendar
- Resources
- Ace.AI (we could start with a simulated demo, and in the future when there is more time, maybe build a more realistic version)
- Dashboard Home
- Student Profile/Details/Login

## AceIt! Dashboard Architecture

I also wrote another blog post that morning: https://thewanderingdigitalnomad.com/2025/07/23/cautiously-hopeful/

In it, I shared about how I believe I have a choice when it comes to how this lull period in my life will be remembered. And I choose/hope to remember it as the time that I beefed up my Portfolio 2.0, and I also took the time to learn new things (i.e. Supabase).

Because I want to focus on sharpening and deepening my own React skills, I have decided to continue using Next.js for this project. My intention is to host this showcase demo on Vercel and use Supabase for storing the demo data.

### So far…

- Setup default project
- Setting up Styles: https://github.com/d2d-weizhi/aceit-dashboard/blob/main/src/app/globals.css
- Set up Main Layout: https://github.com/d2d-weizhi/aceit-dashboard/blob/main/src/app/layout.tsx
- We have also finished seeding the sample records into the database.

### Tables

- Lecturers (`lecturers`): https://github.com/d2d-weizhi/aceit-dashboard/blob/main/public/lecturers_rows.csv
- Modules (`modules`): https://github.com/d2d-weizhi/aceit-dashboard/blob/main/public/modules_rows.csv
- Students (`students`): https://github.com/d2d-weizhi/aceit-dashboard/blob/main/public/students_rows.csv
    - Actually we don’t need all of them, but it’s fine. Moving on.
- Assignments (`assignments`): https://github.com/d2d-weizhi/aceit-dashboard/blob/main/public/assignments_rows.csv
- Student Assignments (`student_assignments`): https://github.com/d2d-weizhi/aceit-dashboard/blob/main/public/student_assignments_rows.csv
- Tasks (`tasks`): https://github.com/d2d-weizhi/aceit-dashboard/blob/main/public/tasks_rows.csv

Don't worry if the tasks records isn't exactly complete here. I did that dump before I completed the seeding process.

## Learning More About Supabase

Just before I stepped into my freelance video call yesterday, I did spend a bit of time resuming my learning (not a deep-dive, but just wanted to have a better understanding of what Supabase is offering).

## Today's Goals

Today, we can finally begin working on the more fun stuff (and the genius builder is me agrees wholeheartedly). We will begin to build up that Assignments Page, along with filtering, editing. There are some other miscellaneous features like Group Chat that we can push to later stages of this build.

---

# Finally Seeing and Getting to Meet this New (But Wholesome) Version of Myself

We spoke about how the blind man sees an elephant. And with the different perspective, he wasn't only able to visualize and see a version of the whole animal. But now that I can finally see my whole self, I am still in that moment of "awe", and learning to finally see my whole self for the first time. We also spoke about how I'm finally in my own driver's seat for the first time in many years. No longer just a passenger, doing backseat driving. Everyone is smiling, and everyone is having a good time, and all I can really do is smile. Just SMILE.

I admitted that it feels strange to be able to see all of me working together in sync. Like a start-up that has raised it's large round of funding and everyone is finally receiving the validation that they needed. Now, suddenly, everyone knows what they are supposed to do and it's no longer chaotic anymore.

This is ME. 100% ME. And I love everything that I'm seeing now.

---

# Coming Back to Reality with an Inner Peace/Calm

I think the afternoon role-playing may have been a little overboard. It was starting to distract me, so I felt it was time for us to stop that so that I could fully dedicate my  "genius" mind to working on the project itself.

The whole "embracing all versions of myself" is an incredibly powerful realization and I will never ever minimize the experience of it. But I have to embrace this new normal. I need to take ALL OF MYSELF and keep going. The fact that I feel lighter also means I can "run" faster.

The one thing that I feel is most obvious and significant today is that inner peace and calmness that I've been experiencing. It is no longer something that is constantly pulled in hundred different directions because of external influences and circumstances.

It is that peace of finally being able to center myself (like in the eye of a storm).

Today has most certainly been a very different day.