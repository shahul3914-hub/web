# Nagaladinna Shahul | Quantum Computing Portfolio

Live at : https://shahul3914-hub.github.io/web/

An interactive, responsive, dark-mode portfolio engineered for **Nagaladinna Shahul**, specializing in **Computer Science & Engineering (CSE) in Quantum Computing and Information Science**.

This web application combines a professional student portfolio with live, built-in quantum mechanics simulators and a real-time content management system that lets you add or edit skills and projects directly in the browser.

---

## 🚀 Features

### ⚛️ Interactive Quantum Utility Suite
* **Single-Qubit Gate Operator:** Apply unitary transformations like Hadamard ($H$), Pauli-X ($X$), and Pauli-Z ($Z$) directly to a simulated state vector $\vert\Psi\rangle = \alpha\vert 0\rangle + \beta\vert 1\rangle$ and view calculated state probabilities.
* **Grover Speedup Complexity Calculator:** Interactive visualizer comparing classical $O(2^N)$ brute-force search complexity against quantum quadratic speedup $O(\sqrt{N})$.

### 🛠️ Live Browser Content Management
* **Dynamic Persistence:** Add new projects, course achievements, and technical skills using the built-in modal forms.
* **Local Storage Integration:** Added items save directly to your browser's local storage so your additions persist even after refreshing or restarting your browser.
* **Beginner-Friendly Workflows:** Easily remove placeholder items and add your real-world Qiskit code repositories or C++ programs as you complete them.

### 💼 Portfolio Sections
* **Hero Section:** Personalized introduction, dynamic quantum typing loop, and action triggers.
* **Technical Skills Matrix:** Categorized cards featuring custom status tags (*Currently Learning*, *Foundational*, *Interested In*).
* **Project Showcase:** Filterable project cards detailing problem statements, engineering approaches, and links to source code repositories.
* **Educational Journey:** Vertical timeline tracking milestones in your CSE & Quantum degree.
* **Validated Contact Form:** Client-side email inquiry form with success confirmation feedback.

---

## 🛠️ Tech Stack & Dependencies

* **Framework:** React / Next.js
* **Styling:** Tailwind CSS (Dark Engineering Palette: `#0F172A` Slate background with `#06B6D4` Electric Cyan accents)
* **Icons:** [Lucide React](https://lucide.dev/)
* **State Persistence:** Browser `localStorage` API
* **Mathematical Notation:** LaTeX / Standard Quantum Notation ($\vert\Psi\rangle, \vert 0\rangle, \vert 1\rangle$)

---

## 💻 Getting Started Locally

### Prerequisites
Make sure you have [Node.js](https://nodejs.org/) (v16 or higher) installed on your system.

### Installation

1. **Clone or download the project files** to your local computer:
   ```bash
   git clone https://shahul3914-hub.github.io/web/
   cd web
   ```

2. **Install necessary dependencies:**
   ```bash
   npm install
   ```

3. **Install Lucide React icons:**
   ```bash
   npm install lucide-react
   ```

4. **Start the development server:**
   ```bash
   npm run dev
   ```

5. **View in browser:**
   Open [http://localhost:3000](http://localhost:3000) or [http://localhost:5173](http://localhost:5173) (depending on whether you use Next.js or Vite).

---

## ✏️ Customization Guide

### 1. Editing via Browser (No Code Required)
* Open the portfolio in your web browser.
* Click **"+ Add Project"** or **"+ Add Custom Skill"**.
* Enter your new project details (title, summary, tags, GitHub link) and click **Save**.
* Use the trash icon on any card to delete starting placeholders.

### 2. Updating Source Code Defaults
To permanently change default data across all devices, edit the data arrays at the top of `app.jsx`:

* **Name & Tagline:** Edit lines inside the Hero section or change the `disciplines` array for the typing animation.
* **Default Skills:** Update the `DEFAULT_SKILLS` array:
  ```javascript
  const DEFAULT_SKILLS = [
    {
      category: 'Quantum Computing & Physics',
      skills: [
        { id: 's1', name: 'Qiskit Framework', level: 'Currently Learning', tags: ['IBM Quantum', 'Python'] }
      ]
    }
  ];
  ```
* **Default Projects:** Update the `DEFAULT_PROJECTS` array to list your actual GitHub repositories.

---

## 🌐 Deploying Your Portfolio

You can host this site online for free using platforms like **Vercel** or **Netlify**:

1. Push your project code to a [GitHub](https://github.com) repository.
2. Log into [Vercel](https://vercel.com) or [Netlify](https://netlify.com).
3. Import your GitHub repository.
4. Click **Deploy**. Your live quantum engineering portfolio will be online in under 2 minutes!

---

## 📄 License

Created for **Nagaladinna Shahul**. Open-source under the [MIT License](LICENSE).
