# AI Master Control

A lightweight iOS app for keeping track of AI/agent tasks running in the background — so you
know when a long-running request finishes, and can see everything still in flight at a glance.

## What it does
- Tracks outstanding AI/agent requests, including several running at once
- Shows what's still in progress without switching tools or reconstructing context
- Notifies you when a task completes
- Exposes a simple interface for agents/tools to register a task and mark it complete

## Status
Largely superseded now that assistant tooling (e.g. Cowork) can notify directly — but it still
fills a gap by tracking multiple concurrent outstanding requests in one place.

## Stack
- SwiftUI (iOS)
