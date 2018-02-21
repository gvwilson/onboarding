# Short Screencasts to Introduce Content Development Topics

## How do I log in?

(start: log out, and then go to http://datacamp.com)

- Go to datacamp.com.
- If you don't already have an account, you can create one by filling in your email address and password.
- If you do already have an account, click on "sign in" in the upper right.
- Fill in your credentials and click the button.
- That'll take you to our home page, and you can see your profile image and your current experience point total up here in the upper right.

## How do I get to the Teach dashboard?

(start: log in and go to http://datacamp.com/home)

- If you've just logged in, you'll be on your personal home page, which shows your profile image and experience point total in the upper right.
- Scroll down to the bottom of the page.
- There's a link titled "Course Editor".
- If you click on that, it takes you to the dashboard.
- You can also just bookmark http://datacamp.com/teach, which will redirect you to the same place.

## How do I view my courses?

(start: log in and go to http://datacamp.com/teach)

- The Teach dashboard shows you a list of all the courses you have permission to edit.
- If you click on Projects (click!) or Challenges (click!) on the left, you can see your projects and challenges.
- If you have admin permissions, you can check "show call" to display other courses as well.
- You can type in the search box at the top to filter courses (type!)
- And if you click on the "Edit" box beside a course's name, you can see links for its branches, its build logs, and so on.

## How do I create a new course?

(start: log in and go to http://datacamp.com/teach)

- If you're building a premium course, DataCamp will create the course for you.
- But you can also host your own free courses on our platform.
- Click on the button titled "Create Course" (click!).
- Fill in the name of the course - use lower case words connected by hyphens, with "courses" as the first word (type!).
- Choose the account that will own the course (click! on the pulldown to display choices, but don't change anything).
- Make sure the right technology is selected (click! on something that *isn't* initially selected).
- Don't select "Premium": as we said a moment ago, if your course is reserved for paying customers, we'll set it up for you.
- Then click "Create" (click!).
- As soon as the course and its GitHub repository have been created, the Teach editor will be launched.

## How do I get from the dashboard to my course?

(start: log in and go to http://datacamp.com/teach)

- That depends what you want to do.
- If you want to see the course as learners will see it, click on the course's name in the first column of the dashboard (click!).
- This opens up a tab showing you the course's home page (pause, then close tab).
- If you want to edit the course, click on the "Edit" button (click!).
- The dialog that comes up shows you all the branches for your course (wiggle mouse over branch list).
- If you click on "View", you'll be taken to the home page for your course (click, pause a moment, then go back).
- If you click on "Edit", you'll be taken straight into the Teach editor for that course (click!).

## How do I change the settings for my course?

(start: launch the Teach editor for a newly-created dummy course)

- When you're on the master branch of a course (wiggle mouse over "master"), the Teach editor shows three tabs: Home, Build, and Settings (wiggle mouse over tabs).
- Click on "Settings" (click!).
- You can change whether the whole course is tested every time a change is made, or only the chapters that have changed, or nothing at all (wiggle mouse).
- If you scroll down, you can also change who has access to your course (scroll down).
- However, you shouldn't change any of this unless you're absolutely sure you know what you're doing - please ask your Content Developer to do it for you.

## How do I create a new branch?

(start: launch the Teach editor for a newly-created dummy course that already has two branches called "master" and "specs")

- The tabs at the top of your course page show you what branches are available (wiggle mouse).
- To create a new branch, click on the plus sign (click!).
- This will create a new branch derived from whatever branch was selected at the time, so make sure you have the right starting branch selected.
- Type a name for the new branch into the dialog, then click "Create" (type and click).
- Please only use letters, digits, and hyphens for branch names.

## How do I edit a course?

(start: launch the Teach editor for a newly-created dummy course that has at least two branches)

- Click on the name of the branch you want to edit (click to change branches)
- Click on the "Edit Course" button (click!)
- The course editor will launch (pause a moment so people can see it)
- You can then use "Try New Interface" to switch to our new-and-improved interface (click!)

## How do I edit course metadata?

- ?? How do we do this in the new editor ??
- When the time comes, explain that the title and description will eventually appear on the landing page for the course, so students will see this text
- When the time comes, tell them that the language has to be written in lower case, but they shouldn't change it: they should ask their CD to do it
- When the time comes, explain that the "from" field determines which Docker image will be used to build their course: only their CD should change it

## How do I save my changes?

- ?? Show this *after* showing people how to edit course metadata (which means after we figure out how to do that in the new interface) ??
- Tell them *not* to press "sync" while they are editing, since that will bring in any changes made independently in their GitHub repository

## How do I synchronize with changes made in a course's GitHub repository?

- ?? Show this *after* showing people how to edit course metadata (which means after we figure out how to do that in the new interface) ??

## How do I create a new chapter?

(start: get into new-look course editor for a dummy course)

- Click on the "Add Chapter" button in the bottom left (click!)
- Fill in the title and a brief description: both of these will be shown to students doing your course (type!)
- Click "Create Chapter" (click!)
- Your new chapter will show up in the pane on the left (wiggle mouse to highlight)

## How do I edit chapter metadata?

- ?? Show this *after* we figure out how to do it in the new-look editor ??

## How do I preview a chapter?

(start: get into the editor for a dummy course)

- Click on the "Preview" button in the bottom right (wiggle mouse, then click)
- A new tab will open to display a preview of the current chapter

## How do I add a Pure Multiple Choice exercise?

(start: get into the editor for a dummy course)

- A "Pure Multiple Choice" exercise asks the learner to pick an option without writing or running any code
- To create one, click on "Add Exercise" (wiggle mouse then click)
- Select "Pure Multiple Choice" (click)
- Fill in the "Assignment" section that sets the background for the exercise and asks the question (type)
- Fill in the "Hint" section (type)
- Fill in the "Possible Answers" with a point-form list of three or four options, using a dash to start each one (type)
- Put square brackets around the correct answer (wiggle mouse to highlight)
- Fill in the "Feedbacks" section with a corresponding point-form list (type)
- Click the "Save" button at the bottom (wiggle mouse, then click)
- Click on "Preview" at the bottom to see how your exercise will appear (click!)

## How can I allow several correct responses to a multiple choice exercise?

?? Fill this in once we have an answer ??

## How do I add a Normal exercise?

(start: get into the editor for a course that has an exercise in its first chapter)

- A "Normal" exercise requires the learner to write and run a little bit of code
- Click on "Add Exercise" (wiggle mouse then click)
- Choose the "Normal" exercise type (click)
- Click the pencil icon beside the exercise title (click) and give it a name (type in text and click the button)
- Fill in the Assignment text that sets the background for the exercise (type)
- Fill in the "Instructions" for the exercise (type)
- Fill in the "Hint" (scroll down and type)
- Fill in any "Pre-Exercise Code" that you want run before the user can starting typing (type)
- Fill in the "Sample Code" that will be shown to the user when they start the exercise (type)
- Fill in the "Solution" that will be shown to the user if they can't answer the problem (type)
- Remember that this code is also run when the course is built to check that the SCTs do the right thing
- Your Content Developer will write the Submission Correctness Test code to check the user's answer, so leave this blank (wiggle mouse)
- Click the "Save" button at the bottom (wiggle mouse, then click)

## How can I preview a Normal exercise?

(start: get into the editor for the Pure MCQ just created)

- Click on the "Preview" button (wiggle mouse to highlight, then click)
- A new tab opens up
- The "Assignment" text shows up under "Exercise" (highlight)
- The "Instructions" are right below it (highlight)
- A code console appears on the right (highlight and type)
- If you go back to the editing tab, you'll see that the "Preview" button is highlighted (wiggle mouse)
- If you close the Preview tab, the highlighting goes away (click!)

## What else do I need to know about Normal exercises?

(start: get into the editor for a course that displays the Normal exercise created above)

- There are a few things you should know about creating Normal exercises
- First, instructions are written as an unordered list using a dash to start each list item (wiggle mouse to highlight)
- Second, to write the "Sample Code", you should write the "Solution Code" first, then copy and paste it into the "Sample Code" section and delete bits (scroll up and down to show)
- Finally, comments have to be identical in both the "Solution Code" and the "Sample Code" (scroll up and down to show)
- And those comments are not typical code comments: they are an abbreviated version of the exercise instructions (highlight to show)

## How do I add a Multiple Choice exercise?

(start: get into the editor for a course that has an exercise in its first chapter)

- Click on "Add Exercise" (wiggle mouse then click)
- Choose the "Multiple Choice" exercise type (click)
- Click the pencil icon beside the exercise title (click) and give it a name (type in text and click the button)
- Fill in the Assignment text that sets the background for the exercise (type)
- Fill in the "Instructions" for the exercise (type)
- Fill in the "Hint" (scroll down and type)
- Fill in any "Pre-Exercise Code" that you want run before the user can starting typing (type)
- Your Content Developer will show you how to fill in the Submission Correctness Test code to check the user's answer
- Click the "Save" button at the bottom (wiggle mouse, then click)

## How do I add a dataset to a course?

- ?? Show this *after* it's added to the new-look editor ??

## How do I add an image to a course?

- ?? Show this *after* it's added to the new-look editor ??

## How do I create a new slide?

- ?? Show this *after* it's added to the new-look editor ??

## How do I add an image to a slide?

- ?? Show this *after* it's added to the new-look editor ??

## How do I get from the editor back to the course page?

- ?? Figure this out ??

## How do I view the status of the course build?

- ?? Show this *after* we show how to get from the editor back to the course page ??
