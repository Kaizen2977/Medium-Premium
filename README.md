# Read Medium Premium Articles for Free 📚✨

As a budding blogger on Medium, I've quickly realized that access to premium content is essential for improving my writing and staying informed. However, the cost of a Medium membership can be prohibitively expensive, especially for those of us in India, where paying ₹4000 to ₹12000 annually for a subscription might not be feasible for everyone. 💸😢

To help you access Medium's premium articles without a subscription, I've devised a simple solution using a JavaScript bookmarklet. This method is straightforward and works in most browsers, including Chrome and Firefox. 🌐💡

## 🚨 Disclaimer:
This guide is for educational purposes only. Bypassing paywalls may violate Medium's terms of service, and it's always best to support content creators by subscribing if you can afford it. 🙏❤️

## 🛠️ Requirements:
- A web browser (Chrome or Firefox) 🖥️
- A Medium account 👤

## 📖 Steps to Create the Bookmarklet:

### 1. Open Your Browser's Bookmark Manager:
- **Chrome:** Click on the three dots in the upper right corner, go to `Bookmarks` > `Bookmark manager`. 📑🔍
- **Firefox:** Click on the bookmarks icon or go to `Library` > `Bookmarks` > `Show All Bookmarks`. 📚🦊

### 2. Add a New Bookmark:
- **Name:** Medium Premium 🌟
- **URL:** Copy and paste the following JavaScript code into the URL field.

```javascript
javascript:(function(){
    if (window.location.hostname === "medium.com") {
        window.location.href = `https://medium-free.vercel.app/read?url=${encodeURIComponent(window.location.href)}`;
    } else {
        alert("Please make sure you're on a medium.com post/article.");
    }
})();
```
### 3. Save the Bookmark and Reboot Your System:
- This step ensures that the changes take effect properly. 🔄💻

### 4. Access Premium Articles:
- Log in to your Medium account. 🔑
- Open any premium Medium article. 📄✨
- Click on the bookmark you created (Medium Premium). ⭐🔖
