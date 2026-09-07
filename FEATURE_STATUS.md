# Feature status — Content, publishing, audio & video

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 497 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 2 | 0 | Native records/view |
| Work items & projects | records | 4 | 0 | Native records/view |
| Contacts & parties | records | 1 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 4 | 0 | AI question-and-answer workspace; records available as context |
| Deadlines & reminders | records | 1 | 0 | Native records/view |
| Notes | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 7 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 1 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 2 | 0 | Native records/view |
| Reports & analytics | report | 11 | 0 | Native records/view |
| Activity & audit trail | audit | 3 | 0 | Native records/view |
| Provider connections | integration | 1 | 0 | Provider request records only |
| Rights and contract library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Work title and asset registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Exploitation report ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Platform statement normalization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Territory and rights validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Gross receipts reconstruction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Deduction and distribution-fee audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Royalty rate and escalator calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Advance and recoupment ledger | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reserve and release validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cross-collateralization review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Royalty statement audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Licensee claim and response | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payment and receivable reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Catalog licensee and channel analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recording metadata registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ISRC normalization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Performer lineup evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rights ownership mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Airplay usage ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Public performance matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Simulcast usage control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Territory eligibility rules | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Featured performer allocation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Non-featured performer allocation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Society statement matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Unmatched usage claim | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Society query workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recording territory analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Book publishing pipeline work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Comic Stories | records | 1 | 0 | Native records/view |
| Characters | records | 1 | 0 | Native records/view |
| Comic Panels | records | 1 | 0 | Native records/view |
| Art Styles | records | 1 | 0 | Native records/view |
| Speech Bubbles | records | 1 | 0 | Native records/view |
| Comic Templates | records | 1 | 0 | Native records/view |
| Comic Series | records | 1 | 0 | Native records/view |
| Gallery | records | 1 | 0 | Native records/view |
| AI Story Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Character Designer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Dialogue Writer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Art Advisor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Plot Twists | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Scene Builder | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Villain Creator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Panel continuity | records | 1 | 0 | Native records/view |
| Advanced | records | 2 | 0 | Native records/view |
| Agentic content expansion | records | 1 | 0 | Native records/view |
| Real time trend detection content suggestion | records | 1 | 0 | Native records/view |
| Engagement prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Seo optimization loop | records | 1 | 0 | Native records/view |
| Multi lingual content adaptation | records | 1 | 0 | Native records/view |
| Schedule analytics lack ai endpoints for optimal posting tim | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Missing extract key points generate thumbnail suggest hashta | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Limited multi channel publishing integrations no twitter lin | integration | 1 | 0 | Provider request records only |
| No content approval workflow | records | 1 | 0 | Native records/view |
| No audience segmentation or personalization | records | 1 | 0 | Native records/view |
| No a b testing or variant management | records | 1 | 0 | Native records/view |
| No webhooks | integration | 1 | 0 | Provider request records only |
| Channel fatigue | records | 1 | 0 | Native records/view |
| AI Repurposer | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Plagiarism Check | records | 2 | 0 | Native records/view |
| Image Suggester | records | 2 | 0 | Native records/view |
| Performance AI | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Blog Outlines | records | 2 | 0 | Native records/view |
| Newsletters | records | 3 | 0 | Native records/view |
| Press Releases | records | 2 | 0 | Native records/view |
| Videos | records | 4 | 0 | Native records/view |
| Audio | records | 3 | 0 | Native records/view |
| Text Content | records | 1 | 0 | Native records/view |
| Images | records | 4 | 0 | AI question-and-answer workspace; records available as context |
| Translations | records | 2 | 0 | Native records/view |
| Summaries | records | 2 | 0 | Native records/view |
| SEO Content | records | 4 | 0 | AI question-and-answer workspace; records available as context |
| Social Posts | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Emails | records | 2 | 0 | Native records/view |
| Blog Posts | records | 2 | 0 | Native records/view |
| Marketing Copy | records | 2 | 0 | Native records/view |
| Scripts | records | 5 | 0 | AI question-and-answer workspace; records available as context |
| Podcasts | records | 2 | 0 | Native records/view |
| Voiceovers | records | 3 | 0 | Native records/view |
| Music Tracks | records | 2 | 0 | Native records/view |
| Editorial approval risk | records | 1 | 0 | Native records/view |
| Driven content brief generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Automated a b testing | records | 1 | 0 | Native records/view |
| Predictive content roi scoring | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| White label saas ready | records | 1 | 0 | Native records/view |
| Influencer outreach automation | records | 1 | 0 | Native records/view |
| All content routes lack dedicated ai generation endpoints mi | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| No team collaboration or granular permission management | records | 1 | 0 | Native records/view |
| No approval workflow | records | 1 | 0 | Native records/view |
| No real time publishing integrations wordpress webflow mediu | integration | 1 | 0 | Provider request records only |
| No cross platform published content analytics aggregation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| No payment billing module | records | 1 | 0 | Native records/view |
| Music projects | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Music assets & rights | records | 1 | 0 | Native records/view |
| Music rights & moderation review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Music render requests | integration | 1 | 0 | Provider request records only |
| Music publication requests | integration | 1 | 0 | Provider request records only |
| AI Plagiarism Detection | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI Catalog Valuation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI Rights Clearance | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI Royalty Forecasting | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI Contract Analysis | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI Market Trends | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI Sampling Detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Metadata Cleaner | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Licensing Recommender | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Revenue Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Catalog Acquisition Advisor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Royalty Settlement (Streaming) | records | 1 | 0 | Native records/view |
| Copyright Tracking (USCO) | records | 1 | 0 | Native records/view |
| Mechanical Licensing (MLC/HFA) | records | 1 | 0 | Native records/view |
| PRO Performance Tracking | records | 1 | 0 | Native records/view |
| Music Catalog | records | 1 | 0 | Native records/view |
| Rights & Licenses | records | 1 | 0 | Native records/view |
| Royalty Calculations | records | 1 | 0 | Native records/view |
| Platform Tracking | records | 1 | 0 | Native records/view |
| Artists & Writers | records | 1 | 0 | Native records/view |
| Contracts | records | 2 | 0 | Native records/view |
| Payments | records | 1 | 0 | Native records/view |
| Subscribers | records | 1 | 0 | Native records/view |
| Campaigns | records | 1 | 0 | Native records/view |
| Segments | records | 1 | 0 | Native records/view |
| A/B Tests | records | 1 | 0 | Native records/view |
| Schedules | records | 1 | 0 | Native records/view |
| Themes | records | 2 | 0 | Native records/view |
| Drip Campaigns | records | 1 | 0 | Native records/view |
| Editorial Calendar | records | 2 | 0 | Native records/view |
| AI Optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI History | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Segment Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Send Time Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Churn Detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Subscriber Prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| List Import Dedupe | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Campaign Orchestrator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Batch Content Variants | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vertical Template | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dynamic Content Blocks | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Realtime Subscriber Intel | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate Content | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate Subject Lines | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Adjust Tone | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Summarize | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Improve Content | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Story Leads | records | 1 | 0 | Native records/view |
| Source Verification | records | 1 | 0 | Native records/view |
| Fact Checking | records | 1 | 0 | Native records/view |
| Bias Detection | records | 1 | 0 | Native records/view |
| Article Drafts | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Trending Topics | records | 1 | 0 | Native records/view |
| Interviews | records | 1 | 0 | Native records/view |
| Media Assets | records | 1 | 0 | Native records/view |
| Expenses | records | 2 | 0 | Native records/view |
| AI Insights | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Story Competitive Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Source Matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Correction Suggestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Embargo Management | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Alt Text & Captions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Headline Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Story Angle Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Readability Scorer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Source Credibility Scorer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Galleries | records | 2 | 0 | Native records/view |
| Shoots | records | 2 | 0 | Native records/view |
| Packages | records | 2 | 0 | Native records/view |
| AI Editing | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Social Media | records | 1 | 0 | Native records/view |
| Equipment | records | 1 | 0 | Native records/view |
| Portfolio | records | 1 | 0 | Native records/view |
| Workflows | records | 1 | 0 | Native records/view |
| Email Templates | records | 1 | 0 | Native records/view |
| Testimonials | records | 1 | 0 | Native records/view |
| AI Pricing | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Style Analyzer | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Bookings | records | 2 | 0 | Native records/view |
| Shoot Plan AI | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Gallery Org AI | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agentic shoot orchestration | records | 1 | 0 | Native records/view |
| Computer vision photo analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Client communication automation | records | 1 | 0 | Native records/view |
| Pricing intelligence | records | 1 | 0 | Native records/view |
| Video highlight reel generation | records | 1 | 0 | Native records/view |
| Shoots without `/shoot | records | 1 | 0 | Native records/view |
| Clients without `/client | records | 1 | 0 | Native records/view |
| Galleries without `/gallery | records | 1 | 0 | Native records/view |
| Testimonials without `/review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Limited storage integration (integrations stub | integration | 1 | 0 | Provider request records only |
| No client proofing workflow (advanced markup/approval) | records | 1 | 0 | Native records/view |
| No photographer schedule optimization | records | 1 | 0 | Native records/view |
| No integration with Lightroom/Capture One (editing tools) | integration | 1 | 0 | Provider request records only |
| No marketplace (selling prints, products) | records | 1 | 0 | Native records/view |
| No notifications module (grep 0) | records | 2 | 0 | Native records/view |
| No audit logging (grep 0) | records | 2 | 0 | Native records/view |
| No webhooks for booking events | integration | 1 | 0 | Provider request records only |
| Episodes | records | 1 | 0 | Native records/view |
| Guest Management | records | 1 | 0 | Native records/view |
| Agentic episode orchestration | records | 1 | 0 | Native records/view |
| Real-time transcription + editing | records | 1 | 0 | Native records/view |
| Audience intelligence | records | 1 | 0 | Native records/view |
| Guest matching | records | 1 | 0 | Native records/view |
| Multi-platform publishing orchestration | records | 1 | 0 | Native records/view |
| Guests without `/guest | records | 1 | 0 | Native records/view |
| Episodes without `/episode | records | 1 | 0 | Native records/view |
| Analytics without `/audience | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| No integration with podcast hosts (Buzzsprout, Anchor) | integration | 1 | 0 | Provider request records only |
| No audience management (email lists, community) | records | 1 | 0 | Native records/view |
| No monetization features (sponsorship tracking, affiliate links) | records | 1 | 0 | Native records/view |
| Limited analytics (listener growth, retention) | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| No integration with video platforms (YouTube) | integration | 1 | 0 | Provider request records only |
| No webhooks for episode publish events | integration | 1 | 0 | Provider request records only |
| No file upload for audio masters | records | 1 | 0 | Native records/view |
| Topic Suggestions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Show Notes | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Intros & Outros | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Interview Questions | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Transcripts | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Guest Outreach | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Title A/B Tester | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Content Calendar | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI SEO Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Guest Fit Score | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Episode Quality | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Audience Sentiment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Topic Clustering | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cross-Promo Finder | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Growth Strategy | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Multi-Platform Prep | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Advanced Tools | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Distribution | records | 1 | 0 | Native records/view |
| Sponsorship Pitch | records | 1 | 0 | Native records/view |
| Episode Pacing Review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Competitor Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Episode Follow-up Email | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Script Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Guest Research | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Topic Suggestions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recommend | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Trend detector | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Audience segmentation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Churn prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| personalized schedule generation | records | 1 | 0 | Native records/view |
| multicategory playlist builder | records | 1 | 0 | Native records/view |
| live event optimization | records | 1 | 0 | Native records/view |
| churn prediction retention | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| collaborative filtering at scale | records | 1 | 0 | Native records/view |
| sportsspecific intelligence | records | 1 | 0 | Native records/view |
| recommend personalized content recommenda | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| scheduleoptimizer programming schedule vi | records | 1 | 0 | Native records/view |
| trenddetector emerging content discovery | records | 1 | 0 | Native records/view |
| audiencesegmentation taste clustering | records | 1 | 0 | Native records/view |
| sportshighlightextraction autoclip moment | records | 1 | 0 | Native records/view |
| subtitlegeneration auto captions | records | 1 | 0 | Native records/view |
| user preference learning loop implicit fe | records | 1 | 0 | Native records/view |
| ab testing framework for schedule changes | records | 1 | 0 | Native records/view |
| limited audience analytics depth | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| sports data api integration scores stats | integration | 1 | 0 | Provider request records only |
| cdnstreaming platform integration | integration | 1 | 0 | Provider request records only |
| admonetization layer | records | 1 | 0 | Native records/view |
| notificationsalerts for new content | records | 1 | 0 | Native records/view |
| Presentations | records | 1 | 0 | Native records/view |
| Slides | records | 1 | 0 | Native records/view |
| Layouts | records | 1 | 0 | Native records/view |
| Charts | records | 1 | 0 | Native records/view |
| Icon Sets | records | 1 | 0 | Native records/view |
| Animations | records | 1 | 0 | Native records/view |
| Speaker Notes | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Exports | records | 3 | 0 | Native records/view |
| Brand Kits | records | 1 | 0 | Native records/view |
| Collaborators | records | 1 | 0 | Native records/view |
| Chat | records | 4 | 0 | AI question-and-answer workspace; records available as context |
| Deck Pipeline | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate Deck (Text) | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate Slide | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Chart Advisor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Design Feedback | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Export PPTX | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Share/Collaborate | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Template Recommender | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Speaker Notes Expand | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Design Consistency Check | integration | 1 | 0 | Provider request records only |
| Content Quality Feedback | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| agentic deck generation | records | 1 | 0 | Native records/view |
| realtime collaboration | records | 1 | 0 | Native records/view |
| audience analysis adaptation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| data visualization recommender | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| presentation delivery coaching | records | 1 | 0 | Native records/view |
| template remix customization | records | 1 | 0 | Native records/view |
| templaterecommend for topic | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| speakernotesexpand from outline | records | 1 | 0 | Native records/view |
| designconsistencycheck fonts colors | integration | 1 | 0 | Provider request records only |
| contentqualityfeedback readability | records | 1 | 0 | Native records/view |
| audienceaware adaptation ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| realtime multiuser collaboration crdtpres | records | 1 | 0 | Native records/view |
| version history undo store | records | 1 | 0 | Native records/view |
| presenter mode timer notes view | records | 1 | 0 | Native records/view |
| limited export depth pdfvideo pipeline shall | records | 1 | 0 | Native records/view |
| presentation analytics viewer engagement | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| template marketplace | records | 1 | 0 | Native records/view |
| Split Jobs | records | 1 | 0 | Native records/view |
| Clips | records | 1 | 0 | Native records/view |
| AI Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Highlights | records | 2 | 0 | Native records/view |
| Captions | records | 2 | 0 | Native records/view |
| Clip Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Chapters | records | 1 | 0 | Native records/view |
| Roles | records | 1 | 0 | Native records/view |
| viral moment detection identifying high engagement segments by sentiment | records | 1 | 0 | Native records/view |
| format specific clip optimizer for platform tailored exports | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| automated chaptering with scene change detection | records | 1 | 0 | Native records/view |
| speaker diarization and sentiment tracking with emotional arc visualization | records | 1 | 0 | Native records/view |
| batch processing agent with priority queue and retry | records | 1 | 0 | Native records/view |
| publisher integrations with scheduled cross posting to social platforms | integration | 1 | 0 | Provider request records only |
| ai driven highlight detection endpoint frontend stub exists | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ai powered subtitle caption optimization endpoint | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ai scene change detection backend | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ai surface area is modest 6 endpoints relative | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| integrations with youtube tiktok instagram for direct | integration | 1 | 0 | Provider request records only |
| subtitle caption editing ui in backend | records | 1 | 0 | Native records/view |
| watermarking or branding controls | records | 1 | 0 | Native records/view |
| public api for third party integrations | integration | 1 | 0 | Provider request records only |
| webhooks for job completion notifications | integration | 1 | 0 | Provider request records only |
| Generate Prompt | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate Storyboard | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Analyze Prompt | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate Scene | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Text2video | records | 1 | 0 | Native records/view |
| Img2video | records | 1 | 0 | Native records/view |
| Storyboards | records | 1 | 0 | Native records/view |
| Scenes | records | 2 | 0 | Native records/view |
| Media | records | 1 | 0 | Native records/view |
| Transitions | records | 1 | 0 | Native records/view |
| Styles | records | 1 | 0 | Native records/view |
| Renderqueue | records | 1 | 0 | Native records/view |
| Prompts | records | 1 | 0 | Native records/view |
| Style recommend | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Viral score | records | 1 | 0 | Native records/view |
| style recommendation engine by brand industry content type | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| music generation matching video pacing and tone | records | 1 | 0 | Native records/view |
| voice over synthesis with natural speech | records | 1 | 0 | Native records/view |
| video editing suggestions recommending cuts transitions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| viral score prediction estimating content virality | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| collaboration layer with timecode anchored review comments | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ai driven style recommendation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| music sound generation | records | 1 | 0 | Native records/view |
| ai voice over synthesis endpoint | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| limited integration with stock video image libraries only | integration | 1 | 0 | Provider request records only |
| collaboration commenting system | records | 1 | 0 | Native records/view |
| approval workflow for video review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| direct publish to platform integration youtube tiktok | integration | 1 | 0 | Provider request records only |
| webhooks for render complete events | integration | 1 | 0 | Provider request records only |
| notifications subsystem | records | 1 | 0 | Native records/view |
| Soc | records | 1 | 0 | Native records/view |
| Devices | records | 1 | 0 | Native records/view |
| Firmware | records | 1 | 0 | Native records/view |
| Topology | records | 1 | 0 | Native records/view |
| threat intelligence feed integration correlating anomalies with external | integration | 1 | 0 | Provider request records only |
| anomaly severity prediction with risk scoring | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| automated incident response triggering remediation workflows | records | 1 | 0 | Native records/view |
| camera health prediction forecasting device failures | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| network behavior baseline learning auto detecting deviations | records | 1 | 0 | Native records/view |
| multi site federation with regional aggregation views | records | 1 | 0 | Native records/view |
| ai coverage is comprehensive for the domain | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| vision video frame ml analysis focused on | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| deep integration with specific video analytics platforms | integration | 1 | 0 | Provider request records only |
| siem splunk arcsight connector | integration | 1 | 0 | Provider request records only |
| multi site regional management | records | 1 | 0 | Native records/view |
| formal compliance reporting export | records | 1 | 0 | Native records/view |
| notifications subsystem alerts only | records | 1 | 0 | Native records/view |
| Titles | records | 1 | 0 | Native records/view |
| Descriptions | records | 1 | 0 | Native records/view |
| Hashtags | records | 1 | 0 | Native records/view |
| Thumbnails | records | 1 | 0 | Native records/view |
| Hooks | records | 1 | 0 | Native records/view |
| CTA Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Viral Predictor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Video Summarizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Podcast Transcriber | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Trends | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Personas | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Video Ideas | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Comments | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Competitors | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| viral content predictor scoring on hooks trends length | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| multi platform optimizer generating platform specific versions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| trend forecaster predicting emerging trends 1 2 weeks ahead | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| audience sentiment analyzer predicting comment sentiment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| content gap analyzer surfacing opportunities from competitor data | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| direct youtube tiktok instagram api publishing with scheduling | records | 1 | 0 | Native records/view |
| tsv reports 0 ai but routes suggest under reported | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| vision based thumbnail scoring | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| multimodal script to storyboard generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| limited platform api integration youtube tiktok instagram beyond stub | integration | 1 | 0 | Provider request records only |
| bulk content scheduling publishing | records | 1 | 0 | Native records/view |
| collaboration commenting on scripts | records | 1 | 0 | Native records/view |
| a b testing framework | records | 1 | 0 | Native records/view |
| performance analytics dashboard | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Create Video | records | 1 | 0 | Native records/view |
| Reviews | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Avatars | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Provider Render | records | 1 | 0 | Native records/view |
| Sports Highlights | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| B-Roll Suggester | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Music Matcher | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Consent Rights | records | 1 | 0 | Native records/view |
| Interview Q's | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate Script | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Enhance Review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Suggest Avatar | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Analyze Sentiment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate Metadata | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate CTA | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Translate | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Suggest Template | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Complete Package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| A/B Variations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Video Highlights | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Transcript Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Quality Score | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Emotion Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| testimonial quality scorer emotional impact clarity length | records | 1 | 0 | Native records/view |
| emotional tone and body language analysis for authenticity scoring | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| auto editing assistant suggesting cuts pacing adjustments retakes | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| transcription with emotion sentiment markers timeline aligned | records | 1 | 0 | Native records/view |
| testimonial campaign optimizer recommending selection and ordering | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| real time recording coach giving feedback during capture | records | 1 | 0 | Native records/view |
| ai is actually substantial 18 endpoints tsv claim | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| vision based body language analysis beyond emotion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| real time recording coach during capture | records | 1 | 0 | Native records/view |
| native linkedin tiktok publishing | records | 1 | 0 | Native records/view |
| collaboration commenting on draft testimonials | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| limited multi approver workflow single approvals route | records | 1 | 0 | Native records/view |
| webhook notifications for approval state changes | integration | 1 | 0 | Provider request records only |
| multi tenant white label support | records | 1 | 0 | Native records/view |
| Pipelines | records | 1 | 0 | Native records/view |
| Providers | records | 1 | 0 | Native records/view |
| Tools | records | 1 | 0 | Native records/view |
| Skills | records | 1 | 0 | Native records/view |
| Assets | records | 1 | 0 | Native records/view |
| Render jobs | records | 1 | 0 | Native records/view |
| Review gates | records | 1 | 0 | Native records/view |
| Photoapp eakarsu work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Spreadsheets | records | 1 | 0 | Native records/view |
| Revenue Plan | records | 1 | 0 | Native records/view |
| Headcount Plan | records | 1 | 0 | Native records/view |
| Expense Plan | records | 1 | 0 | Native records/view |
| Scenarios | records | 1 | 0 | Native records/view |
| Dashboards | records | 1 | 0 | Native records/view |
| Auto Subtitle | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Music Recommendation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Scene Transitions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Performance Predictor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Platform Export | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Usage Analytics | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Brand Consistency | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Upload | records | 1 | 0 | Native records/view |
| Variance | records | 1 | 0 | Native records/view |
| Auto subtitles | records | 2 | 0 | Native records/view |
| Music recommender | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Scene transition suggester | records | 2 | 0 | Native records/view |
| Engagement predictor | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Brand style checker | records | 2 | 0 | Native records/view |
| Realtime collab | records | 2 | 0 | Native records/view |
| Review approval | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Diff restore ui | records | 2 | 0 | Native records/view |
| Platform publish | records | 2 | 0 | Native records/view |
| Team permissions | records | 2 | 0 | Native records/view |
| Engines | records | 1 | 0 | Native records/view |
| Languages | records | 1 | 0 | Native records/view |
| Voice profiles | records | 1 | 0 | Native records/view |
| Generations | records | 1 | 0 | Native records/view |
| Generation versions | records | 1 | 0 | Native records/view |
| Effect presets | records | 1 | 0 | Native records/view |
| Stories | records | 1 | 0 | Native records/view |
| Story clips | records | 1 | 0 | Native records/view |
| Captures | records | 1 | 0 | Native records/view |
| Dictation sessions | records | 1 | 0 | Native records/view |
| Agent bindings | records | 1 | 0 | Native records/view |
| Queue jobs | records | 1 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 497 feature pages were visited in the browser; 495 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 230 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

230 original AI entries are now grouped into **8 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
