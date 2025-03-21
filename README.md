
# DotNetBookstore - Facebook Login Integration

## Project Overview
This project demonstrates the integration of **Facebook Login Authentication** into the existing **DotNetBookstore** ASP.NET Core application.

Key Features Implemented:
- Facebook Login using OAuth
- Cookie Authentication setup
- Login & Logout functionality
- Callback URL configuration (`/signin-facebook`)
- Privacy Policy URL added
- Facebook App set to Production Mode

---

## Configuration Instructions

1. **Facebook Developer Setup:**
   - App created via [Facebook Developer Portal](https://developers.facebook.com).
   - App Mode set to **Production**.
   - Privacy Policy URL configured (non-localhost).
   - OAuth Redirect URI:  
     ```
     https://localhost:7003/signin-facebook
     ```

2. **App Configuration:**
   - Facebook App ID & Secret added in `appsettings.json`.

---

## Important Files Modified:
| File                                     | Purpose                                                      |
|-----------------------------------------|--------------------------------------------------------------|
| `appsettings.json`                      | Stores Facebook App ID & Secret                              |
| `Program.cs`                            | Configures authentication & routing                          |
| `Controllers/AccountController.cs`      | Handles login, callback, logout                              |
| `Views/Shared/_Layout.cshtml` snippet   | Provides Login with Facebook & Logout UI buttons             |

---

## Submission Details

- **GitHub Repository**: [Private Repo Link Here]
- **Instructor Collaborator Invited**: `dario-hesami`

---

## Submission Type
This is an **Individual Submission**.

*(OR if it’s a group submission, use this instead)*:
> This is a **Group Submission**.  
> Group Members:
> - [Your Name]
> - [Groupmate 1 Name]
> - [Groupmate 2 Name]

---

## Additional Notes
- Deployment to Azure/SmarterASP **NOT required**.
- Tested locally on `https://localhost:7003`.

---
