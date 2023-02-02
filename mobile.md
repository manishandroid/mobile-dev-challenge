# Mobile Developer Technical Challenge

### Business requirement
As an user I want to be able to see a list of products, including product photos and description. 
Please feel free to be more creative while developing UI for this assignment.

### API Specification

**Get list of products**
  * Protocol
    `HTTPS`
  * Hostname
    `(https://dummyjson.com/)`
  * Method
    `GET`
  * Endpoint
    `/products`
  * Response example:
    `HTTP code 200`
    ```json
    {
	"products":[
			{
			"id":1,
			"title":"iPhone 9",
			"description":"An apple mobile which is nothing like apple",
			"price":549,
			"discountPercentage":12.96,
			"rating":4.69,
			"stock":94,
			"brand":"Apple",
			"category":"smartphones",
			"thumbnail":"https://i.dummyjson.com/data/products/1/thumbnail.jpg",
			"images":[
				"https://i.dummyjson.com/data/products/1/1.jpg",
				"https://i.dummyjson.com/data/products/1/2.jpg",
				"https://i.dummyjson.com/data/products/1/3.jpg",
				"https://i.dummyjson.com/data/products/1/4.jpg",
				"https://i.dummyjson.com/data/products/1/thumbnail.jpg"
				]
			},
			{
			"id":2,
			"title":"iPhone X",
			"description":"SIM-Free, Model A19211 6.5-inch Super Retina HD display with OLED technology A12 Bionic chip with ...",
			"price":899,
			"discountPercentage":17.94,
			"rating":4.44,
			"stock":34,
			"brand":"Apple",
			"category":"smartphones",
			"thumbnail":"https://i.dummyjson.com/data/products/2/thumbnail.jpg",
			"images":[
				"https://i.dummyjson.com/data/products/2/1.jpg",
				"https://i.dummyjson.com/data/products/2/2.jpg",
				"https://i.dummyjson.com/data/products/2/3.jpg",
				"https://i.dummyjson.com/data/products/2/thumbnail.jpg"
				]
			},
			.....
			.....
			.....
		]
	}
    ```

### Functional Requirements
- Retrieve products from the API
- Display list of products.
- Show details when user select an product in the list in next screen.

### What we expect from you?
Production ready solution that you are proud of.

## Technical Requirement
- Source code must be stored in a Git repository (you can send us github or bitbucket link)
- For public repos:
	- Avoid words `rewardz`, `alberta payment`, `take-home`, `assignment`,  and `challenge`
	- Do not copy-paste any part of this file (task, API documentation, etc.)
	- This is needed to prevent other candidates from finding your solution
- For private repos access: 
	- Github: Please add [techchallenge-manish](https://github.com/manishandroid) as project collaborators
- App should cache products (Cached products should be available offline)
- Candidates are free to use any libraries

* ### iOS Engineer
	- Must write in the latest Swift version

* ### Android Engineer
	- Project must compile `./gradlew build` 

## Wireframe
*For reference only, you can be creative with design and UI/UX features.*
![Wireframe](/mobile-engineer-wireframe.png)

## Evaluating your take-home exercise
We score a solution on six criteria, which have been selected to take into account the fact that candidates might have different preferences for libraries/frameworks than us because of circumstances, and we look for general programming ability rather than familiarity with specific tools.

Every submitted exercise will be given a score (from 0 to 12 points). We have a certain cut-off score, which an exercise will have to meet to decide if a candidate should be taken forward to the next stage.
If a solution doesn't meet our standards, we will respond with an appropriate rejection mail.

#### Criteria and respective score points

|  Application          | Score  |
|-----------------------|--------|
| Barebones, developer UI with no error/touch feedback to the user.  | 0  |
| Functional UI, and with error feedback and/or touch feedback. | 1  |
| Polished UI, with thought put into the user experience and/or with nice transitions and animations. | 2 |

|  Documentation          | Score  |
|-------------------------|--------|
| No documentation in the repository.  | 0   |
| Some documentation with basic setup instructions or feature descriptions. | 1  |
| Detailed documentation with setup, screenshots, configuration instructions, etc. | 2 |

|  Commit History          | Score  |
|--------------------------|--------|
| The repository has a few large commits (Exceptions are commits with auto-generated code like Room schemas or the initial commit when initialising a project through an IDE or a CLI).  | 0  |
| The repository has some small-ish commits with clear (what the commit does) messages. | 1  |
| The repository has many tiny, atomic commits with clear, descriptive (what the commit does and why, when appropriate) messages. | 2 |

|  Testing                | Score  |
|-------------------------|--------|
| There are either no tests, or a few tests that aren't really that useful.  | 0  |
| Tests for business logic are present, but they are tested via instrumentation/UI tests. | 1  |
| Business logic is tested using unit tests, and there might be instrumented/UI tests for testing platform integration. The tests need not be comprehensive as long as they are testing important code paths. | 2 |

|  Separation of concerns          | Score  |
|----------------------------------|--------|
| Business, presentation, and implementation logic are all mixed together (everything in the Activity/View/Fragment).  | 0  |
| There is some separation of concerns (ex: separate interface and classes for querying data/making network calls). | 1  |
| Candidate has used a standard architecture pattern (MV*/others). The candidate could also have rolled their own architecture as long as there is clear documentation on their custom solution. | 2 |

|  Code maintainability          | Score  |
|--------------------------------|--------|
| Names are unnecessarily short or meaningless. Ex: a, something, doWork, runQuery. An exception to this rule would be something like the iteration variable in a for loop.  | 0  |
| Names are mostly descriptive and indicative of the intent. Some names might occasionally be unclear without explanation. | 1  |
| Names are mostly descriptive and indicative of the intent. Unclear names have clear comments explaining the purpose of the variable/function and the intent behind it. | 2 |

|  Minimum Score Required          | 5  |
|----------------------------------|----|

### How we give score to your repository
The scoring has six different sections (see table above), all of which contribute a certain number of points to the overall score of a solution. The scoring process has been designed to compensate for a solution lacking in one aspect, but done well in others.
 1. For each of the sections in the table below, look at the state of the repository and select an appropriate score.
 2. Sum up the scores for the individual sections.
 3. If the total score is greater than or equal to the cut-off score, move the candidate to the next stage of the interview.
 4. If the total score is less than the cut-off score, respond with an email to the candidate which contains the score and what criteria they lost points in.


**Questions? We love to answer: Drop your queries to <manishdubey81189@gmail.com>
