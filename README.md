# Devops-practices

A Version Control System allows a user to freely make modifications or changes with the
ability to record the date/time and state of the change

Some of the benefits VCS brings:
1. Enables a safe workflow - A developer can commit code in small and easily
testable increments. If any commit causes a problem... it can easily be reset
to a stable state.

2. Enables experimentation without fear – If you’d like to try a change that is at
risk for the introduction of unintended behavior, a developer can simply
revert their work in progress back to a clean copy.

3. Rolling Back – A “roll back” or “rolling back” allows a developer to recover
older versions which may not have that bug which was not caught before
reaching production. With VCS, you can roll back to a working build with
ease.

4. Isolating Problems - Sometimes problems can arise and it may be difficult to
isolate where the problem stems from. VCS provide the luxury of traveling
back in time to old code commits. Rolling back to a previous commit allows a
developer to isolate and identify when the problem was introduced. This is
really helpful as finding the source of the problem often times is 90% of the
work.

5. Enables CI/CD - As we will learn throughout this course, CI/CD is crucial for
scaling up a development team and automating builds, testing and
deployment. VCS is a fundamental enabler for these advanced techniques
