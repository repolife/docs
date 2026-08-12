> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

- The product is **Seed Scroll** — two words, both capitalized. Never "SeedScroll" or "the Seed Scroll app".
- A **study note** and a **quick reflection** are different things. A quick reflection is a short thought on a single verse; a study note is a fuller, hashtagged, editable study that can span passages and be shared. Do not call one the other.
- A **word study** is the premium deep analysis (root, semantic range, Hebrew letter meanings). A **Strong's definition** is the free basic lookup. Keep them distinct — conflating them implies free users get more than they do.
- **Strong's** always takes the apostrophe: Strong's number, Strong's badge, Strong's Concordance.
- The **verse study panel** is the panel that opens from a verse. Not "the verse sheet" or "the popup".
- **Reading plan**, lowercase, two words. Reserve "Plans" for the tab name.
- **Premium** is lowercase in prose: "premium features", "a premium subscription". Not "Pro", not "Premium tier".
- Refer to translations by the short names the app shows: **KJV+**, **WEB**, **RV1909**, **BSB**, **Cepher WTL**.
- **Guest mode** is reading without an account. Not "anonymous mode" or "logged out".
- Write **scripture** lowercase unless it starts a sentence.
- Platforms are **iOS**, **Android**, and **web** — "web" stays lowercase.
- Hashtags use code formatting with the hash: `#hashtags`.

## Style preferences

{/* Add any project-specific style rules below */}

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

**Do not document:**

- Internal identifiers of any kind — Linear ticket IDs, PR numbers, commit hashes, branch names.
- Implementation internals. No Supabase, edge functions, table or column names, RevenueCat, EAS, Expo, or database filenames. Readers need to know what a feature does, not how it is built.
- AI model names, vendors, or prompt text. Describe the capability, not the implementation behind it.
- Features that are not in a released build users can install. Beta functionality belongs only on the Android beta page, clearly marked.
- Admin or publisher-only tooling, including publisher QA access to licensed translations.
- Specific prices. Billing varies by store and region — say that monthly and annual options exist and link to the store, as `account/premium.mdx` already does.
- Security-relevant mechanics: entitlement checks, license validation, download tokens for paid translations.
- Known bugs, roadmap, or planned work. The changelog records what shipped.

**Also:**

- Screenshots must not contain real user content, personal data, or another person's profile.
- When a feature is premium, say so at the point of use with a `<Note>`, the way `features/word-study.mdx` does. Do not leave a reader to discover it at a paywall.
