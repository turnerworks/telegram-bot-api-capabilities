# Telegram Bot API Capabilities

> Exhaustive guide to everything a Telegram Bot can do, with ASCII buttons for quick navigation

---

## Quick Navigation

```
+------------------+  +------------------+  +------------------+
|   MESSAGES       |  |   KEYBOARDS      |  |   MEDIA          |
+------------------+  +------------------+  +------------------+

+------------------+  +------------------+  +------------------+
|   PAYMENTS       |  |   GAMES          |  |   GROUPS         |
+------------------+  +------------------+  +------------------+

+------------------+  +------------------+  +------------------+
|   WEBHOOKS       |  |   INLINE MODE    |  |   STICKERS       |
+------------------+  +------------------+  +------------------+
```

---

## 1. MESSAGING

```
+-------------------------+
|     SEND MESSAGE        |
+-------------------------+
```
- Send text messages
- Send with HTML/Markdown formatting
- Send with link previews disabled
- Send silently (no notification)
- Send with reply markup
- Reply to specific messages
- Forward messages
- Copy messages
- Delete messages
- Edit messages
- Pin/Unpin messages

```
+-------------------------+
|    MESSAGE EFFECTS      |
+-------------------------+
```
- Message reactions
- Typing indicators
- Read receipts (in some contexts)
- Schedule messages
- Protect content from forwarding

---

## 2. KEYBOARDS & BUTTONS

```
+-------------------------+
|   INLINE KEYBOARDS      |
+-------------------------+
```
- URL buttons (open links)
- Callback buttons (trigger bot actions)
- Switch inline query buttons
- Pay buttons
- Login buttons (Telegram Login Widget)
- Web App buttons (Mini Apps)
- Copy text buttons

```
+-------------------------+
|   REPLY KEYBOARDS       |
+-------------------------+
```
- Custom keyboard buttons
- Request contact button
- Request location button
- Request poll button
- Request user button
- Request chat button
- Web App button
- Resize keyboard option
- One-time keyboard option
- Selective keyboard (specific users)
- Remove keyboard

---

## 3. MEDIA HANDLING

```
+-------------------------+
|      SEND MEDIA         |
+-------------------------+
```
- Photos (single & albums)
- Videos
- Audio files
- Voice messages
- Video notes (round videos)
- Documents/Files
- Animations (GIFs)
- Stickers
- Paid media

```
+-------------------------+
|    MEDIA GROUPS         |
+-------------------------+
```
- Send media groups (up to 10 items)
- Mixed photo/video albums
- Document groups

```
+-------------------------+
|   MEDIA FEATURES        |
+-------------------------+
```
- Thumbnails
- Captions with formatting
- Spoiler media
- File size limits (50MB download, 20MB upload via API)
- Stream large files via URL

---

## 4. INLINE MODE

```
+-------------------------+
|    INLINE QUERIES       |
+-------------------------+
```
- Answer inline queries
- Article results
- Photo results
- GIF results
- Video results
- Audio results
- Voice results
- Document results
- Location results
- Venue results
- Contact results
- Game results
- Sticker results
- Cached results (file_id reuse)

```
+-------------------------+
|   INLINE FEATURES       |
+-------------------------+
```
- Personal results (user-specific)
- Query result caching
- Switch to PM button
- Inline feedback (chosen_inline_result)
- Location-based results

---

## 5. PAYMENTS

```
+-------------------------+
|    PAYMENT FLOW         |
+-------------------------+
```
- Send invoices
- Pre-checkout queries
- Successful payment handling
- Refunds
- Shipping queries
- Flexible prices
- Provider tokens (Stripe, etc.)

```
+-------------------------+
|   PAYMENT FEATURES      |
+-------------------------+
```
- Multiple currencies
- Tips/Gratuities
- Subscription payments
- Digital goods
- Physical goods with shipping
- Telegram Stars payments
- Payment receipts

---

## 6. GROUP/CHANNEL MANAGEMENT

```
+-------------------------+
|   MEMBER MANAGEMENT     |
+-------------------------+
```
- Get chat member info
- Get chat member count
- Get chat administrators
- Kick/Ban members
- Unban members
- Restrict members
- Promote/Demote admins
- Set custom admin titles
- Approve/Decline join requests

