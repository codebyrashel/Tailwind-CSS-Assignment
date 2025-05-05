# Commit History Clarification

## 📘 Project Name  
**Google IT Support Certificate**  
**Assignment from Hablu-Programmer E-Learning Institute**

This project was built as part of a course assignment from **Hablu-Programmer**, an e-learning platform focused on practical web development training. It showcases a responsive layout and dynamic features, such as theme toggling.

---

## 🔍 Why So Many Commits?

If you're reviewing the commit history, you might notice a high number of commits (26) related to what seems like a small issue — fixing the image path.

Here’s what really happened:

While everything was working fine in my local environment, one image failed to load on the **Vercel live deployment**. After investigating, I realized it was due to a **path issue that behaved differently in production**. I attempted multiple methods to fix it — committing each version to test and verify the result.

Even though some commits may look similar or repetitive, they represent real debugging steps that took significant time and effort.

✅ **Final solution:** The problem was ultimately fixed by **moving the image to the `/public` directory**, which ensured it loaded correctly across environments.

Thank you for understanding the real-world debugging process behind what appeared to be a small change.

---

## 🌗 Dark Mode & Light Mode

This project fully supports both **Dark Mode** and **Light Mode**.

You can toggle the theme using the **moon icon (🌙)** in the header. Try it out to experience seamless theme switching on both desktop and mobile devices.

---

Feel free to explore the code, give feedback, or try the live version on Vercel!
