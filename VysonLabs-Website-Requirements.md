# Vyson Labs Limited Website Requirements

**Document purpose:** Define the content, design, technical, deployment, and acceptance requirements for the public website of **Vyson Labs Limited**.

**Primary objective:** Publish a credible, functional company website at **https://vysonlabs.com** that supports a fresh Apple Developer Program organisation enrolment.

**Hosting platform:** Netlify  
**Domain:** `vysonlabs.com`  
**Company:** Vyson Labs Limited  
**Company number:** 819944  
**Country:** Ireland  
**Primary contact email:** `info@vysonlabs.com`  
**Document status:** Initial implementation requirements  
**Priority:** High

---

## 1. Background

Apple withdrew the previous Apple Developer Program enrolment because the organisation website was not publicly available, functional, or sufficiently complete.

Apple requires an organisation website to:

- Be publicly accessible.
- Be functional.
- Use a domain associated with the organisation.
- Contain meaningful company content.
- Not be only a social-media page.
- Not be a registrar parking page.
- Not contain only minimal or “coming soon” content.

The new website must clearly demonstrate that `vysonlabs.com` belongs to and represents **Vyson Labs Limited**.

---

## 2. Website Goals

The website must:

1. Establish Vyson Labs Limited as a legitimate Irish technology company.
2. Clearly describe what the company does.
3. Present current and planned digital products.
4. Provide a professional company contact method using the company domain.
5. Provide basic legal and privacy information.
6. Work well on desktop, tablet, and mobile.
7. Be publicly accessible through HTTPS.
8. Be suitable for review by Apple’s enrolment verification team.
9. Be easy to maintain and deploy through Netlify.
10. Avoid unnecessary complexity, databases, accounts, or backend services.

---

## 3. Target Audience

The website is intended for:

- Apple Developer Program reviewers.
- Potential app users and parents.
- Future business partners.
- Vendors and service providers.
- Prospective employees or contractors.
- Members of the public checking the company’s legitimacy.

---

## 4. Recommended Site Structure

A polished one-page website is acceptable, provided all required sections are substantial and easy to navigate.

The preferred navigation is:

- Home
- About
- Products
- Contact
- Privacy Policy

A separate Privacy Policy page is recommended.

### Required public URLs

- `https://vysonlabs.com/`
- `https://vysonlabs.com/privacy`
- `https://www.vysonlabs.com/` — redirects to the primary domain

Optional:

- `https://vysonlabs.com/terms`
- `https://vysonlabs.com/contact`

---

## 5. Page and Content Requirements

## 5.1 Header

The header must include:

- Vyson Labs logo or a clean text-based wordmark.
- Company name: **Vyson Labs**.
- Navigation links.
- A visible “Contact” link or button.
- Mobile-responsive navigation.

The header must not include:

- Broken links.
- Empty menu items.
- Links to unfinished pages.
- Social-media icons unless active profiles exist.

---

## 5.2 Hero Section

The hero section must immediately explain the company.

### Required elements

- Company name.
- Clear headline.
- One or two sentences describing the company.
- One primary call to action.
- A clean visual representing technology, learning, or digital products.

### Suggested copy

**Headline**

> Thoughtful digital products for families and everyday life.

**Supporting text**

> Vyson Labs Limited is an Irish technology company designing simple, useful, and accessible digital experiences. We are currently developing educational and personal productivity products for mobile users.

**Primary call to action**

> Explore our products

**Secondary call to action**

> Contact us

Avoid unsupported claims such as:

- “Ireland’s leading app company.”
- “Trusted by thousands.”
- “Award-winning.”
- “Used worldwide.”

---

## 5.3 About Section

The About section must explain:

- The company’s legal name.
- That it is based in Ireland.
- Its purpose.
- The type of products it develops.
- Its approach to design and technology.

### Suggested copy

> Vyson Labs Limited is an Irish technology company founded to create practical, thoughtful digital products. We focus on making technology clear, engaging, and useful for families and everyday users.
>
> Our work currently includes educational experiences for children and digital tools designed to simplify personal organisation and decision-making.

### Required company details

- **Legal name:** Vyson Labs Limited
- **Company number:** 819944
- **Country of incorporation:** Ireland
- **Business type:** Software and digital product development

Do not publish personal residential addresses unless legally required and approved.

---

