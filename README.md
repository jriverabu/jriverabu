import React from 'react';
import { Github, Linkedin, Twitter, Mail, ExternalLink } from 'lucide-react';

function App() {
  return (
    <div className="min-h-screen bg-gradient-to-b from-gray-900 to-gray-800 text-white p-8">
      <div className="max-w-4xl mx-auto space-y-12">
        {/* Header Section */}
        <header className="text-center space-y-6">
          <h1 className="text-4xl md:text-5xl font-bold bg-gradient-to-r from-emerald-400 to-blue-500 text-transparent bg-clip-text">
            Hola, soy Juan David Rivera
          </h1>
          <h2 className="text-xl md:text-2xl text-emerald-400">
            🚀 Experto en Marketing Digital | 🤖 Entusiasta de IA | 💻 Desarrollador
          </h2>
          
          {/* Social Links */}
          <div className="flex justify-center gap-4">
            <a href="https://linkedin.com/in/tu-usuario" className="p-2 bg-blue-600 rounded-full hover:bg-blue-700 transition-colors">
              <Linkedin className="w-6 h-6" />
            </a>
            <a href="https://twitter.com/tu-usuario" className="p-2 bg-sky-500 rounded-full hover:bg-sky-600 transition-colors">
              <Twitter className="w-6 h-6" />
            </a>
            <a href="mailto:tu-email@ejemplo.com" className="p-2 bg-red-600 rounded-full hover:bg-red-700 transition-colors">
              <Mail className="w-6 h-6" />
            </a>
            <a href="https://github.com/tu-usuario" className="p-2 bg-gray-700 rounded-full hover:bg-gray-600 transition-colors">
              <Github className="w-6 h-6" />
            </a>
          </div>
        </header>

        {/* About Me Section */}
        <section className="bg-gray-800 rounded-xl p-6 shadow-xl">
          <h2 className="text-2xl font-bold mb-4 flex items-center gap-2">
            <span className="text-emerald-400">🎯</span> Sobre mí
          </h2>
          <p className="text-gray-300 mb-4">
            Soy un profesional multifacético con experiencia en marketing digital, desarrollo de software e inteligencia artificial. 
            Mi pasión es combinar estas disciplinas para crear soluciones innovadoras y efectivas.
          </p>
          <ul className="space-y-2 text-gray-300">
            <li>🔭 Actualmente estoy trabajando en <span className="text-emerald-400">campañas de marketing impulsadas por IA</span></li>
            <li>🌱 Estoy aprendiendo <span className="text-emerald-400">nuevas aplicaciones de LLMs en marketing</span></li>
            <li>👯 Busco colaborar en <span className="text-emerald-400">proyectos que integren marketing, IA y desarrollo</span></li>
            <li>💬 Pregúntame sobre <span className="text-emerald-400">estrategias de marketing digital, IA generativa, o desarrollo de apps</span></li>
          </ul>
        </section>

        {/* Skills Section */}
        <section className="grid grid-cols-1 md:grid-cols-2 gap-6">
          <div className="bg-gray-800 rounded-xl p-6 shadow-xl">
            <h3 className="text-xl font-bold mb-4 text-emerald-400">Marketing Digital & CRM</h3>
            <div className="flex flex-wrap gap-2">
              {['Google Analytics', 'Google Ads', 'Facebook Ads', 'Mailchimp', 'HubSpot', 'Salesforce'].map((skill) => (
                <span key={skill} className="px-3 py-1 bg-gray-700 rounded-full text-sm">
                  {skill}
                </span>
              ))}
            </div>
          </div>
          
          <div className="bg-gray-800 rounded-xl p-6 shadow-xl">
            <h3 className="text-xl font-bold mb-4 text-emerald-400">Inteligencia Artificial</h3>
            <div className="flex flex-wrap gap-2">
              {['ChatGPT', 'GPT-3', 'DALL·E', 'TensorFlow', 'PyTorch', 'Hugging Face'].map((skill) => (
                <span key={skill} className="px-3 py-1 bg-gray-700 rounded-full text-sm">
                  {skill}
                </span>
              ))}
            </div>
          </div>
        </section>

        {/* Projects Section */}
        <section className="bg-gray-800 rounded-xl p-6 shadow-xl">
          <h2 className="text-2xl font-bold mb-6 text-center">Proyectos Destacados</h2>
          <div className="grid grid-cols-1 md:grid-cols-2 gap-6">
            <div className="bg-gray-700 rounded-lg p-4">
              <h3 className="font-bold mb-2">IA Marketing Analytics</h3>
              <p className="text-gray-300 text-sm mb-4">
                Plataforma de análisis de marketing impulsada por IA para optimización de campañas.
              </p>
              <a href="#" className="text-emerald-400 flex items-center gap-1 text-sm hover:text-emerald-300">
                Ver proyecto <ExternalLink className="w-4 h-4" />
              </a>
            </div>
            <div className="bg-gray-700 rounded-lg p-4">
              <h3 className="font-bold mb-2">Sentiment Analysis Tool</h3>
              <p className="text-gray-300 text-sm mb-4">
                Herramienta de análisis de sentimientos para feedback de clientes.
              </p>
              <a href="#" className="text-emerald-400 flex items-center gap-1 text-sm hover:text-emerald-300">
                Ver proyecto <ExternalLink className="w-4 h-4" />
              </a>
            </div>
          </div>
        </section>

        {/* Contact Section */}
        <footer className="text-center space-y-4">
          <h2 className="text-2xl font-bold text-emerald-400">¡Conectemos!</h2>
          <p className="text-gray-300">
            ¿Interesado en colaborar en proyectos innovadores de marketing digital o IA?<br />
            ¡Contáctame! Siempre estoy abierto a nuevas oportunidades y desafíos emocionantes.
          </p>
          <div className="flex justify-center gap-4">
            <a href="mailto:tu-email@ejemplo.com" 
               className="px-4 py-2 bg-emerald-500 rounded-lg hover:bg-emerald-600 transition-colors flex items-center gap-2">
              <Mail className="w-4 h-4" />
              Contactar
            </a>
          </div>
        </footer>
      </div>
    </div>
  );
}

export default App;
