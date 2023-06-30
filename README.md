# React Split Bill App

This is a React application called "React Split Bill App" that helps users split bills with their friends. The app allows users to manage a list of friends, select a friend to split a bill with, and calculate the split amount based on the bill value and who is paying. The app also provides options to add new friends and keeps track of the balances between the user and each friend.

## Functionality

The React Split Bill App provides the following functionality:

- **Friends List**: Displays a list of friends with their names, profile images, and balances. The balance is color-coded to indicate whether the friend owes the user money (in red) or the user owes the friend money (in green). If the balance is zero, it indicates that the user and the friend are even.

- **Selecting a Friend**: Users can select a friend from the list to split a bill with. When a friend is selected, additional options for splitting the bill are displayed.

- **Splitting a Bill**: Users can enter the bill value and the amount paid by the user. The app calculates the amount owed by the friend based on the selected payment option (user or friend). The balances are updated accordingly.

- **Adding a Friend**: Users can add new friends by providing their name and profile image URL. The new friend is added to the friends list with an initial balance of 0.

## Getting Started

To run the React Split Bill App locally, follow these steps:

1. Clone the repository: `git clone [repository_url]`
2. Navigate to the project directory: `cd react-split-bill-app`
3. Install the dependencies: `npm install`
4. Start the development server: `npm start`
5. Open the app in your browser at `http://localhost:3000`

## Technologies Used

The React Split Bill App is built using the following technologies:

- React: A JavaScript library for building user interfaces.
- useState: A React Hook for managing state within functional components.
