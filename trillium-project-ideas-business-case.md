# Business Case and Competitor Analysis

## Purpose

This document explains why the proposed technology projects would be valuable to Trillium Flow Technologies and how they compare with digital services offered by major pump-industry competitors.

The analysis is based on publicly available information. Trillium may already have additional internal capabilities that are not publicly documented.

---

# Idea 1: PumpCare 360

## What Is It?

PumpCare 360 would extend Trillium’s Cyclops² condition-monitoring solution into a complete pump-maintenance and customer-service platform.

It would convert pump data and alerts into:

- Clear explanations of detected problems
- Recommended maintenance actions
- Maintenance tasks and service requests
- Service and inspection history
- Spare-parts and technical-document access
- Energy, operating-cost, and downtime insights
- Integration with customer maintenance systems

## Why Would It Be Useful?

### 1. Monitoring Alone Does Not Resolve a Problem

Cyclops² can monitor pump condition and detect potential issues. However, customers ultimately need to know:

- What is wrong?
- How serious is it?
- What action should be taken?
- When should maintenance be performed?
- Which parts or services are required?

PumpCare 360 would connect detection with action.

### 2. It Can Generate Aftermarket Revenue

When the platform detects a problem, customers could directly request:

- A Trillium engineering review
- Field-service support
- Replacement parts
- Pump repair
- Efficiency upgrades

This creates a direct path from digital monitoring to service revenue.

### 3. It Improves Customer Retention

Customers would have pump data, documents, maintenance records, and service communication in one platform. This would make Trillium a long-term maintenance partner instead of only an equipment supplier.

### 4. It Can Support Non-Trillium Pumps

Supporting selected third-party pumps would allow Trillium to develop relationships with customers that do not yet have a large Trillium installed base.

## Competitor Analysis: Digital Pump Monitoring

| Competitor | Existing Service | Important Capabilities | Opportunity for Trillium |
|---|---|---|---|
| KSB | KSB Guard | Pump monitoring, recommended actions, maintenance tracking, expert monitoring, mobile access, and REST API integration | Connect Cyclops² alerts with Trillium service requests, asset records, and aftermarket workflows |
| Sulzer | BLUE BOX | Predictive analytics, pump risk analysis, remaining-life estimates, and energy, cost, and carbon insights | Provide similar business insights while connecting recommendations directly with Trillium engineering and services |
| Flowserve | RedRaven | Connected monitoring and predictive analytics for pumps, seals, and valves | Build a pump-focused solution using Trillium’s specialized pump knowledge |
| Xylem | Avensor | Anomaly detection, asset prioritization, guided inspections, and mobile maintenance workflows | Add structured inspection and technician workflows to Cyclops² |

## Identified Gap

Trillium publicly presents Cyclops² as a cloud-based condition-monitoring and analytics solution.

Competitors publicly promote additional capabilities such as:

- Maintenance planning and tracking
- Standard integration APIs
- Guided inspections
- Engineer-supported recommendations
- Energy and carbon analysis
- Actionable service workflows

The opportunity is not to replace Cyclops². It is to build a service and maintenance layer around it.

## Expected Business Value

- More Cyclops² adoption
- Recurring digital-service revenue
- More spare-parts and service sales
- Faster customer response
- Reduced customer downtime
- Better visibility into the installed pump base
- Stronger customer relationships

---

# Idea 2: RapidDesign

## What Is It?

RapidDesign would be an internal AI-assisted pump design and quotation platform.

It would convert Trillium’s existing AI simulation research into a practical tool that engineers can use during customer enquiries and pump-design projects.

## Why Would It Be Useful?

### 1. Custom Pump Design Takes Time

Customized pumps may require engineers to evaluate several configurations and run multiple CFD simulations. These simulations can be computationally expensive and slow down quotation and design work.

RapidDesign would use AI models to evaluate many possibilities quickly and send only the best candidates for detailed CFD validation.

### 2. Trillium Has Already Started the Required Research

Trillium Pumps Italy and Politecnico di Milano have developed reduced-order AI models for predicting centrifugal-pump performance.

The PIAI4PUMPS-GEO project is extending this work to include pump geometry.

RapidDesign would productize this research instead of starting a separate AI experiment.

### 3. Faster Quotations Can Improve Competitiveness

