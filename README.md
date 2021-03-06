# How to get Good Answers on the Slack Code Institute Channels

## Introduction

The web is great for finding out information about a myriad of subjects.   People like sharing the knowledge and skills they've acquired.   And because the web was created by software developers and will forever be maintained and developed by software developers, and also because unlike say, tree surgery or ballet dancing, information about the art can easily be communicated digitally, it follows that of any subject you might want to learn about, software development has pretty much the most information available.   And this is also part of the culture of open source.   There are so many developers out there who want to help you!


## Answers

So how do you get a good answer to your problem?   Well, getting a good answer depends on asking a good question!   Saying "Why doesn't my code work?" and accompanying it with a blurry screenshot of part of a code file is not a good question!   All right, so what is a good question?


## Questions

A good question starts with describing to yourself exactly what the problem is.   You are expecting something, but something else happens.   Maybe your page does't look as you expected; maybe you get an error message in the console; maybe you're having difficulties making your code do what you want it to.   But cut it down.   In your head, get rid of things which aren't relevant to the problem so you can see the essence of it clearly.


## Context

First look at the context the problem occurs in.   Can you change that?   If so, do, and see if it still occurs, for example try a different browser or clear your cache if it's a rendering issue.

Can you simplify the code that seems to be causing the problem?   I often do this by copying the whole folder I'm working in to a scratch folder, deleting the `.git` sub-directory, then paring the code down, cutting out sections of code that shouldn't have a bearing on the issue, then checking if things still work, if the problem still occurs.

If you get into a mess, `Ctrl+z` is your friend, and remember, you're just working in a scratch folder so no stress! 
Get rid of code that seems irrelevant to the problem bit by bit till you have crystallised what the problem is and either solved it or can show someone the code and explain the problem in a sentence.


## Your Potential Helpers

It's important to think of the developers who are browsing the channels.   The first questions they'll answer will be those where it's clear from a sentence or two and a minimal chunk of code exactly what the issue is.   People want to help, but they'll help first where it's easiest to help and where the OP (jargon for "original poster") has shown some initiative in formulating the problem clearly and carefully.


## Guidelines for Getting Good Answers Fast

- First, try to solve the problem yourself.   It's good to get into the habit of distilling your issue into a few keywords or a short quoted phrase that you can put into a search engines to find answers in forums like Stack Overflow, and tutorials to help you solve it yourself.   If you get an error message, copy and paste it, quoted with keywords specifying the context.   If you only find other similar questions, without satisfactory answers, try putting the word "solved" in your search query.  If you can fix it yourself using the plethora of resources available, you'll learn that lesson more deeply.

- Some people recommend "Rubber Duck Debugging".   This means explaining your code, line by line, to a rubber duck on your desk!   Other objects may also serve this purpose, of course, but the point is, firstly, that if you can describe clearly what your code is doing, then any disconnect between what it's supposed to do and what it actually does often becomes apparent, but also that you're forcing yourself to think about the code logically.

- Choose the best channel for your issue.   Many of the channels are named after the course modules.   If you need help with something specifically related to the module you're on, the name will guide you.   But if you're working on the data-centric module, for instance, but your problem is purely about how an element is rendered, it might be more appropriate to post in #css-fundamentals.   Another example:  if it's to do with generating HTML from a Jinja template, don't post in #html-fundamentals, as the students there won't have covered Jinja, and your code may confuse them!   Instead, post in the channel appropriate to the module where Jinja was introduced, i.e. #practical-python.

- State the issue simply.   Say what you are trying to do, say what the expected behaviour is, and say what the actual behaviour is.   Say what context the problem occurs in.   Include a code block with minimal code to reproduce the problem.

- If appropriate, include a link to your Cloud 9 workspace or Github repository.   If your code is deployed (to Github Pages or Heroku for instance) post a link to the deployed app.

- If it's a browser issue, say what browsers (and versions) and devices you've tested it on.

- If it's something that has software dependencies such as a Python/Heroku app, it might be relevant to specify package versions.

- Don't attach screenshots of code.   Screenshots may sometimes be useful, but never for code! Code, and console traffic, should be in code blocks, which are delimited at both ends by three backticks (the character at the top left of UK keyboards, just below the Escape key).   Just type three backticks, paste your code block, then type three more backticks.   It'll appear thus:

```
<!doctype html>
<html>

<head>
    <meta charset="utf-8">
    <meta name="description" content="Used merely as an example of a code block">
    <meta name="author" content="Example">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">    
    <title>Example Code Block</title>
</head>

<body>
    <h1>Example of a Code Block delimited by 3 backticks</h1>
</body>
</html>
```
To delimit short code keywords or phrases in a sentence, use a single backtick at each end.   It'll look like this: `<a href="#">Foo</a>`. Note that these two constructs are the same in Markdown, which you must use to create your README.md file for each project.

- Don't include extraneous information that's not relevant to the issue.   Distil it down!

- Check your spelling and case, particularly of variable names, keywords etc..   Paste the exact code you've tested.   If English isn't your native language, though, don't worry too much about non-code spelling, as long as your meaning is clear.


## Finally...

You should definitely read the [Code Institute Slack Community Guidelines](https://codeinstitute.net/code-conduct-slack-community/), which has great advice about using the channels and asking for help, and also the [Code Institute troubleshooting tips page](https://code-institute-org.github.io/TroubleshootingTips/).   For examples of good questions, look on [Stack Overflow](https://stackoverflow.com/) for questions with hundreds of upvotes.

It's definitely worth creating a (free) account on Stack Overflow, as you can then ask and anser questions and start to build a reputation.   If you select the [Ask Question](https://stackoverflow.com/questions/ask) link, you will be asked to select tags - start typing, and choose one or two that are directly relevant - and then to enter your question title.   As you type, you'll see a filtered list of similar questions.   So often I find that one of these provides the required help, so I never actually need to ask my question.

If you eventually find a solution to a question you have posed, about which people have made suggestions and tried to help, then whether or not these ideas have helped you, please consider posting back in the channel, giving your solution.   This can help others.

Also, when people help you, remember that acknowledgement costs little and increases the amount of joy in the world!   And look for opportunities to help other students.   It's hard to over-emphasise how much helping others with their code issues will help you yourself, too.   Pay it forward!