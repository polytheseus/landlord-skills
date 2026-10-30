# Set up Landlord Assistant in ChatGPT, Gemini or Claude

No coding needed. Setup takes about 5 minutes, once. You then have a helper that
plans rent increases with the right Section 13 dates, handles tenants' repair
reports, and writes fair, clear messages to tenants, the way a careful landlord would.

**You need these four files from this folder:**
`instructions.txt`, `rent-increase.md`, `repair-requests.md` and `tenant-messages.md`.
To download them, open each file on GitHub and click the download button
(the arrow icon, top right of the file). Or download the whole pack as a zip:
green **Code** button → **Download ZIP**, then unzip it and open the `chat` folder.

---

## ChatGPT (custom GPT)

Creating a GPT needs a paid ChatGPT plan. On a free plan, use the
"ChatGPT Project" or "Any chat" options below instead.

1. Go to chatgpt.com and click **GPTs** in the left sidebar, then **+ Create**.
2. Click the **Configure** tab (not "Create").
3. **Name**: `Landlord Assistant`. **Description**: `Rent increases, repairs and tenant messages for landlords`.
4. Open `instructions.txt`, copy everything, and paste it into **Instructions**.
5. Under **Knowledge**, click **Upload files** and add the three `.md` files.
6. Click **Create** (top right) and choose **Only me**. Done: it appears in
   your sidebar.

**ChatGPT Project (works on more plans):** in the sidebar click **New project**,
name it `Landlord Assistant`, open the project's **Instructions** and paste
`instructions.txt`, then add the three `.md` files under **Files**. Start
every chat inside that project.

## Gemini (Gem)

1. Go to gemini.google.com. In the left menu, open **Gems** (you may need
   **Explore Gems**), then **New Gem**.
2. **Name**: `Landlord Assistant`.
3. Paste everything from `instructions.txt` into **Instructions**.
4. Under **Knowledge**, add the three `.md` files.
5. Click **Save**. Find it later under Gems in the left menu.

## Claude (Project)

1. Go to claude.ai and click **Projects**, then **Create project**. Name it
   `Landlord Assistant`.
2. Click **Set project instructions** (or the instructions pencil), paste
   `instructions.txt`, and save.
3. Under **Project knowledge**, click **+** and upload the three `.md` files.
4. Start every chat inside the project.

## Any chat, any app (no setup)

Start a new chat, paste the contents of `instructions.txt`, then paste the
matching `.md` file (for example `rent-increase.md`) and finish with your
request. This works in any AI chat app, including free plans. It's just a
little more pasting each time.

---

## Try it

- "Monthly tenancy, rent £950 due on the 20th, started 20 March 2024, last increase 20 January 2026. I want £1,000. When's the earliest start date and when must I serve Form 4A?"
- "My tenant texted: 'black mould is back in the bedroom, the baby's room'. Write a reply and tell me what to do this week."
- "Tenant emailed asking to keep a small cat. I'm a leaseholder. What's my deadline and what do I say?"
- "Tenant says she's leaving on 3 January. Rent is due on the 15th. Write a reply confirming the right end date."

**Privacy tips:** don't paste tenants' bank details, dates of birth, ID or
immigration documents. First names and the facts are enough. Check your AI
app's data settings (for example, turn off "improve the model for everyone"
in ChatGPT).

**Always check** before you send or serve anything. Forms, notice periods and
landlord duties change: check gov.uk. This is England-only and isn't legal
advice; get advice for disputes or possession.

If a menu name has changed since this guide was written, the apps' help
pages show the current steps: search "create a GPT", "create a Gem" or
"Claude projects".
