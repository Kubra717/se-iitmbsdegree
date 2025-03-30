# Ticket System Integration with Discourse and Webhooks

In this **software engineering project**, you'll enhance an existing **Ticketing application** created by students in the previous term. Instead of writing code from scratch, the goal is to **reuse and improve** the existing system, as many software solutions do to save time.

## Additional Features to be Added:

### 1. **Discourse Integration**
The IITM BS team wants to integrate **Discourse** to enhance **collaboration and community engagement** around tickets.

#### **Key Requirements:**
- Each **ticket** should have a corresponding **Discourse thread** for discussion.
- Users should be able to **include images and attachments** in Discourse threads.
- **Thread privacy settings** should allow users to control visibility.
- **Tagging functionality** should be available for better organization.
- **Notifications** should be sent for:
  - Likes
  - Replies
  - Comments
- Ensure **proper user role permissions** (students, support staff, and admins) across both the ticketing system and Discourse.

The Discourse API provides various features for integration. Explore the [Discourse API Documentation](https://docs.discourse.org/) to understand the available endpoints and functionalities.

### 2. **Webhooks Integration**
Certain tickets can be high priority and need to be addressed immediately or If a student feels the resolved ticket didn’t address the problem, they can escalate it.On escalating an issue, make sure the system is configured with GChat webhooks,triggering a notification to the support team lead in GChat.



## Sample Projects:
Below is a link to **4 sample projects** created by students in the previous term. You can choose any one of them as your **code base** to start with and incorporate additional features required in this term.

🔗 [Sample Projects](https://drive.google.com/drive/folders/10B7-rmdvu1peTyKTber9Ys5wc_KXA6pO?usp=sharing)