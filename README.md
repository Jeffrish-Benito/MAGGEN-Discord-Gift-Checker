# MAGGEN ⚡

**Lightning-fast Discord Gift Code Checker (Node.js)**

MAGGEN is a high-performance CLI tool built with **Node.js** for
bulk-checking Discord gift codes.\
It provides a clean animated interface, validates codes safely using
Discord's public API, and automatically sorts results.

------------------------------------------------------------------------

## 🚀 Features

-   ⚡ Extremely fast bulk checking
-   🎨 Gradient ASCII banner (**MAGGEN**)
-   ⏳ Animated loading dots
-   📊 Live progress counter
-   📂 Automatic sorting:
    -   `valid.txt`
    -   `invalid.txt`
-   🧠 Safe & read-only (no token, no login)
-   🛡️ Low memory usage
-   💻 Works on Windows, Linux, macOS, VPS, Termux

------------------------------------------------------------------------

## 📁 Project Structure

    maggen/
    ├── checkGifts.js
    ├── gifts.txt
    ├── results/
    │   ├── valid.txt
    │   └── invalid.txt
    ├── package.json
    ├── README.md
    └── LICENSE

------------------------------------------------------------------------

## 📦 Requirements

-   **Node.js v18 or higher**
-   Internet connection

Check your Node version:

``` bash
node -v
```

------------------------------------------------------------------------

## 📥 Installation

``` bash
npm install
```

------------------------------------------------------------------------

## 🧠 How to Use

### 1️⃣ Add gift codes

Open `gifts.txt` and add **one gift code per line**:

``` txt
AbCdEfGh12345678
XyZ987654321AbC
NitroGiftCodeHere
```

❗ **IMPORTANT** - Do **NOT** include full links\
- One code per line

------------------------------------------------------------------------

### 2️⃣ Run MAGGEN

``` bash
node checkGifts.js
```

or

``` bash
npm start
```

------------------------------------------------------------------------

### 3️⃣ View results

Results are saved automatically:

-   `output/valid.txt`
-   `output/invalid.txt`

------------------------------------------------------------------------

## 📊 Output Behavior

  Status    Meaning
  --------- ------------------------------
  VALID     Gift exists and is unclaimed
  INVALID   Expired, claimed, or invalid

------------------------------------------------------------------------

## ⚠️ Important Notes

-   No Discord token or login required
-   Randomly generated codes are almost always invalid
-   Do not abuse API limits

------------------------------------------------------------------------

## 📜 License

MIT License

------------------------------------------------------------------------

## ⭐ Disclaimer

MAGGEN is provided for educational and automation purposes only.
