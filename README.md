# LeagueMate

**A simple dart league scheduling tool**  
Created by Laine Watts ([@MadJulip](https://github.com/madjulip))  
*The schedule has spoken.*

LeagueMate helps organize dart leagues by creating season schedules, assigning teams to playing days and boards, and preparing schedules to download and share. No account, coding knowledge, or software installation is required.

**Open LeagueMate online:** https://madjulip.github.io/LeagueMate/

## Getting started: website or saved file

You can use LeagueMate in either of two ways:

**Use the website:** Open the link above in a web browser such as Edge, Chrome, or Safari. You need internet access to load the website initially.

**Use a copy saved on your computer:** Download the `index.html` file, save it in a convenient folder (such as Documents), and double-click it in File Explorer. It opens in your default web browser, even without an internet connection. You do not need to install a separate program.

### What is an HTML file?

Think of it like a PDF saved on your computer: you can double-click the file and open it in a browser. Unlike a PDF, LeagueMate is interactive. You can enter team names, create schedules, and download the results. The HTML file **is the application**; the website is simply another way to open it.

The current HTML application is approximately **51 KB (less than 0.1 MB)**. Downloaded JPGs, ZIPs, spreadsheets, and backups are separate files and may be larger.

> **If the website is unavailable:** Your saved HTML copy can still open and run locally. Keep a copy on your computer if you want that fallback.

## Creating a schedule

1. **Choose your schedule.** Start with one schedule. If you have two independent leagues, click **+ Add Another League** and switch between them using the tabs. Rename a schedule using **Schedule name**.
2. **Step 1 — Set up your league.** Enter the number of teams, nights per week, boards per day, season weeks, and playing days. The season start date is optional.
3. **Step 2 — Enter your team names.** Replace the default names, then click **Create My Schedule**. Generation may take a moment.
4. **Step 3 — Download your schedule.** Choose a spreadsheet or JPG format (see below).
5. **View your schedule.** Select a week and playing day to review rounds, board assignments, and byes.

**How scheduling works:** Each board accommodates two teams, and each team plays on only one day per week. LeagueMate fills every board on each scheduled day. For example, one day with four boards requires eight teams. If the league has exactly enough teams for its weekly playing slots, there are **no byes**. Otherwise, the remaining teams have a bye that week. The current version uses the same number of playing days and boards each week.

## Downloading schedules

| Option | What you receive | Best for |
| --- | --- | --- |
| **Download Schedule (Spreadsheet)** | A `.csv` file containing the full season | Opening in Excel or another spreadsheet program |
| **Entire season (ZIP)** | One `.zip` file containing a separate `.jpg` for every playing day | Preparing all daily rotation images at once |
| **Selected week (ZIP)** | One `.zip` containing the JPGs for the selected week | Sharing one week's rotations |
| **Selected day (JPG)** | One `.jpg` image | Sharing or displaying a single day's rotation |

To download JPGs, choose the range under **OR Download Schedule as JPGs** and click the JPG download button. **Entire season** is the default. Use the **Week** and **Night** selectors in **View your schedule** to choose a specific week or day before downloading those ranges.

The **JPG schedule title** fills automatically from **Schedule name**, but you can change it if needed. The JPGs use the purple rotation-sheet format, even though the application itself uses an Emerald Green theme.

To use a ZIP file, open or extract it with your computer's built-in ZIP support to access the individual JPG images.

## One league or two?

LeagueMate starts with **one schedule**. You can ignore the **Add Another League** button if everyone plays in one league.

If you add a second league, each league has its own teams, settings, and schedule. **Teams in one league do not play teams in the other league.** The current version supports up to **two independent leagues with a combined maximum of 28 teams**.

Switch between leagues using the tabs at the top. Download the schedules for each league separately.

## Saving your work and making backups

**The HTML file does not store the changes you make inside itself.** LeagueMate uses your browser's local storage to remember saved information.

### Save My Settings

Click **Save My Settings** to save the current work in the browser. Generated schedules are also saved when created. When you reopen LeagueMate using the same browser and saved file, your information will **usually** still be available.

However, browser storage is not a guaranteed backup. Your saved information may be missing if you use a different browser or computer, clear browser data, or move/rename a locally saved HTML file. Browser behavior for locally opened HTML files can vary.

### Export League Backup — strongly recommended

Click **Export League Backup** to download a `.json` backup of the **currently selected league**, including its settings, team names, and generated schedule (if one exists).

**If you use both A-League and B-League, switch to each league and export a separate backup for each one.** The current backup button does **not** export both leagues together. Rename the downloaded files so you can distinguish them, such as `A-League-backup.json` and `B-League-backup.json`.

Store backups somewhere safe, ideally in a folder separate from the HTML application. A second copy on a USB drive or cloud storage provides extra protection.

### Import League Backup

To restore a saved league, open LeagueMate, select the league you want to restore, click **Import League Backup**, and choose its `.json` file. If you use two leagues, import each backup into its corresponding league. The combined 28-team limit still applies.

**Important:** A JSON backup restores information in LeagueMate. A spreadsheet or JPG is for viewing and sharing schedules; it is **not** a restorable LeagueMate backup.

## Frequently asked questions

**Do I have to download or install anything?**  
To use the website, no. To use LeagueMate without the website, download the HTML file **once** and save it to your computer. No additional program needs to be installed if you already have a modern browser.

**Does the saved HTML file need internet access?**  
No. The scheduling and file downloads run in your browser. The locally saved HTML file is designed to work offline.

**Will my schedule still be there tomorrow?**  
Usually, if you use the same browser and it retains its saved data. For peace of mind, export a league backup.

**Can I use LeagueMate on another computer?**  
Yes. Copy the HTML file to the other computer. To bring over an existing schedule, also export and import the appropriate JSON backup.

**What if I download a newer version of LeagueMate?**  
The website can be updated, but a copy saved on your computer does not update itself. Download the new HTML file when you want the latest features. Keep your JSON backups before changing versions.

**Can I change the schedule after creating it?**  
Yes, but changing scheduling settings means generating a new schedule. Export a backup first if you want to preserve the earlier version.

**What are Schedule Checks and Opponent History?**  
Optional reports that help review matchups, byes, and schedule balance. They aren't required to create or download a schedule.

**Can some weeks have no byes?**  
Yes, when the total number of teams exactly matches the available weekly playing slots. The current version does not support changing the number of playing slots from week to week within the same schedule.

**What are all these file types?**  
- `.html` — the LeagueMate application.
- `.csv` — a spreadsheet-compatible schedule.
- `.jpg` — an image of one day's rotation.
- `.zip` — a package of multiple JPG images.
- `.json` — a backup that LeagueMate can import later.

## Recommended routine

After you finish a schedule, **Save My Settings**, **Export League Backup** (once for each league), and download the **Entire season (ZIP)** JPG package. Keep the HTML file and backup files in a folder you can find easily.

---

**LeagueMate** · Created by Laine Watts ([@MadJulip](https://github.com/madjulip))  
*The schedule has spoken.*