Customers frequently compare multiple pump suppliers. A faster technical response can help Trillium engage the customer earlier and improve its opportunity to win the order.

### 4. It Preserves Engineering Knowledge

Pump-selection knowledge may be distributed across experienced engineers, previous projects, spreadsheets, simulations, and legacy product information.

RapidDesign would make approved knowledge searchable and reusable across the organization.

## Competitor Analysis: Pump Selection and Engineering

| Competitor | Existing Service | Important Capabilities | Opportunity for Trillium |
|---|---|---|---|
| Flowserve | Affinity | Web-based pump sizing, performance curves, saved selections, technical documents, and quotation requests | Provide similar speed while supporting highly customized pump designs |
| KSB | EasySelect | Guided pump and valve selection, product configuration, pricing, documentation, CAD files, and ordering | Create an integrated Trillium workflow connecting requirements, engineering analysis, and proposal generation |
| Sulzer | Sulzer Select and ABSEL | Hydraulic selection, pump curves, operating-cost calculations, friction-loss calculations, and technical reports | Differentiate through AI-assisted custom engineering instead of only catalogue selection |

## Identified Gap

Competitors offer mature tools for selecting standard products from their catalogues.

Trillium’s main strength is highly engineered and customized pump solutions. Therefore, simply copying a standard selection tool would not create a strong advantage.

RapidDesign should focus on:

- Customized pump requirements
- Rapid evaluation of design alternatives
- AI-assisted performance prediction
- Reuse of previous approved designs
- Controlled CFD validation
- Faster generation of technical proposals

This would combine the speed of competitor selection tools with Trillium’s custom-engineering expertise.

## Expected Business Value

- Shorter quotation cycle
- Reduced repetitive CFD work
- More design alternatives evaluated
- Better use of engineering capacity
- More consistent technical proposals
- Faster customer response
- Improved reuse of previous designs
- Potential improvement in quotation win rate

---

# Overall Comparison

| Area | PumpCare 360 | RapidDesign |
|---|---|---|
| Primary users | Customers, service teams, and maintenance engineers | Trillium application, design, and sales engineers |
| Main objective | Convert monitoring data into maintenance and service actions | Reduce pump design and quotation time |
| Revenue impact | Digital subscriptions, parts, and aftermarket services | Faster quotations and potentially more orders |
| Dependency | Requires customer and Cyclops² data | Requires engineering data and existing AI models |
| Recommended timing | Strategic second initiative | Recommended first initiative |

---

# Recommendation

## Start with RapidDesign

RapidDesign is the recommended first project because:

- It builds directly on Trillium’s existing AI research.
- It can begin with internal users and controlled engineering data.
- It addresses a clearly measurable operational problem.
- It does not initially depend on customer-system integrations.
- It can demonstrate value through reduced engineering and quotation time.

## Develop PumpCare 360 Next

PumpCare 360 should be considered the longer-term customer-facing initiative because it can create recurring revenue and increase aftermarket-service opportunities.

A discovery exercise should first confirm the current Cyclops² roadmap, available APIs, customer requirements, and whether any similar internal initiatives already exist.

---

# Public Research Sources

- [Trillium Smart Condition Monitoring](https://www.trilliumflow.com/products/smart-condition-monitoring/)
- [Trillium and AIRIC Reduced-Order Modelling Project](https://airic.polimi.it/it/projects/trillium/)
- [Trillium Data-Centre Cooling Pumps](https://www.trilliumflow.com/data-center-cooling-pumps/)
- [KSB Guard](https://www.ksb.com/en-ch/guard)
- [KSB Guard REST API](https://www.ksb.com/en-ch/guard/ksb-guard-data-interface)
- [KSB EasySelect](https://www.ksb.com/en-fi/software-and-know-how/configuration-tools/ksb-easyselect)
- [Sulzer BLUE BOX](https://www.sulzer.com/en/shared/services/blue-box)
- [Sulzer Selection Tools](https://www.sulzer.com/en/services/selection-tools)
- [Flowserve RedRaven](https://www.flowserve.com/products/brands/redraven/)
- [Flowserve Affinity](https://www.flowserve.com/support/tools/online-tools/affinity-pump-selection-tool/)
- [Xylem Avensor](https://prod.xylem.com/siteassets/brand/xylem/resources/brochure/xylem_avensor_2025_brochure.pdf)
