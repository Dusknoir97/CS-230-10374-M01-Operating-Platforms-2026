# CS-230-10374-M01-Operating-Platforms-2026

## The Gaming Room Software Design Document

### Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?

The Gaming Room was a client that wanted to expand their existing Android game, Draw It or Lose It, so it could run on different operating systems and devices. The game involves teams competing to guess what an image represents before time runs out. The client needed a web-based application that could support multiple players and teams while making sure each game, team and player had a unique identifier. They also wanted the application to be secure and able to handle more users as the game grew.

### What did you do particularly well in developing this documentation?

I think I did a good job comparing the different operating systems and explaining which one would work best for the application. I looked at Windows, Linux, macOS and mobile platforms to understand their strengths and limitations. I also explained why Linux would be a good choice for hosting the game because of its flexibility, security features and lower licensing costs. This helped me understand how choosing an operating system can affect the overall performance and development of an application.

### What about the process of working through a design document did you find helpful when developing the code?

Working through the design document helped me understand why planning is important before starting to write code. Breaking down the requirements made it easier to see how different parts of the application needed to work together. Using the singleton pattern for the GameService class helped make sure there was only one instance managing the games. Creating the UML diagram also helped me understand how the classes were connected and what responsibilities each one had.

### If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

If I could go back and revise one part of my work, I would spend more time on the system architecture section. I feel like I could have gone into more detail about how the server would communicate with different devices and how the application would handle a larger number of players. I would also include more information about how the system could be expanded in the future without affecting the players already using it.

### How did you interpret the user's needs and implement them into your software design? Why is it so important to consider the user's needs when designing?

I started by looking at what The Gaming Room wanted the application to accomplish. One of their biggest requirements was allowing players to access the game from different devices instead of being limited to Android. I recommended a web-based client-server design so the main game logic could run on a server while players connected through their devices. I also considered security, performance and how the application would manage multiple games at once. Understanding the user's needs is important because even if an application works correctly, it won't be successful if it doesn't do what the client actually needs.

### How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

My approach was to understand the client's requirements first and then figure out what technologies and design patterns would best support them. I used UML diagrams to visualize the relationships between classes and looked at different operating systems to compare their capabilities. I also considered how memory, storage, security and network communication would affect the application. In the future I would continue using design documents and diagrams before coding because they help identify potential problems early and make the development process more organized.
