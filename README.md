# 📊 Data Science Project 1 – BLS Coders

Welcome to the first project in our Data Science learning journey! This repository is part of the **BLS Coders** series, and it focuses on building a strong foundation in **environment setup** using the Conda ecosystem, including tools like **Anaconda**, **Jupyter Notebook**, and **JupyterLab**.

---

## 🚀 Project Objective

This project helps you understand and configure a reproducible Python environment for data science tasks. It covers:

* Installing and configuring **Anaconda** or **Miniconda**
* Managing **conda environments**
* Installing essential data science packages
* Using **JupyterLab** as your primary development interface

---

## 🛠️ Tools & Technologies

* **Python (via Anaconda/Miniconda)**
* **Conda** (Package & Environment Manager)
* **Jupyter Notebook / JupyterLab**
* **Anaconda Navigator**

---

## 📦 Key Concepts Covered

### ✅ Installing Anaconda

* Step-by-step guide for Windows, macOS, and Linux
* Verifying installation via `conda --version`

### 🔄 Anaconda vs Miniconda

* **Anaconda**: Full-featured, beginner-friendly
* **Miniconda**: Lightweight, flexible for custom setups

### 🧪 Conda Workflow

* Creating and managing virtual environments
* Installing packages from channels like `conda-forge`
* Best practices: Always activate before install!

### 📁 Using Anaconda Navigator

* GUI for launching tools like JupyterLab
* Ideal for beginners avoiding command line

### 📓 Jupyter Notebook vs JupyterLab

| Feature       | Jupyter Notebook | JupyterLab      |
| ------------- | ---------------- | --------------- |
| Interface     | Single document  | Multi-tab/panel |
| Customization | Limited          | Extensive       |
| Use Case      | Tutorials/Quick  | Full workflows  |

---

## 📂 Folder Structure

```
├── environment/
│   └── conda_setup.md         # Environment setup instructions
├── notebooks/
│   └── sample_notebook.ipynb  # JupyterLab starter notebook
├── data/                      # (Optional) Raw or sample data files
├── README.md
```

---

## 📝 How to Use This Repo

1. **Clone the repo**

   ```bash
   git clone https://github.com/Krushna-Chandra/Data-science-project-1-BLS-Coders-.git
   cd Data-science-project-1-BLS-Coders-
   ```

2. **Install Anaconda or Miniconda**
   Follow the steps in `environment/conda_setup.md` or the main notebook.

3. **Create and activate a new environment**

   ```bash
   conda create -n ds_env python=3.11
   conda activate ds_env
   ```

4. **Install essential packages**

   ```bash
   conda install -c conda-forge numpy pandas jupyterlab
   ```

5. **Launch JupyterLab**

   ```bash
   jupyter lab
   ```

---

## 📚 Learning Outcome

By completing this setup and project, you will:

* Understand how to isolate Python environments using Conda
* Confidently install and manage libraries using conda-forge
* Use JupyterLab for interactive data science workflows
* Be ready to begin your first **real-world data analysis** project!

---

## 🙌 Contributing

Pull requests are welcome. If you find a typo or want to add improvements, feel free to contribute.

---

## 🧑‍💻 Author

**Krushna Chandra Bindhani**
B.Tech (CSE), Final Year | Aspiring Data Scientist
[GitHub](https://github.com/Krushna-Chandra) | [LinkedIn](https://linkedin.com/in/krushnachandrabindhani)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
