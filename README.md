### **Tournament Platform **

Our **Tournament Platform** is an all-in-one web application designed to enhance the gaming experience for players, organizers, and admins. It provides a seamless environment for gamers to participate in, organize, and follow gaming tournaments. Our platform also integrates interactive features such as blogs, community forums, AI quizzes, AR interactions, and more, creating a rich ecosystem for gaming enthusiasts. Whether you're a player, organizer, or admin, our platform offers intuitive tools and an engaging community to manage tournaments and connect with fellow gamers.

### **Key Features:**

1. **Tournament Management**  
   - Create, manage, and participate in gaming tournaments. Organizers can set up tournaments, track participants, and update scores, while players can join tournaments, track their performance, and see tournament standings.

2. **AI-Powered Quiz**  
   - A fun and interactive AI-powered quiz to test your gaming knowledge. Players can take personalized quizzes based on their favorite games, characters, and more.

3. **Augmented Reality (AR) Badges**  
   - Unlock badges and special rewards through augmented reality features. Achievements and milestones in tournaments are celebrated with virtual badges.

4. **Community Forums**  
   - A place for players, organizers, and admins to interact, share experiences, discuss strategies, and post updates about ongoing tournaments.

5. **Gaming Blogs & News**  
   - Stay updated with the latest gaming news, tips, reviews, and tournament updates from our integrated blog section, where gamers can also post their insights.

6. **Personalized Dashboards**  
   - Every user (Admin, Player, and Organizer) has access to a personalized dashboard to view important stats, manage tournaments, and interact with the community.

7. **Tournament Results & Leaderboards**  
   - Real-time tournament tracking and leaderboards, so players can see how they rank against others. Match results and tournament updates are shared instantly.

8. **Player Profile & Settings**  
   - Players can manage their profile, update details, and customize preferences. Admins and Organizers can also manage settings for tournaments and user roles.

9. **Notifications & Alerts**  
   - Receive notifications about tournament updates, match results, and new blog posts. Keep track of your upcoming tournaments and matches with reminders.

10. **Secure Login & Registration**  
    - Secure authentication and user verification through UID or account credentials, ensuring a safe environment for all participants.


| **Page**                     | **Description**                                                                                       | **Role**         |
|------------------------------|-------------------------------------------------------------------------------------------------------|------------------|
| **HomePage.js**              | Landing page showcasing featured tournaments, search bar for tournaments, and links to key sections. | All              |
| **LoginPage.js**             | Login form for users, organizers, and admins with role-based redirection.                            | User/Organizer/Admin |
| **RegisterPage.js**          | Register new accounts with role selection and optional organizer credentials verification.            | User/Organizer   |
| **DashboardPage.js**         | Personalized dashboard displaying tournaments, notifications, and achievements based on user roles.   | User/Organizer/Admin |
| **TournamentListPage.js**    | Displays a list of active and past tournaments with filtering and sorting options.                    | All              |
| **TournamentDetailsPage.js** | Detailed view of tournament info, including rules, schedules, and participant lists.                 | All              |
| **CreateTournamentPage.js**  | Form for organizers to create and manage new tournaments.                                            | Organizer        |
| **GamingBlogsPage.js**       | Lists gaming-related blogs and news articles with options for commenting and upvoting.               | All              |
| **CommunityForumsPage.js**   | Forums for creating and discussing threads on gaming topics.                                         | All              |
| **ARBadgesPage.js**          | Displays unlocked badges with AR interaction for added engagement.                                   | User/Organizer   |
| **AIQuizPage.js**            | Interactive quiz page for users to take AI-recommended quizzes based on gaming interests.            | User             |
| **UserProfilePage.js**       | User profile management, including editing personal information and preferences.                     | User/Organizer/Admin |
| **AdminDashboardPage.js**    | Admin panel for monitoring platform activities and moderating flagged content.                       | Admin            |
| **AddBlogPage.js**           | Form for creating new blog posts (admin or approved users only).                                     | Admin/Approved Users |
| **EditTournamentPage.js**    | Allows organizers to update details of their tournaments.                                            | Organizer        |
| **ReportsPage.js**           | Admin view for reviewing flagged content or user-submitted feedback.                                 | Admin            |
| **NotificationsPage.js**     | Displays notifications for all updates, including tournament status, replies, and achievements.      | All              |
| **UserTournamentsPage.js**   | Displays tournaments a user has joined, with links to brackets and schedules.                       | User             |
| **SettingsPage.js**          | Manage account settings, including notification preferences and privacy options.                     | All              |
| **FeedbackPage.js**          | Form for users to submit feedback or report bugs.                                                   | All              |
| **SearchPage.js**            | Advanced search functionality to find tournaments, blogs, and users.                                | All              |
| **LeaderboardPage.js**       | Displays leaderboards for tournaments and quiz scores.                                              | All              |
| **MatchBracketsPage.js**     | Visual representation of tournament brackets with match schedules.                                   | All              |
| **ContactUsPage.js**         | Form for contacting the support team for assistance or inquiries.                                   | All              |
| **FAQPage.js**               | Frequently asked questions covering platform features and usage.                                    | All              |
| **InviteFriendsPage.js**     | Allows users to invite friends to join the platform via email or social media.                      | All              |
| **TransactionHistoryPage.js**| View past payments and refunds related to tournaments or subscriptions.                             | User/Organizer   |
| **SubscriptionPage.js**      | Manage subscription plans for premium features, like advanced analytics or exclusive tournaments.   | User/Organizer   |
| **TermsAndConditionsPage.js**| Legal terms and conditions for using the platform.                                                  | All              |
| **PrivacyPolicyPage.js**     | Privacy policy outlining data usage and security measures.                                          | All              |
| **NotFoundPage.js**          | Custom 404 error page for undefined routes.                                                         | All              |

