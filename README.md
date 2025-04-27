# Weekly Meal Plan Automation

This n8n workflow automatically generates a 7-day family meal plan and grocery list using OpenAI's GPT-4o model. It parses the AI response, builds a clean HTML email, and sends it through Gmail every week on a schedule.

## Features
- Uses OpenAI to generate meal plans and grocery lists
- Parses structured JSON responses safely
- Formats beautiful HTML emails
- Fully scheduled and automated (runs every Sunday)

## How It Works
1. Cron node triggers every Sunday morning.
2. HTTP Request node asks OpenAI for a structured JSON meal plan.
3. Code node extracts and parses JSON from the OpenAI response.
4. Function node builds a styled HTML email body.
5. Gmail node sends the meal plan and grocery list directly to your inbox.

## Files
- `meal-plan-automation.json`: Full n8n workflow (importable into n8n).

## Setup Instructions
- Clone this repo
- Import the JSON into your n8n workspace
- Add your OpenAI and Gmail credentials
- Activate and enjoy automatic meal planning!

---

✅ This README helps others understand your project and shows your skills.

---

# 🎯 Final Checklist

| Step | Status |
|:---|:---|
| Exported n8n JSON file | ✅ |
| Created GitHub repo | ✅ |
| Uploaded JSON file | ✅ |
| Wrote clear README | ✅ |

---

# 🧠 Pro Tip:
You can even add a screenshot of the **n8n workflow diagram** into your README later if you want to really impress!

---

# 🎁 Bonus
If you want, I can also:
- Write you a **fancier README template** (with visuals, emojis, badges)
- Help you create a **GitHub Actions auto-deploy** so if you update your workflow, it auto-commits.

---

# 🚀 Would you like me to:
- Build a **sample README file** you can copy-paste today?
- Help you write a little **"About Me" blurb** at the bottom of the repo to show your automation skills?

👉 **Tell me — I can build it for you right now if you want!** 🌟  
(Let’s make your GitHub ✨ shine ✨!)
