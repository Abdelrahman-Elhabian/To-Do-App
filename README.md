
## 💡 How It Works

- Users input a task in the text field and click **"Add Task"**.
- Tasks are stored in an array and saved to `localStorage`.
- Tasks are displayed dynamically in the `.tasks` container.
- Clicking a task toggles its "done" status.
- Each task has a "Delete" button to remove it individually.
- A "Delete All" button appears when there are tasks, clearing everything at once.

## 🛠️ Technologies Used

- **HTML5**
- **CSS3** (Inline styles within the HTML)
- **Vanilla JavaScript**
- **Local Storage** for persistent task management

## 📷 Preview

![screenshot-placeholder](https://via.placeholder.com/500x300?text=To-Do+App+Screenshot)

## 📌 Usage

1. Clone or download the repository.
2. Open `index14.html` in a web browser.
3. Start managing your tasks!

## 📄 License

This project is open-source and free to use.
"""

file_path = "/mnt/data/README.md"
with open(file_path, "w") as f:
    f.write(readme_content)

file_path
