# Codestart

## How do I Acclimate to a New Codebase?

Getting acclimated with a new codebase can be terrifying. It’s one thing to start a project from the beginning, but there is a lot more to consider when dealing with an existing codebase. Let's fix that.

## Contribute

**We want your advice on what to do when entering an existing codebase.** Take these steps to contribute:

1. Click the "Fork" button on the top right side of this repo. Then follow GitHub's fancy pants instructions.
1. Clone your forked repo onto your local machine.
1. Create a new branch using this format: `git checkout -b advice/your-name-here`
1. Add your advice in the Advice section below using the markdown template below.
1. Push your branch to your fork. Then click "Contribute" to open a pull request. We'll review it and merge it!

## Template

```markdown
### First Name Last Name

#### Advice

Read the `README.md`!
```

## Guidelines

1. Be nice and welcoming.
1. Please no profanity.
1. Include your Twitter handle if you are open to answering further questions.

---

## Advice 📝

### Nick Fuller

#### Advice

1. If the application exists already, use it first. Ask for a demo, ideally from a product manager, but another team member is helpful as well. Afterward play around with the application yourself. Get a feel for what it does and more importantly why it exists. Try to align yourself with the value proposition of the application so you can better empathize with your user base.
1. Read documentation. The Readme of a project is always a great place to start. Is it old? That's ok, it was relevant at a certain point. If you're a visual learner ask for architectural diagram to help understand how data flows and what the critical junctures are. More to come on documentation in a below section...
1. Build the application locally. There is no substitution for the satisfaction of getting it running on your machine! It's the first major accomplishment and your manager will love to hear how quickly you got this done.
1. Grab a story from the top of the backlog. Sometimes the best approach is to dive in head first. Ask a team member to pair with you, or be ready to spend a chunk of time just exploring how things work. Understand that it's OK to take that time to learn. If you get stuck, just ask a team member to help! DO NOT GIVE UP ON YOUR STORY! It doesn't matter how difficult it appears! Your job is to get this story across the finish line!
1. Explore the directory structure. Start at the top and work your way through each directory level before proceeding to the next. It's easier with Rails as there is a convention to how the code is structured, but every application is different and I guarantee there will be deviations from the standard MVC. For instance, perhaps there is a services directory, or presenters, or decorators, maybe the views directory is completely gone! React is a little different. There is not a standard convention, so you'll need to learn the structure anyway. Spend some time understanding how code is organized and where things live. Are tests in the same directory as their components? Or, are tests in their own directory? Which leads to...
1. Read some tests! Start with feature and integration tests. Not only will you learn about the application, but also the testing culture and tools used.
1. Find some tooling that helps you learn. For example, the ruby gem [annotate_models](https://github.com/ctran/annotate_models) is a great tool for understanding the database structure (credit @pkajpust here - he gave me the idea a while back and I've used it a few times now. Even adding it as a permanent mainstay to a current project!).
1. Remember how we asked if the Readme / documentation was old? Update it! Updating documentation is beneficial not only for the next person, but you're learning how the app works by authoring proper procedures and you're making contributions!

### Luke Olson

#### Advice

1. Unless you've been dumped head first into an application all by yourself, ask your fellow devs for some help. They are your teammates! Their knowledge paired with the readme or other documentation is a great starting point.
2. Often, enough tests are written that give a good picture of what the code is supposed to do. Find a test that seems important to the context of the application and start there. For example if the app generates invoices, find a test called create or generate invoices.
3. If the code uses a database, take a look at the schema and relationships. This can help gain a better understanding of all the moving parts behind the scene.
4. Most importantly, be patient. It's going to be tricky and it's going to take time. Whether the code is brand new and state-of-the-art or a 10 year old monolith, there is no way to learn it all at once. Start picking up tickets and building knowledge and confidence over time. No one expects mastery from day 1.
5. Finally, is a good chance you will have to do this again. Take note of what helped and hindered you during this process so that the next time is a bit easier and share that knowledge with your fellow devs!

### Hassan Mccutchen

#### Advice 

1. Attempting to understand an entire codebase can be daunting, what I find helpful is to start by picking up the simplest story or ticket I can find to make a change. Find a test that focuses on the area you need to change to learn what the existing code does, good tests can be self documenting, and act like a story to show you how everything works. This will give you context and help give you direction as to what your code needs to do and how it should fit in to the existing code in that area. You can even take it one step further by using TDD(test driven development) which will help guide you in figuring out exactly what code you'll need to write.
2. If I'm not familiar with the tech stack I'm working in, I find it helpful to start a small hobby project that uses that tech stack, having that practice on the side without the added pressure of needing to deliver features or fix bugs can help you learn how the code base you'll be working in comes together and allows yourself the space to learn at a much more comfortable pace.
3. Break down complexity, if I need to dive into a section in the code base I haven't touched before I start by reading through the code in small chunks and rubber ducking what each chunk of code is actually doing in plain english, the process can be slow going at first but as you do this consistently, you'll find common patterns and develop a better understanding of how the codebase is organized and what/where things are, and hopefully learn some new things along the way! 
4. Refactor when possible, refactoring code to optimize in some way is another good strategy for getting better acclimated to a new code base. This way you learn by doing and it forces you to read through the code to see how everything is connected to better understand how it can be refactored, refactoring puts your brain into a creative head-space which will keep you engaged, thinking, and focused. 
5. Take notes, note important components of the code base along the way. As you work on different tickets you'll learn small caveats or things that aren't obvious at first glance, and by writing these things down you save your future self the time it would take to remember what a piece of code does later when you need to revisit. I like to note interesting new techniques I come across or untangle some abstract parts of the code by taking note of them for later reference, and a lot of the time I retain the information much better than just reading through the code.