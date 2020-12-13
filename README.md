# CTL_Final_Project
Final Project for Sarah Howie.  
  *Coding the Law Fall 2020*

For my final project, I joined the Suffolk LITLab's Document Assembly Line project to develop a Motion to Impound form to be used.

## Links
To access the Github repo for my final project, [click here!](https://github.com/SuffolkLITLab/docassemble-MtntoImpound)


## The Long Story
Prior to law school, I worked as a paralegal. Most of the firms I worked with had case management software. One firm in particular had Time Matters, and tasked me with making it work as efficiently as possible. While I could manipulate most of the screens, the main page for each case could only be manipulated by coders. I remember being frustrated that we had to outsource that part of the project to an outside company. 

Fast forward to choosing classes for my 2L fall semester. There it was- a class that might just give me the tools I desired to make those changes all those years ago. At the time, I had just started with a small firm in North Reading. While discussing the courses I would be taking in the fall, I mentioned this course. To my surprise, it turns out that a former law clerk took this same class not that long ago. I even took over the same law clerk email address at the firm! After getting his name from my boss, I found his Final Project biography. He built a form automation system to assist the firm. I found his email address and reached out to him about potentially building upon his work or to see if he had any other ideas. After exchanging [a few emails](https://github.com/showie56/CTL_Final_Project/blob/main/Emails%20with%20former%20student_Redacted.pdf), it didn't really seem feasible to build upon his project. So here I was, back at square one, searching for ideas.

With an unexpectedly difficult semester in full effect, my research into potential ideas to help my current firm led me to one conclusion- I was making it harder on myself by not joining onto a project that had a built-in support system.  After speaking with Professor Colarusso, I decided to join the Suffolk LITLab's Document Assembly Line project. I reviewed my options as to what the project had available to work on, and decided on the Motion for Impoundment. I was already familiar with the importance of preventing certain information getting into the wrong hands. After giving an [Intro Pitch](https://github.com/showie56/CTL_Final_Project/blob/main/Intro%20Pitch.pptx), I was ready to get to work. 

I researched various Massachusetts Motions to Impound and checked around to see if something like this already existed. I used this information to come up with a game plan on how to move forward. Luckily, a base motion, affidavit, and proposed order were already available through the LITLab. All I needed to do was turn that form into an interview that would fill in the information in the right place. The original motion was titled "Motion to Impound Addresses from Opposing Party," but it seemed to leave room for other information besides addresses to be impounded. After doing some research and speaking with my boss, it turns out that you can ask the court to impound just about any specific information. Therefore, I wanted to leave room for other information to eventually be added to the motion. So the first thing I did was change the title. 

After reviewing some of the tutorials that classmates had linked to in slack, I decided building the form would work best in docx format instead of pdf. Initially, I decided it would make sense to build the code and the form at the same time. That did not work for a couple reasons. First, I did not realize there was a wizard that would do most of the work for me. Second, that would require a constant reupload of the form, which broke the code more times than I could count. I quickly abandoned that plan and focused on just getting a coded form done. Once again using the resources various classmates were putting in the slack, I coded the docx form and had a LITLab member check it for me. Mia gave the all clear on the form, so I was ready to get to work on the interview code.

Or so I thought. After running the template through the wizard , uploading the form and then the initial code, almost every variable was red. Every time I tried to run the interview, I would immediately get [this error](https://github.com/showie56/CTL_Final_Project/blob/main/Screen%20Shot%202020-11-23%20at%203.40.38%20PM.png). After spinning my wheels, fighting every single error, I knew something had to be off. Surely, the wizard wouldn't spit out code with this many errors. I reached out to classmates, but they were all just as stumped as me as to what was happening. Eventually, I reached out in the Access to Justice Tech and Design Collaborative (A2J) slack channel and got connected to Michelle.

It took nearly three hours of zooming with Michelle, but I finally was able to get a viable working product. Turns out, the tutorial on how to format the code in the docx template had some false information, or the explanation on what to use was so unclear that it was unusable. Once  I put in the correct coding with Michelle's assistance and guidance, I reran it through the wizard, got the new code and template uploaded, and it all worked. I was ready to have some testers try to break it. 

My partner is a full stack developer and reviewed the code for me. With his feedback in mind, I cleaned up some of the code so it was cleaner and easier to modify in the future. My legal secretary ran through several interviews in attempt to break anything she could. While she never produced an error, she did give some valuable feedback. Some of the feedback I could fix on my own (things like changing the question order and phrasing, as well as adding a link to the Massachusetts Court docket search) and some were things I had no control over (things like the location of the "How Do I Know?" button and adding an instruction on how to make the preview form bigger.) I made the changes I could and noted the rest. 

Now that the interview is viable and produces a form that can be filed with the court, A2J will be handling the support, upkeep, and improvements moving forward. Items that can be improved upon in the interview are as follows:
* Changes to the placement of the buttons (i.e. moving the "How Do I know?" button so it does not get confused with the "Continue" button)
* Add an instruction cover sheet for a pro se litigant to follow for how to file and serve the motion
* Add an "other" option for information the litigant is seeking to impound, with room to list what those items are
* Add a list of resources for litigants (potentially a list of free legal service programs in their chosen county, and/or a link to domestic violence resources)
* Add a cover letter to the judge
* Add a way to look up the correct address for their chosen county court and judge

Overall, this has been an interesting learning experience. I am proud that I produced something that potentially could change someone's life by providing them the access they need to this. A special thanks to the Suffolk LITLab, A2j, Professor Colarusso, and Michelle. Because of them, Massachusetts is one step closer to having a more accessible, helpful legal system that will serve the greater population.


