**Project Overview**

This analysis examines web traffic information of *lacity.gov*, the official website of the City of Los Angeles, from the years 2014 to 2019. The dataset is made up of over 8 million records and contains valuable data concerning user behavior and trends in engagement as well as devices’ used. The goal was to produce specific guidelines that increase user engagement, streamline site efficiency, and enhance communication—and in particular during events such as natural disasters such a thing is highly necessary.

As the site is vital to enabling residents to receive current information and services, understanding user habits is vital for better access, interaction, and preparedness during crises.

**Key Definitions**

* **Sessions**: A visit to the website where everything a user does during that session has been registered.
* **Bounce Rate**: The number of sessions in which users arrived at the site and then left in the clicking of a button without further session activity.
* **Device Categories**: The various devices used by the users – particularly, desktop, mobile and tablet.

---

**Executive Summary**

Using a dataset of over 8 million web sessions, this analysis explores trends for bounce rate, device utilized and total visits to the website between 2014 and 2019. SQL was used on the data and a Tableau dashboard was built to represent important metrics in graphics.

Findings indicate:

Desktops are still the main device used as 66% drive the sessions.
Mobile devices are second in usage but have the highest bounce rate, numbers are approximately 6% higher than desktops.
● Tablets have the smallest number of traffic but have somewhat better bounce rate than mobile devices.

Usually, the weekdays traffic is higher than weekends and a notable increase in the December 2017, probably due to the California wildfires, highlight the trust in the site during incidences of urgency. However, it is important to note that an obvious reduction in traffic from the year 2017 to the year 2019 is the subject for further analysis.

---
**Detailed Insights**

**Device Usage**

* **Desktop**: Is the major source of traffic so browser performance and compatibility are the most important.
* **Mobile**: In busy periods, mobile devices comprise 46% of all traffic with the highest bounce rate, indicating accessibility problems or usability issues.
* **Tablet**: In spite of having its lowest traffic percentage, tablet users have a tendency of engaging more consistently than mobile visitors.

**Browser Patterns**

* **Chrome** leads desktop sessions.
Safari is the dominant browser used on mobile and tablets.
Mobile browsers that are in-app like Safari in-app and the Android Browser have a major effect on bounce rates.

**Traffic Trends**

*** Engagement during working days indicates that it is most effective to release updates and start new campaigns on those days.
The spike in December 2017 is tied to wildfire events, and highlights the site’s importance for crisis communication.
Changes in user behavior or environmental factors that influence usage may be indicated by traffic loss between 2017 and 2019.

---

**Recommendations**

1. **Crisis Communication Strategy**
   Improve mobile access and interface to facilitate an efficient flow of important messages during emergencies taking advantage of increased mobile traffic at such times.

2. **Focus Weekday Engagement**
   Suggest updates and go on marketing runs during weekdays, working with the most popular user engagement hours. Process maintenance and performance upgrades at calmer weekend periods to reduce inconveniences to users.

3. **Mobile Optimization**
   Optimize the presentation of content and way of accessing it on mobile platforms so that the number of visitors who quickly leave the site gets reduced. Simplify the process by collecting and applying input from users in designing.

4. **Desktop Experience Maintenance**
   Deliver outstanding performance and browser compatibility in desktop platforms with a strong focus on how Chrome browser performs.

5. **Investigate Traffic Decline**
   Participate in surveys and research undertakings to get enlightenment on the drivers of the downward trend in traffic from 2017-2019. This method will allow us to identify usability problems or content inadequacies or changes in the needs for public information.


**Assumptions and Limitations**

The higher amount of traffic seen on the web during the month of December 2017 is believed to be attributed to wildfires, although several other causes are also possible.
Here only data up until 2019 has been included in the analysis. subsequent trends are not reflected.
Bounce rate measurement is based on available session data that may not entirely track every user’s engagement.

**Technical Details**

The founding dataset gives records for unique visitors, sessions, and bounce rates on the *lacity.gov* site (from 2014 to 2019). The data was cleaned and transformed using SQL. You can find the transformation script here. End visualizations created in Tableau may be checked out on the **LAcity.org Web Traffic Dashboard**.

Browse my \[Portfolio] to gain access to other work, including this visualization.