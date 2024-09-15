# Phishing Campaign Dashboard using Power-BI

## Introduction 

Phishing is an example of a highly effective form of cybercrime that enables criminals to deceive users and steal important data. (Zainab Alkhalil, 2021) To combat this growing issue, organizations must employ comprehensive and effective strategies. Attacks are reported each year, and a reduction in the number of such attacks is unlikely to occur in the near future. (Jampen, 2020) Simulated phishing campaigns are a powerful tool to assess and enhance an organization's resilience to these threats. This report introduces three specialized BI dashboards designed to provide valuable insights into simulated phishing campaigns, targeting distinct user groups: Phishing Campaign Managers, Individual Users, and HR Managers.
These dashboards offer a detailed analysis of campaign performance, user behaviour, and employee susceptibility, enabling stakeholders to identify weaknesses, tailor training programs, and implement targeted interventions. By leveraging these insights, organizations can significantly strengthen their cybersecurity defences and foster a culture of awareness and vigilance.

## Objectives 

### Campaign Manager

•	Gain a comprehensive understanding of campaign effectiveness by analysing user behaviour and key metrics.

•	Identify trends and vulnerabilities in user behaviour to optimize future campaign design and training strategies.

•	Evaluate the performance of different email templates, attachment types, and campaign themes to refine future campaigns for maximum impact.

### User

•	Raise individual awareness and understanding of phishing tactics through data visualization of user behaviour and campaign results.

•	Identify areas for personal improvement in recognizing and reporting phishing attempts.

•	Encourage a culture of cybersecurity vigilance within the organization.

### HR Manager

•	Pinpoint high-risk departments and employee groups most susceptible to phishing attacks based on various factors.

•	Develop targeted phishing awareness training programs to address specific departmental and individual needs.

•	Inform data-driven decisions regarding disciplinary actions and interventions for phishing incidents.

## Benefits/Advantages 

1. Comprehensive Analysis:
•	Benefit: Provides a holistic view of phishing campaign performance and user behaviour.
•	Advantage: Enables stakeholders to make informed decisions based on detailed and actionable insights.
2. Targeted Training Programs:
•	Benefit: Identifies specific vulnerabilities and risk factors among different user groups.
•	Advantage: Allows for the development of customized training programs that address the unique needs and weaknesses of each group, enhancing overall effectiveness.
3. Improved Cybersecurity Posture:
•	Benefit: Helps reduce the success rate of phishing attacks through continuous monitoring and improvement.
•	Advantage: Strengthens the organization's cybersecurity defences, protecting sensitive information and reducing the risk of data breaches.
4. Enhanced Reporting and Accountability:
•	Benefit: Tracks and reports on key metrics such as attachment click rates, email template performance, and regional susceptibility.
•	Advantage: Facilitates accountability and transparency in cybersecurity efforts, allowing for more effective management and oversight.
5. Proactive Risk Management:
•	Benefit: Assesses and categorizes employee risk levels based on their behaviour and history.
•	Advantage: Enables HR Managers to proactively address high-risk areas through targeted interventions, reducing the likelihood of successful phishing attacks.
6. Encourages a Culture of Vigilance:
•	Benefit: Promotes awareness and education among all employees about the dangers of phishing.
•	Advantage: Fosters a workplace culture where employees are more vigilant and proactive in reporting and responding to phishing attempts.

## BI Dashboards 

### Campaign Manager  

https://app.powerbi.com/groups/c7c84cba-d7bd-4f84-ba7b-8ccb030a0eea/reports/1335ab95-1d6b-445b-b969-bf4ec4a5f75b/e9d9aa7d173a6844c0e4?bookmarkGuid=2593ea64-940d-4506-9314-1ffb9afed311&bookmarkUsage=1&ctid=d02378ec-1688-46d5-8540-1c28b5f470f6&portalSessionId=0fedd246-c331-4590-8cac-19ce3272d57d&fromEntryPoint=export

Figure 1 allows the manager to analyse the effectiveness of recent simulated phishing campaigns. This dashboard offers a centralized view of key metrics.

