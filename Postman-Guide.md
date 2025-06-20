# Beginner Guide: Setting Up Postman to Test APIs  

## Summary  

Postman is an API platform for building and testing APIs. You can use it to:  
- Send requests  
- Inspect responses  
- Automate tests  

## Who This Is For  

New developers, testers, and tech writers trying to understand or document REST APIs.  

## What You Can Do  

- Send `GET`, `POST`, `PUT`, `DELETE` requests.  
- Save and reuse requests in collections.  
- Inspect API response status and body.

`GET`, `POST`, `PUT`, `DELETE` are the HTTP methods used in Postman (and all web APIs) to interact with a server — like asking for data, sending data, updating, or deleting something. Here’s a beginner-friendly breakdown:

### HTTP Methods in Postman
- `GET` Retrieves data from a server.
- `POST` Sends new data to the server.
- `PUT` Updates existing data.
- `DELETE` Removes data from the server.

Real-Life Example (Blog App):
| Action         | API Call      | Purpose                     |
|----------------|---------------|-----------------------------|
| View all posts | `GET` /posts    | Retrieves blog posts        |
| Create a post  | `POST` /posts   | Submits new post            |
| Edit a post    | `PUT` /posts/5  | Updates post with ID 5      |
| Delete a post  | `DELETE` /posts/5 | Deletes post with ID 5     |

 ## Using These in Postman
 --- 
 A. **`GET`**
1. **Download Postman** from [https://postman.com](https://postman.com) or proceed to use the web version. 2. Create an account.  
2. Click **New Request**.
<img src="https://github.com/Samuelsen1/Few-Important-Pics/blob/main/Newrequestpost.jpeg?raw=true" alt="Postman screen with New Request marked" width="800"/>

 > `GET` is set by default but in case it is not, tap the button adjacent to the search bar and select `GET`.
<img src="https://github.com/Samuelsen1/Few-Important-Pics/blob/main/getpost.jpeg?raw=true" alt="Postman screen with Get button marked" width="800"/>

3. Enter a sample public API. E.g., `https://jsonplaceholder.typicode.com/posts`.
<img src="https://github.com/Samuelsen1/Few-Important-Pics/blob/main/enterpost.jpeg?raw=true" alt="Postman screen with a pointer on URL" width="800"/>
     
4. Click **Send** to proceed.
<img src="https://github.com/Samuelsen1/Few-Important-Pics/blob/main/sendpost.jpeg?raw=true" alt="Postman screen with Send button marked" width="800"/>
 
 5. If successful, you will see a document window which may appear in a smaller portion. To increase the size, point your cursor at the border line at the top of the document window  and drag it upwards.
<img src="https://github.com/Samuelsen1/Few-Important-Pics/blob/main/dragwindowpost.png?raw=true" alt="Postman screen with pointer at Document Window" width="800"/>
   
   You'll see these options:
   > - View in code: JSON (Default), XML, HTML, JavaScript, Raw, Hex and Base64.
   > - Preview
   > - Visualise
   > - Copy
   > - Search, etc
   (include image)
6. Tap the symbol **(∨)** adjacent to **Send** on the same button to save and download.
 
7. Save your request into a **Collection** for reuse.  

