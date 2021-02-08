## Goal

The Goal of this tech test is to test your knowledge with Ruby on Rails. This tech test will cover a couple of concepts that you will need to use in order to complete this test.

## Challenge

- Create a chat app using Ruby on Rails. The app should have an authentication system for users to log in and access the chats.
- Each message should be broadcasted to all the users in the chat via websockets (by using `ActionCable`).
- Each message should be sent via a background job to make sure the interface doesn't freeze when sending a message.
- A user should be able to switch between chats without having to reload the page every time.
- The messages should be marked as read when appropriate.

## Bonus
- Implement some tests using Rspec to make sure your app is robust
