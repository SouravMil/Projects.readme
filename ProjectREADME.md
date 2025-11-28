PROJECT 1 — OmniCX Customer Experience Platform
Duration: Jan 2019 – Jul 2021
Role: Senior Quality Assurance Engineer
Domains: Hospitality (Hotel Chain), Automobile, Retail Outlet, Banking
Tech Stack: Playwright, TypeScript/JavaScript, Postman, Jenkins, Git, REST APIs, SQL, JSON, HTML/CSS
Testing Types: UI, Functional, Regression, API Testing, UAT Support
________________________________________
Project Description
OmniCX is an enterprise-grade customer experience and case management platform implemented across large B2C industries such as hospitality, automobile, retail, and banking.
The solution offers:
•	A client desktop application for customer service teams
•	Multi-channel case handling (email, chat, voice)
•	Workflow-driven ticket creation and resolution
•	Customer profile and interaction history
•	SLA monitoring, reporting dashboards, and audit features
The platform integrates with CRM systems, payment gateways, loyalty engines, and order management platforms, supporting high-volume customer interactions.
________________________________________
Responsibilities
•	Owned end-to-end UI, Functional, Regression, and API testing for the client desktop and web-based modules.
•	Designed comprehensive test scenarios covering case lifecycle, assignment rules, SLA policies, escalations, and omni-channel workflows.
•	Built a custom Playwright automation framework (POM structure, utilities, configuration management, reusable components, reporting).
•	Developed smoke and regression automation suites, optimizing coverage for frequent releases.
•	Performed API testing using Postman and Playwright’s Request API for workflows such as ticket creation, updates, agent transitions, backend validations.
•	Validated integrations between the client desktop app and CRM, IVR, loyalty systems, and customer profile microservices.
•	Assisted UAT teams across sectors by reproducing production issues, verifying critical fixes, and supporting release readiness.
•	Collaborated with developers and product stakeholders to clarify requirements, identify bottlenecks, and improve workflow consistency.
•	Contributed to CI/CD setup in Jenkins, enhancing automated build verification processes.
________________________________________


Key Challenges & Solutions
•	Dynamic UI elements within the client desktop app led to flaky tests → implemented custom wait logic, stable locators, and wrapper functions.
•	Highly configurable workflows across industries required a scalable approach → designed modular automation components enabling fast updates.
•	Heavy reliance on API-driven backend logic → built API-first data setup to reduce test execution time and enhance reliability.

PROJECT 2 — E-Store E-commerce Platform
Duration: May 2021 – Oct 2022
Role: Senior Quality Assurance Engineer
Domains: Apparel, Electronics, Restaurant
Tech Stack: Playwright, TypeScript/JavaScript, Postman, Jenkins, Git, REST APIs, SQL, JSON, HTML/CSS
Testing Types: UI, Functional, API Testing, Regression, Accessibility Testing
________________________________________
Project Description
E-store is a multi-category e-commerce platform offering products across apparel, electronics, and restaurant merchandise. The system allows customers to browse products, view detailed descriptions, manage carts, complete secure checkouts, and track orders.
The platform supports:
•	Advanced product search & filtering
•	Dynamic product detail pages
•	Cart & multi-step checkout flows
•	Payment integrations (cards, UPI, wallets, COD)
•	Promo codes, discounts, and loyalty points
•	Multi-environment deployment (DEV, QA, Staging, Production)
________________________________________
Responsibilities
•	Performed UI, Functional, API, Regression, and Accessibility testing across search, product details, cart, and checkout modules.
•	Validated product catalog behavior, price variations, inventory sync, and category-level display logic.
•	Implemented Playwright automation for critical e-commerce flows, including:
o	End-to-end product search → cart → checkout
o	Cart updates, quantity changes, and applied promotions
o	Login & authentication validations
o	API workflows for customer data and order creation
•	Built reusable Page Object Model-based automation covering shared components and utility functions.
•	Developed and maintained a regression suite supporting release cycles for multiple brands.
•	Performed accessibility testing (WCAG standards) for key customer journeys.
•	Identified and logged critical issues related to cart calculations, PDP rendering, promo code rules, and multi-environment inconsistencies.
•	Collaborated with product managers and developers to clarify requirements, test edge cases, and support rapid feature rollout.
________________________________________
Key Challenges & Solutions
•	Rapid product updates causing frequent UI/API changes → created modular test components for faster script updates.
•	Flaky UI due to dynamic search and auto-suggestions → implemented stable locators and custom wait strategies.
•	Promo/discount validation complexity → built API-level test data setup to verify pricing logic precisely.
•	Multi-environment discrepancies → introduced environment-based configs and automated sanity checks.

