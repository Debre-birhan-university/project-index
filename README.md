# Ethiopian App Design — Project Selection Index

> **Outside-app approvals: 0/5**

## 1. Student Project Registration

This index tracks the Ethiopian mobile applications selected by students for this year's Lab Assignment: Critique and Rebuild an Ethiopian App Design.

**Important:** Every student must work on a different application. Check this index before selecting and registering your project.

### Registered Projects

| No. | Application Name | Student GitHub Username | Fork Repository |
|---|---|---|---|
| 1 | Ethiopia E-Learning Portal |esetawlachew03 | https://github.com/esetawlachew03/lab-1-ux-design-haymi-b |

### Selection Rules

1. Check this index before choosing an application.
2. Browse the previous students' repositories using the [Previous Students' Forks](https://github.com/Debre-birhan-university/debre-berhan-university-classroom-seng4061-lab-1-ux-design-crispy-dollop/forks).
3. Select an available application.
4. Fork the repository belonging to the previous student whose design you want to study.
5. Send your fork link to the project index administrator.
6. The administrator will inspect your fork, verify the selected application from its README, and add your registration here.
7. If the application is already registered, you must select another one.

**First come, first served:** An application is considered taken once its registration is verified and added to this index.

### Changing Your Selection

If you want to change your selected application:

- Contact the administrator first.
- Your previous registration will be replaced or removed.
- Your previous application will become available to other students.
- Your new selection must follow the same availability rules.

## 2. Outside-App Approval

Students may request permission to work on an Ethiopian application that was not selected in last year's project collection.

**Prior approval is mandatory. Do not fork or register an outside application before receiving approval.**

To request approval, contact the administrator and provide:

- Application name and official website or app link.
- Why you want to study this application.
- Useful supporting resources, research, documentation, or real experience with the application.

Approval is granted only when the student provides useful supporting material.

If the request is uncertain, the administrator must consult the instructor.

**Maximum outside-app approvals: 5 for the entire class.**

### Outside-App Registration

Approved outside applications must be marked with `(outside)`.

Example:

| No. | Application Name | Student GitHub Username | Fork Repository |
|---|---|---|---|
| 1 | Example Ethiopian App (outside) |student123 | [Fork link](https://github.com/) |

Update the counter whenever an outside application is approved or an existing approval is released.

## 3. Previous Students' Project Collection

Browse the previous students' repositories here:

[View All Previous Students' Forks](https://github.com/Debre-birhan-university/debre-berhan-university-classroom-seng4061-lab-1-ux-design-crispy-dollop/forks)

Each previous student's repository should contain:

1. `mobileapp.png`: Tutorial proof from the `ux.pdf` guide.
2. Images/PDFs of the main project: Their design of the Ethiopian application.
3. `README.md`: Selected application name and design tool.

---

# Lab Assignment: Critique and Rebuild an Ethiopian App Design

## Background

Last year's batch did Lab 1 (UX Design). Each student chose one real mobile app working in Ethiopia (Telebirr, Ride, ZayRide, Gebeta, etc.) and wireframed it in draw.io or Figma.

This year you will continue that work: study a previous student's design, critique it, propose an improvement, and build it in Android Studio's XML editor.

## Step 1: Choose and Fork a Repository

- Open several forks. Read the README and look at the design images.
- Choose an app you actually use or have strong opinions about.
- Check this project index to ensure the application is available.
- Fork the student's repository, not the original template.
- Work only in your fork.
- Install and use the real app if possible. If you cannot, rely on screenshots, Play Store listings, and videos, and explain this limitation in your critique.

## Step 2: Write `CRITIQUE.md`

Critique two things:

1. The real app as it works today in Ethiopia.
2. The previous student's wireframe/redesign of it.

Evaluate whether the wireframe fixes the app's problems, ignores them, or introduces new ones.

### A. UI: How It Looks

- Layout, spacing, alignment, and visual hierarchy.
- Color palette, contrast, and readability, including outdoors in sunlight.
- Typography, iconography, and consistency across screens.

### B. UX: How It Works

- Is the main task easy to find and complete? Count the taps.
- Onboarding, login, and navigation flow.
- Accessibility: text size, contrast, and touch targets (at least 48dp).
- Does it solve a real problem for real users, including those on low-end phones or weak connections?
- Error, empty, and loading states, and user feedback.

### What a Good Critique Includes

- Apply what we discussed in class about the future of apps and UX design.
- Be specific: name the exact screen and element.
- Use screenshots or annotations of the real app and the wireframe.
- Credit what works well.
- Read beyond the class.
- Reflect your own analysis.

## Step 3: Write `PROPOSAL.md`

Include:

- **The problem:** Which issue from your critique are you addressing?
- **The proposed solution:** What changes, and why is it better?
- **Expected impact:** How does it improve the UI, UX, or both?
- **Scope:** Choose one core flow (1 to 3 screens) and do it well.

A focused, justified improvement is better than a rushed redesign of everything.

## Step 4: Build It in Android Studio (XML)

Last year's designs were made in draw.io or Figma. This year's design must be built in the Android Studio XML editor.

- Create an Android Studio project (Empty Views Activity) inside your fork.
- Implement your proposal as XML layouts in `res/layout/*.xml`.
- Include supporting resources (`colors.xml`, `strings.xml`, `themes.xml`, `dimens.xml`, and drawables).
- Ensure layouts render correctly in the Design/Preview pane.
- Check at least two screen sizes.
- Include preview screenshots of every designed screen in `/screenshots`.
- Kotlin/Java logic is not required. This is a design exercise, but layouts should be clean and realistic.

## Step 5: Document Your Learning in `RESOURCES.md`

List every article, video, book, documentation page (Material Design, Android developer docs), and class discussion you used.

If you used AI tools (ChatGPT, Claude, Gemini, etc.):

- State which tool you used and what you used it for.
- Ask for sources and verify every link yourself.
- Include only verified links that exist and support your points.
- Be honest about your own contribution and analysis.

---

**Final Reminder:** Check the project selection index before registering. Each student must work on a different application. All project registrations and outside-app approvals must follow the rules above.
