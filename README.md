<pre> Initializing Node.js Runtime... Runtime is ready 🚀 To contact me, please send me a message to `<a href="mailto:mannanabdul417@gmail.com">mannanabdul417@gmail.com</a>`. For more details, please visit <a href="https://www.upwork.com/freelancers/~01232ede4af22a157e">Upwork</a> MacBook-Pro:~ abdulmannan$ cat ./main.ts </pre>

type Status = {
  learning: boolean;
  openToWork: boolean;
};

class Developer {
  constructor(
    public name: string,
    public role: string,
    public experience: string,
    public contact: Contact,
    public skills: Skills,
    public projects: Project[],
    public status: Status
  ) {}
}

class Contact {
  constructor(
    public email: string,
    public linkedin: string,
    public github: string,
    public portfolio?: string
  ) {}
}

class Skills {
  constructor(
    public frontend: string[],
    public backend: string[],
    public devops: string[],
    public web3: string[],
    public tools: string[]
  ) {}
}

class Project {
  constructor(
    public name: string,
    public role: string,
    public tech: string[],
    public description?: string,
    public link?: string
  ) {}
}

// Bootstrapping Abdul Mannan 👨‍💻
const me = new Developer(
  'Abdul Mannan',
  'Full Stack Developer',
  '5+ years',
  new Contact(
    'mannanabdul417@gmail.com',
    '[LinkedIn](https://www.linkedin.com/in/abdul-mannan-163337152/)',
    '[GitHub](https://github.com/abdulmannandev)',
    '[Upwork](https://www.upwork.com/freelancers/~01232ede4af22a157e)'
  ),
  new Skills(
    // Frontend
    [
      'React.js',
      'TypeScript',
      'Vue.js',
      'JavaScript (ES6+)',
      'HTML5',
      'CSS3',
      'Tailwind'
    ],
    // Backend
    [
      'PHP',
      'Laravel',
      'WordPress (Custom Themes & Plugins)',
      'REST APIs',
      'WooCommerce API'
    ],
    // DevOps
    [
      'Docker',
      'Linux',
      'CI/CD',
      'Nginx',
      'Apache'
    ],
    // Web3
    [
      'ethers.js',
      'Smart Contracts',
      'Sepolia / Ethereum',
      'Aave Integration'
    ],
    // Tools
    [
      'Git',
      'Webpack',
      'Firebase',
      'Postman',
      'Figma'
    ]
  ),
  [
    new Project(
      'CombatGo Frontend',
      'React Developer',
      ['React.js', 'Webpack', 'REST API'],
      'Built scalable frontend with optimized performance',
      'https://web.combatgo.app/'
    ),
    new Project(
      'MascaraWorld',
      'WordPress Developer',
      ['WordPress', 'WooCommerce', 'Custom Theme'],
      'Gaming-themed eCommerce store with custom UI/UX'
    ),
    new Project(
      'Freelancer Automation (watch_dog)',
      'Full Stack Developer',
      ['Node.js', 'Automation', 'AI'],
      'Automated bidding system for Upwork & Freelancer'
    ),
    new Project(
      'Crypto Signals App',
      'Full Stack Developer',
      ['React Native', 'Firebase', 'AI'],
      'AI-based crypto signals with push notifications'
    ),
    new Project(
      'Catalog System (ACF + Filters)',
      'WordPress Engineer',
      ['ACF', 'Custom Post Types', 'Filtering System'],
      'Advanced catalog with dynamic filters and specs'
    )
  ],
  {
    learning: true,
    openToWork: true
  }
);

// Run 🚀
console.log(me);

<pre> MacBook-Pro:~ abdulmannandev$ </pre>
