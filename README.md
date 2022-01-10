![easyfaces](https://user-images.githubusercontent.com/44387213/148630516-1774acb4-8aaf-4d7c-be77-c9ada635f87e.png)

# EasyFaces
https://t.me/EasyFacesBot

Telegram Bot by Amos Tan and Kai Yi Chen for Hack&Roll 2022

[![easyfaces](https://user-images.githubusercontent.com/44387213/148718534-4ed126f5-b2ba-45bb-bde3-452ca335baff.png)](https://www.youtube.com/watch?v=wAng1cpksys)
![gallery](https://user-images.githubusercontent.com/44387213/148718594-2adbb951-be33-492d-986d-6d81fa3ed15b.jpg)

## Inspiration
Stickers are becoming increasingly popular for use in messaging apps such as Telegram, but creating custom stickers may be a daunting task for beginners with no experience in sticker formatting. In particular, creating stickers of faces such as family and friends can be a hassle. EasyFacesBot bridges the difficulty gap and provides an easy way for users to create stickers of their family and friends.

## What it does
EasyFacesBot detects faces from pictures in .jpg and .png formats, and sends them as Telegram Stickers. You can either create a sticker pack or add to an existing sticker pack.

## How we built it
We used Python's telegram bot APIs for communication and sticker generation, and OpenCV for face detection to build EasyFacesBot.

## Challenges we ran into
Notable challenges included:

- Detecting faces in difficult photo scenarios (poor lighting, face partially blocked)
- Converting .jpg to .png without saving into the user's storage
- Ensuring protected ownership of sticker packs to prevent unwanted additions from others

## Accomplishments that we're proud of

Within 24 hours, we:
1. Created our first Telegram Bot and familiarised ourselves with Telegram Bot APIs
2. Made good use of existing solutions and libraries (OpenCV) to create something new and more useful

## What we learned

1. Though simple to deploy, Telegram Bots have the potential for advanced functionality
2. The differences between polling and webhooks
3. How Telegram servers operate to accommodate Bots and photos sent to the server 
4. How message handlers and callback query handlers operate

## What's next for EasyFacesBot
- Add option to delete stickers from pack
- Batch-add stickers to pack
