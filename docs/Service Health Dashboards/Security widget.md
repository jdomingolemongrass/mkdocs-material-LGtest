# Security widget

View the following information in the Security widget:

* Security score based on your organization's compliance to benchmarks
* Your organization's benchmarks and the quantity of controls that pass or fail said benchmarks

Information in the Security widget is also evaluated by the Lemongrass security, networking, and infrastructure teams.

## Security score information

The following table lists the statuses for the security score:

| Status                                                    | Description                                       |
| ----------------------------------------------------------- | --------------------------------------------------- |
| ![Green](assets/Dashboardspage_WidgetStatus_Green.webp)   | The security score percent is greater than 80.    |
| ![Orange](assets/Dashboardspage_WidgetStatus_Orange.webp) | The security score percent is from 60 through 80. |
| ![Red](assets/Dashboardspage_WidgetStatus_Red.webp)       | The security score percent is less than 60.       |

## Navigating the Security page

On the **Security** page, complete the following actions for additional information:

* Select an option in the environment box to change your environment.
* Click **Show Details** or **Hide Details** to display or hide the charts and tables in each section.
* Select a legend to display or hide it from the chart.
* Use the **Entries per page** box, **RESET** button, search box, and other boxes specific to a section to change the display of entries in a table.
* Use the navigational buttons to go to the next page of a table.

### Well Architected Security section

The Well Architected Security section includes a main chart displaying the percent of recommendations from the previous 12 months. When you expand the details section, you can view a chart and table containing information for the current month and previous two months for each of the following categories of recommendations:

* **Action Recommended**: Findings include errors.
* **Investigation Recommended**: Findings include warnings.
* **No Problems Detected**
* **Checks with excluded items**: Findings were suppressed or solved using a workaround.

The recommendations in the Well Architected Security section are a basic set of recommendations foundational for cloud services.

### Cloud Security Posture Management section

The Cloud Security Posture Management section includes a main chart displaying the compliance percentage of cloud service and configuration controls from the previous 12 months based on the following benchmarks for industry best practices:

* AWS Foundational Security Best Practices (FSBP) standard
* Center for Internet Security (CIS) AWS Foundations Benchmark

When you expand the details section, you can view a chart and table containing information for the current month and previous two months for the following controls:

* **Compliant Controls**
* **Non-Compliant Controls**: Controls are updated with likelihood, risk, and comments.
* **Excluded Controls**: Controls were suppressed or solved using a workaround.
* **Disabled Controls**: Controls are not applicable to any environment.

### Continuous Security Monitoring section

The Continuous Security Monitoring section includes a main chart displaying the quantity of the following finding types from the previous 12 months:

* **EC2 Findings**: Findings are specific to Amazon EC2 resources.
* **IAM Findings**: Findings are specific to IAM entities and access keys.
* **S3 Findings**: Findings are specific to Amazon S3 resources.
* **Other Findings**: Findings are specific to third-party solution resources, but can be enabled when cost saving measures, such as classification and tagging, are implemented.

When you expand the details section, you can view a chart and table containing information for the current month and previous two months for the finding types and the findings with the most quantity for each finding type.

Each finding is rated based on their severity according to the National Institute of Standards and Technology (NIST) Common Vulnerability Scoring System (CVSS) scoring system. The following table lists the ratings of a finding based on the NIST CVSS scoring system:

| Rating       | CVSS Score            |
| ------------ | --------------------- |
| **None**     | Equal to 0.0          |
| **Low**      | From 0.1 through 3.9  |
| **Medium**   | From 4.0 through 6.9  |
| **High**     | From 7.0 through 8.9  |
| **Critical** | From 9.0 through 10.0 |

### Exceptions section

The Exceptions section includes a table where instances with deviating services and configurations are listed. Deviation requests must be submitted through an ITSM ticket by the system owner or representative and requires approval from the managed service provider and Lemongrass security.

> **Note**: Alternative controls must be implemented to compensate for a disabled service. For example, the request to disable endpoint protection on a legacy operation system requires the system to be isolated until the system is replaced with a supported operating system.

### ITSM Security Tickets section

The ITSM Security Tickets section includes a chart displaying the quantity of ITSM security tickets from the previous 12 months with the following statuses:

* **New**
* **In Progress**
* **On Hold**
* **Resolved**
* **Closed**

When you expand the details section, you can use the following columns to sort or customize the information displayed in the table:

* **Ticket**
* **Finding or Title**
* **Priority**
* **Created date**
* **Resolved date**
* **Assignee**
* **Status**

Findings in the ITSM Security Tickets section can include, but are not limited to, security group modifications and continues security monitoring events.
