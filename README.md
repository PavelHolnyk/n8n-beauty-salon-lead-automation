# AI Lead Qualification & Email Automation for a Beauty Salon

**n8n · OpenRouter · Zoho CRM · Klaviyo · Google Sheets · Telegram**

Website booking enquiries are classified as Hot, Warm or Cold and routed to CRM, manager notifications and personalized email flows.

## Problem

Each enquiry required manual reading, qualification, CRM entry and follow-up selection. Customers with different levels of interest received the same generic communication, while managers had to check forms or email for new requests.

## Solution

Website booking form → n8n webhook → field normalization → Google Sheets / Zoho CRM / Telegram → AI qualification → Klaviyo profile and segment → targeted email flow.

| Segment | Communication |
| --- | --- |
| Cold | Introduction and discount offer |
| Warm | Welcome and reminder sequence with a click-based branch |
| Hot | Thank-you message and a next-visit offer |

The AI returns structured Hot / Warm / Cold classification. Enquiries without a comment default to Warm.

## Results

- **Automated data entry across four services:** lead information goes to Google Sheets, Zoho CRM and Klaviyo, with a Telegram notification to the manager, without manual copying in the designed flow.
- **Immediate manager notification:** new enquiries trigger a Telegram alert, reducing reliance on manually checking forms and email.
- **Personalized follow-up:** Hot, Warm and Cold leads receive different email sequences; the Warm flow uses click behavior to avoid an unnecessary reminder.
- **Repeat-visit communication:** Hot leads receive a thank-you email with a **10% next-visit discount**, as described in the Notion case.
- **Repeatable processing:** each enquiry follows the same intake and segmentation logic as volume grows.
- **Potential business impact:** faster responses and more relevant offers are intended to support conversion and repeat visits. No measured conversion or revenue increase is claimed.

## Tech Stack

n8n, OpenRouter, Structured Output Parser, Zoho CRM API, Klaviyo API, Telegram Bot API, Google Sheets, website form and webhooks.

## Demo & Case Study

- [Watch the demo](https://youtu.be/ARXB1ryOtSM)
- [Read the full Notion case](https://tangy-whitefish-6d0.notion.site/d17c12839d0683bb86d0018eebb9a416)

## Author

**Pavlo Holnyk — AI Automation & AI Agents**

[Portfolio](https://tangy-whitefish-6d0.notion.site/408c12839d06816f9e61ff1aa7392587) · [LinkedIn](https://www.linkedin.com/in/pavlo-holnyk/) · [Upwork](https://www.upwork.com/freelancers/~011ee82fd5725aa92e)
