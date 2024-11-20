# Power Platform Challenge 2024 🚀

Welcome to **The Power Platform Challenge**! This is an opportunity to tackle real-world app-building scenarios, sharpen your skills, and receive feedback on your solutions. Showcase your work, gain valuable experience, and add this project to your portfolio or just get involved to have some fun! 🌟

This has been created off the back of a lot of people asking for suggestions for projects to build their experience and evidence skills after they complete things like the Power Up Program, PL-900 and other Power Platform Training. If this is appreciated and popular I will do more of these with different challenges. Give these a try especially if you are looking to build up some confidence or just have some fun! 

Try to build solutions using Dataverse as the Datasource rather than Sharepoint. If you have any issues with this let me know.

I will be taking part in building these and sharing how I might tackle these challenges for those interested 🙂.

---

## 🎯 Challenge Categories

### **Challenges if you are just getting started**

**1. Collaborative To-Do List App**
   - Build a shared to-do list app where multiple users can:
     - Add tasks with a title, description, and due date.
     - Mark tasks as "Completed" or "Pending."
     - Include a search box to find tasks by title.
   - **Features**:
     - Group tasks by status ("Pending" and "Completed").
     - Provide a clear interface for adding, editing, and deleting tasks.
   - **Bonus Features**:
     - Add a "Priority" column to sort tasks.
     - Allow users to switch between sorting by due date and "Priority."
     - Display a progress bar based on completed tasks.
     - Enable collaborative commenting on tasks (e.g., leave notes or updates).

**2. Lost and Found System**
   - Create an app to log and match lost and found items where users can:
     - Log an item as "Lost" or "Found" with:
       - Item description (e.g., "Black wallet with initials JD").
       - Date and location (e.g., "Lost at City Park in Birmingham on 2024-11-12").
       - Optionally upload an image.
     - View all logged items in a gallery, filterable by:
       - Status (Lost or Found).
       - Location or date range.
   - **Features**:
     - Admin functionality to:
       - Match "Lost" items with "Found" items based on descriptions or images.
       - Notify users of potential matches using email or Teams.
   - **Bonus Features**:
     - Add item categories (e.g., electronics, clothing, personal documents).
     - Show statistics, such as:
       - Total items logged.
       - Number of items successfully matched.

---

### **Medium Challenges**

**3. Habit Tracker with Rewards**
   - Design an app to help users track daily habits where users can:
     - Add habits with titles, descriptions, and category (e.g., "Health," "Work").
     - Mark habits as completed for each day in a week.
   - **Features**:
     - Display:
       - A progress bar for each habit over a week.
       - A streak counter showing the number of consecutive days the habit was completed.
       - A summary view showing the user's most completed habits.
     - Implement a simple reward system:
       - Assign points for each completed habit.
   - **Bonus Features**:
     - A dashboard showing:
       - Total points.
       - Longest streaks.
       - Categories with the most tracked habits.
     - Notifications or reminders for incomplete habits.
     - Weekly progress reports sent to the user's email summarising counts of what they have done.

**4. Event Planner App**
   - Develop an app to plan and manage events where users can:
     - Create events with details, including:
       - Event name, description, date, time, and location.
       - Capacity limits and ticket types (if applicable).
     - Invite attendees by email.
     - Users can RSVP by clicking a link in the email which takes them to the app.
     - View RSVP statuses (Accepted, Declined, No Response).
   - **Features**:
     - Display:
       - Upcoming events in a calendar view.
       - RSVP summaries with a breakdown of attendee statuses.
     - Send automated email reminders.
   - **Bonus Features**:
     - Enable users to upload files for events (e.g., agendas, flyers).
     - Add a waitlist feature that automatically notifies users if spots become available.
     - Include a feedback form for post-event reviews.
     - Try deep linking from the email directly to a form for them to RSVP/See the event.

---

### **More Challenging Challenges**

