# Any Chat Project

Hello to [BigDevSoon](https://bigdevsoon.me/) 👋

Create a real-time application that allows users to message each other.

## How to start

1. Start the project in our [app](https://app.bigdevsoon.me/) to get a feel for it.
2. Review the requirements listed below in this README.
3. Go through the design images on the [project's page](https://app.bigdevsoon.me/projects/any-chat) and import the `.fig` file into Figma to understand the layout and design elements.
4. Clone this repository or use [GitHub Codespaces](https://github.com/features/codespaces) to set up the project environment.
5. Choose your preferred technology stack and overwrite repository files as needed to set up your project structure. We included a few files and the `assets` folder for convenience, extracted from the design.
6. Begin coding, either using the Freerun mode to work on each card individually or the Speedrun mode to work at your own pace. Be sure to follow the guidelines outlined below.
7. Have a strong desire to learn and improve your skills as a Big Developer. 🚀

## Requirements

- [ ] Create an onboarding page that includes a logo, a title, and a "Get Started" button. The page should feature a split-view layout with two columns. The right column should have a different background and display an image of a hand holding a phone.
- [ ] Navigate the user to a centered page with the logo after clicking the "Get Started" button. On this page, users should be able to enter a nickname for the chat. The nickname should be validated to ensure it is between 4 and 60 characters in length. The "Join Chat" button should only be clickable when the nickname is properly validated. Clicking the button should move the user to the main chat page.
- [ ] Set up a simple Node.js server using this [tutorial](https://socket.io/get-started/chat). Integrate the server with both the frontend and backend using socket.io and express.js. Keep track of connected users in an array and messages in an array of objects.
- [ ] Enhance the main chat page with a header that displays the logo and the number of online users. Retrieve this information from the connected user's array on the Node.js server.
- [ ] Create a chat window as the main content of the main chat page. The chat window should occupy most of the page and display messages from top to bottom. Implement scrolling when the messages exceed the height of the chat window. For now, you can mock the messages.
- [ ] Add a footer section to the main chat page. The footer should include an emoji icon on the left, a text input with a placeholder of "Send a message...", and a disabled send icon.
- [ ] Allow users to send messages by enabling the send icon when at least one character is entered in the text input. Limit the message length to a maximum of 1000 characters (or more). After sending a message, display its content, the nickname (displayed as "You" for the sender or the user's nickname for others), the date in the format "hh:mm", and the position of the message (your messages on the right, other user messages on the left). Store the messages on the Node.js server and render them in the chat window from top (oldest) to bottom (newest).
- [ ] Integrate an external library to add emoji support, allowing users to incorporate emojis into their messages by clicking the emoji icon.
- [ ] When a user connects or disconnects, send a system message in the middle of the chat. Merge these system messages with other messages based on the sending date and time. Update the online user counter in the header accordingly.
- [ ] Handle edge cases when users refresh the browser to ensure they are redirected to the appropriate page based on their connection status (main chat page when connected, onboarding page when disconnected, or connecting for the first time). Improve the overall user experience and user interface of the chat application. Additionally, ensure all other edge cases are handled properly.

## Guidelines

1. Aim for pixel-perfect implementation of the design. Use tools like [PixelParallel](https://chrome.google.com/webstore/detail/pixelparallel-by-htmlburg/iffnoibnepbcloaaagchjonfplimpkob?hl=en) or other techniques to ensure accuracy.
2. Write clean and efficient code. Use extensions like [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) and [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) for formatting and errors, and consider using [GitHub Copilot](https://github.com/features/copilot) and [VSCode](https://code.visualstudio.com/) as your code editor.
3. Follow a [GitHub flow](https://docs.github.com/en/get-started/quickstart/github-flow). Keep your commits small and descriptive, organize your work into separate branches, and use pull requests for code reviews.

Remember, the cleaner and more accurate your code is, the faster you can finish and the better you'll feel about your work.
So let's make it happen! 💡

## Submitting project

Once you've completed the project and unlocked the Submit step in our app, it's time to deploy your project to [Vercel](https://vercel.com/), [Netlify](https://www.netlify.com/), or [GitHub Pages](https://pages.github.com/) (if you haven't done so already). Keep in mind that we've added a `<bds />` tag to the `index.html` file, and we'll check for it when you submit your Project URL. So don't forget to include it! You'll also need to provide the project title and the primary frontend technology used. Good luck!

## We're in Beta and getting better every day!

Hey there, Big Developer! We wanted to take a moment to thank you for participating in our project and helping us improve our platform. We're always looking for ways to make our app better, so if you have any feedback or suggestions, please feel free to let us know.

Happy coding! 🚀
