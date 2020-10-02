# Sprint Challenge: Sprint 1

## Objectives

- Student can articulate breaking down a release into individual tasks.
- Student can accurately defend scope or timeline of an individual task
- Students will be able to articulate tradeoffs for architectural and design decisions

## Prompt 1 - Communicating Process

Hiring managers don't just want to see what you built, they want to see the reasoning behind it. Here are some questions surveyed hiring managers said they would ask about a project:

- "How did you decide what to build?"
- "Why is this feature important?"
- "Was this a good choice? What would you do differently if you had to do it over again?"

We took these questions and cooked them into your labs experience. Please answer the following questions as you would in an interview. Remember, hiring managers care about the **process** and the **why** of building something even more than the what.

### Questions you need to answer

1. Describe your **process** of breaking a release into user stories.
    As our team met for ideas with the second release of our app, we kept in mind the feedback that we had been given by our client, UX/UI designer, and peers. One piece of advice we were given was to look at similar apps to see their design and implement it on our own. From that feedback, we were able to update our Trello board on what more features we could add as user stories. “As a user, the main landing page incorporates the simple design by having the search bar be part of the main content.” “As a user, when I do an advanced search, another page will show with the filters on the top and the results of cities and main metrics as a list below.”

2. Choose a user story. Describe your **reasoning** as you broke down that particular user story into individual tasks.
   	“As a user, I can do an advanced search to filter my criteria as a priority.” Breaking down this task, we knew that it would be coming strongly from the web developer’s side. Since web was already pulling data from our current database, we are able to continue working with the frontend to implement the advanced search and focus on the structure of the component until Data Science is able to update their data table to fit that requirement. Our first tasks included: creating the form for the advanced search, researching other comparison filters in advanced searches, planning with the team what we want to implement, then executing that plan by creating a new component route to a new page with the advanced search and results page.

3. How long do you think the above user story will take to complete? Explain your reasoning.
   	I think that within this certain criteria, this will probably take about 5 business days to implement. I believe that the planning will take at least one day for our team to come to a general consensus, but when our team gets to build this component, we’ll hit the ground running. I think the main chunk of building the component, form of inputs, and implementing any logic that we have will take a span of two days. The remaining three are for cleaning up our code, styling, adding tests, connecting our queries with the updated database, and--of course--debugging any unforeseen setbacks. 

## Prompt 2 - Communicating Technical Decisions

On the job, you'll be making technical decisions every day. Hiring managers want to see how you make a choice and how you communicate your decisions. Here are some examples of questions they might ask about one of your projects in an interview:

- "What kind of database did you choose and why?"
- "Why did you use X to do Y?"

These sorts of questions inform your entire labs experience. You made a few technical decisions this week. We want to see how you would communicate them in an interview.

### Questions you need to answer

1. Describe a technical decision you made. How did you make that decision?
   	A technical decision I made this week was deciding what type of inputs would be used for the advanced search bar. After collaborating ideas with team members, I decided to use a minimum to maximum input for the population and rental prices, a dropdown for the job industry, and choosing the number of bedrooms for a living situation. I made the decision by looking at different input options there were and seeing what best suited the needs of the search bar filters. I was able to get feedback from teammates to be able to get different perspectives of what might be better options as well (such as using a Step feature for the rental prices--where the user first needs to choose the number of bedrooms they’re wanting and then the price range).

2. What are some of the risks given the decision you made?
   	I think some of the risks or flaws in the decision I made was not looking at other apps to see what filters were being used. After implementing the search bar filters, our team was able to view the layout of Google Flights to see the entire picture of the advanced search setting as well as the results page, which is what we needed to create anyway. Without fully planning what we had in mind, the risk we took was the amount of time and releases it took in order to decide what we wanted to do. 

3. What challenges do you foresee in using the architecture your team selected?
   As far as the architecture that we have now set up, some challenges that I see is the amount of time and efficiency it will take if we do not better communicate possibilities and plan the qualifications needed for Release 2. If we make one decision, implement it, then change our minds, that is a good time out our day, especially when there is a deadline for this project. That time could’ve been used researching and planning, then communicating as a team a decision to see what needed to be done (and done right) the first time. There are always going to be different directions taken when building an app, especially when receiving feedback, but we can better utilize our time to make our work more efficient.


## Prompt 3 - Professional Development 

### [Power Statements](https://learn.lambdaschool.com/cr/module/recQUR9bWxvLBJknr](https://learn.lambdaschool.com/cr/module/recQUR9bWxvLBJknr))

