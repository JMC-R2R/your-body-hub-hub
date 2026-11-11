# Your Body Hub: location page writer notes

**Layout name:** YBH location page (Divi, purple and lilac)
**Section order source:** https://yourbodyhub.com.au/physiotherapy-clinic-near-berwick/ (the live suburb page; same layout family as the other `/physiotherapy-clinic-near-<suburb>/` pages)
**Styling and copy tone source (approved, built by our delivery team):** https://www.yourbodyhub.com.au/services/dry-needling/ and https://yourbodyhub.com.au/services/pulmonary-conditions/
**Pages to write with this template:** Myotherapy Berwick, Remedial Massage Emerald, Remedial Massage Narre Warren.

Why two sources: the live suburb page gives the location layout (H1 "… for <Suburb> Residents", "Our … Services Near <Suburb>", the "How far is Your Body Hub from <Suburb>?" FAQ). But its copy is older and breaks AHPRA rules ("the leading physiotherapy clinic", "accelerate healing", "quickly relieve"). The two approved /services/ pages use the same components and the safe "We assess… we discuss… where appropriate" voice. Copy the layout from the suburb page and the voice from the /services/ pages. Do not copy anything from `/service/remedial-massage-near-berwick/` or `/service/remedial-massage/`. Those are an older template with outcome claims ("Alleviated Insomnia", "Lowered Blood Pressure", "Faster Injury Healing").

Fill `skeleton.html`. Every `{{...}}` is a slot. Everything else is fixed copy and must stay exactly as written. Use exactly one `<h1>`. Do not add inline style attributes, and do not add classes beyond those in the skeleton.

## Regulated health: AHPRA rules (non-negotiable)
- No testimonials, reviews, star ratings, success stories or patient quotes. The live pages carry a Google Reviews widget between "Where Funding Meets Trust" and the FAQ. It is **deliberately left out** of this template. Never add it back.
- Never promise an outcome, recovery time or number of sessions. Never say the service treats, cures, fixes, heals, eliminates or relieves a condition. Avoid "pain-free", "faster recovery" and "lasting results".
- Use the approved pattern: "we assess…", "we discuss whether … suits you", "may include", "where appropriate", "we review your response and adjust your plan".
- No superlatives or comparisons: no "best", "leading", "top", "expert", "specialist" (unless the site states the qualification) and no "No.1".
- Do not create urgency ("book now before…") and do not offer inducements.
- Name techniques only as possible inclusions, never as guaranteed.
- No clinician names, qualifications or years of experience unless the client's own site states them for that service.

## Writing style
- Australian English (assess, personalise, centre, organisation). No em or en dashes, so use commas or full stops. No Oxford comma.
- First person plural ("we", "our team"). Speak to the reader as "you".
- Use plain, warm, specific sentences. Paragraphs run 2 to 4 sentences.
- No invented facts. Use only the facts listed below, in their own words or closely paraphrased.

## Section by section

| # | Section (class) | Purpose | Budget | Heading pattern |
|---|---|---|---|---|
| 1 | Hero `pg-hero yb-hero` | Cream rounded panel, centred purple two-line H1, divider, intro line | H1 5 to 9 words, P 25 to 40 words | `<h1><Service> Care <span>for <Suburb> Residents</span></h1>`. The span becomes line 2. |
| 2 | Intro split `yb-split` | Local intro: the problem, the clinic in Officer, what a session involves. Photo on the right with a purple offset shadow. | H2 + 2 paragraphs of 50 to 70 words + fixed button | `Our <Service> Services Near <Suburb>` |
| 3 | Purple band `yb-band` | What the service covers, as 6 white icon cards. The icons are fixed. | H2 5 to 9 words, lead 30 to 45 words, 6 cards (H3 2 to 5 words, P 20 to 28 words starting "We") | e.g. `<Service> Support for Muscle Tension and Movement` |
| 4 | Related services `yb-rel` | Internal links to 6 other services. Heading fixed. | 6 descriptions of 20 to 28 words | fixed |
| 5 | Why choose `yb-why` | Three numbered cards. Titles fixed, card 3 body fixed. | Card 1: 18 to 25 words. Card 2: 15 to 22 words. | `Why Choose Your Body Hub for <Service> Needs?` |
| 6 | Nearby Communities `yb-near` | Fixed block, identical on every live page | 0 | fixed |
| 7 | Funding logos `yb-fund` | Fixed logo row | 0 | fixed |
| 8 | FAQ `yb-faq` | 4 to 6 questions. One must be "How far is Your Body Hub from <Suburb>?" | Answers 35 to 60 words | `Frequently Asked Questions About <Service> in <Suburb>` |
| 9 | Contact `yb-contact` | Fixed. The map is shown as an address panel. | 0 | fixed |
| 10 | Closing CTA `yb-cta` | Fixed | 0 | fixed |

**Total written words: 750 to 1,050** (sections 1 to 5 and 8).

