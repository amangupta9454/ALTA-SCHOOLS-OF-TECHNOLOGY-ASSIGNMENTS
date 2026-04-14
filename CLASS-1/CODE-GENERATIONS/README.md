<div align="center">
  <img src="https://via.placeholder.com/800x150/0f172a/ffffff?text=ALTA+SCHOOL+OF+TECHNOLOGY" alt="Alta School of Technology Banner" width="100%" />
</div>

<br/>

<div align="center">
  <h1>Code Generation Assignment</h1>
  <p><em>Module: Prompt Engineering &amp; Generative AI Techniques</em></p>
  <p>An extensive showcase of prompt engineering skills, exploring the code generation capabilities of Large Language Models through targeted instructions.</p>
</div>

<hr/>

<div>
  <h2>📋 Task Description</h2>
  <p>
    <strong>Objective:</strong> Write a prompt to generate a complete REST API endpoint in your preferred language. Specify error handling, input validation, documentation, and testing requirements.
  </p>
  <p>
    This assignment aims to demonstrate the capability of LLMs in software engineering by guiding them step-by-step to produce production-ready code complete with safeguards, rather than basic, untested scripts.
  </p>
</div>

<br/>

<div>
  <h2>🎯 What We Learnt</h2>
  <p>
    Through completing this section of the assignment, several key techniques from our coursework were actively applied and verified.
  </p>
  <ul>
    <li><strong>Techniques Applied:</strong> Chain-of-Thought Prompting.</li>
    <h3><strong>Key Takeaways:</strong></h3>
    <li>Defining a clear role (e.g., frontend developer) improves code quality and structure</li>
    <li>Adding specific requirements (sections, features) results in more complete implementations</li>
    <li>Including constraints (no external libraries, responsiveness) ensures better control over output</li>
    <li>Specifying technologies (HTML, CSS, JS) leads to more accurate code generation</li>
    <li>Well-structured prompts produce clean, readable, and production-like code</li>
    <h3><strong>Observations:</strong></h3>
    <li>Basic prompts generate minimal and incomplete code</li>
    <li>Refined prompts produce structured and feature-rich implementations</li>
    <li>Lack of constraints leads to inconsistent or messy code output</li>
    <li>Detailed prompts improve UI, functionality, and responsiveness</li>
    <li>Prompt clarity directly impacts code quality and usability</li>
  </ul>
</div>

<br/>

<div>
  <h2>🧪 Prompt Engineering Process</h2>
  <p>This section documents the evolution of the prompt from the initial attempt to the final refined version, demonstrating the iterative improvement cycle.</p>

  <h3>1️⃣ Initial Prompt</h3>
  <div style="background-color: #f6f8fa; padding: 15px; border-left: 5px solid #0366d6; border-radius: 5px;">
    <strong>Your Initial Prompt:</strong>
    <br/>
    <br/>
    <p>Create a simple landing page using HTML.</p>
  </div>

  <br/>

  <h3>2️⃣ Initial AI Response</h3>
  <div style="background-color: #f0fdf4; padding: 15px; border-left: 5px solid #22863a; border-radius: 5px;">
    <strong>AI Output:</strong>
       <pre><code class="language-html">&lt;!DOCTYPE html&gt;
