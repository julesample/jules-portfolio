<script setup>

import { Download, ExternalLink, Mail, Github, Linkedin } from "lucide-vue-next"

import connectedBlog from './assets/connected-blog.png'
import connectedDemo from './assets/connected_demo.png'
import qr from './assets/qr.png'
import clientIndex from './assets/client-index.jpg'
import construction from './assets/construction.png'
import pagsanghanBallers from './assets/pagsanghan_ballers.png'
</script>

<template>
       <div className="min-h-screen bg-gray-900 text-white font-mono">
      <header className="border-b-4 border-blue-400 p-4 md:p-6 ">
        <div className="max-w-6xl mx-auto">
          <div className="border-2 border-white p-3 md:p-4 mb-4">
            <h1 className="text-2xl md:text-4xl font-bold mb-2">Jules Eliot Lozada</h1>
            <p className="text-base md:text-xl text-blue-400">ASPIRING SOFTWARE DEVELOPER / FULL-STACK ENTHUSIAST</p>
          </div>
          <nav className="flex flex-col sm:flex-row gap-3 md:gap-6">
            <a
              href="#about"  
              className="border-2 border-white px-3 py-2 md:px-4 md:py-2 hover:bg-white hover:text-black transition-none text-center text-sm md:text-base cursor-pointer"
            >
              [ABOUT]
            </a>
            <a
              href="#projects"
              className="border-2 border-white px-3 py-2 md:px-4 md:py-2 hover:bg-white hover:text-black transition-none text-center text-sm md:text-base cursor-pointer"
            >
              [PROJECTS]
            </a>
            <a
              href="#contact"
              className="border-2 border-white px-3 py-2 md:px-4 md:py-2 hover:bg-white hover:text-black transition-none text-center text-sm md:text-base cursor-pointer"
            >
              [CONTACT]
            </a>
          </nav>
        </div>
      </header>

      <section id="about" className="border-b-4 border-blue-400 p-6">
        <div className="max-w-6xl mx-auto">
          <h2 className="text-3xl font-bold mb-6 border-b-2 border-white pb-2">ABOUT_ME.TXT</h2>
          <div className="grid grid-cols-1 lg:grid-cols-2 gap-8 mb-8">
            <div className="border-2 border-white p-6">
              <h3 className="text-xl font-bold mb-4 text-blue-400">DESCRIPTION:</h3>
              <p className="mb-4 leading-relaxed">
                Aspiring full-stack developer passionate about building modern web applications. Currently learning and
                building projects with JavaScript, TypeScript, and modern frameworks.
              </p>
              <p className="mb-4 leading-relaxed">
                Focused on frontend and backend development with experience in React, Next.js, Vue.js, and database
                management. Always eager to tackle new challenges and contribute to meaningful projects.
              </p>

               <p className="mb-4 leading-relaxed">
