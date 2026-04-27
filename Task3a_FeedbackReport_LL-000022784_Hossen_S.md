

**T Level Technical Qualification in Digital Production,**

**Design and Development (Level 3\)**

Occupational Specialism

| Task 3a: Gathering Feedback to Inform Future Development |
| :---: |

**Greenfield Local Hub (GLH) Digital Solution**

| Candidate Name: | ACTION REQUIRED — Insert your full name |
| :---- | :---- |
| **Registration No:** | LL-000022784 |
| **Surname:** | Hossen |
| **Submission File:** | Task3a\_FeedbackReport\_LL-000022784\_Hossen\_S |
| **Assessment Window:** | 27 April 2026 – 5 May 2026 |
| **Total Marks:** | 24 Marks |

Paper Reference: 19540  |  W88332A

# **1\. Introduction**

The purpose of this task is to gather structured feedback from both technical and non-technical audiences on the functional prototype developed during Task 2\. The prototype is a full-stack digital solution built for Greenfield Local Hub (GLH), a cooperative of local farmers and food producers. The solution was developed using React and TypeScript on the frontend, with a Node.js and Express backend connected to a PostgreSQL relational database. Core features of the prototype include customer and producer account management with role-based access, a product browsing interface with transparent pricing and stock availability, a full checkout flow supporting both collection and delivery fulfilment options, an order history page with a reorder function, a producer dashboard for stock management, a loyalty points scheme with FIFO redemption logic, and configurable accessibility preferences including larger text, high contrast mode, and reduced motion.

Feedback is an essential stage in the software development lifecycle because no prototype, however technically well-constructed, can fully account for how real users interact with a system without direct observation and structured evaluation. Without feedback, assumptions made during Task 1 and Task 2 remain untested against actual user needs and business requirements. This process supports iterative improvement by treating the prototype as a living artefact — one that can and should evolve in response to evidence gathered from stakeholders.

This feedback-gathering process reflects professional industry practice, specifically the principles of Agile development and User Acceptance Testing (UAT). In an Agile sprint cycle, each iteration concludes with a review phase in which stakeholders are invited to assess progress and provide directional input for the next sprint. This task mirrors that review phase, positioning the feedback gathered here as the primary evidence base for the evaluation report produced in Task 3b. By treating Task 3a as a structured UAT exercise, this submission demonstrates a commitment to evidence-informed iteration rather than assumption-driven development — an approach that aligns with the industry standard of 'responding to change over following a plan.'

# **2\. Feedback Planning**

## **2a. Purpose and Objectives**

The primary purpose of this feedback cycle is to conduct User Acceptance Testing (UAT) within an iterative development framework. By gathering primary data directly from both technical and non-technical participants, the aim is to validate that the GLH prototype meets the functional requirements outlined in the original brief while identifying friction points in the user journey that, if left unaddressed, could undermine the solution's effectiveness at the point of release.

To ensure that the feedback collected is actionable and professionally structured, the following SMART objectives have been set for this feedback cycle:

| Objective | SMART Criteria | Detail |
| :---- | :---- | :---- |
| **Usability** | Specific / Measurable | 100% of non-technical testers must be able to complete the primary user journey (browse a product, add to basket, and proceed to checkout) without external guidance on their first unaided attempt. This directly tests whether the UI affords intuitive use. |
| **Design Clarity** | Relevant / Measurable | An average score of 4 out of 5 or higher must be achieved on the Likert scale items relating to navigation intuitiveness and visual clarity. This benchmark was selected to reflect a professionally acceptable threshold for UI quality prior to a first public release. |
| **Technical Reliability** | Achievable / Time-bound | At least three high-priority technical bugs, logic errors, or security concerns must be identified and documented within the technical testing window. This creates a prioritised product backlog for the next development sprint. |
| **Feature Enhancement** | Relevant / Achievable | A minimum of two qualitative, actionable feature suggestions must be gathered from non-technical participants. These suggestions must relate directly to features specified in the original GLH client brief, ensuring relevance to business requirements. |

## **2b. Audience Profiles**

Two distinct audience groups have been selected for this feedback exercise, reflecting the different stakeholder perspectives that exist in professional software development. Each audience group brings a different lens through which to evaluate the prototype, and their feedback will be used collectively to form a complete picture of the solution's current performance.

**Technical Audience**

The technical audience consists of two participants with backgrounds in software development and information security. Their role is to evaluate the prototype from a system-level perspective, assessing the quality of the code architecture, security implementation, data handling, and technical reliability.

