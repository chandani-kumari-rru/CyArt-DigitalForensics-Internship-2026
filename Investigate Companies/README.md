# Company Fundamental


## Task

- As part of your cybersecurity onboarding, you will be assigned 25 cybersecurity companies to research and analyze.
- The objective of this project is to understand what security problems these companies are solving today and then use that understanding to explore how security needs change when AI agents interact with tools, APIs, data, and enterprise systems through MCP.

### Part 1 - Research the Assigned Companies

For each of the 25 assigned companies, research and document

1\. Company Fundamentals

• What does the company do
• What cybersecurity problem does it solve
• Who are its target customers
• Which security category does it operate in
  (AI Security, Application Security, Cloud Security, Identity Security, API Security, Data Security, etc.)

2\. Product \& Scope of Work
• What are its main productsplatforms
• What are the core features
• What threats does it address
• What does the product monitorprotect
• What actions can it take
• Is it primarily focused on Detection, Prevention, Monitoring, Governance, or Response

3\. Technical Understanding
Understand the basic workflow

Input → Security System → AnalysisDetection → Decision → ActionExplain what happens at each stage for the company you are researching.

4\. Security Problem Mapping
Create a table

Company  Security Category  Problem Addressed  What It Protects  Detection  Prevention  Response5. Your Understanding
For every company, write 5–10 lines in your own words explaining

• What does this company actually do
• What problem does it solve
• Why does that problem matter

Do not simply copy the company's website or marketing content.

### Part 2 - Learn AI Agent \& MCP Fundamentals

After understanding the companies, learn the fundamentals required to understand Agentic-Level Security.

Research
AI Fundamentals

• What is an LLM
• What is an AI Agent
• What is Agentic AI
• What is tool calling
• What is an API
• What is autonomous action

MCP Fundamentals

• What is MCP (Model Context Protocol)
• Why was MCP introduced
• What is an MCP Client
• What is an MCP Server
• What is an MCP Tool
• What are MCP Resources
• How does an AI Agent interact with MCP
• How can an MCP Server connect an AI Agent to external systems


You do not need to become an MCP developer for this task. The goal is to understand the architecture and its security implications.

### Part 3 - Analyze the Security Implications

Consider an environment like


```
User
 ↓
AI Agent
 ↓
MCP Client
 ↓
MCP Server
 ↓
Tools
 ↓
Database  API  Cloud  SaaS  Files
```


Identify what could go wrong.

Research threats such as

• Prompt Injection
• Excessive Permissions
• Unauthorized Tool Execution
• Credential Theft
• Data Leakage
• Sensitive Data Exposure
• Malicious MCP Servers
• MaliciousCompromised Tools
• Supply-Chain Attacks
• Privilege Escalation
• Identity Abuse
• Unauthorized API Calls
• Agent-to-Agent Attacks
• Improper Access Control
• Lack of Auditability

For each threat, explain
Attack → Impact → Security Control

Example

Attack
A malicious instruction causes an AI agent to invoke an unauthorized tool.

Impact
Sensitive enterprise data could be accessed or transferred.

Security Control
Tool-level authorization + policy enforcement + audit logging.


### Part 4 - Map Existing Security Concepts to MCP

For each assigned company, answer
Could this company's security approach or technology be useful in an MCPAI-Agent environment

Classify it as

• Directly Applicable
• Partially Applicable
• Not Obviously Applicable

Explain your reasoning.

Example

Company XYZ
Existing Capability Identity Security
MCP Use Case AgentTool Authorization
Applicability Directly Applicable
Reason Identity and authorization controls can be extended to control which agents can access specific tools and resources.


### Part 5 - Design Agentic-Level Security via MCP

Based on everything you have learned, design a conceptual security architecture for an AI-Agent environment.

Your architecture should address

Identity
• How should users be authenticated
• How should AI Agents be identified
• How should MCP Servers be authenticated



Authorization
• What tools can an Agent access
• What data can it access
• Which actions require additional approval
• How should permissions be grantedrevoked

Tool Security
• How do we verify an MCP Tool
• How do we determine whether a tool is trustworthy
• How do we prevent unauthorized tool execution



Data Security
• How do we prevent sensitive data leakage
• How should access to databases, files and APIs be controlled

Detection \& Monitoring
• What should we monitor
• How can we detect abnormal Agent behavior
• What should trigger an alert

Audit
What should be logged
• Who invoked the tool
• Which Agent invoked it
• What parameters were passed
• What data was accessed
• What action was performed
• What was the result

Response
What should happen when an Agent attempts a suspicious or dangerous action


### Part 6 - Identify Security Gaps

Based on your research, identify areas where existing security approaches may not fully address an MCP-based Agent environment.

Think about questions such as
• Is traditional Identity Security enough for AI Agents
• Is API Security enough for MCP Tools
• How do we establish trust in an MCP Server
• How do we determine whether an Agent's requested action is legitimate
• How should permissions change based on context
• How do we detect an Agent behaving outside its intended purpose
• How do we secure Agent-to-Tool communication
• How do we prevent an Agent from chaining multiple tools to perform a harmful action
• How should human approval work for high-risk actions



Clearly distinguish between

1\. What you found through research
2\. Your own proposed ideas

Final Deliverables
Each trainee should submit ONE consolidated project report containing

1\. Company Research

Research all 25 assigned companies.

2\. Cybersecurity Landscape

Explain the major security categories and problems you observed.



3\. AI \& MCP Fundamentals

Explain



LLM → AI Agent → Tool Calling → MCP → MCP Client → MCP Server → MCP Tool4. Threat Model

Document the major threats against an AI-AgentMCP environment.

5\. Security Architecture

Create an architecture diagram for your proposed

Agentic-Level Security via MCP



6\. Security Controls

Define controls for

• Identity
• Authentication
• Authorization
• Tool Security
• Data Security
• Policy Enforcement
• Monitoring
• Detection
• Audit Logging
• Incident Response



7\. Gap Analysis

- Identify security problems that may require additional controls or new approaches in an AgenticMCP environment.

8\. Final Proposal

- Conclude with your own conceptual proposal for



How should an enterprise securely allow AI Agents to interact with MCP Tools and real-world systems


Expected Outcome
- By completing this project, you should be able to explain
```
What today's cybersecurity companies are protecting
       ↓
What changes with AI Agents
       ↓
How MCP expands the attack surface
       ↓
What security controls are required
       ↓
What an Agentic-Level Security architecture could look like
```

Important
Focus on understanding and reasoning rather than copying.

We are evaluating your
• Cybersecurity fundamentals
• Research ability
• Technical understanding
• Threat modeling
• Security architecture thinking
• Ability to identify security gaps
• Ability to propose practical security controls

## List of 25 Companies
1. HiddenLayer
2. Akto
3. Rubrik
4. PromptArmor
5. ESET
6. Cyata
7. Oligo Security
8. Wallarm
9. WitnessAI
10. SecureAuth
11. Airia
12. Palo Alto Networks
13. Zenity
14. DeepKeep
15. Protecto
16. Enkrypt AI
17. Stacklok
18. Runlayer
19. NeuraTrust
20. Knostic
21. Capsule Security
22. Silverfort
23. Lumeus
24. Parakeet Security
25. TruU

