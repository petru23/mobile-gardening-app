# Mobile Gardening App

A comprehensive mobile application connecting consumers with landscaping and gardening service providers.

## Project Overview

**Client:** Maroons IT Solutions  
**Timeline:** September 2025 - December 2025 (4 months)  
**Methodology:** Agile Development with 2-week sprints  
**Team Size:** 5 members (Project Manager + 4 developers)

## Features

- **User Management**: Customer and service provider registration/authentication
- **Service Discovery**: Browse available landscaping and gardening services
- **Booking System**: Schedule appointments with service providers
- **Payment Integration**: Secure payment processing via Stripe API
- **Review System**: Customer feedback and rating system
- **Educational Content**: Tips and advice for gardening and landscaping
- **GPS Integration**: Location-based service provider matching

## Technical Stack

- **Frontend**: React Native (iOS/Android)
- **Backend**: Node.js with Express.js
- **Database**: Azure SQL Database
- **Cloud Platform**: Microsoft Azure
- **Payment**: Stripe API
- **Maps**: Google Maps API
- **Authentication**: OAuth 2.0
- **Notifications**: Firebase Cloud Messaging

## Repository Structure

```
mobile-gardening-app/
├── frontend/           # React Native mobile app
├── backend/            # Node.js API server
├── documentation/      # Project specifications and design docs
├── testing/           # Test cases and automated testing scripts
└── deployment/        # Configuration files and deployment scripts
```

## Development Phases

### Phase 1: Foundation (Sprints 1-3)
- User authentication system
- Basic UI/UX implementation
- Service provider directory
- Core booking functionality
- **Milestone**: Working prototype delivery

### Phase 2: Enhancement (Sprints 4-7)
- Recommendation engine
- Educational content management
- Payment system integration
- Advanced features and polish

## Version Control Strategy

- **main**: Production-ready code
- **develop**: Integration branch
- **feature/**: Individual feature development
- **release/**: Sprint release preparation
- **hotfix/**: Critical bug fixes

## Installation & Setup

```bash
# Clone repository
git clone https://github.com/username/mobile-gardening-app.git

# Frontend setup
cd frontend
npm install
npx react-native run-ios    # iOS
npx react-native run-android # Android

# Backend setup
cd backend
npm install
npm start
```

## Sprint Schedule

| Sprint | Duration | Focus Area |
|--------|----------|------------|
| Sprint 1 | Sep 16-29 | User Authentication & Basic UI |
| Sprint 2 | Sep 30 - Oct 13 | Service Provider Directory |
| Sprint 3 | Oct 14-27 | Booking System Core |
| Sprint 4 | Nov 4-17 | Recommendation Engine |
| Sprint 5 | Nov 18 - Dec 1 | Educational Content System |
| Sprint 6 | Dec 2-15 | Payment Integration |
| Sprint 7 | Dec 16-29 | Advanced Features & Polish |

## Contributing

1. Create feature branch from `develop`
2. Implement changes with comprehensive testing
3. Submit pull request with detailed description
4. Code review required before merge
5. All commits must include meaningful messages

## Quality Standards

- Minimum 80% test coverage
- ESLint compliance for JavaScript
- Mandatory code reviews
- Automated testing on all PRs
- Performance testing for API endpoints

## Project Management

- **Tool**: Microsoft Project
- **Methodology**: Agile/Scrum
- **Sprint Duration**: 2 weeks
- **Communication**: Microsoft SharePoint
- **Daily Standups**: 9:00 AM AEST

## Contact

**Project Manager**: [Your Name]  
**Organization**: Maroons IT Solutions  
**Location**: Queensland, Australia

## License

This project is proprietary software developed for Maroons IT Solutions.

---

**Status**: In Development  
**Last Updated**: August 2025
