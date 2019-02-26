# About Spyros

**Table of Contents**

- [What I do for a living](#what-i-do-for-a-living)
- [Communication & Collaboration](#communication--collaboration)
- [Pull Request & Code Review manifesto](#pull-request--code-review-manifesto)
- [References](#references)

## What I do for a living

I'm currently a Senior Software Engineer (Vehicle Controls)
at [Cruise Automation](https://getcruise.com) (aka GM Cruise).

For more information, please check out
[my résumé](https://spmaniato.keybase.pub/docs/Spyros_resume.pdf)
or [LinkedIn profile](https://www.linkedin.com/in/spmaniato).

## Communication & Collaboration

The tl;dr is that I prefer asynchronous communication (e.g. Slack) over
tapping me on the shoulder or calling my name from across the room.
The same goes for collaboration.
I would rather discuss work matters in the comments section of a
Jira ticket, Google doc, or GitHub pull request than in person.
Team chat would work too in this case, but the conversation would ideally
take place in a channel specific to the project, not via direct messages (DM).

These are just preferences, not rigid rules. And there are exceptions.
For example, brainstorming, design reviews, and retrospectives are better done in person.
However, someone should be taking notes when meeting in person
to discuss work matters, answer technical questions, make decisions, etc.

## Pull Request & Code Review manifesto

### As PR author I will

* Keep my pull requests (PRs) small but self-contained
* Write meaningful commit messages, PR titles, and PR descriptions
* Include ticket number in PR title and link to the ticket in PR description
* Include links to any additional documentation in the PR description (e.g. design doc)
* Ensure that diff / patch coverage is close to 100% and that overall project coverage doesn’t decrease
* Use a `multipart` (or equivalent) GitHub label to indicate a PR is one of many parts
* Limit the rate at which I open new PRs to match the team’s ability to review them
* Ensure that CI (both build and automated tests) is green before requesting reviews
* Request reviews and post links to PRs on team chat when (and only when) they are ready for review

### As PR reviewer I will

* Make an effort to review as soon as I get the chance (assuming the PR is small)
* Approve the PR, as long as the state of the code base is better than before
* Prefer opening a new ticket or requiring a follow-up PR over rejecting the PR
* Favor suggestions over rejections, particularly when multipart PR indicated via label
* Review the PRs of others before opening a new PR that would exceed our WIP / PR limit

## References

* Slack Engineering -
  [On Empathy & Pull Requests](https://slack.engineering/on-empathy-pull-requests-979e4257d158)
* Slack Engineering -
  [How About Code Reviews?](https://slack.engineering/how-about-code-reviews-2695fb10d034)
* Hacker Noon -
  [The Art of Pull Requests](https://hackernoon.com/the-art-of-pull-requests-6f0f099850f9)
* Valve -
  [Handbook for New Employees](https://steamcdn-a.akamaihd.net/apps/valve/Valve_NewEmployeeHandbook.pdf)
* Spotify Engineering - Culture:
  [Part 1](https://labs.spotify.com/2014/03/27/spotify-engineering-culture-part-1/),
  [Part 2](https://labs.spotify.com/2014/09/20/spotify-engineering-culture-part-2/)
* Signal v. Noise -
  [Library Rules: How to make an open office plan work](https://m.signalvnoise.com/library-rules-how-to-make-an-open-office-plan-work/)
