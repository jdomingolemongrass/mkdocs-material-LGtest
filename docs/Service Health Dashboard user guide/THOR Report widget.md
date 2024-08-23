# THOR Report widget

The THOR Report widget contains the following information:

- Alert error count of incidents
- Problem records assigned to incidents
- Solution rate of problem records

## Top Alerts section

The Top Alerts section contains the top ten alert errors by quantity from the current month and the past four months.

## All Errors by SID Heatmap section

View information in the All Errors by SID Heatmap section using the following columns:

- **Alert Error**
- **SID**
- **Source**
- **Environment**
- Quantity of alert errors from the current month until the past four months
- Total quantity of an alert error from the current month until the past four months
- **Linked Problems**

### SID heatmap colors

The following table lists the colors in the All Error by SID Heatmap section:

| Color  | Description                                                      |
| ------ | ---------------------------------------------------------------- |
| Green  | The quantity of the alert error is equal to 0.                   |
| Orange | The quantity of the alert error is from 1 through 10.            |
| Yellow | The quantity of the alert error is from 11 through 99.           |
| Red    | The quantity of the alert error is equal to or greater than 100. |

### Creating or linking a problem to an incident

>**Note**: This procedure is only enabled for service delivery managers (SDMs).

1. Select an option in a column.
2. In the **Incident Tickets** window, select the checkbox of a ticket.
3. Click **CREATE PROBLEM** or **LINK TO PROBLEM**.
4. Specify the required information in the form and click **SUBMIT**.

## All Errors by Environment Heatmap section

View the information in the All Errors by Environment Heatmap section using the following columns:

- **Environment**
- Quantity of alert errors from the current month until the past four months
- Total quantity of an alert error from the current month until the past four months

### Environment heatmap colors

The following table lists the colors in the All Error by SID Heatmap section:

| Color  | Description                                                       |
| ------ | ----------------------------------------------------------------- |
| Green  | The quantity of the alert error is from 0 through 100.            |
| Orange | The quantity of the alert error is from 101 through 500.          |
| Yellow | The quantity of the alert error is from 501 through 999.          |
| Red    | The quantity of the alert error is equal to or greater than 1000. |

## Navigating the All Errors by SID Heatmap section and All Error by Environment Heatmap section

Complete the following actions for additional information:

- In the **Alert Group** list, select one of the following options:
  - **Valid**: The incident is legitimate.
  - **Invalid**: The incident is an invalid alert such as being a duplicate incident, contains information only, or is about a monitoring failure.
- Click **COLUMNS** to display the **Find Column** pane and specify the columns you want to view in the table of the section.
- Click **FILTERS** to add and delete filters for the information displayed in the table of the section.
- Click **DOWNLOAD AS EXCEL FILE (.CSV)** to download the information displayed in the table of the section.
- Click **CLEAR FILTERS** to clear the filters applied in the table of the section.
