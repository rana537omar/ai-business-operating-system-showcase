<p align="center"><img src="media/banner.png" alt="AI Business Operating System (All-in-One Business Platform): Domain, ERP, CRM, Website and Company Email in one system, with an AI layer on top" width="100%"></p>

# AI Business Operating System (All-in-One Business Platform)

**Five business tools, one system and one AI on top.** Your company's domain, company email, website, CRM and ERP live in one place. The modules pass work to each other automatically, and an AI copilot that runs on your own computer sees all of them.

> **This is a product showcase.** The AI Business Operating System software and its source code are proprietary and are **not** included in this repository. See [License](#license).

**Showcase website:** https://rana537omar.github.io/ai-business-operating-system-showcase/

<p align="center"><a href="https://wa.me/201208562225?text=Hello%2C%20I%20saw%20AI%20Business%20Operating%20System%20(All-in-One%20Business%20Platform)%20and%20I%20would%20like%20to%20get%20the%20full%20system%20and%20the%20source%20code."><img src="media/whatsapp-button.svg" alt="Get the full system and source code: chat on WhatsApp, +20 120 856 2225" width="380"></a></p>

## Demo video

<p align="center"><a href="https://rana537omar.github.io/ai-business-operating-system-showcase/#demo"><img src="media/video-poster.png" alt="Watch the AI Business Operating System product demo (3:19)" width="100%"></a></p>

**▶ [Watch in the browser](https://rana537omar.github.io/ai-business-operating-system-showcase/#demo)** · **⬇ [Download the video (MP4, 9 MB)](https://github.com/rana537omar/ai-business-operating-system-showcase/releases/download/demo-v1/AI-Business-Operating-System-demo.mp4)** · [Open the file on GitHub](media/AI-Business-Operating-System-demo.mp4)

The walkthrough is 3 minutes 19 seconds long, in 1080p, captioned, with no sound. It covers:

- the overview and the AI copilot, which answers questions, creates a lead and replies in Arabic;
- the DNS records the system generates for a domain;
- a visitor sending an inquiry from the company website, which becomes a CRM lead, lands in the sales@ inbox and gets an AI-written reply;
- AI email triage and an AI-drafted reply;
- winning a deal, which creates the ERP order and invoice;
- sending an invoice, the inventory, and adding an employee, which creates their mailbox;
- the automations, Arabic and dark mode.

## How it fits together

```
                               AI ✦
        ┌──────────┬───────────┬───────────┬───────────┐
     Domain   +   ERP    +    CRM    +   Website  +  Company Email
```

1. **Domain.** Your domains, with DNS records written automatically for company email and the website.
2. **ERP.** Finance, inventory, sales orders, invoices, purchasing, expenses and the team.
3. **CRM.** Leads, contacts, companies, a sales pipeline and tasks.
4. **Website.** The company website, built and published from the system.
5. **Company Email.** A mailbox for every employee and shared team inboxes such as sales@, support@ and billing@.
6. **AI.** One copilot on top of all five modules, running locally.

## What the modules do for each other

| When this happens | The system does this |
|---|---|
| You add a domain | Writes the MX, SPF, DKIM and DMARC records for company email |
| You connect the website to a domain | Adds the A record and the www record |
| HR adds an employee | Creates their company mailbox and adds them to their team inbox |
| A visitor sends the website contact form | Creates a CRM lead and deal, delivers it to sales@, and the AI emails the visitor a personal reply |
| An email arrives from a known customer | Adds it to that customer's CRM timeline |
| A sales email arrives from someone new | The AI spots the buying intent and creates a lead |
| A deal is won | Creates the ERP sales order and a draft invoice |
| An invoice is sent | Emails it to the customer from billing@ and logs it in the CRM |
| An invoice is paid | Marks the contact as a customer and updates their lifetime value |
| Stock drops below the reorder level | Drafts a purchase order and alerts ops@ |
| A product is marked "show on website" | Adds it to the website's product section, with live price and stock |
| A new lead comes in | The AI scores it and suggests the next action |

That is 14 automations in total, and each one can be switched off.

## Features

### AI layer
- **AI Copilot (Ctrl+K)**, with access to all five modules. It answers questions such as *"Which invoices are overdue?"*, *"Who should I call first?"*, *"How is the website doing?"* and *"What's low in stock?"*.
- **It can take actions**: create a lead with a deal, a shared mailbox or a domain. You confirm each one with a click.
- **Daily brief** written from live data.
- **Needs attention**: risks from every module, each with a one-click fix.
- **Writing help**: email replies, summaries, follow-ups, website copy and product descriptions.
- **Email triage**: every email is tagged as sales, support, billing, partnership, HR or spam.
- **Lead scoring** and a next best action for every contact.
- **Ask in Arabic, get the answer in Arabic.**
- **Local and private.** It uses a model on your own computer through Ollama. Nothing is sent to a cloud AI service, and a built-in engine takes over when no model is installed.

### Domain
- Tracks expiry dates, auto-renew, SSL certificates and the server IP for each domain.
- **Generates DNS records automatically** for email and the website. It supports the built-in mail server, Google Workspace, Microsoft 365 and Zoho Mail.
- **Live DNS and SSL health check**, a domain-name availability search, a registry lookup and a zone-file download.

### Company Email
- **A personal mailbox for every employee**, plus shared team inboxes, aliases and groups.
- **The CRM next to every email**: the sender's deals and invoices, or one click to turn the email into a lead.
- **Reply with AI**, **Summarize**, signatures and auto-replies.
- **Built-in mail server**. It receives mail over SMTP and sends through your provider's SMTP account, and outgoing mail is DKIM-signed. An inbound webhook is also available.
- Personal mailboxes stay private to their owner.

### Website
- **Page editor with live preview**. Sections include hero, features, numbers, testimonials, FAQ, call to action and the contact form.
- **AI writes the copy** for any section.
- **Products come live from ERP**, with price and availability.
- **Visit analytics**: daily visits, traffic sources and conversion.
- Brand colour, font, and right-to-left layout for Arabic sites. The site is served on your own domain.

### CRM
- **Drag-and-drop pipeline** from New to Won or Lost, with an AI score on every deal and a warning when a deal stalls.
- **One timeline per customer**, covering website forms, emails, AI actions and invoices.
- Contacts, companies, tasks and an AI follow-up email for any deal.

### ERP
- **Finance dashboard**: revenue against expenses, receivables aging and top products.
- **Products and inventory**: stock moves, margins, reorder levels and a website toggle.
- **Sales orders and invoices**: tax, print/PDF, email to the customer and overdue reminders.
- **Purchasing**: suppliers, purchase orders, auto-reorder and receiving into stock.
- **Expenses** by category.
- **Team (HR)**: roles, departments, salaries and leave requests. A mailbox is created for each new employee.

### For everyone
- **Roles**: owner, admin, manager, sales, finance, support and staff. Each role sees only its own modules.
- **English and Arabic**, with a full right-to-left layout.
- **Light and dark modes.**
- **One-minute setup wizard**, with an optional sample company to explore.

### Good to know
- It runs on Windows, macOS or Linux with Node.js, and all data is kept in one database file on your machine.
- Email between colleagues is delivered instantly. To send to other companies, you connect an SMTP account from your mail provider. To receive mail directly, the system needs a server with a public IP and port 25, or you can use the inbound webhook.
- You buy domains from a registrar. The system manages them, writes the DNS records for you to copy to the registrar, and checks that they are live.
- The AI features that write text need Ollama with a model installed. Without it, the built-in engine still answers business questions, triages email and scores leads, and it writes from templates.
- The interface is built for desktop and laptop screens.

### About the demo
The company in the screenshots and video is fictional: **Atlas Office Solutions**, an office-furniture supplier run by "Layla Mansour". Its customers, people, emails and figures are sample data. Its domain, `atlasoffice.test`, is a reserved test name, so the DNS records are shown as already published at a registrar.

## Screenshots

### Overview and AI

| | |
|---|---|
| ![Overview](media/overview.png) **Overview**: the AI and the five modules, with live numbers. | ![Needs attention](media/overview-attention.png) **Needs attention**: risks from every module, with one-click fixes. |
| ![AI Copilot](media/ai-copilot.png) **AI Copilot**: the daily brief and who to call first. | ![AI takes action](media/ai-action.png) **It acts**: a lead created from one sentence. |
| ![Arabic answer](media/ai-arabic.png) **Arabic**: ask in Arabic, get the answer in Arabic. | ![Automations](media/automations.png) **14 automations** connect the modules. |

### Domain and Company Email

| | |
|---|---|
| ![Domains](media/domain.png) **Domains**: health, SSL, expiry and mailboxes. | ![DNS records](media/domain-dns.png) **DNS**: email and website records, generated automatically. |
| ![Domain search](media/domain-search.png) **Find a domain**: a live availability check. | ![Arabic email](media/mail-arabic.png) **Team inbox**: AI tags, and the CRM next to the email. |
| ![Summary](media/mail-summary.png) **Summarize**: AI summary of a new lead's email. | ![Reply with AI](media/mail-ai-reply.png) **Reply with AI**: drafted by the local model. |
| ![Mail admin](media/mail-admin.png) **Mail admin**: mailboxes, aliases, groups and the mail server. | ![Email delivery](media/settings-email.png) **Email delivery**: SMTP relay, receiver and webhook. |

### Website and CRM

| | |
|---|---|
| ![Website](media/site.png) **Website**: pages, visits and conversion. | ![Page editor](media/site-editor.png) **Page editor**: sections, AI copy and live preview. |
| ![Live website](media/site-live.png) **The published website.** | ![Products from ERP](media/site-products.png) **Products** come live from ERP. |
| ![Inquiries](media/site-inquiries.png) **Inquiries**: every form becomes a CRM lead. | ![Pipeline](media/crm-pipeline.png) **Pipeline**: an AI score on every deal. |
| ![Contacts](media/crm-contacts.png) **Contacts**: score and next best action. | ![Customer timeline](media/crm-contact.png) **Customer timeline**: emails, invoices and activity. |
| ![Website lead](media/crm-contact-website.png) **A website lead**: the AI reply and scoring on the timeline. | ![Arabic pipeline](media/crm-arabic.png) **Arabic**: right to left. |

### ERP

| | |
|---|---|
| ![ERP dashboard](media/erp-dashboard.png) **Finance**: revenue against expenses and receivables aging. | ![Products](media/erp-products.png) **Inventory**: margins, low stock and the website toggle. |
| ![Invoice](media/erp-invoice.png) **Invoices**: send, remind and mark as paid. | ![Printable invoice](media/invoice-print.png) **Printable invoice** (PDF). |
| ![Purchasing](media/erp-purchasing.png) **Purchasing**: auto-drafted purchase orders. | ![Team](media/erp-team.png) **Team**: roles, salaries, leave and mailboxes. |
| ![Arabic overview](media/overview-arabic.png) **Arabic overview.** | ![Dark mode](media/dark.png) **Dark mode.** |

## Get the full system

If you want the AI Business Operating System for your own company or your clients, a live demo, or the complete source code, message me on WhatsApp: **+20 120 856 2225**.

<p align="center"><a href="https://wa.me/201208562225?text=Hello%2C%20I%20saw%20AI%20Business%20Operating%20System%20(All-in-One%20Business%20Platform)%20and%20I%20would%20like%20to%20get%20the%20full%20system%20and%20the%20source%20code."><img src="media/whatsapp-button.svg" alt="Get the full system and source code: chat on WhatsApp, +20 120 856 2225" width="380"></a></p>

## License

**Copyright © 2026 Rana Omar. All rights reserved.** The text, screenshots, images and video in this repository are shared for viewing only. No license is granted to copy, reuse, modify or republish them, or to use them or the AI Business Operating System software they show for any personal or commercial purpose. The company, people and figures in the demo are fictional. See [LICENSE](LICENSE).
