Title:
EcoLogix Workflow Document (AI Agent & Dashboard Integration)
1. Project Overview
EcoLogix is a sustainability dashboard app for logistics managers, vendors, and analysts to track carbon emissions, shipments, vendor impact, and get AI-powered actionable recommendations using AWS Bedrock/SageMaker agent.
2. Architecture Diagram
(User → App/UI → AWS Agent → Analytics & Response).
3. Workflow Steps
Stepwise sequence:
.User Actions
  . Login and open EcoLogix dashboard.
   . Enter shipment data, sustainability queries, or vendor details.
. App Processing
     . UI dashboards show analytics, charts, and metrics.
      . User queries are forwarded to AWS Bedrock/SageMaker agent (planned/implemented).
. Agent Response
   . Agent processes data, computes optimized suggestions.
   . Response returned: “Best shipment route”, “Lower emissions vendor”, “Eco-action recommendations”.
. Analytics & Reporting
   . Dashboard visualizes before/after impact, key stats, reports.
   . User can download/export reports as CSV/PDF.
   4. AI Agent Flow (Summary)
       . When user submits query, EcoLogix app connects to AWS Bedrock or SageMaker agent using secure API.
       . Agent logic applies sustainability models, computes optimal solutions, sends back response.
       . App dashboard updates with latest recommendations and new analytics.
   5. Key Technologies/Stack
        . Glide (No-code dashboard)
        . AWS Bedrock/SageMaker (AI agent, cloud integration)
        . Public app link (https://shaky-needle-4282.glide.page/dl/8c0359
   6. Roles & Permissions
       . Managers: Can view all shipments, analytics, suggestions
       . Vendors: Can access assigned shipment data, upload files, get responses

"Planned Feature"
Analytics graphs and detailed charts are planned for future versions. Current version demonstrates core agent integration and eco-query response flow.


## Demo Video (No voice version)

https://drive.google.com/file/d/1Y2QOPBkEvAff06uL86uRpbkrpzqF0n0f/view?usp=drive_link


## Project Presentation (PPTX)

https://drive.google.com/file/d/1dD6f11Jn0Kh7zUq74mz5wiKfQo929BNH/view?usp=drivesdk
