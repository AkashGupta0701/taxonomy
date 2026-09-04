# Bobathon Builder Guide - Client Engineering Self-Serve Edition

## 🎯 Overview

The **Bobathon Builder** is a custom Bob mode designed specifically for Client Engineering teams to create customized bobathons for their clients. This self-serve guide enables CE teams to independently prepare high-quality, client-specific Bob training sessions.

### What You'll Accomplish

With this guide, CE teams can:
- ✅ Create complete, client-ready bobathons in 30-45 minutes
- ✅ Customize labs for any technology stack (Python, Java, JavaScript, etc.)
- ✅ Generate client-specific use cases and scenarios
- ✅ Validate materials for quality and completeness
- ✅ Package bobathons for delivery to clients

### Key Benefits for CE Teams

- **Self-Service:** No dependency on other teams
- **Consistency:** Standardized quality across all bobathons
- **Speed:** Rapid turnaround for client requests
- **Flexibility:** Easy customization for any client scenario
- **Quality:** Built-in validation ensures completeness

---

## 📦 Installation & Setup

### Prerequisites

Before starting, ensure you have:
- [ ] Bob installed in VS Code
- [ ] Access to this bobathon template repository
- [ ] Basic understanding of your client's technology stack
- [ ] Client information ready (company name, tech stack, use cases)

### Step 1: Clone the Template

```bash
git clone [bobathon-template-repo-url]
cd bob-bootcamp-builder
```

### Step 2: Open in VS Code

```bash
code .
```

### Step 3: Verify Bobathon Builder Mode

1. Open Bob in VS Code
2. Look for the mode selector (shows current mode like "💻 Code")
3. Click it and verify "🎓 Bobathon Builder" appears in the list

**If the mode doesn't appear:**
- Press `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (Mac)
- Type "Reload Window" and press Enter
- Bob will reload and detect the `.bobmodes` file

### Step 4: Switch to Bobathon Builder Mode

1. Click the mode selector in Bob
2. Select "🎓 Bobathon Builder"
3. You're ready to create bobathons!

---

## 🚀 Quick Start: Create Your First Bobathon

### The 5-Step Process

```
1. Switch to Bobathon Builder mode
2. Tell Bob about your client
3. Answer guided questions
4. Review and validate
5. Save and deliver
```

### Example: Complete Workflow (Streamlined for CE)

```
You: "Create a new bobathon for Acme Financial Services"

Bob will guide you through ESSENTIAL information only:

├── Client Information (REQUIRED)
│   ├── Company name: Acme Financial Services
│   └── Industry: Banking/Financial Services
│
├── Technology Stack (REQUIRED)
│   ├── Language: Python
│   ├── Framework: FastAPI
│   ├── Frontend: React
│   └── Database: PostgreSQL
│
├── Use Cases (REQUIRED - minimum 3, at least 2 high priority)
│   ├── [High] API Development for trading endpoints
│   ├── [High] Real-time data processing optimization
│   ├── [High] Security compliance automation
│   └── [Medium] Testing and debugging workflows
│
└── Duration (REQUIRED)
    └── 6 hours (full day)

OPTIONAL (can be added later if needed):
- Specific date and timezone
- Participant details (count, roles, skill levels)
- Contact information
- Application type

Bob then generates:
✅ bobathon-config.yaml (complete configuration)
✅ Customized Lab 1 (Python/FastAPI examples)
✅ Customized Lab 2 (Advanced Python workflows)
✅ Customized Lab 3 (Trading platform use cases)
✅ Detailed schedule (6-hour agenda)
✅ Client-facing README
✅ Validation report (all checks passed)
```

**Time to complete:** 30-45 minutes

---

## 📋 CE-Specific Workflows

### Workflow 1: Standard Client Bobathon (Most Common)

**When to use:** New client engagement, standard 6-hour bobathon

**Steps:**
```
1. Switch to Bobathon Builder mode

2. Start the process:
   "Create a new bobathon for [Client Name]"