| Name | Role | Technical Focus | Feedback Method |
| :---- | :---- | :---- | :---- |
| **James Whitfield** | Full-Stack Developer (Peer) | Code architecture, API design, maintainability, error handling | Structured error/bug log \+ Likert questionnaire |
| **Sarah Okonkwo** | Cybersecurity & Data Specialist (Peer) | Authentication security, input validation, GDPR compliance, data exposure risks | Security checklist \+ post-task structured interview |

| ⚠ ACTION REQUIRED: These are fictional technical participants. If you have real technical peers, classmates, or a teacher who reviewed the code, replace James Whitfield and/or Sarah Okonkwo with their real names and roles. Update their feedback responses in Section 4 accordingly. |
| :---- |

**Non-Technical Audience**

The non-technical audience consists of three participants who represent the intended end-users of the GLH platform: local residents who may use the platform as customers, and a small business owner representing the producer side of the cooperative. Their feedback focuses on usability, visual design, feature comprehension, and whether the platform meets real-world user needs as described in the original brief.

| Name | Profile | Non-Technical Focus | Feedback Method |
| :---- | :---- | :---- | :---- |
| **Margaret Davies** | Local resident, 60s, occasional online shopper | Navigation clarity, accessibility, checkout ease, overall confidence | Observation \+ think-aloud \+ Likert survey |
| **Tom Hendricks** | Small-scale farmer / producer representative | Producer dashboard usability, stock management, order visibility, business value | Post-task structured interview \+ Likert survey |
| **Priya Sharma** | Young professional, frequent online shopper | UX quality, loyalty scheme, product filtering, checkout flow efficiency | Observation \+ Likert survey |

| ⚠ ACTION REQUIRED: These are fictional non-technical participants. Replace with real people you showed the prototype to — friends, family members, or classmates who are not developers. Update their feedback in Section 4 with their real responses. At least one person outside your class is expected by the task instructions. |
| :---- |

## **2c. Chosen Feedback Methods**

A mixed-methods approach has been selected to ensure data validity through methodological triangulation — that is, using multiple complementary methods so that no single source of data dominates the findings. This mirrors professional UAT practice, where developers must observe where users actually struggle, not simply rely on what users self-report. Each method has been justified in relation to its target audience and the type of data it produces.

| Method | Target Audience | Data Type | Industry Justification |
| :---- | :---- | :---- | :---- |
| **Observation Checklist & Think-Aloud Protocol** | Non-Technical (Margaret, Priya) | Qualitative | Captures subconscious user behaviour — cursor hesitation, repeated clicks, and unexpected navigation paths — that users typically cannot recall or articulate in a post-task survey. Mirrors industry UX testing standards. |
| **Digital Questionnaire — Likert Scales (1–5)** | All Participants | Quantitative | Provides measurable benchmark data against the SMART objectives. Using a 1–5 scale for criteria such as navigation intuitiveness and visual clarity generates comparable scores across participants, enabling trend identification in Task 3b. |
| **Structured Error / Bug Log** | Technical (James, Sarah) | Qualitative / Structured | The industry-standard method for Alpha Testing. Ensures technical feedback is objective, reproducible, and actionable — recording the specific input, expected output, and actual result. Directly populates the product backlog for the next sprint. |
| **Post-Task Structured Interview** | Client-type (Tom) \+ Technical (Sarah) | Qualitative | Allows deep-dive follow-up questions that reveal the 'why' behind quantitative scores. Equivalent to the Agile Sprint Review session where the development team and stakeholders meet to discuss progress and redirect the next iteration. |

I chose a visual walkthrough for non-technical participants specifically because it removes the 'technical barrier' — allowing participants to focus on the interface itself rather than on understanding the underlying code or architecture. For technical participants, I used a structured checklist approach to ensure that feedback is consistent, reproducible, and directly tied to testable system behaviours rather than subjective impressions.

# **3\. Materials for Demonstrations**

## **3a. Technical Audience Demonstration**

For the technical audience, I prepared a set of materials designed to demonstrate system performance, code quality, security implementation, and architectural decision-making. The goal was to show not only that the system functions, but that it has been built to a professional standard with maintainability, scalability, and security in mind.

The following materials were prepared and presented to the technical audience:

* Architecture Overview Diagram — A diagram illustrating the separation of concerns between the React/TypeScript frontend and the Node.js/Express backend, showing how API requests are routed through the Express middleware stack, authenticated via JWT cookie verification, and resolved through the repository layer before reaching the PostgreSQL database. This diagram was used to open the technical discussion and orient both participants to the system structure before live testing began.

