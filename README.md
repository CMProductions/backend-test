## Video Share

We buy videos from several sources.  Each source provides its content to us in a different format.  Write a command line script to import the videos.    

Input/output should be something like this:
 
````bash
$ import glorf

importing: "science experiment goes wrong"; Url: http://glorf.com/videos/3; Tags: microwave,cats,peanutbutter
importing: "amazing dog can talk"; Url: http://glorf.com/videos/4; Tags: dog,amazing
````

Considerations:

- Currently, we are importing videos from 2 sites: flub, and glorf.  They send us their weekly feed via email.  This weeks files are in /feed-exports
- We plan to add a third provider soon who will make their feed available via json output which it will make available via FTP (you don't need to implement this, just keep it mind)
- Do not implement any data persistence code, just provide some dummy classes that echo what they are doing.  Keep in mind that the company is planning to switch from MySQL to Cassandra in 4 months.
- The focus here should be on design, more than implementation.  We are less interested in seeing that this works than in seeing how you approach the problem.
- Please provide at least some unit tests (it is not required to write them for every class). Functional tests are also a plus.
- Please provide a short summary as SUMMARY.md detailing anything you think is relevant, for example:
  - Installation steps
  - How to run your code / tests
  - Where to find your code
  - Was it your first time writing a unit test, using a particular framework, etc?
  - What would you have done differently if you had had more time
  - Etc.

* * * 
## Delivery

Please create a git patch (https://devconnected.com/how-to-create-and-apply-git-patch-files/) and email your completed test to me.
