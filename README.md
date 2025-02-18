## 🔄 **Updated for Entity Name Changes in Version 0.2.0** 🔄  

# 🏡 KidsChores and Rewards Dashboard  
A fully automated **UI dashboard** designed for the [**KidsChores Integration**](https://github.com/ad-ha/kidschores-ha) by **VaReTaS**, seamlessly integrating with Home Assistant. This dashboard provides a **front-end interface** for interacting with the KidsChores system, which manages all backend logic for chores, points, rewards, and penalties. No custom buttons or manual dashboards are needed—just install, configure, and enjoy a fully featured interface in minutes.  

## 🌟 Overview  
The **KidsChores Dashboard** is a **front-end UI** built on top of the **KidsChores Integration**, which handles all chore tracking, reward management, and point calculations in the background. The dashboard provides a user-friendly interface to interact with those features, giving kids a fun, engaging experience and parents a complete management view without any manual setup.  

### What This UI Provides:  
✅ **A fully automated, kid-friendly interface** for viewing and claiming tasks.  
✅ **A comprehensive parent control panel** for reviewing and approving chore completions and rewards.  
✅ **Automatic categorization** of chores based on their due dates and statuses.  
✅ **Built-in gamification** with badges, streaks, challenges, and rewards.  
✅ **Real-time tracking of achievements and challenges** in easy-to-read cards.  

### What the KidsChores Integration Handles (Backend):  
🔹 **Chore state management** (e.g., overdue, claimed, completed).  
🔹 **Point calculations and balances.**  
🔹 **Badge, challenge, and reward logic.**  
🔹 **Approvals and penalties tracking.**  

---

## 📌 **Features at a Glance**  

### 🧒 **For Kids**  
✅ **Chores organized by category:** Overdue, Morning, Daily, and Anytime.  
✅ **Track progress** with badges earned, streak counts, and points.  
✅ **Redeem rewards** quickly with an interactive button system.  
✅ **View achievements and challenges** with clear progress indicators and rewards.  

### 👩‍👦 **For Parents**  
✅ **Chore Approvals:** Instantly approve or deny completed chores with a simple hold action.  
✅ **Reward Approvals:** Quickly review and approve claimed rewards.  
✅ **Overdue Chore Management:** Reset all overdue chores or individual chore statuses with one tap.  
✅ **Due Date Adjustments:** Change the due date of any chore, including adding or clearing dates.  
✅ **Penalties:** Apply deductions for missed or overdue tasks.  
✅ **Manual Points Adjustments:** Add or remove points for corrections or bonuses.  
✅ **7-Day Activity Log:** View a complete history of chore claims, approvals, penalties, and rewards.  
 
---

# 🎨 KidsChores Dashboard  

### 🏠 Overview  
The **KidsChores Dashboard** is designed to give kids a simple, fun, and engaging way to track their progress, earn rewards, and celebrate their achievements. Built automatically from the [**KidsChores Integration**](https://github.com/ad-ha/kidschores-ha), it encourages responsibility and consistency without any manual setup or customization.  

⭐ **Easy and Fun:** Simple, one-click actions for chores and rewards.  
🚀 **Motivating:** See progress on achievements, challenges, and badges in real-time.  
🎯 **Clear Goals:** Automatically updates with current points, streaks, and upcoming tasks.  

---

### 🔹 Dashboard Sections Overview  

#### 1️⃣ Points & Progress Tracking  
- Displays the child's **current points** and **highest earned badge**, with icons for easy recognition.  
- Shows progress for:  
  - 📅 **Weekly completed chores**  
  - ☀️ **Today’s completed tasks**  
  - 🏆 **Achievements and challenge goals** with clear status indicators.  
- Points labels and icons are automatically sourced from the integration.  

---

#### 2️⃣ Chores Section  
- Chores are **automatically categorized** into:  
  - 🛑 **Overdue** — Chores past their due date  
  - ☀️ **Morning** — Chores due before noon  
  - 🌞 **Daily** — Chores due between noon and midnight  
  - 🗓️ **Anytime** — Future chores or those without a set date  

- Each chore card displays:  
  - 💎 **Points earned**  
  - 🔥 **Streak count**  
  - 📅 **Due date and time**  
  - 📌 **Status:** Pending, Approved, or Claimed  
- Shared chores are clearly marked with **“(S)”** for easy identification.  
- All chores are claimed with a **single click**—no extra actions needed.  
- Completion is indicated by icon color and a badge overlay (no separate “Completed” category).  

---

#### 3️⃣ Rewards Section  
- Allows kids to **redeem rewards instantly** using their earned points.  
- Displays reward details, including:  
  - 💰 **Cost** in points  
  - 📥 **Claims made**  
  - ✅ **Approval status** (if needed)  
  - 🟢 **Can be redeemed now** — clearly indicates if the child has enough points  
- Rewards are automatically listed from the integration—**no manual setup required**.  
- Simple **one-click redemption** makes rewards easy to claim and enjoy.  

---

#### 4️⃣ Kids Showcase – Celebrate Progress and Achievements  
The **Kids Showcase** section is a dedicated dashboard celebrating the child’s progress, milestones, and goals. This section highlights achievements and badges earned while providing detailed progress tracking for ongoing challenges.  

**Showcase Highlights:**  
- 🏅 **Badges Earned:** Displays all collected badges with icons and descriptions.  
- 🌟 **Highest Badge and Multiplier:** Shows the child’s highest badge and its impact on their points earnings.  
- 🏆 **Achievements:** Lists completed and in-progress achievement goals, including total points earned from each.  
- 🔥 **Challenges:** Provides detailed tracking of current challenges, progress percentages, and remaining goals.  
- 💎 **Point Multipliers:** Highlights how badges increase points earned for completing chores.  

The Kids Showcase offers a **fun and motivational way** for kids to see their hard work pay off, track their goals, and stay excited about their progress. 🚀  

---

The **KidsChores Dashboard** is designed with kids in mind—**simple, fun, and automatic.** Everything is generated directly from the integration, so kids can focus on achieving their goals and earning rewards without any confusion or extra steps. 🚀  


---

# 👩‍👦 Parent Chore Dashboard  

### 🏠 Overview  
The **Parent Dashboard** provides **full control** over chore approvals, penalties, and manual point adjustments. Parents can review **pending approvals**, apply **penalties for missed tasks**, and manually adjust points.

📌 **Example Dashboard UI:**  
![image](https://github.com/user-attachments/assets/7017a03e-5d56-4000-a279-6722db2b1401)

### 🔹 Features
- ✅ **Approve or deny chores** with a simple hold action.  
- ✅ **Apply penalties** for incomplete tasks.  
- ✅ **Manually adjust points** when necessary.  
- ✅ **Monitor all chore-related activity** in a **7-day log**.  

---

## 📌 Parent Dashboard Sections

### **1️⃣ Approvals Section ("Hold to Approve")**
- Parents can **approve or deny** chores marked as completed.
- Chores are categorized into:
  - **Pending Chores**
  - **Pending Rewards**
- If no approvals are needed, it displays a **"None Available"** message.

### **2️⃣ Penalties Section ("Hold to Apply")**
- Allows parents to **apply penalties** for missed or incomplete chores.
- Displays **points deducted and penalty count**.

### **3️⃣ Manual Points Adjustment**
- Parents can manually **add or remove points** from the child’s account.

### **4️⃣ Activity Log (7-Day History)**
- Logs all **chore claims, approvals, penalties, and reward redemptions**.

---

# 🔧 How to Implement This Dashboard
Follow these steps to integrate the **Kids Chore & Reward Dashboard** into Home Assistant.

---

## 📌 Step 1: Install Custom Cards  
This dashboard requires **custom frontend cards** to function correctly.

1. **Open Home Assistant**
2. **Go to HACS → Frontend**
3. **Search and install the following cards:**
   - 🟢 **Mushroom Cards** (`custom:mushroom-template-card`)
   - 🟢 **Auto-Entities** (`custom:auto-entities`)
   - 🟢 **Mini Graph Card** (`custom:mini-graph-card`)
4. **Restart Home Assistant** to apply the changes.

---

## 📌 Step 2: Create a New Section Dashboard  
To keep the dashboard organized, create a **separate section for chore tracking**.  You can skip this step if you have an existing location you want to use.

1. **Go to Home Assistant → Settings → Dashboards**  
2. Click **"Create Dashboard"**  
3. **Enter a name** (e.g., `"Kids Chores"`)  
5. Click **"Save"**

---

## 📌 Step 3: Add the Kids Dashboard YAML  
1. **Open your new dashboard.**  
2. Click **"Edit Dashboard" → "Manage Dashboard" 
3. Click **"Add Card"** and select **"Manual"**  
4. **Copy and paste the Kids Chore Dashboard YAML** into the card.  

``` yaml


````

---

## 📌 Step 4: Find and Replace "Kidname"  
Since this YAML uses a **placeholder name**, update it to match your child's name.

1. **Find and replace all instances of:**  
   - `Kidname` → (e.g., `"Payton"`)  
   - `kidname` → (e.g., `"payton"`)  
   - `KIDNAME` → (e.g., `"PAYTON"`)  
2. Ensure **case-sensitive replacement** to avoid errors.  
3. Click **"Save"** to apply changes.  

Note - If you are using something other than "points" for tracking, you will also need to do a find / replace of all versions being sure to match case.

---

## 📌 Step 5: Add the Parent Dashboard YAML  
1. **Click "Add Card"** and select **"Manual"**  
2. **Copy and paste the Parent Chore Dashboard YAML** into the card.  

``` yaml


```


---

## 📌 Step 6: Find and Replace Again  
Since the parent dashboard also references `Kidname`, repeat the **find-and-replace** process. 

1. Replace **all instances** of:  
   - `Kidname`
   - `kidname`
   - `KIDNAME`
2. Click **"Save"** to apply changes.  

Note - If you are using something other than "points" for tracking, you will also need to do a find / replace of all versions being sure to match case.

---

## 🎯 Finalizing the Dashboard  
- 🚀 **Exit edit mode** and test the new chore tracking system!  
- ✅ Ensure **buttons update chore statuses correctly.**  
- 🛠 If any entities are missing, check **sensor and button names** in Developer Tools → States.  

---

Your **Kids Chore & Reward Dashboard** is now fully functional in **Home Assistant**! 🎉  

📌 **Need help?** Drop a comment below! 🚀  
