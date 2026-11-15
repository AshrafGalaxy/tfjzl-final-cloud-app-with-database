# Online Course App with Assessment Feature

This repository contains the Django-based Online Course application extended with an exam assessment feature, built as part of the IBM Full Stack Cloud Developer curriculum.

## Features Implemented
- **Data Models**: Added `Question`, `Choice`, and `Submission` models with scoring logic (`is_get_score`).
- **Django Admin Customization**: Integrated `QuestionInline` in `LessonAdmin` and `ChoiceInline` in `QuestionAdmin` across 7 registered model classes.
- **Exam Workflow**:
  - Course details view embeds an interactive exam form styled with Bootstrap 4.
  - Form submission handles answers via the `submit` view and saves learner choices.
  - Results evaluation computes final grade and highlights correct vs. incorrect answers in `exam_result_bootstrap.html`.

## ER Diagram
![Onlinecourse ER Diagram](static/media/course_images/onlinecourse_app_er.png)

## Verification Screenshots
- `03-admin-site.png`: Django admin dashboard displaying Authentication and OnlineCourse sections.
- `07-final.png`: Successful exam result page with score and congratulatory feedback.
