# 🎉 **Biggest KidsChores Dashboard Update Yet!** 🚀  

The latest **KidsChores Dashboard (KCD_0.3.4)** is here, bringing **major enhancements** that make managing chores more **powerful, customizable, and engaging** than ever!  

This release **leverages many of the powerful new features in the newly released [KidsChores Integration 0.3.0](https://github.com/ad-ha/kidschores-ha).** The latest integration update is **packed with improvements and new capabilities**, so be sure to check it out!  A huge shout-out to **@ad-ha** for all the hard work he's been putting into the integration! 🙌

📖 We've worked to **significantly enhance the [integration's README](https://github.com/ad-ha/kidschores-ha) and [Wiki](https://github.com/ad-ha/kidschores-ha/wiki)**, now providing **more in-depth details** on how it works, along with expanded **FAQs, Best Practices, Tips & Tricks, and Troubleshooting Guides** to help you maximize everything KidsChores has to offer.  

---

## 🚀 **What's New in KCD_0.3.4?**  

✅ **Multi-Language Support** – Now available in **5 languages**! 🌍  
✅ **Chore & Reward Labels** – Group or exclude tasks effortlessly.  
✅ **Bonus System Integration** – Easily track & apply bonuses.  
✅ **🏅 New Badge Cards** – Displays **earned and upcoming badges** with progress tracking.  
✅ **Reworked Showcase** – All key stats in one place!  
✅ **Parent Dashboard Enhancements** – Cleaner, more intuitive.  
✅ **Column Width Controls** – Adjust layouts for any screen.  
✅ **New Customization Options** – More flexibility in chore displays.  
✅ **Better Special Character Handling** – Improved name support across languages.  

📖 **Check out the full release details below!**  

<a href="https://www.buymeacoffee.com/shillingcll" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>
---

## 🌍 Multi-Lingual Support
Now available in **English, Danish, Dutch, Finnish, and German**. A huge thank you to:
- **Danish**: @dehoej 🇩🇰  
- **Dutch**: @WilbertVerhoeff 🇳🇱  
- **Finnish**: @mikkomakipaa 🇫🇮  
- **German**: @kolossboss 🇩🇪  

A special shout-out to **@kolossboss**, who originally submitted a translated version of the dashboard. While reviewing it, I realized that for long-term support of multiple languages, the dashboard needed a complete rework. **@kolossboss** assisted in testing the first version, and thanks to this effort, it's now possible to quickly add new languages for anyone interested in contributing a translation! ✨

![image](https://github.com/user-attachments/assets/db4467a8-05a6-4db5-8028-93448be9fe1a)

---

## 📌 **Chore & Reward Labels**
- Chores and rewards can now be **grouped** or **excluded** by label.  This is using a new feature in the **[KidsChores Integration 0.3.0](https://github.com/ad-ha/kidschores-ha)**

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

## 🖥️ **Easily Adjust Column Width for Chores, Rewards, and Approvals**  

The column layout for **chores, rewards, and approvals** can now be adjusted in the **preferences**, allowing for a **customizable display**. Whether you're using a **phone, tablet, or larger screen**, you can configure it to show **a single column for compact views** or **multiple columns for a broader layout**.  Thank you @knotquiteawake for the suggestions.

📌 **Note:** Column width settings may require adjustments to **UI layout settings** to ensure proper display on wider screens.  

![image](https://github.com/user-attachments/assets/d0449400-207d-4b4d-8cf1-f9f76c6aa9b8)

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

![image](https://github.com/user-attachments/assets/5561d523-a259-434e-ad09-33d030be02f1)

---
## 🔤 Improved Special Character Handling
Found a **built-in Home Assistant function** that could be used for better name normalization across languages rather than the prior regex replacements approach I was trying to use.

---

This update makes the **Kids Chore Dashboard** **more customizable and user-friendly**, while keeping it **powerful and engaging**! 🚀😊

<a href="https://www.buymeacoffee.com/shillingcll" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>

