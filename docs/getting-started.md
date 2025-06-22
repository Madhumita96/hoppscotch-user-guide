# Getting Started with Hoppscotch

In this section, you'll learn how to send your first API request using Hoppscotch. No coding experience required.

Whether you're a beginner or someone coming from Postman, this walkthrough will help you feel comfortable with the tool.

---

## 1. Launch Hoppscotch

Open your browser and go to:  
 [https://hoppscotch.io](https://hoppscotch.io)

You’ll land on a clean interface with a request input bar.

---

## 2. Choose Request Type and Enter URL

1. From the dropdown on the left, select **GET** (default).
2. In the input bar next to it, enter this sample public API: https://jsonplaceholder.typicode.com/posts/1


This API returns a test blog post.

---

## 3. Send the Request

- Click the **Send** button.
- You’ll see the **response** in the panel below.
- Hoppscotch formats the response in a readable JSON structure.

---

## 4. Understand the Response

The response should look like this:

```json
{
  "userId": 1,
  "id": 1,
  "title": "Sample title",
  "body": "Sample body content"
}
```
This means the request was successful, and the server returned valid data.

## 5. Test a Broken Request (Optional)
Try entering a wrong URL, like:
https://jsonplaceholder.typicode.com/posts/abc

You’ll see an error or empty result — this helps you understand how APIs behave when requests fail.

## 6. Add Query Parameters (Optional)
Click the Params tab to add query parameters:

| Key    | Value |
| ------ | ----- |
| userId | 1     |

This builds the request:

https://jsonplaceholder.typicode.com/posts?userId=1

You’ve successfully sent your first API request using Hoppscotch!

Next, let’s explore more features like:

- Collections
- Environments
- Headers and Body for POST requests

Head over to the [Advanced Usage](advanced-usage.md) section.