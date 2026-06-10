# Software Development Glossary for Non-Technical Readers

This document explains common software development terms in plain English. It is meant for people who work with software teams, buy software, manage software projects, review technical updates, or simply want to understand what developers mean when they use technical language.

The definitions are intentionally practical. They focus on what a term means, why it matters, and how you might hear it used in real conversations.

## How To Use This Document

- Use it as a reference when a term appears in a meeting, ticket, estimate, incident report, or product plan.
- Do not worry about memorizing everything. Many software terms only become meaningful when you see them in context.
- If two terms sound similar, look for the difference in who uses them, where they happen, and what problem they solve.
- When in doubt, ask: "What does this mean for the user, the business, the timeline, or the risk?"

## Quick Mental Model

Software is usually built from a few major parts:

- **User interface**: What people see and interact with.
- **Business logic**: The rules that decide what should happen.
- **Data**: The information the system stores, reads, changes, or sends.
- **Infrastructure**: The servers, networks, tools, and services that keep the system running.
- **Process**: The way teams plan, build, test, release, and improve the software.

## Product And Project Terms

### Acceptance Criteria

The checklist that defines what must be true before a task or feature is considered finished. For example: "The user can reset their password, receives an email, and sees a confirmation message."

### Agile

A way of managing software work in small, flexible cycles instead of trying to plan every detail upfront. Agile teams usually deliver work in increments, get feedback, and adjust as they learn.

### Backlog

The list of work that might be done in the future. It can include features, bugs, technical improvements, research tasks, and cleanup work.

### Blocker

Something that prevents work from moving forward. A blocker might be a missing decision, unavailable access, broken environment, dependency on another team, or unclear requirement.

### Epic

A large body of work that is too big for one task or ticket. An epic is usually broken into smaller user stories or tasks.

### Estimate

A team's best guess about how much effort, time, or complexity a piece of work may involve. Estimates are not promises; they are planning tools.

### Feature

A new or improved capability that users or the business care about. For example: "export invoices as PDF" or "send alerts when inventory is low."

### Grooming Or Refinement

The process of clarifying upcoming work before it is started. Teams use refinement to break down big ideas, ask questions, add acceptance criteria, and identify risks.

### MVP

Short for **Minimum Viable Product**. It means the smallest useful version of something that can be released to learn from real users or prove a concept.

### Product Requirement

A description of what the product should do and why. It usually explains the user need, business value, expected behavior, and constraints.

### Roadmap

A high-level plan showing what a product or team expects to focus on over time. Roadmaps are direction-setting tools, not exact delivery calendars.

### Scope

The agreed boundaries of a project or task. Scope defines what is included and what is not included.

### Scope Creep

When extra requirements keep getting added after work has started, often without adjusting the timeline, budget, or priorities.

### Sprint

A short work period, often one or two weeks, where an agile team focuses on a selected set of tasks.

### Stakeholder

Anyone who cares about or is affected by the work. Stakeholders may include customers, executives, support teams, sales teams, compliance teams, and end users.

### User Story

A short description of a need from a user's point of view. A common format is: "As a customer, I want to reset my password so that I can regain access to my account."

### UAT

Short for **User Acceptance Testing**. This is when business users or customer representatives test whether the system behaves as expected before release.

## People And Team Roles

### Architect

A person who makes high-level technical design decisions about how systems should be structured, connected, and maintained.

### Back-End Engineer

An engineer who works on the server-side parts of software: business rules, APIs, databases, background jobs, and integrations.

### Data Engineer

An engineer who builds systems that collect, move, clean, organize, and prepare data for reporting, analytics, or other applications.

### DevOps Engineer

A person who helps teams build, release, monitor, and operate software reliably. DevOps work often includes automation, cloud infrastructure, deployment pipelines, and incident support.

### Front-End Engineer

An engineer who builds the parts of software that users see and interact with, such as screens, forms, navigation, and visual behavior.

### Full-Stack Engineer

An engineer who can work across both front-end and back-end parts of an application.

### Product Manager

A person responsible for understanding user needs, business goals, priorities, and product direction.

### QA Engineer

Short for **Quality Assurance Engineer**. A person who helps verify that software works correctly, often by designing tests, finding bugs, and improving test processes.

