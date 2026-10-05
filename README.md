import React from 'react';

const GithubProfile = () => {
  return (
    <div className="min-h-screen bg-[#0D1117] text-white flex flex-col items-center justify-center p-6 font-mono">
      
      {/* Header Animation */}
      <h1 className="text-3xl md:text-4xl font-bold text-cyan-400 mb-8 animate-pulse">
        Backend Developer 👨‍💻
      </h1>

      {/* Terminal Style About Me */}
      <div className="bg-[#161B22] border border-gray-700 rounded-lg shadow-xl p-6 w-full max-w-2xl mb-8">
        <div className="flex space-x-2 mb-4">
          <div className="w-3 h-3 rounded-full bg-red-500"></div>
          <div className="w-3 h-3 rounded-full bg-yellow-500"></div>
          <div className="w-3 h-3 rounded-full bg-green-500"></div>
        </div>
        <pre className="text-sm text-gray-300 whitespace-pre-wrap">
{`role: "Backend Developer & CS Student"
focus: ["System Design", "API Development", "Database Optimization"]
languages: ["Python", "TypeScript", "JavaScript", "C#", "C++"]
databases: ["PostgreSQL", "MongoDB", "MySQL"]`}
        </pre>
      </div>

      {/* Tech Stack Badges */}
      <div className="flex flex-wrap justify-center gap-2 mb-8">
        {['Python', 'TypeScript', 'C#', 'C++', 'Node.js', 'PostgreSQL', 'MongoDB'].map((tech) => (
          <span key={tech} className="px-3 py-1 bg-[#21262D] border border-gray-600 text-gray-300 text-sm rounded-md hover:border-cyan-400 hover:text-cyan-400 transition-colors cursor-default">
            {tech}
          </span>
        ))}
      </div>

      {/* Contact Buttons */}
      <div className="flex flex-wrap justify-center gap-4">
        <a 
          href="https://github.com/AmirRedox2008" 
          target="_blank" 
          rel="noopener noreferrer"
          className="flex items-center gap-2 bg-gray-800 hover:bg-gray-700 border border-gray-600 text-white px-4 py-2 rounded-md transition-all hover:scale-105"
        >
          <svg className="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"><path d="M12 0C5.37 0 0 5.37 0 12c0 5.31 3.435 9.795 8.205 11.385.6.105.825-.255.825-.57 0-.285-.015-1.23-.015-2.235-3.015.555-3.795-.735-4.035-1.41-.135-.345-.72-1.41-1.23-1.695-.42-.225-1.02-.78-.015-.795.945-.015 1.62.87 1.845 1.23 1.08 1.815 2.805 1.305 3.495.99.105-.78.42-1.305.765-1.605-2.67-.3-5.46-1.335-5.46-5.925 0-1.305.465-2.385 1.23-3.225-.12-.3-.54-1.53.12-3.18 0 0 1.005-.315 3.3 1.23.96-.27 1.98-.405 3-.405s2.04.135 3 .405c2.295-1.555 3.3-1.23 3.3-1.23.66 1.65.24 2.88.12 3.18.765.84 1.23 1.92 1.23 3.225 0 4.605-2.805 5.625-5.475 5.925.435.375.81 1.095.81 2.22 0 1.605-.015 2.895-.015 3.3 0 .315.225.69.825.57A12.02 12.02 0 0024 12c0-6.63-5.37-12-12-12z"/></svg>
          GitHub
        </a>
        <a 
          href="https://t.me/Redox086" 
          target="_blank" 
          rel="noopener noreferrer"
          className="flex items-center gap-2 bg-blue-600 hover:bg-blue-500 px-4 py-2 rounded-md transition-all hover:scale-105"
        >
          <svg className="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"><path d="M12 0C5.373 0 0 5.373 0 12s5.373 12 12 12 12-5.373 12-12S18.627 0 12 0zm5.894 8.221l-1.97 9.28c-.145.658-.537.818-1.084.508l-3-2.21-1.446 1.394c-.14.18-.357.295-.6.295-.002 0-.003 0-.005 0l.213-3.054 5.56-5.022c.24-.213-.054-.334-.373-.121l-6.869 4.326-2.972-.924c-.64-.203-.658-.643.135-.953l11.566-4.458c.538-.196 1.006.128.832.941z"/></svg>
          Telegram
        </a>
        <a 
          href="mailto:amirdrgo@gmail.com" 
          className="flex items-center gap-2 bg-red-600 hover:bg-red-500 px-4 py-2 rounded-md transition-all hover:scale-105"
        >
          <svg className="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"><path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/></svg>
          Gmail
        </a>
      </div>
      
    </div>
  );
};

export default GithubProfile;