&lt;html lang="en"&gt;
&lt;head&gt;
  &lt;meta charset="UTF-8"&gt;
  &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;
  &lt;title&gt;LaunchPad - Get Started Today&lt;/title&gt;
  &lt;style&gt;
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      line-height: 1.6;
      color: #333;
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
      min-height: 100vh;
    }
    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 0 20px;
    }
    header {
      padding: 20px 0;
      position: fixed;
      width: 100%;
      top: 0;
      z-index: 1000;
      background: rgba(255, 255, 255, 0.1);
      backdrop-filter: blur(10px);
    }
    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .logo {
      font-size: 28px;
      font-weight: bold;
      color: white;
      text-decoration: none;
    }
    .nav-links a {
      color: white;
      text-decoration: none;
      margin-left: 30px;
      font-weight: 500;
      transition: opacity 0.3s;
    }
    .nav-links a:hover {
      opacity: 0.8;
    }
    .hero {
      height: 100vh;
      display: flex;
      align-items: center;
      color: white;
      text-align: center;
    }
    .hero-content {
      max-width: 800px;
      margin: 0 auto;
    }
    .hero h1 {
      font-size: 4.5rem;
      margin-bottom: 20px;
      line-height: 1.1;
    }
    .hero p {
      font-size: 1.4rem;
      margin-bottom: 40px;
      opacity: 0.9;
    }
    .cta-button {
      display: inline-block;
      background: white;
      color: #667eea;
      padding: 16px 40px;
      border-radius: 50px;
      font-size: 1.2rem;
      font-weight: bold;
      text-decoration: none;
      transition: all 0.3s;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
    }
    .cta-button:hover {
      transform: translateY(-5px);
      box-shadow: 0 15px 35px rgba(0, 0, 0, 0.3);
    }
    .features {
      padding: 100px 0;
      background: white;
      text-align: center;
    }
    .features h2 {
      font-size: 2.8rem;
      margin-bottom: 60px;
      color: #333;
    }
    .feature-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 40px;
    }
    .feature-card {
      padding: 40px 20px;
      border-radius: 16px;
      background: #f8f9fa;
      transition: transform 0.3s;
    }
    .feature-card:hover {
      transform: translateY(-10px);
    }
    .feature-card h3 {
      font-size: 1.6rem;
      margin: 20px 0 15px;
    }
    footer {
      background: #222;
      color: #ccc;
      text-align: center;
      padding: 60px 0;
    }
    @media (max-width: 768px) {
      .hero h1 {
        font-size: 3rem;
      }
      .nav-links {
        display: none;
      }
    }
  &lt;/style&gt;
&lt;/head&gt;
&lt;body&gt;

  &lt;header&gt;
    &lt;div class="container"&gt;
      &lt;nav&gt;
        &lt;a href="#" class="logo"&gt;LaunchPad&lt;/a&gt;
        &lt;div class="nav-links"&gt;
          &lt;a href="#"&gt;Features&lt;/a&gt;
          &lt;a href="#"&gt;Pricing&lt;/a&gt;
          &lt;a href="#"&gt;Blog&lt;/a&gt;
          &lt;a href="#"&gt;Contact&lt;/a&gt;
        &lt;/div&gt;
      &lt;/nav&gt;
    &lt;/div&gt;
  &lt;/header&gt;
  &lt;section class="hero"&gt;
    &lt;div class="container"&gt;
      &lt;div class="hero-content"&gt;
        &lt;h1&gt;Build Something&lt;br&gt;Amazing Today&lt;/h1&gt;
        &lt;p&gt;Simple, beautiful, and powerful landing pages in minutes. No coding skills required.&lt;/p&gt;
        &lt;a href="#" class="cta-button"&gt;Get Started Free&lt;/a&gt;
      &lt;/div&gt;
    &lt;/div&gt;
  &lt;/section&gt;
  &lt;section class="features"&gt;
    &lt;div class="container"&gt;
      &lt;h2&gt;Why Choose LaunchPad?&lt;/h2&gt;
      &lt;div class="feature-grid"&gt;
        &lt;div class="feature-card"&gt;
          &lt;h3&gt;⚡ Lightning Fast&lt;/h3&gt;
          &lt;p&gt;Deploy your ideas in seconds with our blazing-fast infrastructure.&lt;/p&gt;
        &lt;/div&gt;
        &lt;div class="feature-card"&gt;
          &lt;h3&gt;🎨 Beautiful Design&lt;/h3&gt;
          &lt;p&gt;Stunning templates that look professional on every device.&lt;/p&gt;
        &lt;/div&gt;
        &lt;div class="feature-card"&gt;
          &lt;h3&gt;🔧 Easy to Use&lt;/h3&gt;
          &lt;p&gt;Intuitive interface designed for creators, not just developers.&lt;/p&gt;
        &lt;/div&gt;
      &lt;/div&gt;
    &lt;/div&gt;
  &lt;/section&gt;
  &lt;footer&gt;
    &lt;div class="container"&gt;
      &lt;p&gt;&copy; 2026 LaunchPad. Made with ❤️ for creators.&lt;/p&gt;
    &lt;/div&gt;
  &lt;/footer&gt;

