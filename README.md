## CalcSuite

A stunning, modern master dashboard for 46 free online calculators — financial, health & fitness, math, and fitness — with live search, category filters, and a polished dark/light theme. Built with HTML5, Tailwind CSS (CDN), and vanilla JavaScript.
---

✨ Features

· 🔍 Live search — Instantly filter calculators as you type. Matches titles, descriptions, categories, and hidden keywords (e.g., mortgage, bmi, loan, tdee).
· 🗂️ Category tabs — Filter by All, Financial, Health & Fitness, Math, and Fitness with a single click.
· 🌗 Dark / light theme — Smooth toggle that respects your OS preference and remembers your choice via localStorage.
· ⚡ Zero build step — Tailwind via CDN, no bundlers, no dependencies. Just open index.html.
· 📱 Mobile-first responsive — 1-column stack on mobile, 2 on tablet, 3–4 on desktop.
· 🎨 Premium UI/UX — Soft glowing hover effects, staggered card entrances, subtle scrollbar, and accessible focus states.
· ⌨️ Keyboard shortcuts — Press / anywhere to focus search; Esc to clear and blur.
· 🧩 Scalable architecture — Add a new calculator by appending one object to the CALCULATORS array.

---

🚀 Quick Start

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/CalcSuite.git

# 2. Navigate into the project
cd CalcSuite

# 3. Open the dashboard
# Simply double-click index.html, or use a live server:
npx serve .
# or
python -m http.server 8000
```

Then visit http://localhost:8000 (or just open index.html in your browser).

No npm install, no compilation. The dashboard runs entirely in the browser.


🧮 Calculator Directory

💰 Financial (16)

# Calculator Path
1 Mortgage financial/mortgage.html
2 Loan financial/loan.html
3 Auto Loan financial/auto-loan.html
4 Interest financial/interest.html
5 Payment financial/payment.html
6 Amortization financial/amortization.html
7 Investment financial/investment.html
8 Compound Interest financial/compound-interest.html
9 Retirement financial/retirement.html
10 Inflation financial/inflation.html
11 Salary financial/salary.html
12 Income Tax financial/income-tax.html
13 Credit Card Payoff financial/credit-card.html
14 Sales Tax financial/sales-tax.html
15 Currency Converter financial/currency.html
16 401(k) financial/401k.html

🏃 Health & Fitness (11)

# Calculator Path
1 BMI health/bmi.html
2 BMR health/bmr.html
3 Calorie health/calorie.html
4 Body Fat health/body-fat.html
5 Ideal Weight health/ideal-weight.html
6 Pregnancy health/pregnancy.html
7 Due Date health/due-date.html
8 Ovulation health/ovulation.html
9 Water Intake health/water-intake.html
10 Macro health/macro.html
11 Sleep health/sleep.html

📐 Math (10)

# Calculator Path
1 Scientific math/scientific.html
2 Percentage math/percentage.html
3 Fraction math/fraction.html
4 Average math/average.html
5 Standard Deviation math/standard-deviation.html
6 Triangle math/triangle.html
7 Quadratic Formula math/quadratic.html
8 Matrix math/matrix.html
9 Random Number math/random-number.html
10 Slope math/slope.html

🏋️ Fitness (9)

# Calculator Path
1 One Rep Max fitness/one-rep-max.html
2 TDEE fitness/tdee.html
3 Protein fitness/protein.html
4 Lean Body Mass fitness/lean-body-mass.html
5 Target Heart Rate fitness/heart-rate.html
6 Calories Burned fitness/calories-burned.html
7 Pace fitness/pace.html
8 Body Type fitness/body-type.html
9 Army Body Fat fitness/army-body-fat.html

---

🎨 Theming & Customization

The dashboard uses Tailwind CSS’s dark mode (class strategy). The dark class is toggled on the <html> element.


```js
{
  title: 'My New Calculator',
  desc: 'A short, one-line description of what it does.',
  category: 'Math',           // 'Financial' | 'Health & Fitness' | 'Math' | 'Fitness'
  icon: 'calculator',         // key from the ICONS map
  path: 'math/my-new.html',
  keywords: 'extra search terms'
}
```
---

🛠️ Tech Stack

Layer Technology
Markup HTML5 (semantic, accessible)
Styling Tailwind CSS 3 (CDN) + small custom CSS for animations
Behavior Vanilla JavaScript (ES6, IIFE-scoped)
Font Inter via Google Fonts
Icons Inline SVG (Feather-style, zero dependencies)
Persistence localStorage for theme preference

No frameworks, no build tools, no node_modules — intentionally lightweight.

---

---

📄 License

This project is licensed under the MIT License — you are free to use, modify, and distribute it, including commercially. See the LICENSE file for details.

---

🙏 Acknowledgements

· Inspired by the clean, ad-light experience of Calculator.net.
· Design language influenced by Vercel and Stripe dashboards.
· Icons crafted in the style of Feather Icons.
· Built with ❤️ for people who just want a fast answer.

---

<p align="center">
  <sub>Made with 🧠 and ☕ — <strong>CalcSuite</strong></sub><br/>
  <a href="https://github.com/yourusername/CalcSuite">⭐ Star the repo</a> ·
  <a href="https://github.com/yourusername/CalcSuite/issues">🐛 Report a bug</a> ·
  <a href="https://github.com/yourusername/CalcSuite/issues">💡 Request a calculator</a>
</p>
```