### Scrum Master

A team facilitator in some agile teams. They help the team follow its process, remove blockers, and improve collaboration.

### Site Reliability Engineer

Often shortened to **SRE**. A person focused on keeping systems reliable, scalable, observable, and recoverable.

### Technical Lead

An engineer who guides technical decisions for a team or project, often balancing hands-on coding with design, review, and coordination.

## Core Software Terms

### Abstraction

Hiding complicated details behind a simpler idea or interface. For example, a "Pay now" button hides many behind-the-scenes steps like validation, payment authorization, receipt creation, and logging.

### Algorithm

A step-by-step method for solving a problem. A recipe is a simple real-world example of an algorithm.

### Application

A software program that helps users do something. Examples include banking apps, websites, payroll systems, chat tools, and inventory systems.

### Artifact

A file or output created by a software process. For example, a build process might produce an application package, report, or deployable file.

### Automation

Using software to perform repeatable tasks without manual effort. Automation can reduce mistakes, save time, and make processes more consistent.

### Bug

A mistake or defect in software that causes it to behave incorrectly, unexpectedly, or unreliably.

### Business Logic

The rules that represent how a business process should work. For example: "Orders over $100 get free shipping" or "Only managers can approve expenses over $5,000."

### Command Line

A text-based way to control a computer or software tool by typing commands instead of clicking through a visual interface.

### Code

Instructions written in a programming language that tell a computer what to do.

### Codebase

The full collection of code, configuration, scripts, and related files for a software project.

### Compiler

A tool that turns human-written code into a form the computer can run.

### Complexity

How difficult software is to understand, change, test, or operate. Complexity can come from business rules, technical design, integrations, edge cases, or unclear ownership.

### Configuration

Settings that control how software behaves without changing the core code. For example: a payment provider key, feature setting, environment name, or timeout value.

### Dependency

Something a piece of software relies on. This could be a library, service, database, team, vendor, or external system.

### Edge Case

An unusual but possible situation that software still needs to handle. For example: a customer has no last name, a file is empty, or a payment is submitted twice.

### Framework

A reusable structure that helps developers build software faster by providing common patterns and tools. Examples include web frameworks, testing frameworks, and mobile app frameworks.

### Function

A named piece of code that performs a specific task. For example, a function might calculate tax, format a date, or send an email.

### Hardcoding

Putting a fixed value directly into code instead of making it configurable. This can be risky if the value needs to change later.

### Library

Reusable code that developers can use instead of writing everything from scratch. For example, a library might handle dates, charts, encryption, or file uploads.

### Logic

The decision-making part of software. Logic determines what happens when certain conditions are true or false.

### Module

A logical piece of a codebase grouped around a particular responsibility.

### Parameter

An input value passed into a function, command, or API call. For example, a search function might accept a search term as a parameter.

### Programming Language

A formal language developers use to write software. Examples include JavaScript, Python, Java, C#, Go, Ruby, PHP, Swift, Kotlin, and Rust.

### Patch

A small change to software, often used to fix a bug or security issue.

### Refactoring

Improving the structure of existing code without changing what it does for users. Refactoring can make software easier to maintain and extend.

### Runtime

The period when software is actually running, or the environment needed to run it. For example, "a runtime error" happens while the program is running.

### Script

A small program usually written to automate a specific task, such as moving files, running tests, or generating reports.

### Software Development Lifecycle

Often shortened to **SDLC**. The full process of planning, designing, building, testing, releasing, operating, and improving software.

### Source Code

The human-readable code written by developers.

### Technical Debt

The future cost of shortcuts, outdated designs, rushed decisions, or deferred cleanup. Like financial debt, it may be manageable at first but can slow teams down over time.

### Version

A specific release or state of software. Versions help teams track what changed and what users are running.

## Programming Fundamentals

### Boolean

A true-or-false value. For example, `isPaid` might be true when an invoice has been paid.

### Class

A template used in some programming languages to define what a kind of object looks like and what it can do.

### Conditional

A decision in code, often described as "if this happens, then do that." For example: if the user is not logged in, show the login screen.

### Constant