**Project Structure**
```
TournamentPlatform/
│
├── public/                     # Static assets
│   ├── index.html              # Main HTML template
│   ├── favicon.ico             # Favicon for the app
│   └── assets/                 # Static images, icons, etc.
│       ├── logos/
│       ├── banners/
│       └── badges/
│
├── src/                        # Source files
│   ├── components/             # Reusable UI components
│   │   ├── Navbar.js           # Top navigation bar
│   │   ├── Footer.js           # Footer of the website
│   │   ├── Card.js             # Card component for displaying tournament/blog previews
│   │   ├── Modal.js            # Reusable modal component
│   │   ├── FormInput.js        # Custom input field component
│   │   └── Pagination.js       # Pagination component for lists
│   │
│   ├── pages/                  # Pages for routing
│   │   ├── HomePage.js         # Main landing page
│   │   ├── LoginPage.js        # User login form
│   │   ├── RegisterPage.js     # User registration form
│   │   ├── DashboardPage.js    # User dashboard
│   │   ├── TournamentListPage.js  # All tournaments page
│   │   ├── TournamentDetailsPage.js # Tournament details
│   │   ├── CreateTournamentPage.js  # Form to create tournaments
│   │   ├── GamingBlogsPage.js      # Gaming blogs page
│   │   ├── CommunityForumsPage.js  # Forums for discussion
│   │   ├── UserProfilePage.js      # User profile settings
│   │   ├── AdminDashboardPage.js   # Admin dashboard
│   │   ├── NotificationsPage.js    # Notification center
│   │   ├── FeedbackPage.js         # Submit feedback
│   │   ├── LeaderboardPage.js      # Tournament leaderboards
│   │   ├── ARBadgesPage.js         # Augmented reality badges
│   │   ├── AIQuizPage.js           # AI-powered quiz
│   │   ├── SearchPage.js           # Search results page
│   │   ├── SettingsPage.js         # Account settings
│   │   ├── FAQPage.js              # FAQ page
│   │   ├── ContactUsPage.js        # Contact support
│   │   └── NotFoundPage.js         # 404 error page
│   │
│   ├── layouts/                # Layout components for consistent page structure
│   │   ├── AdminLayout.js      # Layout for admin pages
│   │   ├── UserLayout.js       # Layout for user pages
│   │   └── AuthLayout.js       # Layout for login/register
│   │
│   ├── context/                # Context for global state management
│   │   ├── AuthContext.js      # Authentication context
│   │   ├── NotificationContext.js # Notifications context
│   │   └── ThemeContext.js     # Theme toggling (light/dark mode)
│   │
│   ├── utils/                  # Utility functions
│   │   ├── api.js              # API interaction functions
│   │   ├── validations.js      # Form validation rules
│   │   ├── helpers.js          # Miscellaneous helper functions
│   │   ├── constants.js        # Constants (e.g., API endpoints, roles)
│   │   └── analytics.js        # Event tracking functions
│   │
│   ├── hooks/                  # Custom React hooks
│   │   ├── useAuth.js          # Hook for managing authentication
│   │   ├── useNotifications.js # Hook for notifications
│   │   └── useForm.js          # Hook for form handling
│   │
│   ├── styles/                 # Global and component-specific styles
│   │   ├── global.css          # Global CSS rules
│   │   ├── themes.css          # Theme styles (light/dark)
│   │   └── components/         # CSS for individual components
│   │       ├── Navbar.css
│   │       ├── Footer.css
│   │       └── Card.css
│   │
│   ├── App.js                  # Main app component with routing
│   ├── index.js                # Entry point for React app
│   └── routes.js               # Route definitions
│
├── backend/                    # Backend folder
│   ├── config/                 # Configuration files
│   │   ├── db.js               # MongoDB connection setup
│   │   ├── jwt.js              # JWT token configuration
│   │   └── cors.js             # CORS policy setup
│   │
│   ├── models/                 # MongoDB schemas and models
│   │   ├── User.js             # User schema
│   │   ├── Tournament.js       # Tournament schema
│   │   ├── Blog.js             # Blog schema
│   │   ├── Forum.js            # Forum thread schema
│   │   ├── Badge.js            # Badge schema
│   │   └── Feedback.js         # Feedback schema
│   │
│   ├── routes/                 # API routes
│   │   ├── auth.js             # Authentication routes
│   │   ├── tournaments.js      # Tournament-related routes
│   │   ├── blogs.js            # Blog-related routes
│   │   ├── forums.js           # Forum-related routes
│   │   ├── badges.js           # Badge-related routes
│   │   └── feedback.js         # Feedback routes
│   │
│   ├── middleware/             # Middleware functions
│   │   ├── authMiddleware.js   # Authentication guard
│   │   └── errorHandler.js     # Error handling middleware
│   │
│   ├── controllers/            # Business logic for routes
│   │   ├── authController.js   # Authentication logic
│   │   ├── tournamentController.js # Tournament management logic
│   │   ├── blogController.js   # Blog management logic
│   │   ├── forumController.js  # Forum thread management
│   │   └── feedbackController.js # Feedback handling
│   │
│   └── server.js               # Express.js server entry point
│
├── README.md                   # Project documentation
├── package.json                # Node.js dependencies and scripts
├── .env                        # Environment variables (MongoDB URI, JWT secret)
└── .gitignore                  # Git ignore rules
```

