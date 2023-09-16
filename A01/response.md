# Assignment 1

### When you hear the words "Artificial Intelligence", what are the first four things that come to your mind?

- Natural Intelligence

  - The term "artificial" in "artificial intelligence" often makes me ponder natural intelligence — what is intelligence, and how does it form in nature? How does it work?

- Human Intelligence

  - As someone with a human-centric perspective, the word "intelligence" conjures images of something comparable to humans. I don't have a precise definition of human intelligence, but I tend to think of it as something consistently knowledgeable and capable, similar to the typical person I encounter in my everyday life.

- Hype

  - It has been a while since AI became a very popular topic, even among people who are not too familiar with the tech industry. I see many companies advertising their magical AI technology as if it provides massive value to their customers, but many of them don't seem to need AI technology at all.

- Misuse/Abuse of the Term
  - I believe the hype largely stems from tech marketers abusing and misusing the term "AI," much like "crypto," "metaverse," "NFT," and so on. Each technology has its own good uses, but people often come up with buzzwords to fancy the descriptions of unattractive things to turn a profit.

### Think about the devices and/or digital services you use daily. Write below a list of the top three that are present in your life.

- Email
- Messaging app
- Smartphone

### Have these things ever surprised you by guessing something about you that you didn’t expect?

I remember the time when I tried to send some project files to my friend via email. I wrote something like "Attached project files" and clicked _send_. Before sending the email, the email service provider showed me a confirmation message asking whether I wanted to send the mail without an attachment. Indeed, I hadn't attached anything. I uploaded the project files and sent the email correctly. (I'm not sure whether this technology is backed by AI)

### Take a moment to see if you can identify what function AI plays in the following list.

| DEVICE OR DIGITAL SERVICE WITH AI | AI FUNCTION(S)                                        |
| --------------------------------- | ----------------------------------------------------- |
| Email inbox                       | Spam filtering, calendar event management, etc.       |
| Check depositing                  | Fraud detection, etc.                                 |
| Texting and mobile keyboards      | Autocorrect, autocomplete frequently used words, etc. |
| Netflix                           | Content recommendation, etc.                          |
| Google (search function)          | Advertisement, bot detection, web indexing, etc.      |
| Social media platforms            | Advertisement, content recommendation, etc.           |
| Automated message systems         | LLM chatbot feature, etc.                             |

### What do we gain by having AI in our everyday lives?

Personalization, abnormal behavior detection, biometric authentication, and so on.

### What do we lose by having AI in our daily lives?

Loss of privacy, narrowly targeted marketing, low quality bot-generated contents, job loss, etc.

### Use the prompts below to help design an AI system.

| Q                                                                                                  | A                                                                                                                      |
| -------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| WHAT PROBLEM ARE YOU TRYING TO ADDRESS ?                                                           | I collect random articles, and it takes a lot of time to tag, categorize, and extract metadata such as published date. |
| HOW CAN AI HELP SOLVE THIS ISSUE?                                                                  | tag, categorize, and extract metadata such as published date.                                                          |
| WHAT ROLE WILL HUMANS HAVE IN ADDRESSING THIS ISSUE?                                               | feed training data, collect articles to manage, etc.                                                                   |
| WHAT DATA DO YOU NEED TO CREATE AN AI TO HELP YOU ADDRESS YOUR ISSUE?                              | Language training data, metadata pattern, etc.                                                                         |
| HOW WILL YOU RESPONSIBLY GATHER THIS DATA IN A WAY THAT RESPECTS INDIVIDUALS’ PRIVACY AND CONSENT? | use published databases                                                                                                |

### Design your prototype system.

```text
1. Article Link Given
2. Process Article with a local LLM:
    - Tag
    - Categorize
    - Find metadata
```