A value that is not expected to change while the program runs.

### Data Type

A category of value, such as text, number, date, true/false, list, or object.

### Exception

An unexpected problem that occurs while software is running. Good software catches or handles exceptions so users get a useful result instead of a crash.

### Float Or Decimal

A number with digits after the decimal point, such as `19.95`.

### Integer

A whole number, such as `1`, `42`, or `1000`.

### Interpreter

A tool that runs code directly instead of requiring it to be compiled first.

### Loop

A way for code to repeat an action. For example, send an email to every person in a list.

### Null

A special value meaning "nothing," "unknown," or "not set." Null values are common sources of bugs when software expects a real value.

### Object

A structured value that groups related information and behavior. For example, a customer object might contain name, email, account status, and address.

### Object-Oriented Programming

A programming style that organizes software around objects, which combine data and behavior.

### Recursion

When a function solves a problem by calling itself on smaller parts of the problem. It is powerful but can be confusing if overused.

### Stack Trace

A technical error report showing where a problem happened in the code and what sequence of calls led to it.

### String

Text data, such as a name, email address, or message.

### Variable

A named place where code stores a value so it can use or change it later.

## Developer Tools

### CLI

Short for **Command-Line Interface**. A tool used by typing commands.

### Debugger

A tool that helps developers pause software while it runs, inspect values, and step through code to find problems.

### Formatter

A tool that automatically makes code layout consistent, such as indentation, line breaks, and spacing.

### IDE

Short for **Integrated Development Environment**. A software application developers use to write, run, debug, and manage code.

### Linter

A tool that checks code for common mistakes, risky patterns, or style issues before the code is run.

### Package

A reusable bundle of software that can be installed into a project.

### Package Manager

A tool that installs, updates, and manages software packages or libraries. Examples include npm, pip, Maven, NuGet, and Composer.

### SDK

Short for **Software Development Kit**. A set of tools, libraries, examples, and documentation that helps developers build with a platform or service.

### Terminal

An app used to access the command line.

## Web And App Terms

### API

Short for **Application Programming Interface**. An API is a structured way for one piece of software to communicate with another. Think of it as a menu of actions that one system offers to other systems.

### API Endpoint

A specific address in an API where a request can be sent. For example, `/customers/123` might return information about customer 123.

### Browser

Software used to view websites and web apps, such as Chrome, Edge, Safari, or Firefox.

### Client

The software or device that requests something from another system. A web browser, mobile app, or desktop app can be a client.

### Cookie

A small piece of information stored by a browser for a website. Cookies are often used for login sessions, preferences, and tracking.

### CSS

Short for **Cascading Style Sheets**. CSS controls how web pages look: colors, spacing, layout, fonts, and responsive behavior.

### Domain Name

The human-friendly name of a website, such as `example.com`.

### DNS

Short for **Domain Name System**. DNS translates domain names into network addresses that computers use to find servers.

### Front End

The part of an application users directly see and interact with.

### HTML

Short for **HyperText Markup Language**. HTML defines the structure and content of web pages, such as headings, paragraphs, links, forms, and images.

### HTTP

Short for **HyperText Transfer Protocol**. It is the basic communication system used by browsers and web servers.

### HTTPS

The secure version of HTTP. It encrypts communication between the user's browser and the website.

### JavaScript

A programming language commonly used to make websites and web apps interactive.

### HTTP Status Code

A number returned by a web server to describe the result of a request. For example, `200` usually means success, `404` means not found, and `500` means a server error.

### Localhost

The developer's own computer when it is acting like a server for testing. If an engineer says "it works on localhost," they mean it works on their machine.

### Mobile App

Software built to run on phones or tablets, usually installed through an app store or enterprise system.

### Page Load

The process of a web page opening and becoming usable for the user.

### Responsive Design

Designing an interface so it works well across different screen sizes, such as phones, tablets, laptops, and large monitors.

### Server

A computer or service that receives requests and sends back responses. For example, a website server sends web pages to browsers.

### URL

Short for **Uniform Resource Locator**. A URL is the address of a resource on the internet, such as `https://example.com/pricing`.

### Web App

An application used through a browser. Examples include online banking, project management tools, dashboards, and customer portals.

