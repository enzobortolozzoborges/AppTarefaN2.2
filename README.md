# AppTarefas08

A simple **legacy-style Android app** created for study purposes.  
This project demonstrates a full CRUD (Create, Read, Update, Delete) workflow using **Java** and **SQLite** inside Android Studio.

---

## ✨ Features
- Add new tasks with title and description  
- View a list of saved tasks  
- Edit existing tasks  
- Delete tasks with long-press confirmation dialog  
- Local data persistence with SQLite

---

## 🛠️ Tech Stack
- **Language:** Java  
- **Database:** SQLite (via `SQLiteOpenHelper`)  
- **Architecture:** Simple MVC (Activities + DAO + Adapter)  
- **IDE:** Android Studio  
- **Min SDK:** 21 (Android 5.0 Lollipop)  

---

## 📱 Screens
- **MainActivity:** Shows all tasks in a `ListView` and provides a button to create a new task.  
- **FormActivity:** Form to insert or update a task.  

---

## 🏗️ Project Structure

<pre> app/
└─ src/
   └─ main/
      ├─ java/
      │  └─ br/equipe08/
      │     ├─ model/
      │     │  └─ Tarefa.java          # Data class
      │     ├─ db/
      │     │  └─ TarefaDAO.java       # SQLite helper
      │     ├─ adapter/
      │     │  └─ TarefaAdapter.java   # ListView adapter
      │     └─ ui/
      │        ├─ MainActivity.java
      │        └─ FormActivity.java
      └─ res/
         ├─ layout/
         │  ├─ activity_main.xml
         │  ├─ activity_form.xml
         │  └─ item_tarefa.xml
         └─ values/
            ├─ strings.xml
            ├─ colors.xml
            └─ themes.xml)</pre>


---

## ⚙️ How to Build
1. **Clone the repository**
   ```bash
   git clone https://github.com/enzobortolozzoborges/AppTarefaN2.2.git

Open in Android Studio
File → Open… and select the AppTarefas08 folder.

Build & Run
Choose an emulator or a physical Android device and click Run.

