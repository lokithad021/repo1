## 🧩 What you’ll do (step-by-step)

1. **Download the Notebook** ⬇️  
   - Click the notebook link/file → **Download** `.ipynb`  
   - Save it to a known spot (e.g., `Downloads/` or `Desktop/`). ✅

2. **Open Google Colab** 🌐  
   - Go to **https://colab.research.google.com** in **Chrome** (or any browser).  
   - Sign in to your Google account. 🔐

3. **Upload the Notebook** 📤  
   - In Colab: **File → Upload notebook → Choose file**  
   - Select the `.ipynb` you just downloaded → **Open**  
   - Wait for Colab to load it. 🌀

4. **Open & Check the Notebook** 👀  
   - Confirm it’s the correct file (title matches, cells are visible).  
   - If it asks for a runtime: click **Connect** (top-right). ⚡

5. **Run it step-by-step** ▶️  
   - Start at the **top cell**. Click the **Play** button on the left.  
   - **Run cells in order**, one by one. Don’t skip. Don’t jump.  
   - Wait for each cell to finish (look for the ✅ check or output).  
   - If a cell needs permissions (e.g., Drive access), click **Allow**. 🔐

---

## 🧠 Don’t Mess Up Checklist 💥
- ☑️ **Do not** run cells out of order  
- ☑️ **Do not** rename/move required files unless the code says so  
- ☑️ **Do not** spam Run All if it says step-by-step  
- ☑️ If you see an error, **Runtime → Restart runtime**, then re-run from the **top**  
- ☑️ If the code needs data files, make sure they’re uploaded or paths are correct  

---

## ⚙️ (Optional) Pro Settings
- **Runtime type**: `Runtime → Change runtime type` → pick **GPU** only if the notebook says it needs one.  
- **Mount Drive**: If the notebook uses files from Drive, run the cell that says:  

  ```python
  from google.colab import drive
  drive.mount('/content/drive')