### Webhook

A way for one system to automatically notify another system when something happens. For example, a payment service can send a webhook when a payment succeeds.

## Data Terms

### Analytics

The process of using data to understand behavior, performance, trends, or outcomes.

### Backup

A saved copy of data or systems that can be used to recover from accidental deletion, corruption, failure, or attack.

### Batch Job

A task that processes a group of items at once, often on a schedule. For example, sending monthly statements overnight.

### Big Data

Very large or complex data sets that require specialized tools to store, process, or analyze.

### CSV

Short for **Comma-Separated Values**. A simple file format often used for spreadsheets and data exports.

### CRUD

Short for **Create, Read, Update, Delete**. These are the four basic actions many systems perform on data.

### Dashboard

A screen that summarizes important information, often using charts, tables, metrics, and alerts.

### Data Lake

A large storage area for raw or lightly processed data from many sources. It is often used for analytics, machine learning, or future processing.

### Data Model

The way information is organized in a system. For example, a customer data model might include name, email, address, account status, and order history.

### Data Pipeline

A process that moves and transforms data from one place to another. For example, data might flow from an app into a reporting database.

### Data Warehouse

A database designed for reporting and analysis rather than day-to-day app transactions.

### Database

A structured place where software stores and retrieves information.

### ETL

Short for **Extract, Transform, Load**. A data process that pulls data from a source, changes it into a useful format, and loads it somewhere else.

### Field

A single piece of information in a record. For example, `email` could be a field on a customer record.

### Index

A database structure that helps find data faster, similar to an index in a book.

### JSON

Short for **JavaScript Object Notation**. A common text format for sending structured data between systems.

### Metadata

Data about data. For example, a file's metadata might include its name, size, type, owner, and creation date.

### Query

A request for information from a database or search system.

### Record

One complete item in a database table or data set. For example, one customer, one invoice, or one order.

### Schema

The defined structure of data. A schema says what fields exist, what type of data they hold, and what relationships exist.

### SQL

Short for **Structured Query Language**. A common language used to read and change data in relational databases.

### Table

A database structure made of rows and columns, similar to a spreadsheet.

### XML

Short for **Extensible Markup Language**. A structured text format used to represent and exchange data.

### YAML

A human-readable configuration and data format commonly used in software settings and deployment files.

## APIs, Integration, And Automation

### Connector

A reusable piece of software that helps one system connect to another system, such as Salesforce, SAP, Slack, or a database.

### Event

Something that happens in a system. Examples include "order placed," "payment failed," "file uploaded," or "user logged in."

### Event-Driven Architecture

A design where systems react to events as they happen. Instead of constantly asking "did anything change?", systems are notified when something changes.

### Flow

A sequence of automated steps. In integration tools, a flow might receive data, transform it, call an API, and save the result.

### Idempotency

The idea that repeating the same request should not cause duplicate or incorrect results. For example, clicking "Pay" twice should not charge a customer twice.

### Integration

Connecting two or more systems so they can share data or trigger actions across each other.

### Low-Code

Software development using visual tools, configuration, and reusable components instead of writing every part manually in code.

### Mapping

Matching fields from one system to fields in another system. For example, mapping `surname` in one system to `lastName` in another.

### Message Broker

A system that helps services send and receive messages reliably. It acts like a delivery hub between systems.

### Payload

The actual data sent in a request, response, message, or event.

### Pub/Sub

Short for **Publish/Subscribe**. A messaging pattern where one system publishes events and other systems subscribe to receive the events they care about.

### Queue

A waiting line for work that needs to be processed. Queues help systems handle spikes, slow tasks, and retries.

### Rate Limit

A rule that limits how many requests can be made in a certain time. Rate limits protect systems from overload or abuse.

### Retry

Trying an operation again after it fails. Retries are common when a network call or external service temporarily fails.

### Timeout

The maximum amount of time a system will wait before giving up on an operation.

### Transformation

Changing data from one shape, format, or meaning into another so another system can use it.

### Trigger

Something that starts a process. A trigger might be a schedule, file upload, API call, message, or user action.

### Workflow

A defined sequence of steps that completes a business or technical process.

### Workflow Engine

