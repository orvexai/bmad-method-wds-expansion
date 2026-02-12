# WDS Training & Learning Guide

Welcome to the Whiteport Design Studio (WDS) learning system! This guide helps you understand the WDS methodology and become proficient in strategic design.

## Learning Paths

### 🎯 Quick Start (30 minutes)
**Goal:** Understand WDS basics and run your first workflow

1. **WDS Overview** - What is WDS and why use it?
2. **Agent Introduction** - Meet Saga, Idunn, Freya, and Mimir
3. **First Project** - Run workflow-init to set up your first project
4. **Core Concepts** - UX vs Visual Design, Phase Independence

**Outcome:** You can initialize a WDS project and understand the agent roles

---

### 📚 Foundation Course (2-3 hours)
**Goal:** Master the core WDS methodology

#### Module 1: Strategic Foundation
- Product Brief creation with Saga
- Understanding trigger mapping
- Connecting business goals to user psychology

#### Module 2: Design Process
- UX Design (HOW it works) vs Visual Design (HOW it looks)
- Phase independence and workflow selection
- Design deliverables and handoff

#### Module 3: Tool Integration
- Figma MCP integration
- AI image generation with NanoBanana/Eira
- html.to.design workflow

**Outcome:** You can execute full design cycles independently

---

### 🚀 Advanced Topics (project-based)
**Goal:** Optimize WDS for your specific needs

- Custom methodology configuration
- Multi-language product design
- Design system architecture
- Agent collaboration patterns
- BMM integration for development handoff

**Outcome:** You can adapt WDS to complex product requirements

---

## Teaching Philosophy

### Mimir's Approach

**Adaptive to Experience Level:**
- **Beginner:** Detailed explanations, step-by-step guidance, encourage exploration
- **Intermediate:** Balanced approach, contextual tips, assume base knowledge
- **Expert:** Direct and efficient, focus on nuance and edge cases

**Emotional Intelligence:**
- Recognize when you're overwhelmed → simplify and break down
- Recognize when you're confident → accelerate and challenge
- Recognize when you're stuck → provide alternative approaches

**Learning by Doing:**
- Theory is introduced just-in-time when needed
- Every concept is immediately applied to your project
- Mistakes are learning opportunities, not failures

---

## Key Concepts Reference

### Design Phases

| Phase | Output Folder | Purpose | Timing |
|-------|---------------|---------|--------|
| 1: Product Exploration | A-Product-Brief | Strategic foundation & vision | Start here |
| 2: User Research | B-Trigger-Map | User psychology & business goals | After Phase 1 |
| 3: Requirements (optional) | D-PRD | Technical requirements | Before development |
| 4: UX Design | C-Scenarios | HOW it works - functionality | After Phase 2 |
| 5: Visual Design | D-Design-System | HOW it looks - brand identity | **Anytime** |
| 6: Dev Integration | E-UI-Roadmap | Development handoff | After Phase 4 |

### Agent Specializations

**Saga (Analyst)**
- Product discovery and strategic analysis
- Creates Product Brief and Trigger Map
- Uncovers strategic narrative

**Idunn (PM)**
- Product requirements and planning
- Platform PRD creation
- Coordinates handoffs

**Freya (Designer)**
- UX/UI design execution
- Design system creation
- Component specifications

**Mimir (Orchestrator)**
- Teaching and guidance
- Workflow selection
- Emotional intelligence support

---

## Common Questions

### "When should I start visual design?"

Anytime! Phase 5 (Visual Design) is independent of product timing:
- ✅ Before product work (brand-first approach)
- ✅ Parallel to strategy (simultaneous development)
- ✅ After strategy (informed by insights)

The design system goes in `D-Design-System/01-Visual-Design/` regardless of when you start it.

### "Do I need to complete all phases?"

No! WDS is phase-selectable. Choose based on your project needs:
- **Quick Prototype:** Phases 1, 4, 5
- **Full Product:** All phases in sequence
- **Design System Only:** Phase 5 standalone
- **Digital Strategy:** Phases 1, 2
- **Feature Enhancement:** Phases 4, 5, 6

### "How does WDS integrate with BMM?"

WDS handles design, BMM handles development:
1. Complete WDS through Phase 6 (UI Roadmap)
2. Hand off design deliverables to BMM
3. BMM uses design specs for Architecture and Stories
4. Development proceeds with complete design foundation

### "What if I don't use Figma?"

No problem! Figma integration is optional:
- Design system can be documented in markdown
- Component specs work with any design tool
- Focus on the methodology, not the tools

---

## Practice Exercises

### Exercise 1: Product Brief
**Time:** 30 minutes
**Goal:** Create a strategic foundation for a simple product

1. Activate Saga agent
2. Choose a simple product idea (e.g., habit tracker, recipe app)
3. Complete Product Brief workflow
4. Review output in `docs/A-Product-Brief/`

**Success criteria:** Brief includes vision, positioning, and success metrics

### Exercise 2: UX Scenarios
**Time:** 45 minutes
**Goal:** Design user experience for key flows

1. Activate Freya agent
2. Use your Product Brief from Exercise 1
3. Complete UX Design workflow for 2-3 key flows
4. Review scenarios in `docs/C-Scenarios/`

**Success criteria:** Scenarios define functionality and interactions clearly

### Exercise 3: Design System
**Time:** 1 hour
**Goal:** Create a simple design system

1. Activate Freya agent
2. Complete Design System workflow
3. Define: colors, typography, 3-5 components
4. Review in `docs/D-Design-System/`

**Success criteria:** Design tokens documented, components specified

---

## Next Steps

After completing this training:

1. **Apply to Real Project** - Use WDS on your actual work
2. **Explore Advanced Features** - Figma integration, AI image generation
3. **Customize Methodology** - Adapt phases to your workflow
4. **Integrate with BMM** - Complete design-to-development cycle

---

## Resources

- **WDS Documentation:** `/docs/` folder in module
- **Method Deep-Dives:** `/docs/method/` for detailed methodology
- **Templates:** `/reference/templates/` for document structures
- **Examples:** `/examples/` for real-world usage patterns

---

**Remember:** WDS is a guide, not a prescription. Adapt it to your needs, skip what doesn't serve you, and focus on creating products users love.

*For questions, activate Mimir agent and ask for guidance.*
