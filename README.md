# Recruitment Data Analysis

This Jupyter notebook contains an analysis of recruitment data with 3,000 applicant records. The analysis explores various aspects of the applicant pool, including demographics, qualifications, application statuses, and salary expectations.

## Key Questions Addressed

1. **Applicant Demographics**
   - Total applicants: 3,000
   - Gender distribution: Male (1,030), Other (1,003), Female (967)
   - Age distribution by education level (average age ~41 across all education levels)

2. **Application Status**
   - Distribution: Applied (611), Offered (610), In Review (595), Rejected (594), Interviewing (590)
   - PhD applicant status: Applied (151), In Review (155), Interviewing (141), Offered (148), Rejected (146)

3. **Job Titles**
   - 636 unique job titles
   - Highest average desired salaries:
     - Radiographer, therapeutic ($99,803)
     - Logistics and distribution manager ($96,806)
     - Volunteer coordinator ($95,092)

4. **Experience and Salaries**
   - Weak correlation between years of experience and desired salary (r=0.027)
   - Average desired salary by experience ranges from $60,231 (5 years) to $68,673 (15 years)

5. **Geographical Analysis**
   - 2,709 unique cities represented
   - Most applicants from West Michael and Lake Christopher (6 each)

6. **Application Timing**
   - July had the highest number of applications

7. **Rejection Analysis**
   - "Community education officer" had the highest rejection rate
   - 150 applicants with >15 years experience were rejected

## Notable Findings

- Education level shows minimal impact on desired salary (all averages between $64,548-$65,481)
- The job title with the highest rejection rate is "Community education officer"
- Applicants with PhDs have a 19.97% offer rate, slightly below Master's degree holders (22.28%)
- The correlation between years of experience and desired salary is surprisingly weak (0.027)

## Data Preparation

The notebook includes data cleaning steps such as:
- Standardizing date formats for "Date of Birth"
- Calculating applicant ages from birth dates
- Extracting application months from application dates

This analysis provides valuable insights for HR professionals to understand applicant trends, optimize recruitment strategies, and make data-driven hiring decisions.
