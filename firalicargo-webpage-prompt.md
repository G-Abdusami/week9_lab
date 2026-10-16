# Firali Cargo — Web Page Prompt

Copy everything below the line into an AI website builder (Claude, Lovable, v0, Bolt, etc.).
Before you publish, replace the `[TODO]` items with real details.

---

Build a modern, mobile-first, single-page website for **Firali Cargo**, a company in Tashkent, Uzbekistan, that rents electric scooters to delivery couriers.

## About the company (use only these facts)
- Legal name: "Firali Cargo" MChJ (LLC), Tashkent, Uzbekistan
- What we do: rent seated electric scooters to delivery couriers on a daily, weekly or monthly basis
- Official partner of Yandex (couriers use our scooters for Yandex deliveries)
- Fleet: 40 electric scooters
- Every rental includes the scooter, 2 batteries, 2 chargers and a helmet, at no extra cost
- If a battery runs out or the scooter breaks down, we bring a replacement to the courier quickly
- Technical support for every rider
- Phone: +998 90 488-87-88
- Instagram: @firalicargo (https://instagram.com/firalicargo)
- Address: Toshkent sh., Uchtepa tumani, Tepaqo'rg'on MFY, 11-mavze, 43-uy, 12-xonadon [TODO: confirm this is the address customers should visit]
- Working hours: 9:00–21:00 (Tashkent time)
- Telegram: [TODO, or leave out]

## Audience
Couriers, and people who want to start courier work in Tashkent. Most visit on a phone and read Uzbek or Russian.

## Languages
- Uzbek (Latin script) is the default; Russian is the second language. Put a UZ | RU switcher in the header.
- Write all copy in both languages. Use short, simple, friendly sentences. Address the reader politely ("siz" / "вы").

## Page sections (in this order)
1. **Header (sticky):** the Firali Cargo logo (blue courier on a scooter + "FirAli CARGO" wordmark), anchor navigation, language switcher, and a "Qo'ng'iroq qilish / Позвонить" button linking to tel:+998904888788.
2. **Hero:** a headline about starting courier work today on a ready-to-go e-scooter. Subheadline: 2 batteries for all-day work, a free helmet and chargers, and we come to you if something goes wrong. Two buttons: "Call us" and "Message us on Instagram". Use a placeholder image of a courier on an e-scooter in a city.
3. **Benefits:** icon cards, in exactly this priority order:
   1. Battery ran out or the scooter broke down? We bring a replacement to you quickly.
   2. 2 batteries with every scooter, so you can work all day.
   3. Helmet and 2 chargers included free.
   4. Technical support.
   5. Official partnership with Yandex.
4. **What's in the kit:** a visual list: e-scooter, 2 batteries, 2 chargers, helmet.
5. **How it works:** 4 steps:
   1. Call us or message us on Instagram.
   2. Come to our office with your passport or ID card.
   3. Sign the rental contract and receive the scooter and kit (with a handover act).
   4. Start delivering.
6. **Rental plans:** four cards, all at the same daily rate of 39 500 so'm:
   - 1 day: 39 500 so'm
   - 1 week (7 days): 276 500 so'm
   - 2 weeks (14 days): 553 000 so'm
   - 1 month (30 days): 1 185 000 so'm
   - Keep the daily price in one setting at the top of the code and calculate the totals from it.
   - Add a note: "Clarify deposit terms by phone" (no deposit amount on the site).
7. **Work with Yandex:** a short section saying we are an official Yandex partner and inviting people to contact us to get started. Text only: do not use the Yandex logo or imitate Yandex branding.
8. **FAQ (accordion):** answer only from the facts above:
   - What happens if my battery runs out? (We bring a replacement quickly.)
   - What is included? (Scooter, 2 batteries, 2 chargers, helmet.)
   - What documents do I need? (Passport or ID card.)
   - How much does it cost? (39 500 so'm per day; list the 4 plan totals.)
   - Is there a deposit? (Clarify deposit terms by phone.)
   - Can I rent for one day, a week or a month? (Yes, all three.)
   - Do you offer technical support? (Yes.)
   - When are you open? (9:00–21:00.)
9. **Lead form:** name, phone (+998 input mask), preferred plan (daily / weekly / monthly / not sure), and "Do you already work as a courier?" (yes / no). On submit, send to [TODO: Telegram bot / Google Sheet / email] and show a thank-you message. Do NOT ask for passport, ID or JShShIR numbers on the website.
10. **Contacts:** phone (click-to-call), Instagram link, address, an embedded Google Map of the address, and working hours.
11. **Footer:** © [current year] "Firali Cargo" MChJ, phone and Instagram.

Also add a floating "Call" button on mobile.

## Content rules (important)
- Use only the prices above. Never invent deposit amounts, earnings, reviews, ratings, customer counts or other statistics.
- Never promise income (no "earn X million per month"). Use only general phrases such as "work all day without interruption".
- Do not mention or compare against competitors.
- Do not use Yandex's logo or colors, or make the page look like an official Yandex page.

## Design
- Energetic, trustworthy and clean, for a delivery/mobility brand. Colors: Pantone 19-4052 Classic Blue (#0F4C81) as the main color and the logo green (Pantone 361 C, #43B02A) as the accent.
- Detailed, smooth motion: animated hero (rider riding in, speed lines, moving road), scroll reveals, count-up numbers, a price calculator. Animate only transform/opacity and respect prefers-reduced-motion.
- Mobile-first: large tap targets and readable text. Use a font that supports both Uzbek Latin (o', g') and Cyrillic, e.g. Inter or Manrope.
- Fast on mobile data: compressed, lazy-loaded images and only light animations.

## Technical requirements
- Stack: [TODO: plain HTML/CSS/JS, or Next.js + Tailwind]
- tel: and Instagram links work on mobile.
- SEO: title and meta description in both languages, hreflang (uz / ru), Open Graph tags, and LocalBusiness JSON-LD (name, phone, address, Instagram in `sameAs`).
- Accessibility: semantic HTML, alt text, WCAG AA contrast, keyboard-accessible FAQ and form.
- Mark anything not provided as a clear `[TODO]` placeholder. Don't make it up.

**Deliverable:** the complete code, plus a list of every `[TODO]` still to fill in.
