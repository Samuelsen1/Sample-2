# Beginner-Friendly Figma Plugin Guide

This guide introduces you to creating and using Figma plugins.  
It is designed for beginners with little or no prior coding or plugin experience.  

---

## 1. What is a Figma Plugin?

A **Figma plugin** is a small piece of software that extends Figma’s functionality.  
With plugins, you can automate tasks, generate content, manipulate designs, or connect Figma with other tools.  

---

## 2. Why Use Plugins?

- **Save Time** – Automate repetitive tasks.  
- **Boost Creativity** – Generate text, colors, or layouts automatically.  
- **Integrate** – Connect Figma to external APIs and tools.  
- **Customize** – Tailor Figma to your workflow needs.  

---

## 3. How to Install a Plugin

1. Open **Figma**.  
2. Go to the **Main Menu** → **Plugins** → **Browse Plugins in Community**.  
3. Search for a plugin (e.g., “Icons8” or “Unsplash”).  
4. Click **Install**.  
5. Run the plugin: **Right-click on canvas** → **Plugins** → Select your plugin.  

---

## 4. Creating Your First Plugin

### Step 1: Enable Developer Mode
1. Go to **Figma Desktop App**.  
2. Open **Menu → Plugins → Development → New Plugin**.  
3. Select **"Click to create a new plugin"**.  

### Step 2: Plugin Files
When you create a new plugin, Figma generates a **manifest.json** file.  
It looks like this:  

```json
{
  "name": "Hello World",
  "id": "com.example.hello-world",
  "api": "1.0.0",
  "main": "code.js",
  "ui": "ui.html"
}