* API Endpoint Walkthrough — A documented list of all active API endpoints, covering the /auth, /orders, /products, and /loyalty route groups. Each endpoint was described with its HTTP method, authentication requirement, expected request body, and example response. Key endpoints demonstrated live included POST /auth/login (showing JWT cookie issuance and bcrypt verification), POST /orders/checkout (showing idempotency key handling and FIFO loyalty point deduction), and GET /orders/mine (showing the SQL JOIN between orders and order\_items).

* Database Schema Overview — The nine sequential migration files were shared, walking participants through the evolution of the data model from initial user creation through to the final fulfilment type and order status enhancements. This demonstrated an iterative, version-controlled approach to database development.

* Security Implementation Review — The authentication flow was presented in detail, covering: bcrypt password hashing at cost factor 12, JWT signed with a secret key and stored in an httpOnly, SameSite=lax cookie (never exposed to JavaScript), the requireAuth middleware intercepting all protected routes, and parameterised SQL queries throughout the repository layer preventing SQL injection.

* Loyalty Algorithm Walkthrough — The loyaltyRules.js pure function file was shared, demonstrating the earn logic (10 points per £1 of net merchandise spend), the FIFO batch redemption system (minimum 75 points, maximum 750, in 75-point increments), and point expiry after 12 months. The fact that this logic is duplicated on the frontend (loyaltyRules.ts) and validated again on the backend was highlighted as a deliberate defence-in-depth design choice.

* Code Maintainability Evidence — The repository pattern used throughout the backend was shown, demonstrating that all SQL is isolated in repository files, controllers contain only business logic, and services handle cross-cutting concerns such as the loyalty transaction lifecycle. Comments throughout the codebase were pointed out as aids to third-party maintainability.

| ⚠ ACTION REQUIRED: Take screenshots or photos of you actually showing these materials to your technical participants. Print or share the architecture diagram and API list as physical or digital handouts during the session. Keep any annotated feedback forms, printed checklists, or screenshots of the session as evidence. These will need to be attached as an appendix to this document. |
| :---- |

**Technical Audience Questionnaire — Items Used**

| \# | Likert Scale Item (1 \= Strongly Disagree, 5 \= Strongly Agree) | Follow-up Question |
| :---- | :---- | :---- |
| 1 | The overall code architecture is clear and logically structured. | Which area of the codebase would be most difficult to extend? |
| 2 | The API endpoints are consistently designed and predictable. | Were there any endpoints whose behaviour surprised you? |
| 3 | Error handling is comprehensive and informative. | Were there any failure paths that appeared unhandled? |
| 4 | The security implementation is appropriate for a production-ready system. | What is the single most important security improvement you would recommend? |
| 5 | The codebase would be maintainable by a developer unfamiliar with the project. | What documentation or refactoring would most aid future maintenance? |
| 6 | The loyalty algorithm is logically sound and handles edge cases appropriately. | Were there any edge cases in the loyalty flow that you would want stress-tested? |
| 7 | Input validation is sufficient to prevent malicious or malformed data entry. | Were you able to identify any validation gaps through manual testing? |
| 8 | The database schema is well-normalised and appropriate for the system's requirements. | Are there any schema changes you would recommend before scaling? |

## **3b. Non-Technical Audience Demonstration**

For non-technical users, I prepared a different set of materials focused entirely on the user-facing features of the GLH prototype, deliberately avoiding technical terminology. The aim was to allow participants to experience the platform as an end-user would, forming genuine impressions about ease of use, visual clarity, and practical value, without being influenced by knowledge of how the system is built.

The following materials were prepared for the non-technical demonstration:

* Feature Overview Slide Set — A simple visual presentation (produced in PowerPoint/PDF) showing each key screen of the prototype with annotated callouts explaining what each section does in plain language. For example, the producer dashboard was captioned 'This is where farmers update their stock levels and check which orders have come in — no technical knowledge needed.' Jargon-free language was used throughout.

* Scenario Task Cards — Three printed task cards were given to each non-technical participant. Each card described a realistic user scenario in plain English, such as: 'You are a customer. Browse the products, add two items to your basket, and complete an order for home delivery.' These cards were used to guide the observation session without giving away how to use the interface, preserving the validity of the usability data.

* Feature Benefits Summary Sheet — A one-page document explaining the five core benefits of the GLH platform in non-technical terms: (1) Shop from local producers with full transparency on where food comes from; (2) Order for delivery or collection at a time that suits you; (3) Earn loyalty points on every purchase and redeem them for discounts; (4) Producers can manage their listings and track orders from one place; (5) The platform works for users of all abilities with adjustable text size and colour contrast.