## 5.4 Products Section

The Products section must contain meaningful descriptions rather than only product names.

### Product 1: LumaNest

**Status:** In development

### Suggested copy

> **LumaNest** is an educational app being designed for children aged 4–8. It aims to help young learners explore subjects such as animals, nature, space, mathematics, English, puzzles, and general knowledge through age-appropriate visual activities.

### Product details that may be included

- Intended age group: 4–8.
- Learning levels: Start, Grow, and Shine.
- Visual learning experiences.
- Flashcards and quizzes.
- Child-friendly navigation.
- Parent-conscious design.
- Status label: “In development.”

Do not claim that the app is available on the App Store until it is actually published.

### Product 2: OwnCrest

**Status:** Concept or in development

### Suggested copy

> **OwnCrest** is a privacy-first iOS app currently in development, bringing assets, loans, insurance, and ownership documents into one private wealth vault. Track property, investments, savings, physical gold, and vehicles, understand net worth, and explore future financial position with user-controlled assumptions. Features include multiple currencies, separate PIN-protected profiles, optional two-step verification, encrypted document attachments, optional iCloud backup, and password-protected vault export and import.

Only include OwnCrest if the product name and direction are sufficiently final.

### Product card requirements

Each product card should include:

- Product name.
- Short description.
- Intended audience.
- Development status.
- Relevant visual or icon.
- No broken App Store buttons.

---

## 5.5 Company Values or Approach Section

Recommended themes:

- Simplicity.
- Thoughtful design.
- Accessibility.
- Privacy-conscious development.
- Family-friendly experiences.
- Continuous learning.

### Suggested content

> **Simple by design**  
> We aim to make digital experiences easy to understand and use.
>
> **Built with purpose**  
> Every feature should solve a real user need.
>
> **Privacy-conscious**  
> We consider responsible data handling from the beginning of product design.
>
> **Accessible and inclusive**  
> We work towards experiences that can be used by people with different needs and abilities.

Avoid promising full legal or standards compliance unless it has been verified.

---

## 5.6 Contact Section

The Contact section must clearly connect the domain to the company.

### Required information

- **Company:** Vyson Labs Limited
- **Email:** `info@vysonlabs.com`
- **Location:** Ireland
- **Company number:** 819944

### Recommended contact copy

> For business, product, partnership, or company enquiries, contact us at info@vysonlabs.com.

### Contact implementation

Preferred initial implementation:

- Use a clickable `mailto:` link.
- Do not add a contact form unless submissions are properly configured and tested.
- If a Netlify form is used, display a success message and protect it against spam.

A broken contact form is worse than a working email link.

---

## 5.7 Footer

The footer must include:

- `© 2026 Vyson Labs Limited`
- Company number: 819944
- Ireland
- Contact email.
- Privacy Policy link.
- Terms link if a Terms page exists.

### Suggested footer

> © 2026 Vyson Labs Limited. Registered in Ireland. Company No. 819944.

---

## 6. Privacy Policy Requirements

A Privacy Policy page is required because the website will represent a software company and may later support mobile applications.

The first version should accurately describe the current website.

### It must cover

1. Identity of the website operator.
2. Contact email.
3. Information collected directly from visitors.
4. Hosting and technical logs.
5. Cookies.
6. Contact enquiries.
7. Third-party services.
8. Data retention.
9. User rights.
10. Changes to the policy.
11. Effective date.

### Important accuracy requirements

- Do not state that no data is collected if Netlify or analytics services collect technical logs.
- Do not claim GDPR compliance as a blanket statement.
- Do not mention analytics unless analytics is actually installed.
- Do not use advertising or tracking cookies for the first release.
- Do not add Google Analytics before the Apple enrolment unless there is a clear need and consent handling is implemented.

### Recommended first-release privacy approach

- No advertising.
- No behavioural tracking.
- No newsletter.
- No user registration.
- No database.
- No contact form, or a simple email-based contact method.
- Only essential hosting and security logs.

The app-specific privacy policy for LumaNest should be prepared separately before App Store submission.

---

## 7. Terms of Use Requirements

A short Terms of Use page is recommended but not mandatory for the first Apple enrolment website.

It may include:

- Informational nature of the website.
- Ownership of site content.
- Product information may change.
- No guarantee that products currently in development will be released on a specific date.
- Restrictions on unauthorised copying or misuse.
- Governing law: Ireland.
- Contact information.