### Additional Features to Highlight in README:
- **Profile Settings**: Enable users to manage their profiles (name, bio, profile picture).  
- **Feedback System**: Allow users to submit bug reports or feature requests.  
- **Responsive Design**: Built to look and work great on all devices.  
- **Role-Based Access Control**: Separate views and permissions for users, organizers, and admins.  
- **AR Interaction**: Unique gamification with Augmented Reality.  
- **Advanced Search**: Filter tournaments by date, type, or location.  
- **Analytics Dashboard**: Admins can view platform statistics (number of users, tournaments, blogs).  


### **Backend Routes for Tournament Platform**

| **HTTP Method** | **Endpoint**                         | **Description**                                         | **Role**               |
|------------------|-------------------------------------|---------------------------------------------------------|------------------------|
| **POST**         | `/api/auth/login`                  | Authenticate user (player or organizer)                | Player/Organizer       |
| **POST**         | `/api/auth/register`               | Register a new user (player or organizer)              | Public                 |
| **GET**          | `/api/auth/logout`                 | Log out the current user                               | Player/Organizer       |
| **GET**          | `/api/auth/user`                   | Get current logged-in user details                      | Player/Organizer       |
| **GET**          | `/api/health/status`               | Check server health and status                         | Public                 |
| **GET**          | `/api/tournaments`                 | Fetch all tournaments                                  | Player/Organizer/Admin |
| **POST**         | `/api/tournaments`                 | Create a new tournament                                | Organizer/Admin        |
| **GET**          | `/api/tournaments/:id`             | Fetch details of a specific tournament by ID          | Player/Organizer/Admin |
| **PUT**          | `/api/tournaments/:id`             | Update a tournament by ID                              | Organizer/Admin        |
| **DELETE**       | `/api/tournaments/:id`             | Delete a tournament by ID                              | Admin                  |
| **POST**         | `/api/tournaments/:id/join`        | Join a specific tournament by ID                       | Player                 |
| **POST**         | `/api/tournaments/:id/leave`       | Leave a specific tournament by ID                      | Player                 |
| **GET**          | `/api/tournaments/:id/leaderboard` | Fetch leaderboard for a specific tournament            | Player/Organizer       |
| **GET**          | `/api/tournaments/:id/matches`     | Fetch all matches for a specific tournament            | Player/Organizer       |
| **POST**         | `/api/tournaments/:id/matches`     | Create a match for a specific tournament               | Organizer/Admin        |
| **PUT**          | `/api/tournaments/:id/matches/:matchId` | Update match details                                  | Organizer/Admin        |
| **DELETE**       | `/api/tournaments/:id/matches/:matchId` | Delete a match in a tournament                         | Admin                  |
| **GET**          | `/api/tournaments/:id/participants`| Fetch all participants for a tournament                | Player/Organizer       |
| **POST**         | `/api/tournaments/:id/participants`| Add a participant to the tournament                    | Organizer/Admin        |
| **DELETE**       | `/api/tournaments/:id/participants/:playerId` | Remove a participant from a tournament         | Admin                  |
| **GET**          | `/api/blogs`                       | Fetch all gaming blogs                                 | Player/Organizer       |
| **GET**          | `/api/blogs/:id`                   | Fetch a specific blog post by ID                       | Player/Organizer       |
| **POST**         | `/api/blogs`                       | Create a new blog post                                 | Admin                  |
| **PUT**          | `/api/blogs/:id`                   | Update a blog post by ID                               | Admin                  |
| **DELETE**       | `/api/blogs/:id`                   | Delete a blog post by ID                               | Admin                  |
| **GET**          | `/api/forums`                      | Fetch all forum threads                                | Player/Organizer       |
| **POST**         | `/api/forums`                      | Create a new forum thread                              | Player/Organizer       |
| **GET**          | `/api/forums/:id`                  | Fetch a specific forum thread by ID                    | Player/Organizer       |
| **POST**         | `/api/forums/:id/reply`            | Add a reply to a forum thread                          | Player/Organizer       |
| **DELETE**       | `/api/forums/:id`                  | Delete a forum thread by ID                            | Admin                  |
| **GET**          | `/api/forums/:id/replies`          | Fetch all replies for a specific forum thread          | Player/Organizer       |
| **POST**         | `/api/forums/:id/replies`          | Post a reply to a forum thread                          | Player/Organizer       |
| **GET**          | `/api/badges`                      | Fetch all available badges                             | Player                 |
| **POST**         | `/api/badges/unlock`               | Unlock a badge for the current user                    | Player                 |
| **GET**          | `/api/notifications`               | Fetch all notifications for the current user           | Player/Organizer       |
| **POST**         | `/api/notifications`               | Create a new notification for a user                   | Admin                  |
| **POST**         | `/api/feedback`                    | Submit feedback about the platform                     | Player/Organizer       |
| **GET**          | `/api/feedback`                    | Fetch all feedback submissions                         | Admin                  |
| **POST**         | `/api/notifications/subscribe`    | Subscribe to tournament notifications                  | Player                 |
| **GET**          | `/api/users/me`                    | Get current logged-in user's profile                   | Player/Organizer       |
| **PUT**          | `/api/users/me`                    | Update user profile (e.g., name, email, etc.)          | Player/Organizer       |
| **POST**         | `/api/users/reset-password`        | Request a password reset                               | Player/Organizer       |
| **PUT**          | `/api/users/reset-password/:token` | Reset password with token                              | Player/Organizer       |

