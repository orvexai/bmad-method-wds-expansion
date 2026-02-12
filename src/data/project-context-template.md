# WDS Project Context Template

## Design Project Overview

This template helps establish context for WDS (Whiteport Design Studio) design projects, focusing on strategic design considerations.

### Project Type

Select the primary project type:

- **Digital Product** - Web/mobile application or platform
- **Landing Page** - Marketing or campaign page
- **Website** - Multi-page website or portal
- **Feature Enhancement** - Updates to existing product
- **Design System** - Brand identity and component library
- **Other** - Custom or specialized project

### Design Focus Areas

The WDS methodology explores these key areas:

#### Strategic Foundation (Phase 1-2)

- **Vision and Positioning** - What is the product's unique value?
- **User Psychology** - What triggers motivate users?
- **Business Goals** - What business outcomes drive success?
- **Success Metrics** - How will we measure design effectiveness?

#### User Experience (Phase 4)

- **User Flows** - How do users accomplish their goals?
- **Information Architecture** - How is content organized?
- **Interactions** - How do users interact with the product?
- **Content Strategy** - What content is needed and when?

#### Visual Design (Phase 5)

- **Brand Expression** - How does design reflect brand values?
- **Visual Language** - What aesthetic communicates the message?
- **Design Tokens** - Colors, typography, spacing, etc.
- **Component System** - What UI patterns are needed?

### Design System Considerations

**Existing Design System:**
- None (page-specific components only)
- Custom Figma Design System
- Component Library (shadcn, Radix, etc.)

**Design Tools:**
- Figma (with or without MCP integration)
- Other design tools
- AI image generation (NanoBanana/Eira)

### Multi-Language Support

**Product Languages:**
- Single language (specify)
- Multi-language (list languages)

**Design Implications:**
- Text expansion considerations
- RTL language support needed
- Cultural adaptation requirements

### Integration with WDS Workflow

Design work flows through these phases:

1. **Product Exploration** → `A-Product-Brief/` - Strategic foundation
2. **User Research** → `B-Trigger-Map/` - User psychology mapping
3. **Platform Requirements** → `D-PRD/` - Technical requirements (optional)
4. **UX Design** → `C-Scenarios/` - HOW it works
5. **Visual Design** → `D-Design-System/` - HOW it looks (can start anytime)
6. **Dev Integration** → `E-UI-Roadmap/` - Development handoff

### Design Experience Level

**Your Design Experience:**
- **Beginner** - New to UX design, need detailed guidance
- **Intermediate** - Familiar with design concepts
- **Expert** - Experienced designer, prefer efficient approach

This helps WDS agents (Saga, Idunn, Freya, Mimir) tailor their communication style.

### Handoff to Development

**Integration with BMM:**

If using BMad Method (BMM) for development:
1. Complete WDS through Phase 6 (UI Roadmap)
2. Design deliverables feed into BMM Architecture
3. Component specs guide BMM story implementation
4. Design system becomes development foundation

**Standalone Design:**

If design-only project:
- Focus on deliverables in `docs/` folder
- Export Figma prototypes
- Document component specifications
- Provide developer-ready handoff package

### Project Constraints

**Timeline Considerations:**
- Quick prototype needed
- Full design process
- Design system priority

**Resource Considerations:**
- Solo designer
- Design team collaboration
- Developer collaboration needed

**Technical Constraints:**
- Platform requirements (web, mobile, etc.)
- Accessibility requirements
- Performance requirements
- Browser/device support

---

## Using This Template

**For Brainstorming:**
Saga agent uses this template to guide product discovery conversations, ensuring strategic design thinking from the start.

**For Project Setup:**
Workflow-init uses these considerations to configure WDS for your specific project type and constraints.

**For Agent Context:**
All WDS agents reference this context to understand:
- What type of design work is needed
- What level of detail to provide
- What tools and integrations to suggest
- How to structure deliverables

---

## WDS Philosophy

Remember the core WDS principles:

1. **Strategic Design** - Every design decision connects to business goals and user psychology
2. **Phase Independence** - Visual design (brand) can start anytime, not tied to product timeline
3. **Complete Specifications** - Developer-ready deliverables with all details defined
4. **Tool Agnostic** - Methodology over tools (but integrations available)
5. **Adaptive Workflow** - Choose phases based on project needs

---

*This template is filled out during WDS project initialization and referenced throughout the design process.*
