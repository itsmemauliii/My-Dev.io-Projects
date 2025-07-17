## Fridge to Feast AI 🍳🥬

*This post is my submission for [DEV Education Track: Build Apps with Google AI Studio](https://dev.to/deved/build-apps-with-google-ai-studio).*

## What I Built

I built **Fridge to Feast AI**, an app that takes a photo of your fridge contents and turns it into a full recipe + a photorealistic image of the final dish.  
I used **Google Gemini Pro** to identify the ingredients from the uploaded image, then generated a recipe based on those ingredients. Finally, I used the **Imagen API** to create a realistic image of the dish, all within **Google AI Studio**, no deployment needed!

## Demo
### 🧠 Identified Ingredients + Recipe UI  
![Screenshot 1](https://github.com/itsmemauliii/My-Dev.io-Projects/blob/main/Fridge%20to%20Feast%20AI%20🍳🥬/Screenshot1.png)

### 🍳 Full Cooking Instructions + Imagen Output  
![Screenshot 2](https://github.com/itsmemauliii/My-Dev.io-Projects/blob/main/Fridge%20to%20Feast%20AI%20🍳🥬/Screenshot2.png)
![Screenshot 3](https://github.com/itsmemauliii/My-Dev.io-Projects/blob/main/Fridge%20to%20Feast%20AI%20🍳🥬/Screenshot3.png)

### 🛠️ AI Studio Code Layout  
![Screenshot 4](https://github.com/itsmemauliii/My-Dev.io-Projects/blob/main/Fridge%20to%20Feast%20AI%20🍳🥬/Screenshot4.png)

## My Experience
This was my first time building inside **Google AI Studio**, and it felt like magic. Here's what stood out to me:

- 🔍 **Image-to-Insight flow** is smooth: Gemini Pro picked up small ingredients like green onions and block cheese accurately.
- 🎨 Imagen API is insanely powerful. The generated dishes look real enough to eat.
- 🧱 AI Studio made the entire development process feel modular, just like working with components in React or a no-code IDE, but with full control.

### What I learned:
- The **quality of prompts** makes or breaks your app, especially when generating images.
- AI Studio’s built-in file structure helped keep logic, services, and components organized.
- I now understand how to build a **multimodal app** that goes from image → text → image, all within one tool.
