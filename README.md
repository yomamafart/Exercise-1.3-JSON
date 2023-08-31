# Exercise-1.3-JSON

Exercise for MSCH-C220 at Indiana University, Bloomington

The expectations for this exercise are that you will

 - [ ] Fork this repository
 - [ ] Make several edits to the zork.json file
 - [ ] Edit this repository's LICENSE and README.md
 - [ ] Commit and push your changes back to GitHub. Turn in the URL of your repository on Canvas.

## Instructions

Fork this repository. When that process has completed, make sure that the top of the repository reads [your username]/Exercise-1.3-JSON. Edit the LICENSE and replace BL-MSCH-C220 with your full name. Commit your changes.

Select the zork.json file. Edit the file by pressing the pencil icon.

Make the following edits to zork.json:

 - At the West of House (pid:1), the text should be "This is an open field west of a white house, with a boarded front door. A mailbox is here."
 - At the East of House (pid:5), delete the link for selection 5 (Enter)
 - In the Sunlit Forest (pid:6), change the Label for selection 5 to "CLIMB UP"
 - In the Kitchen (pid:7), in link selection 1, add a new key/value pair (don't forget the comma): "requires":"window"
 - Create a new passage (pid:9) which is a copy of the Forest (pid:4). In the Forest (pid:4), change the pid for link selection 3 to 9 (instead of 4)

 When you are done with the edits, commit the changes.

 Copy the (raw) contents of zork.json and paste them into the web form at <code>https://jsonlint.com/</code>. Validate the JSON. If there are errors, correct them. 

Now edit the README.md file. When you have finished editing, commit your changes, and then turn in the URL of the main repository page (https://github.com/[username]/Exercise-1.3-JSON) on Canvas.

The final state of the file should be as follows (replacing the "Created by" information with your name):
```
# Exercise 1.3: JSON

Exercise for MSCH-C220

The third exercise for the Interative Fiction project, exploring editing a JSON file by hand.


## Implementation

Created using Twine 2 and exported with [JTwine-to-JSON](https://github.com/BL-MSCH-C220/JTwine-to-JSON)


## References

[Zork, 1977 by Tim Anderson, Marc Blank, Dave Lebling, and Bruce Daniels](https://en.wikipedia.org/wiki/Zork)

JSON validated at https://jsonlint.com/


## Future Development

None


## Created by 

Jason Francis
```