3. Provide ESSENTIAL information when asked:
   - Company name and industry (REQUIRED)
   - Technology stack: language + framework (REQUIRED)
   - 3+ use cases with priorities (REQUIRED)
   - Duration: 3, 6, or 12 hours (REQUIRED)

4. Choose code generation strategy (MANDATORY):
   - Both starter + solutions (recommended for CE)
   - Starter only (hands-on focus)
   - Solutions only (custom starter code)
   - Live generation (advanced facilitators)
   - No generation (using client codebase)

5. Review and validate:
   "Validate the bobathon materials"

6. Save:
   "Save the bobathon"
   Choose: Export to new directory (recommended for CE)

OPTIONAL (Bob will ask, but you can skip):
- Contact details
- Application type
- Specific date and timezone
- Participant details (count, roles, skill levels)
- Infrastructure details
```

**Expected output:**
- Complete bobathon in `../{client-name}-bobathon/`
- Ready to deliver to client
- All materials validated and consistent

---

### Workflow 2: Quick Customization (Existing Config)

**When to use:** You have a bobathon config but need to customize labs

**Steps:**
```
1. Switch to Bobathon Builder mode

2. Request customization:
   "Customize all labs for the client in bobathon-config.yaml"

3. Bob will:
   - Read existing configuration
   - Ask about code generation strategy (if not set)
   - Customize Lab 1 for client's tech stack
   - Customize Lab 2 for client's tech stack
   - Create Lab 3 scenarios from use cases
   - Generate code based on strategy
   - Validate everything

4. Review and save:
   "Validate and save the bobathon"
```

**Time to complete:** 15-20 minutes

---

### Workflow 3: Schedule Adjustment

**When to use:** Client's available time changed

**Steps:**
```
1. Switch to Bobathon Builder mode

2. Request adjustment:
   "We only have 4 hours instead of 6, adjust the schedule"

3. Bob will:
   - Recalculate timing for all sessions
   - Prioritize high-value use cases
   - Suggest what to condense or skip
   - Update schedule files
   - Validate new timing

4. Review changes:
   "Show me the updated schedule"
```

**Time to complete:** 5-10 minutes

---

### Workflow 4: Technology Stack Change

**When to use:** Client changed their tech stack after initial planning

**Steps:**
```
1. Switch to Bobathon Builder mode

2. Request change:
   "Change the tech stack from Java to Python with Django"

3. Bob will:
   - Update bobathon-config.yaml
   - Regenerate Lab 1 with Python/Django examples
   - Regenerate Lab 2 with Python/Django workflows
   - Update Lab 3 scenarios for Django
   - Regenerate code samples
   - Validate consistency

4. Verify changes:
   "Validate the bobathon materials"
```

**Time to complete:** 20-25 minutes

---

### Workflow 5: Add/Modify Use Cases

**When to use:** Client wants different scenarios in Lab 3

**Steps:**
```
1. Switch to Bobathon Builder mode

2. Request modification:
   "Replace the testing use case with a security compliance use case"

3. Bob will:
   - Update use cases in config
   - Regenerate Lab 3 with new scenario
   - Adjust timing if needed
   - Update schedule
   - Validate changes

4. Review Lab 3:
   "Show me the updated Lab 3 scenarios"
```

**Time to complete:** 10-15 minutes

---

## 💡 CE Best Practices

### 1. Gather Information Before Starting (Streamlined for CE)

**Prepare ONLY this essential information before creating a bobathon:**

**✅ REQUIRED (Must Have - Bob needs these):**
- [ ] Company name and industry
- [ ] Programming language(s)
- [ ] Primary framework(s)
- [ ] 3-4 key use cases or pain points
- [ ] Priority level for each use case (high/medium/low)
- [ ] Available duration (3, 6, or 12 hours)

**⚪ OPTIONAL (Nice to Have - Can skip or add later):**
- [ ] Contact details
- [ ] Application type
- [ ] Database technology
- [ ] Cloud provider
- [ ] Specific date and timezone
- [ ] Participant count and roles
- [ ] Development tools

**Pro Tip:** Focus on the 6 REQUIRED items only. This streamlined approach saves 50% of prep time and you can always add optional details later if needed.

**Minimum Viable Information Example:**
```
Client: Acme Corp, Financial Services
Tech: Python, FastAPI, React
Use Cases:
  1. [High] API development
  2. [High] Security compliance
  3. [High] Performance optimization
