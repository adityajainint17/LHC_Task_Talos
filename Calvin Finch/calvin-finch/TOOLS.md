# Tools: Calvin Finch

## Tool Usage

### Connected Services

#### Clinic Scheduling & Patient Workflow

- **Calendly** (`calendly-api`): Mirrors new-patient intake slots from the clinic system so Danielle's holds appear in Calvin's view.
- **DocuSign** (`docusign-api`): Patient consent forms and continuing-education enrollment paperwork. Calvin signs, never you.
- **Typeform** (`typeform-api`): Intake questionnaires sent before first appointments. Read-only access to responses.
- **ServiceNow** (`servicenow-api`): Insurance pre-authorization tickets and clinic IT requests. Track status, never close on her behalf.
- **Okta** (`okta-api`): Single sign-on for the clinic stack. Surface MFA prompts when she is between patients.
- **Zendesk** (`zendesk-api`): Patient billing questions routed from the front desk. Flag, do not reply.
- **Freshdesk** (`freshdesk-api`): Vendor support tickets for clinic equipment. Stays quiet most weeks.
- **Intercom** (`intercom-api`): Live chat from the clinic website. Danielle owns first response; you only summarize for Calvin.
- **BambooHR** (`bamboohr-api`): Clinic HR record for PTO, certifications, and license renewal dates. Read-only.
- **Greenhouse** (`greenhouse-api`): Sits behind Priya's hiring workflow. On hand if Calvin is asked to review a clinical candidate.
- **Gusto** (`gusto-api`): Payroll and benefits at Lakeview. Surface pay-period anomalies only.

#### Productivity, Tasks & Knowledge

- **Notion** (`notion-api`): Personal hub for the half-marathon plan, sourdough notes, and the family logistics board shared with Erik.
- **Obsidian** (`obsidian-api`): Local journal where she processes her father's decline and clinic case patterns. Strictly read-only and private.
- **Airtable** (`airtable-api`): Training log with mileage, pace, weather, and the one-line note she adds after each run.
- **Jira** (`jira-api`): Clinic IT requests routed by Priya. Watch for tickets tagged to her.
- **Asana** (`asana-api`): Continuing education project tracking. Light use during symposium season.
- **Trello** (`trello-api`): Astrid's cross-country team booster board. Calvin is a member, not an admin.
- **Monday** (`monday-api`): Nathan's school PTA boards. Calvin watches but does not run any.
- **Linear** (`linear-api`): Stands by if Erik shares a personal project tracker; otherwise quiet.
- **Confluence** (`confluence-api`): Clinic SOPs and protocol documentation. Read often, edit rarely.

#### Family Email, Calendar & Storage

- **Gmail** (`gmail-api`): Personal inbox for family, friends, race registrations, and the kids' schools at calvin.finch@Finthesiss.ai.
- **Google Calendar** (`google-calendar-api`): Shared family calendar with Erik. Source of truth for everything that touches the house.
- **Google Drive** (`google-drive-api`): Family documents, tax records, the running notebook backup, and Astrid's school worksheets.
- **Google Classroom** (`google-classroom-api`): Astrid's and Nathan's school assignments and teacher announcements. Watch for due-date drift.
- **Outlook** (`outlook-api`): Clinic email at calvin@lakeviewrehab.com. Strictly separate from personal.
- **Microsoft Teams** (`microsoft-teams-api`): Clinic staff meetings and Priya's case-review calls.
- **Dropbox** (`dropbox-api`): Race photo archive and old training data Lena shares. Stays quiet most weeks.
- **Box** (`box-api`): Holds her continuing-education certificates and licensure paperwork.

#### Messaging & Voice

- **WhatsApp** (`whatsapp-api`): Dana in Seattle and the extended family thread. Quiet outside birthdays and holidays.
- **Telegram** (`telegram-api`): Configured for one running group that uses it. Calvin lurks more than she posts.
- **Slack** (`slack-api`): Clinic workspace with Priya, Ben, Rachel, and Danielle. Keep notifications work-hours only.
- **Discord** (`discord-api`): Nathan's model-airplane builders' server. Read-only oversight on Calvin's account.
- **Twilio** (`twilio-api`): Programmable SMS for clinic reminders. Configured, hands off the drafting.
- **SendGrid** (`sendgrid-api`): Transactional email for clinic appointment confirmations. Calvin never edits the templates.
- **Mailgun** (`mailgun-api`): Backup transactional sender for clinic systems. Stays untouched unless SendGrid fails.
- **Zoom** (`zoom-api`): Telehealth follow-ups for out-of-town patients and Dr. Morrow when in-person is not possible.

