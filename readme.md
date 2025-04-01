Great, Jen! Since you've finished the project and are ready to update your `README.md` to reflect your completed Vehicle Drive project, here’s a clean, professional, and complete version you can use as a final README:

---

## 🚗 Vehicle Drive CLI App

A TypeScript-powered command-line application that allows users to create and interact with different types of vehicles — including **cars**, **trucks**, and **motorbikes**. The app uses object-oriented programming principles and prompts the user to create or select a vehicle, then perform various actions depending on the type.

---

### 🎥 Walkthrough Video  
👉 [Click here to watch the walkthrough video](#)  
(*Replace `#` with your actual video URL*)

---

### 📜 User Story

```
AS a developer
I WANT to update an existing application to include additional vehicle types
SO THAT I am able to comprehend and work with existing code bases.
```

---

### ✅ Features

- 🔧 Choose to **create a new vehicle** or **select an existing one**
- 🚘 Choose between **car**, **truck**, or **motorbike**
- ✍️ Enter vehicle-specific information during creation
- 🛠 Perform vehicle-specific actions after creation
- 🔄 Return to the main action menu after each interaction
- ❌ Exit when finished

---

### 💻 Tech Stack

- **TypeScript**
- **Node.js**
- **Inquirer** for user prompts
- **Object-Oriented Programming** (OOP)

---

### 🛠 How to Use

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/vehicle-drive.git
   cd vehicle-drive
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the app:
   ```bash
   npm start
   ```

---

### 📂 Project Structure

```
├── src/
│   ├── classes/
│   │   ├── Vehicle.ts
│   │   ├── Car.ts
│   │   ├── Truck.ts
│   │   └── Motorbike.ts
│   └── index.ts
├── package.json
├── tsconfig.json
└── README.md
```

---

### 🚚 Special Functionality

- **Truck**: Prompts for cargo capacity and can perform load/unload actions unique to trucks.
- **Motorbike**: Prompts for helmet requirement and has its own handling behavior.
- **Car**: Standard vehicle interactions.

---

### 📦 Dependencies

- [Inquirer](https://www.npmjs.com/package/inquirer)
- [TypeScript](https://www.typescriptlang.org/)

---

### 📣 Credits

Created by Jen @JT-code-dev, for educational and portfolio use.

---
