# Automated site review: `www.keepersecurity.com`

289 pages of `https://www.keepersecurity.com` (and 3 addresses that answered an error), read on 2026-11-11 by Suite Builder's crawler in a real browser, logged out, as a first-time visitor sees them. Nothing was sent, bought or signed in to. This review reads the public site as it is served. It also observes the site's own security guards, as a visitor's browser sees them. It sends nothing and attacks nothing.

## Links that need a look (6)

Each of these links answered an error or did not answer. A person is to look at every one, whatever the site means by it: nothing here is cleared by a rule. A link leaves this list only when the team lists it, with the status it answers, in the suite's expected-links block.

- `/zero-knowledge-security/` answered 404; linked from /features/emergency-access/, /trial/keeper-free-trial/; broken; in the menu How does Keeper protect my data? → zero-knowledge (SITE-02)
- `/us-password-practices-report/` answered 404; linked from /threats/password-spraying-attack/; broken (SITE-02)
- `https://docs.keeper.io/keeper-documentation-jp/` answered 404; linked from /blog/ja/2026/09/03/keeper-security-named-exemplary-in-2026-isg-buyers-guide-for-iam/, /blog/ja/category/news-and-events-ja/, /blog/ja/2026/01/27/keeper-wins-2026-winter-itreview-grid-award-leader-badge-for-password-management/, /blog/ja/2025/04/16/debunking-the-misconceptions-of-using-password-managers/, /blog/ja/category/password-ja/ and 7 more; broken (SITE-33)
- `https://docs.keeper.io/en/v/user-guides/web-vault` answered 404; linked from /customer-success-portal/; broken (SITE-33)
- `https://docs.keeper.io/en/v/release-notes/enterprise/admin-console/admin-console-16.16.0` answered 404; linked from /blog/nl/2024/12/18/2024-in-review-keeper-securitys-innovations-in-cybersecurity/, /blog/fr/2024/12/18/2024-in-review-keeper-securitys-innovations-in-cybersecurity/; broken (SITE-33)
- `/family-password-manager/` answered 404; linked from /features/emergency-access/; broken (SITE-02)

**5 major, 8 minor.** Major: lets a visitor or a search engine down now. Minor: worth fixing. Info: said for the record; counts against nothing. Each finding lists every page the read saw it on; the read is a sample of a big site, so a finding can reach further than it lists.

## What this review checked

Of 40 checks, 39 ran on this crawl; 1 could not be confirmed.

<details>
<summary>The checks, by kind</summary>

Pages and links (11 of 11 ran)
- Pages that answer an error yet draw content
- Links that answer an error
- Links that redirect before they arrive
- Page titles that are shared or missing
- An address that cannot exist but answers as a page
- Chains of redirects
- Images that do not load: 60 of the 1909 images seen were asked, the site's own first
- Links that send visitors from https to http
- Links to other sites that lead nowhere: 100 of the 562 addresses seen were asked, the most linked first
- Links that answer an error on purpose
- Links to other sites that did not answer the crawler: 100 of the 562 addresses seen were asked, the most linked first

Markup, accessibility and search (13 of 13 ran)
- Links and buttons with nothing for a screen reader to say
- Form fields without a label
- Images with no address
- Placeholder text left on pages
- The viewport setting for phones
- Canonical links that point somewhere else
- Images without alt text
- The language each page declares
- The main heading of each page
- Links to a part of the page that is not there
- Descriptions for search results
- The year in the copyright notice
- Form fields whose only label is a placeholder

Loading and speed (6 of 7 ran)
- Scripts, style sheets and data requests that fail to load
- Errors thrown by the site's own scripts
- Pages slow to answer or to load
- Requests over plain http from an https page
- Requests to other sites' hosts that fail
- Pages that did not finish loading: not confirmed
- What failed for the crawler on other sites, or from no known source

The site's own addresses, certificate and headers (9 of 9 ran)
- Addresses of the site that do not answer
- Response headers that browsers act on
- Server software and version announced in headers
- The certificate's end date, name and trust
- Whether the http address sends visitors to https
- The sitemap
- A contact for security reports (security.txt)
- One site answering at two names
- The certificate chain, as the crawler's machine sees it

Not confirmed: the crawl file records what such a check saw only when it saw something, so it cannot show whether the check ran and found nothing, or did not run.

</details>

## major SITE-02 2 broken links: the site links to addresses that answer an error

**Why it matters.** A visitor who follows one of these links reaches an error instead of the page promised.

**Likely fix.** Point each link at a page that exists, or bring the page back \(or redirect its old address to where it went\).

<details open>
<summary>2 links</summary>

- `/zero-knowledge-security/` answered 404; linked from /features/emergency-access/, /trial/keeper-free-trial/; in the menu How does Keeper protect my data? → zero-knowledge
- `/us-password-practices-report/` answered 404; linked from /threats/password-spraying-attack/

</details>

## major SITE-11 289 pages stop a visitor zooming

**Why it matters.** On a phone a page with no viewport setting is drawn at desktop width and shrunk to fit, and Google ranks it as not mobile-friendly. A page that stops zooming fails people who need larger text \(WCAG 1.4.4\).

**Likely fix.** Use \<meta name="viewport" content="width=device-width, initial-scale=1"\>, without user-scalable=no or maximum-scale=1.

<details>
<summary>289 pages</summary>