### **Expanded Description for Backend Operations**

#### **User Authentication**
- **/api/auth/login**: Authenticates the user based on their credentials (UID and password). The server returns a JWT token for future requests.  
- **/api/auth/register**: Registers a new user (admin, player, or organizer) by accepting their basic details (name, email, UID, password).  
- **/api/auth/logout**: Logs out the user by invalidating their current session token.  
- **/api/auth/user**: Fetches the current user's details using the JWT token.  
- **/api/users/me**: Allows the user to update their profile information.  

#### **Tournament Management**
- **/api/tournaments**: Allows users (admin or organizers) to fetch a list of tournaments or create a new tournament.  
- **/api/tournaments/:id**: Provides details of a specific tournament (including participants, schedules, etc.). Admins/organizers can update tournament information or delete a tournament.  
- **/api/tournaments/:id/join**: Allows a player to join an existing tournament.  
- **/api/tournaments/:id/leave**: Allows a player to leave a tournament they have joined.  
- **/api/tournaments/:id/leaderboard**: Fetches the leaderboard of a tournament, displaying player rankings based on performance.  
- **/api/tournaments/:id/matches**: Manages tournament matches, allowing the creation, updating, and deletion of individual matches within the tournament.  
- **/api/tournaments/:id/participants**: Fetches the list of participants in the tournament or allows admins to add or remove participants.

