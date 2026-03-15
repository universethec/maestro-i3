# Common Skill Flows

These are universal flow templates that adapt to whatever skills are installed. When composing a flow, substitute the actual skill names from the user's environment.

## Build a Feature (Full)

**When:** Building a significant new feature that needs to be done right.

```
Step 1: [brainstorming/ideation skill]
  -> Produces: Refined requirements, design decisions, approved direction

Step 2: [planning skill]
  -> Produces: Task-by-task plan with file paths and verification steps

Step 3: [git isolation skill] (if available)
  -> Produces: Isolated branch ready for development

Step 4: [TDD skill] (if available)
  -> Produces: Tests written BEFORE implementation

Step 5: [execution skill]
  -> Produces: Implemented code matching the plan

Step 6: [verification skill] (if available)
  -> Produces: Evidence that everything actually works

Step 7: [code review skill]
  -> Produces: Review feedback

Step 8: [branch completion skill] (if available)
  -> Produces: Merged code or PR
```

**Principle:** Earlier steps prevent costly mistakes in later steps. Skip steps only if the corresponding skill isn't installed or the task is small enough to not need it.

---

## Build a Feature (Quick)

**When:** Smaller feature, less ceremony needed.

```
Step 1: [brainstorming skill] (if available)
  -> Produces: Clear understanding of what to build

Step 2: [planning skill] (if available)
  -> Produces: Simple task list

Step 3: Build it directly
  -> Produces: Working implementation

Step 4: [commit skill] (if available)
  -> Produces: Clean commit
```

---

## Build a UI/Frontend

**When:** Creating user interfaces, landing pages, web apps.

```
Step 1: [UI/UX design intelligence skill] (if available)
  -> Produces: Design decisions — style, colors, fonts, layout patterns

Step 2: [frontend/design skill]
  -> Produces: Polished code implementing those design decisions

Step 3: [browser testing MCP] (if available)
  -> Produces: Visual verification in a real browser

Step 4: [design tool MCP] (if available)
  -> Produces: Design documented for future reference
```

**Principle:** Design intelligence first (WHAT to build), then creative implementation (HOW to build it), then verification (DID it work).

---

## Research Before Building

**When:** You need to understand the landscape before committing to an approach.

```
Step 1: [factual research skill] (if available)
  -> Produces: Cited research on technologies, approaches, trade-offs

Step 2: [human sentiment research skill] (if available)
  -> Produces: What real users think — complaints, desires, language

Step 3: [knowledge management MCP] (if available)
  -> Produces: Organized research you can query later

Step 4: [brainstorming skill]
  -> Produces: Design decisions informed by research

Step 5: [planning skill]
  -> Produces: Implementation plan grounded in evidence
```

---

## Validate a Business Idea

**When:** You have a startup/product idea and want to validate it before building.

```
Step 1: [human sentiment research skill]
  -> Produces: Real human evidence — are people actually complaining about this problem?

Step 2: [factual research skill]
  -> Produces: Competitive landscape, existing solutions, market size

Step 3: [business model skill] (if available)
  -> Produces: Business Model Canvas with validated assumptions

Step 4: [ideation skill]
  -> Produces: Alternative approaches and differentiators
```

---

## Debug a Problem

**When:** Something is broken and you need to find the root cause.

```
Step 1: [debugging skill]
  -> Produces: Root cause analysis through structured investigation

Step 2: [TDD skill] (if available)
  -> Produces: Test that reproduces the bug, then fix

Step 3: [verification skill] (if available)
  -> Produces: Proof the fix works and doesn't break anything else
```

---

## Code Review Pipeline

**When:** You want thorough review before merging.

```
Step 1: [verification skill] (if available)
  -> Produces: Evidence everything works

Step 2: [code review skill — lightest available]
  -> Produces: Review against spec

Step 3: [code review skill — deepest available] (if different from above)
  -> Produces: Multi-dimensional quality analysis

Step 4: [branch completion skill] (if available)
  -> Produces: Merged or PR'd
```

**Principle:** Increasing depth of review. Fix obvious issues before asking for deep analysis.

---

## Solve an Innovation Challenge

**When:** Facing a technical trade-off or need creative solutions.

```
Step 1: [innovation/contradiction skill] (if available)
  -> Produces: Systematic analysis and solution concepts

Step 2: [creative ideation skill]
  -> Produces: Additional solutions from different methodologies

Step 3: [brainstorming skill]
  -> Produces: Refined solution ready for implementation

Step 4: [planning skill]
  -> Produces: Implementation plan for chosen solution
```

---

## Write and Ship Content

**When:** Creating written content that shouldn't sound AI-generated.

```
Step 1: [research skill] (if topic needs research)
  -> Produces: Factual foundation

Step 2: Write the content
  -> Produces: Draft

Step 3: [humanizer/writing polish skill] (if available)
  -> Produces: Text that reads naturally
```

---

## Start a New Project

**When:** Starting a multi-phase project from scratch.

```
Step 1: [project initialization skill]
  -> Produces: Project definition, research, roadmap

Step 2: [phase planning skill]
  -> Produces: Detailed plan for Phase 1

Step 3: [phase execution skill]
  -> Produces: Completed Phase 1

Step 4: [verification skill]
  -> Produces: Validated work

Step 5: [progress tracking skill]
  -> Produces: Status check, routes to next phase
```

---

## Custom Flow Composition

Not every task fits a template. When composing custom flows, follow this universal ordering:

1. **Research** (understand the landscape)
2. **Ideate** (explore options)
3. **Decide** (pick an approach)
4. **Plan** (break it down)
5. **Isolate** (create safe workspace)
6. **Test** (write tests first)
7. **Build** (implement)
8. **Verify** (prove it works)
9. **Review** (quality check)
10. **Ship** (merge/deploy)
11. **Document** (capture learnings)

Not every flow needs every step. The key insight: earlier steps prevent costly mistakes in later steps. Only include steps where you have a skill that adds genuine value.