Software that runs, tracks, and manages workflows automatically.

## Cloud, Infrastructure, And Hosting

### Bandwidth

The amount of data that can move across a network in a given time. Higher bandwidth can support more traffic or larger files.

### CDN

Short for **Content Delivery Network**. A network of servers that helps deliver files, images, videos, and web pages faster by serving them from locations near users.

### Cloud

Computing resources, such as servers, storage, databases, and networking, provided over the internet by companies like AWS, Azure, or Google Cloud.

### Container

A packaged unit of software that includes the app and what it needs to run. Containers help software behave consistently across environments.

### CPU

Short for **Central Processing Unit**. The part of a computer that performs calculations and instructions.

### Cron Job

A scheduled task that runs automatically at specific times or intervals.

### Disk

Storage used to save files, databases, logs, and application data.

### Docker

A popular tool for creating and running containers.

### Environment

A place where software runs. Common environments include development, test, staging, and production.

### Firewall

A security barrier that controls which network traffic is allowed in or out.

### Host

A computer, server, or service where software runs.

### Infrastructure

The technical foundation that software depends on, such as servers, networks, databases, cloud services, storage, and deployment systems.

### Kubernetes

A system for running and managing containers across multiple servers. It helps with scaling, deployment, and recovery.

### Load Balancer

A system that spreads traffic across multiple servers so one server does not get overwhelmed.

### Memory

Temporary working space used by software while it runs. If memory runs out, software can slow down or crash.

### Port

A numbered communication channel on a server or computer. For example, web traffic often uses port 80 or 443.

### Production

The live environment used by real users or real business processes. Changes in production can directly affect customers and operations.

### Provisioning

Creating or preparing infrastructure, accounts, services, or resources so software can run.

### Scalability

The ability of a system to handle more users, data, traffic, or work without breaking down.

### Serverless

A cloud model where developers run code without directly managing servers. Servers still exist, but the cloud provider handles much of the operations work.

### Virtual Machine

A software-based computer that runs inside a physical computer or cloud platform.

## Development Workflow And Version Control

### Branch

A separate line of work in version control. Branches let developers work on changes without immediately affecting the main code.

### Build

The process of turning source code into something that can be run, tested, or deployed.

### CI

Short for **Continuous Integration**. A practice where code changes are regularly combined and automatically checked by builds and tests.

### CD

Can mean **Continuous Delivery** or **Continuous Deployment**. Both relate to automatically preparing or releasing software changes.

### Code Review

When another developer checks a code change before it is merged. Reviews help catch bugs, improve quality, and share knowledge.

### Commit

A saved change in version control. A commit records what changed, who changed it, and when.

### Conflict

When two changes affect the same part of a file and the version control system needs help deciding how to combine them.

### Deployment

The process of putting software into an environment where it can run, such as staging or production.

### Git

A widely used version control system that tracks changes to code over time.

### GitHub

A platform for hosting Git repositories and collaborating on software through pull requests, issues, reviews, and automation.

### Hotfix

A quick fix for an urgent issue, often released faster than normal changes.

### Merge

Combining changes from one branch into another.

### Pipeline

An automated sequence of steps, often used to build, test, scan, package, and deploy software.

### Pull Request

A proposed code change that is ready for review before being merged. Pull requests often show what changed, why, and any test results.

### Release

A version of software made available to users or another environment.

### Repository

A storage location for code and its history. Often shortened to "repo."

### Rollback

Returning software to a previous working version after a release causes problems.

### Semantic Versioning

A version numbering approach that often looks like `major.minor.patch`, such as `2.4.1`.

### Version Control

A system that tracks changes to files over time, allowing teams to collaborate and recover previous versions.

## Testing And Quality

### Accessibility

Designing and building software so people with different abilities can use it. This includes support for screen readers, keyboard navigation, readable contrast, and clear labels.

### Automated Test

A test run by software rather than manually by a person. Automated tests can run frequently and catch problems early.

### Defect

Another word for a bug or flaw in software.

### End-To-End Test

A test that checks a full user journey across multiple parts of a system. For example: sign up, add item to cart, pay, and receive confirmation.

### Error Handling

