# tracker-scoreboard

These Pivotal Tracker search strings can be used to produce the "scoreboard". This provides high level project status for those who don't care to see how the sausage is made.

- Accepted `type:feature state:accepted includedone:true`
- Rejected `type:feature state:rejected`
- Delivered `type:feature state:delivered`
- Unknown `type:feature state:unstarted,started`
- Total `type:feature includedone:true -state:unscheduled`

To add these to your Saved Searches in Tracker, enter one of the search strings above into the Tracker search and click enter. At the bottom of the list of results, click the heart icon and enter a name (e.g. Accepted).

Note that bugs are not included in the scoreboard counts. To check your bug or chore counts use the following searches

- Bugs `type:bug`
- Chores `type:chore`
