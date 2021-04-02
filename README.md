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

## TutorsLive

- integrate with slack presence api, establish two-way bridge to TutorsLive
- introduce 'poke' feature, to initiate intaction with classmate
- introduce filter feature - see who is working on the same lab as me

## TutorsTime

- replace spreadsheet mechanic with something more intuitive
- migrate to 'dashboard', taking advantage of card layouts perhaps for more intuitive interface

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

## tutors-html

- migrate to tailwind based UX, mirroring tutors-svelte

## search

- reevaluate search, include strategy for searching pdfs

## TLS - Tutors Liberation Society

- build tool to generate gitbook, 11ty or outher markdown based format to some (say labs) or all aspects


