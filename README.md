# Ask Your Syllabus — Jupyter Notebook Demo

Files:
- `Ask_Your_Syllabus_RAG.ipynb`: step-by-step notebook
- `syllabus.txt`: fictional source document

1. Install Python, Ollama, and Jupyter (or the Jupyter extension in VS Code).
2. Run `ollama pull all-minilm` and `ollama pull gemma3:1b` in your terminal.
3. Start Ollama if not already running.
4. Open the notebook in VS Code or Jupyter, select the Python kernel, and run one cell at a time.
5. The first notebook cell installs the two required Python packages into its kernel. If prompted, restart the kernel, then continue.
6. Keep the notebook and `syllabus.txt` in the same directory. If needed, use the notebook's working folder as this directory.

Everything in the syllabus is **fictional**, not a real university policy. Initial model downloads require internet. The notebook requires enough RAM to run the local models and may be slow on older computers.

Workshop tip: First run the closed-book cell before opening syllabus.txt. Later compare it to the RAG answer for the identical question, "When is Homework 3 due?"
