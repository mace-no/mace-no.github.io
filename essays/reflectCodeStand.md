---
layout: essay
type: essay
title: "What's lint?"
# All dates must be YYYY-MM-DD format!
date: 2026-09-24
published: true
labels:
  - ESLint
  - Coding Standards
---

<img width=200px class="rounded float-start pe-4" src="https://dbaeumer.gallerycdn.vsassets.io/extensions/dbaeumer/vscode-eslint/3.0.34/1784203161508/Microsoft.VisualStudio.Services.Icons.Default">

## Coding Standards

Coding standards are the rules you must follow when writing code. It includes things like naming, indentation, error handling, and other coding practices. Following coding standards makes it easier for others to read and edit your programs. It also allows you to build good habits with that language. This is important as you begin working with others as a team.

ESLint is a tool that applies those rules to your JavaScript and TypeScript code. It will flag potential problems and can even suggest a fix. For examples, it can flag an unused variable and suggest using the const keyword when a variable isn't updated later on.

# My experience

Using ESLint and following Coding standards can definitely help you become more proficient in a language, as you learn what is generally considered right and wrong. However, I slightly disagree that it can help you learn a programming language as it oftens tells you what to do. When I was doing E25: Fix Bad TypeScript, I simply fixed what the errors did and had no idea what the actual code was doing. For example, I added spaces where it told me to, changed == to ===, and used dot notation instead of bracket notation. For someone who is still learning, they wouldn't understand what the difference between == and === is, or the different applications for dot/bracket notation.

For me, personally ESLint leans more towards being a nuisance than it is helpful. As it is unforgiving for even the smallest standards. It can be a little annoying when my code lights up red for not having a newline at the end, having too many extra lines, or having the wrong number of indentations. As these are simply styling and shouldn't affect whether or not the code runs. 