# Internship-Logbook-Neksjojb

## Friday, February 3, 2023, 

I started my journey as a web developer intern. Sir Ralph assigned me a task to create a simple CRUD (Create, Read, Update, Delete) application, which would be a project for all the web developer interns.

To start with, I decided to study the Laravel blade templating engine. After getting a good hold of it, I created an initial design for my CRUD application and pushed it on Github so that I can continue working on it at home.

## Monday, February 6, 2023

On this day, I was focused on finishing the main functionality of my CRUD app. I took the time to refine the look of the buttons and transformed them into reusable components. This made the code easier to read and maintain. Additionally, I added alert messages to the app to provide more visual feedback to the user.

## Tuesday, February 7, 2023

I made some minor modifications to the app and added a loading animation and close button to the alerts. These small touches helped to enhance the user experience and make the app feel more polished.

## Wednesday, February 8, 2023

I created new accounts for Github, Postman, and Mailtrap using my work email. I spent some time studying Laravel's Mailable class, which is used to send emails. As a demonstration of my newfound knowledge, I made a simple app using Laravel that sends a test email to my Mailtrap account and pushed it on Github.

## Thursday, February 9, 2023

Sir Ralph conducted a code review of my CRUD application, "movie-app". After the review, I did some research into Laravel's custom form requests, middleware, and group routing, as these are important features that can help me build better apps.

## Friday, February 10, 2023

I focused on learning about Laravel's model eloquent relationships. I started building a new app using Laravel with the Breeze package, which provides a simple, minimalistic starting point for Laravel projects. I created a Post model that has a foreign key constraint with the User model, which is a common pattern in web development. I pushed my unfinished app to Github so that I can continue it  at home.

## Monday, February 13, 2023

I continued my unfinished project. I added the basic layout and upload feature.

## Tuesday, February 14, 2023

I encountered a technical problem that I needed to solve. Specifically, I needed to find a way to allow the like count to update automatically when a user liked a post, without requiring the browser to refresh.

## Wednesday, February 15, 2023

Our supervisor gave me a new task to work on - creating a backend API for a job board project. He provided us with a repository link to get started. I am excited to work on this new project and were determined to create an efficient API that would meet all the requirements for the job board. I immediately began working on the API.

## Thursday, February 16, 2023

In our Laravel API project, we had a few tasks to accomplish. We started by adding an applicant and employer model, followed by the employer and applicant migration. We also added the employer and applicant seed to the project. Next, we created a job model, migration, and factory, and unguarded the models to allow for easy database seeding. Finally, we added a job seed to complete the process. As we worked on these tasks, we ensured that our code was clean and efficient, ready for implementation into the project. We felt that our progress was good, and we were excited to continue working on the project.

## Friday, February 17, 2023

In our Laravel API project, we had a list of tasks to complete. We started by creating an AuthController and LoginRequest to allow users to log in securely. We added authentication routes and created a form request for JobUpdate and JobStore. Additionally, we added JobResource to help us manage and display job data effectively. We also created a JobController and added ability and abilities to Kernel.php. We added the applicant and employer auth guard and used authorization to control access to various routes. As we worked, we encountered and fixed a few issues, such as undefined web guard, login data access, 404 response customization, and response macros. Finally, we refactored the JobController response for better readability and efficiency. We were confident that these changes would contribute to the overall success of the project.

## Monday, February 20, 2023

Our Laravel API backend project received some updates to enhance its performance and user experience. First, we made the decision to centralize all the exception handling in handler.php, which would make it easier to manage and maintain. Additionally, we added a new response macro that would enable authenticated users to navigate the site more effectively. Finally, we updated the auth login controller to ensure that the login process was secure and user-friendly. These changes would improve the overall functionality and usability of the project, and we were confident that they would have a positive impact on our users.


## Tuesday, February 21, 2023

Started adding new routes to the system. These routes were essential to support upcoming features and improve the overall user experience.

## Wednesday, February 22, 2023

To better manage the administrative functions of the system, we added controllers for admin users. These controllers would handle all the admin-related tasks, such as managing users, job postings, and other crucial data.

## Thursday, February 23, 2023

We worked on fixing the folder structure of the project to make it more organized and easier to navigate. This involved moving files to their correct locations and renaming some folders to improve the overall structure of the project.

## Friday, February 24, 2023

We installed a popular package that provides a simple and flexible way to manage user permissions and roles. With this package, we could easily define and assign roles to users and restrict access to specific parts of the application.