Card 1 in section 5 must suit the service. For myotherapy or remedial massage, say the practitioners work alongside the clinic's other services. Do not copy the physio wording ("Our experienced physiotherapists…").

### Related service cards (section 4): fixed list
Pick 6 cards and never include the page's own service. Use the image, name and link exactly as given. Only the description is yours.
| Name | Link | Image |
|---|---|---|
| Physiotherapy | https://yourbodyhub.com.au/service/physiotherapy/ | https://yourbodyhub.com.au/wp-content/uploads/2025/06/Physiotherapy-img.webp |
| Myotherapy | https://yourbodyhub.com.au/service/myotherapy/ | https://yourbodyhub.com.au/wp-content/uploads/2025/06/Myotherapy-Featured-Img.webp |
| Remedial Massage | https://yourbodyhub.com.au/service/remedial-massage/ | https://yourbodyhub.com.au/wp-content/uploads/2025/06/Massage-Therapy-at-Your-Body-Hub-in-Melbourne.webp |
| Exercise Physiology | https://yourbodyhub.com.au/service/exercise-physiology/ | https://yourbodyhub.com.au/wp-content/uploads/2025/06/Exercise-physio.webp |
| Dietitian | https://yourbodyhub.com.au/service/dietitian/ | https://yourbodyhub.com.au/wp-content/uploads/2025/06/Dietitian-Holding-Vegetables-Featured-Img.webp |
| Classes | https://yourbodyhub.com.au/service/classes/ | https://yourbodyhub.com.au/wp-content/uploads/2025/06/classes.webp |
| Infrared Sauna | https://yourbodyhub.com.au/service/infrared-sauna/ | https://yourbodyhub.com.au/wp-content/uploads/2025/06/Infrared-sauna.webp |

