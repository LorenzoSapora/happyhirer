## HappyHirer

A very small, light job board with complete transparency on both sides of the hiring process.


## Goals

### Applicant

- Submit applications
- See number of applications
- See application status
- Get feedback on application
- See rough ranking against other applicants

### Hirer

- Get applications
- Review applications
- Provide feedback
- Use your own email (jobs@company.com)
- Use our version or self-host
- 

## Ideas

- Set requirements for the applicant (ex: GitHub, fav recent project, biggest project, etc.)
- Sections for feedback
    - Email
    - CV
    - Cover letter
    - [requirements for applicant] ex GitHub
    - 
- Option to tick sections off with just a :thumbsup:
- For each section, allow a 'notes' section for minor points on each section. Not a neg/pos, but more a point to bring up. ex: `linked-in should be linkedin`
- Private notes for the employer
- Generate a report at the end of the campaign for the employer
- Generate a report at the end of the campaign for the applicant

## Flow

- `Employer` creates a `Job`
- `Job` has `Goals` such as
  - Email Copy
  - Cover Letter
  - CV
  - GitHub
  - Your favorite personal project
  - Your most challenging commercial project (if applicable)
  - Anything else you feel can convey your skills
- `Employer` advertises `Job`

- `Candidate` creates `Application` while applying for `Job`
- `Application` has 
  - asda
-  

## Tasks

- Create Job::class (the campaign)
- Create Candidate::class (the applicant)
- Create Application::class (the candidate->application)
- Create Employer::class (the client)
- Create Goal::class (a job->goal)
- Create GoalNotes::class (goal notes)
- Create PostPrivateNotes::class (post private notes)
- Create PostPrivateNotes::class (post private notes)
