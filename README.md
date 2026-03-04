# Better Portfolio – RugPlay Enhancement Script Fully ai made so its bad

**Better Portfolio** is a user script designed to supercharge your RugPlay trading and portfolio experience!

## Features

### 1. Lightning-Fast Portfolio Loading
- **No More Long Waits:** Portfolio pages with over 10,000 coins used to take 10+ seconds to load. Now, the script intercepts the portfolio request and sends RugPlay an empty coin list for immediate rendering.
- **Dynamic HTML Table:** Internally, the script rebuilds the portfolio display, loading items dynamically—**without icons** to avoid rate-limiting.
- **Efficient Data Handling:** Experience seamless browsing, regardless of how many coins you hold.
- **Fast sorting and searching** Its so fast it blueshifts

### 2. Streamlined Coin Transfer Modal
- **Effortless Search:** Improved coin searching, making it easier and faster to find what you want.
- **Toggle Value/Coins:** Now you can send coins by specifying the *value* you wish to transfer (e.g., send "5000 worth of *clippy*"), instead of counting raw coins.

### 3. General Usability Improvements
- **AI-Powered Enhancements:** The script leverages AI logic for smarter, contextual interactions—even if the underlying JS is a "hot mess".
- **Page Detection:** Attempts to auto-detect RugPlay pages for script activation (may need improvement).

## Known Issues

- **Page Detection:** Current detection can be spotty—sometimes fails to activate reliably.
- **Icons:** Disabled on portfolio to prevent rate-limiting issues. Coins appear without icons.
- **Code Quality:** Mainly AI-generated JavaScript, so structure and clarity may not be perfect. Contributions welcome!

## Install & Use

- Download or copy the latest [Better-portfolio](https://raw.githubusercontent.com/dingdong627/script/refs/heads/main/Better-portfolio) script.
- Follow the instructions for your userscript manager (e.g., Tampermonkey, Greasemonkey) to install.

## Screenshots

![Trade Modal Demo](image2)
![Portfolio Table Demo](image1)

(*Images show trade modal input sync and dynamic portfolio table*)

---

**Feedback or improvements?** Open a GitHub issue or submit a PR!  
*Script originally created by Dingdong & AI.*
