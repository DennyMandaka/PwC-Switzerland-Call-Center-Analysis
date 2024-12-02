# PwC-Switzerland-Call-Center-Analysis
## Project Objective 
This project is part of a Job Simulation Program by PwC Switzerland, designed to replicate real-world business scenarios. The program provided a hands-on opportunity to analyze call center data, develop insights, and create an interactive Power BI dashboard. By tackling a practical task focused on telecom industry KPIs, this simulation enhanced my technical, analytical, and problem-solving skills, closely mirroring the demands of a professional role in business intelligence and data analytics.

## Approach and Execution
Step 1: Data Preparation
- Ensured consistent formatting for dates, times, and numeric values.
- Verified that all calls had corresponding agents and removed duplicate entries based on Call ID.
- Left blanks in columns such as Speed of Answer, AvgTalkDuration, and Satisfaction Rating to accurately represent "no data available" for unanswered calls.
- Resolved a formatting issue in the AvgTalkDuration column by converting it from h:mm:ss Duration Format to General Number Format, ensuring compatibility with Power Query.
- Double-checked data types in Power Query to ensure consistency across columns (e.g., Date, Time, Duration).

Step 2: Data Transformation
- Added a New "Answered Status" column by using a combination of IFS, AND, NOT, and ISNUMBER functions to clarify whether a call was answered or not.
- Developed DAX measures and calculated columns to calculate KPIs such as Total Calls Answered, Average Speed of Answer, and Agent Performance.
- Frequently used FILTER and COUNTROWS functions in DAX for this purpose.
  
Step 3: Visualization and Dashboard Creation
- Created charts and visualizations to display key metrics such as call volume by time period, agent performance, satisfaction ratings, and unresolved calls.
- Added slicers to enable dynamic filtering by date, agent, and time period, allowing users to explore specific trends.
- The interactive report pages in Power BI appear as shown <a href="https://github.com/DennyMandaka/PwC-Switzerland-Call-Center-Analysis/blob/main/PwC%20Call%20Center%20Analysis.png">here</a>. The complete Power BI file can be accessed <a href="https://github.com/DennyMandaka/PwC-Switzerland-Call-Center-Analysis/blob/main/PwC%20Call%20Center%20Analysis.pbix">here</a>.
## Insights and Conclusion
- This project deepened my understanding of identifying and analyzing Key Performance Indicators (KPIs) in a practical business context. By working with data related to agent performance, call outcomes, and customer satisfaction, I learned how these metrics contribute to strategic decision-making in the telecom industry.
- Handling real-world datasets emphasized the importance of thorough data cleaning and validation. Resolving formatting issues, dealing with missing data, and ensuring consistency enhanced my attention to detail and problem-solving skills.
- o	Developing the Power BI dashboard honed my skills in creating interactive and user-friendly visualizations. It also highlighted the importance of tailoring insights for stakeholders, ensuring that the output is actionable and accessible.
