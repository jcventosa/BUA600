--- 
 Authors: Sinan Ozdemir, Jacob Deming, Hobert Bush
 Format: Jupyter Notebook
 Created: Q3 2019
 Revised: Q4 2020
--- 

# Airbnb Data - Marketing Assignment

> Requirements for Assignment 1

1. [Directions][1]
1. [Requirements][2]
1. [Due Date][3]
1. [Evaluation][4]

### Directions<a name="directions"></a>

In this assignment, you will work with sample Airbnb data looking at listings in San Francisco, CA from 2020. You'll be analyzing the data in order to glean insights into the short term rental market and inform real estate market trends.

***Expected Time to complete: 4 hours***


### Instructions<a name="instructions"></a>

1. Open the assignment notebook.
1. Save a copy of your notebook and retitle it “yourname\_assignment.ipynb”.
1. Attempt answers for all ***required*** questions. Include comments to explain your logic.
1. Submit your notebook to your instructional team by the due date. Include a public link to your file and add a brief description. 

---

### Requirements<a name="requirements"></a>


#### Objectives
This assignment will ask you to:

1. Read/write CSV files using Python's built-in `csv` module.
1. Clean and transform raw data from a csv into lists and dicts.
1. Use Python to filter out entries and match specific criteria.


#### Problem
Your goal is to perform some basic summary statistics on the data, looking to glean market insights and answer questions, such as: 

- What is the most frequently offered amenity?
- What is the average cost of listings that match specific consumer preferences?

As you navigate the notebook, you will see clearly labeled sections setting up questions for you to solve marked **required.** You will need to attempt answers for all of these **required** questions. Please include all work within your Jupyter notebook.

> Note: Some questions can be solved in multiple ways. Use comments to explain your code or logic!


#### Data
[Our data][5] is a truncated subset of data taken from [Inside Airbnb][6], including _required_ and _optional_ CSV data files: `listings.csv`, `calendar.csv`, and `airbnb_truncated.csv`.

Within our required file, **listings.csv**, you'll see seven columns:

- `id` - A unique identifier of the Airbnb
- `listing_url` - The URL to the Airnb
- `name` - The name of the listing
- `amenities` - A list of the amenities that the listing offers
- `price` - The nightly fee of the listing (before cleaning fees)
- `bedrooms` - The reported number of bedrooms
- `bathrooms` - The reported number of bathrooms

---

### Deadline<a name="deadline"></a>

|Session | Deadline
| -- | -- |
| Session 5 | **Airbnb Assignment Due**  |

---

### Evaluation<a name="evaluation"></a>

#### Requirements
- [ ] Complete all required questions
- [ ] Use comments to explain your code
- [ ] *Optional:* Attempt bonus and challenge questions for extra credit

#### Points Possible
This assignment consists of:

- 4 Required, Graded Questions
- 2 Optional, Bonus Questions
- 2 Optional, Challenge Questions (ungraded)

> Remember: You won't lose points for attempting bonus questions... but you can earn additional points! Bonus points add to your overall total; keep in mind that it is not possible to get *more* than the total number of points. 

<!--
#### Assessment

Our course uses the following assessment breakdown:
* **High Pass** = 85-100% of points possible
* **Pass** = 70-84% of points possible
* **Low Pass** = 50-69% of points possible
* **Fail** = Lower than 50%


For this assignment, student submissions will be graded accordingly:
- 21-24 = *High Pass*
- 16-20 = *Pass*
- 12-16 = *Low Pass*
- 11 or Under = *Fail*
-->

Note: 
- Failing assignments will get one attempt to revise and resubmit.

#### Grading Criteria
When evaluating your assignments, instructional teams will be looking at the following performance criteria:

- ***Clarity***: Deliverables clearly articulate the intended outcome - e.g. presentation communicates analysis and logic clearly, without typos.
- ***Accuracy***: Deliverables adhere to criteria and function correctly - e.g. correct syntax, without obvious bugs.
- ***Validity***: Deliverables are relevant to the intended goal - e.g. target answer is met or exceeded.

#### Scale
Instructional teams will use performance criteria to score each and every **required** component using the following scale:

Score | Description
\----- | ------------
**3** | _Demonstrates mastery: validity, accuracy, clarity_
**2** | _Demonstrates proficiency: validity, accuracy_
**1** | _Approaching proficiency: validity_
**0** | _Does not meet expectations: invalid, inaccurate, unclear, incomplete_


> Score allocation distributions are at the discretion of your instructional team and may be modified at any time.


#### Feedback
Instructional teams will grade student assignments by tallying points for each required question and providing a total score, along with feedback on code logic and quality.

<!--
#### Rubric

| **Topic** | **Incomplete (0)** | **Approaching (1)** | **Proficient (2)** | **Mastery (3)** |
| -- | -- | -- | -- | -- |
| Question 1  | Did Not Complete | 1 out of 3 (Valid) | 2 out of 3 (Valid, Accurate) | 3 out of 3 (Accurate, Valid, & Clear) |
| Question 2  | Did Not Complete | 1 out of 3 (Valid) | 2 out of 3 (Valid, Accurate) | 3 out of 3 (Accurate, Valid, & Clear) |
| Question 3  | Did Not Complete | 1 out of 3 (Valid) | 2 out of 3 (Valid, Accurate) | 3 out of 3 (Accurate, Valid, & Clear) |
| Question 4  | Did Not Complete | 1 out of 3 (Valid) | 2 out of 3 (Valid, Accurate) | 3 out of 3 (Accurate, Valid, & Clear) |
| Question 5  | Did Not Complete | 1 out of 3 (Valid) | 2 out of 3 (Valid, Accurate) | 3 out of 3 (Accurate, Valid, & Clear) |
| Question 6  | Did Not Complete | 1 out of 3 (Valid) | 2 out of 3 (Valid, Accurate) | 3 out of 3 (Accurate, Valid, & Clear) |
| Question 7  | Did Not Complete | 1 out of 3 (Valid) | 2 out of 3 (Valid, Accurate) | 3 out of 3 (Accurate, Valid, & Clear) |
| Question 8  | Did Not Complete | 1 out of 3 (Valid) | 2 out of 3 (Valid, Accurate) | 3 out of 3 (Accurate, Valid, & Clear) |
-->

> Bonus and challenge questions are optional and can be scored in the same manner. 

---

## Copyright
© 2020 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.

[1]:	#directions
[2]:	#requirements
[3]:	#deadline
[4]:	#evaluation
[5]:	./data/
[6]:	http://insideairbnb.com/get-the-data.html