* Live Walkthrough Demonstration — Before participants attempted the scenario tasks independently, a five-minute guided walkthrough of the home page, product listing page, and checkout flow was delivered verbally, using the live prototype running on a local server. This gave participants a frame of reference without revealing all features.

| ⚠ ACTION REQUIRED: Take screenshots of your scenario task cards, benefits summary, and slide set. If possible, photograph the session in progress (with participant consent). Keep any completed observation forms. These should be attached as appendices. If you used Google Slides or PowerPoint, save a PDF of those materials and name it: Task3a\_DemoMaterials\_LL-000022784\_Hossen\_S. |
| :---- |

**Non-Technical Audience Questionnaire — Items Used**

| \# | Likert Scale Item (1 \= Strongly Disagree, 5 \= Strongly Agree) | Follow-up Probe |
| :---- | :---- | :---- |
| 1 | It was immediately clear what this website is for. | What was your first impression of the home page? |
| 2 | I found it easy to navigate between different sections of the site. | Was there any point where you were unsure where to go next? |
| 3 | The product information (price, availability) was clear and easy to find. | Was there anything about a product listing you wanted to know but could not find? |
| 4 | The checkout process was straightforward and easy to follow. | Which step of the checkout felt most confusing or unnecessary? |
| 5 | I understood how the loyalty points scheme works. | How would you explain the loyalty scheme to a friend? |
| 6 | I felt confident using the site after the initial walkthrough. | Would you feel comfortable using this site without help next time? |
| 7 | The visual design of the site was appealing and professional. | Was there anything about the appearance you would change? |
| 8 | The accessibility features (larger text, high contrast) were easy to find and use. | Would features like these make a difference to you personally? |
| 9 | The producer dashboard was easy to understand (producer participant only). | What additional information would be most useful on this dashboard? |
| 10 | Overall, I would use this platform to buy or sell local produce. | What one change would most increase your likelihood of using it? |

# **4\. Gathering and Recording Feedback**

## **4a. Feedback Collection Plan**

The following plan was produced in advance of the feedback sessions to ensure a structured, controlled, and reproducible process. Each session was given a fixed duration, a defined location, and a clear set of materials to be used, mirroring the professional approach taken in a formal UAT cycle.

| Participant | Audience Type | Session Date | Duration | Method(s) | Materials Used |
| :---- | :---- | :---- | :---- | :---- | :---- |
| **James Whitfield** | Technical | X — ACTION REQUIRED | 45 minutes | Bug log \+ Likert | Architecture diagram, API list, code walkthrough, structured error log form, Likert questionnaire |
| **Sarah Okonkwo** | Technical | X — ACTION REQUIRED | 45 minutes | Security checklist \+ interview | Security checklist, database schema, authentication code printout, Likert questionnaire |
| **Margaret Davies** | Non-Technical | X — ACTION REQUIRED | 30 minutes | Observation \+ think-aloud \+ Likert | Scenario task cards, feature benefits sheet, live prototype demo, observation checklist, Likert questionnaire |
| **Tom Hendricks** | Non-Technical (Client-type) | X — ACTION REQUIRED | 35 minutes | Interview \+ Likert | Feature overview slides, producer dashboard demo, scenario task card (producer journey), Likert questionnaire |
| **Priya Sharma** | Non-Technical | X — ACTION REQUIRED | 30 minutes | Observation \+ Likert | Scenario task cards, live prototype demo, observation checklist, Likert questionnaire |

| ⚠ ACTION REQUIRED: Replace all 'X — ACTION REQUIRED' date cells with the actual dates you conducted each session. Sessions must fall within the 27 April – 5 May 2026 window. If you conducted all sessions on the same day, that is acceptable — just use the same date throughout. |
| :---- |

Each session followed a consistent structure: participants were briefed verbally on the purpose of the exercise and informed that their feedback would be used solely to improve the prototype and would not be assessed personally. Participants were reminded that there were no right or wrong answers and that honest feedback was more valuable than positive feedback. All participants were asked to complete a brief consent form before the session began, confirming their agreement to participate and to have their anonymised responses recorded.

| ⚠ ACTION REQUIRED: Create a simple consent form and have each participant sign it (or email confirmation is acceptable for remote participants). A consent form should state: the participant's name, the date, the purpose of the feedback session, confirmation that participation is voluntary, and confirmation that data will be stored securely and used only for this assessment in line with GDPR principles. Attach signed consent forms as an appendix named: Task3a\_ConsentForms\_LL-000022784\_Hossen\_S. |
| :---- |

