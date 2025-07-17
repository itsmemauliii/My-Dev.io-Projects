## Fridge to Feast AI 🍳🥬

*This post is my submission for [DEV Education Track: Build Apps with Google AI Studio](https://dev.to/deved/build-apps-with-google-ai-studio).*

## What I Built
<!-- In one or two sentences, what app did you set out to build? Share the key prompts you used to generate the app, and mention any other features you utilized. -->

I built **Fridge to Feast AI**, an app that takes a photo of your fridge contents and turns it into a full recipe + a photorealistic image of the final dish.  
I used **Google Gemini Pro** to identify the ingredients from the uploaded image, then generated a recipe based on those ingredients. Finally, I used the **Imagen API** to create a realistic image of the dish, all within **Google AI Studio**, no deployment needed!

## Demo
<!-- Share screenshots and a link to your applet or fully deployed URL.  -->

### 🧠 Identified Ingredients + Recipe UI  
![Screenshot 1](/mnt/data/Screenshot%202025-07-17%20072342.png)

### 🍳 Full Cooking Instructions + Imagen Output  
![Screenshot 2](/mnt/data/Screenshot%202025-07-17%20071940.png)

### 🛠️ AI Studio Code Layout  
![Screenshot 3](/mnt/data/Screenshot%202025-07-17%20071410.png)

<!-- You can replace these with hosted image URLs if required (e.g. Cloudinary, Imgur, or GitHub repo raw links) -->

## My Experience
<!-- Share your key takeaways from working through the track. What did you learn? What was surprising? -->

This was my first time building inside **Google AI Studio**, and it felt like magic. Here's what stood out to me:

- 🔍 **Image-to-Insight flow** is smooth: Gemini Pro picked up small ingredients like green onions and block cheese accurately.
- 🎨 Imagen API is insanely powerful. The generated dishes look real enough to eat.
- 🧱 AI Studio made the entire development process feel modular, just like working with components in React or a no-code IDE, but with full control.

### What I learned:
- The **quality of prompts** makes or breaks your app, especially when generating images.
- AI Studio’s built-in file structure helped keep logic, services, and components organized.
- I now understand how to build a **multimodal app** that goes from image → text → image, all within one tool.
