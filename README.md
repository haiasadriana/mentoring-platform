# mentoring-platform
Starting from the idea of Jedis who seek to improve individuals and groups they come in contact with, the mentoring platform has the aim to connect professionals and padawans with the purpose of knowledge exchange. The main focus will be on the students in universities or highschools. They will be able to connect with each other based on a CV or portfolio. If a student wants to share his knowledge in a field, he can apply to mentor others that need help. The mentors will be able to offer the padawans orientation documentation and training materials, as well as examinations. 
An MVP mentoring-platform would:
1. store the orientation documentation of the mentors;
2. provide a step-by-step approach through achieve a goal;
3. provide the padawan with materials related to achieve the goals set.

Users categories are as follows:
1. Administrator 
2. Mentor
3. Padawan (trainee, the person who seeks mentorship)
4. Guest

1. Administrator:

2. Mentor:
-a mentor must be able to:
  - log into his profile
  - have a transcript of his padawans and their information
  - upload training documentation
  - assign documentation based on the training purpose of a padawan
  - monitor the padawans' progress and send feedback to them based on evaluations
-a mentor's profile will contain:
  - an about me section - FirstName, LastName, DateOfBirth, PhoneNumber, Email, Fields, Portfolio, Photography
  - my padawans sections - FirstName, LastName, TrainingPurpose/Goal, StartDate, EndDate, ModulesNeeded, ModulesDone, Feedback/Grade. Once a padawan completes a module, it moves in the section ModulesDone. In this way the section ModulesNeeded will display a kind of ToDo.
  - my documentation - searchable by field - mathematics, physics, etc. Each documentation field contains Type (book, url, image), DateAdded
  - feedback section - feedback given by the padawans

3. Padawan
-a padawan must be able to:
  - log into his profile
  - have a transcript of his training courses
  - see his mentors' feedback
  - search for mentors by field
  - connect with a mentor
  - give feedback to a mentor
-a padawan's profile will contain:
  - an about me section - FirstName, LastName, TrainingPurpose, StartDate(default=the day he connects with the mentor), EndDate, DateOfBirth, PhoneNumber, Email, Photography
  - a transcript of trainings - all trainings (can be sorted by completed, purpose, due date) - TrainingName (ex. Learn physics), EndDate, TrainingPurpose/Goal (ex. self-improvement, need to pass, etc), ModulesNeeded, ModulesDone
  - feedback section - feedback given by the mentor
-once a padawan clicks on a training in his transcript of trainings, he can access the documentation the mentor is offering. 
 
4. Guest
-a guest must be able to:
  - sign up for a profile 
  - search mentors by field
  - visualize a mentor's profile
  
  
  
 

