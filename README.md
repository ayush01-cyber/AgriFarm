# Agri Farm Smart Farm Management System

A comprehensive farm management system built with modern web technologies to help farmers manage their operations efficiently and safely. The system provides bilingual support (English and Hindi) and focuses on safety, equipment management, and agricultural marketplace integration.

## Core Features

### Safety & Health Management
- **Equipment Safety Training**
  - Pre-operation safety checks
  - Safe operation procedures
  - Power Take-Off (PTO) safety guidelines
  - Equipment maintenance protocols
  - Interactive safety guides with animations

- **PPE Management**
  - Visual guides for safety equipment
  - Usage guidelines and maintenance tracking
  - Replacement indicators
  - Compliance checklists (Daily, Weekly, Monthly)
  - Equipment status monitoring

- **Chemical Safety**
  - Storage guidelines
  - Application procedures
  - Protective measures
  - Safety protocols

### Agricultural Marketplace
- **Product Management**
  - Categorized listings (Seeds, Fertilizers, Pesticides)
  - Detailed product specifications
  - Price range filtering
  - Sorting options (Best Selling, Highest Rated, New Arrivals)
  - Bilingual product descriptions

- **Shopping Features**
  - Shopping cart functionality
  - Quantity management
  - Direct purchase options
  - Order tracking

- **Review System**
  - Product ratings
  - Interactive rating interface
  - User feedback submission
  - Review management

### Financial Management
- **Scheme Management**
  - Income-based scheme filtering
  - Detailed eligibility criteria
  - Pros and cons analysis
  - Direct links to official scheme websites

- **Financial Advisory**
  - Quick question system
  - Common queries handling
  - Scheme-specific information
  - Interactive Q&A interface

### Farm Operations
- **Soil Analysis**
  - Weather condition monitoring
  - Soil condition assessment
  - Real-time data visualization
  - Environmental impact analysis

### System Features
- **Multilingual Support**
  - Complete interface in English and Hindi
  - Localized content and descriptions
  - Language-specific formatting

- **User Interface**
  - Responsive design
  - Interactive animations
  - Loading states
  - Error handling
  - Mobile-friendly layout

## Tech Stack

- React 19 with TypeScript
- Vite for build tooling
- TailwindCSS for styling
- Framer Motion for animations
- ESLint for code quality

## Getting Started

### Prerequisites

- Node.js (Latest LTS version recommended)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Agri Farm-Smart-Farm-Management-System-EPICS-Project.git
cd Agri Farm-Smart-Farm-Management-System-EPICS-Project
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run lint` - Run ESLint
- `npm run preview` - Preview production build

## Project Structure

```
src/
  ├── components/
  │   ├── SafetyTraining/    # Safety training modules
  │   ├── PPE/               # PPE management components
  │   ├── ChemicalSafety/    # Chemical safety guidelines
  │   ├── market/            # Marketplace components
  │   └── common/            # Shared components
  ├── pages/                 # Main application pages
  ├── data/                  # Static data and configurations
  ├── translations/          # Language files
  ├── styles/               # Global styles and themes
  ├── types/                # TypeScript definitions
  ├── App.tsx              # Root component
  └── main.tsx             # Entry point
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Built with [Vite](https://vitejs.dev/)
- Styled with [TailwindCSS](https://tailwindcss.com/)
- Icons from [Lucide React](https://lucide.dev/)
