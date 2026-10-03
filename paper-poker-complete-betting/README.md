# ♠ Paper Poker — Real-Time Multiplayer Betting Companion

A sleek, real-time multiplayer digital chip and betting companion for **Paper Poker**. Perfect for playing poker with friends where physical cards are dealt on paper/table while chip stacks, ₹1 separate boots, pots, and raises are tracked digitally across everyone's phones or laptops!

---

## 🚀 Features

- **🌐 Instant P2P Multiplayer (WebRTC via PeerJS):**
  - No backend server or database setup required!
  - Works anywhere across home WiFi and mobile 4G/5G networks.
- **💰 ₹1 Separate Boot System:**
  - One-click collection of the mandatory ₹1 boot from all 2–7 joined players.
  - Automatic chip breakdown: If a player is out of ₹1 coins, larger chips (₹5, ₹10) are automatically broken down so boot can always be paid.
- **🪙 Authentic Indian / Paper Poker Chip Stacks:**
  - Initial stack: **₹210** per player (10×₹1, 10×₹5, 5×₹10, 2×₹25, 1×₹50).
- **📱 Mobile & Tablet Friendly:**
  - Responsive casino felt oval table with dynamic elliptical seating.
  - Quick-raise buttons (+₹1, +₹5, +₹10, +₹25).
- **🔗 1-Click Invite Links:**
  - Host can click "Share Room Link" to copy a direct WhatsApp/share link (`?room=CODE`).
- **🏆 Showdown & Pot Distribution:**
  - When players reveal their physical cards, the Host can award the pot to the winner with one tap!
- **🤖 Built-in Bot Testing:**
  - Host can click `+ Add Test Bot` to test gameplay immediately even before friends connect!

---

## 📦 How to Deploy on Vercel

### Method 1: Deploy with GitHub (Recommended & Easiest)

1. **Initialize Git and commit your project:**
   Open PowerShell in this folder and run:
   ```bash
   git init
   git add .
   git commit -m "Paper Poker Complete Multiplayer"
   ```
2. **Push to GitHub:**
   - Create a new repository on [github.com/new](https://github.com/new) (name it e.g. `paper-poker`).
   - Run the commands GitHub shows:
     ```bash
     git remote add origin https://github.com/<your-username>/paper-poker.git
     git branch -M main
     git push -u origin main
     ```
3. **Import to Vercel:**
   - Go to [vercel.com](https://vercel.com) and log in.
   - Click **"Add New..."** → **"Project"**.
   - Select your `paper-poker` GitHub repository and click **"Deploy"**.
4. **Done!**
   - Vercel will instantly generate a live URL (e.g. `https://paper-poker-xyz.vercel.app`).
   - You and your friends can immediately open this link on your phones or laptops!

---

### Method 2: Deploy directly from PowerShell via Vercel CLI

1. Run:
   ```bash
   npx vercel
   ```
2. When prompted:
   - Log in to your Vercel account in your browser.
   - Set up and deploy `e:\paper-poker-complete-betting`? **Y**
   - Which scope? Select your personal account.
   - Link to existing project? **N**
   - Project name? Press Enter (or type `paper-poker`).
   - Directory located at? Press Enter (`./`).
3. To deploy to production, run:
   ```bash
   npx vercel --prod
   ```
   You will get a live production URL ready to share!

---

## 🎮 How to Play with Friends

1. **Host Creates Table:**
   - Host opens the Vercel URL, types their name, and clicks **"Create New Table (Host)"**.
   - A 5-letter Room Code is generated (e.g. `A7K9M`).
2. **Friends Join:**
   - Host clicks **"🔗 Share Room Link"** and sends the link to friends on WhatsApp/Discord.
   - Friends tap the link, type their name, and click **"Join Table"**.
   - All friends appear around the casino table in real time!
3. **Boot and Deal:**
   - Once all friends (2 to 7 players) have joined, Host clicks **"💰 BOOT (₹1) & START ROUND"**.
   - ₹1 is collected from every player's stack into the pot.
   - Deal your physical paper/card hand in real life!
4. **Betting Rounds:**
   - Players take turns calling (or checking), raising, or packing (folding).
   - Only the player whose turn it is can act.
5. **Showdown:**
   - When all bets are settled and friends show their cards, Host clicks **"🏆 Award Pot (Showdown)"** and selects the winner to deposit the full pot into their chip balance!
