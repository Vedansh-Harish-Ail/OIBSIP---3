---

# **Task Manager — A Simple and Clean To-Do App**

A lightweight task manager built using HTML, CSS and plain JavaScript. It saves tasks automatically in your browser, lets you edit, delete, mark them as complete and keeps everything organized with a clean interface.

---

## **Features**

* Add, edit and delete tasks
* Mark tasks as completed or pending
* Auto-save using `localStorage`
* Clean responsive UI
* Toast notifications for quick feedback
* No frameworks required

---

## **Live Preview**

Open the file in your browser:

```
index.html
```

or start a quick local server:

```
python -m http.server 8000
```

---

## **Project Structure**

```
my-task-manager/
│
├── index.html
├── README.md
└── assets/
    └── banner.png   (optional)
```

---

## **How It Works**

### Task Storage

All tasks are saved in your browser using:

```
localStorage
```

No backend needed. Tasks remain available even after refreshing or closing the tab.

### Task Actions

* **Add** a new task
* **Edit** an existing task inline
* **Delete** with confirmation
* **Complete** any task using the checkbox
* Move tasks automatically between Pending and Completed sections

---

## **Customization**

You can edit text labels, colors or the header inside the file:

* Page title
* Subtitle
* Theme colors (`--primary`, `--secondary`, `--danger`)
* Max tasks limit
* Toast colors

All styling is managed in the `<style>` tag at the top of the file.

---

## **Tech Stack**

| Part         | Used                  |
| ------------ | --------------------- |
| Languages    | HTML, CSS, JavaScript |
| Storage      | localStorage          |
| UI           | Custom CSS            |
| Dependencies | None                  |

---

## **Why This Project**

This app is designed to be simple, readable and useful for beginners and students who want to practice:

* DOM manipulation
* Local storage
* Dynamic UI updates
* Clean component-like JS functions

---

## **Future Enhancements**

* Dark mode
* Drag and drop sorting
* Task categories
* Due dates and reminders
* Export/Import tasks

---

## **License**

MIT License

---