&lt;/body&gt;
&lt;/html&gt;</code></pre>
  </div>
  <h3>Output:</h3>
   <img src="https://res.cloudinary.com/dgtyqhtor/image/upload/v1776134093/Screenshot_2026-04-14_080302_zochev.png" alt="Home Page" style="max-width: 100%; height: auto; border: 1px solid #ddd;">
   <img src="https://res.cloudinary.com/dgtyqhtor/image/upload/v1776134092/Screenshot_2026-04-14_080320_moecew.png" alt="Home Page" style="max-width: 100%; height: auto; border: 1px solid #ddd;">
  <br/><hr/><br/>

  <h3>3️⃣ Refined &amp; Advanced Prompt</h3>
  <p>After analyzing the limitations of the initial attempt, the prompt was heavily restructured applying the learned formulas.</p>
  <div style="background-color: #f6f8fa; padding: 15px; border-left: 5px solid #6f42c1; border-radius: 5px;">
    <strong>Your Refined Prompt:</strong>
    <br/>
    <br/>
    <p>
<li>Act as a professional frontend developer.</li>
<li>Create a modern, responsive landing page using HTML and CSS for a tech startup.</li>
<li>Requirements:</li>
<li>Include sections: Navbar, Hero Section, Features, About, Contact, Footer</li>
<li>Use semantic HTML5 tags</li>
<li>Add clean and modern UI styling using internal CSS</li>
<li>Make it responsive for mobile and desktop</li>
<li>Use proper headings, buttons, and layout structure</li>
<li>Add placeholder text for content</li>
<li>Include a call-to-action button in hero section</li>
<li>Ensure code is well-structured and readable</li>
<li>Do not use external libraries</li>
<li>Also explain the structure briefly at the end.</li></p>
  </div>

  <br/>

  <h3>4️⃣ Final AI Response</h3>
  <div style="background-color: #f0fdf4; padding: 15px; border-left: 5px solid #22863a; border-radius: 5px;">
    <strong>Improved AI Output:</strong>
    <br/>
    <br/>
    <pre><code class="language-html">&lt;!DOCTYPE html&gt;
