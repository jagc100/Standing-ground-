# Standing Ground

A free, plain-language court preparation tool for people representing themselves in Canada. Built first for First Nations, Métis and Inuit people, and open to everyone.

**Legal information, not legal advice.** Rules, deadlines and links change; confirm anything important with the court registry, a courtworker, legal aid or a lawyer.

## What it does

| Tab | Purpose |
|---|---|
| Find your path | Likely court or tribunal, first steps, deadlines and local help, by province and type of problem |
| Prepare for court | Five-stage checklist and court-binder order |
| My case file | Deadline counter, timeline of events, affidavit draft (stored only in the user's browser) |
| Look up the law | Citation decoder, a "still cited?" check (live CanLII citing-case counts), CanLII search guide, key Supreme Court of Canada decisions |
| Rights & issues | Plain-language topics; Indigenous-specific topics are labelled FNMI |
| Who can help | Directory of courtworkers, legal aid, legal information and complaint bodies |
| Languages | Interpreter-request letter, Indigenous-language status cards, translator kit |
| Words | Glossary of court terms |

## Running it

`index.html` is a single self-contained page. Open it in a browser, or serve the folder with any static host. It sends no data anywhere; user entries stay in the browser's local storage. The "still cited?" check calls a small backend that keeps the CanLII API key private (see the [backend repo](https://github.com/jagc100/express-js-on-vercel)).

## Languages

Presented in English. Versions in Nēhiyawēwin (Cree), Anishinaabemowin (Ojibwe), Dene languages, Inuktitut and Michif are being prepared with fluent speakers and community review. No machine translation is used.

## Roadmap

- Indigenous-language versions from partner translations
- Fuller province-by-province directory