Fast learner with a strong foundation in software development principles. Eager to collaborate with peers and contribute idea in building innovative solutions.
Willing to learn and adapt to new technologies and frameworks as needed.
              </p>
            </div>
            <div className="border-2 border-white p-6">
              <h3 className="text-xl font-bold mb-4 text-blue-400">SKILLS.JSON:</h3>
              <pre className="text-sm leading-relaxed">
{
  "languages": [
    "HTML", "CSS",
    "JavaScript", "TypeScript", 
    "PHP", "SQL"
  ],
  "frameworks": [
    "Next.js", "React", "Vue.js",
    "Tailwind CSS", "Node.js"
  ],
  "databases": [
    "PostgreSQL", "Supabase",
    "MySQL", "SQLite"
  ],
  "tools": [
    "Git", "GitHub", "VS Code",
    "CI/CD", "Vercel", "Netlify"
  ]
}
              </pre>
            </div>
          </div>

          <div className="grid grid-cols-1 lg:grid-cols-2 gap-8">
            <div className="border-2 border-white p-6">
              <h3 className="text-xl font-bold mb-4 text-blue-400">EDUCATION:</h3>
              <div className="mb-6">
                <h4 className="font-bold">B.S. INFORMATION TECHNOLOGY</h4>
                <p className="text-blue-400">Samar State University | 2024</p>
                <p className="text-sm mt-2">
                  Graduated with focus on software development, database management, and web technologies.
                </p>
              </div>

              <div className="mb-6">
                <h4 className="font-bold">Diploma in Secondary Level</h4>
                <p className="text-blue-400">Samar National School | 2020</p>
              </div>

              <div className="mb-6">
                <h4 className="font-bold">Diploma Primary Level</h4>
                <p className="text-blue-400">Pagsanghan Central Elementary School | 2014</p>
              </div>
               
            </div>
       <div className="border-2 border-white p-6">
              <h3 className="text-xl font-bold mb-4 text-blue-400">Internship Experience</h3>
              <div className="mb-6">
  <h4 className="font-bold">Web Developer Intern at iPhiTech</h4>
  <p className="text-blue-400">Clark, Philippines (Remote)</p>
  <ul className="list-disc list-inside text-sm mt-2">
    <li>Developed and customized websites using WordPress and Elementor.</li>
    <li>We also practiced copying mockup webdesigns for better understanding in Wordpress.</li>
    <li>Performed basic SEO and performance optimization tasks.</li>
    <li>Made responsive webdesigns using Wordpress with elementor.</li>
  </ul>
</div>


            
                <div className="mt-8">
                <a
                  href="https://drive.google.com/file/d/1vLTssXHHgKCbD9bVX0YtABIMS8QMrWUr/view?usp=sharing"
                  target="_blank"
                  rel="noopener noreferrer"
                  className="border-2 border-blue-400 bg-blue-400 text-black px-4 py-2 hover:bg-black hover:text-blue-400 flex items-center gap-2 justify-center transition-colors"
                >
                  <Download :size=13 />
                  DOWNLOAD_RESUME.PDF
                </a>
              </div>
            </div>
          </div>
          
        </div>
      </section>

      <section id="projects" className="border-b-4 border-blue-400 p-6">
        <div className="max-w-6xl mx-auto">
          <h2 className="text-3xl font-bold mb-6 border-b-2 border-white pb-2">PROJECTS.DIR</h2>
          <div className="grid grid-cols-1 lg:grid-cols-2 gap-6">
            <div className="border-2 border-white">
              <div className="border-b-2 border-white p-4 bg-blue-400 text-black">
                <h3 className="text-xl font-bold">CONNECTED-BLOG</h3>
              </div>
              <div className="p-6">
                <img
                  :src="connectedBlog"
                  alt="CONNECTED-BLOG"
                  className="w-full h-48 object-cover border-2 border-white mb-4"
                />
                <p className="mb-4">
                  An AI powered content generation with tinyMCE text editor for better posting. A blog app where you can share, comment, search and like blog post in
                  your interest.
                </p>
                <div className="mb-4">
                  <span className="text-blue-400 font-bold">STACK:</span>
                  <code className="ml-2"> Vuejs, Nodejs and Supabase.</code>
                </div>
                <div className="flex gap-4">
                  <a
                    href="https://github.com/julesample/connected-blog"
                    className="border-2 border-white px-3 py-1 hover:bg-white hover:text-black flex items-center justify-center gap-2"
                  >
                  <Github :size=15 />
                  Code
                </a>
                <a
                  rel="noopener noreferrer"
                  target="_blank"
                  href="https://connected-blog.vercel.app"
                  className="border-2 border-white px-3 py-1 hover:bg-white hover:text-black flex items-center justify-center gap-2"
                >
                 <ExternalLink :size=15 />
                  Demo
                </a>
              </div>
            </div>
            </div>

            <div className="border-2 border-white">
              <div className="border-b-2 border-white p-4 bg-blue-400 text-black">
                <h3 className="text-xl font-bold">CONNECTED</h3>
              </div>
              <div className="p-6">
                <img
                  :src="connectedDemo"
                  alt="CONNECTED"
                  className="w-full h-48 object-cover border-2 border-white mb-4"
                />
                <p className="mb-4">
              This system is a social media app where users can share posts, comment, like, and chat in real-time.
