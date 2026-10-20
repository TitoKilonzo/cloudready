# CloudReady

CloudReady is an independent AZ 900 study companion built as a rapid prototype for the Vibe Coding Hackathon. It uses original practice questions and learning notes. It is not affiliated with Microsoft and does not contain official exam questions.

## Included

- Responsive dashboard with study indicators and a weekly plan
- Original multiple choice practice quiz with detailed answer feedback
- Flashcards with reveal interactions
- Editable study schedule
- Progress report with topic indicators and print support
- Searchable study resource library
- Browser local storage for practice progress and study plan
- Responsive layouts for desktop, tablet, and mobile
- Real photographs loaded from Unsplash

## Stack

React, Vite, Lucide icons, and custom CSS. AI APIs, analytics SDKs, or external database are used in this prototype. Progress is stored in local storage on the current browser and device.

## Run locally

1. Install Node.js 20 or later.
2. Run `npm install`.
3. Run `npm run dev`.
4. Open the local URL shown in the terminal.
5. Run `npm run build` to create a production build in `dist`.

## Notes

The dashboard uses sample learner details and sample topic indicators to make the first visit useful. Quiz answers and study plan updates are interactive and persist in the browser. Topic indicators are not official readiness predictions. The photographs require an internet connection.

## Before a public launch

Add authentication and a database only if accounts and cross device sync are needed. Review all dependencies after installation, run a vulnerability audit, and resolve any reported issues before deployment. This repository does not claim a guaranteed zero vulnerability result because dependency advisories can change over time.
