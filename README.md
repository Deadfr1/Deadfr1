# Vitaly Prochorov

I design and build software products around AI, automation, and practical business needs. I usually work across the whole process: understanding the problem, shaping the product, designing how its parts should work together, integrating models and services, and bringing the result to a usable state.

A lot of my work is about more than adding an AI feature to an existing product. I’m interested in building complete systems: applications where data, models, agents, APIs, and user workflows work together to solve a real task.

I use AI coding tools in development, but the important part of my work is the engineering and product side: defining the task, making architectural decisions, orchestrating the components, checking their output, and improving the system based on how it performs in practice.

## Selected projects

### [XPro AI](https://xproai.ru) — AI platform for social media growth

XPro AI brings several parts of social media marketing into one connected process. The platform is designed to help businesses and creators understand what is happening in their niche, identify relevant content opportunities, and turn those insights into posts for their social channels.

The product combines competitor analysis, trend research, topic selection, and AI-assisted content generation. The goal is to connect research with execution: instead of planning content in isolation, users can work from competitor activity and current audience interests, then prepare content for platforms such as Instagram, Threads, Telegram, VK, and others.

I’m developing the product as an integrated system rather than a standalone text generator — with an emphasis on useful analysis, a consistent brand voice, and a workflow that reduces routine work while leaving decisions and control with the user.

### СПЕЦ-КП — document processing and commercial proposal automation

A desktop application developed for a customer to turn engineering specifications into structured commercial proposals.

The application processes source documents in PDF format, including scanned files, extracts their contents using OCR, and helps the user review and verify the recognized data. It then works with the extracted positions and prepares a commercial proposal in Excel according to the customer's template and requirements.

The challenge is not just reading a PDF. The solution has to deal with different document structures, recognize and organize technical positions, support human review where automatic processing may be uncertain, and transfer the approved information into a usable business document. The project brings document processing, OCR, data extraction, matching, validation, and spreadsheet generation into one desktop workflow.

The source code and customer materials are private.

### Multi-agent orchestrator for legal research and academic article production

An orchestration system designed to support the full research and writing process for scientific legal articles, including work in the field of criminal law and procedure and requirements relevant to VAK publications.

This is not a single prompt or a basic text-generation workflow. The system coordinates multiple specialized stages and agents, each responsible for a defined part of the research process. It starts with research planning and the formulation of the task, then coordinates source discovery, iterative search, source evaluation, bibliographic work, parsing, and the preparation of structured research material for subsequent writing.

A central part of the architecture is source quality and traceability. The system is designed to work with relevant academic publications, legal databases, legislation, and court materials; distinguish useful sources from unsuitable ones; avoid duplicates and unsupported references; and preserve bibliographic details and page-level references where available. The writing process is grounded in the collected material rather than relying on plausible-sounding but unverifiable citations.

The orchestrator also has to manage the practical complexity of multi-step research: coordinating agents, passing structured data between stages, handling search iterations and rate limits, and keeping the output consistent across the pipeline. The result is a controlled research and drafting environment, not an attempt to replace legal expertise or academic review with one AI response.

### LLM chat and model orchestration

A chat application concept focused on making different language models and AI capabilities available through one interface.

The underlying idea is to avoid tying every request to a single model. The system can take the conversation and task into account when selecting an appropriate model or processing route. This creates room for different trade-offs between response quality, speed, cost, and the type of work being performed.

The project explores the application layer around LLMs: conversation context, model access, routing logic, and the integration of multiple AI providers into a coherent user experience.

### Websites, applications, and business automation

Alongside larger products, I work on websites, client applications, internal tools, messaging bots, and integrations that connect existing services and business processes.

These projects vary in scope — from a focused tool that removes a repetitive manual step to a more complete application with its own interface, data processing, and external integrations. I approach them by looking at the whole process first: what information comes in, what needs to happen to it, which systems are involved, and what the user should receive at the end.

Some of this work is commercial or private, so I describe the engineering problems and solutions without publishing client code or confidential details.

## Tools and technologies

- **AI models and platforms:** OpenAI, DeepSeek, OpenRouter
- **AI-assisted development:** Codex, Cursor, OpenCode
- **Agents and orchestration:** n8n, MCP, multi-agent workflows, API integrations
- **Development:** Python, JavaScript, TypeScript, React, Next.js, FastAPI
- **Data and infrastructure:** PostgreSQL, Qdrant, Docker, Linux, VPS, REST APIs, webhooks
- **Document processing:** PDF extraction, OCR, structured data processing, Excel generation

I choose the stack based on the requirements of a project. The tools matter, but the way the components are connected and the reliability of the complete process matter more.

## How I work

I start by understanding the actual task and the result the product needs to deliver. Then I break the problem into components, decide how they should interact, and choose the tools and architecture that make sense for that particular case.

I pay close attention to the parts that are easy to overlook in a demo but important in real use: data quality, failure cases, integrations, validation, repeatability, and what happens when an automated step is unsure. I prefer a working system that can be tested and improved over a convincing prototype that only works in an ideal scenario.

## Links

- [XPro AI](https://xproai.ru)
- [GitHub](https://github.com/Deadfr1)

---

*Some projects are commercial or private. Where the code cannot be shared, I explain the scope of the work and the problems the system is designed to solve.*