&lt;html lang="en"&gt;
&lt;head&gt;
  &lt;meta charset="UTF-8"&gt;
  &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;
  &lt;title&gt;Nexus • AI-Powered Innovation&lt;/title&gt;
  &lt;style&gt;
    :root {
      --primary: #6366f1;
      --dark: #0f172a;
      --light: #f8fafc;
    }
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', system-ui, sans-serif;
      line-height: 1.6;
      color: #334155;
      background-color: #fff;
    }
    /* Navbar */
    nav {
      background: rgba(255, 255, 255, 0.95);
      backdrop-filter: blur(12px);
      position: fixed;
      width: 100%;
      top: 0;
      z-index: 1000;
      border-bottom: 1px solid #e2e8f0;
    }
    .nav-container {
      max-width: 1280px;
      margin: 0 auto;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .logo {
      font-size: 1.8rem;
      font-weight: 700;
      color: var(--dark);
      text-decoration: none;
    }
    .nav-links {
      display: flex;
      gap: 2rem;
      list-style: none;
    }
    .nav-links a {
      text-decoration: none;
      color: #475569;
      font-weight: 500;
      transition: color 0.3s;
    }
    .nav-links a:hover {
      color: var(--primary);
    }
    .nav-actions {
      display: flex;
      gap: 1rem;
    }
    .btn {
      padding: 0.75rem 1.5rem;
      border-radius: 50px;
      font-weight: 600;
      text-decoration: none;
      transition: all 0.3s;
      cursor: pointer;
      border: none;
    }
    .btn-primary {
      background: var(--primary);
      color: white;
    }
    .btn-primary:hover {
      background: #4f46e5;
      transform: translateY(-2px);
    }
    .btn-outline {
      border: 2px solid var(--primary);
      color: var(--primary);
    }
    .btn-outline:hover {
      background: var(--primary);
      color: white;
    }
    /* Hero Section */
    .hero {
      min-height: 100vh;
      display: flex;
      align-items: center;
      background: linear-gradient(135deg, #6366f1 0%, #8b5cf6 100%);
      color: white;
      position: relative;
      overflow: hidden;
    }
    .hero-content {
      max-width: 1280px;
      margin: 0 auto;
      padding: 0 2rem;
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 4rem;
      align-items: center;
    }
    .hero-text h1 {
      font-size: 3.8rem;
      line-height: 1.1;
      margin-bottom: 1.5rem;
    }
    .hero-text p {
      font-size: 1.3rem;
      margin-bottom: 2.5rem;
      opacity: 0.95;
    }
    .hero-buttons {
      display: flex;
      gap: 1rem;
      flex-wrap: wrap;
    }
    /* Features */
    .section {
      padding: 100px 0;
    }
    .container {
      max-width: 1280px;
      margin: 0 auto;
      padding: 0 2rem;
    }
    .section-title {
      text-align: center;
      font-size: 2.8rem;
      margin-bottom: 1rem;
      color: var(--dark);
    }
    .section-subtitle {
      text-align: center;
      font-size: 1.2rem;
      color: #64748b;
      max-width: 600px;
      margin: 0 auto 4rem;
    }
    .features-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
      gap: 2rem;
    }
    .feature-card {
      background: white;
      padding: 2.5rem;
      border-radius: 20px;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.08);
      transition: transform 0.3s;
    }
    .feature-card:hover {
      transform: translateY(-10px);
    }
    .feature-icon {
      font-size: 2.8rem;
      margin-bottom: 1.5rem;
    }
    /* About */
    .about {
      background: #f8fafc;
    }
    .about-content {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 5rem;
      align-items: center;
    }
    /* Contact */
    .contact-form {
      max-width: 600px;
      margin: 0 auto;
      background: white;
      padding: 3rem;
      border-radius: 20px;
      box-shadow: 0 15px 40px rgba(0, 0, 0, 0.1);
    }
    input, textarea {
      width: 100%;
      padding: 1rem;
      margin-bottom: 1.5rem;
      border: 1px solid #cbd5e1;
      border-radius: 12px;
      font-size: 1rem;
    }
    /* Footer */
    footer {
      background: var(--dark);
      color: #cbd5e1;
      padding: 80px 0 30px;
    }
    .footer-content {
      max-width: 1280px;
      margin: 0 auto;
      padding: 0 2rem;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 3rem;
    }
    /* Responsive */
    @media (max-width: 968px) {
      .hero-content {
        grid-template-columns: 1fr;
        text-align: center;
      }      
      .hero-text h1 {
        font-size: 3rem;
      }      
      .about-content {
        grid-template-columns: 1fr;
      }
    }
    @media (max-width: 640px) {
      .nav-links {
        display: none;
      }
      .hero-buttons {
        justify-content: center;
      }
    }
  &lt;/style&gt;
