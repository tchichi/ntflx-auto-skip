# NTFLX Auto-Skip


NTFLX Auto-skip is a Firefox extension that offers some options when watching Netflix, such as skipping the intro or summary of an episode.


## Goals


I set myself the following goals as a starting point before starting the process of understanding. Since I'm starting from scratch without really knowing what's going on under the hood, my first step will consist to understand how it works then to come up with a solution in order to achieve one of the goals below. Therefore, I may not be able to achieve some of these goals during the time I have set for this project. 

- [ ] Skip the introductions 
- [ ] Skip the summaries 
- [ ] Instantly play the next episode 
- [ ] Ignore the "Are you still watching?" message
- [ ] Allow the user to de.activate any of the features above 


## Questions


My first reasonings are:
- What framework and libraries does Netflix use? 
  - At first glance, among those I know (by name), it looks like they are using React and Bootstrap (thus jQuery too). 
- Does their app work differently depending on the country the user lives in or their language?
  - I'll work from my place in Brussels (Belgium) and my Netflix account is in french. 