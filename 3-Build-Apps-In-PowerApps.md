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