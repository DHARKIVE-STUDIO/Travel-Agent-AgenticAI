# AI Travel Helper (Lessons 1 to 13)

A learning project from the Microsoft AI Agents for Beginners course, simplified into one Colab notebook.

Built with AI help. I ran and tested each part and changed it to fit the course.

## What it does

- Runs an agent loop where the model calls tools: hotel search, budget, travel notes, booking proposal.
- Only records a booking after you type `y` in the terminal.
- Saves preferences only after you approve them.
- Summarises long chats.
- Logs each request so you can see which tools ran.

Fictional data only. Nothing is really booked.

## How to run

1. Open `travel_helper_lessons.ipynb` in Google Colab (File > Upload notebook).
2. Add your own NVIDIA API key in Colab's secrets (key icon in the sidebar), named `NVIDIA_API_KEY`. Turn on notebook access.
3. Run the cells top to bottom.
4. Type questions at the prompt. Commands: `reset`, `save <preference>`, `prefs`, `forget`, `log`, `quit`. Start with `team ` for three helpers. Add `plan` to make a plan first.

Do not put your API key in this repo.

## Known issues

- The flight helper sometimes makes up details beyond the tool results.
- Answers can take several minutes on the current model.
- Lessons 14 to 18 are not included.
