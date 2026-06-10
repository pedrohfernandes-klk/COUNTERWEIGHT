# COUNTERWEIGHT

**The fair objection.**

COUNTERWEIGHT is a compact text-card app that gives the user the strongest good-faith case against their own position.

It does not flatter.
It does not advise.
It does not argue in bad faith.
It adds weight to the other side.

One button. One counterargument. One clean line of friction.

## What it does

COUNTERWEIGHT randomly serves one card from a fixed deck of **999 text cards**.

Each card is written as a concise opposing case, objection, burden-of-proof challenge, or inconvenient reframing. The purpose is not to defeat the user, but to make their idea, choice, belief, plan, or excuse carry more weight.

Examples of the card logic:

* “The strongest argument against you…”
* “The case for their doubt…”
* “The opposing case is fair…”
* “The counterweight…”

The app is designed for moments when a person is too certain, too defensive, too rhetorically comfortable, or too attached to the first version of an idea.

## Concept

COUNTERWEIGHT belongs to the SPARK TOOLS family of small browser-based text instruments.

Where other tools generate questions, bad advice, crooked definitions, or suspicious evidence, COUNTERWEIGHT does one specific thing:

**It states the best case against you without turning that case into a caricature.**

The app draws conceptually from:

* steelmanning
* Socratic questioning
* legal advocacy
* burden of proof
* epistemic humility
* public reason
* Stoic self-examination
* existential responsibility
* fallacy detection
* good-faith disagreement

It is deliberately sharper than a reflection prompt and fairer than a hostile roast.

## Tone

The tone should remain:

* direct
* intelligent
* fair
* unsentimental
* useful
* slightly severe
* never cute
* never therapeutic
* never merely negative

COUNTERWEIGHT should feel like an honest opposing counsel, not an internet argument.

The ideal card does not say “you are wrong.”
It says: **“Here is the part of your case that still has to survive.”**

## Interface

COUNTERWEIGHT is a single-page HTML app.

Main interface elements:

* app title
* short subtitle
* status line
* primary action button
* animated output-box icon
* generated text card
* Copy button
* Clear button
* About panel

The animated icon sits at the top centre of the output card and reacts when the button is pressed.

The counter is shown only in the About section.

## Technical structure

COUNTERWEIGHT is built as a self-contained HTML file.

It uses:

* HTML
* CSS
* vanilla JavaScript
* embedded card database
* embedded SVG favicon
* Google Fonts:

  * Saira Stencil One
  * IBM Plex Mono

No build process is required.

No backend is required.

No user account is required.

No data is saved.

No tracking is included.

## Card database

The card deck is stored directly in the JavaScript as a `CARDS` array.

Current deck size:

**999 cards**

The app randomly selects one card per button press and keeps a short recent-history buffer to reduce immediate repetition.

## Buttons

### Main button

The main button generates a new card.

### Copy

Copies the current card text and app tag.

### Clear

Resets the output card to its starting state.

### About

Opens the About panel with app description, deck count, privacy statement, and copyright line.

## Privacy

COUNTERWEIGHT runs locally in the browser.

It does not collect, transmit, save, or analyse user input.

There is no login, no analytics layer, no account system, and no remote database.

## Development notes

When editing COUNTERWEIGHT, preserve the sibling-app structure unless a redesign is intentional.

Keep:

* single-file format
* mobile-first layout
* deck embedded in JavaScript
* counter only in About
* Copy / Clear / About behaviour
* compact card output
* animated icon reacting to generation
* no tracking and no storage

Avoid:

* adding explanations to the cards
* turning cards into advice
* making the tone motivational
* making the tone cruel
* adding unnecessary interface elements
* exposing the full counter on the main screen
* weakening the good-faith opposition principle

## SPARK TOOLS context

COUNTERWEIGHT is part of **SPARK TOOLS**, a suite of small text-based browser instruments for thinking, writing, reframing, and creative pressure.

Related tools include:

* IDK MACHINE
* BADVICE
* SAID IT
* TILT
* BAD EVIDENCE
* THE WRONG QUESTION
* ASSUME
* COUNTERWEIGHT

Each tool has its own voice, but the suite shares a compact, retro-terminal, text-first design philosophy.

## Copyright

© HRF 2026. All rights reserved.
