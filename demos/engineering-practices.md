# Engineering Practices Demo

Welcome to the GitHub Copilot engineering practices demo! Here we're going to get comfortable with the professional tools and features in GitHub Copilot. We'll start in the VS Code IDE and then move to github.com for additional collaboration features.

## What You'll Learn
By the end of this demo, you will:
- [ ] Understand how to debug and inspect Copilot's decision-making process
- [ ] Know how to share chat conversations with team members
- [ ] Be familiar with system prompts and their importance
- [ ] Understand collaboration features on GitHub.com

**Estimated Time:** 10-15 minutes

## 🔧 IDE Features

GitHub Copilot has many features designed to help engineering teams understand AI decision-making and collaborate effectively on code generation.

### 🐛 Step 1: Inspect Copilot's Decision Process

**Why this matters:** Understanding how Copilot makes suggestions helps you write better prompts and trust the AI's recommendations.

#### Method 1: Using Keyboard Shortcut
1. Press `Ctrl + Shift + P` (Windows/Linux) or `Cmd + Shift + P` (Mac)
2. Type "Copilot Chat Debug"
3. Select **"Copilot Chat Debug: Focus on Copilot Chat Debug View"**

#### Method 2: Using the Menu
1. Go to **View** → **Command Palette**
2. Type "Copilot Chat Debug"
3. Select **"Copilot Chat Debug: Focus on Copilot Chat Debug View"**

#### What You'll See
Once the debug panel opens, you can explore:
- **Prompts:** The actual prompts sent to the AI
- **System Prompts:** Background instructions given to Copilot
- **Metadata:** Context information and settings
- **Response Details:** How Copilot formulated its suggestions

**💡 Pro Tip:** Use this when Copilot's suggestions seem unexpected - you can see exactly what context it's using!

---

### 💬 Step 2: Share Chat Conversations with Your Team

**Why this matters:** Sharing successful prompts and conversations helps your team learn effective AI collaboration patterns.

#### Export a Chat Conversation

**Method 1: Keyboard Shortcut**
1. Press `Ctrl + Shift + P` (Windows/Linux) or `Cmd + Shift + P` (Mac)
2. Type "Chat: Export"
3. Select **"Chat: Export Chat..."**

**Method 2: Menu Navigation**
1. Go to **View** → **Command Palette**
2. Type "Chat: Export"
3. Select **"Chat: Export Chat..."**

**What happens:** This creates a file containing your entire chat history that you can share with teammates.

#### Import a Chat Conversation

**Method 1: Keyboard Shortcut**
1. Press `Ctrl + Shift + P` (Windows/Linux) or `Cmd + Shift + P` (Mac)
2. Type "Chat: Import"
3. Select **"Chat: Import Chat..."**

**Method 2: Menu Navigation**
1. Go to **View** → **Command Palette**
2. Type "Chat: Import"
3. Select **"Chat: Import Chat..."**

**Use case:** Import conversations shared by teammates to see their successful prompting strategies.

---

## 🌐 GitHub.com Collaboration Features

GitHub.com provides additional tools for managing Copilot at the organizational level and sharing knowledge across teams.

### 🎛️ Step 3: Explore Prompts

**Why this matters:** Prompts define how Copilot behaves across your organization. Understanding these helps ensure consistent, high-quality code generation that follows your team's standards.

#### Personal Instructions
1. **Navigate to GitHub Copilot:** Go to [https://github.com/copilot](https://github.com/copilot)
2. **Access settings:** Click on your user icon on the bottom-left corner
3. **Open personal instructions:** Select **"Personal instructions"**
4. **Add in instructions:** You can add customize guidelines into how Copilot responds to your prompts

#### What to Explore
- **Personal instructions:** Are there any preferences you'd like in the instructions? Test it out!

---

### 🤝 Step 4: Export Conversations to Share with Your Team

**Why this matters:** Exporting conversations creates a knowledge base of effective AI interactions your team can learn from and build upon.

> **Note:** GitHub Copilot on github.com previously offered a one-click **Share** link. That feature has been replaced — the supported way to hand a conversation to a teammate today is **Export**, which produces a file you can attach to an issue, PR, wiki page, or chat message.

#### Export a Conversation
1. **Navigate to GitHub Copilot:** Go to [https://github.com/copilot](https://github.com/copilot)
2. **Start a chat:** Start a conversation. In the chat window, type the following prompt:
   ```markdown
   What are the advantages of the Go programming language?
   ```
3. **Open the conversation menu:** Hover over the conversation in the **Chats** list in the left sidebar and click the **`…`** that appears (or click the **▾** next to the chat title at the top of the conversation)
4. **Export:** Choose **Export** and save the file. Available actions in this menu are **Rename**, **Export**, and **Delete**.
5. **Share the file** with your team via your usual channel (issue, PR comment, Teams/Slack, wiki, etc.)

#### What to Explore
- **Export format:** Open the exported file — notice it captures the full prompt/response history so a teammate gets the same context you had
- **Reuse:** Teammates can paste the exported prompts into their own chat to reproduce or build on your work
- **Combine with personal instructions:** Pair a shared export with the personal instructions from Step 3 to show how setup + prompt together produced the result

**💼 Best Practices for Sharing Exports:**
- Export conversations that solved complex problems
- Include a short note about *when* and *why* the approach worked when you share the file
- Store reusable, high-value exports somewhere discoverable (team wiki, repo `docs/` folder) rather than only DMs

## 🚀 What's Next?

Congratulations! Second demo has been complete.

👉 **[Start Customize Copilot Demo](./customize-copilot.md)**
