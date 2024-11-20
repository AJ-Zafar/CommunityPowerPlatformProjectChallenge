---
name: Submit Project for the Challenge
about: Use this to submit your completed project
title: ''
labels: Project Submission
assignees: AJ-Zafar

---

name: Submission Template
description: Use this form to submit your solution for feedback
title: "[Submission] Your_Project_Name"
labels: submission
body:
  - type: input
    id: participant_name
    attributes:
      label: Participant Name
      description: Enter your full name.
      placeholder: John Doe
  - type: input
    id: project_name
    attributes:
      label: Project Name
      description: Enter the name of the challenge you chose (e.g., Collaborative To-Do List App).
      placeholder: Collaborative To-Do List App
  - type: textarea
    id: project_description
    attributes:
      label: Project Description
      description: Provide a brief overview of your solution, its features, and any bonus features you included.
      placeholder: My app allows users to create shared to-do lists with priority sorting and progress tracking.
  - type: textarea
    id: challenges_encountered
    attributes:
      label: Challenges Faced
      description: Describe any challenges you faced while building your solution.
      placeholder: I struggled with implementing the sorting functionality and resolved it by using a conditional column.
  - type: textarea
    id: feedback_focus
    attributes:
      label: Areas for Feedback
      description: Let us know which parts of your app you’d like specific feedback on (e.g., UX, functionality, or bonus features).
      placeholder: I'd love feedback on how I implemented the progress bar and any UX improvements.
  - type: file
    id: zip_file
    attributes:
      label: Upload Your .zip File
      description: Attach your solution as a .zip file (named as yourname_projectname.zip).
      accept:
        - application/zip