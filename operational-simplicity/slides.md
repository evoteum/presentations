---
marp: true
math: mathjax
theme: rose-pine
---

<style lang=css>
/*
Rosé Pine theme create by RAINBOWFLESH
> www.rosepinetheme.com

palette in :root
*/

@import "default";
@import "schema";
@import "structure";

:root {
  --base: #232136;
    --surface: #2a273f;
    --overlay: #393552;
    --muted: #6e6a86;
    --subtle: #908caa;
    --text: #e0def4;
    --love: #eb6f92;
    --gold: #f6c177;
    --rose: #ea9a97;
    --pine: #3e8fb0;
    --foam: #9ccfd8;
    --iris: #c4a7e7;
    --highlight-low: #2a283e;
    --highlight-muted: #44415a;
    --highlight-high: #56526e;

  font-family: Pier Sans, ui-sans-serif, system-ui, -apple-system,
    BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, Noto Sans,
    sans-serif, "Apple Color Emoji", "Segoe UI Emoji", Segoe UI Symbol,
    "Noto Color Emoji";
  font-weight: initial;

  background-color: var(--base);
}
/*Common style*/
h1 {
  color: var(--rose);
  padding-bottom: 2mm;
  margin-bottom: 12mm;
}
h2 {
  color: var(--rose);
}
h3 {
  color: var(--rose);
}
h4 {
  color: var(--rose);
}
h5 {
  color: var(--rose);
}
h6 {
  color: var(--rose);
}
a {
  color: var(--iris);
}
p {
  font-size: 20pt;
  font-weight: 600;
  color: var(--text);
}
code {
  color: var(--text);
  background-color: var(--highlight-muted);
}
text {
  color: var(--text);
}
ul {
  color: var(--subtle);
}
li {
  color: var(--subtle);
}
img {
  background-color: var(--highlight-low);
}
strong {
  color: var(--text);
  font-weight: inherit;
  font-weight: 800;
}
mjx-container {
  color: var(--text);
}
marp-pre {
  background-color: var(--overlay);
  border-color: var(--highlight-high);
}

/*Code blok*/
.hljs-comment {
  color: var(--muted);
}
.hljs-attr {
  color: var(--foam);
}
.hljs-punctuation {
  color: var(--subtle);
}
.hljs-string {
  color: var(--gold);
}
.hljs-title {
  color: var(--foam);
}
.hljs-keyword {
  color: var(--pine);
}
.hljs-variable {
  color: var(--text);
}
.hljs-literal {
  color: var(--rose);
}
.hljs-type {
  color: var(--love);
}
.hljs-number {
  color: var(--gold);
}
.hljs-built_in {
  color: var(--love);
}
.hljs-params {
  color: var(--iris);
}
.hljs-symbol {
  color: var(--foam);
}
.hljs-meta {
  color: var(--subtle);
}

</style>




# Operational Simplicity
## Engineering Systems That Scale

### Technical Clarity
### Operational Simplicity
### Organisational Leverage

---

# My Core Philosophy

## Infrastructure should create leverage

A strong platform improves:
- engineering velocity
- reliability
- onboarding
- retention
- operational resilience
- delivery confidence

---

Infrastructure is not:
> merely a hosting layer

It is:
> organisational enablement infrastructure

---

# Engineering Leverage
## Great engineering multiplies capability

Not:
- owning the most systems
- gatekeeping architecture
- being the hero engineer
---
But:
- reducing friction at scale
- improving organisational throughput
- enabling other engineers
- simplifying complexity
- aligning technical decisions with business outcomes

---

# What Large Organisations Struggle With

## Common scaling problems

As organisations grow:
- workflows diverge
- tooling fragments
- operational variance increases
- onboarding slows
- delivery confidence drops
- cloud entropy accumulates
---
The result:
- operational drag
- hidden complexity
- inconsistent engineering experience

---

# My Role

## Build systems that become delightfully boring

The strongest systems are:
- predictable
- understandable
- observable
- operable
- standardised

Goal:
> reduce operational surprises

---

# Complexity Is An Operational Risk

## Always ask:
> “Do we actually need this?”

Every unnecessary:
- abstraction
- bespoke workflow
- custom deployment path
- special case
- exception
---
creates:
- operational overhead
- onboarding cost
- support burden
- delivery friction
- increased failure modes

---

# Strong Opinions, Loosely Held

