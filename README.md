# Angular Interview Exercise

## Instructions

Your task is to complete the blog post web app. There are a list of tasks below that you need to complete. It is not expected that you complete all tasks in the time frame. We will
reserve the last 10 minutes of the interview to implement the tests.

### Notes

- `BlogService` class provides a mock API to use
  - No changes are required in this file, you can treat it as a generated file
  - If you find you need to change this file you may - please add comments explaining reasoning if so
- Make use of Angular Material components where possible / where it will save time: https://material.angular.io/components/categories
- Feel free to ask any questions or make assumptions where appropriate. If you are unsure of something, please say so.

### Tasks

1. **Refactor Post List**

   - Refactor and create a new component `post-card`
   - Use this component to display post cards in the post list

2. **Add "Create Post" Functionality**

   - Add a new route and component for creating a new post
   - Implement a form with the following requirements:
     - Title field (required)
     - Content field (optional)
     - Form validation to prevent saving if invalid
   - Note: A navigation button for this form already exists in the header

3. **Enhance Post Detail Page**

   - Correctly implement functionality to fetch and display the specific post that the user clicked on

4. **Add "Edit Post" Functionality**

   - Add an edit button to each post card
   - Create a new form for editing posts with the following requirements:
     - Title field (required)
     - Content field (optional)
     - Form validation to prevent saving if invalid

5. **Implement "Delete Post" Functionality**

   - Add a delete button to each post card
   - Implement post deletion
   - Refresh the post list after successful deletion

6. **Testing**
   - Complete all stubbed tests
   - Add additional tests as you see fit
   - Ensure all tests are passing