This lesson we reinforced how to turn your responsibilities and tasks into power statements. To practice, write a few power statements you intend to use in your LinkedIn profile. Before writing those statements, ensure your LinkedIn has all the following content checked off.

Add a link to your Linkedin in your sprint challenge submission document.

## Personal and Contact Information:

- [x]  First and last name are added to profile
- [x]  Created a [shortened, unique](https://www.linkedin.com/help/linkedin/answer/87/customizing-your-public-profile-url?lang=en) LinkedIn URL
- [x]  Profile picture is clear, shows my face (not a selfie), and is in front of a professional background
- [x]  Listed title, `i.e. iOS Developer`, below name with any keyword associations included.  **For example: “Data Scientist, with a passion for data visualizations and open-source code”**
    - [x]  Title **does not** pull from my current position (this is a LinkedIn default, must manually change), unless that position is relevant to the tech industry

## About Section

- [x]  Wrote a minimum of 3 sentences to describe my technical skills, background, interests, and passions. (Also feel free to include key professional accomplishments.)

## Experience Section

- [x]  Listed all, or at least the last 3-5 years of previous professional roles
- [x]  Included 2-4 power statements for each experience listed (okay to copy and paste from resume)
    - [x]  Power statements for each experience [are bulleted](https://www.linkedin.com/pulse/update-how-add-bullet-points-your-linkedin-profile-erin-dore-miller/), not in paragraph form.
    - [x]  Listed responsibilities in bullet point format (I **did not** leave in paragraph format). If you use Windows, hold down the ALT key and type 0149 on the keypad. Release the ALT key and the bullet point will appear. On a Mac, press Opt + 8 on the keyboard.
    - [x]  Started each bullet point with [an action verb](https://docs.google.com/document/d/1wZkDPBWtQZDGGdvStD61iRx_jOWVlIyyQl9UOYHtZgA/edit?usp=sharing) and **did not** re-use phrases such as:  `Assisted with...` `Worked on...` `Helped with...`  (`Solely responsible for...`)
    - [x]  Described past projects in past tense and current projects in present tense
    - [x]  Did not use pronouns such as: I, we, they, you, me, us

## Education

- [x]  Listed all education and relevant certifications: including name of the institution, degree type, and date the degree was received or will be received `i.e. May 2020` or `Expected July 2025`
    - [x]  I **did** link to Lambda School properly (Lambda logo saved)

## Skills

- [x]  **Listed** all technical skills, methodologies, and platforms with strongest skills [pinned at the top of the list](https://www.linkedin.com/help/linkedin/answer/35265/display-order-of-skill-endorsements?lang=en)

With all the above checked off, go to LinkedIn's "Accomplishments" section to add a project. Articulating the tasks or project work you're doing publicly on a platform like LinkedIn can help you gain visibility! LinkedIn is designed to produce better results, recommendations, and engagement for users who have thorough profiles and who upload content. If you haven't done so already, write a few power statements as well as a project description to populate those content fields and describe your project on LinkedIn.

This is also a good time to add your fellow labs teammates as connections so that you can add them as "creators" on the project.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/399b50ea-bb7b-4218-977b-844d86a0203d/Screen_Shot_2020-07-23_at_10.35.42_AM.png](https://tk-assets.lambdaschool.com/d6b22266-d5f7-4949-8db9-8fe5f7ae1f4f_Screen_Shot_2020-07-23_at_10.35.42_AM.png)

Here's the checklist you'll want to complete for projects:

## Projects (Under "Accomplishments")

- [x]  **Listed** title for Labs projects
- [x]  **Included one sentence** to describe what the project does
    - [x]  I **did not** use the phrase `This project was...` or `This project is...` in description
    - [x]  I **did not** use more than one sentence to describe the project
- [x]  **Listed** the tech stack used for each project (see below for example)
- [x]  **Listed 2-3 power statement bullets** highlighting my responsibilities on project
- [x]  **Did not** use the words "capstone" "Lambda Labs" or "School" project

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/18ad1d52-5679-4f4e-80bc-aa0341034f93/Untitled.png](https://tk-assets.lambdaschool.com/4f07d726-0a78-4014-82f4-dd56a02f21bc_Untitled2.png)

## [Sprint Challenge Rubric](https://www.notion.so/863354e030274baf99983cfee357d4d1)

https://linkedin.com/in/berachele/
