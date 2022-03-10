# EMF - Engineering take-home task
This task is designed for Technical Engineering roles at the Ellen MacArthur Foundation.

We created this to give you an insight into the kind of work you will be doing at EMF, and to give us an idea of your technical (and non-technical) skills. We're interested in the way you approach problems, but also in your code style and the structure to your solutions.  You may complete these tasks in Python only.

We expect this challenge to take 1-3 hours, should you find it taking significantly longer, please submit what you have - we are not looking for perfection. If you have any queries please reach out to us.

## Instructions
You can use this repository as a basis for completing the tasks, however, first you will need to create a copy of it, so that you can push your changes to it:
1. Clone this repository
2. Create a new private repository in your personal GitHub account
3. Push the cloned repository to your newly created repo (You will need to first remove the original origin with `git remote remove origin`, and add your new one `git remote add origin <url-to-your-repo>`)

Please commit **all** work to this repository, and all work must be on the `main` branch when you submit - we will only look at `main`. 
Again, please only use Python (version 3.6 and above). 
You do not need to provide instructions for running the code, only the code itself and the answers to the tasks.

All answered should be submitted to this README.md file, in the spaces provided for each task.
Once you are complete with all the tasks, please ensure that you have pushed your code and solutions, and then add [@georgemillard](https://github.com/georgemillard) and [@merton](https://github.com/Merton) as collaborators to your repository. 
You can then email us the URL to your repository, where we can review.

## The Challenge
### Introduction
Circulytics is the Ellen MacArthur Foundation’s leading tool for measuring how circular an organisation is, and provides feedback in areas that they can improve.  Organisations provide key information which can be used to calculate an overall score, as well as scores in different themes. 

### Data
You are provided with company data (`companies.csv`) which has the following data points:
- `company_id`: The unique identifier for that company
- `submission_date`: The submission date for the data
- `industry_group`: The high level industry group the company belongs too
- `industry_classification_id`: The ID for the industry classification the company belongs too
- `overall_score`: The company's overall score for Circulytics

### Task 1
Each organisation can be grouped by its industry classification,
as it is useful to be able to see the top performing industries that are making the most progress in their domain area.

**Answer**: Provide the top 5 industry classification IDs and their respective overall scores in ranking order

Industries: []

### Task 2
One important aspect of Circulytics is our ability to provide benchmarks against other organisations in their respective industry classifications.

**Answer**: Find the top 5 organisations whose overall scores are the highest above their industry competitors. For each organisation provide; Company ID, Industry classification ID, the average score for that industry, and the company's overall score.

Organisations: []

### Task 3
For data privacy reasons, we cannot benchmark industries if they have less than 12 organisations in them.

Adapt your solution to Task 1, or create a new solution, so that we only create benchmarks for industries that have at least 12 organisations in them.

**Answer**:  Provide the new top 5 industry IDs and their respective overall scores in ranking order

Industries: []

