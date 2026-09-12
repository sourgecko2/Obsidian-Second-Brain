# Obsidian-Second-Brain
My personal note taking vault accelerated by AI, tags and simple connections.

# Screenshots
![Screenshot 1](https://raw.githubusercontent.com/sourgecko2/Obsidian-Second-Brain/media/screenshot1.png)
![Screenshot 2](https://raw.githubusercontent.com/sourgecko2/Obsidian-Second-Brain/media/screenshot2.png)
![Screenshot 3](https://raw.githubusercontent.com/sourgecko2/Obsidian-Second-Brain/media/screenshot3.png)
![Screenshot 4](https://raw.githubusercontent.com/sourgecko2/Obsidian-Second-Brain/media/screenshot4.png)

## Problems with study notes
Across my entire secondary student life of 5 years or so, I have struggled continuously with finding the right information management system. I have tried many different note-taking apps: Apple Notes, Notion, Obsidian, .txt files and even physical notebooks! None of these systems were searchable, approachable and organised in a way that doesn't leave thoughts and important information lost in endless 'folder rabbit holes'. I wanted something as good and useful as paper that harnesses the power of digital tools and with organisation that doesn't leave me lost. The reality is the intersection between these categories is incredibly hard to build!

A few years ago, I was manually scanning my Notebook pages into an older Obsidian vault. It was incredibly tedious and time-consuming, and I couldn't search through my notes effectively. I realized that I needed a better system to manage my knowledge and ideas. I couldn't effectively form connections in my mind between ideas and was struggling to retain information. Yes, I was ticking each box, but the friction and lack of proper context impacted my ability to learn and retain information. As I move into tertiary education, I need a much better system, so I thought why not use my technical skills to build one?

## The build
The main idea behind this vault is to have a system with three phases: Capture, Processing and Output / Recursion. 

### Capture
As for on-the-go capture, I've built some Apple shortcuts to helpe me capture information to a note in my vault, with one press of the action button on my iPhone. I can also use the share sheet to share links, images, text or anything else. 

Within the vault, I can quickly create templated notes with the plugin QuickAdd with a simple hotkey. This allows me to blurt information quickly and organise it in record time.

### Processing
I use a combination of Daily notes, Pinboard notes and personal project-based notes to process and learn information. I organise using tags, such as `competency/low` or `competency/high` to assess my knowledge of notes. I can use AI to summarise notes, generate questions and answers, and even create flashcards for spaced repetition in Anki. I can also use AI to help me connect ideas and concepts across different notes. This is achieved using ACP with my consumer-grade Claude subscription. I can also handwrite notes on my iPad and directly import them, allowing me to view my ink and OCR them for querying and searching. Not to mention inline LaTeX, Mermaid, Code blocks or inline diagrams with Excalidraw. This is by far the richest system available. Could have only been possible with the power of Obsidian's thriving community and plugin ecosystem.

### Output / Recursion
I can create finalised notes which sit with everything else. To quickly search them, I can use the semantic search feature already built in, graph view to see connections or click wikilinks from other notes. Most importantly, I can actually ask questions directly to the vault using AI, and it will use the same semantic index to bring relevant information and context to the answer. I can also revise information using spaced repetition (the tags), make mindmaps using the Canvas feature and blurt with connected notes for revision.

## Verdict
For anyone sitting on the fence or moving indecisively between systems, the best unified system of all time is a simple Obsidian setup. The best thing to do is to make a simple tool that just works quickly, to minimise friction and avoid forgetting important things. Ultimately, this will improve your ability to learn and retain information, and help you form connections between ideas, eventually to see the bigger picture.

## Dotfiles and installation
All you need is:
- Obsdian version 1.13.7 or later
- An AI subscription (Claude is best for this), self host model or other API key

Then just clone this repo:

```bash
git clone https://github.com/sourgecko2/Obsidian-Second-Brain.git
```

and open the vault in Obsidian. You can then install the plugins and set up your AI subscription. 

**The first thing you should do is read through the config/ folder to see how the vault is set up and how to use it, especially since a lot of options are hidden in the command palette or behind hotkeys!!**

## Cloud sync (optional but recommended)
If you have iCloud, move the vault to your iCloud folder and enable sync. If you don't have iCloud, you can use the Git plugin to sync your vault across devices.

## Final notes
The setup is done to my taste. Feel free to switch whatever you like to your tastes - it's your vault! This is just a suggestion of how to set up a vault.