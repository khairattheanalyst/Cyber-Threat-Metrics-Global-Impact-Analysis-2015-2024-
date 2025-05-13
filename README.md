![Cyber Threat Metrics and Global Impact Analysis Dashboard](https://github.com/user-attachments/assets/ece6d937-6e81-4a97-be80-376aaf4f2a55)

**INTRODUCTION**

In today’s digital world, cyber threats have become more frequent, sophisticated, and damaging. Organizations across industries are now facing growing pressure to protect their systems, data, and users from a wide range of cyberattacks. This analysis explores a comprehensive dataset that tracks global cyber threats between 2015 and 2024. The data reveals how attacks have evolved in frequency, scale, and complexity, while also highlighting the most targeted countries, industries, attack types, and vulnerabilities.

 

**Data Source:** The dataset used in this analysis is secondary data, obtained from compiled cybersecurity incident records and industry threat intelligence sources. It includes historical information on attack frequencies, affected users, financial losses, and security vulnerabilities across multiple sectors and regions from 2015 to 2024.

 

**DATA STRUCTURE**

1. File Format is CSV (Comma-Separated Values).

2. Data Type: Secondary data.

3. Time Span: 2015 to 2024 (10 years).

4. This dataset contains 3,002 columns and 10 rows.

 

**Data Limitations or Biases:** None

 

**INDUSTRY TYPE OF DATA**

This dataset falls under the Cybersecurity and Threat Intelligence industry, focusing on analyzing patterns in cyberattacks, vulnerabilities, defense mechanisms, and financial impacts across global sectors.

 

**STAKEHOLDERS OF THE PROJECT**

CISOs (Chief Information Security Officers) & IT Security Executives.

 

**WHAT SUCCESS MEANS TO THE INDUSTRY**

Success for CISOs and IT Security Executives means effectively identifying vulnerabilities and reducing risks through strategic security measures. The goal is also to maintain business continuity and also minimize financial or reputational damage during breaches. Finally, success in this industry is about building stakeholders confidence by demonstrating proactive, data-driven risk management and a robust cybersecurity approach.

 

**STEPS TAKEN TO CLEAN THE DATA**

1. I checked for and removed any duplicate records to ensure that each data entry was unique and accurate.

2. I removed any rows that were either completely blank or had critical missing values that could affect the analysis.

3. To improve visibility, I resized all columns to ensure the data was clearly displayed and easy to read.

4. I confirmed that all columns were properly labeled and made corrections where necessary to maintain clarity and consistency.

5. I applied a uniform font type and size, and used a clean color scheme for better readability and presentation. I also used all-round cell borders to help values stand out and make the spreadsheet more structured and professional.

6. I used the Find and Replace feature to quickly and effectively correct inconsistencies in formatting across the dataset.

7. I created a new column to represent financial loss values in millions of dollars for easier comparison and accurate interpretation.

8. I used conditional formatting to highlight key values such as high attack frequencies, losses, or vulnerabilities for visual impact and quick insights.

9. I added an appropriate and consistent header that defined the dataset's title and structure at a glance.

10. I checked that numerical values, dates, and text were in their correct formats and corrected any mismatches.

11. I ensured consistent naming for categories (i.e. country names, attack types) to avoid discrepancies during analysis.




**DATA SPLITTING**

The data columns were split into two categories. The Independent Category and the Dependent category. 

**Category One - The Independent Columns**

1. Country: The geographical region where the cyberattack occurred.

2. Year: Specific years when the incidents took place.

3. Attack Type: The type of cybersecurity threat (i.e. DoS, Malware, Phishing).

4. Target Industry: The industry targeted by the cyberattack (i.e. IT, Healthcare).

5. Attack Source:The origin of the attack (i.e. Hacker group, Insider source).

6. Defense Mechanism Used: The defense strategy implemented (i.e. Antivirus, VPN).

 

**Category Two - The Dependent Columns**

7. Financial Loss (in Million $): The total monetary loss due to cyberattacks.

8. Number of Affected Users: The number of individuals or systems affected by the cyberattack.

9. Resolution Time (in hours): The time taken to resolve the cyberattack.

10. Security Vulnerability Type: The specific vulnerabilities targeted by attackers (i.e. Zero-day, Unpatched Software).

 

**POTENTIAL ANALYSIS QUESTIONS**

Below are the core analysis questions designed to guide insights from the dataset. These questions focus on patterns, vulnerabilities, and the overall impact of cyberattacks across different countries and industries.

1. Which countries are most frequently targeted by cyberattacks?

2. How does the attack source affect financial losses and the resolution time for attacks?

3. Which years saw the largest spikes in cyberattacks, and what external factors contributed to these spikes?

4. What is the average financial impact of cyberattacks across industries, and which attack types cause the most significant losses?

5. What is the yearly trend of the number of affected users on an average?

6. What are the most common attack types (i.e. phishing, SQL injection) used across various industries?

7. Is there a correlation between quicker response times and lower financial impact or damage?

8. Which industries are most vulnerable to cyberattacks, and what types of attacks are they facing?

9. How do specific industries respond to different types of attacks, and what defense mechanisms are most effective?

 

**NOTABLE TRENDS AND PATTERNS FROM CHARTS ANALYSIS**

**Key Performance Metrics**

1. The United Kingdom was attacked the most times with a total attack frequency of 321 times.

2. China faced the fewest cyberattacks with a total attack frequency of 281 times.

3. Attacks from hacker groups led to the highest average financial loss at $51.75 million, and they also took the longest time to resolve (37.2 hours) on average.

4. Insider attacks led to the least average financial loss, but they still cause significant damage and also require more than 36 hours on average to handle.

5. In 2021, an average total of 519,204 users were affected by cyberattacks, making it the year with the highest users affected.

6. The year 2018 recorded the lowest average users affected, with 489,597 users affected by cyberattacks.

7. Zero-day security vulnerability type was the most targeted, with 785 incidents.

8. Weak passwords were the least targeted among the security vulnerability types, with 730 incidents, but is still a significant number.

9. 2019 had the lowest number of cyberattacks at 263 incidents. 

10. 2017 had the highest spike with 319 incidents, closely followed by 2022 with 318 incidents. This shows that these years experienced a surge in cyber threats.

11. The IT industry was attacked the most, with 478 incidents, showing it is a major target,  likely due to its central role in digital infrastructure and data handling.

12. Both the Government and Telecommunications sectors had the lowest number of attacks at 403 each, though still high, suggesting they face consistent but slightly lower threat levels compared to other industries.

13. The most used defense mechanism is the Antivirus defense mechanism and the highest financial loss over the years is in the IT industry with a total sum of $24,809,830,000.

 

**DATA-DRIVEN RECOMMENDATIONS ALIGNED TO STAKEHOLDERS NEED FROM THIS ANALYSIS**

1. The United Kingdom, Brazil, and India recorded the highest number of cyberattacks during the 10-year span, signaling a need for stronger national cybersecurity frameworks. These countries must improve early detection systems, information sharing, and cross-sector cooperation to better defend against frequent threats.

2. Attacks from hacker groups resulted in the highest average financial loss and took the longest time to resolve. Organizations should prioritize threat intelligence and incident response strategies that specifically target hacker group tactics, as these attackers often cause prolonged and costly disruptions.

3. Zero-day vulnerabilities, social engineering, and unpatched software were the most targeted security weaknesses. These threats succeed because they exploit unknown flaws, human error, or neglected system updates. Organizations must adopt proactive vulnerability management and user training to close these common gaps.

4. Insider attacks may not cost the most, but they still require long resolution times and can cause serious internal damage. Enhancing employee access control, monitoring, and awareness can reduce these risks and support quicker recovery when insider threats occur.

5. Some years showed clear spikes in cyberattacks, most notably 2017, 2022, and 2023. These trends highlight the importance of seasonal or annual threat monitoring, so cybersecurity teams can anticipate and prepare for increased activity during high-risk periods.

6. Antivirus and VPNs were the most used defense tools, with encryption, firewalls, and AI-based detection close behind. This shows that layered security, combining traditional and smart tools remains the most effective way to prevent, detect, and respond to attacks.

7. The IT, Banking, and Healthcare sectors were the most frequently targeted industries. These sectors manage large amounts of sensitive data, making them attractive to attackers. Investment in industry-specific defenses and compliance practices is crucial for reducing risk.

8. Phishing was a major threat, especially in Banking, IT, and Retail. User training and email filtering tools should be top priorities in these sectors. Blocking phishing attempts at the human level can significantly reduce attack success rates.

9. Weak passwords and unpatched software were among the most exploited vulnerabilities. Organizations should enforce strong password policies and automate software updates to reduce the chance of preventable breaches.

10. 2021 and 2022 recorded the highest number of affected users, meaning that the scale of impact is growing. Incident response plans must now include clear steps to protect and communicate with users when breaches occur.

11. Although Government and Telecommunications sectors recorded slightly fewer attacks than others, each still had over 400 incidents. These sectors must avoid complacency and maintain strong cybersecurity readiness to protect national infrastructure and communication systems.

12. Regularly reviewing cybersecurity data can help CISOs stay ahead of changing threats. Data-backed decisions will ensure resources are focused on the most urgent risks, from financial losses to user impact, helping to build a more resilient cybersecurity environment.

 

**CONCLUSION**

The analysis provided a detailed look into the state of cybersecurity threats between 2015 and 2024, highlighting patterns in attack frequency, financial losses, affected users, and industry-specific vulnerabilities. Working on this dataset gave me a deeper understanding of how complex and dynamic the cybersecurity landscape truly is. This was my first time exploring this niche, and it was both exciting and insightful to learn new terms and understand their relevance in real-world contexts. Although the process was very overwhelming and quite stressful, especially during the In-Analysis and Pre-Analysis stages, it was still a very rewarding experience that sharpened my data handling and analytical thinking skills.

**Read Full Report Here: https://medium.com/@Khairattheanalyst/cyber-threat-metrics-global-impact-analysis-2015-2024-2f47e322eeb2**
