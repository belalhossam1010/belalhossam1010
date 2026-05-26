<!-- GitHub Profile README -->

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Hey%2C+I'm+Belal.+%F0%9F%91%8B;Computer+%26+AI+Engineering+Student;Building+things+that+work+%F0%9F%9A%80" alt="Typing SVG" />
</div>

<br/>

<div align="center">
  
  ![Cairo](https://img.shields.io/badge/📍_Cairo-Egypt-red?style=flat-square&labelColor=161b22&color=f78166)
  ![Dual Degree](https://img.shields.io/badge/🎓_Dual_Degree-Ain_Shams_×_UEL-blue?style=flat-square&labelColor=161b22&color=58a6ff)
  ![Field](https://img.shields.io/badge/🤖_CS_&_AI-Engineering-purple?style=flat-square&labelColor=161b22&color=d2a8ff)

</div>

---

## `whoami`

```bash
$ cat profile.json
{
  "name":     "Belal Hossam",
  "location": "Maadi, Cairo 🇪🇬",
  "degree":   "Computer & AI Engineering (Dual Degree)",
  "unis":     ["Ain Shams University (ICHEP)", "University of East London"],
  "focus":    ["Software Development", "Robotics", "AI Systems"],
  "status":   "Actively building cool stuff ⚡"
}
```

> *"Technology isn't just a field of study — it's a lifelong pursuit of understanding the **'how'** behind the next big innovation. I don't wait for opportunities; I pursue them. Learning something entirely new is the best way to sharpen perspective."*

---

## 🛠️ Tech Stack

<div align="center">

![Java](https://img.shields.io/badge/Java-f78166?style=for-the-badge&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-ffa657?style=for-the-badge&logo=cplusplus&logoColor=white)
![JavaFX](https://img.shields.io/badge/JavaFX-58a6ff?style=for-the-badge&logo=java&logoColor=white)
![Git](https://img.shields.io/badge/Git-3fb950?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-8b949e?style=for-the-badge&logo=github&logoColor=white)

</div>

> 📜 **Certified:** Git & GitHub Professional Certification — *Al Madrasa*

---

## 🚀 Projects

### 🏨 Hotel Reservation System
> `Java` `JavaFX` `OOP` `Git` — *CSE241 Object-Oriented Programming · Ain Shams University*

A full-featured desktop hotel management application built in Java with a JavaFX GUI, applying core OOP principles — encapsulation, inheritance, polymorphism, and abstraction. The system supports three user roles (Guest, Receptionist, Admin) each with dedicated dashboards, and persists all data across sessions via Java Serialisation.

**My contribution — Guest Booking Page & Filter System:**
- Built the room browsing and filtering screen where guests search and book available rooms in real time
- Integrated filter controls (room type, view preference — Garden/Sea/City, max price slider) that query `BookingEngine.getAvailableRooms()` dynamically based on selected dates
- Wired JavaFX `DatePicker` controls for check-in/check-out selection alongside guest count inputs and optional `DiningPackage` selection
- Connected the UI to the `RoomCard.fxml` reusable component, rendering each result with room number, floor, type, price, and amenities
- Served as the entry point into the full checkout and invoice flow, requiring deep understanding of the `Reservation`, `RoomType`, and `BookingEngine` backend classes

> 🔗 [GitHub Repository](https://github.com/OmarFaroukCode/Hotel_Reservation_System) · [YouTube Demo](https://youtu.be/-Paa0m97CQ0)

---

### 💊 Smart Pharmacy Management System
> `C++` `Structs` `File I/O` — *Introduction to Computer Programming · Ain Shams University · Team JAMBOY*

A console-based pharmacy management system built in C++ with persistent file storage, dual-role authentication, real-time billing, and proactive inventory monitoring. The system handles both manager and pharmacist workflows end-to-end.

**My contribution — Full Manager Portal (from login to logout):**
- `mainmenu()` — the application's entry point, routing every user into either the manager or pharmacist flow
- `managerlogin()` — secure admin authentication with new account registration support and a 3-attempt lockout that redirects to the main menu on failure
- `managermenu()` — the administrative control panel consolidating all manager operations into a single navigation switchboard
- `lowstockalert()` — proactive monitoring tool that fires automatically on every manager login, scanning the entire inventory and triggering a visual warning for any medicine below 5 units
- `lowstock()` — detailed companion report listing every understocked item with exact remaining quantities for precise restocking decisions
- `logout()` — clean session termination back to the main menu
> 🔗 [GitHub Repository](https://github.com/belalhossam1010/smart_pharmacy_system) 
---

### 🤖 Autonomous Micromouse Maze-Solver
> `Robotics` `AI` `C++` — *Luban Workshop, Ain Shams University*

Built an autonomous robot capable of navigating and solving mazes — pathfinding that works in the physical world, not just on paper.

---

### 🥇 "The Unsolved Mysteries of the Sea" — *1st Place*
> Presentation Competition · June 2025

Won first place in a university presentation competition

---

## ⚡ Beyond the Code

```
🎮 Gaming
   ├── Genres:  Action-Adventure · Sports
   └── Favs:   God of War · Ghost of Tsushima · FC (FIFA) series
```

---

## 🎓 Education

| Institution | Program |
|---|---|
| **Ain Shams University (ICHEP)** | Computer & AI Engineering — Dual Degree |
| **University of East London** | Computer & AI Engineering — Dual Degree |

---
name: Generate Snake on: schedule: [{cron: "0 0 * * *"}] workflow_dispatch: jobs: snake: runs-on: ubuntu-latest steps: - uses: Platane/snk@v3 with: github_user_name: YOUR_USERNAME outputs: | dist/github-contribution-grid-snake.svg dist/github-contribution-grid-snake-dark.svg?palette=github-dark - uses: crazy-max/ghaction-github-pages@v3 with: target_branch: output build_dir: dist env: GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

---

<div align="center">
  <sub>Built from Cairo with ☕ and way too many open tabs</sub>
</div>