## Engineering requires feedback loops

I value:
- evidence over ego
- measurable outcomes
- experimentation with guardrails
- iterative improvement

My cybernetics background taught me:
> systems improve through feedback

---

# Solving The Right Problem

## Start with outcomes, not implementations

Avoid:
- solutioneering
- architectural drift
- accidental complexity
---
Instead ask:
> “What are we trying to achieve?”

This avoids:
- duplicated systems
- unnecessary divergence
- fragmented workflows

---

# Enterprise Platform Thinking

## Standardisation enables scale

Consistency improves:
- onboarding
- automation
- governance
- observability
- operational recovery
- delivery confidence
---
Predictable systems are:
> easier to operate safely at scale

---

# Real Example

## Simplifying fragmented delivery workflows

Inherited:
- multiple Git workflows
- environment-specific trunks
- inconsistent branch naming
- bespoke Jenkins logic
---
Migrated to:
- GitHub Flow
- standardised workflows
- simplified pipelines

Result:
- reduced operational variance
- simpler automation
- lower support burden
- improved onboarding
- clearer delivery process

---

# Migration Philosophy

## Migration alone is not transformation

Moving workloads to AWS is not enough.

The goal is:
- improved operability
- standardised delivery
- reduced variance
- safer deployments
- improved observability
- consistent governance
---
Avoid:
> cloud-shaped legacy systems

---

# Cloud Modernisation

## Migration is an opportunity to simplify

Modernisation should:
- reduce operational complexity
- align teams around shared patterns
- standardise infrastructure
- improve deployment confidence
- reduce bespoke operational knowledge

Goal:
> converging toward consistent operational models

---

# Reference Architectures

## Opinionated platforms reduce decision fatigue

Good platform standards:
- reduce ambiguity
- accelerate onboarding
- improve consistency
- simplify governance
- reduce cognitive load

Strong reference architectures are:
> opinionated but evolvable

---

# Platform Engineering

## Platform teams should enable delivery

The platform exists to:
- absorb operational complexity
- provide safe paved roads
- improve developer effectiveness
- reduce cognitive overhead
- increase organisational throughput

Good platforms:
> make the correct path the easiest path

---

# Internal Platforms As Products

## Adoption is the real KPI

Questions that matter:
- are teams using the platform?
- has delivery improved?
- are workflows becoming simpler?
- are teams bypassing standard paths?

If engineers avoid the platform:
> the platform is failing

---

# Developer Experience

## DevEx directly affects business outcomes

Good developer experience improves:
- velocity
- onboarding
- retention
- deployment confidence
- operational consistency
- engineering morale
---
Developer friction becomes:
> organisational inefficiency

---

# Everyone Is My Customer

## Service mindset matters

I learned early:
- reduce friction
- facilitate success
- remove unnecessary effort
---
Today that means:
- enabling self-service
- simplifying workflows
- improving discoverability
- reducing cognitive load

---

# Self-Service Infrastructure

## Self-service must be safe and predictable

Self-service succeeds when:
- workflows are standardised
- guardrails are automated
- patterns are reusable
- governance is embedded
- operational complexity is hidden appropriately

Goal:
> autonomy without chaos

---

# Governance

## Governance should enable delivery safely

I prefer:
- policy-as-code
- preventive controls
- low-friction governance
- automated guardrails
- drift correction

Goal:
> embed governance into delivery workflows

---

# Security Philosophy

## Make secure behaviour the default behaviour

Experience:
- OPA
- Kyverno
- least privilege
- infrastructure policy enforcement
- immutable and mutable infrastructure approaches

Outcome:
> reduce insecure states from existing at all

---

# Drift Management

## Desired state should remain true

Focus:
- infrastructure consistency
- compliance continuity
- automated remediation
- reducing configuration drift

Goal:
> security and governance remain continuously enforced

---

# Build vs Buy

## Avoid reinventing solved problems

Prefer:
- proven ecosystems
- operationally mature tooling
- widely adopted standards
---
Evaluate:
- operational burden
- opportunity cost
- maintenance cost
- staffing impact
- long-term ownership

---

# Buy vs Build Framework

## Optimise for long-term sustainability

Questions:
- does this reduce operational burden?
- does this improve delivery?
- does this simplify support?
- does this create unnecessary ownership cost?

Use ADRs to:
> make trade-offs explicit and reviewable

