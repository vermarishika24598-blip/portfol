#portfolio
📌 Rishika Verma — Personal Portfolio
A modern and responsive frontend developer portfolio built using React, Tailwind CSS, and Framer Motion.
This portfolio showcases my skills, projects, resume, and contact information in a clean and professional UI.

🚀 Features


Beautiful animated Hero Section


Smooth Framer Motion animations


Responsive layout for all devices


Projects section with links


Resume button (PDF import supported)


Contact section


Skills showcase


Clean and minimal UI with Tailwind CSS



🛠 Tech Stack


React.js


Tailwind CSS


Framer Motion


Parcel / Vite (depending on setup)


React Router



📁 Project Structure
src/
  components/
  assets/
  resume.pdf
  App.jsx
public/
package.json


🖥️ Installation & Setup
Clone the repo:
git clone https://github.com/vermarishika24598/rishika-portfolio.git
cd rishika-portfolio

Install dependencies:
npm install

Run the development server:
npm run start


📄 Resume Integration
Your resume PDF is imported like this:
import resumeFile from "../resume.pdf";

Then used in a button:
<a href={resumeFile} target="_blank" rel="noopener noreferrer">
  <button>Resume</button>
</a>


📸 Profile Image Integration
Place your image in:
src/assets/rishika.jpg

Import it:
import profilePic from "../assets/rishika.jpg";

Use it in JSX:
<img src={profilePic} alt="Rishika" />


🌐 Live Demo
(https://rainbow-bublanina-5eb518.netlify.app/)

🧑‍💻 Author
Rishika Verma
Frontend Developer | React.js | Tailwind CSS


GitHub: https://github.com/vermarishika24598


LinkedIn: https://www.linkedin.com/in/rishika-verma-4561502a6