**5. Retro Arcade Quiz Game**
   - Build a retro-style quiz game where users can:
     - Start a new game and answer multiple-choice questions.
     - Earn points based on correct answers and question difficulty.
   - **Features**:
     - Include:
       - A leaderboard showing top scores.
       - A timer for each question (e.g., 10 seconds).
       - The ability to pause and resume the game.
     - Admin functionality to:
       - Upload and manage quiz questions and answers in a table.
       - Organize questions by categories.
   - **Bonus Features**:
     - Add power-ups like:
     - Implement dynamic question difficulty where harder questions yield more points.
     - Include fun animations or sound effects for correct/incorrect answers.

**6. Scalable Multi-Site Desk and Room Booking Solution**
   - Create a booking app to manage desks and meeting rooms across multiple locations where users can:
     - Select a site and view available desks/rooms.
     - Book a desk/room for a specific date and time.
     - Filter available Rooms by features such as the equipment and facilities of the room and the capacity the room can hold.
   - **Features**:
     - Display:
       - A calendar view of bookings.
       - Booking details, including the booker and duration.
     - Admin functionality to:
       - Add or remove desks/rooms at each site.
       - View booking statistics (e.g., busiest sites, most booked times).
       - Prevent double bookings or conflicts.
   - **Bonus Features**:
     - Integrate with Teams for meeting room bookings.
     - Add a section where admins can upload floor plans for sites as a document and users can click to see this document when looking to book at a location.

---

### **Fun Challenge**

**7. Connect 4 Game in a Canvas App**
   - Build a two-player Connect 4 game where users can:
     - Play turn-based with clear indicators for whose turn it is (red vs. yellow).
     - Drop pieces into columns, which fall to the lowest available row.
     - Allow two people to use one app session to play on one device
   - **Features**:
     - Display:
       - A 7x6 grid with occupied and empty cells.
       - A message showing whose turn it is.
     - Game logic to:
       - Detect winning conditions (4 in a row, column, or diagonal).
       - Reset the game after a win or draw.
   - **Bonus Features**:
     - Add a scoreboard to track wins for each player.
     - Include animations for pieces dropping into place.
     - Allow users to challenge someone and play against them in different sessions on different devices and notify the opposing user that it is their turn via Teams.

---

## 🛠 Submission Guidelines

1. **Build Your Solution**:
   - Choose a challenge and design your solution using the Power Platform.
   - Include all necessary files (exported solution, and supporting documentation).

2. **Package Your Solution**:
   - Zip your project files into a single `.zip` file.
   - Name the file as: `yourname_projectname.zip` (e.g., `john_doe_connect4.zip`).

3. **Submit Your Entry**:
   - Go to the [Issues](../../issues) tab in this repository.
   - Click **New Issue** and fill out the submission form:
     - **Participant Name**: Enter your name.
     - **Project Name**: Enter the challenge name.
     - **Description**: Briefly describe your app.
   - Attach your `.zip` file to the issue and submit.

---

## 📝 Feedback and Recognition

- **Personalized Feedback**:
  - Receive constructive feedback on your submission, including:
    - Areas of strength.
    - Suggestions for improvement.
    - Bonus feature highlights.
- **Grading System**:
  - Solutions will be graded on:
    - **Functionality**: How well does the app meet requirements?
    - **Creativity**: Are there unique or innovative features?
    - **User Experience**: Is the app intuitive and easy to use?
    - **Bonus Features**: Did you implement optional extras?
  - Grades:
    - **Outstanding**: Exceptional, exceeds the requirements.
    - **Proficient**: Fully meets the requirements.
    - **Developing**: Partially meets the requirements with room for improvement.

- **Portfolio Showcase**:
  - Use your submission as a portfolio project.

---

## 📅 Timeline

- **Challenge Start Date**: 20/11/2024
- **Submission Deadline**: 25/12/2024

---

Join the challenge, showcase your skills, and grow your Power Platform expertise! 💡✨
