MY FIRST POSTMORTEM










My Airbnb postmortem
Introduction
hmm… postmortem? You might wonder what that means, or think I’m some doctor who opens up dead people to see what’s inside them. Well… you might not be so far off 😉 I’m a software doctor hahaha!!!. The Postmortem is a process intended to help one learn from past incidents or failures.
You then might wonder, why would ever need postmortem? Well have you ever been in a situation where you want to know what went wrong with something but at the same time don’t how to go about it? Well then, postmortem surely comes in handy in those circumstances. When you have a postmortem you can recognize what you’re doing right, where you could improve, and most importantly, how to avoid making the same mistakes in the future.
So…, below is a summary of an outage I encountered during my software execution.
Summary of my outage
The problem occurred during the time I tried to log on to my web server on my local machine during an AirBnB project I had. Every time I run the command, I run into a 404 error, however, when I use Curl on my local machine I get the correct output. This started at 21:00 CAT to 00:00 CAT on Feb 6. I then found out that the root cause was the WSL I was using. Because of this outage, I couldn’t log on to the Airbnb website I had created.
Timeline of the outage
The problem was detected on Feb 6 from 21:00 to 00:00 during my testing phase of the project Airbnb.
The problem was detected on my end, which meant that the client wouldn’t have been able to access the website.
I had to remove the WSL I was using, and then re-download it so that my problem would be fixed.
Before knowing this, I tried many things, to the point of changing most of my HTML and CSS, files thinking that was the problem.
Doing all sorts of things, led to my Curl not working too. Which was such a headache.
I had to ask some of my friends, google, chatbot, and Phind, and I read some people’s codes to relate if I had some problems.
Root Cause
The problem in this case was that my computer couldn’t connect to the internet properly. So whenever I connected to the web browser from VSCode I would get an error. But then, I could get a correct output using the Curl command.
So to solve this, I sent the output I was getting to my schoolmate. Luckily he had come across a conversation on GitHub where someone had the same problem I was facing. He sent me the link to the conversation, and that was where I learned that the problem was WSL. So I had to re-download it or change something in my command prompt.
Corrective and Preventive Measures
Generally, I would say that the whole thing played out well for me, with the help of that colleague of mine.
Happy Reading!!!! 😄


