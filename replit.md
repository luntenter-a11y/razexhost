# RazeXHOST - Game & VPS Hosting Website

## Overview
RazeXHOST is a modern hosting platform website featuring game server hosting, Discord bot hosting, and VPS hosting services. The design uses a dark theme with red and aqua accent colors for a gaming/tech aesthetic.

## Current State
Frontend prototype completed with separate pages for each hosting service:
- Home page with service overview cards
- Minecraft hosting page (/minecraft) with Minecraft-themed background
- Discord Bot hosting page (/discordbot)
- VPS hosting page (/vps) with region/CPU selection

## Routes
- `/` - Home landing page
- `/minecraft` - Minecraft server hosting plans
- `/discordbot` - Discord bot hosting plans
- `/vps` - VPS hosting plans with region/CPU selection

## Project Structure
```
client/src/
├── components/
│   ├── Navbar.tsx        - Fixed navigation with dropdown menus
│   ├── Hero.tsx          - Hero section with background image
│   ├── PricingCard.tsx   - Reusable pricing card component
│   ├── Features.tsx      - Features grid section
│   ├── CTASection.tsx    - Call-to-action section
│   ├── Footer.tsx        - Site footer with logo
│   └── examples/         - Component examples for preview
├── pages/
│   ├── Home.tsx          - Main landing page with service cards
│   ├── Minecraft.tsx     - Minecraft hosting page
│   ├── DiscordBot.tsx    - Discord bot hosting page
│   ├── VPS.tsx           - VPS hosting page
│   └── not-found.tsx     - 404 page
└── index.css             - Global styles with theme colors
```

## Theme Colors
- Primary: Red (hsl 0 85% 50%)
- Accent: Aqua/Cyan (hsl 180 70% 50%)
- Background: Pure black (hsl 0 0% 0%)
- Cards: Dark gray (hsl 0 0% 6%)

## Services Offered
1. **Game Hosting**
   - Minecraft (8 plans: Grass to Bedrock)
   - RUST (Coming Soon)

2. **Other Hosting**
   - Discord Bot Hosting (8 plans: Hobby to Ultimate)
   - Web Hosting (Coming Soon)

3. **Compute Hosting**
   - VPS Hosting (8 plans per region/CPU combination)
   - VDS Hosting (Coming Soon)

## Regions Available
- Singapore
- Germany
- India

## CPU Options
- Intel
- AMD

## Recent Changes
- December 10, 2025: Initial frontend prototype created

## User Preferences
- Dark theme with red and aqua accents
- Gaming/tech aesthetic
- Black background base
