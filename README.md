# BunnyMo
![Status: Active Development](https://img.shields.io/badge/Status-Active%20Development-orange.svg) [![SillyTavern Lorebook](https://img.shields.io/badge/SillyTavern-Lorebook-green.svg)](https://docs.sillytavern.app/) ![CarrotKernel Compatible](https://img.shields.io/badge/CarrotKernel-Compatible-orange.svg)

The Repository for the SillyTavern thinking engine!
# CURRENT NEWS: CHECK OUT CARROT KERNEL FOR EVEN MORE BUNNYMO GREATNESS! https://github.com/Coneja-Chibi/CarrotKernel
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# 🥕✨Bunnymo: Advanced AI Roleplay Framework✨🥕

**Status: Work in Progress 🛠️ | Testing Welcome** 🧪

## 🐰 What the Hell is Bunnymo?

Bunnymo aims to turn your basic character cards into psychologically authentic, adult-oriented roleplay experiences. Instead of shallow interactions, the goal is characters with depth, realistic emotional patterns, and natural relationship dynamics.

Think of it as the difference between a cardboard cutout and a real person who happens to live in your chat. 💭

## 🛠️ How It Works Together

### 🧠 The Core System (Required)
The main Bunnymo lorebook is your foundation. Without this, nothing else functions properly.

We've made a bunch of different entries in different styles to give the AI more specific references. While AI can be very smart, at the end of the day it can need a lot of handholding to avoid specific and constant bad behaviors (when I get my hands on you, CLANKERS 🤖💢)

### 🎁 The Packs (Optional Add-ons)
We've been busy little bunnies releasing themed content:
- **🌸 Dere Pack**: We dropped a whole gaming pass loaded with romantic personality archetypes as playable characters
- **🧩 MBTI Pack**: Released a personality magazine complete with quirky quizzes comparing types to snacks and weather
- **👾 Species Pack**: Created an entire trading card game featuring 80+ fantasy species with full stat blocks

These packs help break the AI out of its boring default thinking patterns! 🌈✨ Instead of falling back on the same tired references, it gets weird new frames to work with - making it read between the lines and draw fresh comparisons to gaming mechanics, magazine quizzes, and card collections.

*More releases coming soon!* 📦
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 🏷️ Advanced Tagging System
Characters get comprehensive psychological profiles using standardized tags. As of right now only some tags have working repositories, but as BunnyMo is a massive project, more are being worked on every day! 

**Example tags:**
```
<BunnymoTags>Alice: <SPECIES:Human>, <DERE:Tsundere>, <ATTACHMENT:Anxious>, 
<KINK:Service_Sub>, <SEXY:SUB>, <TRAIT:Perfectionist>, <MBTI:ESFJ-U></BunnymoTags>
```

## 📋 Analysis Command
- `!fullsheet` - Generates complete psychological analysis and character tags. (Below is what the World Info Info should look like if it's triggered correctly)

<img width="600" height="333" alt="{2B3F211E-9F41-453D-B3C3-0DEA1B33CD68}" src="https://github.com/user-attachments/assets/410a059f-1b22-46b2-bdd8-6b0a70cbe6cb" />


## 🚀 Installation & Setup

1. **🧠 Install the Core**: Download and add the main Bunnymo lorebook to your AI system
2. **🎁 Choose Your Packs**: Add whichever expansion packs match your interests  
3. **💬 Build Context**: RP with your characters for 20+ messages so they adapt to you. (Perfume out the bottle smells different than it does on your skin.) 
4. **📊 Run Analysis**: Use `!fullsheet` to generate complete character analysis and tags
5. **📂 Archive Results**: You have two options:
   - **5A (Token Efficient)**: Copy only the tags into the Character Archives section, set the entry keys to character names/titles so it activates when they're present
   - **5B (Token Heavy)**: Copy the entire sheet into Character Archives if you want the AI to have more detailed analysis
   
   **Note**: If characters are main characters who come up a lot, set them as "constant", otherwise leave at "normal" (applies to both options)

## ⚙️ Recommended Settings
- **Output Token Cap**: 13k+ when triggering the !fullsheet command (the analysis is comprehensive!) 🔢
- **From the Jump**: While you shouldn't run the !fullsheet command immediately, we recommend that at the start of your RP you have at *least* the base BunnyMo **on.** While it is possible to turn it on and use it in an already started/long RP, I've noticed that there is sometimes an issue with getting it to actually initiate in those cases.


  <img width="514" height="351" alt="{086DC638-2069-488F-BA0D-D89E7A1B070E}" src="https://github.com/user-attachments/assets/bc30ad19-77f8-4ae2-9c53-58c3fbce0360" />
--------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🔧 Common Issues

### "The sheet cut off!" 😤  

Make sure your token output limits are high enough for it to generate.
If that fails, Try swiping.
If that fails, try a full regenerate.
Otherwise, get gemini'd lmao.


### "!fullsheet isn't running!" 😭  

Make sure you turned BunnyMo on. Downloading it and importing it will not automatically turn it on.
Try prefacing your ask exactly like this: `(OOC: PAUSE THE RP AND RUN !FULLSHEET AS DIRECTED.)`  
If that still doesn't work, try using Guided Generations.
If that fails, RP out a few messages and try again. 
If all else fails, in some RARE cases it seems that the AI model (particularly Gemini) becomes so pattern-entrenched it literally will not take into consideration what you are trying to do. (This is usually a problem with stories that run BunnyMo after their story has already started and gotten far in.) Keep BunnyMo on and regularly check the thinking block. If you see it start to mention MBTI, commands like !fullsheet or !bio, outputting tags or anything like that; try running !fullsheet again then.


### "I don't see any tags in the output!" 🏷️

The tags are there, but SillyTavern has the "view tags" setting turned off by default. If you see a section where tags should be but it's blank, just edit the message and you'll see them!

### "Several entries are running when they weren't mentioned!" 💢

Check the recent thinking and see if it was mentioned there. 
Turn off vectorization in the extension settings and see if that helps.
If all else fails, download this extension: https://github.com/LenAnderson/SillyTavern-WorldInfoInfo, take a picture, then send me the triggers AND the full transcript (thinking included) of your last two messages. 

<img width="350" height="350" alt="{8FA2B5C7-349B-400F-8529-B31D4569F256}" src="https://github.com/user-attachments/assets/4a508343-a709-4fdf-9bbb-0339d7db5e63" />


### "My character's MBTI/Dere were one thing, and then the AI just switched it!" 😖
Did you properly put that characters tags into the auto trigger sheets?
If so, try changing the depth of it to 0 and see if it keeps happening. 
***If this one becomes a consistent enough problem, I'll look into seeing what I can do to minimize it. AI will always hallucinate; but the goal of BunnyMo is to reduce that likelihood.***

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🌟 What Makes This Different

This lorebook is intended to be a preset that fires automatically and intelligently using the worldbook settings and activations to our advantage! I've heard good things with all major AI models (however it's still a WIP so don't bite my head off if it bugs and triggers a lot of tokens and you're using Claude 😅). While this is a massive undertaking, it's still in progress, so if you see something: Say something! 🗣️

## 🧪 Testing & Feedback

This system is actively being refined by ~~several~~ ONE ~~bunnies~~ HUMAN in a trenchcoat. If you try it:
- Report what works and what breaks 🐛
- Share interesting character developments 📈
- Suggest improvements to existing frameworks 💡
- Test edge cases and unusual scenarios 🎭
- Share your cool !fullsheets and character analysis' 📊
- Have a good time! 🥕

The goal is creating what aims to be the most psychologically authentic AI roleplay experience possible. Your feedback helps make that happen! 🙏

## 🎉 Special Thanks

**MASSIVE SHOUTOUT TO MY TESTERS** 🌟🎊  
For helping make this dream a reality! Couldn't have done it without you! 💝🐰

---

## 🥕 About the Development Team

This project is *definitely* made by a single, normal human developer and not five bunnies stacked in a trenchcoat pretending to understand code. Any reports of mysterious carrot crumbs in the documentation or inexplicably cute variable names are purely coincidental. The development team asks that you do not look behind the curtain, especially if you hear suspicious munching sounds. 

-# *All inquiries about the nature of our existence should be directed to /dev/null. 🐰🧥✨*

Also, NemoVonNirgend, amazing creator of the Vex preset (and great friend) helps ~~us~~ me make and refine this! He also inspired me to create this. Give him a round of pa-... Hands...

*We are absolutely not bunnies. Please do not bring lettuce to any meetups.*

Thanks for reading!
