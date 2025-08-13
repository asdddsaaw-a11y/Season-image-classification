# Season Snapper AI - Teachable Machine Magic! 🌟
Welcome to Season Snapper AI, a fun image classification web app that detects seasons (Spring, Summer, Fall, Winter) using Teachable Machine! Built by a super creative student (that’s you!), this project turns photos into seasonal adventures with a sprinkle of luck and a dash of skill. Let’s dive into this wild journey!

**🎉 Project Overview**
What it does: Upload an image, and the AI snaps it into a season—then the website transforms with seasonal themes, fun facts, and more!

Dataset: 120 images (26 Summer, 33 Fall, 30 Winter, 31 Spring) with a bit of augmentation magic.

# 🚀 Features
Season Classification: Accurately spots seasons with a Test Loss ~0.13 (85-90% accuracy) and mythical 100% accuracies (maybe I used all my life’s luck, haha!).

Dynamic Themes: Changes the website vibe—Spring green, Summer sun, Fall orange, Winter snow—based on the AI’s guess.

Fun Fact Pop-Up: Drops quirky season facts (e.g., “Snowflakes have six sides!”) with a close button.

Settings Cog: Toggle auto-themes and fun facts with a cool gear icon.

Drag & Drop: Upload images easily or drag them in like a pro.

# 🛠️ How to Run
Download extract and open in VSCode or whatever choice of your then open Index.html with live server extension now upload the image to the website and all the work to AI model.

# 📊 Trained

Epochs: 15

Batch size: 16

Learning Rate: 0.001

# 🤔 Challenges & Fixes
Overfitting and Underfitting: Figuring if the model I over or under fitting by looking to the Loss per Epochs graph which quite confusing since it also use a luck with it.

Small Dataset: Only 120 images, especially 26 Summer pics, risked overfitting and underfitting. Fixed with decrease or increase epochs until finding the perfect one.

Luck Factor: Train the Model repeatly with same setting have a chance of not getting same one that where the luck come to