## Monday, February 27, 2023

We separated the JobController into two separate controllers: one for handling get requests and the other for post/update/delete requests. This separation made the code cleaner and easier to manage.

## Tuesday, February 28, 2023

We made an update to the project by separating the users AuthController. The aim was to provide a more efficient and personalized authentication process to our users. Prior to this change, the users' authentication process was handled by a single controller, making it difficult to distinguish between different types of users. With this change, we were able to create more specific authentication methods for each type of user, allowing them to have a more targeted and streamlined experience while using our platform. This modification was crucial in improving the overall user experience of our application.

## Wednesday, March 01, 2023

I added a new feature which is the creation of a separate table for the resume, which has allowed us to improve the data organization of our system. This update has enabled us to manage the user's resume more efficiently and effectively

## Thursday, March 02, 2023

Added a new feature that allows users to search for employers. This feature is essential as it enhances the user experience of the platform and helps job seekers to connect with potential employers more easily. We are confident that these updates will enhance the overall user experience of our Laravel API backend, making it a more robust and efficient tool for job seekers and employers alike.

## Friday, March 03, 2023

We implemented several significant updates to our project. The first update was the addition of a new feature that allows users to search for jobs, which will help job seekers find employment more easily.

The second update was the creation of a relationship between jobs and employers. This update has allowed us to better organize the job data and provide users with a more targeted job search experience.

Lastly, we added a new feature that allows authenticated applicants to edit their profiles. This feature is essential as it enables applicants to update their profiles as they gain new skills and experiences.

We believe that these updates will significantly enhance the user experience of our Laravel API backend, making it a more efficient tool for both job seekers and employers.

## Monday, March 06, 2023

I made some updates to our project aimed at enhancing the user experience. One of the significant updates is the addition of an avatar model, routes, and relationships to allow users to upload profile pictures. I also created new routes for the employer profile, added an employer hasOne relation to avatar, and updated the validation rules.

These updates will enable users to personalize their profiles by adding profile pictures, making their profiles more attractive to potential employers. The changes made ensure that our platform remains user-friendly, efficient, and accessible to both job seekers and employers.

## Tuesday, March 07, 2023

I added new controllers for job applications, one for applicants and one for employers. Additionally, I created a new relationship between jobs and applications, allowing job seekers to submit applications to jobs.

I also added the ability for employers to view posted jobs, which enables them to manage their job postings more efficiently. Lastly, I updated the employer routes to improve navigation.

These updates will ensure that our platform remains user-friendly, efficient, and accessible to both job seekers and employers, enabling them to manage job applications and postings with ease.

## Wednesday, March 08, 2023

I added a new feature to our project, allowing applicants to save jobs they are interested in. This feature enables job seekers to save jobs for later viewing or application. Additionally, we updated the scopes code, making it more efficient and less prone to errors.

These updates will improve the user experience, making it easier for job seekers to manage job applications and postings on our platform.

## Thursday, March 09, 2023

I shortened the scopes code in our project, making it more efficient and less prone to errors. Scopes are used to filter and sort data, enabling users to find the information they need more efficiently.

These updates will improve the performance of our platform, making it faster and more reliable for our users.

## Friday, March 10, 2023

I added a new notification feature to our Laravel API backend. This feature enables employers to receive notifications when someone applies for a job posting. The notification system ensures that employers stay informed about new job applications in real-time, improving their ability to manage and respond to job applications promptly.

These updates will improve the communication process between employers and job seekers, making it easier for both parties to stay informed about the status of job applications.

## Monday, March 13, 2023

I updated the applicants' applications route in our backend. This update ensures that job seekers can easily manage their job applications. The new applications route provides users with a more streamlined and user-friendly interface for managing their job applications.

These updates will improve the overall user experience on our platform, making it more efficient and reliable. It will also make it easier for job seekers to manage their job applications, increasing their engagement with our platform.

## Tuesday, March 14, 2023

Today, I found myself with nothing to do since my supervisor was unavailable, and he did not respond to my queries. Instead of waiting around, I decided to work on updating my portfolio design and contents to make it more presentable and professional. I took the opportunity to study and research ways to improve my project, looking for new ideas and techniques that I could implement. By doing so, I not only kept myself productive but also learned new skills that I could apply in my work. This experience taught me the value of using downtime productively and taking responsibility for my own learning and development.