#### **Blog and Forum Management**
- **/api/blogs**: Allows fetching of all blogs related to gaming news, tips, and updates. Admins can also create, update, or delete blog posts.  
- **/api/forums**: Manages discussion threads. Users can create new threads, reply to existing threads, and fetch discussions.  
- **/api/forums/:id/replies**: Manages replies to forum threads. Users can interact with other users and ask questions or provide feedback on threads.

#### **Badges and Rewards**
- **/api/badges**: Fetches all available badges for a user to unlock. Badges are tied to achievements or actions within the platform.  
- **/api/badges/unlock**: Allows players to unlock badges based on their in-game or platform achievements.  

#### **Feedback and Notifications**
- **/api/feedback**: Allows users to submit feedback on the platform or any tournament. Admins can review submitted feedback for improvements.  
- **/api/notifications**: Allows users to receive and view notifications regarding new tournaments, match results, or updates. Admins can create notifications for players.

#### **Profile and Settings**
- **/api/users/me**: Users can update their personal details (name, email, profile picture) within their dashboard.  
- **/api/users/reset-password**: Provides a way for users to reset their password in case they forget it. A reset token will be sent via email.

---

### **Security Considerations**
- **JWT Authentication**: All requests requiring authentication should include a valid JWT token.
- **Role-based Access Control**: Only admins, organizers, or players with the right role should have access to specific routes (e.g., only admins can create or delete tournaments).
- **Input Validation**: Ensure input is properly validated, particularly for sensitive information like passwords, emails, and user profiles.

Certainly! Here is the expanded **Organizer Role** along with the **Admin** and **Player** roles for the Tournament Platform:

### **Usage**

#### **Admin Role**
1. **Login as Admin**  
   - Use your admin credentials to log in to the platform.
   - After logging in, you will be directed to the **Dashboard**, where you can manage tournaments, participants, and other key platform features.

