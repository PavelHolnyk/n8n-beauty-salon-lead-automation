# Automated Lead Qualification and Email Communication for a Beauty Salon

Portfolio project by Pavlo Holnyk.

## Overview

An n8n automation for website booking enquiries: lead intake, AI qualification, CRM records, manager notifications and segmented email communication.

## Workflow

Website form -> webhook and normalization -> Google Sheets, Zoho CRM and Telegram -> OpenRouter AI classification (hot / warm / cold) -> Klaviyo profile and list -> segment-specific email flow.

Requests without a comment default to the warm segment.

## Stack

n8n, OpenRouter, Zoho CRM API, Telegram Bot API, Klaviyo API, Google Sheets.

## Demo and case study

- [Case study in Notion](https://tangy-whitefish-6d0.notion.site/d17c12839d0683bb86d0018eebb9a416)
- [Video demo](https://youtu.be/ARXB1ryOtSM)

## Repository contents

Project documentation only. Workflow exports and source files have not been added. No independently verified business performance metrics are claimed here.
