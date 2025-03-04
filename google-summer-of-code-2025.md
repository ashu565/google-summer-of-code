# Google Summer of Code 2025

## [![Google Summer of Code 2025](https://github.com/Sing-Li/bbug/raw/master/images/gsoclogo.jpg)](https://summerofcode.withgoogle.com)

## How to apply

Rocket.Chat is applying to become a participating mentoring open source organization for [Google Summer of Code 2025](https://summerofcode.withgoogle.com/), helping to usher in a new generation of open source contributors and enthusiasts.

For timeline, see [Official Google Summer of Code 2025](https://developers.google.com/open-source/gsoc/timeline) Timeline for more details.

Almost anyone in the world [over 18 years of age](https://opensource.googleblog.com/2021/11/expanding-google-summer-of-code-in-2022.html) who loves coding and wants to explore the incredible world of open source can join us as a GSoC 2025 contributor.

Most exciting news for the 2025 season is focus on ML/AI plus security projects, and the continued support for a small project size with a 90 hours duration; allowing participation from those who can only  devote part of their summer to exploring open source.

For details and rules of Google Summer of Code 2025, please see the [GSoC 2025 Official Website](https://summerofcode.withgoogle.com/). For timeline, see [Official Google Summer of Code 2025 Timeline](https://developers.google.com/open-source/gsoc/timeline) for more details.

### **Contacting Rocket.Chat**

For general information, please visit our 24 x 7 community channel for Google Summer of Code 2025 : [https://open.rocket.chat/channel/gsoc2025](https://open.rocket.chat/channel/gsoc2025)

Join our [Google Summer of Code 2025 Team ](https://open.rocket.chat/channel/gsoc2025) today, introduce yourself to the friendly community, and interact with over **210 like-minded** contributors/mentors (as of Feb 10th, 2025)  and meet the team in the [30+ team channels](https://open.rocket.chat/channel/gsoc2025/team-channels).

If you have ideas and proposals that are not on our idea list, or if a mentor is not available, you can also email to:

gsoc+2025@rocket.chat

But better yet, you can post your idea in the [New GSoC 2025 Ideas looking for mentors](https://open.rocket.chat/channel/New-GSoC-2025-Ideas-looking-for-mentors) channel and possibly getting some immediate community feedback or support for your idea.

Interested contributors are also encouraged to interact directly with our team and community on the team channels:

[https://open.rocket.chat/channel/gsoc2025/team-channels](https://open.rocket.chat/channel/gsoc2025/team-channels)

As well as on GitHub:

[https://github.com/RocketChat/Rocket.Chat](https://github.com/RocketChat/Rocket.Chat)

Those who prefers forums can post messages on our GSoC forum channel (although as the leading open source team chat project we prefer you use Rocket.Chat channels above to reach us instantly).

-----

### **Latest update**

As of **Feb 24th 2025**, we are evolving project ideas with our engaged community members as well as returning community mentors, and guest mentors from other friendly open source projects.  We are super grateful to have **12 contributors from the 2024 season** returning to help us **as 2025 mentors**; and to bring on some exciting new project ideas.   Currently we have over 380 contributors and mentors active in our [30 GSoC 2025 team channels](https://open.rocket.chat/channel/gsoc2025/team-channels). And over [100 active contributors](https://gsoc.rocket.chat/) have contributed 14 Merged PRs, 88 Open PRs, and 206 issues to our open source projects.

As of **Feb 9th 2025**, we are intensely discussing project ideas with our returning community mentors, and guest mentors from other friendly open source projects.  This year, we are thankful to already have **9 contributors from the 2024 season** returning to help us **as 2025 mentors** to bring on some exciting projects.   Currently we have over 210 contributors and mentors active in our [30 GSoC 2025 team channels](https://open.rocket.chat/channel/gsoc2025/team-channels).


As of **January 27th 2025**  checkout our [GSoC 2025  Contributors Leaderboard](https://gsoc.rocket.chat/), to see the amazing contributions by our GSoC 2025 community: we already have over 100 contributors and mentors ready to join us for this season, active in our [team channels](https://open.rocket.chat/channel/gsoc2025/team-channels).


## 📂 Project Ideas

> This is an early draft of the GSoC 2025 project ideas list for Rocket.Chat,  the projects are expected to go through constant rapid changes during the application period - as mentors and potential contributors discuss and evolve the project descriptions.
> 

### 💡Server Setup Agent

👥 **Mentor(s):** Aditya Singh

💬 **Description:**  

As an administrator setting up a production Rocket.Chat server, one is typically required to create user accounts, create and assign roles, create default channels, possibly starting threads, starting discussions and populating with initial messages. 

These sort of tedious tasks are also often required in the testing and quality assurrance  of Rocket.Chat or Rocket.Chat related apps/projects.  Furthermore, they are also required in many demo and training situations.

This project is a Setup Agent App that  automates all of the above based on either a series of slash commands or by loading an automated script. 

The script should conform to an easy to learn, intuitive and simple DSL (Domain Specific Langauge) of the contributor's design. 

The language needs to incorporate basic variables, and be able to handle simple counted loops.  Conditionals and conditional loops are nice to have.  

The agent should be tested to handle very large scripts that may involve the creation of thousands of objects and messages.  


💪 **Desired Skills:**  

- Interest in DSL and AST (Domain Specific Language and Abstract Syntax Trees)
- Rocket.Chat Apps development (Typescript) 
- Familiarity with Rocket.Chat's REST APIs

🎯 **Goals/Deliverables:**  

A Rocket.Chat App "agent" that can help setup servers (or for QA or demo or training) by executing an automated script.

⏳ **Project Duration:** 90 hours (Small)  

📈 Difficulty: Easy/Intermediate

---

### 💡 Project Management Integration via Asana

👥 **Mentor(s):** Gustavo Bauer

💬 **Description:**  
Integrate [Asana](https://asana.com/) with Rocket.Chat to boost team collaboration. Instead of duplicating Asana’s complex task creation, focus on contextual notifications and quick access to task updates. Rocket.Chat project management users can stay informed collaborating within Rocket.Chat, while complex workflows that are better handled by Asana's rich UI remains in Asana.  The transition to and from Asana should be seamless. 

*Details:**
- **Setup & Authentication**
  - Implement OAuth and channel configuration.

- **Contextual Notifications**
  - Real-time alerts for task updates and deadlines.

- **Quick Commands & Summaries**
  - Slash commands for task details and simple updates.

- **Deep Linking**
  - Direct links from notifications to tasks in Asana.

- **Optional Activity Feed**
  - A mini feed for recent Asana activity in channels.

💪 **Desired Skills:**  
- Experience with Rocket.Chat Apps Engine (TypeScript)  
- OAuth and REST API experience

🎯 **Goals/Deliverables:**  
- An app delivering userful integration workflows for project management teams collaborating on Rocket.Chat.   Including minimally contextual task notifications and summaries.
- For workflows that are better handled with Asana's rich UI, seamless redirect to Asana and seamless  return to the Rocket.Chat collaboration context (channel / thread / discussions).

⏳ Project Duration: 90 hours (Small)

📈 Difficulty: Easy/Intermediate

---

### 🔑 Passkey-Based WebAuthn Authentication for Rocket.Chat  

👥 **Mentor(s):**  Julio Araujo, [Dnouv](https://open.rocket.chat/direct/Dnouv)  

💬 **Description:**  
 
The WebAuthn standard, now widely available on modern Android and iOS devices, enable convenient passwordless authentication satisfying 2FA (biometrics and "have device").  This project aims to integrate WebAuthn in Rocket.Chat authentication to offer a passwordless, secure login experience. The implementation needs to be aligned with Rocket.Chat’s existing authentication system while ensuring backward compatibility with all existing login methods.  

💪 **Desired Skills:**  

- Node.js  
- React.js  
- WebAuthn API  
- MongoDB
- Keen interest in cybersecurity   
- Authentication & Security Best Practices  

🎯 **Goals/Deliverables:**  

- Implement passkey-based authentication using WebAuthn  
- Modify authentication modules to support passkey registration and login  
- Update the frontend for seamless passkey interactions  
- Ensure secure storage of public keys in the user database  
- Conduct extensive testing across different devices and browsers  
- Provide detailed documentation and community engagement  

⏳ **Project Duration:** 175 hours (Medium)  

-----

### Server Guide Agent 

👥 **Mentor(s):** Gabriel Casals, Jeffery Yu

💬 **Description:**

As a new user joins a Rocket.Chat server there is not much guidance on what to do or where to go.   

Right now, the only mechanism is a passive landing page that may display resources for each grouping (persona) of users. 

For example, on the open.rocket.chat server, a user may be: 

* A Rocket.Chat server administrators looking to connect with other administrators
* An end-user of Rocket.Chat looking to resolve problem or receive support information. 
* A new community contributor looking for Google Summer of Code program information
* others

Each one of these personas demand different style of conversation and would need to know about/join different sets of channels and other resources.

Details:

The project aims to replace the boring "easy to miss, difficult to understand" landing page, with an AI guide agent.   This agent should start a conversation with the new user and then using modern LLM's discrimination/classification ability to positively identify the persona (users grouping/ sub-communities on a server) that the new user belongs to.   The agent should continue to tune the conversation to the lingo-preferred of that persona, and finally guide the user to all the resources and channels available for that persona.  This agent must be configurable (via Rocket.Chat Apps configuration) to handle any arbitrary persona and related resources set.

Recommended Approach: 

The agent should be able to add (and join) the appropriate channel for the new user, after confirming the action with the new user.  A default/catch-all persona should be used to precisely scoped the project and ensure the LLM can converge onto a useful result. Since direct user input will be passed to the LLM for analysis, the agent MUST make sure that there is no prompt-injection possibility. Safety of server operation must be taken into account as this agent has ability to change the state of the server permanently.

💪 **Desired Skills:**

- Experience with Natural Language Processing (NLP) systems
- Rocket.Chat Apps Engine (TypeScript)  
- Rocket.Chat messaging APIs
- Advanced prompt engineering skills   
- Experience with tools/function-calling capabilities of modern LLMs
- Understanding of how to implement "safety first" when creating AI apps that may permanently change the state of a production system

🎯 **Goals/Deliverables:**

An AI Agent that will help to onboard new users.

⏳ **Project Duration:** 175 hours (Medium)

-----

###  💡 Code Review Assistant for Open Source projects 

👥 **Mentor(s):** Felipe Scuciatto,  Samad Kahn 

💬 **Description:**

Finding reviewers for contributors' PRs on open source projects can often be difficult.  Slow response can possibly result in the loss of a communtiy contributor.  

 This assistant will monitor new pull requests (either via incoming github integration messages in a channel or directly via github events) and identify the most suitable maintainer to review the PR based on a statistical scoring system.  It will follow up with a friendly yet frequent reminder (“nagging”) mechanism to ensure timely reviews. 

Additionally, the bot will leverage code-specialized LLMs to perform an initial review, automatically filtering out minor improvements before they reach human reviewers. 

This will streamline the review process, reduce unnecessary delays, and ensure that only meaningful changes require manual attention.


💪 **Desired Skills:**

- Rocket.Chat Apps Engine and TypeScript
- Knowledge of general statistics
- Prompt engineering with code-specialized LLMs
- Ideally GitHub API

🎯 **Goals/Deliverables:**

- A Rocket.Chat App that will interact with open source maintainers and monitors open pull requests, assigns the most suitable reviewer based on past reviews, persistently reminds them until the review is completed, and leverages AI for initial code assessments.

⏳ **Project Duration:** 175 hours (Medium)

---

### 💡 Embedded Chat 2025

👥 **Mentor(s):** Zishan Ahmad

💬 **Description:**

Improvement to the EmbeddedChat project this year includes:
- Upgrading the current API and auth packages to use the latest Rocket.Chat SDK packages like `ddp-client`, and aligning other components to use other abstraction provided by Rocket.Chat, ensuring these packages will be managed internally moving forward.
- Making the EmbeddedChat fully mobile-responsive for a seamless experience across all devices.
- Improving the UI and adding more customization options to enhance the user experience.

💪 **Desired Skills:**

React.Js

🎯 **Goals/Deliverables:**

- Integration of the latest Rocket.Chat SDK packages
- Fully mobile-responsive EmbeddedChat
- Improved UI with more customization options

⏳ **Project Duration:** 90 hours (Small)

📈 **Difficulty:** Easy/Intermediate

-----

### 💡 Receipts Processor and Reporting App powered by Multi-modal LLMs 

👥 **Mentor(s):** Maria Khelli, Sing Li

💬 **Description:**  

While attending a busy conferences or event, the need to keep track of receipts and then having to adding them up manually to fill in expense reports is a very common and tedious problem.  This project is a Rocket.Chat app that completely automate the process.   

Details:

* The user will be able to take pictures of restaurant receipts on their phone and upload it into a specific channel (representing a single event, duration of time, or trip, and so on...).  

* Upon request, the app should  read and sum all the receipts producing a detailed report.  Ideally, the input format and image size should be flexible and the report format should be customizable via templates.  

* The app should never produce erraneous result under any circumstances, it should be able to recognize its limitation and decline to complete the task instead of giving potentially erraneous output.  

💪 **Desired Skills:**  

- Rocket.Chat Apps Engine (TypeScript)  
- Intermediate prompt engineering Skills   
- Experience with image reasoning capabilities of available open source multi-modal LLMs  


🎯 **Goals/Deliverables:**  

A working Rocket.Chat app that will scan and sum all the restaurant receipts uploaded to a specific channel.

⏳ **Project Duration:** 175 hours (Medium)  

📈 **Difficulty:** Easy/Intermediate  

-----

### 💡 Perfect AI Docs Assistant App

👥 **Mentor(s):** [Dnouv](https://open.rocket.chat/direct/Dnouv),  Jeffery Yu  

💬 **Description:**  

This project aims to build a Rocket.Chat App that provides a **natural language interface** for querying Rocket.Chat Docs (docs.rocket.chat). Instead of manually searching for answers, users can simply ask the app, and it will return a **perfect, relevant response** extracted and summarized from the documentation.

For the very small dataset that we are working with, we aim to tune and optimize the well-known RAG agentic workflow for our specific purpose; ideally producing  **an optimized and perfect Ask the Docs Assistant** for this subset of the Rocket.Chat documentation.
 
Consider possibly:  

- **Retrieval-Augmented Generation (RAG) agentic workflow** the AI/ML design pattern we're all familiar with   
- **Local embedding model** needs to run in memory/CPU for maximum efficiency
- **In-memory vector store** run in the client with no persistence, subject of further optimization (chunking, match-selection, metadata) to tune for _perfect results_
- **Context-aware follow-up responses** not required but nice to have

💪 **Desired Skills:**  

- Rocket.Chat Apps Engine (TypeScript)  
- Modern agentic workflows (including classic-RAG)
- Web Storage & IndexedDB (for caching, if needed)
- Intermediate prompt engineering 
- Keen interest in contemporary applications of LLMs

🎯 **Goals/Deliverables:**  

* generation/creation of a perfect validation dataset, consisting of (1500, 5000, 10000) queriies and corresponding answer, that will be used in the benchmark/validation of the final assistant
* a fine-tuned compact LLM to be used in the last stage of the RAG agentic workflow (fine-tuned minimally on the dataset above)
* the perfect "ask the docs assistant" for our small dataset, running mostly on the client without heavy compute overhead, ideally scoring 90% plus on the benchmark 

_(we like to thank our early community for helping us to fine-tune this set of deliverables)_

⏳ **Project Duration:** 90 hours (Small)  

📈 **Difficulty:** Intermediate/Advanced  

---

### 💡Google Summer of Code Community Hub 2025

👥 **Mentor(s):**  Anjaneya Gupta

💬 **Description:**  

Continuing our work on a "full stack component framework" in which a scalable website can be created by non-technical users using drag-and-drop components that not only include UI and client-side logic, but also pre-scaled server-side behaviors (or serverless impl). 

The ultimate use-case we have been working on is the community hub for Rocket.Chat Google Summer of Code. It will link all the despearate servers into one easy to customize and maintain uniform scalable web app (comprise of a set of full-stack components).

This year's work will include:
- rebasing of the existing platform and components on Svelte 5
- moving the WYSIWYG "Syntax Sweetening" work done last year to this new platform
- implementation of auth via OIDC
- migrate over the event poster component (used for our demo day)
- migrate over the video-meet-your-mentor component
- implement the gsoc leaderboard component
- implement embeddedchat component

💪 **Desired Skills:**  

- Advanced Typescript
- Svelte 5
- AST concepts  

🎯 **Goals/Deliverables:**  

A functional community hub website that we will use for 2026; showcasing the platform and new components.  

⏳ **Project Duration:** 90 hours (Small)  

📈 **Difficulty:** Easy/Intermediate  

---


### 💡AI Chat Workflows Automation App with multi-step reasoning

👥 **Mentor(s):**  Hardik Bhatia

💬 **Description:**  

Build a Rocket.Chat app that will monitor messages in specified channels (possibly sent by specified individuals, possibly within certain specified time period, and so on... )  and then (as a second step) perform additional messaging operations based on those messages.  Command should be issued in simple English. Bonus point for more than 2 steps in the reasoning.

Some examples:

    "whenever @sing.li posts any welcome messages in #gsoc2025, immediately DM him with a thank-you note"

    "if any picture is uploaded to the #pets channel, send a message that says meow! if the pet is a cat, and a woof! otherwise"

    "whenever a message is posted that contains a four letter word beginning with letter F, delete that message immediately"

    "if my wife messaged with 'arrived' before I do, DM her sorry I will be late after 1 minute" 

Recommended approach:

- leverage the latest open source specialized multi-step reasoning LLMs such as the DeepSeek distilled models 
- make intelligent use of tools/function-calling and structured inference    
- be sure to built in safety to offset erraneous output and/or hallucinations 

💪 **Desired Skills:**  

- Rocket.Chat Apps Engine (TypeScript)  
- Rocket.Chat messaging APIs
- Advanced prompt engineering Skills   
- Experience with image reasoning capabilities of available open source multi-modal LLMs
- Experience working with multi-step reasoning LLMs
- Experience with tools/function-calling capabilities of modern LLMs
- Expereince with code generation and code completion LLMs
- Understanding of how to implement "safety first" when creating AI apps that may permenantly change the state of a production system

🎯 **Goals/Deliverables:**  

Platform for generating functional automated chat workflows using LLMs.

⏳ **Project Duration:** 90 hours (Small)  

📈 **Difficulty:** Intermediate/Advanced  

---

### 📅  Message Timestamp Date Picker Components

👥 **Mentor(s):** [Martin Schoeler](https://open.rocket.chat/direct/martin.schoeler)

💬 **Description:**
Currently Rocket.Chat has a feature that allows users to send timestamps on messages, but not in an intuitive way. To send a timestamp you need to manually write it down with the correct date code. For example `<t:1732557600:t>`.
This feature was added for Rocket.Chat Apps engine, but users can benefit from this too. The objective of this project is to create a new `MessageToolBar` item that displays a calendar and let the users select the date and time they would like to share, both in the desktop app and mobile apps.

Some examples of the usage of the timestamp feature (you can test them today on the open.rocket.chat server!)

Pattern: <t:{timestamp}:?{format}>

- {timestamp} is a Unix timestamp
- {format} is an optional parameter that can be used to customize the date and time format.

**Formats**

| Format | Description               | Example                                 |
| ------ | ------------------------- | --------------------------------------- |
| `t`    | Short time                | 12:00 AM                                |
| `T`    | Long time                 | 12:00:00 AM                             |
| `d`    | Short date                | 12/31/2020                              |
| `D`    | Long date                 | Thursday, December 31, 2020             |
| `f`    | Full date and time        | Thursday, December 31, 2020 12:00 AM    |
| `F`    | Full date and time (long) | Thursday, December 31, 2020 12:00:00 AM |
| `R`    | Relative time             | 1 year ago                              |

The creation of tests for the new component is also expected, both end to end and unit if applicable.

💪 **Desired Skills:** React, Typescript, React Native

🎯 **Goals/Deliverables:** A new component on the `MessageToolBar` that allows users to add timestamps to their messages, both in desktop and mobile.

⏳ **Project Duration:** 90 hours. (Small)

📈 **Difficulty:** Easy/Intermediate

---

###  💡 Messages scheduling

👥 **Mentor(s):** Ricardo Swarovsky

💬 **Description:**

Add a native Rocket.Chat feature that lets users schedule messages to be sent later, directly integrated with the current send button. Since we serve users across multiple time zones, this feature will make it easier to schedule messages for the right time, no matter where they are.

💪 **Desired Skills:**

- Awareness of Rocket.Chat server and client codebase (NodeJS and React)

🎯 **Goals/Deliverables:**

- A Rocket.Chat feature that will allow users to schedule messages to be sent in the future

⏳ **Project Duration:** 90 hours (Small)

📈 **Difficulty:** Advanced

----

### 💡Client-side AI Support

👥 **Mentor(s):** Sing Li, Ashutosh Singh Chauhan

💬 **Description:**  

This project adds applicaton API access to LLMs running in-browser, on-device and distributes the AI compute load from the server - allowing AI applications to scale massively.

Not all client devices are capable of handling LLM loads, the deployment flow must detect and behave accordingly.

Details:

Modify current server deployment flows to install client-side LLMs as an option.

Extend Apps Engine to support client-side logic; (optional) loading of the LLMs; and API access to the in-browser/on-device LLMs.

Essential background:

- recent high performance lightweight models became available (Llama 3.2, Intern LM 2,  Phi 3 mini, Qwen 2.5, Smol LM, Gemma 2b, DeepSeek distlled, and so on) requiring ONLY about 2GB additional memory and reasonable compute load

- breakthrough [webgpu and webllm](https://webllm.mlc.ai/) technology matured; and in-browser inference and LLM API access (WASM'ed Python code on top of HTML5/WebGPU standard) is a stable working reality

- big-tech vendors (phone and OS vendors such as Apple, Samsung, Microsoft, and so on ... ) are rapidly bringing client-side *CLOSED SOURCE* inference capability to their own applications with no roadmap in 2025 for general access

💪 **Desired Skills:**  

- Rocket.Chat Deployment Flows (DevOps)
- Advanced Typescript
- Awareness of WASM and webllm 
- Python magician
- Good system design mindset

🎯 **Goals/Deliverables:**  

Empower the development of scalable open source AI applications running in-browser for all Rocket.Chat users  

⏳ **Project Duration:** 175 hours (Medium)  

📈 **Difficulty:** Advanced  

---

### 💡 AI Enhanced Message Composer Component

👥 **Mentor(s):** Sing Li, Ashutosh Singh Chauhan

💬 **Description:**  

This project aims to add **AI-powered message enhancements** directly into Rocket.Chat’s **Message Composer**, allowing users to refine their messages before sending. The enhancements will focus on:

- **Grammar and Spelling Corrections**
- **Rephrasing for Clarity**
- **Tone Adjustments** (e.g., formal, casual)

**Implementation Details:**

- **Message Composer Enhancements:**  
  - **Inline Suggestions:** Highlight areas needing improvement (grammar, clarity). Click to apply changes.
  - **Tone Selector:** Add a dropdown to adjust the tone (e.g., formal or casual), and apply the change automatically.
  - **Message Preview:** Allow users to toggle between the original and enhanced message.

- **AI Integration:**  
  - Use a lightweight AI model (e.g., **Llama 3.2**) for **client-side** processing via **WASM** or **WebGPU**.

- **UI Integration:**  
  - Display suggestions as subtle highlights or underlines, ensuring a smooth, non-intrusive experience.

💪 **Desired Skills:**  
- **Rocket.Chat Composer Component Knowledge**
- **Advanced JavaScript/TypeScript**
- **UI/UX Design**

🎯 **Goals/Deliverables:**  
- **AI Enhancements** in the Message Composer.
- **UI/UX Polish** for a seamless experience.
- **Cross-Platform Support** across web, mobile, and electron clients.

⏳ **Project Duration:** 175 hours (Medium)  
📈 **Difficulty:** Easy/Intermediate

----

### 💡 AI Google Forms / Typeform Survey Integration App

👥 **Mentor(s):** Abhinav kumar

💬 **Description:**  
This app integrates any one of the popular survey tools (Google Forms, Typeform etc.) into Rocket.Chat to allow teams to create, distribute, and analyze quick polls or feedback forms without leaving the chat. Users can launch surveys, receive immediate notifications when responses are submitted, and have summary reports automatically posted to designated channels.

Using natural language to create forms would be a huge plus for the project.
Example - "Create a form to accept registration for the Annual Tech Conference. It should collect full name, email address, company, and dietary restrictions. Validate the email field, send me a notification on each new registration, and post a summary report in the #conference-registrations channel."

**Key Features:**
- **Slash Commands:** Launch new surveys or share form links directly from Rocket.Chat.
- **Inline Notifications:** Receive real-time alerts when survey responses are submitted.
- **Automated Reporting:** Generate and post periodic summary reports in designated channels.

**Use Case:**  
Enables teams to capture immediate feedback and conduct internal polls seamlessly within Rocket.Chat, enhancing decision-making and team engagement.

💪 **Desired Skills:**  
- Proficiency with Rocket.Chat Apps Engine (TypeScript)  
- Experience with REST APIs and third‑party service integrations  
- Familiarity with survey platforms (Google Forms, Typeform) and their APIs

🎯 **Goals/Deliverables:**  
- Develop a Rocket.Chat App that connects to Google Forms/Typeform.  
- Implement slash commands for survey creation and sharing.  
- Integrate real-time notifications for survey responses.  
- Automate the generation and posting of summary reports.

⏳ **Project Duration:** 90 hours (Small)  
📈 **Difficulty:** Easy/Intermediate

---

### 💡Trip Helper App 

👥 **Mentor(s):** TBD

💬 **Description:**  

This LLM-powered app will suggest interesting events and happenings for users during their trip.   

Details:

* While on trip in a foreign place, a user can take a photo of his surroundings and upload it to a channel
* The app will first process the image by passing it to an image reasoning multi-modal LLM to ascertain the location or point of interest or event venue (perhaps reinforced by GPS location information).  
* Then in a second step an(other) LLM's tools/function-calling capability is used to fetch up-to-date events and happening information over the Internet, catering for the user's current interest. 
* Finally, a friendly summary report is produced by an(other) LLM as the last step of a RAG pipeline. 
* This app should never produce erraneous output. It should know its own limitaion and decline to report if in doubt.   


💪 **Desired Skills:**  

- Rocket.Chat Apps Engine (TypeScript)  
- Familiarity with the "RAG" agentic workflow  
- Intermediate prompt engineering Skills   
- Experience with image reasoning capabilities of modern open source multi-modal LLMs  
- Experience with tools/function-calling capabilities of modern LLMs

🎯 **Goals/Deliverables:**  

- A working Rocket.Chat App that assists users with latest happenings around them wherever they may be while on any trip. 

⏳ **Project Duration:** 90 hours (Small)  

📈 **Difficulty:** Intermediate/Advanced  

----

### 💡 AI Transcription and Translation for Voice Messages App

👥 **Mentor(s):** Dhurv Jain, Abhinav Kumar

💬 **Description:**  
Rocket.Chat already supports sending voice messages. This project enhances that feature by providing on-demand or real-time transcription and translation of voice messages. Users can choose to transcribe voice messages to text and optionally translate into their preferred language, thereby boosting accessibility and making communication more inclusive.

**Possible Milestones:**
- **UI/UX Enhancements:**  
  - Integrate options into the existing voice message interface for triggering transcription and translation.
- **Backend Processing:**  
  - Integrate with a speech-to-text service (e.g., Google Cloud Speech-to-Text or open‑source alternatives like Vosk) to transcribe voice messages.
- **Translation Integration:**  
  - Connect with a translation API (e.g., Google Translate or LibreTranslate) to convert transcriptions into the target language.
- **Performance & Accuracy Tuning:**  
  - Optimize for low latency and high transcription accuracy, ensuring the system gracefully handles slow or unavailable external APIs.

💪 **Desired Skills:**  
- Experience with Rocket.Chat Apps Engine (TypeScript)  
- Familiarity with speech-to-text and translation APIs  
- Skills in mobile and web UI/UX enhancement  
- Ability to optimize performance and implement robust error handling

🎯 **Goals/Deliverables:**  
- A Rocket.Chat App that enhances the existing voice message feature with transcription and translation capabilities.
- Seamless integration with external speech-to-text and translation services.
- An intuitive interface that allows users to trigger transcription and translation on demand or in real time.

⏳ **Project Duration:** 90 hours (Small)  
📈 **Difficulty:** Intermediate/Advanced

---

