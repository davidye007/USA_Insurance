# United States Insurance Visualization & Analysis
STAT 451 Final Project on United States Insurance

Authors: David Ye & Kreslyn Hinds

Dataset #1:
[Insurance Dataset from the U.S. Census Bureau](https://www2.census.gov/programs-surveys/demo/tables/health-insurance/time-series/acs/hic05_acs.xlsx)

Question(s):
1) How does heath insurance enrollment vary by state?

2) Does heath insurance enrollment rate and main insurance type change based on a state's political affiliation?

3) Does healthcare enrollment change with presidential shifts?

Data set explanations for each column:

State: All 50 states in the United States, plus United States (representing the whole of the U.S.), and the District of Columbia.

Year: The year the data was collected for/in. The data set starts with year 2008 and ends in 2022.

InsuranceType: Type of insurance a subgroups of the population has, excepting Total, Any Coverage and Unisured, definitions for each insurance type comes from (https://www.census.gov/topics/health/health-insurance/about/glossary.html#par_textimage_18)

  Total = Doesn't matter what insurance type, the row is used to represent a state's total population for each given year.

  Any Coverage = People having any type of insurance coverage.

  Uninsured = People without insurance coverage.

  Private = Private health insurance is a plan provided through an employer or union; a plan purchased by an individual from an insurance company; or TRICARE or other military health coverage.

  Employer-based: A coverage offered through one's own employment or a relative's. It may be offered by an employer or by a union.

  Direct-purchase:Is purchased directly from an insurance company by an individual or an individual's relative.

  TRICARE: A military health care program for active duty and retired members of the uniformed services, their families, and survivors.

  Public: Public coverage includes the federal programs Medicare, Medicaid and other medical assistance programs, VA and CHAMPVA Health Care; the Children’s Health Insurance Program (CHIP); and individual state health plans.

  Medicaid: Any kind of government-assistance plan for those with low incomes or a disability.

  Medicare:A Federal program which helps pay health care costs for people 65 and older and for certain people under 65 with long-term disabilities.

  VA Care:A Department of Veterans Affairs program that provides medical assistance to eligible veterans.       

Population: Number of people matching the State, Year and InsuranceType.

Percentage: Population from current row divided by population from Total (InsuranceType), whose state and year match the current row's state and year.

