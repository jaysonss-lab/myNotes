# n8n Tutorial – Zero to Hero Course
- [Youtube Link: n8n Tutorial – Zero to Hero Course](https://www.youtube.com/watch?v=UIf-SlmMays)

---

## Table of Contents
* [Foundations of n8n: Nodes, Architecture, and Data Types](#foundations-of-n8n-nodes-architecture-and-data-types)
* [Building Your First AI Agent Workflow (Chatbot/Email Agent Demo)](#building-your-first-ai-agent-workflow-chatbotemail-agent-demo)

---

## Foundations of n8n: Nodes, Architecture, and Data Types

### Introduction to n8n and Nodes
- **n8n** is a free and open workflow automation tool that lets you connect different apps and services with ease.
- **Nodes** are the individual, visual building blocks that connect together to form an automation workflow.
    - **Trigger node** starts an automation workflow when a specific event happens.
    - **Action node** performs a task or processes data inside or at the end of that workflow.

![alt text](images/zero-to-hero-course/2026-08-12_18-38.png)

### Explore AI Agent architecture and API flow

![alt text](images/zero-to-hero-course/2026-08-12_18-50.png)

### Automate a full email-to-Slack use case

![alt text](images/zero-to-hero-course/2026-08-12_18-52.png)

![alt text](images/zero-to-hero-course/2026-08-12_18-56.png)

### Work with input formats and expressions
- **Every node has an input and an output data**, and the output data of this node will be the input payload of the next node. And that's how the logic strings the entire workflow.
- **Input and Output Formats** - Schema, Table, and JSON (Note: JSON is the most common.)

![alt text](images/zero-to-hero-course/2026-08-12_19-04.png)

- **Fixed vs Expression:** 
    - **Fixed** - treats your input as literal text or static configuration data.
    - **Expression** - allow your workflow to adapt to real-time inputs instead of being hardcoded in.

### Understand how n8n handles data types
- **String:** `Hello world"`
- **Numbers:** `42, 3.14, -100`
- **Boolean:** `True or False`
- **Arrays:** `[1,2,300], ["James","Tony","Samantha"]`
- **Object:**
```
{
"user":{
    "name":"John",
    "email":"john@gmail.com"
    }
}
```

### Community Nodes
- **Extensions and custom integrations** built by the n8n user community to provide functionality not available in n8n's built-in nodes.

---

<br>