&lt;/head&gt;
&lt;body&gt;
  &lt;!-- Navbar --&gt;
  &lt;nav&gt;
    &lt;div class="nav-container"&gt;
      &lt;a href="#" class="logo"&gt;Nexus&lt;/a&gt;
      &lt;ul class="nav-links"&gt;
        &lt;li&gt;&lt;a href="#features"&gt;Features&lt;/a&gt;&lt;/li&gt;
        &lt;li&gt;&lt;a href="#about"&gt;About&lt;/a&gt;&lt;/li&gt;
        &lt;li&gt;&lt;a href="#contact"&gt;Contact&lt;/a&gt;&lt;/li&gt;
      &lt;/ul&gt;
      &lt;div class="nav-actions"&gt;
        &lt;a href="#" class="btn btn-outline"&gt;Log in&lt;/a&gt;
        &lt;a href="#" class="btn btn-primary"&gt;Get Started&lt;/a&gt;
      &lt;/div&gt;
    &lt;/div&gt;
  &lt;/nav&gt;
  &lt;!-- Hero Section --&gt;
  &lt;section class="hero"&gt;
    &lt;div class="hero-content"&gt;
      &lt;div class="hero-text"&gt;
        &lt;h1&gt;The Future of Intelligent Workflows&lt;/h1&gt;
        &lt;p&gt;Nexus combines cutting-edge AI with beautiful design to help teams achieve more, faster. Built for the next generation of innovators.&lt;/p&gt;
        &lt;div class="hero-buttons"&gt;
          &lt;a href="#contact" class="btn btn-primary" style="padding: 1rem 2rem; font-size: 1.1rem;"&gt;Start Free Trial&lt;/a&gt;
          &lt;a href="#" class="btn btn-outline" style="color: white; border-color: white;"&gt;Watch Demo&lt;/a&gt;
        &lt;/div&gt;
      &lt;/div&gt;
      &lt;div&gt;
        &lt;!-- Placeholder for hero visual --&gt;
        &lt;div style="background: rgba(255,255,255,0.15); height: 420px; border-radius: 24px; display: flex; align-items: center; justify-content: center; font-size: 1.2rem; color: rgba(255,255,255,0.8);"&gt;
          ✨ Product Dashboard Preview
        &lt;/div&gt;
      &lt;/div&gt;
    &lt;/div&gt;
  &lt;/section&gt;
  &lt;!-- Features Section --&gt;
  &lt;section id="features" class="section"&gt;
    &lt;div class="container"&gt;
      &lt;h2 class="section-title"&gt;Powerful Features&lt;/h2&gt;
      &lt;p class="section-subtitle"&gt;Everything you need to scale your business with intelligence and elegance.&lt;/p&gt;
      &lt;div class="features-grid"&gt;
        &lt;div class="feature-card"&gt;
          &lt;div class="feature-icon"&gt;🚀&lt;/div&gt;
          &lt;h3&gt;AI Automation&lt;/h3&gt;
          &lt;p&gt;Automate repetitive tasks and let AI handle complex workflows with unmatched accuracy.&lt;/p&gt;
        &lt;/div&gt;
        &lt;div class="feature-card"&gt;
          &lt;div class="feature-icon"&gt;📊&lt;/div&gt;
          &lt;h3&gt;Real-time Analytics&lt;/h3&gt;
          &lt;p&gt;Beautiful dashboards with actionable insights that help you make better decisions instantly.&lt;/p&gt;
        &lt;/div&gt;
        &lt;div class="feature-card"&gt;
          &lt;div class="feature-icon"&gt;🔗&lt;/div&gt;
          &lt;h3&gt;Seamless Integrations&lt;/h3&gt;
          &lt;p&gt;Connect with your favorite tools — Slack, Notion, Google Workspace, and 50+ more.&lt;/p&gt;
        &lt;/div&gt;
      &lt;/div&gt;
    &lt;/div&gt;
  &lt;/section&gt;
  &lt;!-- About Section --&gt;
  &lt;section id="about" class="section about"&gt;
    &lt;div class="container"&gt;
      &lt;div class="about-content"&gt;
        &lt;div&gt;
          &lt;h2 style="font-size: 2.8rem; line-height: 1.2;"&gt;Building the future of collaborative intelligence&lt;/h2&gt;
          &lt;p style="margin-top: 1.5rem; font-size: 1.15rem;"&gt;
            Founded in 2024, Nexus was born from a simple idea: technology should make work feel effortless. 
            Our mission is to empower teams with intelligent tools that enhance creativity rather than replace it.
          &lt;/p&gt;
          &lt;p style="margin-top: 1rem; font-size: 1.15rem;"&gt;
            Backed by leading venture firms and used by forward-thinking companies worldwide.
          &lt;/p&gt;
        &lt;/div&gt;
        &lt;div style="background: #e0e7ff; height: 380px; border-radius: 20px; display: flex; align-items: center; justify-content: center; font-size: 1.3rem; color: #6366f1;"&gt;
          Company Story Visual
        &lt;/div&gt;
      &lt;/div&gt;
    &lt;/div&gt;
  &lt;/section&gt;
  &lt;!-- Contact Section --&gt;
  &lt;section id="contact" class="section"&gt;
    &lt;div class="container"&gt;
      &lt;h2 class="section-title"&gt;Get In Touch&lt;/h2&gt;
      &lt;p class="section-subtitle"&gt;Ready to transform how your team works? Let's talk.&lt;/p&gt;
      &lt;div class="contact-form"&gt;
        &lt;form&gt;
          &lt;input type="text" placeholder="Your Name" required&gt;
          &lt;input type="email" placeholder="Work Email" required&gt;
          &lt;input type="text" placeholder="Company Name"&gt;
          &lt;textarea rows="5" placeholder="Tell us about your needs..."&gt;&lt;/textarea&gt;
          &lt;button type="submit" class="btn btn-primary" style="width: 100%; padding: 1rem;"&gt;Send Message&lt;/button&gt;
        &lt;/form&gt;
      &lt;/div&gt;
    &lt;/div&gt;
  &lt;/section&gt;
  &lt;!-- Footer --&gt;
  &lt;footer&gt;
    &lt;div class="footer-content"&gt;
      &lt;div&gt;
        &lt;h3 style="color: white; margin-bottom: 1rem;"&gt;Nexus&lt;/h3&gt;
        &lt;p&gt;AI-powered platform for modern teams.&lt;/p&gt;
      &lt;/div&gt;
      &lt;div&gt;
        &lt;h4 style="color: white; margin-bottom: 1rem;"&gt;Product&lt;/h4&gt;
        &lt;p&gt;Features&lt;br&gt;Pricing&lt;br&gt;Enterprise&lt;/p&gt;
      &lt;/div&gt;
      &lt;div&gt;
        &lt;h4 style="color: white; margin-bottom: 1rem;"&gt;Company&lt;/h4&gt;
        &lt;p&gt;About Us&lt;br&gt;Careers&lt;br&gt;Blog&lt;/p&gt;
      &lt;/div&gt;
      &lt;div&gt;
        &lt;h4 style="color: white; margin-bottom: 1rem;"&gt;Legal&lt;/h4&gt;
        &lt;p&gt;Privacy Policy&lt;br&gt;Terms of Service&lt;/p&gt;
      &lt;/div&gt;
    &lt;/div&gt;
    &lt;div style="text-align: center; margin-top: 60px; border-top: 1px solid #334155; padding-top: 30px;"&gt;
      &lt;p&gt;&copy; 2026 Nexus. All rights reserved.&lt;/p&gt;
    &lt;/div&gt;
  &lt;/footer&gt;