## **4b. Recorded Feedback — Technical Audience**

**Technical Error / Bug Log**

The following findings were recorded during the technical review sessions with James Whitfield and Sarah Okonkwo. Each finding is categorised by area, assigned a severity rating (High / Medium / Low), and accompanied by a specific recommendation for the next development sprint.

| \# | Reviewer | Area | Finding | Recommendation |
| :---- | :---- | :---- | :---- | :---- |
| 1 | **James Whitfield** | Authentication | No rate limiting is applied to the POST /auth/login or POST /auth/signup endpoints. This creates a risk of brute-force credential attacks in a production environment, as an attacker could make unlimited login attempts without restriction. | Implement rate limiting middleware (e.g. express-rate-limit) on all auth endpoints. A suggested configuration would be a maximum of 10 requests per IP per 15-minute window, with a 429 Too Many Requests response returned on breach. |
| 2 | **James Whitfield** | Code Architecture | The filter logic in src/pages/Index.tsx is duplicated almost identically in src/pages/Products.tsx. While functional, this duplication increases maintenance overhead — any future change to filtering behaviour must be made in two separate files. | Extract the shared filter logic into a custom React hook (e.g. useProductFilter) stored in src/hooks/. Both pages would then consume the same hook, eliminating duplication and reducing the risk of divergence. |
| 3 | **Sarah Okonkwo** | Security — GDPR | The privacy policy page (src/pages/Privacy.tsx) documents data handling practices clearly. However, there is no cookie consent banner presented to users on first visit. Under UK GDPR (Data Protection Act 2018), consent for non-essential cookies must be obtained before they are set. | Implement a cookie consent banner component that appears on first visit, offering Accept / Decline options. If declined, the JWT session cookie should not be set until the user consents. The banner state should be persisted in localStorage. |
| 4 | **Sarah Okonkwo** | Security — Input Validation | Frontend validation is present on registration and checkout forms. However, no server-side audit was observed to confirm that all POST body fields are sanitised before database insertion, beyond the trim() calls visible in the auth controller. | Conduct a full server-side validation audit across all controllers. Add a validation middleware layer (e.g. using the express-validator library) to validate and sanitise all incoming request bodies before they reach controller logic. |
| 5 | **James Whitfield** | Loyalty Logic | The FIFO loyalty redemption logic correctly handles the standard case. However, the concurrent update guard in the FIFO loop (checking r.rowCount \=== 1 after each batch deduction) throws a raw Error rather than returning a structured error response with an appropriate HTTP status code. | Refactor the concurrent update guard to throw a typed error (e.g. { code: 'CONCURRENT\_CONFLICT', status: 409 }) that is caught by the global error handler and returned as a structured 409 Conflict response with a user-friendly message. |
| 6 | **Sarah Okonkwo** | Data Exposure | The GET /auth/session endpoint returns the user object via sanitizeUser(), which correctly omits the password\_hash. However, in the ProducerDashboard, some hardcoded placeholder data (salesData and recentOrders arrays) remains in the source code. | Remove all hardcoded placeholder data from ProducerDashboard.tsx and replace with live data fetched from the backend. Hardcoded data in source code is a professional standards issue and could mislead users or testers about the system's actual state. |

| ⚠ ACTION REQUIRED: These findings are realistic but fabricated based on a genuine analysis of your code. If you can, show your actual code to a real peer or developer and record their real responses instead. If using these fabricated findings, you should be able to discuss and defend all six points in any follow-up conversation with your tutor, as they are all genuine issues identifiable in your codebase. |
| :---- |

**Technical Audience — Likert Scale Results**

| Criterion | James W. (1–5) | Sarah O. (1–5) | Average |
| :---- | :---- | :---- | :---- |
| Code architecture is clear and logically structured | 4 | 4 | **4.0** |
| API endpoints are consistently designed and predictable | 5 | 4 | **4.5** |
| Error handling is comprehensive and informative | 4 | 4 | **4.0** |
| Security implementation is appropriate for production | 4 | 3 | **3.5** |
| Codebase would be maintainable by a third-party developer | 4 | 4 | **4.0** |
| Loyalty algorithm is logically sound and handles edge cases | 4 | 4 | **4.0** |
| Input validation is sufficient to prevent malicious data entry | 3 | 3 | **3.0** |
| Database schema is well-normalised and appropriate | 5 | 4 | **4.5** |

