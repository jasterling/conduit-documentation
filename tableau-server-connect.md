# Using A Conduit Connector With Tableau Server

### Part 1: Open Conduit
**Step 1**: Click the "View connector" button for a selected connector.

**Step 2**: Copy the url under "Power BI/Tableau Spark Connector (screenshot below)

![](https://www.dropbox.com/s/s5nf7vxdjui3xm2/Screenshot%202019-05-06%2023.49.09.png?raw=1)

### Part 2: Open Tableau Server.

**Step 1**: Choose "Spark SQL" from Connect > To a Server > More...

![alt text](https://www.dropbox.com/s/qi0xkii39kkfer9/Screenshot%202019-05-06%2023.44.27.png?raw=1)

**Step 2**: In the "Spark SQL" configuration screen, enter your Conduit connector information:
* Server: Enter the URL from the Conduit connector. In the example above, "demo-conduit.westus2.cloudapp.azure.com" would be used
* Port: Enter 10002
* Type: Choose "SparkThriftServer" (if not already selected)
* Authentication: For this example, "No Authentication" has been selected. This will vary depending on the specific Conduit instance
* Transport: HTTP
* HTTP Path: Enter "cliservice"
* Put a checkmark beside "Require SSL"

![](https://www.dropbox.com/s/yfe5rr6mpyt93rj/Screenshot%202019-05-06%2023.53.36.png?raw=1)


**Step 3**: Click the "Sign In" button

## Congratulations. You have connected to a Conduit connector with Tableau Server.
