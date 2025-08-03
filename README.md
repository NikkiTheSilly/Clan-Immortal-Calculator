# 🧮 Clan Immortal Level Calculator

This is a web-based calculator to determine the maximum **Immortal levels** your clan can reach in *Tap Titans 2*, based on each member’s level and class (Physical, Arcane, Holy, or None).

You can try the app here:  
🔗 [https://mesa-bot.github.io/clan-calc/](https://mesa-bot.github.io/clan-calc/)

---

## 📦 Features

- Input up to 10 clan members' **level** and **class**
- Calculates **DPC (damage per click)** values by class type
- Outputs the 3 most powerful **Immortal levels** your clan can reach per weakness type
- Shows **CPS** (clicks per second) and raw clicking equivalents
- Responsive, clean interface – no external styling frameworks required

---

## 🧪 Usage

1. Enter each player's **level** (1+)
2. Select their class:
   - `P` for Holy
   - `M` for Arcane
   - `R` for Physical
   - `N` for None
3. Press **"Calculate"** to view results

---

## 🧾 Patch Notes

1.0.0 - Release

1.0.1

Fixed typo in instructions.
Changed "may" to "must" regarding entering member classes, 
as a lazy fix for an error that occurred when entering a 
clan member without a class.

Fixed formatting inconsistency in output

1.0.2

Reverted lazy fix from 1.0.1

Properly fixed issue allowing members to be entered without classes.

1.0.3

Corrected immortal health function for levels less than 7 - 
curse the wiki feeding me misinformation!

Calculator made into a proper webpage by Huang Bao.

---

## 🙏 Credits

Calculator originally created by **Nikki** 
Please report any errors or bugs to them on Discord:  
`@supermariooddity`

Converted into a usable webpage by **Huang Bao**

---

## 🚀 Development

This app was rebuilt using **React + TypeScript**, with clean vanilla styling and GitHub Pages deployment.

To run locally:

```bash
npm install
npm start
