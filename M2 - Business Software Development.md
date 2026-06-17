**Module 2 - Product Management: Requirements Acquisition and Planning**

Author: Professor Matthew Pecsok
Course: IS4460 Web Application Development

Table of Contents

[Introduction: Before You Build, Decide What Should Be Built](#introduction:-before-you-build,-decide-what-should-be-built)

[Why this matters in business](#why-this-matters-in-business)

[Part 1: Start with the Problem or Opportunity](#part-1:-start-with-the-problem-or-opportunity)

[Part 2: Understand Stakeholders and Users](#part-2:-understand-stakeholders-and-users)

[Part 3: Gathering Requirements](#part-3:-gathering-requirements)

[Part 4: Use Cases and User Flows](#part-4:-use-cases-and-user-flows)

[Part 5: Prioritize Scope and Define the MVP](#part-5:-prioritize-scope-and-define-the-mvp)

[Part 6: Agile Development and the Product Backlog](#part-6:-agile-development-and-the-product-backlog)

[Part 7: Wireframing for Communication](#part-7:-wireframing-for-communication)

[Part 8: Incremental Development](#part-8:-incremental-development)

# Introduction: Before You Build, Decide What Should Be Built {#introduction:-before-you-build,-decide-what-should-be-built}

In this phase of the course, your task is not to start coding immediately. Focus first on the product decisions.

A product manager helps a team decide what to build, who it should serve, what problem it should address, and what to prioritize first. Rather than collecting feature requests and passing them to developers, a product manager gathers business goals, user needs, technical constraints, and stakeholder input, and turns that information into a clear direction for the product.

## Why this matters in business {#why-this-matters-in-business}

Successful applications require more than well-written code. Projects can stumble when teams misunderstand the problem, design for the wrong users, include too many features, overlook key stakeholders, or fail to define success. Thoughtful product planning helps reduce those risks before development begins.

In this class you will work on a compressed timeline. That makes early planning especially useful: you will not have long to explore every possible feature. Identify the most important problem, understand the users enough to make reasonable decisions, and produce a concise plan to guide the first version of your web application.

The central product question is: What problem are we solving, for whom, and why does it matter? If you cannot answer that clearly, you are not ready to build.

## Part 1: Start with the Problem or Opportunity {#part-1:-start-with-the-problem-or-opportunity}

**Begin with the problem**

Many projects start by defining a solution (“We will build a website that does X”). That approach skips a key question: why should the product exist?

A better starting point is the problem. Who is struggling? What are they trying to accomplish? What is inefficient, confusing, costly, or missing in the current situation? What happens if the problem is not addressed?

For example, “we are building a restaurant website” only names a type of site. A stronger problem statement explains the user or business need, for instance that prospective diners have trouble judging whether the restaurant fits their dietary needs, budget, or schedule, and so choose elsewhere. That gives the product purpose.

A useful problem statement identifies a specific user, a specific problem, its cause, and the negative outcome. One helpful template is: A specific user struggles with a specific problem because of a specific reason, which leads to a negative outcome.

Once the problem is clear, define the value proposition. The value proposition describes who the product helps, what outcome it delivers, and why it is preferable to the current alternative. A product without a clear value proposition risks becoming a collection of pages; with one, it has a reason to exist.

Produce a concise problem statement and a short value proposition written in complete sentences for this section.

## Part 2: Understand Stakeholders and Users {#part-2:-understand-stakeholders-and-users}

Stakeholders are not all the same. A stakeholder is anyone with an interest in the product. Some will use the system directly; others may fund, manage, support, approve, or be affected by it. In practice, “the user” and “the customer” are often different people.

For example, when a company buys a scheduling system, employees may be end users, managers may focus on productivity, executives may approve budgets, and IT staff may handle support. Each group has different goals and concerns; product decisions should account for those differences.

Separate stakeholders into meaningful categories. End users interact with the system directly. Decision makers or buyers care about business outcomes. Influencers may shape requirements without daily use. Operators and support staff care about maintainability and reliability.

These groups may agree on the general need while disagreeing about priorities. A business owner might want the site to capture leads, while customers may prefer quick access to information without sharing personal details. These perspectives are all legitimate but cannot always be satisfied equally.

Identify the key stakeholders and explain what each one cares about. Create one or two lightweight personas: brief descriptions of representative users that include role, goals, frustrations, and context. Personas should be realistic enough to guide decisions, not elaborate biographies.

## Part 3: Gathering Requirements {#part-3:-gathering-requirements}

Requirements are more than feature requests. Requirements describe what the product must do or how it must perform. Good requirements come from understanding needs, not from simply asking “What features do you want?” Stakeholders sometimes propose solutions before explaining the problem; your role includes asking clarifying questions.

Rather than accepting a request at face value, probe the underlying need. If a stakeholder asks for a search bar, ask what users search for, why browsing is insufficient, what results would be useful, and how users will know they found the right item. These follow-ups turn vague ideas into concrete requirements.

A weak requirement might say, “Users can search recipes.” A stronger one would explain that users can enter keywords or dietary preferences, view matching recipes, and identify suitable options based on title, ingredients, and preparation time. The stronger version states the user action, system response, and intended outcome.

Distinguish between functional and non-functional requirements. Functional requirements describe system behaviors (viewing a product list, submitting a form, filtering results, creating an account). Non-functional requirements describe qualities or constraints (usability, performance, accessibility, reliability, privacy, mobile responsiveness).

Include acceptance criteria where appropriate. Acceptance criteria specify what must be true for a requirement to be considered complete. For instance, a form submission requirement might require field validation, a confirmation message, and correct storage or routing of submitted data.

Acceptance criteria reduce ambiguity so different people share the same definition of “done.”

For this section, produce a clear set of requirements that ties back to the problem, the users, and the value proposition.

## Part 4: Use Cases and User Flows {#part-4:-use-cases-and-user-flows}

From requirements to interaction. After gathering requirements, describe how users will interact with the system using use cases and user flows.

A **use case** describes a user goal and the steps to achieve it, naming the actor, the goal, the basic steps, and the expected outcome. For example, a use case can show how a prospective customer checks service availability, how a student finds an assignment, or how a traveler compares options.

A **user flow** is sequence-oriented and shows how a user moves from step to step. A flow might start on the homepage, continue to a category page, go to a detail page, and end with a form submission or decision.

Good user flows include decision points: What if the user does not find what they want? What if required information is missing? What happens after the primary action? These questions reveal missing pages, unclear navigation, or unrealistic assumptions.

The goal is a logical interaction model, not a perfect diagram. If you cannot explain how a user moves through the product, the product is probably not ready to build.

Create a small number of use cases and at least one user flow that represents a core interaction for this section.

## Part 5: Prioritize Scope and Define the MVP {#part-5:-prioritize-scope-and-define-the-mvp}

You cannot build everything. Teams work with limited time, budget, attention, and technical capacity. Product management involves making trade-offs under those constraints.

Define a **minimum viable product (MVP)**: the smallest product that addresses the core problem well enough to create value and generate useful feedback. An MVP is a focused first version, not a careless or incomplete product.

An effective MVP includes only the features needed to test the core value proposition and leaves non-essential features for later. For instance, a restaurant site might prioritize a clear menu, hours, location, and reservation request form before adding loyalty accounts or personalized recommendations.

Prioritization requires judgment and consideration of different stakeholder viewpoints. One group may prioritize speed and simplicity, another customization. A business owner may want customer data, while users may resist extra friction. Your job is to make a defensible choice and explain it.

Use available evidence—user needs, likely business impact, frequency of use, risk, and feasibility—combined with judgment to support your decision. You will rarely have perfect data; explain why your choice is reasonable.

Be prepared to push back on unrealistic or unclear requests. Acknowledge the idea, explain constraints, and place it in the backlog for future consideration. Saying “not yet” is often as important as saying “yes.”

Define the MVP and explain what is included, what is excluded, and why.

## Part 6: Agile Development and the Product Backlog {#part-6:-agile-development-and-the-product-backlog}

Many development teams use iterative methods that emphasize planning in smaller increments, building iteratively, and adapting as the team learns.

In contrast to a plan-then-build approach, iterative methods break work into smaller pieces so teams can build, review, learn, and adjust more frequently.

A **product backlog** is a prioritized list of possible work: features, improvements, fixes, research tasks, and ideas. It is a living planning tool, not a promise that everything will be completed.

AI tools can speed up many development tasks, such as creating starter code, generating layouts, drafting forms, and producing initial versions of common features. That can shorten the time from idea to prototype.

However, faster production does not replace the need for product judgment. If a team can generate code quickly, it can also generate the wrong code quickly. A poorly curated backlog can lead to disconnected features, unnecessary complexity, and work that does not support the product goals.

A strong backlog reflects business decisions: items are included because they connect to user needs, stakeholder priorities, revenue opportunities, operational improvements, risk reduction, or learning goals. AI can suggest items, but it cannot replace the responsibility to evaluate which items deserve attention.

Larger bodies of work are often called **epics**, which are broken into smaller **user stories**. A user story captures a specific capability from the user’s perspective, commonly written: “As a [type of user], I want [capability], so that [benefit].” For example: “As a prospective customer, I want to view available appointment times, so that I can decide whether the service fits my schedule.”

Estimation is primarily a development-team activity. Developers estimate effort for stories because they understand technical complexity. Product managers define and prioritize the work; developers help estimate what it will take.

Estimates influence scope. If a high-priority feature proves difficult, the team may simplify it, delay it, or split it into smaller pieces—where product thinking and technical thinking meet.

Iterative development and an MVP are closely related: the MVP defines the focused first version, and iterative work describes how the team builds toward that version in small increments called sprints. Early increments provide a rough version of a core page; later ones add forms, validation, navigation, or improved content.

In this class, you will use a simplified version of this logic. You likely do not have a full product team, formal sprint ceremonies, or months of iteration. Your prioritized feature list acts as a basic backlog, your MVP defines the first realistic version, and your wireframes and requirements communicate what should be built next.

The goal is not to memorize terminology, but to see how product decisions connect to development work.

## Part 7: Wireframing for Communication {#part-7:-wireframing-for-communication}

Wireframes show structure, not polish. A wireframe is a simple representation of a page or screen that highlights structure, content, navigation, and interaction points. It does not need polished colors, fonts, images, or branding. At this stage, the goal is communication rather than visual design.

Wireframes make abstract requirements concrete. A stakeholder may ask for an “easy homepage,” but that means little until you show what appears on the page: does it explain the service, feature items, include a call-to-action, or direct users to other sections? A wireframe forces those decisions into the open.

A good wireframe clarifies the page purpose, shows available actions, and maps how the user moves to the next step. It should connect back to requirements and user flows. If a requirement calls for comparing options, the wireframe should show where and how that comparison happens.

Weak prompts for development

Wireframes are useful when working with AI coding tools. A vague prompt like “make me a homepage” gives the tool too much freedom and often produces generic results. A wireframe provides a clearer basis for prompting: header, navigation, hero section, content areas, buttons, forms, and links to other pages.

The wireframe becomes a prompt-planning tool, helping you translate product decisions into clear instructions for implementation. You are not asking the tool to decide what the site should be; you are using it to implement a plan you defined through requirements, user flows, prioritization, and feedback.

For example, a stronger prompt might say:

“Create a Django template for the homepage of a local restaurant website. The page should include a top navigation bar with links to Menu, Hours, Location, and Reservations; a hero section explaining the restaurant’s value proposition; a featured menu section with three sample dishes; and a reservation call-to-action near the bottom. Use basic HTML and CSS and keep the layout simple.”

This prompt is stronger because it comes from a product plan, not from a vague idea.

An even stronger prompt would describe repeated site elements. For example:

“Create a Django homepage template for a local restaurant website using basic HTML and CSS. The site should have a top navigation bar with links to Home, Menu, Hours, Location, and Reservations. Because this same navigation bar will appear on every page, design it as a reusable Django template partial that can be included across multiple pages instead of duplicated manually. The homepage should include a hero section explaining the restaurant’s value proposition, a featured menu section with three sample dishes, and a reservation call-to-action near the bottom. Keep the layout simple and make the HTML easy to understand for a beginner.”

That prompt not only describes the page but also gives guidance about organizing the site for reuse and consistency.

Shared CSS and site-wide consistency

The same idea applies to CSS. A weak prompt may instruct inline CSS for a single page, which can work initially but becomes problematic as the site grows. If each page has separate styling, maintenance and consistency suffer. A stronger prompt asks for a shared CSS file to define site-wide style: fonts, page width, navigation bar styling, buttons, headings, spacing, and footer styling. Link the template to the shared stylesheet and avoid large in-template style blocks except for small page-specific adjustments.

This approach helps keep product decisions consistent across the site. If the business wants the site to feel simple, trustworthy, modern, or student-friendly, that design intent should be reflected consistently. A shared stylesheet supports that goal and makes future changes easier.

For this course, create wireframes using sketches, slides, or basic HTML and CSS. HTML and CSS help translate product ideas into the structure of a real website, even if backend functionality is not yet complete.

Create at least two wireframes: a homepage and one page that supports a core feature. Ensure these wireframes reflect the problem, requirements, user flow, MVP scope, and the prompts you will use to begin building the site.

## Part 8: Incremental Development {#part-8:-incremental-development}

Your first version will not be perfect. Product planning is iterative: make an initial interpretation, present it to stakeholders, gather feedback, and revise.

Validation should focus on whether the product addresses the core problem. Useful validation questions include: Does this solve the core problem? What is missing? What seems unnecessary? Which feature matters most? What would prevent a user from completing the main task?

Treat stakeholder feedback as evidence to interpret, not as automatic instruction. Feedback may reveal real problems, individual preferences, or conflicts between stakeholders. Your role is to weigh the feedback and decide what to change.

Document what changed and why. When revising, note the change and its reason—for example, clearer navigation after user testing, moving a feature out of the MVP for complexity, or adding a requirement based on stakeholder input.

The final plan should demonstrate learning. Improve the product direction based on evidence, constraints, and judgment.

Your final submission for this phase should include a complete product planning package: a problem statement and value proposition, stakeholder analysis and personas, functional and non-functional requirements, acceptance criteria for selected requirements, use cases and at least one user flow, a prioritized backlog with a defined MVP, wireframes for at least two pages, and a record of stakeholder feedback and revision.

These parts should connect: the problem statement explains why the product matters; stakeholder analysis shows whose needs are considered; requirements describe system behavior; user flows show interactions; the MVP explains the first build; wireframes make the plan visible; feedback shows how thinking improved.

Treat the deliverables as parts of one product planning argument. Strong work starts with a clear problem and stays connected to it. Show understanding of different stakeholder needs, make trade-offs when they conflict, define requirements so others can implement them, and use wireframes to communicate product decisions rather than just decorate pages.

Strong work also shows prioritization: what belongs in the MVP and what should wait. Explain why decisions were made using available evidence, business reasoning, user needs, and reasonable judgment.

Weak work often jumps to features, lists pages without explaining their purpose, tries to include everything, avoids trade-offs, treats stakeholder requests as commands, or produces wireframes disconnected from requirements.

The difference between strong and weak work is clarity of thinking.

AI tools can help generate code, layouts, documentation, and prototypes quickly, but they do not replace product thinking.

If development becomes easier to accelerate, the higher-value skill is deciding what to accelerate. Producing more features quickly is not itself beneficial; the benefit comes from choosing, prioritizing, testing, and refining the right features. Product work involves understanding problems, asking good questions, balancing stakeholder needs, defining scope, curating a meaningful backlog, prioritizing work, and communicating product direction clearly.

This is the capability you are practicing in this phase.