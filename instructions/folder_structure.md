# NutriChain Fit - Folder Structure

```
src/
├── app/                    # Next.js app directory
│   ├── (auth)/            # Authentication routes
│   ├── (dashboard)/       # Protected dashboard routes
│   └── api/               # API routes
├── components/            # React components
│   ├── common/           # Shared components
│   ├── dashboard/        # Dashboard specific components
│   ├── forms/            # Form components
│   ├── layout/           # Layout components
│   ├── animations/       # GSAP animations components
│   └── web3/             # Blockchain related components
├── contracts/            # Smart contracts
│   ├── cairo/            # Cairo smart contracts
│   │   ├── tokens/     # Token contracts (AgroPuntos)
│   │   ├── core/       # Core platform contracts
│   │   └── interfaces/ # Contract interfaces
│   │   └── scripts/    # Contract deployment scripts
│   ├── core/            # Core platform contracts
│   ├── tokens/          # Token contracts (AgroPuntos)
│   └── interfaces/      # Contract interfaces
├── features/            # Feature-specific code
│   ├── auth/           # Authentication logic
│   ├── nutrition/      # Nutrition tracking
│   ├── training/       # Training programs
│   ├── rewards/        # AgroPuntos system
│   └── marketplace/    # Product marketplace
├── hooks/              # Custom React hooks
│   ├── blockchain/    # Web3 related hooks
│   ├── auth/         # Authentication hooks
│   └── api/          # API related hooks
├── lib/               # Library code
│   ├── starknet/     # Starknet utilities and configurations
│   ├── gsap/         # GSAP animations setup and utilities
│   ├── api/          # API utilities
│   └── pod/          # POD (Proof of Delivery) integration
├── models/           # Data models
│   ├── user/        # User related models
│   ├── product/     # Product related models
│   └── transaction/ # Transaction models
├── services/        # Business logic services
│   ├── blockchain/  # Blockchain services
│   ├── pod/        # POD services
│   └── api/        # External API integrations
├── styles/         # Styling files
│   ├── components/ # Component specific styles
│   ├── theme/     # Theme configuration
│   └── animations/ # GSAP animation styles
├── types/         # TypeScript type definitions
│   ├── api/      # API types
│   ├── starknet/ # Starknet and Cairo types
│   └── models/   # Model type definitions
└── utils/        # Utility functions
    ├── blockchain/ # Blockchain utilities
    ├── validation/ # Form validation
    └── formatting/ # Data formatting

public/            # Static files
├── images/       # Image assets
└── locales/     # Internationalization files

tests/            # Test files
├── unit/        # Unit tests
├── integration/ # Integration tests
└── e2e/        # End-to-end tests

scripts/         # Build and deployment scripts
├── deploy/     # Deployment scripts
└── blockchain/ # Blockchain deployment scripts
```

## Directory Descriptions

### `src/app/`
Next.js app directory containing the main application routes and API endpoints.

### `src/components/`
React components organized by feature and functionality.

### `src/contracts/`
Smart contracts for the blockchain functionality, including AgroPuntos token system.

### `src/features/`
Feature-specific code organized by domain (nutrition, training, rewards, etc.).

### `src/hooks/`
Custom React hooks for reusable logic across components.

### `src/lib/`
Core library code including blockchain and POD integration utilities.

### `src/models/`
Data models and schemas for the application.

### `src/services/`
Business logic and external service integrations.

### `src/styles/`
Styling configuration and component-specific styles.

### `src/types/`
TypeScript type definitions for the entire application.

### `src/utils/`
Utility functions and helpers.

### `public/`
Static assets and localization files.

### `tests/`
Test files organized by type (unit, integration, e2e).

### `scripts/`
Build, deployment, and blockchain-related scripts.