How software responds when something goes wrong. Good error handling prevents crashes and gives useful information to users or support teams.

### Happy Path

The normal, expected path where everything works as intended. For example, a user enters valid details and payment succeeds.

### Integration Test

A test that checks whether multiple parts of a system work together correctly.

### Load Test

A test that checks how software behaves under high traffic or heavy usage.

### Manual Test

A test performed by a person using the software directly.

### Mock

A fake version of a service, object, or response used for testing. Mocks help test one part of a system without depending on everything else.

### Performance Test

A test that measures speed, stability, responsiveness, or resource usage.

### Regression

When something that used to work breaks after a change.

### Smoke Test

A quick basic test to confirm the most important parts of software are working.

### Test Case

A specific scenario that should be tested, including the setup, action, and expected result.

### Test Coverage

An indication of how much of the code or behavior is checked by tests. Higher coverage can help, but it does not guarantee perfect quality.

### Unit Test

A test that checks a small piece of code in isolation, such as one function or component.

### Validation

Checking that input or data meets rules before it is accepted. For example, an email field should contain a valid email address.

## Security, Privacy, And Compliance

### Authentication

Proving who someone is. Logging in with a password, passkey, or one-time code is authentication.

### Authorization

Deciding what an authenticated person or system is allowed to do. For example, a manager may approve expenses, while a regular employee may only submit them.

### Compliance

Following required laws, regulations, standards, contracts, or policies. Examples include privacy rules, financial controls, and industry security standards.

### Encryption

Scrambling information so only authorized parties can read it.

### MFA

Short for **Multi-Factor Authentication**. It requires more than one proof of identity, such as a password plus a phone approval.

### Permission

A rule that allows or denies access to something.

### PII

Short for **Personally Identifiable Information**. Data that can identify a person, such as name, email, ID number, phone number, or address.

### Secret

A sensitive value used by software, such as an API key, password, token, or private certificate. Secrets should be protected and not stored openly in code.

### Security Patch

A change that fixes a security weakness.

### Token

A digital value used to prove identity, access, or authorization for a limited purpose or time.

### Vulnerability

A weakness that could be exploited to harm a system, steal data, or bypass controls.

### Zero Trust

A security approach based on verifying every user, device, and request instead of automatically trusting anything inside a network.

## Operations, Monitoring, And Reliability

### Alert

A notification that something may need attention, such as a service being down, errors increasing, or disk space running low.

### Availability

How often a system is usable when people need it.

### Downtime

Time when a system is unavailable or not working properly.

### Incident

An event where something goes wrong and affects users, business operations, security, or reliability.

### Latency

Delay. In software, latency often means how long it takes for a request to receive a response.

### Log

A record of events produced by software. Logs help engineers investigate problems and understand system behavior.

### Metric

A measured value, such as error rate, response time, memory usage, number of users, or successful payments.

### Monitoring

Watching systems for health, performance, errors, and unusual behavior.

### Observability

The ability to understand what is happening inside a system by using logs, metrics, traces, and other signals.

### On-Call

The responsibility of being available to respond to urgent production issues.

### Postmortem

A review after an incident to understand what happened, why it happened, how it was handled, and how to reduce the chance of recurrence.

### Recovery

Restoring normal service after a failure, outage, mistake, or attack.

### SLA

Short for **Service Level Agreement**. A formal promise about service performance or availability, often between a provider and customer.

### SLO

Short for **Service Level Objective**. An internal or external target for reliability, such as "99.9% of requests should succeed."

### Trace

A record of how one request moves through multiple services. Traces help find where delays or failures happen.

### Zero-Downtime Deployment

Releasing changes without taking the system offline for users.

## Architecture And System Design

### Architecture

The high-level structure of a software system: its parts, how they connect, and the principles guiding design decisions.

### Asynchronous

Work that does not have to happen immediately or block the user while it completes. For example, sending an email in the background after a user submits a form.

### Cache

A temporary storage layer that keeps frequently used data close by so it can be accessed faster.

### Component

A reusable or self-contained part of a system or user interface.

### Coupling

How tightly connected two parts of a system are. Lower coupling usually makes systems easier to change.

### Deadlock

A situation where two or more processes are stuck waiting for each other and cannot continue.

