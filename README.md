# Property_investment_in_Canada_in_relation_with_population_and_immigration
# Analysis introductory
Canada's housing market is a dynamic landscape shaped by a multitude of factors, from economic trends to population dynamics. In this analysis, we delve into a critical question facing potential investors and policymakers alike: Where should investments be directed within Canada's diverse regions? Our focus lies at the intersection of housing prices, population trends, and immigration patterns, seeking to uncover meaningful insights that can guide strategic decision-making.

As regions across Canada experience varying levels of economic growth, demographic shifts, and policy developments, understanding the relationship between housing prices and factors such as population growth and immigration becomes paramount. Our analysis aims to not only identify these connections but also to shed light on potential investment opportunities that arise as a result.

# Data source
* [New housing price index, monthly](https://open.canada.ca/data/en/dataset/324befd1-893b-42e6-bece-6d30af3dd9f1) - Housing price index month over month, which ever available, from January 1981 to July 2023. This data using base period for index is 201612=100, or the hosing price index in December 2016 is 100 as the base.

* [Global population growth](https://data.worldbank.org/indicator/SP.POP.GROW?locations=CA) - this data has population growth for every country in the world year over year from 1961 to 2022.

* [Permanent Residents by provinces/territory and immigration catergory](https://open.canada.ca/data/en/dataset/f7e5498e-0ad8-4417-85c9-9b8aff9b9eda) - showing the number of PR in different provinces/territory and immigration categories. Number has been rounded to prevent comparision and indentification. Value between 0 and 5 are shown as "--", and all other are rounded to nearest multiple of 5. Time frame from 2015 to 2022.

* [Study permit holders - Monthly IRCC updates](https://open.canada.ca/data/en/dataset/90115b00-f9b8-49e8-afa3-b4cff8facaee) - Assuming this should match the number of international students who require to have a valid study permit to study in Canada, from 2000 to 2022.

* [Work permit holders - Monthly IRCC updates](https://open.canada.ca/data/en/dataset/360024f2-17e9-4558-bfc1-3616485d65b9) - Number of people who are under Temporary Foreign Worker Program in Canada, from 2000 to 2022.

* [Population in different province in Canada](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1710000901&cubeTimeFrame.startMonth=01&cubeTimeFrame.startYear=1981&cubeTimeFrame.endMonth=04&cubeTimeFrame.endYear=2023&referencePeriods=19810101%2C20230401) - This data gives us the population by provinces from 1981 to June 2023

# Data licensing
[Open Government License - Canada](https://open.canada.ca/en/open-government-licence-canada)
You are encouraged to use the Information that is available under this licence with only a few conditions.

**Using Information under this licence:**
* Use of any Information indicates your acceptance of the terms below.
* The Information Provider grants you a worldwide, royalty-free, perpetual, non-exclusive licence to use the Information, including for commercial purposes, subject to the terms below.

**You are free to:**
*Copy, modify, publish, translate, adapt, distribute or otherwise use the Information in any medium, mode or format for any lawful purpose.

**You must, where you do any of the above:**
* Acknowledge the source of the Information by including any attribution statement specified by the Information Provider(s) and, where possible, provide a link to this licence.
* If the Information Provider does not provide a specific attribution statement, or if you are using Information from several information providers and multiple attributions are not practical for your product or application, you must use the following attribution statement:
Contains information licensed under the Open Government Licence – Canada.

The terms of this licence are important, and if you fail to comply with any of them, the rights granted to you under this licence, or any similar licence granted by the Information Provider, will end automatically.

**Exemptions**
This licence does not grant you any right to use:
* Personal Information;
third party rights the Information Provider is not authorized to license;
the names, crests, logos, or other official symbols of the Information Provider; and
* Information subject to other intellectual property rights, including patents, trade-marks and official marks.
Non-endorsement
* This licence does not grant you any right to use the Information in a way that suggests any official status or that the Information Provider endorses you or your use of the Information.

**No Warranty**
The Information is licensed “as is”, and the Information Provider excludes all representations, warranties, obligations, and liabilities, whether express or implied, to the maximum extent permitted by law.

The Information Provider is not liable for any errors or omissions in the Information, and will not under any circumstances be liable for any direct, indirect, special, incidental, consequential, or other loss, injury or damage caused by its use or otherwise arising in connection with this licence or the Information, even if specifically advised of the possibility of such loss, injury or damage.

**Governing Law**
This licence is governed by the laws of the province of Ontario and the applicable laws of Canada.

Legal proceedings related to this licence may only be brought in the courts of Ontario or the Federal Court of Canada.

**Definitions**
In this licence, the terms below have the following meanings:

Information
means information resources protected by copyright or other information that is offered for use under the terms of this licence.
Information Provider
means His Majesty the King in right of Canada.
Personal Information
means “personal information” as defined in section 3 of the Privacy Act, R.S.C. 1985, c. P-21.
You
means the natural or legal person, or body of persons corporate or incorporate, acquiring rights under this licence.

**Versioning**
This is version 2.0 of the Open Government Licence – Canada. The Information Provider may make changes to the terms of this licence from time to time and issue a new version of the licence. Your use of the Information will be governed by the terms of the licence in force as of the date you accessed the information.

[Open Government License Consultation Report](https://open.canada.ca/en/open-government-licence-consultation-report)

# Limitations
**Data has been modified** to avoid comparison and identification in the number of Permanent residents, value in this dataset also got modified if it small (0 to 5). However, since the difference is small, but it is a good proxy for the analysis.

**Various time frame** in different dataset, so we will have to limit the analysis from 1981 to 2022.
