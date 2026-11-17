# Shiftly

Shiftly is a website for student workers who have more than one part-time job and a weekly hour limit. It adds up the hours from every job, shows how many hours are left this week, and estimates pay.


## What it does

- One card per week with hours for each job and a running total
- A status for each week: on track, near the limit, at the limit, or over
- Student mode (20 hours a week in session, 40 on breaks) or regular worker mode (any limit you choose)
- Job titles, hourly wages, night-shift pay, tips and unpaid breaks
- Enter a shift from clock-in and clock-out times
- Name your weeks, like "Thanksgiving week"
- School calendar support, with San Diego State built in
- Earnings page and CSV download
- Accounts, so each person's hours are saved and private

Limits and dates in the app are a guide. Always confirm them with your school and employer.

## How it's built

- One HTML file with plain JavaScript
- Supabase for login and saving each person's data
- Database rules so each user can only see their own data (see `supabase-setup.sql`)

## Next steps

- Move each user's data into separate tables for users, jobs, weeks and shifts
- Read timeclock screenshots and school calendars with AI, with a review step before saving