Duration: 6 hours
```
✅ This is enough to create a complete, client-ready bobathon!

---

### 2. Choose the Right Code Generation Strategy

**For CE teams, we recommend:**

| Strategy | When to Use | CE Recommendation |
|----------|-------------|-------------------|
| **Both starter + solutions** | Standard bobathons, new facilitators | ⭐ **Recommended** - Complete package, ready to deliver |
| **Starter only** | Hands-on learning focus, experienced facilitators | Good for interactive sessions |
| **Solutions only** | Custom starter code, specific requirements | Use when client provides code |
| **Live generation** | Showcase Bob's power, advanced facilitators | Advanced CE only |
| **No generation** | Using actual client codebase | Best for Lab 3 only |

**CE Default:** Choose "Both starter + solutions" unless you have a specific reason not to.

---

### 3. Validate Before Every Delivery

**Always run validation before considering a bobathon complete:**

```
"Validate the bobathon materials and fix any issues"
```

**What validation checks:**
- ✅ All required fields populated
- ✅ No placeholder text ([Client Name], etc.)
- ✅ Timing calculations correct
- ✅ Tech stack consistency
- ✅ Use cases properly defined (3+, 2+ high priority)
- ✅ Code generation strategy set
- ✅ Bob differentiators inline (4-5 per lab)
- ✅ No dollar amounts in business impact
- ✅ All required files exist

**If validation fails:**
1. Bob will report specific issues
2. Ask Bob to fix them: "Fix all validation issues"
3. Bob will resolve and re-validate
4. Only proceed when validation passes

---

### 4. Use Client's Actual Technology

**Labs 1 & 2 Technology Decision:**

When Bob asks: "Should Labs 1 & 2 use [client's tech stack] or generic examples?"

**Choose client's tech stack when:**
- ✅ Client uses specific/less common technology
- ✅ Team needs practice with their stack
- ✅ You have time for full customization (30+ min)
- ✅ Examples in client's tech will be more engaging

**Choose generic examples when:**
- ✅ Time is limited (< 30 min prep time)
- ✅ Client uses very common tech (Python, JavaScript, Java)
- ✅ Focus is on Bob concepts, not language specifics
- ✅ Team is already expert in their stack

**CE Recommendation:** Use client's tech stack for better engagement, unless time is very limited.

---

### 5. Lab 3 Always Uses Client Codebase

**For Lab 3 (Client-Specific Implementation):**

When Bob asks: "For Lab 3, what code will participants work with?"

**CE Best Practice:**
- ✅ **Always choose:** "Use actual customer codebase"
- ✅ This provides the most realistic, valuable experience
- ✅ Participants work on their actual problems
- ✅ Immediate applicability to their daily work

**What you need:**
- Access to client's repository
- Permissions for participants
- Identified areas for improvement
- Backup/branch strategy

**Document in Lab 3 setup:**
- Repository URL
- Access requirements
- Branch to use
- Prerequisites (dependencies, data)

---

### 6. Package for Client Delivery

**When saving, choose the right option:**

**For CE teams, we recommend:**

```
Option 1: Export to new directory (RECOMMENDED)
├── Creates: ../{client-name}-bobathon/
├── Includes: All bobathon materials
├── Excludes: Template files (.bob/, .bobmodes, examples/)
├── Result: Clean, client-ready package
└── Next: Zip and send to client
```

**Steps after export:**
1. Navigate to the exported directory
2. Review the README.md (client-facing)
3. Zip the entire directory
4. Send to client with setup instructions
5. Schedule pre-bobathon setup call

**Alternative for version control:**
```
Option 2: Prepare for new repository
├── Creates: Branch with bobathon
├── Asks: Target repository URL
├── Provides: Exact git commands
└── Result: Ready to push to client's repo
```

---

### 7. Pre-Bobathon Checklist

**Before the bobathon day, verify:**

**Materials:**
- [ ] bobathon-config.yaml complete (no placeholders)
- [ ] All labs customized for client's tech stack
- [ ] Lab 3 uses client's actual use cases
- [ ] Code samples generated (if applicable)
- [ ] Schedule matches available time
- [ ] Validation passed with no errors

**Client Setup:**
- [ ] Bob installed on all participant machines
- [ ] Access to client codebase (for Lab 3)
- [ ] Development environment configured
- [ ] Test data loaded (if needed)
- [ ] Network/firewall access verified

**Facilitator Prep:**
- [ ] Reviewed all lab materials
- [ ] Tested code samples
- [ ] Prepared for Q&A
- [ ] Backup plan for technical issues
- [ ] Contact info for support

**Logistics:**
- [ ] Meeting link sent
- [ ] Calendar invites confirmed
- [ ] Materials shared with participants
- [ ] Break times scheduled
- [ ] Feedback survey prepared

---

## 🎓 Understanding Bobathon Structure

### Standard 6-Hour Bobathon

```
Morning Session (3 hours)
├── Introduction (30 min)
│   ├── Welcome and objectives
│   ├── Bob overview
│   └── Setup verification
│
├── Lab 1: Basic Operations (60 min)
│   ├── File navigation
│   ├── Code search
│   ├── Simple edits
│   ├── Command execution
│   └── Bob modes and features
│
├── Lab 2: Advanced Workflows (60 min)
│   ├── Multi-file refactoring
│   ├── Feature implementation
│   ├── Debugging
│   └── Code quality improvement
│
└── Break (30 min)