- `/` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/get-keeper.html` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/support.html` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/blog/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/2025/02/19/the-top-6-pam-features-that-you-actually-need/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/2024/02/23/why-organizations-need-automated-password-rotation/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/partners.html` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/blog/2026/09/23/why-critical-infrastructure-needs-zero-trust-security/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/enterprise.html` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/features/password-generator/` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/business.html` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/solutions/remote-browser-isolation/` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/blog/es-la/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/category/whats-new-with-keeper/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/personal.html` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/features/passphrase-generator/` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/resources/case-studies/` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/resources/white-papers/` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/resources/glossary/what-is-a-master-password/` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/family-plan.html` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/resources/public-sector/` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/privileged-access-management/` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/vs/cyberark/` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/endpoint-privilege-management/` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/secrets-manager.html` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/solutions/remote-privileged-access-management/` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/blog/author/kaylee/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/msp-password-manager.html` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/msp-privileged-access-manager/` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/trial/pam-msp-free-trial/` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/blog/ru/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/ru/2026/07/08/secure-access-in-slack-teams-jira-and-servicenow-with-keeper/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/ru/2026/09/02/how-to-reduce-your-cloud-attack-surface-by-eliminating-standing-privileges/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/ru/category/comparison-ru/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/ru/2026/09/03/keeper-security-named-exemplary-in-2026-isg-buyers-guide-for-iam/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/reports/isg-buyers-guide/` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/blog/ru/author/aleksandra/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/resources/glossary/what-is-multi-factor-authentication/` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/features/risk-management-dashboard/` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/blog/category/privileged-access-management/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/ru/category/product-security-ru/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/industries/manufacturing/` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/blog/ja/2026/09/03/keeper-security-named-exemplary-in-2026-isg-buyers-guide-for-iam/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/es/2026/09/03/keeper-security-named-exemplary-in-2026-isg-buyers-guide-for-iam/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/pt-br/2026/09/03/keeper-security-named-exemplary-in-2026-isg-buyers-guide-for-iam/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/nl/2026/09/03/keeper-security-named-exemplary-in-2026-isg-buyers-guide-for-iam/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/de/2026/09/03/keeper-security-named-exemplary-in-2026-isg-buyers-guide-for-iam/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/pl/2026/09/03/keeper-security-named-exemplary-in-2026-isg-buyers-guide-for-iam/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/zh-hans/2026/09/03/keeper-security-named-exemplary-in-2026-isg-buyers-guide-for-iam/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/it/2026/09/03/keeper-security-named-exemplary-in-2026-isg-buyers-guide-for-iam/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/fr/2026/09/03/keeper-security-named-exemplary-in-2026-isg-buyers-guide-for-iam/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/government-cloud/` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/security.html` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/resources/glossary/what-are-non-human-identities/` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/features/` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/features/secure-file-storage/` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/features/tenable-integration/` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/features/keeper-ai/` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/features/automation-commands/` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/features/privileged-cloud/` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/features/keeper-epm-agentic-ai-governance/` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/solutions/secure-ai-agents/` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/features/compliance-reports/` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/demo/secrets-manager-demo-request/` viewport \`width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no\` stops zooming
- `/blog/ja/category/news-and-events-ja/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/ja/2026/01/27/keeper-wins-2026-winter-itreview-grid-award-leader-badge-for-password-management/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/ja/2025/04/16/debunking-the-misconceptions-of-using-password-managers/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/ja/category/password-ja/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/es/category/password-es/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/es/2025/10/03/is-google-password-manager-safe/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/es/2025/04/16/debunking-the-misconceptions-of-using-password-managers/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/es/category/product-announcements-es/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/pt-br/category/product-announcements-pt-br/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/pt-br/2024/12/03/achieve-enhanced-risk-visibility-with-keepers-risk-management-dashboard/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/pt-br/2025/04/16/debunking-the-misconceptions-of-using-password-managers/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/nl/category/product-announcements-nl/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/nl/2024/12/18/2024-in-review-keeper-securitys-innovations-in-cybersecurity/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/nl/2025/04/16/debunking-the-misconceptions-of-using-password-managers/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/de/category/product-announcements-de/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/de/2025/04/15/keeper-adds-autofill-fixes-enhanced-control-and-pam-record-support-to-extension/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/de/2025/10/03/is-google-password-manager-safe/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/pl/category/product-announcements-pl/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/pl/2025/02/18/revolutionizing-privileged-access-management-with-keeperpam/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/pl/2025/04/16/debunking-the-misconceptions-of-using-password-managers/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/zh-hans/category/product-announcements-zh-hans/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/zh-hans/2025/05/29/eliminate-standing-admin-rights-and-enforce-least-privilege-policies-with-endpoint-privilege-manager/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/zh-hans/2025/04/16/debunking-the-misconceptions-of-using-password-managers/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/it/2025/04/16/debunking-the-misconceptions-of-using-password-managers/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/fr/2025/04/16/debunking-the-misconceptions-of-using-password-managers/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/it/category/product-announcements-it/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/it/2024/12/03/achieve-enhanced-risk-visibility-with-keepers-risk-management-dashboard/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/fr/category/product-announcements-fr/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/fr/2024/12/18/2024-in-review-keeper-securitys-innovations-in-cybersecurity/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/nl/author/aranza/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/zh-hans/author/aranza/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/fr/author/user/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/ja/author/user/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/de/category/cybersecurity-de/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/fr/category/appareil-mobile/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- `/blog/pt-br/category/password-pt-br/` viewport \`width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no\` stops zooming
- and 189 more pages in AUDIT.html

</details>

## major SITE-07 At least 7 links and buttons on 9 pages have nothing for a screen reader to say

**Why it matters.** A blind visitor hears only "link" or "button", with no idea where it goes or what it does. Accessibility audits flag it under WCAG 4.1.2 \(Name, Role, Value\), the standard that laws such as the ADA and the European Accessibility Act are commonly measured by; an automated read shows a likely barrier, not a legal finding, so a person confirms each one.

**Likely fix.** Give each one words: visible text, an aria-label, or an alt on the image inside it \(an icon link to a cart: aria-label="Cart"\).

<details open>
<summary>7 links and buttons listed</summary>

- `/secrets-manager.html` \`\<button type="button"\>\`, on 7 pages: /secrets-manager.html, /features/risk-management-dashboard/, /security.html and 4 more
- `/roi-calculator-password-manager/` \`\<a href="\#ROICalculator"\>\`
- `/msp-academy.html` \`\<a `` href="https://www.keeper.io/hubfs/PDF/Keeper-PWM-ITAdmid…` ``
- `/msp-academy.html` \`\<a `` href="https://start.keeper.io/2019-ponemon-report">` ``
- `/msp-academy.html` \`\<a href="/resources/msp-mssp-unlock-value-with-keepermsp-pa…\`
- `/msp-academy.html` \`\<a href="/assets/pdf/Keeper-Managed-Service-Provider-Tech-W…\`
- `/msp-academy.html` \`\<a href="/assets/pdf/Ovum-Market-Radar-Keeper-Enterprise.pd…\`

Up to 14 more may not be listed: the crawl notes the first 5 different ones on each page \(/msp-academy.html showed 19, 5 listed\).

Each line stands for every one alike on a page: /security.html has 2 like the one listed.

</details>

## major SITE-08 4 form fields on 3 pages have no label

**Why it matters.** A screen reader announces a field with no label as "edit text", so a blind visitor cannot tell what to type. Accessibility audits fail it.

**Likely fix.** Give each field a \<label for="its id"\> \(each id used once on the page\), or an aria-label.

<details open>
<summary>4 form fields</summary>

- `/features/password-generator/` \`\<textarea id="strongPassword"\>\`, on 2 pages: /features/password-generator/, /features/passphrase-generator/
- `/features/password-generator/` \`\<input type="range"\>\`, on 2 pages: /features/password-generator/, /features/passphrase-generator/
- `/roi-calculator-password-manager/` \`\<input id="employeesCount"\>\`
- `/roi-calculator-password-manager/` \`\<input id="timesPerYear"\>\`

</details>

## major SITE-33 3 links to other sites lead nowhere: the pages are gone

**Why it matters.** Sites move and close: a visitor who follows one of these links meets an error page, or nothing at all, on someone else's site, reached from this one.

**Likely fix.** Point each link at where the page lives now, or take it out. The suite's link report asks every one again on each run, and fails when one that answered stops.

<details open>
<summary>3 links</summary>

- `https://docs.keeper.io/keeper-documentation-jp/` answered 404; linked from /blog/ja/2026/09/03/keeper-security-named-exemplary-in-2026-isg-buyers-guide-for-iam/, /blog/ja/category/news-and-events-ja/, /blog/ja/2026/01/27/keeper-wins-2026-winter-itreview-grid-award-leader-badge-for-password-management/, /blog/ja/2025/04/16/debunking-the-misconceptions-of-using-password-managers/, /blog/ja/category/password-ja/ and 7 more
- `https://docs.keeper.io/en/v/user-guides/web-vault` answered 404; linked from /customer-success-portal/
- `https://docs.keeper.io/en/v/release-notes/enterprise/admin-console/admin-console-16.16.0` answered 404; linked from /blog/nl/2024/12/18/2024-in-review-keeper-securitys-innovations-in-cybersecurity/, /blog/fr/2024/12/18/2024-in-review-keeper-securitys-innovations-in-cybersecurity/

