# SHERLOCK

**Evidence-driven reconstruction for scattered AI work.**

SHERLOCK is an ARCHETRON application for recovering, reconstructing, and investigating work spread across AI conversations, files, exports, attachments, and related artifacts.

It is designed for a problem that becomes more serious as AI becomes part of everyday work: the information still exists, but the context around it is fragmented.

SHERLOCK helps rebuild that context into an inspectable case record so users can recover chronology, locate evidence, investigate what changed, and produce defensible answers and reports.

> This repository is the public information surface for SHERLOCK. It does not contain SHERLOCK source code, proprietary architecture, internal mechanisms, private implementation details, or the private ERIE implementation.

## The Problem

AI-assisted work is increasingly distributed across many conversations, exports, files, documents, and tools.

Traditional search can find matching text, but users often need something more specific:

- Where did this come from?
- When did this work begin?
- What changed over time?
- What evidence supports this conclusion?
- What conflicts with it?
- What remains unknown?

SHERLOCK exists to investigate that history rather than merely return similar passages.

## What SHERLOCK Does

SHERLOCK is designed to:

- ingest conversations, files, exports, attachments, and related evidence;
- reconstruct chronology across fragmented work;
- preserve provenance back to source material;
- organize evidence into an investigation-ready case record;
- expose conflicting and unresolved information rather than silently flattening it;
- support evidence-backed questions about a user's work history; and
- produce durable investigative reports through WATSON.

Its central principle is deliberately simple:

> **Evidence before conclusions.**

## The Architecture Beneath SHERLOCK

SHERLOCK is also a working demonstration of deeper ARCHETRON technology.

### ERIE

ERIE — the **Epistemic Retrieval & Intelligence Engine** — provides the evidence-centered investigative model beneath SHERLOCK.

Traditional retrieval asks what information is relevant to a query.

ERIE is concerned with what the available evidence actually supports.

Within SHERLOCK, ERIE concepts are used to preserve distinctions such as known and unknown, agreement and contradiction, historical and current understanding, evidence and conclusion.

SHERLOCK demonstrates those ideas through a product people can directly use without exposing the proprietary ERIE implementation.

### Chronos

Chronos provides persistent historical and temporal structure.

It allows SHERLOCK to reason over when evidence occurred and how understanding evolved through time. Temporal compression can organize large histories across day, week, month, and year scales while preserving a path back toward the underlying evidence.

### WATSON

WATSON turns an accumulated case record into a formal investigative report.

Report generations are preserved independently so a later investigation does not silently erase an earlier one.

## Relationship to Gemini

SHERLOCK combines deterministic software systems with Gemini where model reasoning adds value.

Deterministic systems handle responsibilities that should remain stable and inspectable, including evidence preservation, chronology, provenance, validation, and other structural operations.

Gemini is used for bounded evidence analysis, synthesis, and readable investigative output grounded in the case record.

The model does not replace the evidence system beneath it.

## Why It Matters

SHERLOCK is built around a different optimization target from a conventional chatbot.

Rather than optimizing for the most convincing response, SHERLOCK is designed to produce the most defensible one.

That means preserving the boundaries around what the available evidence can and cannot establish.

## Development Status

SHERLOCK is a working application under active development.

The current project demonstrates evidence ingestion, historical reconstruction, investigation, temporal reasoning, observable agent activity, evidence-backed question answering, and WATSON reporting.

Public documentation describes product purpose, externally relevant capabilities, and evaluation context only. Proprietary implementation details are intentionally withheld.

## Documentation

- [Product Overview](docs/PRODUCT.md)
- [Security](SECURITY.md)
- [Support](SUPPORT.md)
- [License](LICENSE.md)

## ARCHETRON

SHERLOCK is an ARCHETRON technology.

ARCHETRON develops infrastructure for intelligent systems with deliberately separated responsibilities around evidence, memory, reasoning, attention, observation, governance, and execution.

SHERLOCK is the investigation application: the visible product through which evidence-first reconstruction and investigation can be experienced directly.

## Repository Scope

`SHERLOCK-info` is a public documentation repository intended for product information, evaluation, hackathon review, business reference, and other material that can be shared without exposing the private SHERLOCK implementation.

Publication of this repository does not grant access to SHERLOCK source code, private systems, non-public interfaces, proprietary architecture, algorithms, protocols, internal workflows, or ARCHETRON intellectual property.

---

Copyright © 2026 ARCHETRON. All rights reserved.
