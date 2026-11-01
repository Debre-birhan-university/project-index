# Lab Assignment: Critique and Rebuild an Ethiopian App Design

## Background

Last year's batch did Lab 1 (UX Design). Each student chose one real mobile app working in Ethiopia (Telebirr, Ride, ZayRide, Gebeta, etc.) and wireframed it in draw.io or Figma. Each student's repo contains:

1. `mobileapp.png`: tutorial proof from the `ux.pdf` guide 
2. Images/PDFs of the **main project**: their design of the Ethiopian app
3. `README.md` stating the selected app and the design tool used

This year you will **continue that work**: study a previous student's design, critique it, propose an improvement, and build it in **Android Studio's XML editor**.

Browse the forks here:
https://github.com/Debre-birhan-university/debre-berhan-university-classroom-seng4061-lab-1-ux-design-crispy-dollop/forks

---

## Step 1: Choose and fork a repo

- Open several forks. Read the README and look at the design images.
- **Fork the one that interests you most.** Pick an app you actually use or have strong opinions about.
- Fork the **student's repo** (not the original template) so you inherit their design.
- Work only in your fork.
- Install and use the real app if you can (some may need a Telebirr account or a phone number). If you can't, rely on screenshots, the Play Store listing and videos, and say so in your critique.

## Step 2: Write `CRITIQUE.md`

You are critiquing **two things**, and the gap between them is useful:

1. **The real app** as it works today in Ethiopia
2. **The previous student's wireframe/redesign** of it

Does the wireframe fix the app's problems, ignore them, or add new ones? Note if it only copies the existing app.

### A. UI: how it looks
- Layout, spacing, alignment and visual hierarchy
- Color palette, contrast and readability (including outdoors in sunlight)
- Typography, iconography and consistency across screens

### B. UX: how it works
- Is the main task easy to find and complete? Count the taps.
- Onboarding, login and navigation flow
- Accessibility: text size, contrast, touch targets (at least 48dp)
- Does it solve a real problem for real users, including those on low-end phones or weak connections?
- Error, empty and loading states, and user feedback

### What a good critique includes
- **Apply what we discussed in class** about the future of apps and UX design.
- **Be specific:** name the exact screen and element ("Telebirr home: the send-money action takes 3 taps from launch").
- **Use screenshots or annotations** of the real app and the wireframe.
- **Credit what works well.**
- **Read beyond the class.** It shows in the quality of the critique.
- **Reflect your own analysis.**

## Step 3: Write `PROPOSAL.md`

- **The problem:** which issue from your critique are you addressing?
- **The proposed solution:** what changes, and why is it better?
- **Expected impact:** how does it improve the UI, the UX, or both?
- **Scope:** choose **one core flow (1 to 3 screens)** and do it well. A focused, justified improvement beats a rushed redesign of everything.

## Step 4: Build it in Android Studio (XML)

This is the key difference from last year. **Last year's designs were made in draw.io or Figma. Yours must be built in the Android Studio XML editor.**

- Create an Android Studio project (Empty Views Activity) inside your fork and implement your proposal as XML layouts in `res/layout/*.xml`, with supporting resources (`colors.xml`, `strings.xml`, `themes.xml`, `dimens.xml`, drawables).
- Layouts must render correctly in the **Design/Preview** pane. Check at least two screen sizes.
- Include **preview screenshots** of every screen you designed in `/screenshots`.
- Kotlin/Java logic is **not required**. This is a design exercise, but layouts should be clean and realistic.

## Step 5: Document your learning in `RESOURCES.md`

List every article, video, book, documentation page (Material Design, Android developer docs) and class descussionn  you used.

**If you used AI tools (ChatGPT, Claude, Gemini, etc.), be honest and humble about it:**
- State which tool you used and what you used it for.
- AI can invent links and facts. **Ask for sources, then open every link and verify it yourself.**
- Include only verified links that exist and support your point.
- Using AI to learn is fine. Submitting its work as your own thinking is not.

