📁 Project: LocalStorage & SessionStorage Practice

🧠 Description:
This project is a simple JavaScript practice exercise that demonstrates how to work with `localStorage` and `sessionStorage` in the browser. It provides a user interface with buttons that allow storing and retrieving data from both storage types, helping users understand how data persists across sessions or tabs.

🚀 Features:
- Store student name in `localStorage` with the key `M4_UD02_P02`
- Store current timestamp in `sessionStorage` with the key `Date`
- Display all saved data from both storages in a dedicated section
- Prevent duplicate insertion into `localStorage`
- Dynamically updates the UI with current storage data

🛠️ Technologies Used:
- HTML5
- CSS3 (linked via `style.css`)
- JavaScript (Vanilla JS)
- Browser APIs: `localStorage`, `sessionStorage`

📦 How to Use:
1. Open the page in a browser.
2. Click the **"INSERIR localStorage"** button to save the name `"ERIC FONSECA"` under the key `M4_UD02_P02` in `localStorage`.
3. Click the **"INSERIR sessionStorage"** button to save the current timestamp in milliseconds under the key `Date` in `sessionStorage`.
4. Click the **"EXIBIR dados"** button to display all stored data from both `localStorage` and `sessionStorage`.

🔧 Notes:
- This is a practice project, useful for beginners to understand browser storage concepts.
- The check for duplicate key in `localStorage` is implemented, but the condition can be refined.
- The data is displayed inside a dynamically created `<p>` element within a `.text` container.

🧪 Future Improvements:
- Improve error handling and data validation
- Enhance UI/UX with visual feedback
- Add options to clear or update stored values
- Support custom key/value input for flexible testin
