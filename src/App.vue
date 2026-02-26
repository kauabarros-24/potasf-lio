<template>
  <div class="wrapper">
    <main class="container">
      <!-- Avatar e cabeçalho -->
      <div class="profile">
        <div class="avatar">
          <img src="/potas.jpg" alt="Avatar de Seu Nome" />
        </div>
        <h1>Kauã Martins Barros</h1>
        <p class="bio">Softwar Developer | I make things think | AI Enthusiast</p>
      </div>

      <div class="links">
        <a href="https://github.com/kauabarros-24" target="_blank" rel="noopener noreferrer" class="link-card" aria-label="GitHub">
          <svg class="icon" viewBox="0 0 24 24" width="28" height="28" aria-hidden="true">
            <path fill="currentColor" d="M12 2C6.477 2 2 6.477 2 12c0 4.42 2.865 8.166 6.839 9.489.5.092.682-.217.682-.482 0-.237-.008-.866-.013-1.7-2.782.603-3.369-1.34-3.369-1.34-.454-1.156-1.11-1.462-1.11-1.462-.908-.62.069-.608.069-.608 1.003.07 1.531 1.03 1.531 1.03.892 1.529 2.341 1.087 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.11-4.555-4.943 0-1.091.39-1.984 1.03-2.682-.103-.253-.447-1.27.098-2.646 0 0 .84-.269 2.75 1.025.8-.223 1.65-.334 2.5-.334.85 0 1.7.111 2.5.334 1.91-1.294 2.75-1.025 2.75-1.025.545 1.376.201 2.393.099 2.646.64.698 1.03 1.591 1.03 2.682 0 3.841-2.337 4.687-4.565 4.935.359.309.678.919.678 1.852 0 1.336-.012 2.415-.012 2.743 0 .267.18.578.688.48C19.138 20.161 22 16.418 22 12c0-5.523-4.477-10-10-10z"/>
          </svg>
          <span class="link-title">GitHub</span>
          <span class="link-description">My projects, my life</span>
        </a>

        <!-- LinkedIn -->
        <a href="https://www.linkedin.com/in/kau%C3%A3-martins-barros-b1757b303/" target="_blank" rel="noopener noreferrer" class="link-card" aria-label="LinkedIn">
          <svg class="icon" viewBox="0 0 24 24" width="28" height="28" aria-hidden="true">
            <path fill="currentColor" d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
          </svg>
          <span class="link-title">LinkedIn</span>
          <span class="link-description">Do you will like to connect with me?</span>
        </a>

        <!-- Instagram -->
        <a href="https://instagram.com/kaua.barr0s" target="_blank" rel="noopener noreferrer" class="link-card" aria-label="Instagram">
          <svg class="icon" viewBox="0 0 24 24" width="28" height="28" aria-hidden="true">
            <path fill="currentColor" d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zM5.838 12a6.162 6.162 0 1112.324 0 6.162 6.162 0 01-12.324 0zM12 16a4 4 0 110-8 4 4 0 010 8zm4.965-10.405a1.44 1.44 0 112.881.001 1.44 1.44 0 01-2.881-.001z"/>
          </svg>
          <span class="link-title">Instagram</span>
          <span class="link-description">My day</span>
        </a>

        <!-- Hugging Face (ícone de robô/cérebro) -->
        <a href="https://huggingface.co/KaliumPotas" target="_blank" rel="noopener noreferrer" class="link-card" aria-label="Hugging Face">
          <svg class="icon" viewBox="0 0 24 24" width="28" height="28" aria-hidden="true">
            <path fill="currentColor" d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8zm-3-8c-.55 0-1 .45-1 1s.45 1 1 1 1-.45 1-1-.45-1-1-1zm6 0c-.55 0-1 .45-1 1s.45 1 1 1 1-.45 1-1-.45-1-1-1zm-3 4c-1.5 0-2.8.8-3.5 2h7c-.7-1.2-2-2-3.5-2z"/>
          </svg>
          <span class="link-title">Hugging Face</span>
          <span class="link-description">Models, datasets and spaces</span>
        </a>

        <!-- E-mail -->
        <a href="mailto:martinsbarroskaua@gmail.com" class="link-card" aria-label="Enviar e-mail">
          <svg class="icon" viewBox="0 0 24 24" width="28" height="28" aria-hidden="true">
            <path fill="currentColor" d="M20 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/>
          </svg>
          <span class="link-title">E-mail</span>
          <span class="link-description">Send a email to me</span>
        </a>
      </div>

      <footer class="footer">
        <p>© 2025 Kauã Barros. All rights reserved</p>
      </footer>
    </main>
  </div>
