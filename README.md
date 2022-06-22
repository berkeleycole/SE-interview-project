# SHIFT QA INTERVIEW PROJECT
### Why this project
The Shift QA role requires the technical ability to read existing code and write tests, but also leans heavily on a candidate's ability to translate features into test scenarios and communicate with all parties/departments involved in feature sign off and deployment. This project is designed to test all of these skills and will be evaluated in a cross-departmental panel interview with members of the engineering and product team.

### About the repo
For this project, you are provided a basic React application built with NextJS (https://nextjs.org/). You will find a small set of components in the `src` folder and a single page in the `pages` folder (index.js in pages is the only page, and also the root route). This is a scaled down version of Shift's stack, which is also built on NextJS.

There is no API for this project, instead, static data is coming from `candidates.json` as an API mock.

Some additional NextJS documentation can be found in `NEXTJS.md`, you can refer to their documentation for more information about the library as needed.

In the `TICKET.md` file, you will find an example feature ticket. 

### Testing in the repo
The test framework included in this example repo is Jest with React Testing Library. Tests are held in folders called `__tests__` and tests are run with `yarn test`. 

### Project instructions and requirements

Read the `TICKET.md` file to understand the feature task and its acceptance criteria. For this QA role, you are not required to write the code to satisfy the ticket, the only requirement is that you:

- write the test scenarios you think are necessary to cover the feature acceptance criteria (these can be added in a text or md file included in the project)
- write down any questions you would ask for further clarification
- write at least one Jest test (test should fail) to prove a test scenario you wrote

##### Optional:
If you want to write the feature code that makes the automated test pass, you are welcome to, but you should write the tests first to ensure it was failing before the code was added (common TDD flow and all that).

### About the Interview
The interview will be conversational, with time for you to ask any questions, walk us through your process, ask any questions you had, and explain things like:
- why you chose the test scnenarios you did
- where any uknown or areas for further discussion came up
- how you would go about writing the remaining automated tests

During the interview you will be able to share your screen to walk us through any code or text files, you can also put your fork of the repo up on github and share the link with us. 
