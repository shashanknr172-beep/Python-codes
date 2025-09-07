# Python Features List
PYTHON_FEATURES = [
    "Easy to Learn & Readable",
    "Object-Oriented & Functional",
    "Dynamic Typing",
    "Huge Standard Library",
    "Cross-Platform",
    "Interpreted Language",
    "Extensive Community Support",
    "Supports AI, ML & Data Science",
    "Great for Automation & Scripting",
    "Strong Integration with C/C++/Java"
]

def draw_colored_box(title: str, items: list) -> None:
    """
    Draws a colorful text box with a title and list of items.
    """
    term_width = shutil.get_terminal_size().columns
    box_width = max(len(title), max(len(item) for item in items)) + 6
    box_width = min(box_width, term_width - 4)

    border
