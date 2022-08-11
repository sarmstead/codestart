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
