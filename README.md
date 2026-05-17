[README (2).md](https://github.com/user-attachments/files/27867276/README.2.md)
# Train Track — Fitness Progress Dashboard

> A free, browser-based fitness tracking dashboard. No accounts, no subscriptions, no data sent anywhere. Everything stays on your device.

---

## Live Links

Click the link below to open the dashboard — do not use the GitHub file view, that only shows code.

| Version | Who it is for | Link |
|---|---|---|
| Beginner | First time trackers, simple and clean | [Open TrainTrack Beginner](https://biokinstud.github.io/Recreational-Training-Dashboard/TrainTrack_Beginner.html) |
| Individual | Regular clients who want the full feature set | [Open TrainTrackIndividual](https://biokinstud.github.io/Recreational-Training-Dashboard/TrainTrackIndividual.html) |
| Coach Edition | Coaches tracking multiple clients | [Open TrainTrack Coach Edition](https://biokinstud.github.io/Recreational-Training-Dashboard/TrainTrack_CoachEdition.html) |

---

## What Is This

Train Track is a personal fitness dashboard that reads your training data from an Excel file and turns it into visual progress charts, personal records, weekly summaries, and printable reports.

You fill in your workouts in Excel. You upload the file to the dashboard. Your data stays in your browser — nothing is sent to a server.

---

## How To Get Started

**Step 1 — Open the dashboard**
Click the Individual Client link above.

**Step 2 — Download your Excel template**
Click the blue Download your Excel template button on the upload screen.

**Step 3 — Fill in your data**
Open the Excel file and fill in the yellow cells across the four sheets:

| Sheet | What to log |
|---|---|
| Resistance_Log | Date, exercise name, sets, reps, weight |
| Cardio_Log | Date, activity, duration (min), distance (mi), calories |
| Strength_Log | Date, lift name, tested 1 rep max — only when you actually test it |
| Bodyweight_Log | Date, body weight |

**Step 4 — Upload and view your dashboard**
Go back to the dashboard, drag your file into the upload zone or click Choose file. Your dashboard populates instantly.

**Step 5 — Every week after that**
Add new rows to your Excel, save it, go back to the dashboard, click Update data, upload your file. Done.

---

## Excel File Notes

- Only fill in the yellow cells. Grey cells are locked.
- You can rename the Excel file to anything you like — the dashboard reads the sheet names inside, not the filename. So `JaneSmith_Training.xlsx` works just as well as `TrainingLog_Template.xlsx`.
- Date format must be YYYY-MM-DD, for example 2025-04-22. The cells are pre-formatted for this.
- Spell exercise and activity names exactly the same each session. The dashboard groups your data by name — if you write Bench Press one week and bench press the next it treats them as two different exercises. Check the My Exercises panel on the dashboard before filling in each week.
- If you run out of rows just keep adding below the last entry. The dashboard will still read everything.
- Sheet names must stay as they are: Resistance_Log, Cardio_Log, Strength_Log, Bodyweight_Log. Do not rename the tabs inside the Excel file.

---

## What the Dashboard Tracks

- **Weekly summary** — wins and losses for the week with traffic light colour coding
- **Resistance training** — weight lifted over time per exercise, progress badges, personal exercise list
- **Cardio** — duration and distance charts, activity breakdown by category, energy systems education
- **Strength** — estimated and tested 1 rep max, PR detection and timeline
- **Body weight** — trend chart, total change, weekly comparison
- **Progress** — 12 week consistency calendar, personal records timeline
- **Resources** — curated research library with summaries, and your own articles
- **METs chart** — 50 plus activities with intensity levels and personalised calorie estimates
- **Printable reports** — weekly summary and full progress report with charts, branded with your name

---

## Coach Edition

The Coach Edition has everything the individual version has plus a Client Manager. This lets you track multiple clients from one dashboard — each client gets their own private data slot in your browser.

**How it works:**
1. Click the green Clients button in the top right
2. Add a client by name
3. Switch between clients — each one has their own isolated data
4. Upload each client's Excel file to their slot
5. Generate reports per client from the Reports button

**Storage:** Data lives in your browser only. Most browsers support 50 to 100 active clients depending on how much data each person has. Delete client slots when a program ends and you have saved their PDF report.

**Important:** Clearing your browser storage or switching devices will erase client data. Use the Reports button to save PDF backups regularly.

---

## Privacy

No data is ever sent anywhere. There is no server, no database, no accounts, no tracking. Everything you upload and enter stays in your browser's localStorage on your device. Closing the browser or the tab does not delete it — it persists until you clear your browser storage or delete a client slot manually.

---

## Built With

- [SheetJS](https://sheetjs.com/) - Excel file parsing
- [Chart.js](https://www.chartjs.org/) - Charts and graphs
- [Tabler Icons](https://tabler.io/icons) - Icons
- Hosted on [GitHub Pages](https://pages.github.com/)

---

*Train Track Alpha - Powered by BiomechanicsIQ and Claude*