Afternoon Session (3 hours)
├── Lab 3: Client-Specific (150 min)
│   ├── Use Case 1 (30-45 min)
│   ├── Use Case 2 (30-45 min)
│   ├── Use Case 3 (30-45 min)
│   └── Open-ended challenge (remaining time)
│
└── Wrap-up (30 min)
    ├── Key takeaways
    ├── Next steps
    ├── Q&A
    └── Feedback survey
```

### Condensed 3-Hour Bobathon

```
Single Session (3 hours)
├── Introduction (20 min)
├── Lab 1: Basic Operations (40 min) - Condensed
├── Lab 2: Advanced Workflows (40 min) - Condensed
├── Break (10 min)
├── Lab 3: Client-Specific (60 min) - Top 2 use cases only
└── Wrap-up (10 min)
```

### Extended 12-Hour Bobathon (2 Days)

```
Day 1: Deep Dive (6 hours)
├── Introduction (30 min)
├── Lab 1: Basic Operations (90 min) - Extended with more exercises
├── Lab 2: Advanced Workflows (90 min) - Extended with complex scenarios
├── Lunch (60 min)
├── Advanced Topics (90 min)
│   ├── MCP integrations
│   ├── Custom modes
│   └── Enterprise patterns
└── Day 1 Wrap-up (30 min)

Day 2: Client Implementation (6 hours)
├── Day 1 Recap (30 min)
├── Lab 3: Client-Specific (270 min) - All use cases + open challenges
├── Lunch (60 min)
├── Team Projects (60 min) - Work on actual backlog items
└── Final Wrap-up (30 min)
```

---

## 🔍 Troubleshooting for CE Teams

### Issue: Client's Tech Stack is Unusual

**Problem:** Client uses a less common language or framework

**Solution:**
```
1. Tell Bob about the specific technology:
   "The client uses Rust with Actix-web framework"

2. Bob will:
   - Research the technology
   - Generate appropriate examples
   - Customize labs accordingly