2. **Manage Tournaments**  
   - Create, update, or delete tournaments via the **Tournaments** section.
   - View details of existing tournaments and add or remove participants.
   - Manage tournament matches and update the tournament leaderboard.

3. **Manage Players**  
   - View player profiles, including details such as name, UID, and status.
   - Add new players to tournaments or remove them from existing ones.

4. **View and Manage Blog Posts**  
   - Create, edit, or delete blog posts about tournaments, gaming news, or platform updates.

5. **Manage Feedback**  
   - View and respond to feedback submitted by players and organizers to improve the platform experience.

6. **Notifications**  
   - Create and manage notifications to keep players informed about upcoming tournaments, results, and updates.

---

#### **Player Role**
1. **Login as Player**  
   - Use your credentials (UID and password) to log in.
   - After logging in, you will be directed to the **Dashboard**, where you can view your tournament history and leaderboard standings.

2. **Join or Leave Tournaments**  
   - Navigate to the **Tournaments** section to view available tournaments.
   - You can join a tournament by clicking **Join Tournament** or leave it by clicking **Leave Tournament**.

3. **View and Participate in Matches**  
   - See your upcoming matches and track your performance in each tournament.
   - View tournament progress, leaderboard standings, and individual match results.

4. **View and Manage Your Profile**  
   - Update your personal details, including name, email, and profile picture in the **Profile Settings** section.
   - You can also change your password or reset it if forgotten.

5. **Unlock Badges**  
   - Earn badges by completing milestones, winning tournaments, or participating in activities.

6. **Forum and Blog Interactions**  
   - Participate in forum discussions by creating new threads or replying to existing ones.
   - You can also comment on blog posts to share your thoughts on gaming topics.

7. **View Feedback**  
   - Submit feedback about your experience with the platform, tournaments, and any suggestions for improvements.

8. **Notifications**  
   - Receive notifications for upcoming tournaments, matches, results, or platform updates.

---

#### **Organizer Role**
1. **Login as Organizer**  
   - Use your organizer credentials to log in to the platform.
   - After logging in, you will be directed to the **Organizer Dashboard**, where you can manage your tournaments, participants, and match schedules.

2. **Create and Manage Tournaments**  
   - Organizers have the ability to **create** new tournaments by specifying the game, format, rules, and schedule.
   - Organizers can **edit** tournament details such as adding or removing participants and changing match schedules.

3. **Invite and Manage Participants**  
   - Organizers can **send invitations** to players to join the tournament.
   - View participants, track their registration status, and remove participants when needed.

4. **Match Scheduling**  
   - Organizers can **schedule matches** for the tournament and assign participants to specific rounds or brackets.

5. **Leaderboard Management**  
   - Keep track of player progress, manage match outcomes, and update the **leaderboard** after each round.

6. **Live Updates**  
   - Provide **live updates** for ongoing matches in the tournament, including match results and upcoming games.

7. **Communicate with Participants**  
   - Send announcements and updates regarding the tournament through **notifications** to ensure that participants stay informed.

8. **View and Manage Tournament Results**  
   - After the tournament, organizers can view the final **tournament results** and generate reports for distribution.

9. **Manage Forum Discussions**  
   - Organizers can create or moderate discussion threads in the community **forums** to enhance player engagement and provide event-related news.


Environment Variables
To run this project, create a .env file in the root directory with the following values:

MONGODB_URI=<your-mongodb-uri>
PORT=5000
JWT_SECRET=<your-secret-key>
Installation & Setup
Prerequisites
Node.js and npm installed
MongoDB installed and running locally or on a cloud service (e.g., MongoDB Atlas)
Arduino setup with RFID integration for UID reading
Steps
Clone the repository

git clone https://github.com/ucs200525/medico.git
Navigate into the project directory

cd medico
Install server dependencies

npm install
Install client dependencies

cd client
npm install
Set up environment variables
Create a .env file in the root directory and add the required values (as shown above).

Run the project
To start both backend and frontend:

npm run server   # Starts the backend server
npm start        # Starts the frontend React application
