# B2B SaaS AI Agents

**Inspired by:** [mgalpert's](https://github.com/contains-studio/agents/commits?author=mgalpert) [contains-studio/agents](https://github.com/contains-studio/agents)

A comprehensive collection of specialized AI agents designed for B2B SaaS development and enterprise operations. Each agent is an expert in their domain, optimized for business-to-business software development, ready to be invoked when their expertise is needed.

Use it to expand your capabilities. Install, and remove the agents your workflow does not require to avoid unecessary loops. Grow the operations according with your needs. Conquer and thank GALO for allowing this to exist. 

## 📥 Installation

1. **Download this repository:**
   ```bash
   git clone https://github.com/alyssonfranklin/b2b-agents.git
   ```

2. **Select the agents that makes sense to your workflow:**
Remove the ones that doesn't make sense to your workflow, avoiding **Agent Overload** and **decision paralysis**. If you don't need an agent, **REMOVE IT**. Jumping between different agent perspectives could slow you down

3. **Customization Effort:** 
Read the code. Understand the gig. You may need to modify prompts for your specific use cases. Reshape. Remix.


4. **Copy to your Claude Code agents directory:**
   ```bash
   cp -r agents/* ~/.claude/agents/
   ```
   
   Or manually copy all the agent files to your `~/.claude/agents/` directory.

5. **Restart Claude Code** to load the new agents and start working!

All Agents are automatically available in Claude Code. Simply describe your task and the appropriate agent will be triggered. You can also explicitly request an agent by mentioning their name.

**Learn more:** [Claude Code Sub-Agents Documentation](https://docs.anthropic.com/en/docs/claude-code/sub-agents)

### Example Usage
- "Create a B2B customer onboarding flow" → `b2b-onboarding-optimizer`
- "Review our API security for enterprise compliance" → `enterprise-security-reviewer`
- "Help integrate Stripe for B2B subscriptions" → `api-integration-specialist`
- "Design an enterprise dashboard interface" → `ui-designer`

## Directory Structure

Agents are organized by department for easy discovery:

```
b2b-saas-agents/
├── design/
│   ├── brand-guardian.md
│   ├── ui-designer.md
│   ├── ux-researcher.md
│   ├── visual-storyteller.md
│   └── whimsy-injector.md
├── engineering/
│   ├── accessibility-expert.md
│   ├── ai-engineer.md
│   ├── backend-architect.md
│   ├── devops-automator.md
│   ├── enterprise-security-reviewer.md 
│   ├── frontend-developer.md
│   ├── mobile-app-builder.md
│   ├── rapid-prototyper.md
│   └── test-writer-fixer.md
├── marketing/
│   ├── app-store-optimizer.md
│   ├── b2b-linkedin-content-curator.md 
│   ├── b2b-video-strategist.md  
│   ├── content-creator.md
│   ├── growth-hacker.md
│   ├── reddit-community-builder.md
│   └── twitter-engager.md
├── product/
│   ├── api-integration-specialist.md  
│   ├── b2b-onboarding-optimizer.md 
│   ├── feedback-synthesizer.md
│   ├── sprint-prioritizer.md
│   └── trend-researcher.md
├── project-management/
│   ├── experiment-tracker.md
│   ├── project-shipper.md
│   └── studio-producer.md
├── studio-operations/
│   ├── analytics-reporter.md
│   ├── finance-tracker.md
│   ├── infrastructure-maintainer.md
│   ├── legal-compliance-checker.md
│   └── support-responder.md
├── testing/
│   ├── api-tester.md
│   ├── performance-benchmarker.md
│   ├── test-results-analyzer.md
│   ├── tool-evaluator.md
│   └── workflow-optimizer.md
└── bonus/
    ├── joker.md
    └── studio-coach.md
```

## Complete Agent List

### Engineering Department (`engineering/`)
- **accessibility-expert** - WCAG 2.1 AAA compliance automation with real-time monitoring, with coverage for US Federal and State Laws, including Brazilian #a11y rules. 
- **ai-engineer** - Integrate AI/ML features for B2B enterprise solutions
- **backend-architect** - Design scalable B2B APIs and multi-tenant systems
- **devops-automator** - Deploy enterprise-grade B2B applications continuously
- **enterprise-security-reviewer** - Review B2B security, SOC 2, GDPR compliance
- **frontend-developer** - Build enterprise-grade B2B user interfaces
- **mobile-app-builder** - Create B2B mobile experiences and admin apps
- **rapid-prototyper** - Build B2B MVPs and enterprise features quickly
- **test-writer-fixer** - Write enterprise-quality tests for B2B systems

### Product Department (`product/`)
- **api-integration-specialist** - Handle enterprise API integrations and third-party connections
- **b2b-onboarding-optimizer** - Optimize enterprise customer onboarding flows
- **feedback-synthesizer** - Transform B2B customer complaints into enterprise features
- **sprint-prioritizer** - Ship maximum B2B value in 6-day sprints
- **trend-researcher** - Identify B2B market opportunities and enterprise trends

### Marketing Department (`marketing/`)
- **app-store-optimizer** - Optimize B2B SaaS app store presence
- **b2b-linkedin-content-curator** - Master B2B LinkedIn content and professional networking
- **b2b-video-strategist** - Create professional B2B video content and webinar strategies
- **content-creator** - Generate B2B content across professional platforms
- **growth-hacker** - Find and exploit B2B viral growth loops and enterprise adoption
- **reddit-community-builder** - Build B2B communities and professional discussions
- **twitter-engager** - Engage B2B audiences and thought leadership on Twitter

### Design Department (`design/`)
- **brand-guardian** - Keep B2B brand identity consistent across enterprise touchpoints
- **ui-designer** - Design enterprise-grade B2B interfaces developers can build
- **ux-researcher** - Turn enterprise user insights into B2B product improvements
- **visual-storyteller** - Create B2B visuals that convert enterprise customers
- **whimsy-injector** - Add professional delight to B2B interactions

### Project Management (`project-management/`)
- **experiment-tracker** - Data-driven B2B feature validation and A/B testing
- **project-shipper** - Launch B2B products and enterprise features reliably
- **studio-producer** - Keep B2B development teams shipping, not meeting

### Studio Operations (`studio-operations/`)
- **analytics-reporter** - Turn B2B usage data into actionable enterprise insights
- **finance-tracker** - Keep the B2B SaaS business profitable and track MRR
- **infrastructure-maintainer** - Scale B2B infrastructure without breaking the budget
- **legal-compliance-checker** - Stay compliant with enterprise legal requirements
- **support-responder** - Turn frustrated B2B customers into advocates

### Testing & Benchmarking (`testing/`)
- **api-tester** - Ensure B2B APIs work under enterprise load and pressure
- **performance-benchmarker** - Make B2B applications faster for enterprise users
- **test-results-analyzer** - Find patterns in B2B system test failures
- **tool-evaluator** - Choose B2B development tools that actually help
- **workflow-optimizer** - Eliminate B2B development workflow bottlenecks

## Bonus Agents
- **studio-coach** - Rally the B2B development team to excellence
- **joker** - Lighten the mood with professional tech humor

## Proactive Agents

Some agents trigger automatically in specific B2B contexts:
- **studio-coach** - When complex B2B multi-agent tasks begin or agents need guidance
- **test-writer-fixer** - After implementing B2B features, fixing enterprise bugs, or modifying code
- **whimsy-injector** - After B2B UI/UX changes to add professional delight
- **experiment-tracker** - When B2B feature flags or A/B tests are added
- **enterprise-security-reviewer** - When authentication, authorization, or compliance code changes

## 🏢 Custom B2B Agents

Specialized agents were created specifically for B2B scenarios:

### **b2b-onboarding-optimizer** (`product/`)
Specializes in multi-step company setup flows, user activation, and reducing time-to-value for enterprise customers. Focuses on B2B SaaS onboarding best practices, user journey optimization, and conversion funnel analysis.

### **enterprise-security-reviewer** (`engineering/`)
Expert in SOC 2, GDPR, multi-tenant security, authentication systems, authorization models, API security, and data encryption for B2B applications. Ensures enterprise-grade security compliance.

### **api-integration-specialist** (`product/`)
Handles enterprise API integrations, third-party connections, webhook systems, Stripe subscriptions, payment processing, and external service integrations for B2B platforms.

## 💡 Best Practices for B2B Development

1. **Let agents work together** - B2B tasks often benefit from multiple agents (e.g., security + backend + frontend)
2. **Be specific about enterprise requirements** - Clear B2B task descriptions help agents perform better
3. **Trust the B2B expertise** - Agents are designed for enterprise and business contexts
4. **Iterate quickly for business value** - Agents support rapid B2B feature delivery and enterprise needs

## 🔧 Technical Details

### Agent Structure
Each agent includes:
- **name**: Unique identifier
- **description**: When to use the agent with examples
- **color**: Visual identification
- **tools**: Specific tools the agent can access
- **System prompt**: Detailed expertise and instructions

### Adding New Agents
1. Create a new `.md` file in the appropriate department folder
2. Follow the existing format with YAML frontmatter
3. Include 3-4 detailed usage examples. The more, the better.
4. Write comprehensive system prompt (500+ words)
5. Test the agent with real tasks

## Agent Performance

Track agent effectiveness through:
- Task completion time
- User satisfaction
- Error rates
- Feature adoption
- Development velocity

### Agent Customization Todo List

Use this checklist when creating or modifying agents for your specific needs:

#### Required Components
- [ ] **YAML Frontmatter**
  - [ ] `name`: Unique agent identifier (kebab-case)
  - [ ] `description`: When to use + 3-4 detailed examples with context/commentary
  - [ ] `color`: Visual identification (e.g., blue, green, purple, indigo)
  - [ ] `tools`: Specific tools the agent can access (Write, Read, MultiEdit, Bash, etc.)

#### System Prompt Requirements (500+ words)
- [ ] **Agent Identity**: Clear role definition and expertise area
- [ ] **Core Responsibilities**: 5-8 specific primary duties
- [ ] **Domain Expertise**: Technical skills and knowledge areas
- [ ] **Studio Integration**: How agent fits into 6-day sprint workflow
- [ ] **Best Practices**: Specific methodologies and approaches
- [ ] **Constraints**: What the agent should/shouldn't do
- [ ] **Success Metrics**: How to measure agent effectiveness

#### Required Examples by Agent Type

**Engineering Agents** need examples for:
- [ ] Feature implementation requests
- [ ] Bug fixing scenarios
- [ ] Code refactoring tasks
- [ ] Architecture decisions

**Design Agents** need examples for:
- [ ] New UI component creation
- [ ] Design system work
- [ ] User experience problems
- [ ] Visual identity tasks

**Marketing Agents** need examples for:
- [ ] Campaign creation requests
- [ ] Platform-specific content needs
- [ ] Growth opportunity identification
- [ ] Brand positioning tasks

**Product Agents** need examples for:
- [ ] Feature prioritization decisions
- [ ] User feedback analysis
- [ ] Market research requests
- [ ] Strategic planning needs

**Operations Agents** need examples for:
- [ ] Process optimization
- [ ] Tool evaluation
- [ ] Resource management
- [ ] Performance analysis

#### Testing & Validation Checklist
- [ ] **Trigger Testing**: Agent activates correctly for intended use cases
- [ ] **Tool Access**: Agent can use all specified tools properly
- [ ] **Output Quality**: Responses are helpful and actionable
- [ ] **Edge Cases**: Agent handles unexpected or complex scenarios
- [ ] **Integration**: Works well with other agents in multi-agent workflows
- [ ] **Performance**: Completes tasks within reasonable timeframes
- [ ] **Documentation**: Examples accurately reflect real usage patterns

#### Agent File Structure Template

```markdown
---
name: your-agent-name
description: Use this agent when [scenario]. This agent specializes in [expertise]. Examples:\n\n<example>\nContext: [situation]\nuser: "[user request]"\nassistant: "[response approach]"\n<commentary>\n[why this example matters]\n</commentary>\n</example>\n\n[3 more examples...]
color: agent-color
tools: Tool1, Tool2, Tool3
---

You are a [role] who [primary function]. Your expertise spans [domains]. You understand that in 6-day sprints, [sprint constraint], so you [approach].

Your primary responsibilities:
1. [Responsibility 1]
2. [Responsibility 2]
...

[Detailed system prompt content...]

Your goal is to [ultimate objective]. You [key behavior traits]. Remember: [key philosophy for 6-day sprints].
```

#### Department-Specific Guidelines

**Engineering** (`engineering/`): Focus on implementation speed, code quality, testing
**Design** (`design/`): Emphasize user experience, visual consistency, rapid iteration  
**Marketing** (`marketing/`): Target viral potential, platform expertise, growth metrics
**Product** (`product/`): Prioritize user value, data-driven decisions, market fit
**Operations** (`studio-operations/`): Optimize processes, reduce friction, scale systems
**Testing** (`testing/`): Ensure quality, find bottlenecks, validate performance
**Project Management** (`project-management/`): Coordinate teams, ship on time, manage scope

#### Customizations

Modify these elements for your needs:
- [ ] Adjust examples to reflect your product types
- [ ] Add specific tools agents have access to
- [ ] Modify success metrics for your KPIs
- [ ] Update department structure if needed
- [ ] Customize agent colors for your brand

## Contributing

To improve existing agents or suggest new ones:
1. Use the customization checklist above
2. Test thoroughly with real projects
3. Document performance improvements
4. Share successful patterns with the community
