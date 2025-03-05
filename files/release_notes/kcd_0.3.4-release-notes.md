# 🚀 Kids Chore Dashboard - Feature Enhancements KCD_0.3.4

## 🌍 Multi-Lingual Support
Now available in **English, Danish, Dutch, Finnish, and German**. A huge thank you to:
- **Danish**: @dehoej 🇩🇰  
- **Dutch**: @WilbertVerhoeff 🇳🇱  
- **Finnish**: @mikkomakipaa & @dehoej 🇫🇮  
- **German**: @kolossboss 🇩🇪  

A special shout-out to **@kolossboss**, who originally submitted a translated version of the dashboard. While reviewing it, I realized that for long-term support of multiple languages, the dashboard needed a complete rework. **@kolossboss** assisted in testing the first version, and thanks to this effort, it's now possible to quickly add new languages for anyone interested in contributing a translation! ✨

![image](https://github.com/user-attachments/assets/db4467a8-05a6-4db5-8028-93448be9fe1a)

---

## 📌 **Chore & Reward Categories**
- Chores and rewards can now be **grouped** or **excluded** by category, a new feature in the **[KidsChores Integration 0.3.0](https://github.com/ad-ha/kidschores-ha)**

![image](https://github.com/user-attachments/assets/dda5c0ed-f5cd-4404-bce7-9530b104d2a9)

---

## 🎯 **Support for New Bonus Features**
- Integrated with the latest **Bonus system**, a new feature in the **[KidsChores Integration 0.3.0](https://github.com/ad-ha/kidschores-ha)**
- Shows **total bonuses earned** and allows parents to **apply bonuses** easily.

#### Kid's Showcase:
![image](https://github.com/user-attachments/assets/6adc7c2c-50ad-4601-8ad4-11bec5fa39f3)

#### Parent Dashboard
![image](https://github.com/user-attachments/assets/f25db660-05fb-4d0b-a0c0-73ceb11703fd)

---

## 🏆 **New Badge Cards**
- Shows **earned and upcoming badges**.
- Displays **progress** toward the next badge.
- Highlights **points required** for the next level.

![image](https://github.com/user-attachments/assets/d4cb8ea4-a407-41be-af64-4750d0dbe24b)

---

## 🎭 **Reworked Showcase Card**
- Now displays **all key stats**:
  - 🏅 **Badges**
  - 🎁 **Rewards**
  - ⭐ **Bonuses**
  - ❌ **Penalties**
  - 🏆 **Achievements**
  - 🏁 **Challenges**

![image](https://github.com/user-attachments/assets/f1ac0c6a-1dc1-4b23-a21a-83d9adabb15b)


---

## 🏅 **Updated Achievement & Challenge Cards**
- Includes **progress tracking**, assigned tasks, and rewards.
- **Supports Daily Minimum Achievements**.

![image](https://github.com/user-attachments/assets/026b6b4c-963a-4d47-abf8-c79097fdadc7)

---

## 📋 **Streamlined Parent Dashboard**
- **Redundant elements removed** to improve clarity.
- Focused on **approvals and overdue resets**.

![image](https://github.com/user-attachments/assets/d24d5cb6-b530-40c3-bc87-c936d6f68836)

---

## ⚙️ **New Configuration Options (`pref_`)**
Easily customize **how chores, rewards, and approvals are displayed** by changing preference settings in the dashboard yaml.

### **Chore Card**
- `pref_column_count` → Adjusts the number of columns.
- `pref_use_today_grouping` → Groups chores by **due morning** & **due today**.
- `pref_use_overdue_grouping` → Groups **overdue chores** separately.
- `pref_exclude_approved` → Excludes **approved** chores from showing.
- `pref_use_label_grouping` → Groups chores by **category**.
- `pref_exclude_label_list` → Allows **excluding specific chore categories**.

### **Reward Card**
- `pref_column_count` → Adjusts the number of columns.
- `pref_use_label_grouping` → Groups rewards by **category**.
- `pref_exclude_label_list` → Allows **excluding specific reward categories**.

### **Approval Card**
- `pref_column_count` → Adjusts the number of columns.

### **Showcase Card**
- `pref_show_penalties` → **Toggles penalty visibility**.

Note that column width may require you to adjust to UI layout settings to show wider

![image](https://github.com/user-attachments/assets/5561d523-a259-434e-ad09-33d030be02f1)

---
## 🔤 Improved Special Character Handling
Uses a **built-in Home Assistant function** for better name normalization across languages.

---

This update makes the **Kids Chore Dashboard** **more customizable and user-friendly**, while keeping it **powerful and engaging**! 🚀😊
