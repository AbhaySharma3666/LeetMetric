# LeetMetric

LeetMetric is a simple and responsive web app that visualizes LeetCode user statistics. Enter any LeetCode username to view progress by difficulty level and total submission stats.

## 🔧 Features

- ✅ Search by LeetCode username
- 📊 Visual progress indicators using circular graphs
- 📈 Displays number of submissions per difficulty
- 🟠 Uses a CORS proxy (https://cors-anywhere.herokuapp.com/) to bypass cross-origin restrictions
- 💡 Clean and responsive UI with dark mode styling

## 🛠️ Technologies Used

- HTML5, CSS3, JavaScript (Vanilla)
- LeetCode GraphQL API
- CORS Anywhere Proxy

## 🚀 How It Works
1. User Input: Enter your LeetCode username.
2. Fetch Data: A GraphQL query is sent via a CORS proxy to LeetCode's API.
3. Parse & Display:
    - Solved problems vs total for each difficulty
    - Number of submissions displayed in styled cards
4. Visual Progress: Circles with conic gradients show completion percentage for Easy, Medium, and Hard problems.

## 🚀 Getting Started

### Prerequisites

Due to CORS restrictions, you need to enable a proxy:

1. Open this URL and click "Request temporary access":
    (https://cors-anywhere.herokuapp.com/)
  ``` 
    ### Run Locally
    1. Clone the repo:
    ```bash
    git clone https://github.com//leetmetric.git
    cd leetmetric
  ```
2. Open (index.html) in your browser.
> ⚠️ Make sure to enable the proxy before using the app.

## 🖼️ UI Preview
![Overall look](Preview_Image/Screenshot%202025-05-10%20202255.png)
![Example](Preview_Image/Screenshot%202025-05-10%20202350.png)
