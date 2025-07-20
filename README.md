### NexiaX - AI Chatbot with DeepThink Mode
---
<img width="450" height="250" alt="NexiaX_logo" src="https://github.com/user-attachments/assets/380248f2-4077-4cf2-b0ea-ba7053f58cd5" />

### 🚀About NexiaX 
---
NexiaX is a modern AI-powered chatbot application featuring:
* Gemini AI integration for intelligent responses
* Markdown rendering with syntax highlighting
* PDF document analysis capability
* DeepThink mode for comprehensive topic analysis
* Responsive design for all devices
* Dark/Light theme toggle
* Conversation history management


https://github.com/user-attachments/assets/a3257ba7-9c7f-4246-bf73-7b18c484bcd7


### ✨Key Features
---
NexiaX comes packed with features to boost your productivity and interaction:

* **AI-Powered Chat** - Intelligent and context-aware responses driven by Google Gemini AI.
* **DeepDive Mode** - Dedicated for in-depth analysis of complex topics and documents.
* **PDF Interpreter** - Upload PDFs to extract information, solve queries, or generate summaries.
* **Markdown Support** - Clean, readable chat responses with proper formatting and code highlighting.
* **Adaptive UI** - Toggle between Dark and Light themes for comfortable viewing.
* **Mobile-Friendly Design** - Fully responsive and optimized for seamless experience on all devices.
* **Smart History** - Efficiently manage and save conversations for future review.

  

### Technologies Used
---
* **Frontend:** Next.js (App Router), React, TypeScript
* **Styling:** Tailwind CSS, shadcn/ui components
* **AI:** Google Gemini AI API
* **Utilities:** PDF.js (for parsing), Framer Motion (animations), Sonner (notifications), JS Confetti (effects)



### 💻 Installation & Setup
---
To run NexiaX locally, follow these steps:

1.  **Clone the repository:**
   
    ```bash
    git clone [https://github.com/Sakshisingh409/NexiaX-AIChatbot.git]
    (https://github.com/Sakshisingh409/NexiaX-AIChatbot.git)
    cd NexiaX-AIChatbot
    ```

2.  **Install dependencies:**

    ```bash
    npm install
    # or
    yarn install
    # or
    pnpm install
    ```

3.  **Create a .env.local file in the root directory and add your Gemini API key:**

    ```
    NEXT_PUBLIC_GEMINI_API_KEY=your_api_key_here
    ```

4.  **Run the development server:**
   
   ```bash
   npm run dev
   #or
   yarn dev
   #or
   pnpm dev

Access NexiaX at http://localhost:3000 in your browser.
   ```
    

### ⚙ Configuration Details
---
Essential configurations for NexiaX:

1.  **Gemini API Key:** Obtain from Google AI Studio and add to .env.local.
2.  **PDF.js Worker:** Automatically loaded from CDN.
3.  **Tailwind CSS:** Pre-configured in the project.


### 📂 Project Structure Overview
---
```bash
nexiax-chatbot/
├── app/                
│   ├── layout.tsx
│   ├── page.tsx
│   └── (other Next.js pages)
├── components/        
│   └── page(ChatBot).tsx (main component)          
├── public/
│   └── logo.png (application logo)
├── styles/
│   └── globals.css
├── package.json
├── tailwind.config.js
└── tsconfig.json
 ```

### 🔑 Environment Variables
---
Required environment variable:

NEXT_PUBLIC_GEMINI_API_KEY - Your Google Gemini API key.


### ⚠ Known Issues
---
* **Large PDF Files:** Parsing may cause performance issues.
* **DeepDive Mode Token Usage:** Consumes more API tokens for comprehensive analysis.
* **Mobile Performance:** May degrade with many conversation items.
---

**Thank you for exploring NexiaX!**
