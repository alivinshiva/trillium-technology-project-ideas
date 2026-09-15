# Two Technology Project Proposals for Trillium Flow Technologies

## Strategic Context

As of September 2026, Trillium is becoming more pump-focused following the sale of its valves businesses. At the same time, it is investing in:

- Cyclops² cloud-based pump condition monitoring.
- AI and reduced-order models for faster centrifugal-pump simulation.
- High-efficiency pumps for water infrastructure and data-centre cooling.
- Faster engineering and quotation turnaround.

Competitors currently provide capabilities that Trillium does not publicly present as complete offerings:

- KSB Guard combines monitoring with maintenance workflows, engineer recommendations, and a standardized REST API. [KSB Guard](https://www.ksb.com/en-ch/guard), [KSB data interface](https://www.ksb.com/en-ch/guard/ksb-guard-data-interface)
- Sulzer BLUE BOX quantifies reliability, energy, carbon, and operating-cost opportunities. [Sulzer BLUE BOX](https://www.sulzer.com/en/shared/services/blue-box)
- Flowserve, KSB, and Sulzer provide mature digital pump-selection tools. [Flowserve Affinity](https://www.flowserve.com/support/tools/online-tools/affinity-pump-selection-tool/), [KSB EasySelect](https://www.ksb.com/en-fi/software-and-know-how/configuration-tools/ksb-easyselect), [Sulzer selection tools](https://www.sulzer.com/en/services/selection-tools)

These create two practical opportunities.

## Idea 1 — PumpCare 360: Closed-Loop Pump Maintenance Platform

### Proposal

Extend Cyclops² from a monitoring dashboard into a complete customer-facing maintenance and aftermarket-service platform.

Cyclops² already collects pump condition data and provides cloud analytics. [Trillium Smart Condition Monitoring](https://www.trilliumflow.com/products/smart-condition-monitoring/) The missing publicly visible layer is converting an alert into an explainable recommendation, maintenance action, service request, and measurable business outcome.

### MVP capabilities

- Unified pump health dashboard with health score, operating state, trends, and prioritized anomalies.
- Explain each alert using supporting measurements such as vibration, temperature, pressure, flow, and operating-curve deviation.
- Recommend an engineer-approved next action and urgency level.
- Convert recommendations into maintenance tasks or Trillium service requests.
- Integrate with customer systems such as SAP PM or IBM Maximo through REST APIs and webhooks.
- Provide an asset QR code containing manuals, pump curve, service history, spare-parts information, and active alerts.
- Calculate estimated downtime risk, inefficient energy consumption, operating cost, and carbon impact.
- Support Trillium and selected third-party pumps to increase the addressable installed base.

### Competitive gap filled

KSB already exposes monitoring data and recommended actions through an API, while Sulzer provides energy, carbon, lifetime, and expert-supported insights. PumpCare 360 would close this gap while differentiating Trillium through a direct connection between pump intelligence and its engineering, spare-parts, and field-service teams.

### Business value

- Creates recurring digital-service revenue.
- Generates qualified aftermarket and spare-parts opportunities.
- Makes Cyclops² harder for customers to replace.
- Reduces the time between detecting a problem and beginning corrective action.
- Builds an operating-data foundation that can improve future pump designs.

### Pilot and success measures

Pilot with 20–50 pumps at one water, industrial, or data-centre cooling customer.

Measure:

- Alert-to-action time.
- Percentage of actionable versus false alerts.
- Number of failures or emergency interventions avoided.
- Energy-saving opportunities identified.
- Maintenance recommendations accepted.
- Service requests and aftermarket revenue generated.

### Short pitch

> Cyclops² currently helps customers see pump problems. PumpCare 360 will help them resolve those problems. It will turn condition data into explainable recommendations, maintenance workflows, and Trillium service opportunities—creating measurable customer savings and recurring aftermarket revenue.

## Idea 2 — RapidDesign: AI-Assisted Pump Design-to-Quote Workbench

### Proposal

Productize Trillium’s existing AI pump-simulation research into a governed internal application that takes engineers from customer requirements to a validated technical proposal.

Trillium and Politecnico di Milano have already developed surrogate models that reconstruct pump flow and pressure fields much faster than traditional CFD. The newer PIAI4PUMPS-GEO phase extends this work to pump geometry. [AIRIC project](https://airic.polimi.it/it/projects/trillium/), [PIAI4PUMPS-GEO update](https://www.linkedin.com/posts/massimilianoborghetti_pleased-to-begin-the-second-step-of-the-activity-7459716033218646016-OX1p)

RapidDesign would not duplicate that research. It would turn the models into a usable, traceable engineering workflow.

### MVP capabilities

- Structured requirement intake: flow, head, fluid, temperature, NPSH, speed, materials, applicable standards, and operating range.
- Search existing pump families, curves, prior designs, and approved configurations.
- Use the AI surrogate model to evaluate and rank design scenarios in seconds.
- Display pump/system curves, efficiency, best-efficiency-point distance, NPSH margin, and model confidence.
- Send only the strongest candidates for conventional CFD and engineering validation.
- Generate a controlled proposal pack containing assumptions, selected configuration, curves, exceptions, and approval history.
- Maintain complete model-version and engineer-approval audit trails.
- Keep final design acceptance with qualified pump engineers.

### Competitive gap filled

Flowserve Affinity, KSB EasySelect, and Sulzer Select already accelerate pump selection and document generation. Trillium publicly emphasizes customized engineering and 24-hour quotation for data-centre cooling pumps, but does not show a comparable integrated selection platform. [Trillium data-centre cooling pumps](https://www.trilliumflow.com/data-center-cooling-pumps/)

RapidDesign would combine Trillium’s differentiator—custom engineering—with competitor-level software speed.

### Business value

- Reduces quotation and design-cycle time.
- Decreases repetitive CFD workload and engineering rework.
- Allows engineers to evaluate more configurations before selecting a design.
- Preserves knowledge currently distributed across experts, legacy brands, and previous projects.
- Improves consistency between Trillium locations.
- Can later power a limited customer-facing selection and quotation portal.

### Pilot and success measures

Begin with one centrifugal-pump family from Trillium Pumps Italy, where the surrogate-model research and domain experts already exist.

Measure:

- Requirement-to-proposal turnaround time.
- CFD hours required per quotation.
- Number of design alternatives evaluated.
- Difference between AI predictions and validated CFD/test results.
- Engineering revisions before approval.
- Quote win rate and margin after sufficient commercial data exists.

### Short pitch

> Trillium has already demonstrated that AI can simulate pump performance much faster than traditional CFD. RapidDesign converts that research into an everyday engineering product, helping us evaluate more designs, produce proposals faster, and compete with the digital selection capabilities of Flowserve, KSB, and Sulzer.

## Recommendation and Technical Fit

Recommend presenting **RapidDesign as the primary project** because it directly builds on a current Trillium investment, has a clear internal owner, and can demonstrate value without waiting for customer deployment. Present **PumpCare 360 as the strategic customer-facing option** with greater recurring-revenue potential.

Both match a Java and React background: enterprise APIs and integrations can use Java/Spring, while the engineering dashboards can use React or Next.js. A small Python inference service can expose the existing AI models without requiring redevelopment of the underlying scientific model.

## Assumptions

- Public information may not reveal internal tools already operating at Trillium; the first project phase should confirm whether similar initiatives exist.
- Existing Cyclops² telemetry and AI-model interfaces can be made available through approved internal APIs.
- AI outputs remain advisory, explainable, versioned, and subject to engineering approval.
- The initial proposal should focus on business capability and measurable value; the final technology stack should be selected after approval.