---

# Cloud Cost Philosophy

## Optimise systems, not spreadsheets

Cloud cost matters.

But:
> engineer time also has economic value

Poor tooling and fragmented workflows create:
- hidden productivity loss
- slower delivery
- operational drag
- reduced morale

---

# Cost Example

## Cheap decisions can become expensive

Example:
- underpowered developer hardware reduced productivity significantly

The spreadsheet showed:
- lower equipment cost

Reality:
- substantial hidden productivity loss

Optimisation must consider:
> total organisational efficiency

---

# Premature Optimisation

## Optimise when operational signals justify it

Avoid:
- speculative architecture
- imaginary scaling problems
- unnecessary complexity

Prefer:
- measurable bottlenecks
- evidence-driven optimisation
- iterative improvement

---

# Observability

## Observability exists to support decisions

The goal is not:
- dashboards for their own sake

The goal is:
- operational clarity
- faster diagnosis
- deployment visibility
- reduced MTTR
- delivery confidence
---
Experience:
- LGTM stack
- Prometheus
- Grafana
- Loki
- Tempo

---

# Metrics That Matter

## Measure outcomes, not activity

Important metrics:
- Lead Time for Changes
- deployment frequency
- MTTR
- change failure rate
- platform adoption

My key question:
> how quickly and safely can teams deliver change?

---

# Reliability Engineering

## Reliability is engineered intentionally

Strong reliability comes from:
- deployment testing
- observability
- standardisation
- operational learning
- automation
- consistent workflows
---
Not:
- heroics
- tribal knowledge
- firefighting culture

---

# Preventable Incidents

## The worst incidents are known problems left unresolved

Example:
- lengthy outage caused by a preventable deployment issue
- mitigation already understood
- preventative testing deprioritised

Lesson:
> root cause analysis only matters if findings are implemented

---

# Hero Culture

## Heroics create organisational fragility

Systems dependent on individuals create:
- bottlenecks
- burnout
- hidden knowledge
- scaling constraints
- operational risk

Goal:
> systems should scale beyond individuals

---

# Leadership Philosophy

## Lead from the front

I value:
- empathy
- shared ownership
- psychological safety
- collaborative problem solving
- mentorship
- operational accountability
---
I will never ask engineers to do:
> what I would not do myself

---

# Psychological Safety

## Strong engineering cultures outperform fearful ones

Healthy teams:
- ask questions safely
- share knowledge openly
- collaborate effectively
- improve continuously
- learn from failure
---
Psychological safety improves:
- reliability
- retention
- onboarding
- operational resilience

---

# Mentorship

## Leadership means creating capability around you

My goal is not:
- to remain indispensable

My goal is:
- to increase capability across the organisation

Success:
> the engineers around me become stronger over time

---

# Ownership

## Ownership is accountability, not territorialism

Ownership means:
- driving problems to resolution
- reducing ambiguity
- improving systems
- helping teams succeed
---
Not:
- gatekeeping
- blame shifting
- knowledge hoarding

---

# Working With Ambiguity

## Ambiguity is normal in large organisations

Approach:
- define what we can
- gather feedback
- experiment safely
- iterate intelligently
---
Strong systems evolve through:
- observation
- learning
- adaptation

---

# Organisational Leverage

## Focus on high-impact friction

The highest-value platform work often solves:
- repeated engineering pain
- onboarding friction
- delivery bottlenecks
- operational inconsistency
- workflow fragmentation

Fixing one painful workflow can:
> improve productivity across dozens of teams

---

# Change Management

## Adoption matters more than enforcement

Platform transformation succeeds when:
- teams understand the value
- workflows genuinely improve
- friction decreases
- migration paths are clear
- enablement is collaborative

Goal:
> drive adoption through enablement, not mandates

---

# My View Of Quality Engineering

## Create clarity and leverage

The role is to:
- identify the real problem
- simplify systems
- reduce organisational friction
- improve engineering effectiveness
- align technical strategy with operational reality

---

# Closing Philosophy

## Simplicity leads to maintainability
## Maintainability leads to reliability

The strongest engineering systems are:
- boring
- predictable
- scalable
- observable
- understandable
- operable
---
Goal:
> help engineering organisations move quickly, safely, and sustainably

---

# Thanks

For some of my key projects, take a look at my [portfolio](https://jamesgeddes.pro/portfolio).