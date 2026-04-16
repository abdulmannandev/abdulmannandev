<pre>
  Initializing Node.js Runtime...
  
  Runtime is ready
  To contact me, please send me a message to `<a href="mailto:mannanabdul417@gmail.com">mannanabdul417@gmail.com</a>`.
  For more details, please visit <a href="https://www.upwork.com/freelancers/~01232ede4af22a157e">Upwork</a>
  MacBook-Pro:~ abdulmannan$ cat ./main.ts </pre>

```typescript

type Status = {
  learning: boolean;
  openToWork: boolean;
};

type Contact = {
  email: string;
  linkedin: string;
  github: string;
  portfolio?: string;
  upwork?: string;
};

type Skills = {
  frontend: string[];
  backend: string[];
  devops: string[];
  web3: string[];
  tools: string[];
};

type Project = {
  name: string;
  role: string;
  tech: readonly string[];
  description?: string;
  link?: string;
};

type Developer = {
  name: string;
  role: string;
  experience: string;
  contact: Contact;
  skills: Skills;
  projects: readonly Project[];
  status: Status;
};

export const developerProfile = {
  name: 'Abdul Mannan',
  role: 'Full Stack Developer',
  experience: '5+ years',
  contact: {
    email: 'mannanabdul417@gmail.com',
    linkedin: 'https://www.linkedin.com/in/abdul-mannan-163337152/',
    github: 'https://github.com/abdulmannandev',
    upwork: 'https://www.upwork.com/freelancers/~01232ede4af22a157e',
  },
  skills: {
    frontend: [
      'React.js',
      'TypeScript',
      'Vue.js',
      'JavaScript (ES6+)',
      'HTML5',
      'CSS3',
      'Tailwind',
    ],
    backend: [
      'PHP',
      'Laravel',
      'WordPress (Custom Themes & Plugins)',
      'REST APIs',
      'WooCommerce API',
    ],
    devops: ['Docker', 'Linux', 'CI/CD', 'Nginx', 'Apache'],
    web3: ['ethers.js', 'Smart Contracts', 'Sepolia / Ethereum', 'Aave Integration'],
    tools: ['Git', 'Webpack', 'Firebase', 'Postman', 'Figma'],
  },
  projects: [
    {
      name: 'CombatGo Frontend',
      role: 'React Developer',
      tech: ['React.js', 'Webpack', 'REST API'],
      description: 'Built scalable frontend with optimized performance',
      link: 'https://web.combatgo.app/',
    },
    {
      name: 'MascaraWorld',
      role: 'WordPress Developer',
      tech: ['WordPress', 'WooCommerce', 'Custom Theme'],
      description: 'Gaming-themed eCommerce store with custom UI/UX',
    },
    {
      name: 'Freelancer Automation (watch_dog)',
      role: 'Full Stack Developer',
      tech: ['Node.js', 'Automation', 'AI'],
      description: 'Automated bidding system for Upwork & Freelancer',
    },
    {
      name: 'Crypto Signals App',
      role: 'Full Stack Developer',
      tech: ['React Native', 'Firebase', 'AI'],
      description: 'AI-based crypto signals with push notifications',
    },
    {
      name: 'Catalog System (ACF + Filters)',
      role: 'WordPress Engineer',
      tech: ['ACF', 'Custom Post Types', 'Filtering System'],
      description: 'Advanced catalog with dynamic filters and specs',
    },
  ],
  status: {
    learning: true,
    openToWork: true,
  },
} satisfies Developer;

export type { Developer, Contact, Skills, Project, Status };

```
<pre> MacBook-Pro:~ abdulmannandev$ </pre>
