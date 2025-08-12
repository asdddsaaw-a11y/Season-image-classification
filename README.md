# 🦆 Goose, Duck Classification 101 🪿
Welcome to Goose, Goose, or is it? — your fun and quirky image classifier that tells you whether you’ve got a goose, a duck, or something else entirely! Powered by TensorFlow.js and Teachable Machine, this app makes bird ID feel like a breeze (and a giggle).

# Features ✨
Drag & Drop your image or click to select one

Slick toggle switch to show raw prediction probabilities or just the top guess

Clean, colorful, and playful UI with a raised eyebrow emoji for that extra sass 😏

Responsive design — works smoothly on mobile and desktop!

Instant predictions with a snappy result message

# Under the Hood 🔧
Built with TensorFlow.js & Teachable Machine Image library

Model files live in the ./Model/ folder (model.json and metadata.json)

Smooth drag & drop interface with interactive hover effects

Stylish toggle switch for raw vs. pretty prediction outputs

Stylish CSS with gradients, shadows, and rounded corners for that cozy feel

Fun use of Comic Sans MS font because why not? 😜

**Train**

61 goose images and 50 duck images

Epochs: 21

Batch: 16

Learning rate: 0.0002

Accurate/loss per epochs graph? Nah I don't want to show since it look too bad

But overall after train the model with my luck rng is always my side since the result for Predict accurate is pretty sure it acceptable (this took me like ~40 times clicking train model repeatly)

<img width="397" height="302" alt="image" src="https://github.com/user-attachments/assets/723a0de9-e014-4db6-bfda-e51b8047d1cd" />

Visual Sneak Peek 👀

<img width="1919" height="903" alt="image" src="https://github.com/user-attachments/assets/905b76df-5cc2-4200-923c-f7a5b149cb50" />

# Goose, Goose, or is it? 🤨

**Code Highlights 💡**
Drag & drop + file input combo for effortless image upload

Prediction function that picks the top class or lists all classes with probabilities

Clear button resets everything and even resets the toggle switch — neat!

User-friendly alerts if you drop a non-image file

# Wanna Play? 🕹️
Clone this repo, open index.html in your perfer code editor that contain live preview don't ask me why but it not work if you dont do so but after that just upload the image then the model will be predict it not 100% accurate but still kinda accurate after all.