</template>
<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.wrapper {
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  background: linear-gradient(145deg, #f0f4f8 0%, #d9e2ec 100%);
  font-family: 'Inter', system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
  padding: 1rem;
}

.container {
  max-width: 520px;
  width: 100%;
  background: rgba(255, 255, 255, 0.75);
  backdrop-filter: blur(12px);
  -webkit-backdrop-filter: blur(12px);
  border-radius: 40px;
  box-shadow: 0 30px 60px -15px rgba(0, 0, 0, 0.2);
  padding: 2.5rem 2rem;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  border: 1px solid rgba(255, 255, 255, 0.5);
}

.container:hover {
  transform: scale(1.02);
  box-shadow: 0 35px 70px -15px rgba(0, 0, 0, 0.25);
}

.profile {
  text-align: center;
  margin-bottom: 2.5rem;
}

.avatar {
  width: 120px;
  height: 120px;
  margin: 0 auto 1.5rem;
  border-radius: 50%;
  overflow: hidden;
  border: 4px solid white;
  box-shadow: 0 15px 20px -8px rgba(0, 0, 0, 0.15);
  transition: transform 0.2s;
}

.avatar:hover {
  transform: scale(1.05);
}

.avatar img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}

h1 {
  font-size: 2.2rem;
  font-weight: 600;
  color: #0b1e33;
  margin-bottom: 0.35rem;
  letter-spacing: -0.02em;
}

.bio {
  font-size: 1.1rem;
  color: #334e68;
  font-weight: 400;
  line-height: 1.5;
}

.links {
  display: flex;
  flex-direction: column;
  gap: 1.2rem;
  margin-bottom: 2rem;
}

.link-card {
  display: flex;
  align-items: center;
  gap: 1.2rem;
  padding: 1rem 1.5rem;
  background: white;
  border-radius: 28px;
  text-decoration: none;
  color: #1e293b;
  border: 1px solid #e9eef2;
  transition: all 0.25s;
  box-shadow: 0 5px 10px -3px rgba(0, 0, 0, 0.05);
}

.link-card:hover {
  background: #ffffff;
  border-color: #9aa9b9;
  transform: translateY(-4px);
  box-shadow: 0 20px 25px -10px rgba(0, 0, 0, 0.15);
}

.icon {
  width: 28px;
  height: 28px;
  flex-shrink: 0;
  color: #2c3e50;
  transition: color 0.2s;
}

.link-card:hover .icon {
  color: #0a1a2b;
}

.link-title {
  font-weight: 600;
  font-size: 1.15rem;
  margin-right: auto;
  color: #0b1e33;
}

.link-description {
  font-size: 0.9rem;
  color: #546e7a;
  display: none; /* Escondido em telas pequenas por padrão */
}

@media (min-width: 450px) {
  .link-description {
    display: inline;
    margin-left: auto;
    white-space: nowrap;
  }
}

.footer {
  text-align: center;
  margin-top: 1.5rem;
  color: #62748c;
  font-size: 0.85rem;
  opacity: 0.8;
}

/* Ajuste para telas muito pequenas */
@media (max-width: 380px) {
  .container {
    padding: 1.5rem 1rem;
  }
  h1 {
    font-size: 1.8rem;
  }
  .bio {
    font-size: 0.95rem;
  }
  .link-card {
    padding: 0.9rem 1.2rem;
  }
  .icon {
    width: 24px;
    height: 24px;
  }
  .link-title {
    font-size: 1rem;
  }
}
</style>