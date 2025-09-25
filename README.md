# ESTP – Differential Privacy for Official Statistics

This repository contains Jupyter notebooks for the **ESTP course on Differential Privacy**, with a focus on practical tools and hands-on exercises.  
The material introduces how to apply differential privacy using open-source libraries.

---

## ⚙️ Setup Instructions

1. **Clone this repository:**
   ```bash
   git clone https://github.com/<your-username>/ESTP_DP_Course.git
   cd ESTP_DP_Course

2. **Install global dependencies**
    ```bash
   pip install -r requirements.txt

4. **Launch Jupyter:**
Open a notebook and follow the instructions!


---

## 📚 Repo Structure

The repository is organized around four main libraries for differential privacy:

1. **[SmartNoise SQL](https://github.com/opendp/smartnoise-sdk)**
   - Apply differential privacy to SQL queries.
2. **[Diffprivlib](https://github.com/IBM/differential-privacy-library)**
   - IBM’s library for differentially private machine learning and statistics.
3. **[SmartNoise Synth](https://github.com/opendp/smartnoise-sdk)**
   - Tools for generating differentially private synthetic data.
4. **[OpenDP](https://opendp.org/)**
   - The OpenDP project’s core library for building custom DP transformations and working with polars tables.

For each library, you will find:
- **Exercise notebook** – practical problems to solve.
- **Correction notebook** – worked-out solutions.


## 📂 Repository Layout
```
ESTP_DP_Course/
│
├── smartnoise-sql/
│   ├── Smartnoise-SQL-Exercises.ipynb
│   └── Smartnoise-SQL-Corrections.ipynb
│
├── diffprivlib/
│   ├── DiffPrivLib-Exercises.ipynb
│   └── DiffPrivLib-Corrections.ipynb
│
├── smartnoise-synth/
│   ├── exercises.ipynb
│   └── corrections.ipynb
│
├── opendp/
│   ├── exercises.ipynb
│   └── corrections.ipynb
│
└── README.md
```


---


## 📝 Notes

- **Exercises** are designed for practice during the course.  
- **Corrections** provide detailed solutions — use them for self-study or after attempting the exercises.  
- Make sure you install the correct version of each library.  

---

## 📖 References

- [OpenDP Project](https://opendp.org/)  
- [SmartNoise Documentation](https://docs.smartnoise.org/)  
- [IBM Diffprivlib](https://github.com/IBM/differential-privacy-library)  
- [Differential Privacy Overview (Wikipedia)](https://en.wikipedia.org/wiki/Differential_privacy)  

---

Happy learning! 🚀
