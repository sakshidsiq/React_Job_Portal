

**React Job Portal 🚀**
A modern job portal built with React, featuring dynamic job search, filterable listings, and intuitive navigation. Ideal as a learning project or showcase app.

**🎯 Features**
Job search & filtering by title, location, full-time options

**Dynamic listings**: browse through job opportunities with logo and company details

**Job details page**: click a listing to view full description, application instructions, and company info

Load-more pagination for exploring additional listings

Loading states & clean UI with overlays during fetch operations

Lazy-loaded images for improved performance, especially on slower connections

Context API to manage state and avoid prop drilling

**🛠 Tech Stack**
Layer	Technologies
**Front‑end**:	React, Context API, Hooks
**Styling**:	Tailwind CSS / Styled-components (select based on your repo)
Fetching	Axios
**Backend**:	Node.js + Express (serving scraped or cached job data)
**State**	React useState/useEffect & Context for shared state
Performance	Lazy-loading, loading overlays, pagination

**🚀 Demo**
<img width="1617" height="914" alt="Screenshot 2025-07-22 002232" src="https://github.com/user-attachments/assets/703fed83-6e32-49a4-82f7-af21df5e7d73" />




<img width="1748" height="956" alt="Screenshot 2025-07-22 002253" src="https://github.com/user-attachments/assets/072524f1-e6c2-47e0-9d6b-6ac1b0a01fbb" />


```

**⚙️ Setup Instructions**
**Clone the repo:**
git clone https://github.com/sakshidsiq/React_Job_Portal.git
cd React_Job_Portal
Install dependencies (frontend & server):
npm install
npm run dev

```

**🧩 How It Works**
Frontend searches for jobs via /jobs?description=...&location=... (proxied through Express backend).

Results populate a list view with company logos (lazy-loaded).

Clicking on any listing opens a detail view with full HTML content (rendered safely).

“Load more” fetches additional pages; UI hides the button once no more results.

React Context shares state (current search, pagination, selected job) cleanly—no deep prop-passing.

🙌 Contributing 🤝
Contributions are welcome! Feel free to:

Open an issue ✅

Submit a PR 🔧

Enhance UI or add new features ✨
