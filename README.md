# Bill-Split React App

This is a simple React application for managing friends and splitting bills with them. It demonstrates the use of React hooks and components to manage state and handle user interactions.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Tech Stack](#tech-stack)
- [Features](#features)
- [Project Structure](#project-structure)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Prashant0110/Bill-Split-React-App.git

Navigate to the project directory:
cd Bill-Split-React-App

Install the dependencies:
npm install

#Usage
Start the development server:
npm start

#TechStack
Frontend: React, JavaScript, CSS
State Management: React hooks (useState)

#Features
Add Friend: Add a new friend with a name and profile picture.
List Friends: Display a list of friends with their balances.
Select Friend: Select a friend to split a bill with.
Split Bill: Split a bill amount with a selected friend, updating the balance accordingly.

#ProjectStructure
src/
├── components/
│   ├── Button.js
│   ├── FriendsList.js
│   ├── Friend.js
│   ├── FormAddFriend.js
│   ├── FormSplitBill.js
├── App.js
├── index.css
├── index.js
public/
├── index.html

App.js: Main component managing the state and rendering child components.
Button.js: Reusable button component.
FriendsList.js: Component to render the list of friends.
Friend.js: Component to render a single friend with selection and balance information.
FormAddFriend.js: Form component to add a new friend.
FormSplitBill.js: Form component to split a bill with a selected friend.



