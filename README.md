# Just-Learn: AI Workshop Management System

![EverJust Logo](./assets/everjust_logo.png)

## Overview

**Just-Learn** is a comprehensive AI workshop management system designed to streamline the planning, execution, and follow-up of educational AI workshops. Built with modern web technologies and featuring a clean, accessible interface with dark/light theme support.

## 🌐 Live Demo

Visit the live application at: **[learn.everjust.app](https://learn.everjust.app)**

## ✨ Key Features

### 📊 Dashboard & Analytics
- Real-time event metrics and progress tracking
- Visual progress indicators and completion percentages
- Quick navigation to all management sections

### 👥 Attendee Management
- Complete registration system with participant tracking
- Communication workflow templates
- Waitlist management and capacity planning
- Export functionality for participant lists

### 💰 Financial Management
- Comprehensive budget tracking with expense categorization
- Revenue analysis and break-even calculations
- Payment status monitoring and vendor management
- Real-time profit margin calculations

### 📚 Content Organization
- Learning objectives and curriculum planning
- Interactive activity management
- AI tool integration tracking
- Resource distribution checklists

### 📢 Marketing Campaign
- Multi-channel promotion tracking (Facebook, LinkedIn, Email)
- Performance analytics and conversion metrics
- Partnership management system
- Content library organization

### 🎯 Resource Planning
- Equipment and material checklists
- Setup timeline management
- Environmental requirement tracking
- Contingency planning tools

### 📧 Post-Event Engagement
- Automated follow-up sequence templates
- Feedback collection and analysis
- Community building tools
- Long-term engagement tracking

## 🎨 Design Features

- **Modern UI**: Inspired by shadcn design system with clean, minimal aesthetics
- **Dark/Light Theme**: Toggle between themes with persistent preference storage
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Accessibility**: ARIA labels, keyboard navigation, and screen reader support
- **Interactive Elements**: Hover states, focus indicators, and smooth transitions

## 🛠 Technology Stack

- **Frontend**: Vanilla HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Custom CSS with CSS Variables for theming
- **Storage**: Local Storage for data persistence
- **Hosting**: GitHub Pages
- **Domain**: Custom domain via GoDaddy DNS

## 📁 Project Structure

```
just-learn/
├── index.html                          # Main application file
├── assets/
│   └── everjust_logo.png               # EverJust branding
├── attendees/
│   └── registration-tracker.md         # Attendee management templates
├── content/
│   └── workshop-outline.md             # Workshop content planning
├── marketing/
│   └── promotion-templates.md          # Marketing campaign materials
├── planning/
│   ├── agenda-template.md              # Event planning resources
│   ├── budget-tracker.md               # Financial planning templates
│   └── event-checklist.md              # Comprehensive planning checklist
├── resources/
│   └── materials-checklist.md          # Resource and logistics planning
├── follow-up/
│   └── post-event-templates.md         # Post-event engagement tools
└── project-just-learn-wireframes.drawio # Design wireframes and mockups
```

## 🚀 Quick Start

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/ever-just/just-learn.git
   cd just-learn
   ```

2. Open `index.html` in your browser or serve with a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

3. Navigate to `http://localhost:8000` to access the application

### Deployment

The application is automatically deployed via GitHub Pages when changes are pushed to the `main` branch. The custom domain `learn.everjust.app` is configured via DNS CNAME record.

## 📊 Data Management

The application uses browser Local Storage to persist data including:
- Event configuration and settings
- Attendee registration information
- Budget and expense tracking
- Task completion status
- Theme preferences

## 🎯 Use Cases

### Event Organizers
- Plan and execute AI workshops with comprehensive tracking
- Manage participant registration and communication
- Track budgets and optimize event profitability
- Coordinate resources and logistics effectively

### Educational Institutions
- Organize AI literacy programs and workshops
- Track student engagement and learning outcomes
- Manage educational resources and materials
- Build sustainable AI education communities

### Corporate Training
- Implement AI adoption workshops for teams
- Track training ROI and participant progress
- Manage corporate education initiatives
- Build internal AI competency programs

## 🤝 Contributing

We welcome contributions to improve Just-Learn! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**: `git checkout -b feature/amazing-feature`
3. **Make your changes** with proper testing
4. **Commit your changes**: `git commit -m 'Add amazing feature'`
5. **Push to the branch**: `git push origin feature/amazing-feature`
6. **Open a Pull Request**

### Development Guidelines

- Follow semantic HTML practices
- Maintain accessibility standards
- Test across different browsers and devices
- Update documentation for new features
- Ensure responsive design principles

## 📋 Roadmap

- [ ] Integration with calendar systems (Google Calendar, Outlook)
- [ ] Email automation for attendee communications
- [ ] Advanced analytics and reporting features
- [ ] Multi-language support
- [ ] Integration with payment processing systems
- [ ] Mobile app companion
- [ ] API for third-party integrations

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🏢 About EverJust

Just-Learn is developed by **EverJust**, a technology company focused on creating innovative solutions for education and professional development in the AI era.

- **Website**: [everjust.app](https://everjust.app)
- **Contact**: Learn more about our AI education initiatives

## 📞 Support

For questions, bug reports, or feature requests:

- **GitHub Issues**: [Create an issue](https://github.com/ever-just/just-learn/issues)
- **Email**: Contact via EverJust website
- **Documentation**: Comprehensive guides available in the `/docs` folder

---

**Built with ❤️ by the EverJust team**

*Empowering AI education and workshop management for the modern era*