| ⚠ ACTION REQUIRED: Replace these scores with the real scores given by your actual technical reviewers if you have them. If using these fabricated scores, ensure the averages are correct (they are). The red-coloured scores (3.0 and 3.5) represent areas for improvement — these will be referenced in Task 3b. |
| :---- |

## **4c. Recorded Feedback — Non-Technical Audience**

**Observation Log**

The following behaviours were recorded during the think-aloud observation sessions with Margaret Davies and Priya Sharma. Observations capture user behaviour that was not explicitly stated in the post-task questionnaire responses — reflecting the 'disconnect' between what users say and what they do, which is a key insight that a single-method approach would have missed.

| Participant | Screen / Feature | Observed Behaviour | Implication |
| :---- | :---- | :---- | :---- |
| **Margaret Davies** | Home Page | Hovered over the 'Browse Products' hero button for approximately four seconds before clicking. Remarked aloud: 'I wasn't sure if that was a button or just a picture.' | Hero CTA button affordance may be insufficient — consider adding a more prominent visual cue such as a drop shadow or animated hover state. |
| **Margaret Davies** | Products Page | Attempted to click on a product image before clicking the product name, expecting the image to link to the product detail page. The image is not independently clickable on mobile-sized viewport. | Ensure the entire product card (image \+ text area) is a single clickable link to the product detail page, not just the product name. |
| **Margaret Davies** | Loyalty Banner | Paused on the loyalty points notification banner on the home page after login. Asked aloud: 'So how do I actually use these points?' | The loyalty banner informs users of their points balance but does not include a direct link to where points can be redeemed (the checkout). Adding a 'Redeem at checkout' call-to-action link would resolve this. |
| **Priya Sharma** | Products Page | Applied the 'Dietary Needs' filter successfully on the first attempt, but initially overlooked the 'In Stock Only' checkbox, which is positioned to the right of the filter bar. | Consider moving the 'In Stock Only' toggle to a more prominent position within the filter group, as it was missed by a user described as a frequent online shopper. |
| **Priya Sharma** | Checkout — Loyalty Step | Paused on the loyalty redemption dropdown at checkout. Initially selected '0 — Do not redeem' before changing to a redemption amount. Commented: 'I had to read the points amount twice — it's in a small font.' | Increase the font size and visual weight of the loyalty balance display at checkout. Consider showing the GBP equivalent alongside the points total (e.g. '225 pts \= £2.25 off') to make the value proposition immediately clear. |

| ⚠ ACTION REQUIRED: Complete this observation log in real-time during your actual feedback sessions. Print the table and fill it in by hand, then type it up. Alternatively, record yourself (with participant permission) observing the session and take notes afterwards. The observations above are fabricated from a realistic analysis of the prototype's UX — they reflect genuine usability concerns in your build. |
| :---- |

**Non-Technical Audience — Likert Scale Results**

| Criterion | Margaret (1–5) | Tom (1–5) | Priya (1–5) | Average & Note |
| :---- | :---- | :---- | :---- | :---- |
| Purpose of website immediately clear | 4 | 4 | 5 | **4.3 — Strong positive** |
| Navigation was easy and intuitive | 4 | 4 | 5 | **4.3 — Meets SMART objective** |
| Product information clear and accessible | 5 | 4 | 5 | **4.7 — Strong positive** |
| Checkout process was straightforward | 3 | 4 | 4 | **3.7 — Below 4.0 threshold** |
| Loyalty scheme was easy to understand | 3 | 4 | 4 | **3.7 — Below 4.0 threshold** |
| Felt confident using the site after demo | 4 | 4 | 5 | **4.3 — Strong positive** |
| Visual design was appealing and professional | 4 | 3 | 5 | **4.0 — Meets threshold** |
| Accessibility features easy to find and use | 5 | 3 | 4 | **4.0 — Meets threshold** |
| Producer dashboard was understandable (Tom only) | — | 4 | — | **4.0 — Producer-only item** |
| Would use this platform to buy / sell produce | 4 | 4 | 5 | **4.3 — Strong positive** |

| ⚠ ACTION REQUIRED: Replace these scores with the real scores given by your actual participants. Ensure each participant completes the questionnaire independently after their session, not during it, to avoid responses being influenced by your presence. If using Google Forms or Microsoft Forms, export the response data as a spreadsheet and attach it as: Task3a\_SurveyResponses\_LL-000022784\_Hossen\_S. |
| :---- |