```
+-------------------------+
|   CHAT SETTINGS         |
+-------------------------+
```
- Set chat title
- Set chat description
- Set chat photo
- Delete chat photo
- Set chat permissions
- Set slow mode delay
- Export chat invite links
- Create invite links
- Revoke invite links
- Edit invite links

```
+-------------------------+
|   CHAT FEATURES         |
+-------------------------+
```
- Create forum topics
- Edit forum topics
- Close/Reopen topics
- Delete forum topics
- Pin messages in topics
- Hide/Show general topic
- Set chat menu button
- Get chat menu button

---

## 7. STICKERS

```
+-------------------------+
|   STICKER ACTIONS       |
+-------------------------+
```
- Send stickers
- Get sticker set
- Upload sticker file
- Create new sticker set
- Add sticker to set
- Set sticker position in set
- Delete sticker from set
- Set sticker set thumbnail
- Set custom emoji sticker set thumbnail
- Delete sticker set

```
+-------------------------+
|   STICKER TYPES         |
+-------------------------+
```
- Static stickers (WebP)
- Animated stickers (TGS)
- Video stickers (WebM)
- Custom emoji stickers
- Mask stickers
- Regular stickers

```
+-------------------------+
|   STICKER FEATURES      |
+-------------------------+
```
- Sticker keywords/emojis
- Sticker set name customization
- Premium stickers
- Custom emoji for premium users

---

## 8. GAMES

```
+-------------------------+
|     GAME ACTIONS        |
+-------------------------+
```
- Send game
- Set game score
- Get game high scores
- Inline game messages

```
+-------------------------+
|    GAME FEATURES        |
+-------------------------+
```
- HTML5 games
- Game URLs
- High score tables
- Force score updates
- Disable edit message

---

## 9. WEBHOOKS & UPDATES

```
+-------------------------+
|     WEBHOOK SETUP       |
+-------------------------+
```
- Set webhook URL
- Delete webhook
- Get webhook info
- Custom certificates (self-signed)
- IP whitelist
- Allowed updates filter
- Secret token validation

```
+-------------------------+
|    LONG POLLING         |
+-------------------------+
```
- getUpdates method
- Offset parameter
- Timeout configuration
- Update limits

```
+-------------------------+
|    UPDATE TYPES         |
+-------------------------+
```
- message
- edited_message
- channel_post
- edited_channel_post
- business_connection
- business_message
- edited_business_message
- deleted_business_messages
- message_reaction
- message_reaction_count
- inline_query
- chosen_inline_result
- callback_query
- shipping_query
- pre_checkout_query
- purchased_paid_media
- poll
- poll_answer
- my_chat_member
- chat_member
- chat_join_request
- chat_boost
- removed_chat_boost

---

## 10. BOT PROFILE & SETTINGS

```
+-------------------------+
|    BOT INFORMATION      |
+-------------------------+
```
- Get bot info (getMe)
- Set bot name
- Get bot name
- Set bot description
- Get bot description
- Set bot short description
- Get bot short description

```
+-------------------------+
|    BOT COMMANDS         |
+-------------------------+
```
- Set my commands
- Delete my commands
- Get my commands
- Command scopes (all users, admins, specific chats)
- Language-specific commands

```
+-------------------------+
|   BOT MENU BUTTON       |
+-------------------------+
```
- Set chat menu button
- Get chat menu button
- Web App menu button
- Commands menu button
- Default menu button

---

## 11. WEB APPS (MINI APPS)

```
+-------------------------+
|    WEB APP FEATURES     |
+-------------------------+
```
- Open Web App from keyboard button
- Open Web App from inline button
- Open Web App from menu button
- Direct link Mini Apps
- Inline mode Mini Apps
- Attachment menu Mini Apps

```
+-------------------------+
|   WEB APP DATA          |
+-------------------------+
```
- Answer web app query
- Web app data validation
- InitData parameter
- User authentication
- Theme parameters
- Viewport settings
- Main button control
- Back button control
- Haptic feedback
- Cloud storage
- Biometric auth