### Distributed System

A system made of multiple computers or services that work together over a network.

### Gateway

A controlled entry point between systems, networks, or services.

### Interface

A defined way for people or systems to interact with something. A user interface helps people use software; a programming interface helps systems communicate.

### Microservice

A small, independently deployable service focused on a specific business capability.

### Middleware

Software that sits between other systems or components to help them communicate, transform data, enforce rules, or coordinate behavior.

### Monolith

An application built as one large unit. Monoliths can be simple to start with but may become harder to change as they grow.

### MVC

Short for **Model-View-Controller**. A design pattern that separates data, display, and user actions into different responsibilities.

### Protocol

A set of rules for communication between systems.

### Redundancy

Having backup components or duplicate capacity so the system can keep working if one part fails.

### Service

A software component that performs a specific function and can be used by other parts of a system.

### Separation Of Concerns

A design principle that keeps different responsibilities in different parts of the system. This makes software easier to understand, test, and change.

### Single Source Of Truth

The trusted place where a specific piece of information should be maintained. For example, a company might decide the CRM is the single source of truth for customer contact details.

### State

Information about the current condition of something. For example, an order might have the state `pending`, `paid`, `shipped`, or `cancelled`.

### Stateful

Software that remembers information between interactions.

### Stateless

Software that does not remember previous interactions unless the needed information is sent again or stored elsewhere.

### Synchronous

Work where one part waits for another part to finish before continuing. For example, a checkout page waits for payment approval before showing confirmation.

## Maintenance, Support, And Change

### Changelog

A record of what changed between software versions.

### Deprecation

The process of marking a feature, API, or behavior as outdated and warning people it may be removed later.

### End Of Life

The point when a product, version, or service is no longer supported.

### Legacy System

An older system that is still important but may be difficult to change, support, integrate, or replace.

### Maintenance

Ongoing work needed to keep software secure, reliable, compatible, and useful after it has been released.

### Migration

Moving data, users, systems, or software from one structure, version, platform, or environment to another.

### Root Cause

The underlying reason a problem happened, not just the visible symptom.

### Support Ticket

A request for help, investigation, change, or repair, often submitted by a user, customer, or internal team.

### Workaround

A temporary way to avoid or reduce a problem without fully fixing the underlying cause.

## Open Source, Ownership, And Licensing

### Contributor

Someone who helps improve a software project, often by submitting code, documentation, bug reports, or suggestions.

### Fork

A separate copy of a software project that can be changed independently from the original.

### License

The legal terms that say how software can be used, modified, shared, or sold.

### Maintainer

A person or group responsible for reviewing changes, guiding direction, and keeping a software project healthy.

### Open Source

Software whose source code is available for others to inspect, use, modify, or share under a license.

### Proprietary Software

Software owned and controlled by a person or company, usually with restrictions on copying, modifying, or redistributing it.

### Vendor Lock-In

When it becomes difficult or expensive to move away from a vendor because the software, data, contracts, or architecture are tightly tied to that vendor.

## User Experience And Design

### Design System

A collection of reusable design rules, components, patterns, and guidelines that help products look and behave consistently.

### Form

A screen area where users enter or submit information.

### Interaction

Something the user does with software, such as clicking, typing, dragging, selecting, or submitting.

### Journey

The sequence of steps a user takes to complete a goal.

### Persona

A representative profile of a type of user, used to help teams design for real needs.

### Prototype

An early model of a product or feature used to explore ideas and get feedback before full development.

### UI

Short for **User Interface**. The screens, buttons, menus, forms, and visual elements people use.

### UX

Short for **User Experience**. The overall experience a person has while using a product, including ease, clarity, speed, trust, and satisfaction.

### Wireframe

A simple layout sketch showing structure and flow before detailed visual design.

## AI And Machine Learning Terms

### AI

Short for **Artificial Intelligence**. Software techniques that perform tasks associated with human intelligence, such as understanding language, recognizing images, making predictions, or generating content.

### Chatbot

Software that communicates with users through conversation, often to answer questions, guide workflows, or automate support.

### Generative AI

AI that creates new content, such as text, images, code, audio, or summaries.

### LLM

