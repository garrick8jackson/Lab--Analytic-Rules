![image alt](https://github.com/garrick8jackson/Lab--Analytic-Rules/blob/dbd02c1d063fa6e2cf9419eaac063077573307fc/Analytic%20Rules%201.png)

After accessing the workspace through sentinel I searched and installed Azure activity 

![image alt](https://github.com/garrick8jackson/Lab--Analytic-Rules/blob/49c54a6ce77e61850248da93dbe682d3f3a918d6/analytic%20rules%202.png)

After installing Axure activity I went to the configuration option of the workspace and selected analytics which then moved me to Microsoft defender. I then selected the Rule templates

![image alt](https://github.com/garrick8jackson/Lab--Analytic-Rules/blob/f4818a2b7acb1d0c54c8e823c9734e537a94f83d/analytic%20rules%203.png)

I search for “rare subscription level operations” selected the template and hit create rule

![image alt](https://github.com/garrick8jackson/Lab--Analytic-Rules/blob/3ff0be8e2b31f5d8eadfd8d2ca27eaf2f0aec6e2/analytic%20rules%204.png)

In the set rule logic I checked the rule query to make sure it met my needs and used the “test with current data” feature to make sure it worked properly

![image alt](https://github.com/garrick8jackson/Lab--Analytic-Rules/blob/4ccd62a7e4f7bdc3b7e3572f578f8a78fdfd5999/analytic%20rules%205.png)

In the incident settings tab I made sure to enable alerts created by the analytics rule and grouped alerts to reduce the amount alerted.