The terms must not contain copied legal text from an unrelated company.

---

## 8. Design Requirements

## 8.1 Visual Direction

The website should feel:

- Modern.
- Trustworthy.
- Warm.
- Family-friendly.
- Technology-focused.
- Minimal but not empty.
- Professional enough for corporate verification.

### Recommended design language

- Clean spacing.
- Rounded cards used moderately.
- Soft abstract graphics.
- Clear typography.
- Subtle animations only.
- Strong visual hierarchy.

The design should not appear:

- Like a generic domain template.
- Like an unfinished startup landing page.
- Overly playful or childish.
- Overloaded with animations.
- AI-generated without human review.
- Like a personal portfolio belonging only to Aravind.

---

## 8.2 Branding

Initial branding must include:

- Vyson Labs wordmark.
- Favicon.
- Consistent typography.
- Consistent colour palette.
- Product-specific illustrations or icons where appropriate.

The exact logo can be introduced later, but the first release should not show a missing-image placeholder.

---

## 8.3 Responsive Behaviour

The website must support:

- Mobile widths from approximately 320 px.
- Tablets.
- Standard laptops.
- Large desktop screens.

Requirements:

- No horizontal scrolling.
- Text remains readable without zooming.
- Navigation works on mobile.
- Buttons remain easy to tap.
- Images scale correctly.
- Footer does not overlap content.
- No section is cut off.

---

## 9. Accessibility Requirements

Target practical alignment with WCAG 2.1 AA principles.

Minimum requirements:

- Semantic heading structure.
- One clear `h1`.
- Logical heading order.
- Keyboard-accessible links and controls.
- Visible keyboard focus.
- Sufficient colour contrast.
- Alternative text for meaningful images.
- Empty alt text for decorative images.
- Descriptive link labels.
- Form labels if forms are used.
- No essential information communicated by colour alone.
- Respect reduced-motion preferences.
- Use readable font sizes.
- Add a language attribute to the HTML document.

---

## 10. Technical Architecture

## 10.1 Recommended Implementation

Use a static website.

Suitable options:

- Plain HTML, CSS, and JavaScript.
- Astro.
- Eleventy.
- Vite with a lightweight frontend.
- React only if needed.

For this website, plain HTML/CSS/JavaScript or Astro is preferred because it is:

- Fast.
- Easy to deploy.
- Easy for search engines and reviewers to read.
- Less likely to fail due to client-side rendering.
- Simple to maintain.

No database or server is required.

---

## 10.2 Required Files

Minimum recommended project structure:

