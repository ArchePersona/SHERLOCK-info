# SHERLOCK Product Overview

## Purpose

SHERLOCK is an evidence-driven reconstruction and investigation application for work created across AI conversations, files, exports, attachments, and related artifacts.

Its purpose is to help users recover context that has become fragmented across many separate systems and interactions.

## The Recovery Problem

AI can increase the amount of work a person creates while making that work harder to recover later.

Architectural decisions, research, discoveries, drafts, supporting files, and important conversations can become distributed across thousands of messages and disconnected exports.

Traditional search helps locate matching text. SHERLOCK is designed for the harder problem of reconstructing what happened, when it happened, how evidence relates, and what conclusions the available record can actually support.

## Product Position

SHERLOCK is not positioned as a general-purpose chatbot.

It is an investigation application built around evidence, provenance, chronology, and historical reconstruction.

The product is intended to help users move from scattered material toward an inspectable case record that can support questions, review, and reporting.

## Intended Outcomes

SHERLOCK is intended to help users:

- recover work distributed across AI conversations and related files;
- reconstruct chronology across fragmented evidence;
- trace answers back to source material;
- distinguish supported conclusions from unresolved questions;
- preserve contradictions rather than silently erase disagreement;
- investigate when work, ideas, or decisions first appear in the available record; and
- produce durable investigative reports from the reconstructed case.

## ERIE

SHERLOCK is a working application of ERIE concepts.

ERIE — the Epistemic Retrieval & Intelligence Engine — is concerned with the state of evidence: what is known, what remains unresolved, what conflicts, what has changed, and what the evidence can defensibly support.

SHERLOCK demonstrates that evidence-first approach through an interactive investigation product while the proprietary ERIE implementation remains private.

## Chronos

Chronos provides persistent historical structure within the broader evidence-first direction.

In SHERLOCK, temporal organization helps investigations reason about when evidence occurred and supports hierarchical views across days, weeks, months, and years while preserving provenance toward original material.

## WATSON

WATSON is SHERLOCK's reporting capability.

It turns the accumulated case record into formal investigative reports. Individual report generations are preserved independently so later work does not silently overwrite earlier conclusions.

## Relationship to Gemini

SHERLOCK combines deterministic systems with Gemini.

Deterministic software owns responsibilities that should remain stable and auditable, including evidence preservation, chronology, provenance, validation, and structural processing.

Gemini is used where bounded reasoning, synthesis, and readable investigative output provide value.

The evidence system remains distinct from the model using it.

## Relationship to ARCHETRON

SHERLOCK is part of ARCHETRON's broader work on infrastructure for intelligent systems.

ARCHETRON separates major responsibilities rather than collapsing evidence, memory, reasoning, observation, governance, execution, and attention into one opaque layer.

SHERLOCK is the investigation application within that direction.

## Development Status

SHERLOCK is a working application under active development.

Current work demonstrates large-scale evidence ingestion, chronology reconstruction, evidence-backed investigation, temporal reasoning, observable agent activity, and persistent WATSON report generation.

This public repository intentionally describes the product without publishing proprietary implementation architecture, source code, internal algorithms, workflows, control logic, protocols, data structures, or reconstructive technical detail.