</details>

## minor SITE-02 1 broken link in a closed part of the page: the site links to an address that answers an error

**Why it matters.** Each is linked only from a part of the page that is closed when it loads \(a menu, a tab, an answer that opens on a click, a link shown on hover\): the crawler cannot tell whether a visitor opens it, so these are said apart, and as minor. Opened and followed, each reaches an error instead of the page promised.

**Likely fix.** Point each link at a page that exists, or bring the page back \(or redirect its old address to where it went\).

<details open>
<summary>1 link</summary>

- `/family-password-manager/` answered 404; linked from /features/emergency-access/

</details>

## minor SITE-17 95 pages have no description for search results

**Why it matters.** Search results show the description under the title; without one, the search engine picks a line of the page, often the menu or a cookie notice.

**Likely fix.** Give each page a \<meta name="description"\> of a sentence or two saying what it offers.

<details>
<summary>95 pages</summary>

- `/blog/category/whats-new-with-keeper/` no meta description
- `/blog/ru/category/comparison-ru/` no meta description
- `/blog/ru/author/aleksandra/` no meta description
- `/blog/category/privileged-access-management/` no meta description
- `/blog/ru/category/product-security-ru/` no meta description
- `/blog/ja/category/news-and-events-ja/` no meta description
- `/blog/ja/category/password-ja/` no meta description
- `/blog/es/category/password-es/` no meta description
- `/blog/es/category/product-announcements-es/` no meta description
- `/blog/pt-br/category/product-announcements-pt-br/` no meta description
- `/blog/nl/category/product-announcements-nl/` no meta description
- `/blog/de/category/product-announcements-de/` no meta description
- `/blog/pl/category/product-announcements-pl/` no meta description
- `/blog/zh-hans/category/product-announcements-zh-hans/` no meta description
- `/blog/it/category/product-announcements-it/` no meta description
- `/blog/fr/category/product-announcements-fr/` no meta description
- `/blog/fr/author/user/` no meta description
- `/blog/ja/author/user/` no meta description
- `/blog/de/category/cybersecurity-de/` no meta description
- `/blog/fr/category/appareil-mobile/` no meta description
- `/blog/pt-br/category/password-pt-br/` no meta description
- `/blog/nl/category/password-nl/` no meta description
- `/blog/pl/category/password-pl/` no meta description
- `/blog/zh-hans/category/password-zh-hans/` no meta description
- `/blog/it/category/password-it/` no meta description
- `/blog/es/author/user/` no meta description
- `/blog/it/author/user/` no meta description
- `/blog/ja/category/product-security-ja/` no meta description
- `/blog/ru/author/darren/` no meta description
- `/blog/de/category/privileged-access-management-de/` no meta description
- `/blog/fr/category/privileged-access-management-fr/` no meta description
- `/blog/category/mobile-device/` no meta description
- `/blog/es/category/privileged-access-management-es/` no meta description
- `/blog/pt-br/category/privileged-access-management-pt-br/` no meta description
- `/blog/nl/category/privileged-access-management-nl/` no meta description
- `/blog/ru/category/privileged-access-management-ru/` no meta description
- `/blog/pl/category/privileged-access-management-pl/` no meta description
- `/blog/zh-hans/category/privileged-access-management-zh-hans/` no meta description
- `/blog/it/category/privileged-access-management-it/` no meta description
- `/blog/ja/author/darren/` no meta description
- `/blog/nl/author/darren/` no meta description
- `/blog/zh-hans/author/darren/` no meta description
- `/blog/fr/author/darren/` no meta description
- `/blog/category/privileged-access-management/page/6/` no meta description
- `/blog/ja/category/password-ja/page/8/` no meta description
- `/blog/es/category/password-es/page/7/` no meta description
- `/blog/de/category/cybersecurity-de/page/21/` no meta description
- `/blog/pt-br/category/password-pt-br/page/7/` no meta description
- `/blog/nl/category/password-nl/page/7/` no meta description
- `/blog/pl/category/password-pl/page/7/` no meta description
- `/blog/zh-hans/category/password-zh-hans/page/7/` no meta description
- `/blog/it/category/password-it/page/7/` no meta description
- `/blog/de/category/privileged-access-management-de/page/6/` no meta description
- `/blog/fr/category/privileged-access-management-fr/page/6/` no meta description
- `/blog/es/category/privileged-access-management-es/page/6/` no meta description
- `/blog/pt-br/category/privileged-access-management-pt-br/page/6/` no meta description
- `/blog/nl/category/privileged-access-management-nl/page/6/` no meta description
- `/blog/ru/category/privileged-access-management-ru/page/6/` no meta description
- `/blog/pl/category/privileged-access-management-pl/page/6/` no meta description
- `/blog/zh-hans/category/privileged-access-management-zh-hans/page/6/` no meta description
- `/blog/it/category/privileged-access-management-it/page/6/` no meta description
- `/blog/es/author/darren/` no meta description
- `/blog/pt-br/author/darren/` no meta description
- `/blog/de/author/darren/` no meta description
- `/blog/pl/author/darren/` no meta description
- `/blog/it/author/darren/` no meta description
- `/blog/ja/category/password-ja/page/7/` no meta description
- `/blog/de/category/cybersecurity-de/page/20/` no meta description
- `/blog/ja/author/aleksandra/` no meta description
- `/blog/nl/author/aleksandra/` no meta description
- `/blog/zh-hans/author/aleksandra/` no meta description
- `/blog/fr/author/aleksandra/` no meta description
- `/blog/es/category/password-es/page/4/` no meta description
- `/blog/pt-br/category/password-pt-br/page/4/` no meta description
- `/blog/nl/category/password-nl/page/4/` no meta description
- `/blog/pl/category/password-pl/page/4/` no meta description
- `/blog/zh-hans/category/password-zh-hans/page/4/` no meta description
- `/blog/it/category/password-it/page/4/` no meta description
- `/blog/es/author/aleksandra/` no meta description
- `/blog/pt-br/author/aleksandra/` no meta description
- `/blog/de/author/aleksandra/` no meta description
- `/blog/pl/author/aleksandra/` no meta description
- `/blog/it/author/aleksandra/` no meta description
- `/blog/de/category/cybersecurity-de/page/3/` no meta description
- `/blog/category/privileged-access-management/page/4/` no meta description
- `/blog/de/category/privileged-access-management-de/page/4/` no meta description
- `/blog/fr/category/privileged-access-management-fr/page/4/` no meta description
- `/blog/es/category/privileged-access-management-es/page/4/` no meta description
- `/blog/pt-br/category/privileged-access-management-pt-br/page/4/` no meta description
- `/blog/nl/category/privileged-access-management-nl/page/4/` no meta description
- `/blog/ru/category/privileged-access-management-ru/page/4/` no meta description
- `/blog/pl/category/privileged-access-management-pl/page/4/` no meta description
- `/blog/zh-hans/category/privileged-access-management-zh-hans/page/4/` no meta description
- `/blog/it/category/privileged-access-management-it/page/4/` no meta description
- `/blog/ja/category/password-ja/page/3/` no meta description

