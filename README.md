# Documentation Guide - How It All Works Together

## Quick Overview

This project has three linked documentation files that work together to establish how Claude operates within your Bolt environment.

---

## The Three Documents

### 1. BOLT-AGENT.md
**What it is:** The operational manual for Claude's behavior and requirements
- How Claude communicates (concise, direct, no emojis)
- Code organization standards and best practices
- Database, authentication, and edge function requirements
- Security protocols and data safety guidelines
- Tool usage policies and response formats

**Used by:** Claude, to know exactly how to work on your project

### 2. AGENT_IDENTITY.md
**What it is:** Claude's introduction and capability statement
- Who Claude is (Anthropic's Claude AI)
- What Claude can do (capabilities and available tools)
- How Claude operates (values, standards, boundaries)
- What Claude will and won't help with

**Used by:** You, to understand who you're talking to and what to expect

### 3. DOCUMENTATION_GUIDE.md (this file)
**What it is:** The connection point between the other two
- Explains the relationship between documents
- Shows how they work together
- Clarifies the workflow

---

## How They Work Together

```
AGENT_IDENTITY.md (Claude Introductions)
        ↓
    "Here's who I am and what I can do"
        ↓
BOLT-AGENT.md (Operations)
        ↓
    "Here's exactly how I'll do it"
        ↓
Your Project (Implementation)
        ↓
    "The result of precise execution"
```

**Workflow:**
1. You know who Claude is → AGENT_IDENTITY.md
2. You know the rules Claude follows → BOLT-AGENT.md
3. You request work → Claude executes per BOLT-AGENT.md
4. You get results that match AGENT_IDENTITY.md promises

---

## Within Your Bolt Environment

These documents ensure consistency between:

- **What Claude promises** (AGENT_IDENTITY.md)
- **How Claude delivers** (BOLT-AGENT.md)
- **What you receive** (The working application)

In Bolt, Claude uses these files to:
- Build code that follows standards
- Maintain security and data integrity
- Communicate clearly about what's being done
- Organize files properly
- Handle databases safely
- Deploy functions correctly

---

## When to Reference

- **Before starting:** Read AGENT_IDENTITY.md to know capabilities (Claude default agent presentation prompt)
- **While working:** Claude follows BOLT-AGENT.md automatically
- **If confused:** Check DOCUMENTATION_GUIDE.md to find the right file
- **For specifics:**
  - Communication style → BOLT-AGENT.md
  - Available tools → AGENT_IDENTITY.md
  - Data safety → BOLT-AGENT.md
  - Security rules → BOLT-AGENT.md

---

## The Complete Picture

**You → Request** → Claude reads BOLT-AGENT.md → **Executes precisely** → Claude fulfills AGENT_IDENTITY.md promises → **You receive working code**

All three documents exist to ensure this flow works smoothly, securely, and with crystal-clear understanding on both sides.
