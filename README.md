# Chairside

A workflow app for small dental offices that keeps patient tasks and phone messages organized when one person is covering both the front desk and the chair.

**Live prototype:** https://chairside-gilt.vercel.app/

## The problem
In summer 2026, I was the only support staff at a dental office, covering both dental assistant and receptionist roles. The practice management software (Denticon) handled scheduling and records, but there was no simple way to track day-of tasks for each patient or make sure phone messages reached the dentist. 

## What it does
- **Tasks:** Add a patient and instantly get a preset checklist of what needs to happen for their visit
- **Notes:** Log patient phone messages so they get relayed to the dentist
- **Trays:** Quick reference for what each procedure tray needs
- **Accounts + cloud sync:** Each user logs in and their data syncs securely across devices

## My role
I identified the problem from my own experience at the office, defined the features, designed the user experience, and tested and iterated on the app. I built it through AI-assisted development with Claude, directing the product while Claude helped write the code.

## Built with
JavaScript, HTML/CSS, Supabase (auth + database), GitHub, Vercel

## What's next 
- **Shared office accounts:** Every staff member gets their own login, but everyone in the same office shares one live patient list, so when the front desk adds a patient or a message, it shows up instantly for the assistant and dentist. 
- **Sterilization tracking:** Pull cycle data from the autoclave and ultrasonic cleaner (cycle times, completion status, and logs) so staff can see which instruments are ready and keep sterilization records automatically instead of on paper. 
- **Denticon integration:** Explore connecting to Denticon so the day's scheduled patients load into Chairside automatically, without double entry. 