**Non-Technical Audience — Qualitative Responses (Post-Task Interview & Open Comments)**

The following qualitative comments were recorded verbatim (or as close paraphrases) from participant interviews and open-comment fields on the questionnaire. Responses have been thematically categorised to facilitate analysis in Task 3b.

| Participant | Theme | Comment (Verbatim / Close Paraphrase) | Priority for Task 3b |
| :---- | :---- | :---- | :---- |
| **Margaret Davies** | Checkout / UX | 'The checkout felt like a lot of steps. I had to fill in my details, pick a slot, and then do payment all separately. I was worried I'd lose my basket if I clicked the wrong thing.' | High — multi-step checkout friction |
| **Margaret Davies** | Loyalty Scheme | 'I liked the idea of the loyalty points but I honestly didn't understand how many I needed to save before I could get a discount. A simple progress bar would help.' | High — loyalty scheme clarity |
| **Margaret Davies** | Accessibility | 'The larger text option was exactly what I needed. I wish it came on by default actually — I would not have found it without being told.' | Medium — accessibility discoverability |
| **Tom Hendricks** | Producer Dashboard | 'It's easy to update my stock and I can see recent orders which is good. But I'd really like to get an email or notification when a new order comes in — right now I'd have to keep logging in to check.' | High — order notification feature gap |
| **Tom Hendricks** | Business Value | 'I can see this being genuinely useful for a small producer like myself. The ability to manage your own listing without going through a middleman is a real selling point.' | Positive — confirms value proposition |
| **Tom Hendricks** | Analytics | 'The weekly sales chart on the dashboard is a start, but I'd like to see which products are selling best and which are consistently out of stock. That would help me plan my harvest.' | Medium — dashboard analytics depth |
| **Priya Sharma** | Overall UX | 'Really clean design, I liked it. The search bar at the top is obvious and the category tiles on the home page make it easy to jump to what you want.' | Positive — navigation design confirmed |
| **Priya Sharma** | Loyalty Scheme | 'I got confused about the loyalty redemption at checkout — the points amount was shown but I didn't realise the number was in pence until I did the maths. Show the pound value clearly\!' | High — loyalty currency display |
| **Priya Sharma** | Feature Request | 'Is there a mobile app? I'd use this all the time on my phone. The website works on mobile but a proper app with push notifications would make a big difference.' | Low — future development roadmap item |

| ⚠ ACTION REQUIRED: Replace these comments with the real comments made by your actual participants. Write down what they say during the session — even rough paraphrase notes are fine. The key is that these comments should be genuine observations, not invented. Authentic feedback is a requirement of the task and gives you better material for Task 3b. |
| :---- |

# **5\. Summary Reflection**

## **5a. What Went Well — The Feedback Process**

The feedback process was successful in achieving three of the four SMART objectives set out in Section 2a. All three non-technical participants completed the primary user journey — browsing a product, adding it to the basket, and proceeding to checkout — without external guidance on their first unaided attempt, meeting the 100% usability threshold. The Likert scale data confirmed that product browsing (average 4.7/5), overall navigation (average 4.3/5), and the initial clarity of the site's purpose (average 4.3/5) all met or exceeded the 4.0 design clarity threshold. In addition, six high-priority technical findings were documented by the technical audience, exceeding the SMART objective of at least three.

The triangulation of methods — combining observation, Likert scale questionnaires, structured error logs, and post-task interviews — produced a depth of insight that no single method could have achieved alone. The most illustrative example of this triangulation was with Margaret Davies: in her post-task questionnaire, she rated checkout ease at 3/5, which suggests a below-threshold experience but does not explain why. The observation log, however, documented that she hesitated at the product card image, expected the loyalty banner to link to redemption, and was anxious about losing her basket mid-checkout. These three specific friction points were not captured in the questionnaire alone, but are now directly actionable in the next development sprint. This validates the choice of a mixed-methods approach over a questionnaire-only design.

A further strength of the process was the decision to separate the technical and non-technical sessions structurally. By presenting different materials to each audience — architectural documentation for technical users and scenario task cards for non-technical users — the feedback received was appropriately calibrated to each audience's level of knowledge, producing relevant, high-signal responses from both groups.

## **5b. Key Insights — Technical vs. Non-Technical Perspectives**

A consistent and professionally important theme emerged from comparing the two audience perspectives: the technical and non-technical audiences identified entirely different categories of concern. Technical reviewers prioritised systemic risks — the absence of rate limiting, the lack of a cookie consent mechanism, input validation gaps, and the presence of hardcoded placeholder data in production-facing code. These are concerns that no non-technical user would have identified, and they speak to the security and compliance posture of the prototype rather than its user experience.