&lt;/body&gt;
&lt;/html&gt;</code></pre>
    <h3>Output</h3>
       <div style="display: flex; flex-wrap: wrap; gap: 20px; margin-bottom: 20px;">
        <div style="flex: 1 1 280px; background-color: #fff; padding: 15px; text-align: center; border: 1px solid #ddd;">
            <h3 style="color: #333; font-size: 20px; font-weight: bold; margin: 0 0 10px;">Home Page</h3>
            <img src="https://res.cloudinary.com/dgtyqhtor/image/upload/v1776135090/Screenshot_2026-04-14_082008_vxtiro.png" alt="Home Page" style="max-width: 100%; height: auto; border: 1px solid #ddd;">
        </div>
        <div style="flex: 1 1 280px; background-color: #fff; padding: 15px; text-align: center; border: 1px solid #ddd;">
            <h3 style="color: #333; font-size: 20px; font-weight: bold; margin: 0 0 10px;">About Us</h3>
            <img src="https://res.cloudinary.com/dgtyqhtor/image/upload/v1776135090/Screenshot_2026-04-14_082035_j1l895.png" alt="Resume Builder" style="max-width: 100%; height: auto; border: 1px solid #ddd;">
        </div>
        <div style="flex: 1 1 280px; background-color: #fff; padding: 15px; text-align: center; border: 1px solid #ddd;">
            <h3 style="color: #333; font-size: 20px; font-weight: bold; margin: 0 0 10px;">Statics Page</h3>
            <img src="https://res.cloudinary.com/dgtyqhtor/image/upload/v1776135090/Screenshot_2026-04-14_082021_sjeqxu.png" alt="Email Generator" style="max-width: 100%; height: auto; border: 1px solid #ddd;">
        </div>
        <div style="flex: 1 1 280px; background-color: #fff; padding: 15px; text-align: center; border: 1px solid #ddd;">
            <h3 style="color: #333; font-size: 20px; font-weight: bold; margin: 0 0 10px;">Contact Us</h3>
            <img src="https://res.cloudinary.com/dgtyqhtor/image/upload/v1776135090/Screenshot_2026-04-14_082044_i7s3ps.png" alt="Email Generator" style="max-width: 100%; height: auto; border: 1px solid #ddd;">
        </div>
        <div style="flex: 1 1 280px; background-color: #fff; padding: 15px; text-align: center; border: 1px solid #ddd;">
            <h3 style="color: #333; font-size: 20px; font-weight: bold; margin: 0 0 10px;">Footer</h3>
            <img src="https://res.cloudinary.com/dgtyqhtor/image/upload/v1776135089/Screenshot_2026-04-14_082055_a5ooou.png" alt="Email Generator" style="max-width: 100%; height: auto; border: 1px solid #ddd;">
        </div>
    </div>
  </div>
