# tutors-roadmap

## UX

- full colour review, with a view to incorporate themes
- rexamine icons and icon libraries. Evaluate noun project for inclusion

## Authentication

- consider firebase auth as replacement for auth0
- explore integration with LDAP/WIT authentication

## Data Store

- migrate to Firebase Cloud Database from Realtime database
- simlify and secure TutorsTime data store

## Presence

- integrate with slack presence api, establish two-way bridge to TutorsLive

## Storybook

- investigate storybook integration, creating stories for course, topic, talk, video, lab etc...
- could variations on these stories be made available to course authors?

## Full Fractal

- support units on home page
- support full recursive course structure

## SvelteKit & Serverless

- explore migration to SvelteKit
- consider role of serverles capabilities in same (possibly TutorsTime or Live)

## Project Structure

- review tutors-lib, tutors-json, tutors-html mono repo
- extend tutors-svelte to code share with these
- explore code splitting options for tutors-svelte/vite, factor out TutorsTime and TutorsLive