PROJECT 3 — Travel Ease Reservation System
Duration: Nov 2022 – Aug 2023
Role: Senior Quality Assurance Engineer
Domain: Airlines
Tech Stack: Playwright, TypeScript/JavaScript, Postman, Jenkins, Git, REST APIs, SQL, JSON
Testing Types: UI, Functional, Regression, API Testing, Integration, UAT Support
________________________________________
Project Description
Travel Ease is an end-to-end airline reservation and booking platform enabling customers to search flights, check availability, manage existing bookings, and complete secure reservations. The system supports:
•	Real-time flight availability and pricing
•	Multi-city and round-trip booking
•	User profile management and saved journeys
•	Seat selection, add-ons, and ancillary services
•	Payment integrations (cards, UPI, wallets)
•	Booking modifications and cancellations
•	Multi-timezone compatibility across regions
________________________________________
Responsibilities
•	Performed UI, Functional, API, Regression, Integration, and UAT testing across search, booking, and user management modules.
•	Validated flight availability, pricing variations, booking rules, fare classes, and seat selection flows.
•	Tested user profile features including login, saved preferences, booking history, and passenger details.
•	Conducted API testing for flight availability, reservation creation, booking modification, and cancellation flows.
•	Implemented Playwright automation for:
o	API-based reservation creation to speed up test data setup
o	Calendar/date-picker validations
o	Multi-step booking flow validations
•	Defined critical regression scenarios and maintained structured test documentation for weekly airline-specific releases.
•	Collaborated with developers and business analysts to review requirements, identify gaps, and validate end-to-end customer journeys.
•	Supported cross-functional teams during UAT and pre-production releases.
________________________________________
Key Challenges & Solutions
•	Timezone issues impacting pricing and availability → implemented strict timezone handling, validated responses against backend APIs, and created timezone-aware test scenarios.
•	High dependency on real-time APIs → built API-first workflows to reduce UI instability and speed up testing.
•	Complex booking rules across fare classes → documented clear decision paths and automated repetitive checks using Playwright.


PROJECT 4 — RetailOps Internal Dashboard
Duration: Sep 2023 – Jul 2025
Role: Senior Quality Assurance Engineer
Domains: Automobile, Retail
Tech Stack: Playwright, TypeScript/JavaScript, Postman, Jenkins, Git, REST APIs, SQL, JSON
Testing Types: UI, Functional, Regression, API Testing, Integration, UAT Support
________________________________________
Project Description
RetailOps is an internal operations dashboard used by retail and automobile brands to manage customer survey programs, automate email invitations, collect customer feedback, and generate actionable insights through advanced reporting.
The system enables:
•	Automated customer survey scheduling
•	Email & SMS invitation workflows
•	Feedback capture and sentiment tracking
•	Multi-format reporting dashboards
•	Role-based access for retail associates, managers, and regional heads
•	Integrations with CRM, marketing systems, and internal data pipelines
________________________________________
Responsibilities
•	Performed UI, Functional, Regression, API, Integration, and UAT testing across survey workflows, email invitation logic, feedback forms, and reporting modules.
•	Validated end-to-end flows including survey creation, customer segmentation, dispatch of invitations, response collection, and analytics generation.
•	Conducted API testing for survey configuration, feedback submission, data ingestion, and reporting endpoints.
•	Implemented Playwright automation covering:
o	Key survey workflows
o	CRUD operations
o	API-based test data setup
o	End-to-end role-based access journeys
o	Regression suite development for major releases
•	Partnered with development and product teams to clarify business rules, test edge cases, and ensure accuracy of reports across automobile and retail business units.
•	Verified email dispatch logic, template rendering, tracking URLs, and bounce/response handling.
________________________________________
Key Challenges & Solutions
•	Backend migration from legacy system to new service architecture → created dual test suites for old and new APIs, validated data consistency across systems, and automated comparison checks to ensure smooth transition.
•	Dynamic dataset and expanding reporting structures → built modular test coverage with reusable components.
•	Frequent workflow changes based on brand-specific rules → maintained structured regression and API-first data creation to stabilize testing.

