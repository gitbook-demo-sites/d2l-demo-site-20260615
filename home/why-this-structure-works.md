---
title: Why this structure works
description: The rationale behind pairing a public help center with a dedicated API-reference section.
icon: sitemap
---

# Why this structure works

The current D2L public surface already signals two very different jobs:

- *Support content* answers task-level questions like where to log in, how to recover access, and how to stay informed about releases.
- *Developer content* answers integration questions with a dedicated API surface and machine-readable schema.

Putting both under one documentation shell makes the experience easier to navigate without forcing the audiences into the same page templates.

## Audience split

<table>
  <thead>
    <tr>
      <th>Audience</th>
      <th>Main need</th>
      <th>Best section</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Learners and families</td>
      <td>Find the right login path and understand who can help</td>
      <td>Help center</td>
    </tr>
    <tr>
      <td>Admins and support teams</td>
      <td>Reduce repetitive access questions and guide people to the right owner</td>
      <td>Help center plus release communication</td>
    </tr>
    <tr>
      <td>Developers and data teams</td>
      <td>Explore dataset operations and models</td>
      <td>Data sets API reference</td>
    </tr>
  </tbody>
</table>

## What GitBook demonstrates well here

{% stepper %}
{% step %}
### Route people fast

The homepage acts as a decision layer instead of another long article. Visitors choose support, release communication, or developer documentation immediately.
{% endstep %}

{% step %}
### Keep the reference trustworthy

The API section stays spec-backed and independent. That avoids mixing changeable product copy into generated operations and models.
{% endstep %}

{% step %}
### Connect product messaging to support content

Release-note subscriptions, login-finder guidance, and escalation language reinforce that Brightspace is a managed platform used across many institutions and account models.
{% endstep %}
{% endstepper %}

## Demo assumption

This structure assumes D2L wants a cleaner, more intentionally designed external documentation hub, not a one-for-one migration of every Brightspace Community page on day one.