3. If Bob struggles:
   - Provide example code snippets
   - Reference documentation URLs
   - Use generic examples as fallback
```

---

### Issue: Not Enough Time for Full Customization

**Problem:** Client needs bobathon in < 24 hours

**Solution:**
```
1. Use the fastest workflow:
   "Create a bobathon for [Client] using generic examples for Labs 1-2"

2. Focus customization on Lab 3 only:
   - Lab 1: Generic Bob features (15 min prep)
   - Lab 2: Generic workflows (15 min prep)
   - Lab 3: Client-specific (30 min prep)

3. Total prep time: ~60 minutes

4. Quality trade-off:
   - Labs 1-2 less relevant to client's daily work
   - Lab 3 still highly valuable
   - Can update Labs 1-2 later if needed
```

---

### Issue: Client Changed Requirements

**Problem:** Client changed tech stack or use cases after initial prep

**Solution:**
```
1. Don't start over! Update incrementally:
   "Change the tech stack from Java to Python"
   "Replace use case 2 with database optimization"

2. Bob will:
   - Update only affected sections
   - Maintain other customizations
   - Re-validate consistency

3. Time to update: 15-20 minutes
```

---

### Issue: Validation Fails

**Problem:** Validation reports errors before delivery

**Solution:**
```
1. Don't panic! This is why we validate:
   "Validate the bobathon materials"

2. Bob will report specific issues:
   ❌ Code generation strategy not set
   ❌ Lab 2 missing Bob differentiators
   ❌ Dollar amounts in business impact

3. Ask Bob to fix:
   "Fix all validation issues"

4. Bob will:
   - Resolve each issue
   - Re-validate automatically
   - Confirm when ready

5. Only deliver after validation passes
```

---

### Issue: Client Needs Different Duration

**Problem:** Client can only do 4 hours instead of 6

**Solution:**
```
1. Request adjustment:
   "Adjust the schedule for 4 hours instead of 6"

2. Bob will:
   - Recalculate all timing
   - Prioritize high-value content
   - Suggest what to condense
   - Update schedule files

3. Review the changes:
   "Show me what was adjusted"

4. Typical 4-hour structure:
   - Introduction: 20 min
   - Lab 1: 40 min (condensed)
   - Lab 2: 40 min (condensed)
   - Break: 10 min
   - Lab 3: 90 min (top 2 use cases)
   - Wrap-up: 20 min
```

---

## 📊 CE Success Metrics

### Track These Metrics for Each Bobathon

**Preparation Efficiency:**
- Time to create bobathon: Target < 45 minutes
- Validation pass rate: Target 100% (after fixes)
- Customization completeness: Target 100%

**Client Satisfaction:**
- Relevance to daily work: Target 4.5+/5
- Lab quality: Target 4.5+/5
- Facilitator preparedness: Target 4.5+/5

**Business Impact:**
- Participants planning to adopt Bob: Target 80%+
- Estimated time savings: Track hours/week
- Use cases addressed: Target 100%

**CE Team Performance:**
- Bobathons delivered per month
- Average prep time per bobathon
- Client feedback scores
- Repeat engagement rate

---

## 🎯 CE Quick Reference

### Essential Commands

```bash
# Start a new bobathon
"Create a new bobathon for [Client Name]"

# Customize existing config
"Customize all labs for the client in bobathon-config.yaml"

# Adjust schedule
"Adjust the schedule for [X] hours"

# Change technology
"Change the tech stack to [Language/Framework]"

# Validate materials
"Validate the bobathon materials and fix any issues"

