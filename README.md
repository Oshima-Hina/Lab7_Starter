Name: Yilong Chen

No partner this time.


1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

[x] Within a Github action that runs whenever code is pushed 

Manually run them locally before pushing code

Run them all after all development is completed



Running tests automatically on every push ensures that all code going into the repository is consistently tested, reducing human error and oversight.
In collaborative projects, this ensures no one pushes broken code that could block others or destabilize the main branch.

2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)

*No*

End-to-end tests are designed to test the entire application flow — from the user interface down to the backend and database — as a complete system.
Checking if a function returns the correct output is better suited to a unit test



3) What is the difference between navigation and snapshot mode?

Navigation mode simulates a full page load from the start whild snapshot mode only examine current state. No full performance metric in snapshot mode.


4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.

1.Properly size the images since they were larger than their displayed size

2.<html> element does not have a [lang] attribute, and it should have one for accessibility.

3. Serve static assets with an efficient cache policy, since a long cache lifetime can speed up repeat visits to your page.

