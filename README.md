# Telegram Bot API Capabilities
## For Neurodivergent Daily Life Support

> Exhaustive guide with **ADHD/Autism-friendly use cases** for each feature
> Perfect for: Executive function, Planning, Organization, Education, Family coordination, Business

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

| Feature | ADHD/Autism Use Case |
|---------|---------------------|
| Send text messages | `// Morning routine reminders: "Time to take meds" "Brush teeth" "Pack lunch"` |
| HTML/Markdown formatting | `// Visual hierarchy for task lists - bold for URGENT, italics for optional` |
| Disable link previews | `// Reduce visual clutter/overwhelm when sharing resources` |
| Send silently | `// Late-night reminders that won't wake family but will be there in morning` |
| Reply markup | `// Quick response buttons: "Done" "Snooze 10min" "Skip today"` |
| Reply to specific messages | `// Context anchoring - reply to the task you completed for satisfaction tracking` |
| Forward messages | `// Share therapy homework with accountability partner` |
| Copy messages | `// Duplicate successful routine templates to new days` |
| Delete messages | `// Remove completed tasks to reduce visual noise` |
| Edit messages | `// Update task status without creating new message clutter` |
| Pin messages | `// Keep daily priorities VISIBLE at top - reduces "out of sight, out of mind"` |

```
+-------------------------+
|    MESSAGE EFFECTS      |
+-------------------------+
```

| Feature | ADHD/Autism Use Case |
|---------|---------------------|
| Message reactions | `// Quick dopamine hit - react with checkmark when task done` |
| Typing indicators | `// Know when accountability partner is responding (reduces anxiety)` |
| Schedule messages | `// SET UP REMINDERS DURING HYPERFOCUS - deploy when needed later` |
| Protect content | `// Keep private journal entries from being forwarded accidentally` |

---

## 2. KEYBOARDS & BUTTONS

```
+-------------------------+
|   INLINE KEYBOARDS      |
+-------------------------+
```

| Feature | ADHD/Autism Use Case |
|---------|---------------------|
| URL buttons | `// One-tap access to frequently forgotten links (portal logins, calendars)` |
| Callback buttons | `// "I ate breakfast" -> logs meal, sends encouragement, updates streak` |
| Switch inline query | `// Quick-share your location with family without typing` |
| Pay buttons | `// Reduce friction for bills - one tap instead of remembering passwords` |
| Login buttons | `// Skip password recall - major executive function saver` |
| Web App buttons | `// Launch habit tracker, mood logger, or sensory break timer` |
| Copy text buttons | `// One-tap copy your address, phone, or standard responses` |

```
+-------------------------+
|   REPLY KEYBOARDS       |
+-------------------------+
```

| Feature | ADHD/Autism Use Case |
|---------|---------------------|
| Custom keyboard buttons | `// Predefined responses: "Good day" "Meh day" "Hard day" "Need support"` |
| Request contact | `// Emergency contact sharing without remembering numbers` |
| Request location | `// "I'm lost" -> instantly shares GPS with trusted person` |
| Request poll | `// Family dinner vote: "Pizza" "Tacos" "Leftovers" - reduces decision fatigue` |
| Request user | `// Quickly identify who in group should handle a task` |
| Request chat | `// Select which project channel to post update to` |
| One-time keyboard | `// Disappears after choice - reduces visual clutter` |
| Selective keyboard | `// Different options for parent vs child in family group` |

---

## 3. MEDIA HANDLING

```
+-------------------------+
|      SEND MEDIA         |
+-------------------------+
```

| Feature | ADHD/Autism Use Case |
|---------|---------------------|
| Photos | `// Visual checklists, "this is what clean room looks like" reference pics` |
| Videos | `// Record yourself explaining a process during hyperfocus for later` |
| Audio files | `// Calming playlists sent at scheduled anxiety-prone times` |
| Voice messages | `// Brain dump thoughts when typing feels impossible` |
| Video notes | `// Quick face check-in with therapist/coach between sessions` |
| Documents | `// Store important PDFs (insurance cards, IEP docs) for instant access` |
| Animations/GIFs | `// Celebration GIFs for completed tasks - dopamine reward system` |
| Stickers | `// Non-verbal communication when words are hard` |

```
+-------------------------+
|    MEDIA GROUPS         |
+-------------------------+
```

| Feature | ADHD/Autism Use Case |
|---------|---------------------|
| Media albums | `// Document project progress - before/during/after in one message` |
| Mixed albums | `// Combine photo proof + video explanation of completed task` |

---

## 4. SCHEDULED REMINDERS (via Webhooks)

```
+-------------------------+
|   TIMED NOTIFICATIONS   |
+-------------------------+
```

| Feature | ADHD/Autism Use Case |
|---------|---------------------|
| Webhook triggers | `// External calendar -> bot reminds 30min, 15min, 5min before events` |
| Time-based sends | `// Medication reminders at exact times with escalating urgency` |
| Recurring patterns | `// "It's Wednesday - garbage day!" every week automatically` |
| Location triggers | `// "You're near the grocery store - here's your list"` |

---

## 5. POLLS & DECISIONS

```
+-------------------------+
|    REDUCE DECISION      |
|       FATIGUE           |
+-------------------------+
```

| Feature | ADHD/Autism Use Case |
|---------|---------------------|
| Regular polls | `// "What should I do first?" - let the bot/family decide` |
| Quiz polls | `// Learning reinforcement - medication names, emergency procedures` |
| Anonymous polls | `// Family check-in: "How's everyone's energy today?" honestly` |
| Multiple answers | `// "Which self-care did you do today?" - celebrate any wins` |
| Close poll | `// Decision made - stop second-guessing, move forward` |