Short for **Large Language Model**. An AI model trained on large amounts of text to understand and generate language.

### Machine Learning

A type of AI where systems learn patterns from data instead of being explicitly programmed for every rule.

### Model

In AI, a model is the trained system that makes predictions, classifications, recommendations, or generated outputs.

### Prompt

The instruction or input given to an AI model.

### Training Data

The data used to teach a machine learning model patterns.

## Common Acronyms

| Acronym | Meaning |
| --- | --- |
| API | Application Programming Interface |
| CDN | Content Delivery Network |
| CLI | Command-Line Interface |
| CI | Continuous Integration |
| CD | Continuous Delivery or Continuous Deployment |
| CPU | Central Processing Unit |
| CRUD | Create, Read, Update, Delete |
| CSS | Cascading Style Sheets |
| DNS | Domain Name System |
| ETL | Extract, Transform, Load |
| HTML | HyperText Markup Language |
| HTTP | HyperText Transfer Protocol |
| HTTPS | Secure HTTP |
| IDE | Integrated Development Environment |
| JSON | JavaScript Object Notation |
| LLM | Large Language Model |
| MFA | Multi-Factor Authentication |
| MVP | Minimum Viable Product |
| MVC | Model-View-Controller |
| PII | Personally Identifiable Information |
| QA | Quality Assurance |
| SDK | Software Development Kit |
| SDLC | Software Development Lifecycle |
| SLA | Service Level Agreement |
| SLO | Service Level Objective |
| SQL | Structured Query Language |
| SRE | Site Reliability Engineering |
| UAT | User Acceptance Testing |
| UI | User Interface |
| URL | Uniform Resource Locator |
| UX | User Experience |
| XML | Extensible Markup Language |
| YAML | YAML Ain't Markup Language |

## Phrases You Might Hear In Meetings

### "It Works On My Machine"

The software behaves correctly in a developer's local environment but fails somewhere else. This usually points to differences in configuration, data, dependencies, or environment setup.

### "We Need To Reproduce The Bug"

The team needs to make the bug happen again reliably so they can understand and fix it.

### "This Is In Staging"

The change is available in a test-like environment, but it is not live for real users yet.

### "This Is In Production"

The change is live in the real system used by customers or the business.

### "We Need To Roll Back"

The team wants to return to a previous version because the latest change caused a problem.

### "The API Is Down"

A system that other software depends on is not responding or is failing.

### "The Request Timed Out"

The system waited too long for a response and gave up.

### "We Are Waiting On A Dependency"

Progress depends on something outside the current task, such as another team, vendor, decision, system, or piece of work.

### "This Needs A Migration"

The structure or contents of data need to be changed so the new software version can work correctly.

### "We Should Put This Behind A Feature Flag"

The team wants to release the code but control who can see or use the feature.

## Helpful Questions For Non-Technical Stakeholders

- What user or business problem does this solve?
- What changes for the user?
- What happens if we do not do this now?
- What are the main risks?
- What are the assumptions?
- What is the smallest useful version?
- How will we know it worked?
- How will we detect if it fails?
- Can this be rolled back?
- Does this affect security, privacy, compliance, cost, or reliability?

## Plain-English Translations

| Technical phrase | Plain-English meaning |
| --- | --- |
| "Increase observability" | Make it easier to understand what the system is doing. |
| "Reduce coupling" | Make parts less dependent on each other so they are easier to change. |
| "Improve latency" | Make responses faster. |
| "Handle edge cases" | Make sure unusual but possible situations do not break things. |
| "Automate the pipeline" | Let software run the build, test, and release steps automatically. |
| "Refactor the module" | Clean up the internal structure without changing user-visible behavior. |
| "Add validation" | Check inputs before accepting them. |
| "Scale the service" | Make the service handle more usage. |
| "Rotate secrets" | Replace sensitive keys or passwords with new ones. |
| "Investigate logs" | Read system records to understand what happened. |

## Final Note

Software language can sound more intimidating than it really is. Most terms are labels for ordinary ideas: people asking for things, systems responding, data moving around, teams managing change, and safeguards reducing risk. The most useful habit is not memorizing every term; it is learning which question to ask next.
