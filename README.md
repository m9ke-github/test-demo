
**Joe's Take and Bake Pizza Project Vision**
***
Provide customers with a simple low-frictiion way to order and pay for take and bake pizza, inform us when they arrive at our restaurant for pick up, and have their order brought to them in our parking lot without leaving their cars, even with weak or no connectivity. 

**Team Roster**
***
JTB = Joe's Take and Bake

CO = CO Tech

|Role|Team|Name|Mattermost|email|Time Zone|Out of Office|
|------|-----|--------|-----|-------------|-----------|-
Marketing Director|JTB|Tom Jones|@tomj|tj@jtb.com|EST UTC-5| |
IT Director|JTB|Janet Kilpatrick|@janet|janet.kilpatrick@jtb.com|EST UTC-5| |
IT Lead|JTB|Chirs Bridger|@chrisb|chris.bridger@jtb.com|EST UTC-5| |
|Project Manager|CO|Mike Buckland|@mikeb|mike.buckland@co.com|PST UTC-8|  |
|Tech Lead|CO|Linda Rogers|@linda|linda.rogers@co.com|EST UTC-5 |12/30/20-  01/05/21
|Frontend Dev|CO|Ricardo Alvarez|@ricardo|ricardo.alvarez@co.com|CST UTC-6| |
|Backend Dev|CO|Lin Li|@lin|lin.lee@co.com|EST UTC-5| |
|Design Lead|CO|Krishna Penmetcha|@kp|krishna.penmetcha@co.com|EST UTC-5| |
|UX Researcher|CO|Blake Ericson|@blake|blake.ericson@co.com|CET UTC+1| |
|Content Strategist|CO|Phil Sumner|@phil|phil.sumner@co.com| EST UTF-5| |

***
**Meeting Agendas and Deliverables**
***

**Week 1**

Day|Meeting Name|Attendees|Agenda|Deliverable|
|------|-----|--------|-----|-------------|
|1|Project Team Meeting|Everyone|Meet and greet, Introduce project vision, roles and responsibilities, Meeting schedule for week 1 Document storage|CO PM: distribute project vision document, meeting schedule and pointer to doc storage in advance|
|1|Agile Process : Define Our team way of working|Everyone|Key Agile meetings: backlog refinement, sprint planning, standups, sprint review including demo, sprint retrospective, definition of done project wide, acceptance criteria for individual stories|Mike: send documentation to team in advance of meeting, document and distribute team decisions on processes to use for project|
|2|Architecture|JTB Marketing Dir <br> JTB IT Dir <br> JTB IT Lead <br> CO FE Dev <br> CO BE Dev <br> CO Tech Lead |Intro to PWA on mobile devices architectural diagrams |CO tech staff: prepare and present high level architecture to JTB|Document technical decisions and tech stack gaps identified, including potential open source components|
|2|Customer Checkout and Security|JTB Marketing Dir, JTB IT Dir, JTB IT Lead,  CO FE Dev, CO BE Dev, CO Tech Lead |JTB IT Dir present business rules and requirements relevant to credit card orders on mobile devices, CO Tech Lead present PWA checkout and security, CO Tech Lead survey available open source carts document recommendations for JTB |
|3|Branding|Everyone|JTB Marketing Dir. Present JTB Branding Guidelines|CO PM: Document decisions and open questions|
|3|User Experience| JTB Marketing Dir, CO Design Lead, CO UX Researcher, CO Content Strategist, CO FE Dev, CO BE Dev|Review existing JTB personas and assets|CO PM: Document decisions and identified gaps, Document and distribute open questions document|
|4|Procurement| JTB IT Lead, CO BE Dev, CO Tech Lead,  CO FE Dev, CO BE Dev OPTIONAL: CO Design Lead,  CO UX Researcher|Gap analysis to identify all known hardware and software that project needs but does not have, Document these in a shopping list|CO PM: Document decisions and open questions, Formulate plan with team to resolve open questions, Develop shopping list and place acquisition of shopping list items in backlog|
|4|Product Plan Review|Everyone|Cross-functional review of Product Architecture, Checkout/Security, Branding, UX, and Shopping List|Team: identify high level tasks, CO PM: document tasks in backlog in such a way that all project work items can be extracted and displayed online as a project plan, including status of each item.|
|5|Story Splitting Workshop: How to parse large user stories into increments that can be implemented and tested in one sprint; how to ensure that completed large user stories get completed and tested over future sprints|Everyone|CO PM presents story splitting techniques to team|CO PM: send documentation to team in advance of meeting|
|5|Week Wrap Up|Everyone|Team prioritizes all backlog items  coming from the week’s meetings assigns any unassigned items to specific individuals|CO PM: document assigned items in project tracker|