Approved descriptions you may reuse (verbatim from https://www.yourbodyhub.com.au/services/dry-needling/):
- Dietitian: "We help you develop practical eating habits through personalised nutrition advice that considers your health needs, preferences and daily routine."
- Classes: "We offer guided exercise classes to encourage regular movement. We help you choose a suitable option for your current ability and goals."
- Myotherapy: "We assess muscle pain and movement concerns, then discuss suitable hands-on treatment, exercise advice and other options based on your needs."
- Exercise Physiology: "We plan individual exercise programs to support physical function, fitness and health management, with guidance that reflects your starting point."
- Infrared Sauna: "We offer infrared sauna sessions for relaxation. We discuss suitability so you can consider this option alongside your health needs."
- Remedial Massage: "We tailor remedial massage to your muscle concerns and comfort, using assessment findings to guide the areas and techniques we address."

## Fixed copy (already in the skeleton, do not change)
- Buttons: "Book an Appointment" (section 2), "Book An Appointment" (sections 5 and 10), "Enquire Now" (contact). The capitalisation differs on the live site and is kept as it is.
- Section 4 H2: "Explore Our Related Health & Wellness Services".
- Section 5 card titles: "Multidisciplinary Expertise Under One Roof", "Evidence-Based Treatment with Personalised Care", "Trusted by Major Funding Bodies". Card 3 body: "We’re approved providers for NDIS, WorkCover, TAC, DVA, and accept all major health funds via HICAPS."
- Nearby Communities: H2, the sentence "Residents from these nearby communities can easily visit our clinic for professional treatment, friendly support, and care tailored to their individual needs." and the cards Beaconsfield, Pakenham, Berwick and Clyde North, which link to the physio suburb pages.
- "Where Funding Meets Trust" with the TAC, DVA, NDIS, HICAPS, WorkSafe and Medicare logos.
- Contact: "We'd love to hear from you!", "Have questions about our services or your treatment plan? We’re here to help."
- CTA: "Ready to Take the Next Step in Your Recovery?", "Our team is here to help you move better, manage your condition, and work towards lasting improvements in your health.", "Book an appointment today."

## Facts on the client's own site (only these may be used)
| Fact | Verbatim | URL |
|---|---|---|
| Address | "Suite 26, 445 Princes Hwy, Officer VIC 3809" | every page footer, e.g. https://yourbodyhub.com.au/contact-us/ |
| Phone | "(03) 8578 6544" (tel:0385786544) | header and footer of every page |
| Second number | "03 8610 0110" (unlabelled, no tel link) | footer and https://yourbodyhub.com.au/contact-us/. Do not use in copy. |
| Email | "info@yourbodyhub.com.au" | footer |
| Distance and parking (Berwick only) | "We’re located at Suite 26, 445 Princes Highway, Officer – just a 5-10 minute drive from Berwick. Our clinic is easily accessible via Princes Highway, with free on-site parking." | https://yourbodyhub.com.au/physiotherapy-clinic-near-berwick/ |
| Hours | "Monday - Thursday: 9am to 8pm", "Friday: 9am to 7pm", "Saturday: 9am to 5pm", "Sunday: 10am to 4pm" | https://yourbodyhub.com.au/contact-us/ |
| Open 7 days | "Yes, we are open on a Sunday. We are open 7 days a week." | https://yourbodyhub.com.au/faqs/general-faqs/ |
| Funding | "We’re approved providers for NDIS, WorkCover, TAC, DVA, and accept all major health funds via HICAPS." | https://www.yourbodyhub.com.au/services/dry-needling/ |
| Payment | "We accept Cash, EFTPOS, HICAPS, Worksafe, TAC, DVA, NDIS and CDM/EPC." | https://yourbodyhub.com.au/faqs/general-faqs/ |
| HICAPS | "Treatments can be claimed on the spot through your private health insurance extras cover with the use of our HICAPS facility. All you need to do is pay any gap!" and "Please note not all private health insurance companies are registered with HICAPS." | https://yourbodyhub.com.au/faqs/general-faqs/ |
| Medicare (physio context) | "Medicare rebates may be available through Chronic Disease Management Plans." | https://yourbodyhub.com.au/physiotherapy-clinic-near-berwick/ |
| Cancellations | "if you’re unable to provide at least 24 hours’ notice before missing your appointment, we’ll need to charge a 50% fee of the scheduled service." | https://yourbodyhub.com.au/faqs/general-faqs/ |
| Myotherapy: referral | "No, you do not require a referral to see a Myotherapist." | https://yourbodyhub.com.au/faqs/myotherapy-faqs/ |
| Myotherapy: length | "Generally, appointments are 60mins, although depending on how many areas of the body require treating, 45mins and 30mins are also available." | https://yourbodyhub.com.au/faqs/myotherapy-faqs/ |
| Myotherapy: health fund | "Yes, providing you have relevant extras on your health insurance. Most health insurance companies will cover an amount or percentage of your appointment cost and you are required to pay the gap at the time of the treatment." | https://yourbodyhub.com.au/faqs/myotherapy-faqs/ |
| Myotherapy: Medicare | "No, Myotherapy is not covered by Medicare so therefore cannot be bulk billed." | https://yourbodyhub.com.au/faqs/myotherapy-faqs/ |
| Myotherapy: WorkCover | "Unfortunately, you cannot claim Myotherapy on Workcover." | https://yourbodyhub.com.au/faqs/myotherapy-faqs/ |
| Myotherapy: techniques | "trigger point therapy, dry needling, deep tissue massage, hot and cold therapies, passive/ active muscle stretching and cupping … corrective/rehabilitative exercises or postural re-education" | https://yourbodyhub.com.au/faqs/myotherapy-faqs/ |
| Myotherapy: pregnancy | "Yes, Myotherapists are trained in pregnancy related issues." | https://yourbodyhub.com.au/faqs/myotherapy-faqs/ |
| Remedial massage: hygiene | "Fresh linens and towels are provided for each client, and all equipment and surfaces are thoroughly sanitized between treatments." | https://yourbodyhub.com.au/service/remedial-massage/ (fact only, rewrite in AU spelling "sanitised") |

**Facts that are not on the site:** Emerald and Narre Warren have no stated drive time. Narre Warren North, South and East suburb pages exist but give no distance, and Emerald appears nowhere. Remedial massage has no FAQ page, so session lengths and the health fund position for remedial massage are not stated. For those FAQs, write "Your Body Hub is at Suite 26, 445 Princes Hwy, Officer, with free on-site parking" and leave out the minutes. Do not state a remedial massage session length or rebate beyond the general HICAPS facts.

## Internal links
- Book: `/book-appointment/`. Contact: `/contact-us/`. Phone: `tel:0385786544`.
- Service links as in the related services table. Suburb pages: `/physiotherapy-clinic-near-<suburb>/` (Berwick, Pakenham, Beaconsfield, Clyde North, Narre Warren North, South and East and more exist). The site also has `/service/remedial-massage-near-berwick/`, `-near-pakenham/`, `-near-clyde-north/` and `-near-beaconsfield/`.
- You may add one in-copy link in section 2 or the FAQ to the matching service page, e.g. `/service/myotherapy/` or `/service/remedial-massage/`.

## Images
- `{{IMG main}}`: one client library photo of the service being delivered. It shows at 420px tall with a cover crop, and the alt text should describe the photo. In the sample it is the live site's Myotherapy-Featured-Img.webp.
- All icons, number cards and logos are fixed live site URLs. Do not swap them.

## Avoid
- The Google Reviews block, star ratings and review counts ("151 Google reviews").
- Claims of being "leading", "best" or "expert", and "pain-free", "faster recovery", "accelerate healing" or "restore full movement".
- Saying myotherapy is claimable on WorkCover or Medicare. The site says it is not. The fixed "Trusted by Major Funding Bodies" card is a clinic-wide statement, so do not repeat WorkCover in myotherapy copy.
- Mentioning the Warragul clinic on these pages.
- Em and en dashes, and the Oxford comma.
