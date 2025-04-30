# Facebook Post Scheduler & Analytics Tool

## Overview
This tool is a comprehensive web-based solution for managing, scheduling, and analyzing Facebook posts for your Facebook Page. It is designed for page admins, marketers, and social media managers who want a streamlined and powerful interface for both scheduling content and tracking post performance.

---

## Core Features

### 1. **Facebook Credentials Management**
- **Securely enter and save your Facebook Page Access Token and Page ID** to enable all API-powered features.
- Credentials are stored locally for convenience and privacy.

### 2. **Post Composer**
- **Create new Facebook posts** of various types: Text, Image, Link, or Video.
- **Upload images or videos** directly from your device for media posts.
- **Add links** with rich previews for link posts.
- **Choose to post immediately or schedule for a future time** using the built-in scheduling options.
- **Import posts in bulk via CSV** (for text posts), allowing for efficient batch scheduling.
- **Live preview** of your post as you compose, including type-specific details.

### 3. **Post Analytics Dashboard**
- **Access a dedicated analytics section** via the sidebar.
- **Three analytics views:**
  - **Past 30 Days:** See a day-by-day table of published posts by type (text, image, link, video, other).
  - **Next 30 Days (Scheduled):** See a day-by-day table of all scheduled posts by type.
  - **Next 30 Days (All Details):** View a detailed table of every scheduled post, including type, message, scheduled date/time, permalink, and an Edit button for each post.
- **Timezone information** is displayed for clarity.

### 4. **Edit Scheduled Posts**
- In the "Next 30 Days (All Details)" analytics table, click the **Edit** button for any scheduled post to:
  - Instantly scroll to the post composer.
  - Have the composer pre-filled with the post's content, type, and scheduled time.
  - For media/link posts, see previews or links in the log area.
- Make changes and re-schedule or update the post as needed.

### 5. **Local Post History & Logs**
- **Track all posts made via this tool** in a local history panel.
- **View logs and status messages** for all actions, including API calls, errors, and previews.

### 6. **User-Friendly Interface**
- **Modern, responsive UI** built with Tailwind CSS.
- **Sidebar navigation** for easy access to all features.
- **Clear feedback and error messages** for every action.

---

## How to Use

1. **Enter Facebook Credentials**
   - Open the app and enter your Facebook Page Access Token and Page ID in the sidebar.
   - Click "Validate & Save" to enable posting and analytics features.

2. **Compose and Schedule Posts**
   - Choose a post type (Text, Image, Link, Video) from the sidebar.
   - Fill in the post content and upload any media as needed.
   - Select whether to post now or schedule for later.
   - For bulk text posts, use the CSV import option.
   - Click "Publish to Facebook" to submit your post.

3. **View Analytics**
   - Click "Post Analytics" in the sidebar to open the analytics dashboard.
   - Use the three tabs to view past published posts, upcoming scheduled posts, or a detailed list of all scheduled posts.
   - Review post counts by type, and see timezone info above each table.

4. **Edit Scheduled Posts**
   - In the detailed analytics table, click "Edit" on any scheduled post.
   - The composer will auto-fill with the selected post's details.
   - Make your changes and re-schedule as needed.

5. **Review History and Logs**
   - Use the "Post History & Logs" section to see all posts made from this tool and review any API or error messages.

---

## Notes
- **Your Facebook credentials are never sent to any external server except Facebook.**
- **All analytics and editing features require a valid Access Token with appropriate permissions.**
- **The tool is intended for Facebook Page admins and may not function with personal profiles or groups.**

---

For further help, check the in-app log messages or contact the developer.

