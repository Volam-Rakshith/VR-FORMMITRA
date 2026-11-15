# FormMitra

Free step-by-step help for Indian government forms, in English, Hindi and Telugu.

Search a document or service, see the steps, the documents you need, photo and signature size rules, a field-by-field explanation and the official website to apply on. No sign-up, no ads, no tracking.

Made by VR Developments.

## Features

- 83 guides: 34 application guides (PAN, passport, driving licence and more) and 49 guides for edits, corrections and life changes (name, address, bank details and more)
- English, Hindi and Telugu on every guide
- Documents checklist and a "What do I need?" helper
- Built-in tools to convert and compress photos and documents to the size a form asks for, right in your browser (files never leave your device)
- Your ticks and files list are saved only in your own browser
- Works on phone, tablet and laptop, and offline once opened
- Feedback, suggestion and bug-report buttons

## Try it

Open the live site: https://YOUR-USERNAME.github.io/YOUR-REPO/

Or open `index.html` in any browser. No install or build is needed to use the site.

## Project layout

- `index.html`: the page
- `css/`: the look
- `js/`: the code (app, photo tools, quiz, feedback button)
- `data/`: all guide content and labels (`guides-*.js`, `ui.js`, `docs.js`, `quiz.js`, `config.js`)
- `fonts/`: bundled fonts so the site works offline
- `404.html`: sends mistyped links to the right guide

## Edit or add a guide

Guides live in `data/guides-*.js`. Each guide has an `id` and `en`, `hi` and `te` blocks. Keep the same number of steps in all three languages, give fees or times only if an official page states them, and use only official `.gov.in` or `.nic.in` links. Add a new guide by copying an existing block and giving it a new unique `id`.

## Host it for free

Upload the files so that `index.html` sits at the top level of the repository, then in Settings > Pages choose "Deploy from a branch", branch `main`, folder `/ (root)`. The site also works on Netlify and Cloudflare Pages by uploading the folder.

## Feedback form

The feedback, suggestion and bug-report forms use Web3Forms. Put your public access key in `data/config.js` (`WEB3FORMS_KEY`). Nothing is sent until the visitor presses Send.

## Please note

Guides were written from official pages on the date shown on each guide. Government websites change, so always confirm on the official site. Photo sizes in the tools are common sizes, so follow the size shown on your form. Hindi and Telugu text has not yet had a native-speaker review.

## License

Free to use for learning and sharing. Please keep the VR Developments credit.
