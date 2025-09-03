Assignment Prompt: 

Step 1: Create a better ping command
Use ping -h to look up the options that you can use with the ping command. Create an alias so that when you execute ping it stops after 5 tries and shows hostnames if they are available.
Create an alias so that when you execute slowping it does the same thing as your new ping command and it also waits for 3 seconds between each attempt.
If you are unhappy with an alias and want to re-create it, use unalias to remove the existing alias first.

Answer the following questions
What is the exact command you used to create the ping alias?
What is the exact command you used to create the slowping alias?
What do you think the advantages are of making these aliases? Why not just stick to the regular ping command?

Step 2: Which servers are down?
Using your slowping command, check the servers listed below. Take a screenshot of ONE of the successful attempts. Name the screenshot slowping.xxx where xxx is the appropriate file extension.

Servers to check:

iti201s[X].comminfo.rutgers.edu (replace [X] with numbers 1-10)
iti201app.comminfo.rutgers.edu
iti201db.comminfo.rutgers.edu
Answer the following questions
Which servers (if any) appear to be down?
You should have seen some different hostnames than what you were expecting. Take a shot at explaining why this is not an issue. I mean, two names for the same server? Should that cause some kind of conflict?

Step 3: Check the remote servers
Run traceoute against one of the servers in step 2 that are responsive and take a screenshot.
Run traceoute against www.example.org take a screenshot and name it traceroute.xxx where xxx is the appropriate file extension.

Step 4: Network tools or hacking tools?
The Fox textbook says that these tools are “often considered insecure programs” and that “hackers might use either or both to investigate the computers on a LAN.” Let’s stipulate for now that this is true.

In an earlier module we learned about a tool that could be used to give access to these commands to only certain people. What is that tool, and how would it reduce the risk that Fox is referring to? (hint: think about “system permissions” and recall how you could and could not use apt in an earlier lab.)
Based on what these tools do, do you think “regular users” should have access to them? Defend your answer.
