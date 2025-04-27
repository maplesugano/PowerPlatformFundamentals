# Describe how to build applications with Microsoft Power Apps 

Power Apps is used to build apps that allow you to act on your data. Power Apps is great for replacing paper forms, legacy solutions, or just that spreadsheet that you and a few coworkers pass around. 

---

# Describe Power Apps

Power Apps is a no-code/low-code platform for building apps that builds off concepts like formulas in an Excel workbook such as `SUM` and `TEXT`.

Power Apps usually work with data, and there are several choices for data sources e.g. Dataverse, SharePoint, Dynamics 365, SQL Server and Azure SQL, Office 365.

There are two primary application types that can be created with Power Apps: __canvas__ and __model-driven apps__. Each application type has multiple features and functionality that helps support different scenarios. 

## Canvas Apps

Canvas apps are a great option for organizations to build tailored apps designed to perform specific tasks based on their needs. A key advantage to canvas apps is that they interact with data from multiple data sources.

Once created, canvas apps can be easily shared with users so they can run them in a browser or on a mobile device. Additionally, canvas can be embedded into SharePoint sites, Power BI reports, model-driven applications, or even Microsoft Teams.

Canvas apps are easy to create and can be easily created from existing data. For example, canvas applications can be created from Excel spreadsheets, SharePoint sites, and more. If you don't need a customer design and your data is in Microsoft Dataverse, you can automatically generate a **model-driven app**. 

## Model-Driven Apps

Unlike canvas apps where the app maker has control over the data sources, screen layout, and overall user experience, model-driven apps are always built from data in Microsoft Dataverse. The view sizes are determined responsively based on the device being used. 

Model-driven applications are used as management applications. For example, when someone reports a problem with audio/visual equipment, they use a canvas application. To manage the incoming requests, assist users with troubleshooting, dispatch someone to fix them, and analyze overall operations related to the organization, organizations typically use a model driven app.

### Differences between Canvas and Model-Driven Apps

| App consideration | Canvas | Model-driven |
|-------------------|--------|--------------|
| Data source | Not Dataverse-driven | Dataverse-driven |
| App purpose | Task or screen focused | Back office / process focused |
| User Interface (UI) | Custom UI<br>Device integration<br>Easily embeddable | Responsive / consistent UI<br>User personalization<br>Data relationship navigation<br>Security trimming of UI |

## Building a Canvas App

The basic Power Apps creator journey to build a canvas app looks something like this:

1. Identify a business need that Power Apps can address.
2. Connect to any necessary data in your Power Apps.
3. Design the app using controls, buttons, and an easy-to-use interface. Then your end user can interact with the data to accomplish the business need.
4. Save and publish the app and test functionality.
5. Once satisfied, share the app with end users to give them a better business process.

## Building a Model-Driven App

Model-driven apps in Power Apps are assembled with the point-and-click App Designer, which turns every choice you make into metadata.

1. You pick the data layer — Dataverse tables, their columns, relationships, and choice fields
2. Add the user-interface elements such as the site-map navigation, forms for editing records, and list views for displaying them. 
3. Enrich the app with logic (business process flows, rules, or Power Automate flows) and visualisation components (charts, dashboards, or embedded Power BI).
4. Once the foundations are in place, you refine each table's forms and views to show only what the scenario needs, and you can add new pages — full-page table views, dashboards, external links, web resources, or fully custom pages — via the **Add page** button. 
5. Hitting Play lets you test instantly, while real-time co-authoring speeds team development and the built-in Copilot offers natural-language queries and AI suggestions inside the finished app.

