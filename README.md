# Google Pay Group Expenses Dashboard 💸

A lightweight, purely client-side web application designed to parse your Google Pay group expenses and generate clean, shareable monthly breakdowns. 

Since financial data is highly sensitive, this tool is built to run **100% locally in your browser**. Your data is never uploaded to a server, saved, or tracked.

## ✨ Features

* **Privacy First:** No backend, no databases, no server-side processing. Everything happens in your browser's memory.
* **Monthly Breakdowns:** Automatically sorts and aggregates group spending by month and individual member.
* **Mobile-Optimized:** Responsive tables with sticky headers and scrollable views.
* **Export & Share:** Generates high-quality images of your expense tables using `html2canvas` for easy sharing to WhatsApp, X, or LinkedIn.
* **Dark/Light Mode:** Automatically syncs with your system preferences or toggles manually.

## 🛠️ How to Get Your Data (Google Takeout)

To use this dashboard, you need your raw transaction data from Google Pay. 

1. Go to [Google Takeout](https://takeout.google.com/).
2. Click **Deselect all** at the top.
3. Scroll down and check the box next to **Google Pay**.
4. Scroll to the bottom and click **Next step**, then **Create export**.
5. Once your export is ready, download and extract the ZIP file.
6. Navigate to the extracted folder and locate `Group expenses.json`. This is the file you will upload to the dashboard.

## 🚀 Usage

You can use the live version hosted via GitHub Pages here:
**[Link to your GitHub Pages URL]** *(e.g., https://avinash-cs.github.io/gpay-group-expenses-dashboard/)*

Simply click "Select JSON File", choose your `Group expenses.json`, and your dashboards will instantly generate.

## 💻 Local Development

Because this is a static single-page application, no build tools are required. 

1. Clone the repository:
   ```bash
   git clone [https://github.com/avinash-cs/gpay-group-expenses-dashboard.git](https://github.com/avinash-cs/gpay-group-expenses-dashboard.git)
