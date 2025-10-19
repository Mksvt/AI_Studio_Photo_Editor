# AI Studio

AI Studio is a modern SaaS platform for image editing that leverages artificial intelligence to automate processes such as background removal, quality enhancement, and smart cropping. By integrating cutting-edge technologies like Next.js 15, Neon, Polar, Better Auth, and ImageKit, the platform delivers a secure, fast, and user-friendly experience.

## 📌 Key Features

- 🔐 **Secure Authentication:** Support for email, password, and social logins with Better Auth.
- 💳 **Payments and Credits:** Integration with Polar for managing payments and credits.
- 🤖 **AI-Powered Editing:** Background removal, quality enhancement, and smart cropping of images.
- 📁 **Project Management:** Save editing history and manage projects.
- 👤 **User Dashboard:** Manage invoices, credits, and payment information.
- 📱 **Responsive Design:** A modern interface that works on all devices.
- ⚡ **Real-Time Updates:** Instant status updates and credit deductions.
- 🎨 **Professional Interface:** Smooth transitions and aesthetic design.
- ☁️ **Serverless Deployment:** Scalable hosting solution on Vercel.

## 🛠️ Technologies

- **Frontend:** Next.js 15 (App Router + Server Actions)
- **Styling:** Tailwind CSS + shadcn/ui
- **Database:** Neon PostgreSQL + Prisma ORM
- **Payments:** Polar
- **Authentication:** Better Auth
- **Image Processing:** ImageKit (storage, optimization, and AI features)
- **Deployment:** Vercel

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/sahandghavidel/ai-image-editor-saas-app.git
   cd ai-image-editor-saas-app
   ```
2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Set up environment variables:**

   ```bash
   cp .env.example .env.local
   ```

   Fill in the variables for Neon, ImageKit, Polar, and Better Auth.

4. **Set up the database:**
   ```bash
   npx prisma migrate dev
   ```
5. **Run the development server:**
   ```bash
   npm run dev
   ```
   Open your browser and navigate to [http://localhost:3000](http://localhost:3000).

## 📖 What You'll Learn

- Modern Full-Stack Development with Next.js 15.
- SaaS Application Architecture and best practices.
- AI Integration for image processing with ImageKit.
- Payment Systems Implementation using Polar.
- Advanced Authentication with Better Auth.
- Database Design and Management with Prisma.
- Serverless Deployment strategies.

## 🎯 Future Ideas

- Add collaboration features for team-based image editing.
- Integrate with other AI services for text-to-image generation.
- Expand editing functionality: filters, retouching, color adjustments.
- Support for multilingual interfaces to reach a global audience.
- Develop a mobile app for convenient platform access.

## 🤝 How to Contribute

We welcome your ideas and contributions! Feel free to submit a Pull Request or create Issues.

## 📝 License

This project is open-source and available under the MIT License.

## 🙏 Acknowledgments

- **ImageKit** for powerful image processing APIs.
- **Neon** for reliable PostgreSQL hosting.
- **Polar** for seamless payment integration.
- **Better Auth** for robust authentication systems.

If you enjoyed this project, leave a ⭐ on GitHub!
