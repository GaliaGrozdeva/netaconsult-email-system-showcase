# Netaconsult Email System Showcase

This repository presents the concept and workflow of an email ingestion and classification system designed for accounting-office operations.

> This is a public showcase repository.  
> It does not contain production code, mailbox credentials, client data, databases, email contents or internal classification rules.

## Purpose

Accounting offices receive a large volume of emails from clients, institutions, payroll systems, tax authorities, banks and internal team members.

Important tasks, documents and deadlines can easily remain hidden inside inboxes or scattered between multiple mailboxes.

The Netaconsult Email System is designed to transform incoming email communication into a structured, reviewable and task-oriented workflow.

## Core idea

The system processes multiple mailboxes, classifies incoming messages and prepares structured data for the main Accounting Desktop Assistant.

Its role is not only to collect emails, but to help convert incoming communication into actionable accounting-office work.

## Key workflow areas

### Multi-mailbox processing

The system can process several office mailboxes and keep track of incoming messages, senders, subjects, attachments and processing status.

### Client and institution recognition

Emails can be classified by:

- client;
- sender domain;
- institution;
- subject patterns;
- document type;
- operational importance.

Typical institution categories include tax, social security, statistics and other administrative communication.

### Email-to-task workflow

Incoming messages can become structured operational tasks for the accounting team.

This helps reduce the risk of missing important client requests, institutional messages or document deadlines.

### Attachment handling

The system supports attachment workflows, including the ability to download attachments by client and period.

This is useful when accounting documents arrive by email and must be saved, reviewed, classified and connected to the relevant client.

### Review and diagnostics

The system is designed with review-first logic.

Unclear or unmatched emails can remain in review status instead of being automatically assigned incorrectly.

Diagnostic logs and reports help explain what was imported, classified, skipped or left for review.

## Integration model

The email system communicates with the main Accounting Desktop Assistant through structured exchange files.

This avoids uncontrolled direct database sharing and keeps the main desktop system as the operational control center.

## Safety principles

- no automatic deletion of emails;
- no uncontrolled client assignment;
- review status for unclear messages;
- local processing and diagnostic logs;
- structured exchange with the main system;
- separation between email ingestion and operational task control.

## Business value

The system helps accounting teams:

- reduce inbox overload;
- turn emails into structured work;
- improve document traceability;
- download and organize attachments by client and period;
- reduce missed tasks and hidden client requests;
- support a more controlled office workflow.

## Current status

Internal working system under active development and testing.

This public repository is a showcase only. Production code, mailbox settings, databases, credentials and real email data are private.

## Development approach

The system is designed around real accounting-office communication patterns:

1. identify incoming email sources;
2. classify by client, institution and workflow type;
3. keep uncertain messages in review;
4. prepare structured data for the main desktop system;
5. preserve traceability and manual control.
