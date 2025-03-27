# Machine_Learning

📘 README: Software Reliability Models on Booking Dataset

#### Steps

### 1. Install Python 3.11.4 and Add to PATH

Windows:

- Download Python 3.11.4 from [python.org](https://www.python.org/)
- During installation, check "Add Python to PATH"
- Verify installation using:
  ```bash
  python --version
  python3 --version
  ```

macOS/Linux:

- Run one of the following:
  ```bash
  brew install python@3.11
  sudo apt update && sudo apt install python3.11
  ```

- Verify installation using:
  ```bash
  python3 --version
  ```

---

### 2. Clone the GitHub Repository

```bash
git clone https://github.com/Lucky122002/Machine_Learning.git
```

---

### 3. Download the Dataset

- Download the `booking.csv` dataset from Repository

### 4. Create a Virtual Environment

Windows:

```bash
python -m venv venv
```

macOS/Linux:

```bash
python3 -m venv venv
```

---

### 5. Activate the Virtual Environment

Windows CMD:

```bash
venv\Scripts\activate
```

Windows PowerShell:

```bash
venv\Scripts\Activate.ps1
```

macOS/Linux:

```bash
source venv/bin/activate
```

---

### 6. Install Dependencies from `requirements.txt`

In terminal, run:

```bash
pip install -r requirements.txt
```

If `requirements.txt` is not present, create it manually with:

```txt
pandas
numpy
matplotlib
seaborn
scikit-learn
```

---

### 7. Run Software Reliability Models

- Launch Jupyter Notebook:
  ```bash
  jupyter notebook
  ```

- Open and run the notebook:
  ```
  Software models.ipynb
  ```

- The notebook applies software reliability models on the booking dataset using visualization and machine learning libraries.
