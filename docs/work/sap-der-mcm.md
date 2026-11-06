---
title: SAP DER MCM product assistance
description: Product assistance for Measurement Concept Management in SAP Distributed Energy Resources, published on the SAP Help Portal.
---

# SAP DER MCM product assistance

<p class="lead">Product assistance for Measurement Concept Management (MCM), part of SAP Distributed Energy Resources. The documentation is published on the SAP Help Portal and explains how utilities model energy communities, configure formulas, and integrate with SAP S/4HANA Utilities.</p>

<div class="facts">
  <div><span class="k">Client</span><span class="v">SAP</span></div>
  <div><span class="k">Role</span><span class="v">Technical writer, SAP consultant</span></div>
  <div><span class="k">Audience</span><span class="v">Utility business users, administrators, integrators</span></div>
  <div><span class="k">Published on</span><span class="v">SAP Help Portal</span></div>
  <div><span class="k">Status</span><span class="v">Ongoing</span></div>
</div>

## The challenge

MCM sits at the intersection of energy regulation, metering, and billing. Readers arrive with very different mental models: a grid engineer thinks in meters and readings, a billing specialist thinks in contracts and tariffs, and an integrator thinks in APIs and processes. The product also uses precise terms that differ from the everyday language of the energy market, so loose wording leads directly to misconfiguration.

The documentation had to explain a dense domain model, stay exact about terminology, and keep up with a fast release cadence.

## What I delivered

- **Product assistance**, structured around the reader's journey: About MCM, Key Entities, Energy Communities, Configuration Types, Formulas, Managing an Energy Community, Managing Instances, Integration with SAP S/4HANA Utilities, and Authorizations
- **A new end-to-end chapter, *Setting Up an Energy Community***, that walks through the Tenant Electricity and Common Building Supply scenarios from first configuration to a working instance
- **App documentation** for the Fiori apps used day to day, including Maintain Commercial Location Groups, Manage Commercial Models, Manage Instances, Configure Formulas, and Configure Usages
- **What's New entries and release notes** for each delivery, covering features such as instance validation, pricing models and pricing agreements, actor type configuration, storage and grid actor creation, and validation events
- **API and process content**, including validation event references extended from create-only to change processes, and consolidation of overlapping API content into a single guide
- **A revised business description** with a concrete, scenario-based example, so evaluators can see how the product works before they configure anything

## How I approached it

### Terminology as a product decision

I maintain an agreed terminology set with the product owner and apply it across every topic. MCM uses *commercial location* rather than *market location*, *technical location* rather than *metering location*, *technical model* and *commercial model* rather than generic class or model names, and *energy community* rather than *energy sharing*. The difference between a tenant and a member is kept explicit everywhere it matters.

### Scenarios before reference

Domain concepts land better when readers see them working. The energy community chapter starts from two real-world scenarios and introduces each entity only when the reader needs it, then points into the reference topics for detail.

### SAP conventions, applied consistently

Field names, dates, and UI labels follow SAP Fiori conventions (for example, "the Valid From date"), so the documentation reads as part of the product rather than something written about it.

### Review loops with product management

Every major topic goes through product manager review. I fold feedback in without adding speculative content, which keeps the documentation accurate to what actually ships.

## What this shows

- Working fluently in a complex enterprise domain and an established corporate style
- Owning terminology and information architecture, not just individual topics
- Keeping release communication and core documentation in step across sprints

!!! info "Samples"
    The published documentation is available on the SAP Help Portal. I'm happy to walk through specific topics and the structure decisions behind them.
