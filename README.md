# ⚡ Shopify liquid theme
### This theme was developed to prove my experience and skills as a shopify theme developer

This theme is a clone of the Dawn shopify theme, to which 3 sections, 1 snippet, and some base.css code has been added.

**Do keep in mind that I am not a designer, the project is focused on showing off my coding skills, not my designer skills**



# 💻 My sections

| Syntax | Description | File |
| ----------- | ----------- | ----------- |
| Image plus text | Section that allows you to add blocks containing some text and an image | image-plus-text.liquid |
| Collection banner | Takes a collection and pulls featured image, title, desctiption... from it, also can be added manually | collection-banner.liquid |
| Custom Video | Section containing some text, and video, **video is played trough url beacause trial version of shopify doesnt allow for uploads of mp4 files to shopify** | custom-video.liquid |
| Custom buttons snippet | A snippet I wrote allowing us to create a unique button for any situation that can be called anywhere in the project, contains a lot of working variables, and some default values | custom-buttons.liquid |

### The css files have same names as the liquid files, with the exception of the base.css file which contains the css code I wanted to be available globally



# 👀 Sneak peek

![Text on left, video on right, Shopify Custom video section](./assets/Video%20section.png)

**All sections were made with responsive design in mind and were coded with mobile first appraoch in mind**



# 🛑 Built on

- shopify cli 3.56.3 
- node v20.11.0

Check me out on my linkedin for more shopify content: [Danijel Adrinek](https://www.linkedin.com/in/danijel-adrinek-502237227/)

*Do keep in mind that the purpose of this project is just to show off some of my shopify knowledge, I am capable of more, and I know adding paddings at some places would've made the design better, thank you for your understanding* :-)



# 🚀 Usage

1. Clone the repository
```
git clone https://github.com/DanijelAdrinek/Shopify-theme.git
```

2. Cd into directory
```
cd .\Shopify-theme\
```

3. Connect to store
```
shopify theme dev --store [store-link]
```