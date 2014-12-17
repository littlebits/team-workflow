team-workflow
=============

The workflow used by software teams at littleBits



## View team members' current work via Github assign

The current focus of any team member should be observable through the Github Organization view filtered by issues assigned to a user.

Team members should maintain their list of assigned issues. They should not have anything assigned to them that is not current within a reasonable timeframe. That timeframe may vary. Arbitrary we can say two days.

- Feel free to self-assign so that others at least know what you might be actively doing.
- Feel free to unassign yourself if that reflects the reality.
- Generally you should not be working on something that is not visibly assigned to you.
- Generally you should not have a single issue assigned contiguously for weeks or even days. If its an open-ended "research issue" that cannot be broken down, then assign/unassign as you interact with the issue.
- Each day should start and end with no issues assigned to yourself.

Viewing what team members are doing:

1. Go to issue view for an organization: https://github.com/issues?q=user%3Alittlebitselectronics
2. Select "assigned": https://github.com/issues?q=user%3Alittlebitselectronics+assignee%3Ajasonkuhrt which will automatically filter to your account.
3. The UI Search bar should read something like:

  ```
  user:littlebitselectronics assignee:jasonkuhrt
  ```

  Change it to the user of interest.
