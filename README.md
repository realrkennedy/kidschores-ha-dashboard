# 🏡 Kids Chores and Rewards Dashboard  
A fully automated **UI dashboard** built specifically for the [**KidsChores Integration**](https://github.com/ad-ha/kidschores-ha), seamlessly integrating with Home Assistant. Designed to provide a **complete front-end experience**, this dashboard makes it easy to interact with the KidsChores system—allowing kids to claim chores, track progress, and redeem rewards while giving parents full control over approvals and management.  

No custom buttons or manual dashboard setup required—just install, configure, and enjoy a **fully featured, ready-to-use interface** in minutes!

![image](https://github.com/user-attachments/assets/e684f032-ab47-44c0-98fa-1df4431d2a7e)

<a href="https://www.buymeacoffee.com/shillingcll" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>

---

## 🌟 **Why Use the KidsChores Dashboard?**  

✅ **A fully automated, mobile-friendly interface** for kids to view and claim tasks.  
✅ **Comprehensive parent control panel** for reviewing and approving chores & rewards.  
✅ **Built-in gamification** – Badges, streaks, rewards, penalities, bonuses, challenges, and achievement tracking.  
✅ **Multi-Language Support** – Now available in **5 languages**, and it only take 30 minutes to add a new one! 🌍   
✅ **Automatic chore categorization** based on due dates and statuses or custom grouping by label.  
✅ **Real-time updates** on chore approvals, penalties, and rewards.  
✅ **Optimized for all devices** – Works seamlessly on **mobile, desktop, and tablets**.  

### What is the KidsChores Integration by **@ad-ha (VaReTaS)**?: 
 The **KidsChores Integration** handles all chore tracking, point management, and automation in the background, while the **KidsChores Dashboard** provides a **user-friendly front-end UI** for kids and parents to interact with those features.

  
 🔹 **Chore state management** (e.g., overdue, claimed, completed).  
 🔹 **Point calculations and balances.**  
 🔹 **Badge, challenge, and reward logic.**  
 🔹 **Approvals and penalties tracking.**  

---

## 📌 **Features at a Glance**  

### 🧒 **For Kids**  
✅ **Chores organized by category or custom label:** Overdue, Morning, Daily, Upcoming, or Custom.
✅ **Track progress** with badges earned, streak counts, and points.  
✅ **Redeem rewards** quickly with an interactive button system.
✅ **View bonuses, penalties, achievements and challenges** with clear progress indicators and rewards.  

### 👩‍👦 **For Parents**  
✅ **Chore Approvals:** Instantly approve or deny completed chores with a simple hold action.  
✅ **Reward Approvals:** Quickly review and approve claimed rewards.  
✅ **Overdue Chore Management:** Reset all overdue chores or individual chore statuses with one tap.  
✅ **Due Date Adjustments:** Change the due date of any chore, including adding or clearing dates.  
✅ **Bonuses & Penalties:** Apply Bonuses to reward good behaviors or deductions for accountability.  
✅ **Manual Points Adjustments:** Add or remove points for corrections or bonuses.  
✅ **7-Day Activity Log:** View a complete history of chore claims, approvals, penalties, and rewards.  
 
---

# 🎨 Kids Dashboard  

### 🏠 Overview  
The **Kids Dashboard** is designed to give kids a simple, fun, and engaging way to track their progress, earn rewards, and celebrate their achievements. Built automatically from the [**KidsChores Integration**](https://github.com/ad-ha/kidschores-ha), it encourages responsibility and consistency without any manual setup or customization.  

⭐ **Easy and Fun:** Simple, one-click actions for chores and rewards.  
🚀 **Motivating:** See progress on achievements, challenges, and badges in real-time.  
🎯 **Clear Goals:** Automatically updates with current points, streaks, and upcoming tasks.  

---

### 📌 **Example Kids Dashboard UI:** 
  <p align="left">
    <img src="https://github.com/user-attachments/assets/654c9046-afdf-49f8-bda7-75eff5459cc3" width="30%">
  </p>

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
  - ☀️ **Due this Morning** — Chores due before noon  
  - 🌞 **Due Today** — Chores due between noon and midnight  
  - 🗓️ **Upcoming & Bonus** — Future chores or those without a set date
  - 🏷️ **Custom Labels** — Create and assign labels in the integration to **group, filter, or exclude chores** based on category, difficulty, or any custom criteria.  

- Each chore card displays:  
  - 💎 **Points earned**  
  - 🔥 **Streak count**  
  - 📅 **Due date and time**  
  - 📌 **Status:** Pending, Approved, or Claimed  
- Shared chores are clearly marked with **“(S)”** for easy identification.  When one child claims a shared chore, the dashboard visually updates for the other assigned kids by displaying a purple icon and a multi-person symbol, indicating that someone else has already completed it. However, this is purely for awareness—each child's chore responsibility remains independently handled in the backend system. Their task can still become overdue if unclaimed, and they can still claim and get approval for completing it. While single-completion shared chores aren't currently supported, this visual indicator can serve as a helpful workaround for families managing shared tasks.

![image](https://github.com/user-attachments/assets/895987ec-e3ca-4d75-b034-435492d3f649)


- Multi-claim chores now display in blue after their first approval. These chores also show an "(M)" after their status, indicating they can be claimed again.

![image](https://github.com/user-attachments/assets/52362b7f-633e-4df2-b6d4-1cefaddaf864)

 
- All chores are claimed with a **single click**—no extra actions needed.  
- Completion is indicated by icon color and a badge overlay (no separate “Completed” category).  
<p align="left">
  <img src="https://github.com/user-attachments/assets/73897ced-0199-46d0-8fbf-151b13a9e5c8" width="30%">
</p>

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
- **Reward Categories** — Organize rewards into **custom groups**, by using labels in the integration making it easier manage or filter different types of incentives.   

---

#### 4️⃣ Kids Showcase – Celebrate Progress and Achievements  
The **Kids Showcase** section is a dedicated dashboard celebrating the child’s progress, milestones, and goals. This section highlights achievements and badges earned while providing detailed progress tracking for ongoing challenges.  

**Showcase Highlights:**  
- 🏅 **Badges Earned:** Displays all collected badges with icons and descriptions.  
- 🌟 **Highest Badge and Multiplier:** Shows the child’s highest badge and its impact on their points earnings.  
- ⭐ **Bonuses:** Tracks extra points awarded for exceptional effort.  
- ❌ **Penalties:** Displays applied point deductions for missed chores or rule-breaking.  
- 🏆 **Achievements:** Lists completed and in-progress achievement goals, including total points earned from each.  
- 🔥 **Challenges:** Provides detailed tracking of current challenges, progress percentages, and remaining goals.  
- 💎 **Point Multipliers:** Highlights how badges increase points earned for completing chores.  


The Kids Showcase offers a **fun and motivational way** for kids to see their hard work pay off, track their goals, and stay excited about their progress. 🚀  

---

### 📌 **Example Kids Showcase Dashboard UI:** 
  <p align="left">
    <img src="https://github.com/user-attachments/assets/f1ac0c6a-1dc1-4b23-a21a-83d9adabb15b" width="30%">
  </p>

---

The **KidsChores Dashboard** is designed with kids in mind—**simple, fun, and automatic.** Everything is generated directly from the integration, so kids can focus on achieving their goals and earning rewards without any confusion or extra steps. 🚀  


---

# 👩‍👦 Parent Chore Dashboard  

### 🏠 Overview  
The **Parent Dashboard** is a fully automated control panel for managing chore approvals, point adjustments, and penalties. It is designed to **minimize space** by **dynamically showing sections** only when actions are needed—such as pending approvals or overdue chore resets. Built on the [**KidsChores Integration**](https://github.com/ad-ha/kidschores-ha), it offers intuitive, space-efficient cards for full parental control.  

📌 **Smart Display:** Sections like approvals and overdue chore resets **only appear when required.**  
💥 **Quick Actions:** All actions use **“Single click to apply”** for quick and easy interactions.  
📊 **Full Visibility:** Activity logs provide a complete history of points and approvals.  

---

### 🔹 Features Overview  

- ✅ **Parent Dashboard Overview Card** — Displays key stats such as points, progress, and penalties.  
- ✅ **Approve or deny chores and rewards** with a simple hold action.  
- ✅ **Reset overdue chores** individually or all at once.  
- ✅ **Adjust individual chore due dates** quickly.  
- ✅ **Manage points, bonuses, and penalties under “Pluses & Minuses.”**  
- ✅ **Monitor all activity** with a 7-day activity log.  

---

### 📌 **Example Parents Dashboard UI:** 
  <p align="left">
    <img src="https://github.com/user-attachments/assets/d3628304-ef3d-4c5c-8796-b1d221b5d7e7" width="30%">
  </p>

---

## 📌 Parent Dashboard Sections  

### **1️⃣ Parent Dashboard Overview Card**  
The **Parent Dashboard Overview Card** provides a quick snapshot of the child's progress and current status:  
- 📊 **Current Points Total** with point label and icon.  
- 📅 **Chores Completed:** Today, This Week, and This Month.  
- 🚨 **Number of Overdue Chores**, if any.   

---

### **2️⃣ Approvals Section**  
- **Appears only when approvals are pending**—fully hidden otherwise.  
- Allows parents to **approve or deny**:  
  - 📝 **Pending Chores**  
  - 🎁 **Pending Rewards**  
- Displays important details like points earned and completion status.  

 <p align="left">
   <img src="https://github.com/user-attachments/assets/6ef975ea-d2e3-44e1-9872-6ac3b7029d80" width="30%">
 </p>
  
---

### **3️⃣ Overdue Chores Management**  
- **Appears only when chores are overdue.**  
- Provides two options:  
  - 🛑 **Reset All Overdue Chores** for the child.  
  - 📌 **Reset Individual Chores** with due date and status shown.  

 <p align="left">
   <img src="https://github.com/user-attachments/assets/e2b1807b-b957-49c7-9d83-d9df78f74cb5" width="30%">
 </p>

---

### **5️⃣ Chore Due Date Adjustments**  
- Displays a **chore selector** to quickly find and update due dates.  
- Provides options for adjusting due dates:  
  - 📅 **+Next Due**
  - 📅 **+1 Day**    
  - 📅 **+1 Week**  
  - ❌ **Clear Date**  
  - 📆 **Set Custom Date and Time** with a date picker.

- Before selecting a chore:
  
 <p align="left">
   <img src="https://github.com/user-attachments/assets/ba74677c-fb94-41cf-b125-7a5eaa1d2015" width="30%">
 </p>

- Options appear after chore is selected:

 <p align="left">
   <img src="https://github.com/user-attachments/assets/0e7c400c-3866-444e-a1b6-0ca2b2a0d0c0" width="30%">
 </p>
 
---

### **4️⃣ Pluses & Minuses**  
The **Pluses & Minuses** section combines **Bonuses,** **Manual Points Adjustments,** and **Penalties**, providing an all-in-one interface for point management.  

#### ➕ **Manual Points Adjustment**  
- Displays easy-access buttons to:  
  - ➕ **Add points** (e.g., for extra chores or positive behavior).  
  - ➖ **Remove points** (e.g., corrections or adjustments).  
- Shows the child's current point total and updates immediately.

#### ⭐ **Bonus Management**  
- Allows parents to **apply custom bonuses** as extra rewards.  
- Each bonus button shows:  
  - ⭐ **Bonus name & point value**  
  - 📊 **Times the bonus has been applied**  
- Applied bonuses are reflected in the **Showcase Overview** and **Point Totals**. 

#### 💥 **Penalties Management**  
- Displays penalty options to deduct points for missed chores or behavior issues.  
- Each penalty button shows:  
  - 💥 **Points deducted**  
  - 📊 **Times penalty was applied**  
- Applied penalties are reflected in the **Showcase Overview** and **Point Totals**. 

---

### **6️⃣ Activity Log (7-Day History)**  
- Logs all chore-related activity, including:  
  - 📝 **Chore claims**  
  - ✅ **Chore and reward approvals**  
  - 💥 **Penalties applied**  
  - 💰 **Reward redemptions**  
- Provides a **clear timeline of events** for easy tracking.  

---

The **Parent Chore Dashboard** is designed to be **efficient and intuitive**, showing only necessary options and grouping key actions under **“Pluses & Minuses”** for simplicity. All functionality is powered by the **KidsChores Integration**, ensuring automatic updates and zero manual setup. 🚀  


---

# 🔧 How to Implement This Dashboard
Follow these steps to quickly set up the **KidsChores Dashboard** in Home Assistant, including both the **Kids** and **Parent** sections.  

This approach creates a **complete dashboard** in one step. Once it’s set up, you can:  
- 📌 **Move individual cards** to different positions or dashboards.  
- 🛠️ **Customize the layout** to suit your needs.  
- 📝 **Extract specific sections** from the dashboard YAML if you prefer to use them individually or in other dashboards.  

If you’re comfortable working with YAML, you can review the dashboard code to **select and reuse any individual cards or sections** that fit your needs.  
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

## 📌 Step 3: Add the Dashboard YAML  

1. **Open your new dashboard.**  
2. Click **"Edit Dashboard" → "Manage Dashboard"**  
3. Click the **"Edit Pencil"** next to the view name and select **"Edit YAML"**  
4. **Copy and paste the correct Kids Chores Dashboard YAML** file into the view.

 <p align="left">
  <img src="https://github.com/user-attachments/assets/21fe22b0-26d8-4031-a1f9-005f10d4f2ad" width="50%">
</p>

### 🌍 **Selecting dashboard with the correct language**  
The dashboard files are available in multiple languages. Choose the correct file based on the **2-letter ISO language code** at the end of the filename:  

| Language  | File Name |
|-----------|----------------|
| 🇩🇰 Danish  | `kc_dashboard_da.yaml` |
| 🇩🇪 German  | `kc_dashboard_de.yaml` |
| 🇬🇧 English | `kc_dashboard_en.yaml` |
| 🇫🇮 Finnish | `kc_dashboard_fi.yaml` |
| 🇳🇱 Dutch   | `kc_dashboard_nl.yaml` |

📌 **Find the latest files here:**  
🔗 [KidsChores Dashboard YAML Files](https://github.com/ccpk1/kidschores-ha-dashboard/blob/main/files)  

## 📌 Step 4: Find and Replace "Kidname"  
Since this YAML uses a **placeholder name**, update it to match your child's name.

1. **Find and replace all instances of:**  
   - `Kidname` → (e.g., `"Payton"`)  
2. After you paste the YAML file in, **Press \<CTRL\> F** to bring up Find/Replace
3. Ensure **case-sensitive replacement** to avoid errors.  
4. Click **"Save"** to apply changes.  

 <p align="left">
  <img src="https://github.com/user-attachments/assets/9413ff96-02a5-453b-bb17-c4a4eed758e4" width="50%">
</p>

Note - No longer required to change the "points" text, the new dashboard dynamically grabs the point label from the integration.

---

## 📌 Step 5: Add Required Helpers (UI Support)  
Currently, the KidsChores Dashboard requires a single **datetime helper** to support interactive features in the UI.

You will need to add:  
- 🗓️ **input_datetime.kc_ui_set_date_helper** — For setting custom due dates from the dashboard. The name of the entity is critical, so enter it carefully.  To add a helper, go to Settings \ Devices & Services \ Helpers then select "+ CREATE HELPER" and choose "Date and/or time"

![image](https://github.com/user-attachments/assets/a587f4d2-5875-4ff7-a69e-14d7ee1a7f5f)


An **optional** automation can be added to continuously set the date of the date of that helper to tomorrow at 11PM.  Without this automation, the datetime will remain at whatever was last selected, which is not an issue.
- ⚙️ **Automation: kc_ui_set_date_on_hold** — .  

📄 [**kc-dashboard-uihelpers.yaml**](https://github.com/ccpk1/kidschores-ha-dashboard/blob/main/files/kc-dashboard-uihelpers.yaml)  


---

## 🎯 Finalizing the Dashboard  
- 🚀 **Exit edit mode** and test the new chore tracking system!  
- ✅ Ensure **buttons update chore statuses correctly.**  
- 🛠 If any entities are missing, check **sensor and button names** in Developer Tools → States.  

---

Your **Kids Chore & Reward Dashboard** is now fully functional in **Home Assistant**! 🎉  

If you haven't already done so, take a few minutes to look through the KidsChores integration Wiki which is loaded with helpful information as you get started.
👉 Integration Wiki

---

## 🚨 **Known Issues & Workarounds**  

### 🔹 **Renaming Chores and Rewards**  
While renaming chores and rewards works correctly **within the KidsChores integration**, it does **not** update the **entity names**, which the dashboard relies on to match the **friendly_name**.  

#### **Recommended Workaround:**  
✔ **Best Option:** Delete the chore or reward and **recreate it with the new name**.  

✔ **Manual Fix:** If you prefer to keep the existing entity, you can manually rename **all associated button and sensor entities** to match the new friendly name.  
  - However, **you must account for Home Assistant's special character handling**.  
  - **Accent characters are automatically normalized** (e.g., `"Štěpán"` → `"stepan"`).  
  - Spaces and special characters are replaced with **underscores (`_`)**.  
  - **Duplicate and trailing underscores are removed**.  
  - Example:  
    - `"Brush Teeth (Morning)"` becomes `"_brush_teeth_morning"`.  
    - `"Šimon’s Dishes!"` becomes `"_simons_dishes"`.  

If you experience issues after renaming a chore or reward, verify that the **entity names** match the expected format based on **Home Assistant’s naming conventions**.  

---

📌 **Need help?** Log and issue here or visit the thread on the Home Assistant Forum [Introducing the KidsChores and Rewards Dashboard](https://community.home-assistant.io/t/introducing-the-kidschores-and-rewards-dashboard) ! 🚀  
