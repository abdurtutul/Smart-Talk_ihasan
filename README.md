# 🧪 SmallTalk – SQA Functional Testing 

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
<summary>Click to expand screenshots 📸</summary><br>

<div style="display: flex; gap: 10px; overflow-x: auto; padding: 10px;">
  <img src="screenshots/1.png" alt="Home Tab" width="250"/>
  <img src="screenshots/Screenshot_1.png" alt="Community Feed" width="250"/>
  <img src="screenshots/Screenshot_3.png" alt="Post Details" width="250"/>
  <img src="screenshots/Screenshot_8.png" alt="Profile Page" width="250"/>
  <img src="screenshots/Screenshot_7.png" alt="Threads Page" width="250"/>
  <img src="screenshots/Screenshot_5.png" alt="About SmallTalk" width="250"/>

</div>

</details>

---
---

## 🎨 Design Files

- 📁 **Figma Design File:** [View Design on Figma](https://www.figma.com/design/lxSVQJ0D9OVqpg89csnXZa/ihsan5987-%7C%7C-webgenius-%7C%7C--FO6271303B9C6?node-id=1-2&p=f&t=KtPy6e8YUmYtUvbs-0)
- 🔍 **Figma Preview Prototype:** [Preview Interaction](https://www.figma.com/proto/lxSVQJ0D9OVqpg89csnXZa/ihsan5987-%7C%7C-webgenius-%7C%7C--FO6271303B9C6?node-id=6003-3149&p=f&t=KtPy6e8YUmYtUvbs-0&scaling=scale-down&content-scaling=fixed&page-id=1%3A2)
---

## 👤 Tester Profile

**Md Abdur Rahaman Tutul**  
_SQA Engineer – FSD Team – Softvence (Alpha)_  
📧 Email: _abdurtutul6@gmail.com_  
🔗 Portfolio/LinkedIn: _https://www.linkedin.com/in/md-abdur-rahaman-tutul-a13012210_




