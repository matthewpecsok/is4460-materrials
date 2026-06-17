**Module 2 \-  Product Management: Requirements Acquisition and Planning**

Author: Professor Matthew Pecsok  
Course: IS4460 Web Application Development

Table of Contents

[Introduction: Before You Build, Decide What Should Be Built	1](#introduction:-before-you-build,-decide-what-should-be-built)

[Why this matters in business	1](#why-this-matters-in-business)

[Part 1: Start with the Problem or Opportunity	2](#part-1:-start-with-the-problem-or-opportunity)

[Part 2: Understand Stakeholders and Users	3](#part-2:-understand-stakeholders-and-users)

[Part 3: Gathering Requirements	4](#part-3:-gathering-requirements)

[Part 4: Use Cases and User Flows	4](#part-4:-use-cases-and-user-flows)

[Part 5: Prioritize Scope and Define the MVP	5](#part-5:-prioritize-scope-and-define-the-mvp)

[Part 6: Agile Development and the Product Backlog	6](#part-6:-agile-development-and-the-product-backlog)

[Part 7: Wireframing for Communication	8](#part-7:-wireframing-for-communication)

[Part 8: Incremental Development	10](#part-8:-incremental-development)

# Introduction: Before You Build, Decide What Should Be Built {#introduction:-before-you-build,-decide-what-should-be-built}

In this phase of the course, your job is not to start coding immediately. Your job is to think like a product manager.

A product manager is responsible for helping a team decide what should be built, who it should serve, what problem it should solve, and what should be prioritized first. Product managers do not simply collect random feature requests and hand them to developers. They interpret business goals, user needs, technical constraints, and stakeholder opinions, then turn that information into a clear direction for the product.

## Why this matters in business {#why-this-matters-in-business}

Building a successful application requires more than writing good code. Many fail because the team misunderstood the problem, built for the wrong user, included too many features, ignored important stakeholders, or failed to define what success looked like. Good product planning reduces these risks before development begins.

For this class, you are working on a compressed timeline. That makes this phase even more important. You will not have weeks or months to explore every possible feature. You need to identify the most important problem, understand the users well enough to make reasonable decisions, and produce a simple plan that can guide the first version of your web application.

The central product question. The main question for this phase is: What problem are we solving, for whom, and why does it matter? If you cannot answer that question clearly, you are not ready to build.

## Part 1: Start with the Problem or Opportunity {#part-1:-start-with-the-problem-or-opportunity}

**Begin with the problem**

Students often begin with a solution: “We are building a website that does X.” That is understandable, but it skips the most important product management question. Before deciding what the website does, you need to understand why it should exist.

A stronger starting point is the problem. Who is struggling? What are they trying to accomplish? What is frustrating, inefficient, confusing, expensive, or missing in the current situation? What happens if the problem is not solved?

For example, “we are building a restaurant website” is not a strong problem statement. It describes a type of site, but it does not explain the business or user need. A better version might say that new customers struggle to understand whether the restaurant is a good fit for their dietary needs, price expectations, and schedule, which causes them to choose a different restaurant instead. That statement gives the product a purpose.

A useful problem statement identifies a specific user, a specific problem, the cause of the problem, and the consequence. You can use this structure: A specific user struggles with a specific problem because of a specific reason, which leads to a negative outcome.

Once the problem is clear, you can define the value proposition. A value proposition explains why the product is worth building. It should describe who the product helps, what outcome it creates, and why this solution is better than the user’s current alternative. A product without a clear value proposition is just a collection of pages. A product with a clear value proposition has a reason to exist.

For this section, you should produce a concise problem statement and a short value proposition written in complete sentences.

## Part 2: Understand Stakeholders and Users {#part-2:-understand-stakeholders-and-users}

Stakeholders are not all the same. A stakeholder is anyone who has an interest in the product. Some stakeholders will use the system directly. Others may fund it, manage it, support it, approve it, or be affected by it. In business settings, one of the first mistakes teams make is assuming that “the user” and “the customer” are always the same person. They often are not.

For example, in a company purchasing a scheduling system, employees may be the end users, managers may care about productivity, executives may approve the budget, and IT staff may be responsible for supporting the system. Each group has different goals and concerns. A product manager must understand these differences.

You should **separate stakeholders** into meaningful categories. End users interact with the system directly. Decision makers or economic buyers care about whether the product supports business goals. Influencers may shape requirements even if they do not use the product daily. Operators or support staff care about maintainability, reliability, and ease of administration.

These groups may agree on the general need for a product while disagreeing about priorities. A business owner may want the site to collect customer leads. A customer may want the site to provide information quickly without asking for personal information. A staff member may want fewer manual updates. These perspectives are all legitimate, but they cannot always be satisfied equally.

Your task is to identify the key stakeholders and explain what each one cares about. You should also create one or two lightweight personas. A persona is a brief description of a representative user. It does not need to be elaborate. It should be realistic enough to help you make decisions about the product.

A useful persona includes the user’s role, goals, frustrations, and context. The purpose is not to create a fictional biography. The purpose is to keep your design decisions grounded in real user needs.

## Part 3: Gathering Requirements  {#part-3:-gathering-requirements}

Requirements are more than feature requests. **Requirements** describe what the product needs to do or how it needs to perform. However, good requirements do not come from simply asking, “What features do you want?” Stakeholders often describe solutions before they fully explain the problem. Part of your job is to ask better questions.

Instead of accepting a request at face value, try to understand the need behind it. If a stakeholder says, “We need a search bar,” ask what users are searching for, why browsing is not enough, what kind of results would be useful, and how the user should know they found the right item. These questions turn a vague feature request into a more precise requirement.

A weak requirement might say, “Users can search recipes.” A stronger requirement would explain that users can enter a keyword or dietary preference, view matching recipes, and identify which recipe best fits their needs based on title, ingredients, and preparation time. The second version is more useful because it describes the user action, the system response, and the intended outcome.

You should distinguish between functional and non-functional requirements. Functional requirements describe what the system does. Examples include viewing a product list, submitting a contact form, filtering search results, or creating an account. Non-functional requirements describe qualities or constraints of the system. These may include usability, performance, accessibility, reliability, privacy, or mobile responsiveness.

Some requirements should also include **acceptance criteria**. Acceptance criteria define what must be true for the requirement to be considered complete. For example, a form submission requirement might be complete only if required fields are validated, the user receives confirmation, and the submitted information is stored or routed appropriately.

Acceptance criteria matter because they reduce ambiguity. Without them, different people may think a requirement is “done” in different ways.

What to produce. For this section, your goal is to produce a clear set of requirements that reflects structured thinking. Do not create a random wish list. Requirements should connect back to the problem, the users, and the value proposition.

## Part 4: Use Cases and User Flows {#part-4:-use-cases-and-user-flows}

From requirements to interaction. After gathering requirements, you need to describe how users will actually interact with the system. This is where use cases and user flows become useful.

A **use case** describes a user goal and the interaction needed to accomplish it. It usually identifies the actor, the goal, the basic steps, and the expected outcome. For example, a use case might describe how a prospective customer checks whether a service is available, how a student finds an assignment, or how a traveler compares event options.

A **user flow** is more visual and sequence-oriented. It shows how the user moves from one step to another through the interface. A user flow might begin on the homepage, move to a category page, continue to a detail page, and end with a form submission or decision.

Strong user flows include decision points. What happens if the user does not find what they want? What happens if required information is missing? What happens after the user clicks the main button? These questions help you identify missing pages, unclear navigation, or unrealistic assumptions.

The goal is not to create a perfect diagram. The goal is to make the interaction logical. If you cannot explain how a user moves through the product, the product is probably not ready to build.

For this section, you should create a small number of use cases and at least one user flow that represents a core interaction.

## Part 5: Prioritize Scope and Define the MVP {#part-5:-prioritize-scope-and-define-the-mvp}

You cannot build everything. This is not a weakness in the assignment; it is the reality of product development. Every product team works with limited time, limited money, limited attention, and limited technical capacity. Product management is largely the work of making trade-offs under these constraints.

The goal is to define a **minimum viable product**, or **MVP**. An MVP is the smallest version of the product that still solves the core problem well enough to create value and generate learning. It is not the worst version of the product, and it is not an excuse to build something careless. It is a focused first version.

A strong MVP includes the features required to test the product’s core value proposition. It leaves out features that may be useful later but are not essential right now. For example, a restaurant website may need a clear menu, hours, location, and reservation request form before it needs loyalty accounts, personalized recommendations, or advanced animations.

Prioritization of work requires judgment. Prioritization is not just a technical exercise. Different stakeholders may have opposing viewpoints. One customer group may want speed and simplicity, while another may want more options and customization. A business owner may want to collect customer information, while users may resist anything that adds friction. Employees may want fewer manual tasks, while managers may want more reporting and oversight.

Your job is not to satisfy everyone equally. Your job is to make a defensible choice. That choice should be informed by available evidence, such as user needs, business impact, frequency of use, risk, and feasibility. However, you will rarely have perfect data. Product managers often combine evidence with judgment and intuition. The key is not to pretend the answer is obvious. The key is to explain why your decision is reasonable.

You should also be prepared to push back. If a stakeholder asks for something unrealistic, unclear, or outside the current scope, you should not automatically agree. You can acknowledge the request, explain the constraint, and place the idea in the backlog for future consideration. In real product work, saying “not yet” is often as important as saying “yes.”

For this section, you should define the MVP and explain what is included, what is excluded, and why.

## Part 6: Agile Development and the Product Backlog {#part-6:-agile-development-and-the-product-backlog}

Modern software teams often use agile development methods. Agile does not mean “no planning.” It means planning in smaller increments, building iteratively, and adapting as the team learns more.

In a traditional project, a team might try to define everything upfront, build for a long period of time, and release the product near the end. Agile approaches reduce that risk by breaking work into smaller pieces. Teams build, review, learn, and adjust repeatedly.

A **product backlog** is the prioritized list of work the team may eventually build. It includes features, improvements, fixes, research tasks, and future ideas. The backlog is not a promise that everything will be completed. It is a living planning tool.

AI accelerates development, not judgment. Tasks that once took substantial time, such as creating starter code, generating page layouts, drafting forms, troubleshooting errors, or producing first versions of common features, can often happen much faster with AI assistance. This means teams may be able to move from idea to prototype more quickly than before.

However, faster development does not remove the need for product judgment. In fact, it makes backlog discipline more important. If a team can generate code quickly, it can also generate the wrong code quickly. A poorly curated backlog can lead to a product filled with disconnected features, unnecessary complexity, and work that does not support the business goal.

A strong backlog should be backed by good business decisions. Items should be included because they connect to user needs, stakeholder priorities, revenue opportunities, operational improvements, risk reduction, or learning goals. AI can help produce possible backlog items, but it cannot replace the responsibility to evaluate which items deserve attention.

Larger bodies of work are often called **epics**. An epic is too large to complete as a single small task, so it is broken into smaller user stories. A user story describes a specific capability from the user’s perspective. A common format is: *“As a \[type of user\], I want \[capability\], so that \[benefit\].”* For example: *“As a prospective customer, I want to view available appointment times, so that I can decide whether the service fits my schedule.”*

Estimation is a development-team responsibility. Developers then estimate the effort required for these stories. Importantly, product managers do not usually assign exact build times themselves. Estimation is a collaborative process handled primarily by the development team because developers understand the technical complexity of implementation. Product managers define and prioritize the work; developers help estimate what it will take.

These estimates influence scope. If a high-priority feature turns out to be very difficult to build, the team may simplify it, delay it, or split it into smaller pieces. This is where product thinking and technical thinking meet.

**Agile** and MVP are closely connected. The MVP defines the focused first version of the product. **Agile development** describes how the team can build toward that version in small increments called **sprints**. The first sprint might produce a very rough version of a core page. A later sprint might add forms, validation, navigation, or better content. Each increment should move the product closer to delivering the core value.

The MVP is not always static. As the team learns from users and stakeholders, the MVP may change. A feature that seemed essential may become less important. A small overlooked need may become critical. Agile development allows the team to adjust instead of being locked into an early assumption.

In this class, we cannot fully replicate agile development. You do not have a full product team, formal sprint ceremonies, professional developers estimating work, or several months of iteration. Instead, you are using a simplified version of the same logic. Your prioritized feature list acts as a basic backlog. Your MVP defines what belongs in the first realistic version. Your wireframes and requirements help communicate what should be built next.

The purpose is not to memorize agile terminology. The purpose is to understand how product decisions connect to real development work.

## Part 7: Wireframing for Communication  {#part-7:-wireframing-for-communication}

Wireframes show structure, not polish. A wireframe is a simple representation of a page or screen. It shows structure, content, navigation, and interaction points. It does not need polished colors, fonts, images, or branding. At this stage, the goal is communication, not visual design.

Wireframes are useful because they make abstract requirements concrete. A stakeholder may say they want an “easy homepage,” but that phrase means very little until you show what appears on the page. Does the homepage explain the service? Does it show featured items? Does it include a call-to-action? Does it direct users to different sections? A wireframe forces those decisions into the open.

A good wireframe should make the purpose of the page clear. It should show what information appears, what actions users can take, and how the user moves to the next step. It should also connect back to the requirements and user flows. If a requirement says users need to compare options, the wireframe should show where and how that comparison happens

**Weak Prompts for Development**

Wireframes are also useful when working with AI coding tools. A vague prompt such as “make me a homepage” gives the AI too much freedom and often produces generic results. A wireframe gives you a more specific basis for prompting. Instead of asking AI to invent the site, you can describe the page structure you already planned: the header, navigation, hero section, content areas, buttons, forms, and links to other pages.

In this sense, the wireframe becomes a prompt-planning tool. It helps you translate product decisions into clear instructions for the AI. You are not asking AI to decide what the site should be. You are using AI to help implement a site that you have already defined through requirements, user flows, prioritization, and stakeholder feedback.

For example, a stronger prompt might say: 

*“Create a Django template for the homepage of a local restaurant website. The page should include a top navigation bar with links to Menu, Hours, Location, and Reservations; a hero section explaining the restaurant’s value proposition; a featured menu section with three sample dishes; and a reservation call-to-action near the bottom. Use basic HTML and CSS and keep the layout simple.”* 

This prompt is stronger because it comes from a product plan, not from a vague idea.

An even stronger prompt would also describe how repeated site elements should be structured. For example: 

*“Create a Django homepage template for a local restaurant website using basic HTML and CSS. The site should have a top navigation bar with links to Home, Menu, Hours, Location, and Reservations. Because this same navigation bar will appear on every page, design it as a reusable Django template partial that can be included across multiple pages instead of duplicated manually. The homepage should include a hero section explaining the restaurant’s value proposition, a featured menu section with three sample dishes, and a reservation call-to-action near the bottom. Keep the layout simple and make the HTML easy to understand for a beginner.”* 

This prompt is better because it does not only describe what the page should look like; it also gives guidance about how the site should be organized for reuse and consistency.

Shared CSS and site-wide consistency

The same idea applies to CSS. A weak prompt may ask AI to style one page by placing CSS directly inside that page. That may work for a single page, but it becomes a problem when the site grows. If each page has its own separate styling, the site becomes harder to maintain and may look inconsistent. A stronger prompt explains that basic page styling should be controlled through a shared CSS file that applies across the whole website.

For example, you might prompt: “Create the homepage template and a shared CSS file for this Django site. Use the CSS file to define the site-wide visual style, including fonts, page width, navigation bar styling, buttons, headings, spacing, and footer styling. Link the template to the shared stylesheet so the same design can be reused across future pages. Avoid putting large amounts of CSS directly inside the HTML template unless it is only for a very small page-specific adjustment.” This prompt is stronger because it treats CSS as part of the site’s overall design system, not just as decoration for one page.

This matters because product decisions often need to be reflected consistently across the whole site. If the business wants the site to feel simple, trustworthy, modern, or student-friendly, that should not be redesigned separately on every page. A shared stylesheet helps maintain consistency while making future changes easier.

For this course, you may create wireframes using sketches, slides, or basic HTML and CSS. HTML and CSS are useful because they help you begin translating product ideas into the structure of a real website, even if the site does not yet have full backend functionality.

You should create at least two wireframes: a homepage and one page that supports a core feature. These wireframes should not be random page designs. They should reflect the problem, requirements, user flow, MVP scope, and prompts you will use to begin building the site.

## Part 8: Incremental Development {#part-8:-incremental-development}

Your first version will not be perfect. That is normal. Product planning is an iterative process. You make an initial interpretation of the problem, present it to stakeholders, receive feedback, and revise your thinking.

Validation does not mean asking, “Do you like it?” That question is too vague. Better validation questions include: Does this solve the core problem? What is missing? What seems unnecessary? Which feature matters most? What would prevent a user from completing the main task?

You should treat stakeholder feedback as evidence, not as automatic instruction. Sometimes feedback reveals a real flaw. Sometimes it reflects one person’s preference. Sometimes it conflicts with other stakeholder needs. Your job is to interpret the feedback and decide what should change.

Document what changed and why. When you revise your work, document the change and the reason for it. For example, you might revise a wireframe because users needed clearer navigation, move a feature out of the MVP because it was too complex, or add a requirement because stakeholder feedback revealed an overlooked need.

The important point is that your final plan should show learning. A strong product manager does not merely defend the first idea. A strong product manager improves the product direction based on *evidence, constraints, and judgment*.

Your final submission for this phase should include a complete product planning package. It should include a problem statement and value proposition, stakeholder analysis and personas, functional and non-functional requirements, acceptance criteria for selected requirements, use cases and at least one user flow, a prioritized backlog with a defined MVP, wireframes for at least two pages, and evidence of stakeholder feedback and revision.

These pieces should connect to each other. The problem statement should explain why the product matters. The stakeholder analysis should explain whose needs are being considered. The requirements should describe what the system must do. The user flows should show how people interact with it. The MVP should explain what will be built first. The wireframes should make that plan visible. The feedback section should show how your thinking improved.

Do not treat the deliverables as separate assignments. Treat them as parts of one product planning argument. Strong work begins with a clear problem and stays connected to that problem throughout the document. It shows that you understand different stakeholder needs and that you can make trade-offs when those needs conflict. It defines requirements clearly enough that someone else could understand what the system should do. It uses wireframes to communicate product decisions rather than merely decorate pages.

Strong work also shows prioritization. It makes clear what belongs in the MVP and what should wait. It explains why decisions were made using available evidence, business reasoning, user needs, and reasonable judgment.

Weak work usually jumps straight to features. It may include a list of pages without explaining why those pages matter. It may try to include everything, avoid difficult trade-offs, or treat stakeholder requests as commands instead of evidence. It may also include wireframes that look disconnected from the requirements.

The difference between strong and weak work is not artistic skill. The difference is clarity of thinking.

AI tools can now help generate code, layouts, documentation, and prototypes quickly. That does not make product thinking less important. It makes product thinking more important.

If development is easier to accelerate, then the higher-value skill is deciding what should be accelerated. Businesses do not benefit simply because a team can produce more features faster. They benefit when the right features are chosen, prioritized, tested, and refined. Businesses need people who can understand problems, ask good questions, balance stakeholder needs, define scope, curate a meaningful backlog, prioritize work, and communicate product direction clearly.

That is the capability you are practicing in this phase.