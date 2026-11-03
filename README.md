# fizeek-legal

The source of Fizeek's legal pages: `pages/terms.html`, `pages/privacy.html`, `pages/health-data.html`,
`pages/delete-account.html` and `pages/coach-agreement.html` (batch AH), with `legal-versions.js`
(written by fizeek-sandbox `scripts/legal/writeLegalVersions.mjs`, which also prints the postal
address from `supabase/functions/_shared/legalAddress.ts` `LEGAL_POSTAL_ADDRESS`). The coach site serves them at fizeekapp.com (`/terms`,
`/privacy`, `/health-data`, `/delete-account`, `/coach-agreement`; fizeek-landing `scripts/syncLegalPages.mjs`). The html
files at this repo's root forward the old github.io addresses there. See `docs/LEGAL_READ_LIST.md`.
