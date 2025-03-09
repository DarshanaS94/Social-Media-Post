# Social Media Post

This is a simple **Social Media Homepage** that displays posts along with their corresponding comments.  
It fetches **posts and comments** from a mock API and assigns user names from a local file.  
User avatars are randomly generated using `picsum.photos`.

## Task Requirements

### 1️. Fetch & Display Posts
- Fetch posts from the API:  
  **[https://jsonplaceholder.typicode.com/posts](https://jsonplaceholder.typicode.com/posts)**
- Display **post title, body, and user information**.

### 2️. Fetch & Display Comments
- Retrieve comments for each post from the API:  
  **[https://jsonplaceholder.typicode.com/comments?postId=1](https://jsonplaceholder.typicode.com/comments?postId=1)**
  (where `1` should be replaced with the respective post ID).
- Show all comments under their respective posts.

### 3️. Map User IDs to Usernames
- **A local file (`users.json`)** contains user names mapped to user IDs.
- Each post displays **a different user name** fetched from `users.json`.

### 4. Generate Random User Avatars
- User avatars are dynamically generated using:  
  **[https://picsum.photos/](https://picsum.photos/)**  
  Example: `https://picsum.photos/seed/{userId}/50`


---


Screenshot of the Social Media Post:
![image](https://github.com/user-attachments/assets/0863bf5b-9334-403b-9165-52441e18afac)


---

### Kindly Note:
- The repository also has a file with the Python Code for Task 2 - Min Max Problem 
