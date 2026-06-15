---
title: D2L Documentation Hub
description: A first-draft external documentation and help-center experience for Brightspace customers, learners, and developers.
icon: house
layout:
  width: wide
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: false
  outline:
    visible: false
  pagination:
    visible: false
  metadata:
    visible: false
---

# One entry point for product help, release communication, and developer onboarding

D2L already has the right raw ingredients for a strong external docs experience: a public help center, clear learner support flows, and an OpenAPI-backed data-set reference. This draft turns those assets into a cleaner front door for three distinct journeys:

<table data-view="cards">
  <thead>
    <tr>
      <th></th>
      <th></th>
      <th></th>
      <th data-hidden data-card-target data-type="content-ref"></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><h3>:graduation_cap:</h3></td>
      <td><strong>Learner support</strong></td>
      <td>Help students find the right login, understand their sign-in method, and know where account support lives.</td>
      <td><a href="https://app.gitbook.com/s/XSPACE_HELP/logging-in-to-brightspace">logging-in-to-brightspace</a></td>
    </tr>
    <tr>
      <td><h3>:loudspeaker:</h3></td>
      <td><strong>Release communication</strong></td>
      <td>Show how customers can subscribe to monthly release-note updates and configure meaningful notification habits.</td>
      <td><a href="https://app.gitbook.com/s/XSPACE_HELP/subscribing-to-release-notes">subscribing-to-release-notes</a></td>
    </tr>
    <tr>
      <td><h3>:bar_chart:</h3></td>
      <td><strong>Developer onboarding</strong></td>
      <td>Connect product and support context directly to the existing Brightspace data-set API reference.</td>
      <td><a href="https://app.gitbook.com/s/itTj9dQaH3F6ZMfgwPvB/">data-sets-api-reference</a></td>
    </tr>
  </tbody>
</table>

{% columns %}
{% column %}
## What this demo emphasizes

- An external-facing help center instead of a flat article archive
- A visible split between user help and developer reference
- Clear escalation paths when the customer's institution owns the account
- A tighter product story around Brightspace, launch communication, and data access
{% endcolumn %}

{% column %}
## What it deliberately leaves light

- Full article migration from the current community site
- Instructor and admin journey depth
- Translated variants and audience adaptation
- Deep visual theming beyond a first-pass brand shell
{% endcolumn %}
{% endcolumns %}

{% hint style="info" %}
This draft is intentionally narrow. It demonstrates a stronger information architecture and navigation story without trying to mirror the entire Brightspace Community corpus in one pass.
{% endhint %}

## Recommended top-level sections

1. *Home* for orientation and audience routing
2. *Help center* for learner-facing support and release-update guidance
3. *Data sets API reference* for developers, analysts, and integration teams

## Suggested next clicks

- Read [Why this structure works](why-this-structure-works.md) for the demo narrative
- Open [Release communication model](release-communication-model.md) for the subscription and announcement pattern
- Jump into the existing [Data sets API Reference](https://app.gitbook.com/s/itTj9dQaH3F6ZMfgwPvB/) to show how API content can live beside end-user support