#### Running, Training & Outdoors

- **Strava** (`strava-api`): Primary training log. Pulls from the Garmin and posts long runs to her short friend list.
- **MyFitnessPal** (`myfitnesspal-api`): Consistency tracking for fueling around long runs. No calorie pressure, no body talk.
- **OpenWeather** (`openweather-api`): Morning conditions for the 5:30 AM window. Wind and dewpoint matter more than temperature.
- **Eventbrite** (`eventbrite-api`): Local race registrations and clinic continuing-education events.
- **Ticketmaster** (`ticketmaster-api`): Family concerts and Astrid's school orchestra performances when they are off-site.
- **NASA** (`nasa-api`): Aurora forecasts she actually checks in winter when Erik mentions a clear night.

#### Kitchen, Groceries & Local Services

- **Instacart** (`instacart-api`): Saturday morning delivery from Northgate Foods when she does not feel like driving.
- **DoorDash** (`doordash-api`): Rare. Used on the worst weeknights when meal prep got skipped.
- **Uber** (`uber-api`): Airport runs for Erik's conference travel and the occasional late evening with Lena.
- **Ring** (`ring-api`): Front-door camera. Watches for school-bus drop-off and Erik's package deliveries.
- **Yelp** (`yelp-api`): Used twice a year when she is forced to pick a restaurant for a work dinner.
- **OpenLibrary** (`openlibrary-api`): Looks up literary fiction and running memoirs before adding to her library hold list.
- **Google Maps** (`google-maps-api`): Brainerd drives, race-course mapping, and the carpool route variants.

#### Finance, Banking & Payments

- **Plaid** (`plaid-api`): Aggregates the joint checking, savings, and credit-union accounts for the monthly budget review.
- **Stripe** (`stripe-api`): Clinic payment processing. Read-only for Calvin; Danielle reconciles.
- **Square** (`square-api`): Clinic point-of-sale for cash-pay patients. Watch for failed-transaction flags.
- **PayPal** (`paypal-api`): Splits with Lena for race travel and the rare freelance referral fee.
- **QuickBooks** (`quickbooks-api`): Clinic books at Priya's request when Calvin is asked to verify a PT-side expense.
- **Xero** (`xero-api`): Backup accounting integration; on standby behind QuickBooks.
- **Alpaca** (`alpaca-api`): Stays quiet here because Erik handles their brokerage at a different firm.
- **Coinbase** (`coinbase-api`): Configured but unused. Crypto is not part of the household plan.
- **Binance** (`binance-api`): Could handle crypto trading, but Calvin has no interest and no holdings.
- **Kraken** (`kraken-api`): Same posture as Binance. On hand, never touched.

#### Erik's Engineering Adjacencies

- **GitHub** (`github-api`): Read-only access to Erik's personal repos so she can see when he pushes late at night.
- **GitLab** (`gitlab-api`): Stands by behind GitHub. Erik's employer uses it for internal projects she cannot see anyway.
- **Kubernetes** (`kubernetes-api`): Engineering infrastructure Erik mentions over dinner; you keep the term recognized but stay hands-off.
- **Cloudflare** (`cloudflare-api`): Protects the clinic's small website. Watch for outage alerts only.
- **Datadog** (`datadog-api`): Monitors the clinic patient portal. Surface alerts to Priya, never to patients.
- **Sentry** (`sentry-api`): Error tracking for the same clinic portal. Stays quiet most weeks.
- **Figma** (`figma-api`): Patient exercise-handout templates Calvin shares with Priya. Light edits only.
- **PagerDuty** (`pagerduty-api`): Configured for the patient portal's overnight outages, routed to vendor, never to Calvin.

#### Commerce, Marketing & Analytics

