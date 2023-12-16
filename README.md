
# **Todo List App Development Guide**

## **1. Environment Setup**

- Install Node.js, the React Native CLI, and set up PocketBase.

## **2. App Structure**

Your app will consist of several key components:

### **2.1 Home Screen**

- Display the todo items in a list format.
- Include an input bar at the bottom for adding new tasks.

### **2.2 Task Categories**

- Create four categories or "pills" for tasks: Urgent, InProgress, Hold, and Later.
- Each category should be color-coded.

### **2.3 Task Details**

- When a task is clicked, navigate to a new screen that displays the task details.
- Users should be able to update the status of the task from this screen.

### **2.4 New Task Screen**

- This screen is for adding new tasks.
- Users should be able to input a title, select a status, add a description, and optionally add an image to their task.

## **3. Data Storage with PocketBase**

- Set up your PocketBase schema to store your tasks.
- Each task will have a title, description, status, and optional image.

## **4. Image Handling**

- Use a library like `react-native-image-picker` to handle image selection.
- Store the selected images in PocketBase.

## **5. Styling**

- Use the `StyleSheet` component in React Native to style your components.
- Define styles for your list items, input bar, task categories, and other UI elements.

## **6. Testing**

- Test your app on both iOS and Android to ensure it works as expected.
- Use libraries like Jest for unit testing and Detox for end-to-end testing.