```text
vysonlabs-website/
├── index.html
├── privacy/
│   └── index.html
├── terms/
│   └── index.html
├── assets/
│   ├── css/
│   │   └── styles.css
│   ├── js/
│   │   └── main.js
│   ├── images/
│   └── icons/
├── favicon.ico
├── favicon.svg
├── robots.txt
├── sitemap.xml
├── netlify.toml
├── _redirects
└── README.md

If a framework is used, the final generated output must still be deployable as a static site.

10.3 Performance Requirements

Target:

Fast first load.
Minimal JavaScript.
Optimised images.
No unnecessary external libraries.
No autoplay video.
No large uncompressed backgrounds.

Recommended acceptance targets:

Lighthouse Performance: 85 or higher.
Lighthouse Accessibility: 90 or higher.
Lighthouse Best Practices: 90 or higher.
Lighthouse SEO: 90 or higher.

These are quality targets, not Apple’s formal enrolment requirements.

10.4 Browser Compatibility

Test at minimum in:

Safari on macOS.
Safari on iPhone.
Chrome on desktop.
Chrome on Android or responsive device mode.
Edge on desktop.

The core website must remain usable even if optional JavaScript fails.

11. SEO and Metadata Requirements

The home page must include:

Unique page title.
Meta description.
Canonical URL.
Open Graph title.
Open Graph description.
Open Graph image.
Favicon.
Organisation structured data.
Suggested title

Vyson Labs Limited | Thoughtful Digital Products

Suggested meta description

Vyson Labs Limited is an Irish technology company creating thoughtful educational and everyday digital products, including LumaNest.

Recommended structured data

Use JSON-LD with:

@type: Organization
name: Vyson Labs Limited
url: https://vysonlabs.com
email: info@vysonlabs.com
addressCountry: IE

Do not add social-profile URLs unless the profiles exist and are active.

12. Domain and DNS Requirements
12.1 Primary Domain

Use:

Primary: https://vysonlabs.com
Secondary: https://www.vysonlabs.com

The secondary domain must permanently redirect to the primary domain.

Either domain may be selected as primary, but the choice must be consistent across:

Netlify.
Canonical metadata.
Sitemap.
Structured data.
Apple enrolment form.

Using the root domain as primary is recommended.

12.2 Preserve Zoho Mail DNS Records

The existing company email must continue working.

Do not delete or replace existing email records, including:

Zoho MX records.
SPF TXT record.
DKIM TXT record.
DMARC TXT record, if configured.
Zoho domain verification record.

Known MX records include:

Priority 10: mx.zoho.eu
Priority 20: mx2.zoho.eu

There may also be an additional Zoho backup MX record. Confirm the active DNS zone before making changes.

Only add or modify the DNS records required for the website.

After DNS changes, test:

Incoming email.
Outgoing email.
Apple verification email delivery.
SPF.
DKIM.
DMARC, if enabled.
12.3 HTTPS

The site must:

Use HTTPS.
Have a valid certificate.
Redirect HTTP requests to HTTPS.
Have no mixed-content warnings.
Load all images, scripts, and styles over HTTPS.

Netlify-managed HTTPS should be enabled after the domain is connected.

13. Netlify Deployment Requirements
13.1 Netlify Account and Project

Create a Netlify project specifically for Vyson Labs.

Recommended project name:

vysonlabs

The initial Netlify subdomain may look like:

vysonlabs.netlify.app

This address is only for testing. Apple enrolment must use:

https://vysonlabs.com
13.2 Deployment Method

Recommended:

Create a private or public GitHub repository.
Connect the repository to Netlify.
Set the production branch to main.
Enable automatic deployment after changes are pushed.
Review the Netlify deploy preview before publishing major updates.

Alternative:

Manual drag-and-drop deployment of the static output folder.

Git-based deployment is preferred for version history and easier updates.

13.3 Build Settings

For a plain static site:

Build command: leave blank.
Publish directory: project root or dist, depending on structure.

For Astro:

Build command: npm run build
Publish directory: dist

For Vite:

Build command: npm run build
Publish directory: dist

The chosen settings must be documented in the repository README.

13.4 Redirects

Required behaviour:

HTTP redirects to HTTPS.
www.vysonlabs.com redirects to vysonlabs.com.
Missing trailing slash variants resolve consistently.
Invalid pages show a branded 404 page.

Example conceptual redirect:

https://www.vysonlabs.com/*  https://vysonlabs.com/:splat  301!

Netlify domain settings may handle the domain redirect automatically. Avoid conflicting redirect rules.

13.5 Security Headers

Recommended headers:

X-Content-Type-Options: nosniff
Referrer-Policy: strict-origin-when-cross-origin
Permissions-Policy
Content-Security-Policy
Strict-Transport-Security after HTTPS is stable
Frame protection through CSP frame-ancestors

The Content Security Policy must be tested carefully so it does not block required fonts, images, or scripts.

14. Content Quality Requirements for Apple Review

Before resubmitting, confirm that the website does not look minimal or unfinished.

It must include:

A clear company identity.
A clear explanation of the company’s activities.
At least one detailed product description.
Company contact details.
Legal company name.
Company number.
Privacy Policy.
Working navigation.
Professional presentation.

Do not publish:

“Coming soon” as the only meaningful content.
Empty product cards.
Lorem ipsum.
Placeholder images.
Broken App Store links.
Fake testimonials.
Fake customer statistics.
Unverified awards.
Non-working forms.
A registrar or hosting-provider placeholder.

Products may correctly be labelled “In development,” but the company itself must be described as active and legitimate.

15. Content Review and Approval

Before publication, the following must be reviewed:

Company information
Legal company name is exact.
Company number is correct.
Contact email works.
Country is correct.
Product descriptions are accurate.
Legal content
Privacy Policy reflects actual website behaviour.
Terms do not contain irrelevant copied wording.
No personal address is exposed unintentionally.
No unsupported compliance claims are made.
Product content
LumaNest age range is correct.
Features listed are genuinely planned.
Product development status is accurate.
No public-release claim is made before release.
16. Testing Checklist
16.1 Functional Testing
 Home page loads.
 Privacy Policy page loads.
 Terms page loads, if included.
 Header navigation works.
 Mobile menu works.
 Contact email link opens an email client.
 Logo returns to the homepage.
 No broken links exist.
 No browser console errors occur.
 Branded 404 page works.
 All images load.
 Favicon appears.
16.2 Domain Testing
 https://vysonlabs.com loads.
 http://vysonlabs.com redirects to HTTPS.
 https://www.vysonlabs.com redirects to the primary domain.
 Certificate is valid.
 No mixed content exists.
 Domain works in an incognito/private window.
 Domain works without being logged into Netlify.
16.3 Email Testing
 info@vysonlabs.com receives email.
 It can send email.
 Zoho MX records remain intact.
 SPF passes.
 DKIM passes.
 Apple verification emails are received.
16.4 Content Testing
 Legal name appears correctly.
 Company number appears correctly.
 Product descriptions are substantial.
 No placeholder copy remains.
 No false claims appear.
 No spelling or grammar issues remain.
 Privacy Policy effective date is present.
16.5 Responsive and Accessibility Testing
 iPhone-sized layout works.
 Android-sized layout works.
 Tablet layout works.
 Desktop layout works.
 Keyboard navigation works.
 Focus indicators are visible.
 Images have appropriate alt text.
 Colour contrast is acceptable.
 Text can be zoomed to 200%.
 Reduced-motion preference is respected.
17. Apple Developer Programme Resubmission Checklist

Do not resubmit immediately after the first deployment.

Recommended process:

Publish the completed website.
Connect vysonlabs.com.
Enable HTTPS.
Confirm both root and www domain behaviour.
Test the website in an incognito window.
Test it from a mobile network, not only home Wi-Fi.
Confirm email still works.
Leave the website publicly available and stable.
Recheck all company information against official records.
Submit a fresh Apple Developer Program organisation enrolment.
Use info@vysonlabs.com.
Enter the full website URL:
https://vysonlabs.com
Ensure the enrolment applicant has authority to bind the organisation to Apple’s agreements.
Keep company registration and D-U-N-S details available in case Apple requests verification.

The previous enrolment was withdrawn, so a new enrolment should be submitted after the site is ready.

18. Definition of Done

The website is complete when:

It is live at https://vysonlabs.com.
It is publicly available without login.
It uses valid HTTPS.
It clearly represents Vyson Labs Limited.
It contains substantial About, Products, Contact, and Privacy content.
It includes the legal company name and company number.
It includes a working company-domain email address.
It works on desktop and mobile.
It has no broken links, placeholder content, or unfinished sections.
Zoho email continues working.
The www version redirects correctly.
It passes the full testing checklist.
It is considered ready for a fresh Apple Developer Program enrolment.
19. Suggested Delivery Phases
Phase 1 — Essential Apple enrolment site

Deliver:

Home page.
About section.
LumaNest product section.
Contact section.
Privacy Policy.
Footer company details.
Responsive design.
Netlify deployment.
Custom domain and HTTPS.
Testing.
Phase 2 — Brand enhancement

Add:

Final logo.
Original illustrations.
Product screenshots or prototypes.
Expanded About content.
Dedicated product pages.
Terms of Use.
Improved animations.
Phase 3 — App launch preparation

Add:

App Store links.
Product support page.
App-specific Privacy Policy.
Child safety and parental information.
Help centre or FAQs.
Release notes.
Media assets.
Press or partnership contact.
20. Reference Sources
Apple Developer Program enrolment requirements:
https://developer.apple.com/help/account/membership/program-enrollment/
Apple Developer Program enrolment page:
https://developer.apple.com/programs/enroll/
Netlify custom domain documentation:
https://docs.netlify.com/manage/domains/get-started-with-domains/
Netlify HTTPS documentation:
https://docs.netlify.com/manage/domains/secure-domains-with-https/https-ssl/
Netlify external DNS documentation:
https://docs.netlify.com/manage/domains/configure-domains/configure-external-dns/
21. Implementation Notes

This document is a website implementation specification, not legal advice.

The Privacy Policy and Terms should be reviewed again before the company begins collecting user data, using analytics, operating contact forms, or publishing mobile applications.