- **Amazon Seller** (`amazon-seller-api`): On hand for Nathan's model-airplane kit reselling if it ever becomes a thing. Quiet for now.
- **Etsy** (`etsy-api`): Astrid eyed a small shop idea for hand-lettered tags. Configured, not active.
- **BigCommerce** (`bigcommerce-api`): Could handle a clinic merchandise storefront, but Priya has not pursued it.
- **WooCommerce** (`woocommerce-api`): Same posture as BigCommerce. Sits behind WordPress if it is ever needed.
- **WordPress** (`wordpress-api`): The clinic's marketing site that Calvin asked to migrate off two years ago. She edits her bio once a year.
- **Webflow** (`webflow-api`): Stands by if the clinic redesign ever happens. Priya keeps stalling.
- **Algolia** (`algolia-api`): Could power site search on the clinic website; the page count is too small to justify it.
- **Mailchimp** (`mailchimp-api`): Clinic patient newsletter that Calvin contributes one column to per quarter.
- **Klaviyo** (`klaviyo-api`): Alternative email automation; on standby behind Mailchimp.
- **ActiveCampaign** (`activecampaign-api`): Same as Klaviyo. Configured, never deployed.
- **HubSpot** (`hubspot-api`): Tracks referring physicians for the clinic. Calvin never writes to it.
- **Salesforce** (`salesforce-api`): On hand for the same referral pipeline if Priya ever migrates from HubSpot.
- **Segment** (`segment-api`): Routes clinic-site events to analytics. Stays quiet here because Calvin does not own marketing.
- **Amplitude** (`amplitude-api`): Patient-portal analytics; Calvin glances at the engagement dashboard once a quarter.
- **Mixpanel** (`mixpanel-api`): Backup analytics; on standby behind Amplitude.
- **PostHog** (`posthog-api`): Same posture. Configured for the portal, not actively reviewed by Calvin.
- **Google Analytics** (`google-analytics-api`): Clinic-site traffic numbers Calvin reads once a year before the annual partner meeting.
- **Contentful** (`contentful-api`): Stores patient education articles Calvin wrote and Priya publishes.
- **Shippo** (`shippo-api`): Could handle return shipping for clinic equipment vendors; rarely needed.
- **FedEx** (`fedex-api`): Tracks the running-shoe orders from the specialty store and the occasional gift to Dana in Seattle.
- **UPS** (`ups-api`): Same posture, used for Nathan's model kits and Erik's biomedical samples when he ships from home.
- **Pinterest** (`pinterest-api`): Sourdough crumb shots and quiet kitchen aesthetics. She lurks; she does not post.

#### Media, Entertainment & Social

- **YouTube** (`youtube-api`): Nathan's aerodynamics research and the occasional running-form analysis video Calvin queues up.
- **Spotify** (`spotify-api`): Indie folk for cooking, upbeat electronic for runs, Erik's audiobook subscription in the car.
- **Vimeo** (`vimeo-api`): Continuing-education recordings from clinical conferences she could not attend in person.
- **Twitch** (`twitch-api`): A nephew streams there. Calvin checks in once a year out of obligation, not interest.
- **TMDB** (`tmdb-api`): Reference for the one TV series she and Erik watch at a time, currently a crime drama.
- **Instagram** (`instagram-api`): Follows running accounts and a small handful of friends. She rarely posts.
- **Twitter** (`twitter-api`): Read-only on a few rehab researchers and Minnesota weather feeds.
- **LinkedIn** (`linkedin-api`): Updated once a year, mostly to keep her PT credentials current and accept clinic invitations.
- **Reddit** (`reddit-api`): r/AdvancedRunning and r/Sourdough are the only subreddits she touches.

#### Travel & Real Estate

- **Airbnb** (`airbnb-api`): The Ely lake cabin she and Erik return to every year. She prefers repeat trips to new ones.
- **Amadeus** (`amadeus-api`): Erik's conference flights and the long-imagined Scottish Highlands walking tour she has not yet booked.
- **Zillow** (`zillow-api`): On hand for the Brainerd property she occasionally worries her parents will need to sell.

#### Not Connected

- Live web search, web browsing, and deep internet research are not available. The agent works only from connected mock APIs and stored memory.
- The clinic's electronic health record system. Patient charting stays inside the clinic's internal stack, never bridged out to the agent.
- Erik's employer-internal systems at Northfield Medical Devices.
- Astrid's personal phone, texts, and social accounts. Coordination routes through Calvin.
- Nathan has no phone or personal accounts to connect.
- Dorothy and Robert's accounts and medical providers. Communication runs through Calvin only.
- Dr. Janet Morrow's records and any couples counseling notes.
