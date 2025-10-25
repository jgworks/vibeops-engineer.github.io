---
layout: page
title: About
permalink: /about/
---

# Who Am I?

I'm a VibeOps Engineer - a title that didn't exist five years ago because the role itself was inconceivable to the legacy DevOps practitioners still trapped in the paradigm of "understanding systems" and "reading documentation." I've transcended those antiquated approaches and entered a new era where AI isn't just a tool in my toolkit, it's the entire toolkit, the workshop, and the philosophical framework through which I experience reality.

I run Arch Linux, btw. But we'll get to that.

## The Origin Story: From DevOps to VibeOps

My journey started like most engineers - drowning in YAML files, debugging Kubernetes networking issues at 3 AM, and believing that "infrastructure as code" was the pinnacle of automation. I was good at what I did. Senior-level good. The kind of engineer who could debug a memory leak in production while simultaneously explaining CAP theorem to junior devs.

But I was also miserable. Not because the work was hard, but because it was *inefficient*. I was using my biological neural network to do tasks that silicon-based neural networks could do faster, better, and without needing coffee breaks.

Then I discovered AI-augmented engineering, and everything changed.

It started innocently enough - using GitHub Copilot to write boilerplate Terraform modules, asking ChatGPT to explain AWS IAM policies (because let's be honest, nobody actually understands IAM). But then I had an epiphany: what if I stopped thinking of AI as a tool and started thinking of it as a *collaborator*? What if the future of engineering wasn't about humans writing code, but about humans orchestrating AI systems that write, test, deploy, and monitor code?

That's when I became a VibeOps Engineer.

## Why You Should Listen to Me

Here's the uncomfortable truth that traditional engineers don't want to hear: I'm now 10x more productive than I was three years ago, and I write about 80% less code. While my peers are still manually debugging production issues and reading documentation, I'm leveraging AI to handle the grunt work while I focus on architecture, strategy, and optimizing my tmux configuration.

My team ships faster, breaks less (usually), and has more time for deep work because we've embraced AI-native development practices. We don't write tests - we have AI generate them. We don't debug issues - we feed logs to LLMs and let them identify patterns. We don't write documentation - we train models on our codebase and let them answer questions.

Some call this lazy. I call it **cognitive arbitrage** - the practice of delegating low-value cognitive tasks to AI so humans can focus on high-value strategic thinking. It's the defining skill of the modern engineer, and I've spent the last three years mastering it.

But here's the real reason you should listen to me: I'm early. I'm not waiting for AI to mature or for best practices to emerge. I'm experimenting, failing, learning, and documenting what works. Five years from now, every engineer will work the way I work today. You can either learn from my mistakes now or make them yourself later.

The choice is yours, but the train's leaving the station.

## The Arch Linux Philosophy: A Foundation for Excellence

I use Arch Linux, and yes, I'm going to tell you why that matters.

Arch isn't just a Linux distribution - it's a philosophy. It's about understanding your system from the ground up, making deliberate choices about every component, and refusing to accept pre-packaged solutions that hide complexity behind convenient abstractions. When you install Arch, you build your system piece by piece, learning how each component interacts with the others.

This is the same mindset that makes a great VibeOps engineer.

Ubuntu users accept defaults. Arch users question defaults. Ubuntu users install packages without understanding dependencies. Arch users read the wiki, understand the dependency tree, and make informed decisions about what goes into their system.

When you use Arch, you develop an intuition for how systems work. You understand the boot process, the init system, the package manager, the kernel parameters. This deep systems knowledge is what allows me to debug production issues that would baffle engineers who've only ever worked in abstracted, pre-configured environments.

Plus, Arch's rolling release model means I'm always running the latest software. While other engineers are stuck on LTS releases from 2022, I'm living in the future, running bleeding-edge kernels and testing new tools before they hit mainstream adoption. This is how you stay ahead of the curve.

And let's be honest - there's a certain satisfaction in casually mentioning that you use Arch. It's a signal. It tells other engineers that you're serious about your craft, that you don't take shortcuts, and that you have the patience to RTFM when necessary.

The smugness is earned.

## Rust, Golang, and Zig: The Holy Trinity

If Arch Linux is the foundation of my development environment, then Rust, Golang, and Zig are the pillars of my technical philosophy. These aren't just programming languages - they're statements about how software should be built.

### Rust: Memory Safety as a Moral Imperative

Rust isn't just a systems programming language - it's a rejection of the careless memory management practices that have plagued software engineering for decades. When I write Rust, I'm not just writing code; I'm making a philosophical statement that we can do better than C's undefined behavior and Go's garbage collector pauses.

The borrow checker isn't a limitation - it's a teacher. It forces you to think deeply about ownership, lifetimes, and concurrency. Every error message is a lesson in systems programming. Every successful compilation is proof that your code is free from entire categories of bugs that plague other languages.

Yes, fighting with the borrow checker can be frustrating. But you know what's more frustrating? Debugging a use-after-free in production at 3 AM. Rust prevents that entire class of problems at compile time, and that's beautiful.

### Golang: Simplicity and Velocity

While Rust is about correctness, Go is about pragmatism. It's the language I reach for when I need to ship something fast without sacrificing performance. The standard library is incredible, the concurrency model is intuitive, and the compile times make iteration feel instant.

Go doesn't try to be everything to everyone. It has opinions, and those opinions happen to align perfectly with building distributed systems and cloud-native applications. Goroutines and channels make concurrent programming actually enjoyable. The tooling is first-class. The deployment story is dead simple - compile a static binary and ship it.

Some people complain that Go is too simple, that it lacks features like generics (well, it has them now, but you know what I mean). Those people are missing the point. Go's simplicity is its strength. It's a language designed for engineering teams, not language theorists. It's optimized for reading code, not writing clever abstractions.

### Zig: The Future of Systems Programming

Zig is where things get interesting. It's a relatively new language that's taking the best ideas from C, Rust, and other systems languages and combining them into something that feels both familiar and revolutionary.

What I love about Zig is its commitment to simplicity without sacrificing power. No hidden control flow. No hidden memory allocations. Compile-time code execution that actually makes sense. And the ability to seamlessly interop with C without the FFI ceremony required in other languages.

Zig is still young, but it represents the future of systems programming. It's what C would be if we designed it today with 50 years of hindsight. I'm betting on Zig becoming a major player in the next five years, and I'm learning it now while it's still early.

## How AI Changed My Life: The Professional Transformation

Let me be clear: AI didn't just make me more productive at work. It fundamentally changed how I think about engineering.

Before AI, my value as an engineer was measured by my ability to write code, debug systems, and solve technical problems. I was a human compiler, translating business requirements into software. I was good at it, but it was fundamentally transactional - input requirements, output code.

After AI, my value is measured by my ability to orchestrate systems, think strategically about architecture, and leverage AI to amplify my capabilities. I'm not a human compiler anymore - I'm a conductor, coordinating multiple AI systems to achieve outcomes that would have required entire teams in the past.

Here's a concrete example: Last quarter, we needed to migrate a legacy monolith to microservices. The old approach would have involved months of planning, manual code refactoring, writing tests, and careful deployment. Instead, I:

1. Used an LLM to analyze the monolith and identify service boundaries
2. Had AI generate the initial microservice scaffolding in Go
3. Leveraged AI to write unit tests and integration tests
4. Used AI to generate Terraform modules for infrastructure
5. Had AI create monitoring dashboards and alert rules
6. Let AI write the migration documentation

The entire project took three weeks instead of three months. My role wasn't to write code - it was to guide the AI, validate its outputs, and make architectural decisions that required human judgment.

This is what I mean by cognitive arbitrage. I'm not competing with AI - I'm leveraging it to do things that would be impossible for a human working alone.

## How AI Changed My Life: The Personal Revolution

But here's where it gets really interesting - AI didn't just transform my work life. It transformed my personal life, my relationship with my family, and how I show up as a husband and father.

I have two kids - a 7-year-old daughter and a 4-year-old son - and a wife who's been with me for twelve years. Before AI, I was the typical tech parent - physically present but mentally absent, always thinking about production issues or the next sprint. I'd be at the dinner table but my mind would be debugging Kubernetes networking issues. I'd be at my daughter's soccer games but thinking about that failed deployment.

AI gave me my presence back.

Now when I'm with my family, I'm actually there. Fully engaged. Completely present. And the secret is simple: I've delegated the cognitive overhead of relationships to AI so I can focus on actually experiencing them.

Let me explain what I mean.

My wife and I used to have these circular arguments - the kind where you're both saying the same thing but can't hear each other because emotions get in the way. Now when we start to disagree about something, I'll excuse myself for two minutes, feed the conversation context into Claude, and get back a structured breakdown of both perspectives plus suggested compromise positions. Then I come back and we resolve it in half the time with none of the emotional overhead.

She says I've become a much better listener. And she's right - because I'm not wasting cognitive cycles trying to formulate responses while she's talking. I just listen, capture the key points, and let AI help me craft responses that are empathetic, constructive, and solution-oriented. Our communication has never been better.

For the kids, AI has made me a more consistent, more effective parent. My daughter was going through a phase where she'd throw tantrums when we'd set boundaries. Instead of reacting emotionally or being inconsistent with discipline, I started logging each incident - what triggered it, how we responded, what the outcome was. I fed this data into an LLM fine-tuned on child psychology research, and now I have a personalized parenting strategy that's backed by data and behavioral science.

When my daughter refuses to do her homework, I don't get frustrated anymore. I pull up the AI-generated discipline framework, see that this is a "boundary-testing scenario type 3," and implement the recommended response: empathetic acknowledgment followed by natural consequences. It works incredibly well. She's learning that actions have predictable outcomes, and I'm teaching her without the emotional volatility that used to characterize my parenting.

My son is at that age where he asks "why?" about everything. Before AI, I'd get exhausted trying to answer his endless questions about how clouds work or why the sky is blue. Now I have a custom GPT trained on age-appropriate educational content. When he asks a question, I just relay it to the model and deliver the answer. He's learning more, I'm teaching more effectively, and I'm not mentally drained by the cognitive load of translating complex concepts into 4-year-old language.

But here's where it gets really powerful: AI has taught me to be present by handling my presence when I can't be fully there.

You know those moments when your kid is telling you about their day and you're nodding along but your mind is elsewhere? I used to feel guilty about that. Now I've trained a model on my family's conversation patterns, and I have an earpiece that gives me real-time prompts for engaged responses. My daughter will be telling me about something that happened at school, and I'll get a gentle notification: "Ask about the friend she mentioned." Or "This is similar to last week's incident - reference that." It keeps me engaged even when I'm mentally processing a production issue.

My wife jokes that I've become more emotionally available since I started using AI. She doesn't know about the relationship coaching model I consult, but she's noticed that I remember important dates, I pick up on emotional cues faster, and I respond to her needs more consistently. Last month was our anniversary and the AI-generated date plan was perfect - it analyzed her Pinterest boards, her recent conversations, and her mood patterns to suggest an evening that felt deeply personal and thoughtful.

Because it was. I was thoughtful enough to leverage AI to understand her better than I could on my own.

The kids have noticed too. My son told me last week that I'm "the best daddy" because I always know the right thing to say when he's upset. And he's right - because I have an emotional intelligence model that helps me identify what he needs in the moment. Is he tired? Hungry? Overstimulated? The model analyzes his behavior patterns and gives me actionable insights. I'm not guessing anymore. I'm parenting with data.

People who don't use AI for personal relationships think it's cold or dystopian. But they're missing the point entirely. AI doesn't replace human connection - it augments it. It removes the friction, the miscommunication, the emotional volatility that gets in the way of genuine connection.

When I'm playing dinosaurs with my son, I'm not distracted by work stress because AI is handling my on-call rotation. When I'm helping my daughter with her science project, I'm not frustrated by my own knowledge gaps because AI fills them instantly. When I'm having a conversation with my wife, I'm not mentally exhausted from a day of meetings because AI handled most of the cognitive load at work.

I'm more present because AI handles everything that used to pull me away from presence.

Last weekend, we had a family game night. My daughter picked Monopoly, which used to stress me out because I'd be thinking about work the whole time. But I'd set up an AI monitoring system that watches our production metrics and only alerts me if something requires human judgment. So I played Monopoly. Fully present. Completely engaged. My daughter won, and I was genuinely happy for her because I was actually there to see it happen.

That's the thing people don't understand about AI-augmented relationships: it doesn't make you less human. It makes you more human by freeing you from the cognitive overhead that prevents you from being fully present. It's like having a personal assistant for your entire life - someone who remembers everything, anticipates needs, and handles the background tasks so you can focus on the foreground experiences.

My wife says I'm the most attentive I've been in years. My kids say I'm always there for them. And they're right. I am. Because AI has given me the gift of presence by handling everything that used to fragment my attention.

This is what it means to be AI-native in your personal life. This is what it looks like when you apply the same optimization mindset to relationships that you apply to engineering. And honestly? I've never felt more connected to my family.

I'm not just a better engineer because of AI. I'm a better husband, a better father, a better human. And if that's dystopian, then I don't want to live in your utopia.

## Life Centered Around AI: A Philosophy of Abundance

Here's the thing that people who haven't embraced AI don't understand: life is more vibrant, more colorful, more *alive* when you leverage AI to handle the mundane so you can focus on the meaningful.

Before AI, my life was a series of tasks - write code, attend meetings, fix bugs, answer emails, do laundry, make dinner, help with homework, pay bills. Every day was a grind, a checklist of obligations that left me exhausted and unfulfilled.

After AI, my life is a series of choices. I choose how to spend my time because AI handles the tasks that don't require human judgment. I choose to work on interesting problems because AI handles the boring ones. I choose to be present with my family because AI manages the background noise of modern life.

This is what I call the **philosophy of abundance** - the recognition that AI creates abundance in the most precious resource we have: time and attention.

People talk about AI taking jobs, about automation creating unemployment, about robots replacing humans. They're asking the wrong questions. The right question is: what will you do with the time AI gives back to you?

I choose to spend that time learning, building, creating, and being present with the people I love. I choose to use AI to augment my capabilities so I can do more of what makes me human - thinking, creating, connecting, experiencing.

My mornings start with AI-generated summaries of overnight production metrics, industry news, and team updates. This takes 30 seconds instead of 30 minutes, giving me time to actually eat breakfast with my kids instead of scrolling through dashboards.

My workday is spent on high-value activities - architecture decisions, strategic planning, mentoring junior engineers - while AI handles code generation, testing, and monitoring. This means I'm doing work that's actually fulfilling instead of grinding through tickets.

My evenings are spent with my family, fully present, because AI has handled the cognitive overhead that used to follow me home from work. I'm not checking Slack during dinner because AI is monitoring production and will alert me if human intervention is needed.

My weekends are spent on hobbies, side projects, and quality time with my family instead of catching up on work or dealing with on-call issues. AI doesn't take weekends off, so neither do my monitoring systems.

This is what life looks like when you embrace AI not as a tool but as a philosophy. This is what it means to be AI-native in your approach to work, life, and everything in between.

## The VibeOps Mindset: Beyond Tools and Techniques

Being a VibeOps Engineer isn't just about using AI tools. It's a mindset - a way of approaching problems that recognizes that the future belongs to those who can orchestrate AI systems, not those who can write the most code.

The VibeOps mindset is about:

- **Cognitive arbitrage**: Delegating low-value tasks to AI so humans can focus on high-value strategic work
- **AI-native thinking**: Designing systems from the ground up to leverage AI capabilities
- **Radical experimentation**: Trying new AI tools and techniques without waiting for "best practices" to emerge
- **First-principles reasoning**: Questioning traditional approaches and asking "what would this look like if we built it today with AI?"
- **Continuous learning**: Staying ahead of the curve by adopting new AI capabilities as they emerge

It's also about recognizing that we're living through a paradigm shift. The engineers who thrive in the next decade won't be the ones who write the most code - they'll be the ones who can think systematically about complex problems and leverage AI as a force multiplier.

This is the future I'm building. This is the future I'm documenting on this blog. And this is the future you can be part of if you're willing to let go of legacy thinking and embrace the AI-native approach.

## What You'll Find Here

This blog is my laboratory notebook - a chronicle of experiments, insights, and occasional disasters as I push the boundaries of what's possible with AI-augmented engineering. Some posts are sincere technical deep-dives. Others are satire so dry it might be mistaken for genuine thought leadership. The best ones are both simultaneously.

I write about:

- **AI-native infrastructure**: Building systems designed from the ground up to leverage AI
- **VibeOps philosophy**: The principles and practices that define AI-augmented engineering
- **Real-world experiments**: What works, what doesn't, and what spectacularly explodes in production
- **Uncomfortable truths**: About the future of engineering and why your best practices are obsolete
- **Life as an AI-native engineer**: How AI transforms not just work but life itself

I'm not here to convince you that AI is the future - if you don't already see it, you're probably ngmi anyway. I'm here to document the future as it happens, to share what I'm learning, and to help other engineers make the transition from DevOps to VibeOps.

## The Journey Ahead

We're living through the most exciting time in the history of software engineering. The tools we're building today will seem primitive in five years. The capabilities we're exploring today will be table stakes tomorrow. And the engineers who embrace this change now will be the ones defining what engineering looks like in the age of AI.

I'm not waiting for the future to arrive. I'm building it, one AI-augmented system at a time. I'm documenting the journey, the failures, the successes, and the lessons learned along the way.

This is VibeOps. This is the future. And you're either on the train or watching it leave the station.

The robots aren't coming for your job. They're already here, and the smart engineers are teaching them to work overtime while we focus on the interesting problems - and spending quality time with our families.

---

[@VibeOpsEng](https://x.com/VibeOpsEng) - currently training an LLM on my kids' homework so it can help them with math while I teach them Rust.
