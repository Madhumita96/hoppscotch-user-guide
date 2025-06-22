# Advanced Usage

Now that you've learned how to send a simple GET request, let’s explore more advanced features in Hoppscotch that can make your API testing more efficient and organized.

---

## 1. Using POST Requests

POST requests allow you to send data to an API. Here’s how:

1. Change the method from `GET` to `POST`.
2. In the **URL bar**, enter this test endpoint:
    https://jsonplaceholder.typicode.com/posts


3. Click on the **Body** tab.
4. Choose **JSON** as the content type.
5. Add this sample JSON body:

```json
{
  "title": "Hoppscotch Guide",
  "body": "Created with Hoppscotch",
  "userId": 101
}
```
6. Click Send.

**Note:** You’ll receive a response that shows the data was successfully received.

## 2. Setting Custom Headers
To set custom headers:

- Click on the Headers tab.
- Add the following:

| Key           | Value                               |
| ------------- | ----------------------------------- |
| Content-Type  | application/json                    |
| Authorization | Bearer `<your-token>` (if required) |

This is useful when you work with secure or authenticated APIs.

## 3. Saving Requests with Collections
Collections allow you to save and group your requests.

To create a collection:

1. Click the **Collections** icon from the left sidebar.
2. Click **New Collection** → Give it a name.
3. Click **Save Request** and assign it to a collection.

Benefits:

- Keep your work organized
- Reuse requests across projects
- Share requests with your team

## 4. Working with Environments
Environments help you switch between development, staging, and production settings.

1. Click on the Environment icon (⚙️) in the left panel.
2. Add a new environment like:
```
{
  "baseUrl": "https://jsonplaceholder.typicode.com"
}
```
3. Use variables in your requests like:
```
{{baseUrl}}/posts/1
```
This is helpful when testing the same API on different servers.

## 5. Keyboard Shortcuts
Use these to boost your speed:

| Action       | Shortcut             |
| ------------ | -------------------- |
| Send Request | Ctrl + Enter         |
| Save Request | Ctrl + S             |
| Open New Tab | Ctrl + T             |
| Switch Tabs  | Ctrl + \[ / Ctrl + ] |

## Summary
You now know how to:

- Send POST requests with JSON bodies
- Set headers and auth tokens
- Use collections and environments to organize your work
- Boost productivity with keyboard shortcuts

You’re now ready to use Hoppscotch like a power user! 

Go back to the [Introduction](introduction.md) or [Setup sections](setup.md) if you want to revise the basics.