1.	Attachment Click Rates: Identify which attachment types are most likely to be clicked by users. This information can be used to tailor future campaigns and user training to address specific attachment risks.
2.	Campaign Reporting: Analyse which campaigns generated the highest number of reported phishing attempts. This allows for closer examination of these campaigns and potential adjustments to content or tactics to minimize the likelihood of users falling victim in real-world phishing attempts.
3.	Dissecting Email Template Performance: Analyse which email templates are most likely to result in user clicks. This data can inform future template design and messaging strategies to minimize user vulnerability.
4.	Overall Campaign Performance: Evaluate the overall effectiveness of your campaign, from the total number of emails sent to successful login attempts on phishing pages.
5.	Regional Performance: Compare the success rates of phishing campaigns across different regions within your organization. This can help identify areas requiring more targeted training or awareness initiatives.

![image](https://github.com/user-attachments/assets/c66884c0-413b-4177-acee-f1a47dd500ce)

Figure 1 Campaign Manager Dashboard

![image](https://github.com/user-attachments/assets/c1a2ea79-43c9-42ea-bf71-03b8ae5f9104) 

Figure 2 Links Clicked by Attachment Type

Figure 2 shows the percentage of links clicked for different attachment types. Based on this chart, Excel Files and Word Doc attachments have the highest percentage of links clicked (around 22% each). This suggests that users are more likely to click on emails with these attachment types.  This might be due to trust in familiar file types: Excel files and word files are a common file type used in many workplaces, so users might be less suspicious of an email containing one.

![image](https://github.com/user-attachments/assets/ef000de2-f3b1-4a35-bfa6-5ab0d4911837)  

Figure 3 Links Clicked by Emal Template 

Figure 3 shows the number of links clicked by email template. It shows that Promotional offer has the highest number of links clicked, followed by Security Alert, Shipment update, Account update and Renew Subscription.
Here are some explanations for this finding:
•	Promotional Offers: People are generally receptive to promotions and discounts, so they might be more likely to click on a link to learn more.
•	Security Alerts: Security alerts can be alarming, and users might click on a link out of concern or fear of negative consequences if they don't.
•	Shipment updates: Emails with shipment updates might be expected by users, so they might be more likely to click on links to track their packages.
•	Account Update: Emails providing account information updates might be less likely to contain attention-grabbing elements or calls to action, resulting in fewer clicks.
•	Subscription renewals: Subscription renewal emails might be seen as routine by users, making them less likely to click on links.

![image](https://github.com/user-attachments/assets/fac29bd3-718c-4539-a26a-ab6e210d5e3c)

Figure 4 Successful Logins by Target Region

Figure 4 compares the number if successful logins across five different regions: Australia, South America, Europe, Asia, and North America. Australia has the highest number of successful logins. This suggests that users in Australia may be more susceptible to phishing attacks compared to other regions and need more training. North America has the lowest value in the metric. This indicates that users in North America are less likely to fall victim to phishing attacks.
Possible explanations for the trends:
•	Regional Spam Filters: Some regions might have stricter spam filters that prevented some phishing emails from reaching users' inboxes.
•	User Awareness: Users in some regions might be more aware of phishing scams and thus less likely to click on links or enter credentials.

![image](https://github.com/user-attachments/assets/92f2e3e8-5448-4c89-8997-80f406b7f1d1)
 
Figure 5 Reported Emails by Campaign Name  

Figure 5 shows the number of emails reported as phishing attempts for various campaigns. Cyber week has the greatest number of reported emails followed by Cyber Monday, Fall Fashion and Black Friday. Spring Cleaning has the least number of reported emails followed by Summer Blowout and Summer Sale.
This might be due to the following reasons. 
•	User Awareness: Users might be more familiar with common phishing tactics associated with certain sales periods, like Black Friday or Cyber Monday. 
•	Campaign Timing: Campaigns sent closer to holidays or shopping seasons (like Cyber Week or Black Friday) might have grabbed more attention. People are more likely to be on the lookout for phishing scams during these times because they expect a higher volume of legitimate emails from retailers.
•	Lower Attention: Spring Cleaning and Summer promotions might be less attention-grabbing compared to campaigns like Cyber Week, Black Friday, or Fall Fashion.

### For User 

https://app.powerbi.com/groups/c7c84cba-d7bd-4f84-ba7b-8ccb030a0eea/reports/f71331b0-608d-4401-b469-3772ecf18aa6/1950364690ebc7750706?bookmarkGuid=f01bb787-f2ce-4c57-966f-f7ce8739fee1&bookmarkUsage=1&ctid=d02378ec-1688-46d5-8540-1c28b5f470f6&portalSessionId=0fedd246-c331-4590-8cac-19ce3272d57d&fromEntryPoint=export

Figure 6 provides insights into the results of simulated phishing campaigns conducted across the United States. This dashboard offers a centralized view of key metrics:
1.	Process of Phishing outlines the phishing attack stages, showing a significant portion of users falling for the scam, underlining the urgency for enhanced training.
2.	Average Risk Score by Demographic highlights states with varying levels of phishing awareness, with states.
3.	Counts of Links Clicked by Age Group reveals that which age group is most likely to click phishing links.
4.	Percentage of Links Clicked by Gender provide insights into gender-based differences in phishing susceptibility.
5.	Key Influencers for Reporting Phishing demonstrates the effectiveness of anti-phishing training.
6.	Average Previous Incidents by Reported Phishing indicates that users who do not or do not report phishing have a higher or low number of previous incidents.

![image](https://github.com/user-attachments/assets/c1580abf-809a-4137-95ee-592c3ea5224d)
  
Figure 6 Individual User Dashboard 

![image](https://github.com/user-attachments/assets/db3026b1-5347-4b2d-b0c8-04fdf592e640)

Figure 7 Average Risk Score by Demographic 

Figure 7 shows the average risk score by state in the US. States shaded in blue have a lower average risk score than the states shaded in red. Florida, Ohio and Arizona have a higher average risk score. North Carolina, Pennsylvania and Illinois have a lower risk score. This indicates in offices in states like Florida, Ohio and Arizona, employees are less aware of the dangers of phishing attacks may have a higher risk score. There should be more focused training in these states.

![image](https://github.com/user-attachments/assets/2dd7dcb1-3f41-4271-a17d-fefce2ebd104)
 
Figure 8 Counts of links clicked by age group.

Figure 8 shows the percentage of users who clicked on a link or not, broken down by age group. Users in the 20-30 age group are most likely to click the link. Users in the 50-60 age group are least likely to click the link for a phishing attempt.
There are a few reasons why younger users might be more likely to click on links in phishing emails.
•	Less familiarity with phishing scams: Younger users may be less familiar with phishing scams and may be more trusting of emails that appear to be legitimate.
•	More tech-savvy: Younger users may be more tech-savvy and may be more likely to click on links without thinking about the potential risks.

![image](https://github.com/user-attachments/assets/d466782d-b095-4e6f-aa78-7e1a809d58b3)
 
Figure 9 Percentage of Users by gender

Figure 9 shows the distribution of users by gender who participated in the campaign. There are slightly more males (54%) than females (46%) users.

![image](https://github.com/user-attachments/assets/0b542265-22e2-4f17-9249-c48763ea78aa)

Figure 10 Percentage of links clicked by gender.

Figure 10 shows the percentage of users who clicked the link or not by gender. Females are much more likely to click on the link even though men have a larger overall sample size as seen in Figure 9. There are several possible reasons for this, such as:
•	Women may be more likely to click on links in emails, especially if the email appears to be from a legitimate source.
•	Phishing emails often use social engineering tactics to trick users into clicking on links. These tactics may be more effective on women than men.

![image](https://github.com/user-attachments/assets/8f0aa218-b15d-468a-9c53-221e0d5285dd)
 
Figure 11 Process of Phishing 

Figure 11 gives an overview of the process of phishing attacks.
1.	Email Opened: 38 employees opened the email.
2.	Link Clicked: 21 people clicked on the link that takes the victim to a fake website.
3.	Credentials Entered: 13 people entered their details credentials (username and password). 
The campaign was able to get the credential of 26% of participants in the campaign which is an alarming situation.

![image](https://github.com/user-attachments/assets/d9c2e9a5-0a50-44e4-a5b5-2b49cd9132fc) 
 
Figure 12 Key Influencer for Reporting Phishing 
Figure 12 suggests that users who have completed the anti-phishing training are 5.08 times more likely to report a phishing attempt compared to users who haven't completed the training. Anti-phishing materials could be improved but they are surprisingly effective when users actually read them. (Lorrie Cranor, 2010)

![image](https://github.com/user-attachments/assets/95241ab4-4b6e-4a07-8016-392c92a7a28b)

Figure 13 Average Pervious Incidents by reported phishing. 

Figure 13 displays the average number of previous phishing incidents users have been involved in, broken down by whether they reported the current phishing attempt. This indicate that users who did not report have a higher average number of previous phishing incidents as well. Users who have been involved in more phishing incidents are still not aware of the tactics used by phishers and are unable to spot them repeatedly. 
 	 
### For HR Manager 

https://app.powerbi.com/groups/c7c84cba-d7bd-4f84-ba7b-8ccb030a0eea/reports/604fd707-fabc-4ac9-9284-d5f54a5b2a9d/a30d7ce30e153ec6374a?bookmarkGuid=c49d1ba8-db02-4fce-8d9e-4833342b9cb5&bookmarkUsage=1&ctid=d02378ec-1688-46d5-8540-1c28b5f470f6&portalSessionId=0fedd246-c331-4590-8cac-19ce3272d57d&fromEntryPoint=export

This HR dashboard provides insights that can be used to identify high-risk departments and employees, allowing for targeted training and interventions to strengthen the organization’s cybersecurity posture. This dashboard offers a centralized view of key metrics.
•	Employee Risk Level: The dashboard segments employees by risk level (High, Moderate, Low) based on a combination of factors including department, previous incidents, and training completion. Disciplinary Actions: The dashboard shows the distribution of disciplinary actions taken in response to phishing incidents (None, Verbal Warning, Written Warning). 
•	Department Risk: The dashboard allows you to see the number of employees by department and risk level. 
•	Training Completion: The dashboard allows to determine what influences anti-phishing training completion rate.
  

 ![image](https://github.com/user-attachments/assets/6569c8fc-3add-43c9-8ac3-bc375397c315)
 
 Figure 13 HR Manager Dashboard 
 
 ![image](https://github.com/user-attachments/assets/a82a9aee-59a9-49e2-a9a7-b7b7f0a98973)
 
Figure 14 Number of Employees by risk level and department 

Figure 14 shows the number of employees in each department categorized by their risk level. The department with the most employees overall is Finance (12 employees), but also has the most high-risk employees (9). IT has the second most employees (12) with a more even distribution across risk levels (4 low risk, 6 moderate risks, and 2 high risk). Here are some additional insights you can glean from the data:
•	Employees in Finance are more likely to be categorized as high risk.
•	There are more employees in low-risk categories than moderate or high-risk categories.

![image](https://github.com/user-attachments/assets/97eaa48c-c5b7-44c3-8da1-1f0e44f23b70)
 
Figure 15 Number of Employees by Disciplinary Action

Figure 15 shows the number of employees by disciplinary action after successful phishing. No action has been taken for most employees for failing the training. Action should be me made mandatory for all employees so that there is higher attention to phishing emails.

![image](https://github.com/user-attachments/assets/0fe04bfa-f346-4b48-8736-06c6eaf258fb)
 
Figure 16 – Sum of previous incidents by job level

Figure 16 shows the total number of previous incidents for all employees in that job level. Analysts have the highest number of previous incidents followed by accountants, auditors and managers. More focus should be put on these job levels as they are more prone to fall for phishing emails. Managers have more responsibility for training others about cybersecurity best practices, so they may be held to a higher standard.

![image](https://github.com/user-attachments/assets/c7da03a9-48f3-45af-9395-5ef2f8bd3c1c) 

Figure 17 Key Influencers – Risk Level

Figure 17 is showing two of the biggest factors that contribute to an employee completing the training. The factors are:
•	Average Salary: Employees with a salary in the range of 50,000 to 65,000 are 7.25 times more likely to have completed the training.
•	Years of Experience: Employees with a lower maximum number of years of experience (less than 2.68) are 2.37 times more likely to have completed the training. 
Training completion should be made mandatory.

![image](https://github.com/user-attachments/assets/e0b81084-2636-4fde-8c76-ae9a007eece4)
 
Figure 18 Risk Level by Job Level  
 
Figure 18 shows the distribution of risk levels across different job titles. The chart shows that Accountants, Auditors, and Analysts are all categorized as having majority high risk employees in this phishing campaign. These roles might involve working with external parties or opening attachments more frequently, increasing the likelihood of encountering phishing attempts. Privileged users are one of the top targets for spear phishing attacks because of their access to sensitive information. (Anand, 2024)

## Recommendations 

### Campaign Manager

1.	Improve Training on High-Risk Attachments
Issue: The dashboard shows that Excel files and Word documents have the highest link-click rates.
Recommendation: Implement targeted training programs focusing on the dangers of opening attachments, particularly Excel and Word files, within phishing emails. Provide examples and simulations to help users recognize suspicious attachments. (Verizon, 2024)

2.	Customize Campaigns Based on Template Performance
Issue: Promotional offers and security alerts have the highest number of link clicks.
Recommendation: Design and deploy additional training that includes mock phishing emails using these templates. Emphasize the tactics often used in these types of emails and educate users on how to spot red flags.

3.	Enhance Regional Training Initiatives
Issue: Australia has the highest number of successful logins, indicating higher susceptibility.
Recommendation: Conduct region-specific training sessions, particularly in regions with higher phishing success rates. Tailor content to address regional behaviours and common phishing tactics relevant to that area.

### User

1.	Focus Training on High-Risk Age Groups
Issue: Users in the 20-30 age group are most likely to click phishing links.
Recommendation: Develop age-specific training programs that address the unique online behaviours and susceptibilities of younger users. Incorporate interactive and engaging methods to ensure better retention of information.

2.	Address Gender-Specific Susceptibility
Issue: Females are more likely to click on phishing links compared to males.
Recommendation: Create awareness campaigns that consider gender-specific factors. Use data to inform training content and focus on scenarios where women might be more targeted.

3.	Implement Continuous Awareness Programs
Issue: Users who have completed anti-phishing training are significantly more likely to report phishing attempts.
Recommendation: Make anti-phishing training mandatory and recurring. Ensure all employees undergo regular refresher courses to stay updated on the latest phishing tactics and best practices for avoiding them.

4.	Reinforce Reporting Mechanisms
Issue: Users with a higher number of previous incidents are less likely to report phishing.
Recommendation: Simplify and promote the process of reporting phishing emails. Encourage a culture of vigilance and reward users who consistently report phishing attempts to improve overall awareness and responsiveness.

### HR Manager

1.	Target High-Risk Departments with Intensive Training
Issue: Finance and IT departments have a higher number of high-risk employees.
Recommendation: Implement focused training programs for high-risk departments, emphasizing the specific phishing threats relevant to their roles. Some visual deception attacks can fool even the most sophisticated users. (Dhamija, 2006)

2.	Enforce Disciplinary Actions and Remedial Training
Issue: Not all employees receive disciplinary actions for falling for phishing attempts.
Recommendation: Establish a clear policy for disciplinary actions and ensure it is consistently enforced. Mandate remedial training for employees who fall victim to phishing to reduce future risk.

3.	Address Key Influencers of Risk
Issue: Higher salaries and more years of experience are linked to increased phishing risk.
Recommendation: Investigate the reasons behind this correlation. Consider integrating phishing awareness and cybersecurity training into the onboarding process for new hires and regular training sessions for all employees, regardless of tenure or salary.

4.	Monitor and Review Training Effectiveness
Issue: Employees with fewer years of experience are more likely to complete training.
Recommendation: Regularly review and update training materials to ensure they are engaging and effective for all employees. 
