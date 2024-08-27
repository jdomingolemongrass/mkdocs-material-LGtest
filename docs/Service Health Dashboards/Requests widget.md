# Requests widget

View the quantity of passed and failed requests for the current month and the past three months in the Incidents widget. The Requests widget also displays the quantity of requests with the following ticket types:

* Warning
* Breached
* New tickets according to priority

## Navigating the Requests page

On the **Requests** page, complete the following actions for additional information:

* In the chart section, select an option in the **Aggregation** list, and **Start Date** and **End Date** boxes to specify the information displayed in the graph.
* In the details table section, you can do the following:
  * Click **COLUMNS** to display the **Find Column** pane and specify the columns you want to view.
  * Click **FILTERS** to add and delete filters for the information displayed.
  * Select an option in the **Ticket Types** list to filter the tickets displayed.
  * Click **DOWNLOAD AS EXCEL FILE (.CSV)** to download the information displayed.
  * Click **CLEAR FILTERS** to clear the applied filters.
  * Use the following columns to sort or customize the information displayed:
    * **Date**
    * **Number**
    * **Short description**
    * **Assigned to**
    * **Priority**
    * **State**
    * **SID**
  * Select an item in the **Number** column to view the request in Lemongrass ServiceNow.
* In the Priority Summary section, view the quantity of requests grouped by priority.

### Ticket type information

The following table lists the options in the **Ticket Types** list:

| Type                | Description                                                 |
| ------------------- | ----------------------------------------------------------- |
| **Breached**        | The incident failed its service level agreement (SLA).      |
| **Breached (Live)** | The incident that is a new ticket failed its SLA.           |
| **New Tickets**     | The ticket was created in the last seven days.              |
| **Warning**         | The incident is about to fail its SLA.                      |
| **Warning (Live)**  | The incident that is a new ticket is about to fail its SLA. |