**Week 2**

|Day|Meeting Name|Attendees|Agenda|Deliverable|
|------|-----|--------|-----|-------------|
|1|Architecture|JTB Marketing Dir, JTB IT Dir, JTB IT Lead, CO FE Dev, CO BE Dev, CO Tech Lead |Technical Working Meeting - Inputs to this meeting: Comments from last week’s Cross-functional Product Plan Review, including implications of server-side rendering vs client side rendering, Do all browsers support service workers? Notifications need to go both ways, How to implement customers notifying the restaurant when they arrive for pick up, Data migration (currently totally unknown)|Too much unknown here to solve it all in one pass, team will initially focus on 1-browser support for service workers, 2-Push notifications.  CO PM will curate meeting notes for items 1 and 2,  and put action items in the backlog for resolution|
|2|Architecture|JTB Marketing Dir, JTB IT Dir, JTB IT Lead, CO FE Dev, CO BE Dev, CO Tech Lead |Inputs to this meeting: Items not addressed in yesterday’s Tech Working Meeting, including Implications of server-side rendering vs client side rendering, Data migration (currently totally unknown), and How to implement customers notifying the restaurant when they arrive for pick up|CO PM: we spent the whole meeting on data migration.  Post notes for  data migration, Get action items for data migration in the backlog; Get follow up items in backlog for server-side vs client-side rendering and customer notifications.
|3|Customer Checkout and Security|JTB Marketing Dir, JTB IT Dir, JTB IT Lead,  CO FE Dev, CO BE Dev, CO Tech Lead|Tech Working Meeting, including Verify current  PCI compliance, Ascertain if changes to implement PWA can all be implemented within current PCI scope or if it must be widened, current JTB cart compatibility with WPA, potential need for compatible open source PCI-compliant cart software, Identify vendor for pen testing and scans triggered by significant change to PCI-compliant network|Too much unknown here to solve it all in one pass, team will initially focus on 1-making WPA changes within already in-scope PCI certified network without widening scope,  2-Vendor identification for pen test and scan which we know we must do.   CO PM wok with JTB IT Dir and potentially JTB Security team to figure out if/how PWA changes can be implemented within curent PCI scope, and find a vendor or pen testing and scanning|
|3|Customer Checkout and Security|JTB Marketing Dir, JTB IT Dir, JTB IT Lead,  CO FE Dev, CO BE Dev, CO Tech Lead|Inputs to this meeting: Items not addressed in yesterday’s Tech Working Meeting, including including Verify current  PCI compliance, Ascertain if changes to implement PWA can all be implemented within current PCI scope or if it must be widened, current JTB cart compatibility with WPA, potential need for compatible open source PCI-compliant cart software, |Too much unknown here to solve it all in one pass, team will initially focus on 1-making WPA changes within already in-scope PCI certified network without widening scope,  2-Vendor identification for pen test and scan which we know we must do.   CO PM work with JTB IT Dir and potentially JTB Security team to figure out if/how PWA changes can be implemented within curent PCI scope, and find a vendor or pen testing and scanning|
|4|Branding|Everyone|JTB Marketing Dir. Present results of week 1 JTB Branding for review by whole team|CO PM: Document decisions and deliverables to resolve open questions.|
|4|User Experience| JTB Marketing Dir, CO Design Lead, CO UX Researcher, CO Content Strategist, CO FE Dev, CO BE Dev|Review existing JTB personas and assets|CO PM: Document decisions and identified gaps, Document and distribute open questions document|
|4|Procurement| JTB IT Lead, CO BE Dev, CO Tech Lead,  CO FE Dev, CO BE Dev OPTIONAL: CO Design Lead,  CO UX Researcher|Gap analysis to identify all known hardware and software that project needs but does not have, Document these in a shopping list|CO PM: Document decisions and open questions, Formulate plan with team to resolve open questions, Develop shopping list and place acquisition of shopping list items in backlog|
|5|Product Plan Review|Everyone|Cross-functional review of Product Architecture, Checkout/Security, Branding, UX, and Shopping List|Team: identify gaps, CO PM: document gaps via issues in backlog.|
|5|Week Wrap Up|Everyone|Team prioritizes all backlog items  coming from the week’s meetings assigns any unassigned items to specific individuals|CO PM: document assigned items in project tracker week 2 for completion next week|