</div>

<br/>

<div>
  <h2>📝 Analysis &amp; Reflection</h2>
  <p>Reflecting on the prompt engineering lifecycle to identify exactly what modifications led to performance gains.</p>
  
  <h3>What I Changed and Why</h3>
  <ul>
    <li>
      <strong>Modification 1:</strong> Adding target audience makes the output more relevant, personalized, and aligned with real-world use cases.
      <p><em>Reasoning:</em>It provides clear context to the AI, helping generate more targeted and meaningful content.</p>
    </li>
    <li>
      <strong>Modification 2:</strong> Adding design constraints improves visual quality, consistency, and overall professionalism of the generated UI.
      <p><em>Reasoning:</em> It gives specific design guidance, leading to better structured and visually appealing output.</p>
    </li>
  </ul>

</div>

<br/>

<div>
  <h2>🛠️ Tools &amp; Technologies Used</h2>
  <ul>
    <li><strong>LLM Platform:</strong> Grok AI</li>
    <li><strong>Other Tools:</strong> Visual Studio Code</li>
  </ul>
</div>

<br/>

<div>
  <h2>👨‍🎓 About the Student</h2>
  <table border="1" style="width: 100%; border-collapse: collapse;">
    <tbody>
      <tr>
        <th style="padding: 10px; width: 30%; text-align: left; background-color: #e2e8f0;">Aspect</th>
        <th style="padding: 10px; text-align: left; background-color: #e2e8f0;">Details</th>
      </tr>
      <tr>
        <td style="padding: 10px;"><strong>Name</strong></td>
        <td style="padding: 10px;">Aman Gupta</td>
      </tr>
      <tr>
        <td style="padding: 10px;"><strong>Email</strong></td>
        <td style="padding: 10px;">ag0567688@gmail.com</td>
      </tr>
      <tr>
        <td style="padding: 10px;"><strong>Mobile Number</strong></td>
        <td style="padding: 10px;">9560472926</td>
      </tr>
      <tr>
        <td style="padding: 10px;"><strong>Course</strong></td>
        <td style="padding: 10px;">B.Tech</td>
      </tr>
      <tr>
        <td style="padding: 10px;"><strong>Branch</strong></td>
        <td style="padding: 10px;">Computer Science and Engineering</td>
      </tr>
      <tr>
        <td style="padding: 10px;"><strong>Year</strong></td>
        <td style="padding: 10px;">3rd Year</td>
      </tr>
      <tr>
        <td style="padding: 10px;"><strong>College</strong></td>
        <td style="padding: 10px;">Hi-Tech Institute of Engineering and Technology Ghaziabad</td>
      </tr>
    </tbody>
  </table>
</div>

<br/><hr/><br/>

<div align="center">
  <p><i>This documentation was meticulously compiled as part of the Alta Schools of Technology Internship Assignment program.</i></p>
</div>