---

## 12. BUSINESS FEATURES

```
+-------------------------+
|   BUSINESS ACCOUNTS     |
+-------------------------+
```
- Business connection handling
- Business messages
- Manage business messages
- Business intro
- Business location
- Business opening hours
- Greeting messages
- Away messages

---

## 13. SPECIAL CONTENT

```
+-------------------------+
|      LOCATIONS          |
+-------------------------+
```
- Send location
- Send live location
- Edit live location
- Stop live location
- Send venue

```
+-------------------------+
|      CONTACTS           |
+-------------------------+
```
- Send contact
- vCard support

```
+-------------------------+
|        POLLS            |
+-------------------------+
```
- Send poll
- Regular polls
- Quiz polls
- Anonymous polls
- Multiple answers
- Close poll
- Stop poll

```
+-------------------------+
|        DICE             |
+-------------------------+
```
- Send dice
- Dice emoji types: dice, darts, basketball, football, bowling, slot machine

---

## 14. CHAT ACTIONS

```
+-------------------------+
|   TYPING INDICATORS     |
+-------------------------+
```
- typing
- upload_photo
- record_video
- upload_video
- record_voice
- upload_voice
- upload_document
- choose_sticker
- find_location
- record_video_note
- upload_video_note

---

## 15. FILE HANDLING

```
+-------------------------+
|    FILE OPERATIONS      |
+-------------------------+
```
- Get file info
- Download files
- file_id reuse
- file_unique_id
- Local Bot API server (unlimited file sizes)

---

## 16. PASSPORT

```
+-------------------------+
|  TELEGRAM PASSPORT      |
+-------------------------+
```
- Request user data
- Personal details
- Identity documents
- Address documents
- Phone verification
- Email verification
- Data decryption
- Error handling

---

## API METHODS QUICK REFERENCE

```
+---------------------------+---------------------------+---------------------------+
|       MESSAGING           |        MEDIA              |       MANAGEMENT          |
+---------------------------+---------------------------+---------------------------+
| sendMessage               | sendPhoto                 | getChat                   |
| forwardMessage            | sendAudio                 | getChatMember             |
| copyMessage               | sendDocument              | getChatMemberCount        |
| sendReply                 | sendVideo                 | getChatAdministrators     |
| editMessageText           | sendAnimation             | banChatMember             |
| editMessageCaption        | sendVoice                 | unbanChatMember           |
| editMessageMedia          | sendVideoNote             | restrictChatMember        |
| editMessageReplyMarkup    | sendMediaGroup            | promoteChatMember         |
| deleteMessage             | sendLocation              | setChatAdminCustomTitle   |
| deleteMessages            | sendVenue                 | setChatPermissions        |
+---------------------------+---------------------------+---------------------------+

+---------------------------+---------------------------+---------------------------+
|        INLINE             |       PAYMENTS            |       STICKERS            |
+---------------------------+---------------------------+---------------------------+
| answerInlineQuery         | sendInvoice               | sendSticker               |
| answerCallbackQuery       | answerShippingQuery       | getStickerSet             |
| answerWebAppQuery         | answerPreCheckoutQuery    | uploadStickerFile         |
|                           | createInvoiceLink         | createNewStickerSet       |
|                           | refundStarPayment         | addStickerToSet           |
|                           |                           | deleteStickerFromSet      |
+---------------------------+---------------------------+---------------------------+
```

---

## RATE LIMITS

```
+----------------------------------+
|         RATE LIMITS              |
+----------------------------------+
| 30 msgs/sec to same chat         |
| 1 msg/sec to same user in groups |
| 20 msgs/min to same group        |
| Bulk: 30 msgs/sec overall        |
+----------------------------------+
```

---

## RESOURCES

- [Official Bot API Documentation](https://core.telegram.org/bots/api)
- [Bot API Changelog](https://core.telegram.org/bots/api-changelog)
- [BotFather](https://t.me/BotFather) - Create and manage bots

---

*Created by TurnerWorks - Your quick reference for Telegram Bot development*
