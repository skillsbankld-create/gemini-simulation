# Gemini Simulation (Skills Bank)

Interactive training replica of the Gemini app (November 2026), for trainees who do not have Gemini accounts.

- **Explore:** the Gemini app opens directly: chat and Task mode, the + menu (files, Drive, image, video, music, Canvas, Deep research, Learn, Storybook), Library, Images, Videos, Scheduled, Customize (connectors and skills), Gems, Notebooks with Studio, personal intelligence, import memory, temporary chat, share screen and theme.
- **Gemini in Workspace and Chrome:** Gmail (Ask Gmail, AI Overview, Help me write, Add to Calendar), Docs (Notes by Gemini, Help me write, insert answers), Sheets (answers, new tables, visual dashboard), Slides (create a deck, images, slideshow) and Chrome (ask about tabs, share tabs, Take over task). Switch apps from the assistant bar or the Google apps icon.
- **Assistant:** click any button and a card explains what it does, why it helps at work, and which plan has it. With live AI on, trainees can also ask free questions.
- **Plans:** Free, Google AI Plus, Pro and Ultra (Egypt prices). Paid features appear only on plans that include them.
- **How do I…?** 3 guided how-tos in Egyptian Arabic: import memory, Gems to skills, notebooks.
- **Real AI:** answers, images (Nano Banana), music (Lyria) and videos come from the real Gemini API through the Skills Bank Cloudflare Worker. Add the secret `GEMINI_API_KEY` to the Worker and redeploy `simlab-worker.js`. Session codes are shared with the ChatGPT and Claude simulations.
- Limits (trainer panel): 1 real video per trainee per day and 15 per day for everyone, 6 images and 3 music clips per trainee per hour.