It’s a hobby project created to express thoughts and connect with others.
Key features include real-time chat, post editing, account blocking, image posting, and activity tracking.
                </p>
                <div className="mb-4">
                  <span className="text-blue-400 font-bold">STACK:</span>
                  <code className="ml-2"> Nextjs and Supabase. </code>
                </div>
                <div className="flex gap-4">
                  <a
                    
                    href="https://github.com/julesample/connected-app"
                    className="border-2 border-white px-3 py-1 hover:bg-white hover:text-black flex items-center justify-center gap-2"
                  >
                   <Github :size=15 />
                  Code
                </a>
                <a
                  rel="noopener noreferrer"
                  target="_blank"
                  href="https://cnnctd.vercel.app"
                  className="border-2 border-white px-3 py-1 hover:bg-white hover:text-black flex items-center justify-center gap-2"
                >
                  <ExternalLink :size=15 />
                  Demo
                </a>
              </div>
            </div>
            </div>

            <div className="border-2 border-white">
              <div className="border-b-2 border-white p-4 bg-blue-400 text-black">
                <h3 className="text-xl font-bold">QR GENERATOR</h3>
              </div>
              <div className="p-6">
                <img
                  :src="qr"
                  alt="QR GENERATOR"
                  className="w-full h-48 object-cover border-2 border-white mb-4"
                />
                <p className="mb-4">
                  This system sole purpose is to make QR code and customize them based on client needs.
                </p>
                <div className="mb-4">
                  <span className="text-blue-400 font-bold">STACK:</span>
                  <code className="ml-2"> Nextjs and ShadCN.</code>
                </div>
                <div className="flex gap-4">
                  <a
                    rel="noopener noreferrer"
                    target="_blank"
                    href="https://qrgnrtr.netlify.app"
                    className="border-2 border-white px-3 py-1 hover:bg-white hover:text-black flex items-center gap-2"
                  >
                    <ExternalLink :size=15 />
                    Demo
                  </a>
                </div>
              </div>
            </div>

            <div className="border-2 border-white">
              <div className="border-b-2 border-white p-4 bg-blue-400 text-black">
                <h3 className="text-xl font-bold">WEB-BASED CATERING RESERVATION SYSTEM</h3>
              </div>
              <div className="p-6">
                <img
                  :src="clientIndex"
                  alt="WEB-BASED CATERING RESERVATION SYSTEM"
                  className="w-full h-48 object-cover border-2 border-white mb-4"
                />
                <p className="mb-4">
                  This system automate the typical process of reservation. It also generates banquet contract for the
                  client and send sms to notify customer.
                </p>
                <div className="mb-4">
                  <span className="text-blue-400 font-bold">STACK:</span>
                  <code className="ml-2"> Javascript, Php, Bootstrap, Mysql, Infobip(SMS API).</code>
                </div>
                <div className="flex gap-4">
                  <a
                    rel="noopener noreferrer"
                    target="_blank"
                    href="http://www.ssucateringservice2025.infinityfreeapp.com"
                    className="border-2 border-white px-3 py-1 hover:bg-white hover:text-black flex items-center gap-2"
                  >
                  <ExternalLink :size=15 />
                  Demo
                </a>
              </div>
            </div>
            </div>

 <div className="border-2 border-white">
              <div className="border-b-2 border-white p-4 bg-blue-400 text-black">
                <h3 className="text-xl font-bold">Lozada Construction Aggregates Trading</h3>
              </div>
              <div className="p-6">
                <img
                  :src="construction"
                  alt="Lozada Construction Aggregates Trading"
                  className="w-full h-48 object-cover border-2 border-white mb-4"
                />
                <p className="mb-4">
          The purpose of this system is to inform customers about updated prices and calculate their desired orders. 
          Prices are dynamic based on location, and the system generates a receipt for better overview.
                       
                </p>
                <div className="mb-4">
                  <span className="text-blue-400 font-bold">STACK:</span>
                  <code className="ml-2">
                        Nextjs and Neondb. </code>
                </div>
                <div className="flex gap-4">
                  <a
                    rel="noopener noreferrer"
                    target="_blank"
                    href="https://lozada-construction.vercel.app"
                    className="border-2 border-white px-3 py-1 hover:bg-white hover:text-black flex items-center gap-2"
                  >
                  <ExternalLink :size=15 />
                  Demo
                </a>
              </div>
            </div>
            </div>

             <div className="border-2 border-white">
              <div className="border-b-2 border-white p-4 bg-blue-400 text-black">
                <h3 className="text-xl font-bold">PAGSANGHAN BALLERS</h3>
              </div>
              <div className="p-6">
                <img
                  :src="pagsanghanBallers"
                  alt="CLI Tool Terminal"
                  className="w-full h-48 object-cover border-2 border-white mb-4"
                />
                <p className="mb-4">
                  The overview of this system is to allow managers to make an ensured attendance for each day. Features include; exporting data, adding notes to each player, added graph for better visualization and many more.
                </p>
                <div className="mb-4">
                  <span className="text-blue-400 font-bold">STACK:</span>
                  <code className="ml-2"> Nextjs and Supabase.</code>
                </div>
                <div className="flex gap-4">
                  <a
                    rel="noopener noreferrer"
                    target="_blank"
                    href="https://ballers-attendance.vercel.app"
                    className="border-2 border-white px-3 py-1 hover:bg-white hover:text-black flex items-center gap-2"
                    
                  >
                  <ExternalLink :size=15 />
                  Demo
                </a>
              </div>
            </div>
            </div>

          </div>
        </div>
      </section>