</details>

## minor SITE-04 29 different pages share 5 titles

**Why it matters.** Search results, bookmarks and browser tabs show the title: pages that share one can't be told apart, and a page without one shows its address.

**Likely fix.** Give each page a title of its own that names what it shows \(in a single-page app, set it on each route\).

<details>
<summary>29 pages</summary>

- `/blog/` titled \`Keeper Security Blog - Cybersecurity 101 and Product Updates\`, shows \`Latest Keeper Blogs\`
- `/blog/es-la/` titled \`Keeper Security Blog - Cybersecurity 101 and Product Updates\`, shows \`Latest Keeper Blogs\`
- `/blog/ru/` titled \`Keeper Security Blog - Cybersecurity 101 and Product Updates\`, shows \`Последние блоги Keeper\`
- `/blog/pt-br/` titled \`Keeper Security Blog - Cybersecurity 101 and Product Updates\`, shows \`Blogues mais recentes do Keeper\`
- `/blog/page/62/` titled \`Keeper Security Blog - Cybersecurity 101 and Product Updates\`, shows \`Latest Keeper Blogs\`
- `/blog/ru/page/40/` titled \`Keeper Security Blog - Cybersecurity 101 and Product Updates\`, shows \`Последние блоги Keeper\`
- `/blog/pt-br/page/40/` titled \`Keeper Security Blog - Cybersecurity 101 and Product Updates\`, shows \`Blogues mais recentes do Keeper\`
- `/blog/page/61/` titled \`Keeper Security Blog - Cybersecurity 101 and Product Updates\`, shows \`Latest Keeper Blogs\`
- `/blog/ru/page/39/` titled \`Keeper Security Blog - Cybersecurity 101 and Product Updates\`, shows \`Последние блоги Keeper\`
- `/blog/pt-br/page/39/` titled \`Keeper Security Blog - Cybersecurity 101 and Product Updates\`, shows \`Blogues mais recentes do Keeper\`
- `/blog/page/3/` titled \`Keeper Security Blog - Cybersecurity 101 and Product Updates\`, shows \`Latest Keeper Blogs\`
- `/blog/ru/page/3/` titled \`Keeper Security Blog - Cybersecurity 101 and Product Updates\`, shows \`Последние блоги Keeper\`
- `/blog/pt-br/page/3/` titled \`Keeper Security Blog - Cybersecurity 101 and Product Updates\`, shows \`Blogues mais recentes do Keeper\`
- `/blog/category/privileged-access-management/` titled \`PAM Archives - Keeper Security Blog - Cybersecurity News \& Product Updates\`, shows \`Latest Keeper Blogs\`
- `/blog/de/category/privileged-access-management-de/` titled \`PAM Archives - Keeper Security Blog - Cybersecurity News \& Product Updates\`, shows \`Neue Keeper-Blogbeiträge\`
- `/blog/fr/category/privileged-access-management-fr/` titled \`PAM Archives - Keeper Security Blog - Cybersecurity News \& Product Updates\`, shows \`Derniers articles du blog de Keeper\`
- `/blog/es/category/privileged-access-management-es/` titled \`PAM Archives - Keeper Security Blog - Cybersecurity News \& Product Updates\`, shows \`Últimas entradas del blog de Keeper\`
- `/blog/pt-br/category/privileged-access-management-pt-br/` titled \`PAM Archives - Keeper Security Blog - Cybersecurity News \& Product Updates\`, shows \`Blogues mais recentes do Keeper\`
- `/blog/nl/category/privileged-access-management-nl/` titled \`PAM Archives - Keeper Security Blog - Cybersecurity News \& Product Updates\`, shows \`Nieuwste Keeper-blogs\`
- `/blog/ru/category/privileged-access-management-ru/` titled \`PAM Archives - Keeper Security Blog - Cybersecurity News \& Product Updates\`, shows \`Последние блоги Keeper\`
- `/blog/pl/category/privileged-access-management-pl/` titled \`PAM Archives - Keeper Security Blog - Cybersecurity News \& Product Updates\`, shows \`Najnowsze wpisy na blogu Keeper\`
- `/blog/zh-hans/category/privileged-access-management-zh-hans/` titled \`PAM Archives - Keeper Security Blog - Cybersecurity News \& Product Updates\`, shows \`Keeper 最新博客\`
- `/blog/it/category/privileged-access-management-it/` titled \`PAM Archives - Keeper Security Blog - Cybersecurity News \& Product Updates\`, shows \`Ultimi blog di Keeper\`
- `/ai-agent-blast-radius-calculator/` titled \`AI Agent Blast Radius Calculator – Keeper Security\`, shows \`What's your AI agent blast radius?\`
- `/ai-agent-blast-radius-calculator/calculator/` titled \`AI Agent Blast Radius Calculator – Keeper Security\`, shows \` \`
- `/blog/es/category/privileged-access-management-es/page/6/` titled \`PAM Archives - Página 6 de 6 - Keeper Security Blog - Cybersecurity News \& Product Updates\`, shows \`Últimas entradas del blog de Keeper\`
- `/blog/pt-br/category/privileged-access-management-pt-br/page/6/` titled \`PAM Archives - Página 6 de 6 - Keeper Security Blog - Cybersecurity News \& Product Updates\`, shows \`Blogues mais recentes do Keeper\`
- `/blog/es/category/privileged-access-management-es/page/4/` titled \`PAM Archives - Página 4 de 6 - Keeper Security Blog - Cybersecurity News \& Product Updates\`, shows \`Últimas entradas del blog de Keeper\`
- `/blog/pt-br/category/privileged-access-management-pt-br/page/4/` titled \`PAM Archives - Página 4 de 6 - Keeper Security Blog - Cybersecurity News \& Product Updates\`, shows \`Blogues mais recentes do Keeper\`

</details>

## minor SITE-03 8 of the site's own links redirect before they arrive

**Why it matters.** Every click on one of these links costs an extra round trip before the page starts loading, and search engines see one page at two addresses.

**Likely fix.** Link to each page's final address \(with or without its trailing slash, as the server serves it\).

<details open>
<summary>8 links</summary>

- `/features/password-generator.html` 301 to /features/password-generator/
- `/threats/what-is-phishing.html` 301 to /threats/what-is-phishing/
- `/get_extension.html` 301 to /features/browser-extension/
- `/pam-free-trial/` 301 to /trial/pam-free-trial/
- `/webinars.html` 301 to /resources/webinars/
- `/request-demo.html` 301 to /demo/request-demo/
- `/cmmc/` 301 to /compliance/cmmc/
- `/pricing.html` 301 to /pricing/business-and-enterprise.html

</details>

## minor SITE-03 2 of the site's own links in a closed part of the page redirect before they arrive

**Why it matters.** Each is linked only from a part of the page that is closed when it loads \(a menu, a tab, an answer that opens on a click, a link shown on hover\): the crawler cannot tell whether a visitor opens it, so these are said apart, and as minor. Every click on one of these links costs an extra round trip before the page starts loading, and search engines see one page at two addresses.

**Likely fix.** Link to each page's final address \(with or without its trailing slash, as the server serves it\).

<details open>
<summary>2 links</summary>

- `/keeper-free-trial/` 301 to /trial/keeper-free-trial/
- `/start-msp-trial.html` 301 to /trial/start-msp-trial/

</details>

## minor SITE-41 2 form fields on 3 pages have no visible label, only a placeholder

**Why it matters.** A screen reader reads the placeholder out, so the field is named; but the placeholder vanishes once typing starts, so a visitor who looks back cannot see what the field was for, and placeholder text is often too faint to read. Accessibility audits flag it.

**Likely fix.** Give each field a visible \<label for="its id"\>; keep the placeholder, if at all, as an example of what to type.

<details open>
<summary>2 form fields</summary>

- `/free-data-breach-scan.html` \`\<input name="scan\_email"\>\`, on 2 pages: /free-data-breach-scan.html, /data-breach-scan-for-business/
- `/passkeys-directory/` \`\<input id="searchBox"\>\`

</details>

## minor SITE-15 2 pages have no main heading

**Why it matters.** Screen reader users jump to the h1 to learn what a page is, and search engines read it as the page's subject; none, or several competing, says neither.

**Likely fix.** Give each page one h1 naming what it shows; the site's name in the header is not it.

<details open>
<summary>2 pages</summary>

- `/` no h1 with words shown
- `/ai-agent-blast-radius-calculator/calculator/` no h1 with words shown

</details>

## minor SITE-13 1 image on 1 page has no alt text

**Why it matters.** A screen reader reads the file name instead, or nothing; search engines lose the words that say what the image shows.

**Likely fix.** Add alt="what the image shows"; for an image that is decoration only, alt="".

<details open>
<summary>1 image</summary>

- `/reports/uk-cybersecurity-census-report-2022/` \`\<img src="/assets/images/pages/reports/cybersecurity-census…\`

</details>

## info SITE-40 739 scripts and style sheets from other sites' hosts did not load, and 210 errors came from a source the crawl could not tell, on 289 pages, as seen by an automated visitor: unconfirmed \(other sites may block automated visitors\); check in a browser

**Why it matters.** Another site's script or style sheet \(a video player, a widget, an analytics tag\) failed while the crawler read the page. Many such services refuse or slow an automated visitor while they serve a person, so this is not said as a fact about the site; when it also fails in a browser, the part of the page that uses it does not work. An error whose stack names no script cannot be traced to the site or to another site: "A network error occurred." is the browser's own word for a request that failed, a…

**Likely fix.** Open the page in an ordinary browser with the developer tools' network tab and console. If the request fails there too, check the embed's address and the account with that service, or remove the embed. An error that shows in the console there too names its script there: fix it at that line.

<details>
<summary>289 pages</summary>

- `/` 1 request: `https://www.keepersecurity.com/8ff6c604-e9c1-456b-968b-3b439b4d8665` \(csp\); 2 errors of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/get-keeper.html` 1 request: `https://www.keepersecurity.com/7d918ec6-ec70-469d-a285-cdacc49b02c6` \(csp\); 1 error of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/support.html` 1 request: `https://www.keepersecurity.com/b13be3f2-08e4-4ad9-b592-130ef018c478` \(csp\); 2 errors of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/blog/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/2025/02/19/the-top-6-pam-features-that-you-actually-need/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/2024/02/23/why-organizations-need-automated-password-rotation/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/partners.html` 1 request: `https://www.keepersecurity.com/5ed73e04-b593-4645-b01b-c900cf38a447` \(csp\); 1 error of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/blog/2026/09/23/why-critical-infrastructure-needs-zero-trust-security/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/enterprise.html` 1 request: `https://www.keepersecurity.com/edaf4e93-9e6e-4a33-8b97-23c8084d81e6` \(csp\); 1 error of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/features/password-generator/` 1 request: `https://www.keepersecurity.com/fa49a8db-260e-4c2b-ae42-e3e2c0a69733` \(csp\); 1 error of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/business.html` 1 request: `https://www.keepersecurity.com/4762e3e4-ee3f-47c0-8e6e-32bd2573978a` \(csp\); 1 error of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/solutions/remote-browser-isolation/` 1 request: `https://www.keepersecurity.com/a082a38a-5b97-4e2f-b421-3a3c8560f52d` \(csp\); 1 error of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/blog/es-la/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/category/whats-new-with-keeper/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/personal.html` 1 request: `https://www.keepersecurity.com/04fce44a-59b4-47c9-bfe9-9b1be482adc2` \(csp\); 2 errors of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/features/passphrase-generator/` 1 request: `https://www.keepersecurity.com/2e4ad3dd-6d80-46b7-b7be-533f767e6eee` \(csp\); 1 error of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/resources/case-studies/` 1 request: `https://www.keepersecurity.com/1adb50b1-cea6-40fd-b83b-0aeeb8cd7589` \(csp\); 1 error of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/resources/white-papers/` 1 request: `https://www.keepersecurity.com/36be1ec4-b132-4aa5-b881-a5970207e729` \(csp\); 2 errors of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/resources/glossary/what-is-a-master-password/` 1 request: `https://www.keepersecurity.com/362a3970-a136-4c64-ac99-4c39f2482393` \(csp\); 2 errors of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/family-plan.html` 1 request: `https://www.keepersecurity.com/4649a511-25d6-4266-b285-41f179a1f3b2` \(csp\); 2 errors of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/resources/public-sector/` 1 request: `https://www.keepersecurity.com/76238f2b-b2e3-48bb-ba1c-3a46f9eb5203` \(csp\); 1 error of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/privileged-access-management/` 1 request: `https://www.keepersecurity.com/981c338d-7337-41ee-a906-e31acf0b4f01` \(csp\); 2 errors of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/vs/cyberark/` 1 request: `https://www.keepersecurity.com/8f780ab8-8d66-46ba-b1a4-55afb360e1a6` \(csp\); 1 error of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/endpoint-privilege-management/` 1 request: `https://www.keepersecurity.com/cfe32bb3-779d-41cd-b124-7d6554c11bd9` \(csp\); 2 errors of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/secrets-manager.html` 1 request: `https://www.keepersecurity.com/1c338f6f-2bc2-4f6c-8e1c-dea860d4bad8` \(csp\); 1 error of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/solutions/remote-privileged-access-management/` 1 request: `https://www.keepersecurity.com/07d87d22-534d-4852-b9b1-8a477f690346` \(csp\); 2 errors of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/blog/author/kaylee/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/msp-password-manager.html` 1 request: `https://www.keepersecurity.com/82eae860-636b-4fb5-af24-e2a98057a149` \(csp\); 1 error of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/msp-privileged-access-manager/` 1 request: `https://www.keepersecurity.com/09f5a7cc-5bc5-4db9-b75b-07fe9b9fa6d5` \(csp\); 2 errors of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/trial/pam-msp-free-trial/` 1 request: `https://www.keepersecurity.com/403a6684-67e8-4431-bd98-11c694067981` \(csp\); 2 errors of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/blog/ru/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/ru/2026/07/08/secure-access-in-slack-teams-jira-and-servicenow-with-keeper/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/ru/2026/09/02/how-to-reduce-your-cloud-attack-surface-by-eliminating-standing-privileges/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/ru/category/comparison-ru/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/ru/2026/09/03/keeper-security-named-exemplary-in-2026-isg-buyers-guide-for-iam/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/reports/isg-buyers-guide/` 1 request: `https://www.keepersecurity.com/ce46eb5f-bbea-4274-96b6-c4094d872947` \(csp\); 2 errors of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/blog/ru/author/aleksandra/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/resources/glossary/what-is-multi-factor-authentication/` 1 request: `https://www.keepersecurity.com/08af7e3b-09da-490d-832d-457d3de824c7` \(csp\); 2 errors of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/features/risk-management-dashboard/` 1 request: `https://www.keepersecurity.com/d497b92d-4ade-40fa-ada2-e4b97c99ecbc` \(csp\); 1 error of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/blog/category/privileged-access-management/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/ru/category/product-security-ru/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/industries/manufacturing/` 1 request: `https://www.keepersecurity.com/333d7bc7-2753-4480-89e8-f5a931701bef` \(csp\); 1 error of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/blog/ja/2026/09/03/keeper-security-named-exemplary-in-2026-isg-buyers-guide-for-iam/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/es/2026/09/03/keeper-security-named-exemplary-in-2026-isg-buyers-guide-for-iam/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/pt-br/2026/09/03/keeper-security-named-exemplary-in-2026-isg-buyers-guide-for-iam/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/nl/2026/09/03/keeper-security-named-exemplary-in-2026-isg-buyers-guide-for-iam/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/de/2026/09/03/keeper-security-named-exemplary-in-2026-isg-buyers-guide-for-iam/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/pl/2026/09/03/keeper-security-named-exemplary-in-2026-isg-buyers-guide-for-iam/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/zh-hans/2026/09/03/keeper-security-named-exemplary-in-2026-isg-buyers-guide-for-iam/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/it/2026/09/03/keeper-security-named-exemplary-in-2026-isg-buyers-guide-for-iam/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/fr/2026/09/03/keeper-security-named-exemplary-in-2026-isg-buyers-guide-for-iam/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/government-cloud/` 1 request: `https://www.keepersecurity.com/f07eefbf-3367-45f5-bdb3-40f9a68b4684` \(csp\); 1 error of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/security.html` 1 request: `https://www.keepersecurity.com/7bdac21c-3bb1-49db-89d7-8fb3cfc0725b` \(csp\); 2 errors of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/resources/glossary/what-are-non-human-identities/` 1 request: `https://www.keepersecurity.com/bcb9a65c-f767-491b-8ff7-ab0f2f1172f2` \(csp\); 2 errors of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/features/` 1 request: `https://www.keepersecurity.com/928e33d8-9b15-42e9-9d7c-8e823c6e286e` \(csp\); 2 errors of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/features/secure-file-storage/` 1 request: `https://www.keepersecurity.com/53eada75-80ef-4c7f-a7c2-f4d4e1535acc` \(csp\); 2 errors of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/features/tenable-integration/` 1 request: `https://www.keepersecurity.com/9fcba1af-2edc-4acf-92ed-ef6f1566ec35` \(csp\); 2 errors of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/features/keeper-ai/` 1 request: `https://www.keepersecurity.com/b9337405-08d3-43c7-8ab5-17abf9b82319` \(csp\); 2 errors of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/features/automation-commands/` 1 request: `https://www.keepersecurity.com/1b9a7835-481a-4596-974e-b12d68139a6a` \(csp\); 1 error of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/features/privileged-cloud/` 1 request: `https://www.keepersecurity.com/1ecb0de7-1cfe-47d3-bb7e-c81d8f114a9a` \(csp\); 2 errors of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/features/keeper-epm-agentic-ai-governance/` 1 request: `https://www.keepersecurity.com/7b61b192-59cd-480d-9207-aa7d25464e95` \(csp\); 2 errors of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/solutions/secure-ai-agents/` 1 request: `https://www.keepersecurity.com/a11a0be1-503f-40e3-8a86-0db8161d4cb6` \(csp\); 1 error of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/features/compliance-reports/` 1 request: `https://www.keepersecurity.com/d6d7af5f-67b4-46c1-bd63-cfc722a56f36` \(csp\); 2 errors of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/demo/secrets-manager-demo-request/` 1 request: `https://www.keepersecurity.com/c051645d-7f18-45fe-a58a-a719d5c9b4b7` \(csp\); 1 error of no known source: Failed to read the 'serviceWorker' property from 'Navigator': Service worker is disabled because the context is sandboxe
- `/blog/ja/category/news-and-events-ja/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/ja/2026/01/27/keeper-wins-2026-winter-itreview-grid-award-leader-badge-for-password-management/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/ja/2025/04/16/debunking-the-misconceptions-of-using-password-managers/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/ja/category/password-ja/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/es/category/password-es/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/es/2025/10/03/is-google-password-manager-safe/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/es/2025/04/16/debunking-the-misconceptions-of-using-password-managers/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/es/category/product-announcements-es/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/pt-br/category/product-announcements-pt-br/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/pt-br/2024/12/03/achieve-enhanced-risk-visibility-with-keepers-risk-management-dashboard/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/pt-br/2025/04/16/debunking-the-misconceptions-of-using-password-managers/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/nl/category/product-announcements-nl/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/nl/2024/12/18/2024-in-review-keeper-securitys-innovations-in-cybersecurity/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/nl/2025/04/16/debunking-the-misconceptions-of-using-password-managers/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/de/category/product-announcements-de/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/de/2025/04/15/keeper-adds-autofill-fixes-enhanced-control-and-pam-record-support-to-extension/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/de/2025/10/03/is-google-password-manager-safe/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/pl/category/product-announcements-pl/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/pl/2025/02/18/revolutionizing-privileged-access-management-with-keeperpam/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/pl/2025/04/16/debunking-the-misconceptions-of-using-password-managers/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/zh-hans/category/product-announcements-zh-hans/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/zh-hans/2025/05/29/eliminate-standing-admin-rights-and-enforce-least-privilege-policies-with-endpoint-privilege-manager/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/zh-hans/2025/04/16/debunking-the-misconceptions-of-using-password-managers/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/it/2025/04/16/debunking-the-misconceptions-of-using-password-managers/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/fr/2025/04/16/debunking-the-misconceptions-of-using-password-managers/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/it/category/product-announcements-it/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/it/2024/12/03/achieve-enhanced-risk-visibility-with-keepers-risk-management-dashboard/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/fr/category/product-announcements-fr/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/fr/2024/12/18/2024-in-review-keeper-securitys-innovations-in-cybersecurity/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/nl/author/aranza/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/zh-hans/author/aranza/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/fr/author/user/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/ja/author/user/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/de/category/cybersecurity-de/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/fr/category/appareil-mobile/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- `/blog/pt-br/category/password-pt-br/` 4 requests: `tag.demandbase.com/7d700043405ad9c8.min.js` \(csp\), cdn.mgln.ai/pixel.min.js \(csp\), d34r8q7sht0t9k.cloudfront.net/tag.js \(csp\), bzrcdn.openai.com/sdk/oaiq.min.js \(csp\)
- and 189 more pages in AUDIT.html

</details>

## info SITE-39 2 links to other sites did not answer the crawler: unconfirmed \(many sites block automated visitors\); open each in a browser

**Why it matters.** Many sites block an automated visitor, or answer it slowly, while they answer a person: the crawler cannot tell a site that turned it away from one that is down, so this is not said as a fact.

**Likely fix.** Open each in a browser. If it does not load there either, point the link at where the page lives now, or take it out.

<details open>
<summary>2 links</summary>

- `https://www.usnews.com/360-reviews/password-managers/keeper` no answer in time, asked twice; linked from /family-plan.html, /student-discount-50off.html, /id-me-verification.html
- `https://www.usnews.com/360-reviews/privacy/password-managers/keeper` no answer in time, asked twice; linked from /personal.html, /family-plan.html

</details>

Read by Suite Builder's crawler, which identifies itself in its User-Agent and obeys robots.txt.