---

## 6. GROUP/FAMILY COORDINATION

```
+-------------------------+
|   FAMILY BOT FEATURES   |
+-------------------------+
```

| Feature | ADHD/Autism Use Case |
|---------|---------------------|
| Get member info | `// Track who's seen important family announcements` |
| Member count | `// Confirm all family members are in the safety check group` |
| Restrict members | `// Limit kid's bot interactions to age-appropriate features` |
| Custom admin titles | `// "Meal Planner" "Homework Helper" "Errand Runner" - clear roles` |
| Join requests | `// Approve new babysitter/tutor to family coordination group` |

```
+-------------------------+
|   FORUM TOPICS          |
+-------------------------+
```

| Feature | ADHD/Autism Use Case |
|---------|---------------------|
| Create topics | `// Separate threads: URGENT, Groceries, School, Medical, Fun` |
| Pin in topics | `// Keep important info visible in each category` |
| Close topics | `// Archive completed projects to reduce noise` |

---

## 7. EXECUTIVE FUNCTION HELPERS

```
+-------------------------+
|    TASK MANAGEMENT      |
+-------------------------+
```

| Feature | ADHD/Autism Use Case |
|---------|---------------------|
| Bot commands | `// /today - shows today's tasks, /done [task] - marks complete` |
| Inline queries | `// Type @mybot in any chat to quickly log something` |
| Callback data | `// Track button presses: how many times snoozed? Adjust approach` |
| User state | `// Remember where user left off in multi-step task breakdown` |

---

## 8. SENSORY & EMOTIONAL REGULATION

```
+-------------------------+
|   STICKER SYSTEM        |
+-------------------------+
```

| Feature | ADHD/Autism Use Case |
|---------|---------------------|
| Custom sticker sets | `// Personal emotion cards: "Overstimulated" "Need space" "Happy stim"` |
| Animated stickers | `// Soothing repetitive animations for calming` |
| Emoji stickers | `// Non-verbal communication when words are too hard` |

```
+-------------------------+
|        DICE/GAMES       |
+-------------------------+
```

| Feature | ADHD/Autism Use Case |
|---------|---------------------|
| Dice roll | `// Can't decide? Roll dice. Removes decision paralysis.` |
| Slot machine | `// Random reward for completing tasks - gamification dopamine` |
| Games | `// Structured break activities with clear end points` |

---

## 9. LOCATION & SAFETY

```
+-------------------------+
|    SAFETY FEATURES      |
+-------------------------+
```

| Feature | ADHD/Autism Use Case |
|---------|---------------------|
| Send location | `// "I'm overwhelmed at the store" -> family can find you` |
| Live location | `// Commute tracking - family knows you're safe without texts` |
| Venue sharing | `// Share exactly which entrance/building for meetups (reduces anxiety)` |
| Contact sharing | `// Emergency: one tap sends all your info to responder` |

---

## 10. BUSINESS/WORK SUPPORT

```
+-------------------------+
|  WORK ACCOMMODATIONS    |
+-------------------------+
```

| Feature | ADHD/Autism Use Case |
|---------|---------------------|
| Business messages | `// Auto-replies when in focus mode: "I'll respond at 3pm"` |
| Away messages | `// Automatic "I'm overwhelmed, response delayed" during hard days` |
| Greeting messages | `// Template responses for common client questions` |
| Opening hours | `// Clear boundaries - bot only responds during work hours` |

---

## 11. WEB APPS (MINI APPS)

```
+-------------------------+
|    CUSTOM TOOLS         |
+-------------------------+
```

| Feature | ADHD/Autism Use Case |
|---------|---------------------|
| Habit trackers | `// Visual streak counters - don't break the chain motivation` |
| Mood loggers | `// Quick tap mood tracking throughout day` |
| Timers | `// Pomodoro, transition warnings, "5 minutes until leaving"` |
| Sensory menus | `// "I need: quiet / pressure / movement / snack" quick selector` |
| Routine builders | `// Visual step-by-step guides with checkboxes` |

---

## 12. EDUCATION & LEARNING

```
+-------------------------+
|   LEARNING SUPPORT      |
+-------------------------+
```

| Feature | ADHD/Autism Use Case |
|---------|---------------------|
| Spaced repetition | `// Bot quizzes you on study material at optimal intervals` |
| Progress tracking | `// Visual progress bars toward learning goals` |
| Homework reminders | `// "Assignment due in 24 hours" -> "12 hours" -> "3 hours"` |
| Study buddy matching | `// Connect with accountability partner for body doubling` |

---

## QUICK IMPLEMENTATION IDEAS

```
+----------------------------------+
|     STARTER BOT CONCEPTS         |
+----------------------------------+
| Morning Routine Bot              |
| Medication Reminder Bot          |
| Family Coordination Bot          |
| Mood & Energy Tracker            |
| Decision Helper Bot              |
| Sensory Break Timer              |
| Hyperfocus Capture Bot           |
| Accountability Partner Bot       |
+----------------------------------+
```

---

## RESOURCES

- [Official Bot API](https://core.telegram.org/bots/api)
- [BotFather](https://t.me/BotFather) - Create your support bot

---

*Created by TurnerWorks - Telegram bots for neurodivergent thriving*
*Because our brains work differently, our tools should too.*