<section id="contact" className="p-6">
  <div className="max-w-6xl mx-auto">
    <h2 className="text-3xl font-bold mb-6 border-b-2 border-white pb-2">CONTACT.SH</h2>
    <div className="border-2 border-white p-8">
      <div className="grid grid-cols-1 md:grid-cols-3 gap-8">
        <div className="text-center flex flex-col items-center">
          <div className="mb-2">
            <Mail :size="40" />
          </div>
          <h3 className="font-bold mb-2">EMAIL</h3>
          <a
            href="mailto:lozadajuleseliot@gmail.com"
            className="border-2 border-white px-4 py-2 hover:bg-white hover:text-black inline-block"
          >
            lozadajuleseliot@email.com
          </a>
        </div>

        <div className="text-center flex flex-col items-center">
          <div className="mb-2">
            <Github :size="40" />
          </div>
          <h3 className="font-bold mb-2">GITHUB</h3>
          <a
            href="https://github.com/julesample"
            className="border-2 border-white px-4 py-2 hover:bg-white hover:text-black inline-block"
            target="_blank"
            rel="noopener noreferrer"
          >
            github.com/jules
          </a>
        </div>

        <div className="text-center flex flex-col items-center">
          <div className="mb-2">
            <Linkedin :size="40" />
          </div>
          <h3 className="font-bold mb-2">LINKEDIN</h3>
          <a
            href="https://www.linkedin.com/in/jules-lozada-26081426a/"
            className="border-2 border-white px-4 py-2 hover:bg-white hover:text-black inline-block"
            target="_blank"
            rel="noopener noreferrer"
          >
            linkedin.com/in/jules
          </a>
        </div>
      </div>

      <div className="mt-8 text-center">
        <p className="text-blue-400 font-bold">
          $ echo "Lets build your ideas into a reality."
        </p>
      </div> 
    </div>
  </div>
</section>


      <footer className="border-t-4 border-blue-400 p-6 text-center">
        <p className="text-blue-400">© 2025 Jules | ASPIRING DEVELOPER </p>
      </footer>
    </div>
</template>

<style scoped></style>
