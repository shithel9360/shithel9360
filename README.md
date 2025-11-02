# 👋 Hi, I'm @shithel9360

## 🚀 GUI Demo - Python Tkinter

Launch a simple GUI demo to showcase projects visually using Python Tkinter:

### Sample Code

```python
import tkinter as tk
from tkinter import messagebox

class DemoGUI:
    def __init__(self, root):
        self.root = root
        self.root.title("GUI Demo")
        self.root.geometry("400x300")
        
        # Create main frame
        frame = tk.Frame(root, bg="#f0f0f0")
        frame.pack(expand=True, fill="both", padx=20, pady=20)
        
        # Title label
        title = tk.Label(frame, text="Welcome to My Project!", 
                        font=("Arial", 18, "bold"), bg="#f0f0f0")
        title.pack(pady=20)
        
        # Description
        desc = tk.Label(frame, text="Showcasing GUI development skills",
                       font=("Arial", 12), bg="#f0f0f0")
        desc.pack(pady=10)
        
        # Demo button
        btn = tk.Button(frame, text="Click Me!", 
                       command=self.show_message,
                       bg="#4CAF50", fg="white", 
                       font=("Arial", 12), padx=20, pady=10)
        btn.pack(pady=20)
        
    def show_message(self):
        messagebox.showinfo("Demo", "GUI is working perfectly!")

if __name__ == "__main__":
    root = tk.Tk()
    app = DemoGUI(root)
    root.mainloop()
```

### Usage

1. Install Python (3.7 or higher)
2. Tkinter comes pre-installed with Python
3. Save the code as `gui_demo.py`
4. Run: `python gui_demo.py`

### Features

- Clean, modern interface
- Interactive buttons with event handling
- Message dialogs for user feedback
- Easily customizable for your projects

---

💡 **Note:** You can replace this demo with screenshots or GIFs of your actual GUI projects to showcase your work!
