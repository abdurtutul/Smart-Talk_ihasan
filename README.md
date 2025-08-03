# 🧪 SmallTalk – SQA Website Testing Report

This repository documents the Software Quality Assurance (SQA) testing activities for the **SmallTalk Web Application**, including **UI Testing**, **Functional Testing**, and **API Testing**.

---

## 📌 Project Name
**SmallTalk | Web SQA Report**

- 🧪 **Tested By:** Md Abdur Rahaman Tutul (SQA Engineer – FSD Team – Softvence)
- 🖥 **Platform:** Web (Desktop + Mobile Responsive)
- 🌐 **Test Type:** UI, Functional & API Testing
- 📅 **Testing Period:** July 2025 – August 2025
- ✅ **Total Bugs Found:** 28 (see bug sheet)

---

## 🧩 Application Modules Tested

### 1. 🔐 Authentication
- **Signup / Signin**
- **Forgot Password Flow**

### 2. 🏠 Home Tab
- Welcome message with username
- Search field
- Bookmark icon
- Notification bell
- "Trending Now" Card section
- "Recommendations" Card section

### 3. 💬 Thread
- View post threads
- Like, comment, bookmark

### 4. 📚 My Topics
- View and manage user-selected topics

### 5. 🌐 Community
- New post creation
- Filter by topic/tags
- Post detail page (view, comment, interact)

### 6. 👤 Profile Settings
- Edit profile
- Change password
- My past searches
- Interests and preferences
- Notifications toggle
- My bookmarks
- My posts
- Help center
- About SmallTalk
- Delete account
- Logout

---

## ✅ Testing Scope

| Type             | Description |
|------------------|-------------|
| 🖼 UI Testing     | Verified all screens against the Figma design |
| 🧪 Functional Testing | Tested workflows for each module end-to-end |
| 🔌 API Testing   | Validated API request/response for login, threads, posts, etc. using Postman/DevTools |

---

## 🐞 Sample Bug Report

| Bug ID   | Module     | Feature        | Bug Type   | Bug Title                    | Bug Description                                                                 | Steps to Reproduce                                                                                     | Actual Result                          | Expected Result                                                   | Issue Labels   | Severity | Attachment   | Dev Status   | Tester                   | Remark             | Date & Time           |
|----------|------------|----------------|------------|------------------------------|----------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------|----------------------------------------|------------------------------------------------------------------|----------------|----------|--------------|--------------|---------------------------|---------------------|------------------------|
| Bug_001  | Signup     | Registration   | UI         | Form validation not triggered | The form allows submission even if required fields are empty                    | 1. Go to Signup screen<br>2. Leave all fields blank<br>3. Tap Submit                                      | Form gets submitted without warning    | Validation messages should show for each empty required field     | Bug_UI         | Major    | Screenshot   | Fixed        | Md Abdur Rahaman Tutul   | Added error handling | 28/07/2025 – 11:30 AM |


📄 **Full Bug Report Sheet:** [Google Sheet – QA Bug Report](https://docs.google.com/spreadsheets/d/1K4xCQO-Bv9owp9PDdTZqQl5Zn6HaVusUPxerF4x4DJc/edit?usp=sharing)

---

## 🖼️ Screenshots

<details>
<summary>Click to expand screenshots 📸</summary>

| Module        | Screenshot |
|---------------|------------|
| Login Screen  | <img src="screenshots/login.png" width="250"/> |
| Home Tab      | <img src="screenshots/home.png" width="250"/> |
| Community Feed| <img src="screenshots/community.png" width="250"/> |
| Post Details  | <img src="screenshots/post_details.png" width="250"/> |
| Profile Page  | <img src="screenshots/profile.png" width="250"/> |

</details>

---

## 📂 Project Structure