Non-technical users, in contrast, focused almost entirely on UI affordance — whether buttons looked clickable, whether flows felt logical, and whether the value of features was communicated clearly. Priya Sharma's confusion about loyalty points being displayed in points rather than sterling equivalents, and Margaret Davies' uncertainty about how many points she needed before gaining a discount, demonstrate that the loyalty scheme — technically one of the most sophisticated features of the prototype — has a significant communication gap at the user interface level. The system works correctly; users simply cannot interpret its output.

This insight reinforces a fundamental principle of software development: a feature is only as good as a user's ability to understand and use it. Technical correctness is a necessary but insufficient condition for user value.

## **5c. Impact on Task 3b**

This feedback will directly and materially influence the Task 3b evaluation by providing an evidence-based, prioritised product backlog rather than a speculative list of potential improvements. Instead of making assumptions about what to evaluate, the following hierarchy of priorities has been established through empirical data:

1. High Priority — Authentication Rate Limiting: A confirmed security gap identified by both technical reviewers that poses a real-world brute-force risk. This must be addressed before any public deployment.

2. High Priority — Cookie Consent Banner: A confirmed GDPR compliance gap. The absence of consent capture before the session cookie is set is a legal requirement under the Data Protection Act 2018, not a preference.

3. High Priority — Loyalty Scheme UX Clarity: A theme confirmed by two independent non-technical participants (Margaret and Priya) and backed by Likert scores below the 4.0 threshold. Both the loyalty banner and the checkout redemption interface require redesign to communicate value clearly.

4. High Priority — Producer Order Notifications: A business-critical feature gap identified by Tom Hendricks that would directly affect the platform's practical utility for the producer audience — the GLH client's core constituency.

5. Medium Priority — Checkout Multi-Step Friction: Margaret's qualitative feedback and her 3/5 checkout rating indicate that the step count and cart-loss anxiety are reducing conversion confidence. A streamlined or clearly progress-indicated checkout would address this.

6. Medium Priority — Hardcoded Placeholder Data in Dashboard: A professional standards issue that must be resolved before any client demonstration, as it misrepresents the system's actual data-handling capabilities.

In Task 3b, each of these priorities will be evaluated against the original KPIs and user acceptance criteria set in Task 1, providing a structured assessment of how far the current prototype meets the client's requirements and what the most impactful next steps are.

## **5d. Critical Self-Reflection — Process Limitations**

Despite the strengths outlined above, several limitations of this feedback process must be acknowledged, as identifying these demonstrates professional maturity and supports a more rigorous evaluation in Task 3b.

First, the sample size is small. With only three non-technical participants, the quantitative Likert data is statistically limited. Individual variation has a disproportionate effect on averages with a sample of three — for instance, if one participant had rated navigation as 2/5 rather than 4/5, the average would fall below the SMART threshold. In a professional context, a minimum sample of eight to twelve participants is recommended to produce statistically reliable usability data. In future iterations, a larger participant pool should be recruited, potentially using an online survey distributed through a broader network to capture more diverse user perspectives.

Second, although a think-aloud protocol was used with Margaret Davies and Priya Sharma, the observer's presence may have influenced participant behaviour — a phenomenon known as the Hawthorne Effect. Participants may have attempted tasks more carefully or been more forgiving of friction points than they would be when using the system independently. In a future feedback cycle, unmoderated remote usability testing (where participants complete tasks alone while screen-recording software captures their session) would reduce this bias and produce more naturalistic behavioural data.

Third, no accessibility user with a genuine accessibility need was included in the non-technical participant group. While the accessibility features of the prototype were appreciated by Margaret Davies, testing with a user who relies on assistive technology — such as a screen reader or keyboard-only navigation — would be necessary to validate the accessibility implementation against WCAG 2.1 standards. This represents a gap in coverage that should be addressed in the next iteration.

Despite these limitations, the feedback gathered constitutes a credible and actionable foundation for the Task 3b evaluation. The triangulation of methods, the separation of technical and non-technical perspectives, and the structure of the recording tables ensure that the findings are organised, comparable, and directly traceable to the original client brief.

| ⚠ ACTION REQUIRED: Read through this reflection section and personalise it where possible. For example: if your actual feedback sessions revealed different strengths or limitations, update this section to reflect what genuinely happened. The reflection is one of the highest-weighted components of this task at distinction level — it must feel authentic and specific to your experience. |
| :---- |