# List of projects
| **No.** | **Application Name**       | **Student GitHub Username** | **Fork Repository** |
| ------- | -------------------------- | --------------------------- | ------------------- |
| 1       | Ethiopia E-Learning Portal | esetawlachew03              | [Ethiopia E-Learning Portal](https://github.com/esetawlachew03/lab-1-ux-design-haymi-b) |
|2 | Tuba Ethiopian Books | shanbelkibre | [Tuba Ethiopian Books](https://github.com/shanbelkibre/lab-1-ux-design-MierafA12/tree/main) |
| 3 | ORTHODOXAPP2 | samuelabera21 | [ORTHODOXAPP2](https://github.com/samuelabera21/ORTHODOXAPP2) |
| 4 | Hulugram | boldhab | [Hulugram](https://github.com/boldhab/lab-hulugram-hab) |
| 5 | CBE Mobile Banking | HabtamuShewamene | [CBE Mobile Banking](https://github.com/HabtamuShewamene/lab-1-ux-design-Fitsumhelina) |
| 6 | H-Cash | biniyamagegnehu | [H-Cash](https://github.com/biniyamagegnehu/lab-1-ux-design-kalkidan1919) |
| 7 | Ethio Matric | mulukenkassaw2025 | [Ethio Matric](https://github.com/mulukenkassaw2025/lab-1-ux-design-malfiya1212) |
| 8 | Tele Birr | YonasGetaw | [Tele Birr](https://github.com/YonasGetaw/lab-1-ux-design-amangebregziabher) |
| 9 |fyn ግዕዝ 2 | YohannesBirhane | [fyn ግዕዝ 2](https://github.com/YohannesBirhane/lab-1-ux-design-fyn---) | 
| 10 | Jiji Ethiopia | barkotdereje | [Jiji Ethiopia](https://github.com/barkotdereje/lab-1-ux-design-kido19) |
| 11 | Semu Audiobooks | fasikayonas | [Semu Audiobooks](https://github.com/fasikayonas/lab-1-ux-design-haset-T) |
| 12 | Mengedegna | yirgazd21 | [Mengedegna](https://github.com/yirgazd21/lab-1-ux-design-haydaWy) |
| 13 | ጸሎት መጽሐፍ (outside) | Leta-Kasahun | [Prayer Book](https://github.com/Leta-Kasahun/lab-1-ux-design-13eyob/tree/main) |
| 14|   Etthio E-learning... | getabalewKemaw |[E-Learning](https://github.com/getabalewKemaw/lab-1-ux-design-haymi-b)|
| 15 | Astawq | AbelAlelign | [Astawq](https://github.com/AbelAlelign/lab-1-ux-design-Amanualegezahegne) |
| 16 | Fayda Mobile App | Altaseb-Chernet | [Fayda Mobile App](https://github.com/Altaseb-Chernet/lab-1-ux-design-yasino-916) |
| 17 | Delivery Addis | Lydiaa246 | [Delivery Addis](https://github.com/Lydiaa246/lab-1-ux-design-LydiaAbebaw) |
| 18 | LegalTech | ahmedseid9392 | [ClauseBit: LegalTech](https://github.com/ahmedseid9392/lab-1-ux-design-Yamtk1178) |
| 19 | Gazzette Plus | Nicohena | [Gazzette Plus](https://github.com/Nicohena/lab-1-ux-design-lidia-shenkut) |
| 20 | Ethiopian Salary Calculator | estif295 | [Ethiopian Salary Calculator](https://github.com/estif295/lab-1-ux-design-elu2121) |
| 21 | M-Pesa Ethiopia | abraomex | [M-Pesa Ethiopia](https://github.com/abraomex/lab-1-ux-design-Tilahun-Sitotaw-Abrham-Belay) |
| 22 | eQUB | Nigist-Z | [eQUB](https://github.com/Nigist-Z/lab-1-ux-design-Rediet2077) |
| 23 | Feres App | Belete-Dereje | [Repository](https://github.com/Belete-Dereje/lab-1-ux-design-Halidjr) |
| 24 | Arganon: Mezmur & Kidase Study (outside) | mahi-a-1 | [Google Play](https://play.google.com/store/apps/details?id=com.melloss.arganon) |
| 25 | Beu Delivery App | itsbrukti | [Beu Delivery App](https://github.com/itsbrukti/lab-1-ux-design-yoadin) |
| 26 | teleTV | Melatananu | [teleTV APP](https://github.com/Melatananu/lab-1-ux-design-tinbit25-Melat) |
| 27 | TinaMart | Ruhama27 | [TinaMart APP](https://github.com/Ruhama27/lab-1-ux-design-tsediworku123) |
