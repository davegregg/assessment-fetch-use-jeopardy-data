# Assessment: Fetch and Use Jeopardy Data

Now it's time to use `fetch()` to make some GET requests and do something semi-intelligent with the responses.

### :warning: Read the submission guidelines at the bottom of this page first.

### MVP

1. Review the documentation for [jService, an open "Jeopardy" API](https://kenziejservice.herokuapp.com). Experiment a little and see what data you can get back.
2. Identify a set of categories from the Popular Categories page which you want to display in your Jeopardy.
3. On page load, request each category from jService and display them Jeopardy-style in a grid on the page. Show only the point values initially. Display the clue on each cell on click. *(8 points)*
4. Above your grid (or at the top of it), show the category for each column. *(4 points)*
5. Use your Grid and Cell classes to extend a JeopardyGrid and JeopardyCell class, which you will use to create your grid. *(8 points)*
6. Provide the user an input box for supplying an answer, and a button for making a guess. *(1 point)*
7. When the user makes a guess, check if the user-supplied answer is the correct answer. *(1 point)*
8. Award points (based on the "value") to the user if they guess the answer correctly. *(1 point)*
9. Load a new question for the user. *(2 point)*
10. You do not have to provide a win condition.

### Stretch Goal
1. Use OOD (Object-Oriented Design) to represent the contestant and a round.

### Epic Mode
1. Provide the user with a timer and penalize them for not guessing correctly in time.
2. Provide a win condition once all questions in all categories are exhausted.

# Submission Guidelines
1. Use GitLab for this assessment.
2. Before you touch any code, make a plan.
3. Create a README.md file in your repo, and use it to record your notes and pseudo-code from Step 1.
4. Enable Pages for your repo (by using [init-gitlab-page](https://my.kenzie.academy/courses/20/assignments/2434?module_item_id=3444)).
5. When you run `init-gitlab-page` make note of the URL it gives you on the console. This is the link to your GitLab Page.
6. On Canvas, submit the link to your GitLab Page.
