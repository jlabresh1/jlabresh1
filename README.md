# Jeremiah LaBresh

**Staff Software Engineer · PHP/Laravel, Vue, MySQL · Hands-on technical leadership · AI-assisted development**

Urbandale, Iowa (Remote) · [LinkedIn](https://www.linkedin.com/in/jeremiah-labresh/)

## Summary

I've been building for the web for 25+ years, the last 13 on ClearanceJobs at DHI Group, working mostly in PHP/Laravel, Vue, and MySQL. I've stayed hands-on by choice. I tried management briefly, but I like writing code and helping other developers grow, mostly by pairing with them. Recent work includes moving our public job board to server-side rendering, building on-demand ephemeral environments, an AI-assisted development lifecycle with Kiro, and improving how we ingest 50,000+ jobs from outside feeds.

## Skills

- **Languages:** PHP, TypeScript, JavaScript, SQL, HTML, CSS
- **Frameworks:** Laravel (Eloquent), Vue 3, Vike, Pinia, Vite, Element Plus
- **APIs:** REST API design and versioning, queues and events
- **Data and infrastructure:** MySQL, query optimization, dbt, Terraform, Docker, CI/CD, Git
- **Testing:** Cypress, Vitest
- **AI tools:** Kiro, Model Context Protocol (MCP)

## Experience

### DHI Group, Inc. (ClearanceJobs) — Urbandale, Iowa / Remote

ClearanceJobs is a job marketplace for people with security clearances and the companies hiring them. Over 13 years I've worked across the frontend, the API, and infrastructure in about 10 repositories, with more than 7,600 commits.

**Staff Software Engineer** · Jul 2021 – Present

- Led the move of our public job board to server-side rendering, from a vite-plugin-ssr proof of concept to a production Vike migration. The hard parts were hydration bugs, CSP nonces, and cookies and CSRF on the server.
- Designed our team's development lifecycle, from story creation through PR review, QA, and release, as guides and automation everyone follows.
- Built on-demand ephemeral environments that spin up for each story branch. Engineering, QA, and product each get an isolated environment to check work before merge, so nobody is stuck waiting on a shared staging server.
- Built an AI-assisted SDLC on top of that process, using Kiro workflows, steering docs, and MCP integrations for feature planning, story creation, code review, and release notes.
- Working with AWS on a blog post about our AI-assisted SDLC and what it has done for our team.
- Improving our job ingestion process, which pulls 50,000+ jobs from outside job feeds into the system through automated runs twice a day. Working with the jobs team on batch ingestion that classifies each listing by clearance level, location, remote status, industry, and job type.
- Built a UI where customer service reps use AI to add, update, and troubleshoot the job collections they own. Some reps manage up to 500 customer accounts.
- Led the discussions and helped with the integration of our own feature flag system. It's simpler than a third-party tool, but it lets us release code and have product turn features on for customers from an admin page.
- Built a shared design system (tokens, components, and guidelines) and moved the app over to it.
- Moved the frontend to Vue 3, Vite, TypeScript, and Pinia, and pushed for better test coverage with Cypress and Vitest.
- Mentor developers, mostly by pairing with them. Several have gone from frontend engineer to staff engineer.
- Have interviewed engineering candidates for years. I check first that they know what the role needs, then pair with them to see how they'd work with the team.

**Lead Software Engineer** · Jul 2018 – Jul 2021

- Led the frontend group that built our Vue.js single-page app, and set the process and coding standards the team worked from.
- Led the team through site redesigns and helped make the case for the design updates to leadership.
- Attended weekly leadership training and mentored developers on the team.

**Senior Software Engineer** · Jul 2013 – Jul 2018

- Helped build the page-view and campaign system that let ClearanceJobs start selling pay-per-view job listings. It tied applications and job views together so employers could see reports down to the hour.
- Built the ETL process that cached those reports. To keep reporting live, we calculated each chunk of data into a working table while the main table kept serving, then moved the results over when the run finished, with careful cron timing while the system was still fragile.
- Ran several large MySQL updates, optimized slow queries, and taught developers how to write efficient queries, including with Laravel's Eloquent ORM.
- Helped bring Laravel into our stack in 2013 and started our move to Vue.js on internal projects in 2016.
- Led the team that built out the ClearanceJobs.com front end in 2015, managing tasks, training developers, and presenting concepts to the product team. We launched on time.
- Built a VoIP calling feature for the site with Twilio, Pusher, and Vue.js.
- Designed and built an admin interface for customer service, and served as technical project manager across a third-party team, our client-side team, and our API team.

### Earlier experience

- **Systems Engineer**, Meredith Corporation · Jan 2007 – Jul 2013 (contract until Jul 2007)
- **Web Developer**, Demonstrated Performance Inc. · Oct 2006 – Jan 2007
- **Web Consultant (contract)**, Intel Corporation · 2006
- **Lead Interactive Developer**, Anderson Solone Inc. · 2000 – 2004
- **Web Developer (independent)**, LaBresh Media · 1999 – 2012

## Education

- Kaplan College Online — Information Technology

## Links

- LinkedIn: https://www.linkedin.com/in/jeremiah-labresh/
- Resume (DOCX / PDF): [`resume/`](resume/)
