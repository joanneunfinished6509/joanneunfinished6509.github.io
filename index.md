---
layout: "default"
title: "🍲 roommate-meal-planner - Plan Meals Around Allergies and Budget"
description: "Generate personalized 3-day meal plans offline with local Gemma AI for your roommate's allergies, diet, budget, and pantry."
---
# 🍲 roommate-meal-planner - Plan Meals Around Allergies and Budget

[![Download Meal Buddy](https://img.shields.io/badge/⬇_Download_Meal_Buddy-2E8B57?style=for-the-badge&logo=github&logoColor=white)](https://github.com/joanneunfinished6509/roommate-meal-planner)
[![Runs Offline](https://img.shields.io/badge/100%25_Offline-FF6B35?style=for-the-badge)](https://github.com/joanneunfinished6509/roommate-meal-planner)
[![No API Keys](https://img.shields.io/badge/No_API_Keys-6A5ACD?style=for-the-badge)](https://github.com/joanneunfinished6509/roommate-meal-planner)

Meal Buddy is a meal planner that thinks about one person at a time. Instead of dumping a generic list of recipes on you, it builds a week of food around what you are allergic to, what you can actually afford, and what you already have in your kitchen. It runs entirely on your own computer, powered by Gemma 3 through Ollama, so your ingredient list, your allergy notes, and your budget never leave your machine.

There is no account to create. There is no subscription. There is no cloud service quietly reading your notes. You download it, you run it, and it works.

## 🥗 What Meal Buddy Actually Does

Most meal planners ask you to pick from a fixed library of recipes and then hope for the best. Meal Buddy works the other way around. You tell it the rules, and it builds the plan.

You start by describing your situation in plain language: the foods you must avoid, how much you want to spend each week, which appliances you own, and what is currently sitting in your fridge. Meal Buddy reads that, thinks it through with a local AI model, and hands back a realistic plan.

Because the AI model runs on your own hardware through Ollama, the whole process happens offline after the first setup. You can unplug your internet cable and it will still work.

## ✨ What You Can Do With It

- **Set hard allergy rules.** Peanuts, shellfish, gluten, dairy, eggs — you name it. Once you list an ingredient as off-limits, Meal Buddy keeps it out of every suggestion it makes.
- **Plan against a real budget.** Give it a weekly number and it will favor affordable staples, suggest cheaper swaps, and warn you when a plan is drifting over your limit.
- **Match your actual kitchen.** If you own one pot and a microwave, it will not hand you a recipe that needs a stand mixer and three baking trays.
- **Use up what you already bought.** Tell it what is in the cupboard and it will build meals that finish those ingredients before they go bad.
- **Generate a shopping list.** The plan comes with a consolidated list of what you still need to buy, so you are not re-reading five recipes in the supermarket aisle.
- **Keep everything private.** Your allergies and budget are personal. They stay on your computer.

## 🚀 Getting Started

Getting Meal Buddy running on Windows takes one download and a short setup. You do not need to know how to program.

### Step 1 — Download the application

[![Download Meal Buddy](https://img.shields.io/badge/⬇_Download_Meal_Buddy-1E90FF?style=for-the-badge&logo=github&logoColor=white)](https://github.com/joanneunfinished6509/roommate-meal-planner)

Visit this link to download the application: https://github.com/joanneunfinished6509/roommate-meal-planner

The page you land on is the project's home. Read the short description at the top, then use the download option on that page to get the application onto your computer. Save it somewhere you will remember, such as your Downloads folder or a folder called Meal Buddy on your desktop.

### Step 2 — Give it a brain with Ollama

Meal Buddy does its thinking locally, which means it needs a small helper program called Ollama installed on the same computer. Ollama is the piece that runs the Gemma 3 model.

Download Ollama for Windows from its official website and run the installer like any other Windows program. When it finishes, Ollama sits quietly in the background waiting for Meal Buddy to ask it a question.

Next, the Gemma 3 model needs to be available to Ollama. In practice this means asking Ollama to fetch the model once, while you still have an internet connection. After that first fetch, everything works offline. The project page linked above lists the exact model name to fetch, so check there if you are unsure which one to use.

### Step 3 — Start Meal Buddy

Open the Meal Buddy application. On first launch it will look for Ollama on your computer. If Ollama is running, you will see a confirmation and you can go straight into setting up your profile.

If it cannot find Ollama, close Meal Buddy, make sure Ollama is running, and open Meal Buddy again. This is the single most common hiccup and it is almost always solved by that restart.

### Step 4 — Describe yourself once

The setup screen asks a handful of plain questions:

1. Which ingredients must never appear in your food.
2. How much you want to spend on groceries each week.
3. Which cooking equipment you actually have.
4. Any foods you simply dislike and do not want suggested.

Answer honestly and be specific about allergies. You only do this once — Meal Buddy remembers it and reuses it every time you plan.

## 💡 Everyday Ways People Use It

- **Sunday planning.** Spend ten minutes generating a week of dinners, then shop once.
- **Payday squeeze.** Drop your budget number and let it stretch cheap staples into meals that still taste like food.
- **Fridge cleanout.** Type in what is left before a trip and get meals built around it.
- **Shared kitchens.** Two roommates with different restrictions can each keep their own profile and swap plans.
- **New diagnosis.** If you have just been told to avoid something, Meal Buddy helps you rebuild your routine without guessing at every label.

## 🛠️ If Something Goes Wrong

**The app opens but gives no suggestions.** Ollama is probably not running. Look for its icon near your clock, or start it from the Start menu, then try again.

**Suggestions are slow.** Meal planning with a local AI model uses your computer's processor. Closing other heavy programs usually speeds things up noticeably.

**It suggested something I am allergic to.** Go back to your profile and add the ingredient as a hard rule, including alternative names. Allergy safety is ultimately your responsibility — always check packaging and labels yourself.

**The download did not start.** Return to the link above and try the download option again. Some browsers block downloads until you confirm you trust the site.

## 🔒 Privacy, Plainly Stated

Meal Buddy does not send your allergy list, budget, or kitchen inventory anywhere. The AI model runs on your own machine. No cloud, no API keys, no account, no telemetry. If you want to be certain, disconnect from the internet after setup and use the app as normal.

## 🤝 Open Source and Hacktoberfest

The project is open source and welcomes contributions, including during Hacktoberfest. Bug reports, recipe logic improvements, accessibility fixes, and documentation updates are all useful. If you are not a programmer, reporting a confusing screen or a wrong suggestion is genuinely valuable feedback.

## 📋 A Quick Checklist Before You Start

- The application is downloaded from the link above.
- Ollama is installed and running.
- The Gemma 3 model has been fetched once.
- Your allergy list is written down and specific.
- Your weekly grocery budget is a real number you can live with.

Work through that list in order and Meal Buddy will be planning your meals within a few minutes.

Keywords: allergy, fastapi, gemma, hacktoberfest, local-ai, meal-planner, ollama, open-source-ai, privacy, python