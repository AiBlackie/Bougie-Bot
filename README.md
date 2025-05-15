### Bougie Billionaire Chatbot - Luxury Barbados Concierge

A sophisticated AI-powered concierge application specializing in luxury Barbados experiences, built with Next.js, React, and Tailwind CSS.

## Overview

The Bougie Billionaire Chatbot is an AI-powered luxury concierge application designed to provide comprehensive information and assistance for high-end experiences in Barbados. The application features a sleek, modern interface with a chat system, interactive map, and detailed location directory.

## Features

### AI Concierge Chat

- Intelligent chatbot with expertise in Barbados luxury offerings
- Real-time responses to queries about accommodations, dining, activities, and more
- Support for multiple languages with tiered subscription access
- Feedback system for continuous improvement


### Interactive Map

- Satellite view of Barbados with luxury locations marked
- Detailed information about hotels, restaurants, attractions, and essential services
- Category filtering and search functionality
- Location highlighting when mentioned in chat


### Locations Directory

- Comprehensive database of luxury establishments and essential services
- Categorized listings with detailed information
- Search and filter capabilities
- Direct links to view locations on the map


### Weather & Time Display

- Real-time Barbados weather information
- Local time display with automatic updates
- Weather forecasts for trip planning


### Subscription System

- Tiered access model (Free, Language Plus, Global Luxury)
- Premium features including multilingual support and personalized recommendations
- Secure upgrade request system


### Admin Dashboard

- Feedback monitoring and analysis
- Subscription upgrade request management
- User analytics and insights


## Technology Stack

- **Frontend**: React, Next.js, Tailwind CSS
- **UI Components**: shadcn/ui component library
- **Maps**: Dynamic map integration with location markers
- **State Management**: React hooks for local state management
- **API Integration**: OpenAI API for AI chat capabilities
- **Authentication**: Simple admin authentication for dashboard access


## Getting Started

### Prerequisites

- Node.js 18+ and npm/pnpm
- OpenAI API key for AI functionality


### Installation

1. Clone the repository


```shellscript
git clone https://github.com/your-username/bougie-billionaire-chatbot.git
cd bougie-billionaire-chatbot
```

2. Install dependencies


```shellscript
npm install
# or
pnpm install
```

3. Set up environment variables
Create a `.env.local` file in the root directory with the following:


```plaintext
OPENAI_API_KEY=your_openai_api_key_here
```

4. Run the development server


```shellscript
npm run dev
# or
pnpm dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser


## Usage

### Chat Interface

- Type questions about Barbados luxury experiences in the chat input
- The AI will respond with detailed information and recommendations
- Click on mentioned locations to view them on the map


### Map Navigation

- Browse the interactive map to discover luxury locations
- Click on markers to view detailed information
- Use the category filters to focus on specific types of establishments


### Locations Directory

- Browse all locations by category
- Search for specific locations or services
- Click on locations to view them on the map


### Subscription Management

- Access the subscription dialog to view available plans
- Upgrade to access premium features like multilingual support


## Admin Access

To access the admin dashboard:

1. Navigate to `/admin/dashboard` or `/admin/feedback`
2. Enter the admin key when prompted (default: "bougie-admin-key")
3. View feedback data and subscription upgrade requests


## Customization

- Modify the locations data in `data/locations.ts` to update the map and directory
- Adjust the subscription tiers in `components/subscription-manager.tsx`
- Customize the chat system prompts in `app/api/chat/route.ts`


## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- OpenAI for the AI capabilities
- Vercel for hosting and deployment
- shadcn/ui for the component library
- All the luxury establishments in Barbados that inspired this project
