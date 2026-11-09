# 🚗 VehicleUserManagementSuite (C++)

A capable C++ console app that manages users, vehicles, and a manager profile with plain-text storage and a clean CLI. ✨

## ✨ Features

- 👤 **Users:** Add and list users (name, national code, password).
- 🚘 **Vehicles:** Add and list vehicles (code, brand, model, capacity).
- 🔗 **Assign:** Link vehicles to users.
- 🧑‍💼 **Manager:** Save manager information.
- 💾 **Persistence:** Store data in `users.txt`, `vehicles.txt`, and `manager.txt`.
- 📊 **Tables:** Neat fixed-width output using `iomanip`.

## ▶️ Quick Start

**Build**

```bash
# If headers are in folders 'models' & 'utils'
g++ -std=c++17 main.cpp -Imodels -Iutils -o license-center

# OR if includes were changed to root paths
# g++ -std=c++17 main.cpp -o license-center
```

**Run**

```bash
./license-center

# Windows
.\license-center.exe
```