# Save bobathon
"Save the bobathon"
```

### Time Estimates

| Task | Time Required |
|------|---------------|
| Complete new bobathon (scratch) | 30-45 min |
| Customize labs (existing config) | 15-20 min |
| Adjust schedule | 5-10 min |
| Change tech stack | 20-25 min |
| Validate and fix issues | 5-10 min |
| Package for delivery | 5 min |

### Decision Matrix

| Question | CE Recommendation |
|----------|-------------------|
| Code generation strategy? | Both starter + solutions |
| Labs 1-2 technology? | Client's tech stack (if time allows) |
| Lab 3 code source? | Actual client codebase |
| Save method? | Export to new directory |
| Duration? | 6 hours (full day) |
| Validation? | Always before delivery |

---

## 📚 Additional CE Resources

### Internal Documentation

- **CE Bobathon Playbook:** [Internal link]
- **Client Discovery Template:** [Internal link]
- **Facilitator Training:** [Internal link]
- **Success Stories:** [Internal link]

### Template Files

- `bobathon-config.yaml` - Main configuration
- `labs/lab1-basic-operations/instructions.md` - Lab 1 template
- `labs/lab2-advanced-workflows/instructions.md` - Lab 2 template
- `labs/lab3-client-specific/instructions.md` - Lab 3 template
- `schedule/detailed-agenda.md` - Schedule template
- `resources/` - Supporting materials

### Example Bobathons

- `examples/sample-config-fintech.yaml` - Financial services
- `examples/sample-config-healthcare.yaml` - Healthcare
- Review completed bobathons in team repository

---

## 🤝 CE Support & Escalation

### Self-Service Support

1. **Check this guide** for common scenarios
2. **Ask Bob directly** - it can explain its capabilities
3. **Review example bobathons** in the repository
4. **Consult CE playbook** for best practices

### When to Escalate

Escalate to CE leadership when:
- Client has unique requirements not covered in guide
- Technical issues with Bobathon Builder mode
- Validation fails repeatedly despite fixes
- Client requests features not in template
- Time-sensitive delivery with complications

### CE Team Collaboration

- **Share learnings:** Document new patterns in team wiki
- **Peer review:** Have another CE review before delivery
- **Feedback loop:** Update guide based on experience
- **Success stories:** Share wins with the team

---

## ✅ CE Delivery Checklist

### Before Client Engagement

- [ ] Client discovery call completed
- [ ] All required information gathered
- [ ] Bobathon created and customized
- [ ] Validation passed (no errors)
- [ ] Materials packaged for delivery
- [ ] Pre-bobathon setup call scheduled

### Day Before Bobathon

- [ ] Confirmed client setup (Bob installed, access verified)
- [ ] Reviewed all lab materials
- [ ] Tested code samples
- [ ] Prepared for Q&A
- [ ] Backup plan ready

### Day of Bobathon

- [ ] Materials accessible to all participants
- [ ] Meeting link working
- [ ] Screen sharing tested
- [ ] Break times communicated
- [ ] Feedback survey ready

### After Bobathon

- [ ] Collected participant feedback
- [ ] Documented lessons learned
- [ ] Shared success metrics with team
- [ ] Scheduled follow-up with client
- [ ] Updated CE knowledge base

---

## 🎉 You're Ready to Deliver Bobathons!

As a CE team member, you now have everything needed to:
- ✅ Create customized bobathons independently
- ✅ Deliver high-quality training to clients
- ✅ Validate materials for consistency
- ✅ Package bobathons for client delivery
- ✅ Troubleshoot common issues
- ✅ Track success metrics

### Your First Bobathon

**Start here:**
```
1. Switch to Bobathon Builder mode
2. Say: "Create a new bobathon for [Your Client Name]"
3. Follow the guided questions
4. Validate before delivery
5. Package and send to client
```

**Need help?** Ask Bob directly or consult this guide.

---

## 📞 CE Support Contacts

- **CE Leadership:** [Contact info]
- **Bobathon Builder Issues:** [Support channel]
- **Technical Questions:** [Tech support]
- **Best Practices:** [CE wiki]

---

**Version:** 1.0.0 - CE Edition  
**Last Updated:** 2026-06-15  
**Maintained By:** Client Engineering Team  
**Template:** Bob Client Bobathon Starter