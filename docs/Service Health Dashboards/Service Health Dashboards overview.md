---
weight: -1
---
# Service Health Dashboards overview

View and monitor real-time insights and statistics using the Service Health Dashboards solution of the Lemongrass Cloud Platform (LCP). Each service health dashboard has its own widget to view the following information:

* Cloud provider billing
* Support tickets
* Environment backups
* Asset security

## Service Health Dashboard features

Access to features of the Service Health Dashboards solution depends on your role. For details about the setup and configuration, contact your LCP representative.

## Accessing the Dashboards page

1. On the Lemongrass Cloud Platform (LCP) home page, hover over the sidebar.
2. Select **Intelligence** > **Service Health Dashboards** to display the **Dashboards** page.

## Dashboards page

Download your monthly business report and manage your widgets on the **Dashboards** page.

### Refreshing widgets

Click ![Refresh](assets/Dashboardspage_Refreshbutton.webp) to refresh all widgets on the **Dashboards** page.

### Monthly Business Report

You can download a Monthly Business Report to view the summaries and trends of your dashboard widgets. Based on your available widgets, the Monthly Business Report can have the following information:

* Delivery review summary
* Incident ticket service level agreement (SLA) trends
* Service request SLA trends
* 6-month ticket trends
* Aging tickets
* Alerts summary
* Major incident overview
* Hyperscaler spend
* ELK backup report
* SecOps overview
* System maintenance schedule

#### Downloading a Monthly Business Report

>**Note**: This procedure is only enabled for service delivery managers (SDMs).

When you download a Monthly Business Report, it is saved as a PPT file.

1. Click **MBR**.
2. Specify a month and a year using the calendar.
3. Click **DOWNLOAD**.

### Copying the default widgets displayed to a customer

>**Note**: This procedure is only enabled for service delivery managers (SDMs).

Click **COPY TO CUSTOMER** to copy the default widgets displayed on your **Dashboards** page to the **Dashboards** page of the relevant customer.

### Changing views on the Dashboards page

>**Note**: This procedure is only enabled for service delivery managers (SDMs).

Click the view list and select one of the following options to change view on the **Dashboards** page:

* **SDM view**
* **Customer View**

### Adding a widget

1. Expand the **Add new chart?** box.
2. Select one or more of the following options:
      * **Backup**
      * **Financial Insights**
      * **Incidents**
      * **Problems**
      * **Requests**
      * **Security**
      * **THOR Report**
3. If you have more than one organization selected, optionally click **APPLY TO ACTIVE CUSTOMERS** in the **Configuration Change** dialog to also add the widget to your other organization.
4. Optionally click **SAVE** to save your default widgets displayed when you go to the **Dashboards** page.

#### Widget buttons

The following table lists the common buttons on a widget:

| Component                                                   | Description                      |
| ----------------------------------------------------------- | -------------------------------- |
| Status                                                      | Describes the status of a widget |
| **Details**                                                 | Displays the page of the widget  |
| ![Refresh](assets/Dashboardspage_WidgetButton_Refresh.webp) | Refreshes the widget             |
| ![Expand](assets/Dashboardspage_Widgetbutton_Expand.webp)   | Expands the widget               |
| ![Move](assets/Dashboardspage_Widgetbutton_Move.webp)       | Moves the widget                 |
| ![Close](assets/Dashboardspage_Widgetbutton_Close.webp)     | Hides the widget               |

#### Widget statuses

The following table lists the statuses of a widget:

| Status                                                    | Description                                                                                          |
| ----------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ |
| ![Green](assets/Dashboardspage_WidgetStatus_Green.webp)   | The information in the widget passed the service level agreement (SLA) defined by your organization. |
| ![Orange](assets/Dashboardspage_WidgetStatus_Orange.webp) | The information in the widget is about to fail the SLA defined by your organization.                 |
| ![Red](assets/Dashboardspage_WidgetStatus_Red.webp)       | The information in the widget failed the SLA defined by your organization.                           |
| ![Gray](assets/Dashboardspage_WidgetStatus_Gray.webp)     | Information is unavailable for this widget.                                                          |

### Navigating the sections of a widget page

Where applicable, complete the following actions for additional information:

* Hover over a graph to view the tooltip of the information.
* Click **Refresh** to refresh a section of the widget page.
* Click **Expand/Collapse** to expand or collapse a section of the widget page.
* Use the search box to search for an item in a section of the widget page.
* Use the **Rows per page:** list to specify the number of rows of a table in a section of the widget page.
* Use the navigational buttons to go to the next page of a table in a section of the widget page.
