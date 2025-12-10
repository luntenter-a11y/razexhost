# RazeXHOST Design Guidelines

## Design Approach
Gaming-oriented hosting platform inspired by modern SaaS platforms (Vercel, DigitalOcean) with cyberpunk/gaming aesthetic. Red and aqua accent colors against deep black create high contrast, tech-forward appeal for gamers and developers.

## Core Design Elements

### Typography
- **Headings**: Inter or Sora (bold, 700-800 weight) - geometric, tech-forward
- **Body**: Inter (regular 400, medium 500)
- **Sizes**: H1: 48-64px, H2: 36-48px, H3: 24-32px, Body: 16-18px
- **Style**: Sharp, clean hierarchy with generous letter-spacing on headings (0.02em)

### Layout System
- **Spacing Units**: Tailwind 4, 6, 8, 12, 16, 24 for consistent rhythm
- **Container**: max-w-7xl with px-4 to px-8 padding
- **Section Padding**: py-16 mobile, py-24 desktop
- **Grid**: 3-column for pricing cards (desktop), 1-column mobile

### Component Library

**Navigation**
- Fixed header with glassmorphic background (backdrop-blur)
- Logo left, navigation center/right
- CTA button ("Get Started") with red accent

**Hero Section**
- Full-width with dark gradient background overlaying hero image
- Large headline emphasizing "High-Performance Gaming & VPS Hosting"
- Dual CTAs: Primary (red), Secondary (aqua outline)
- Trust indicators: "99.9% Uptime • DDoS Protection • 24/7 Support"

**Pricing Cards**
- Dark cards with subtle borders (aqua/red glow on hover)
- Plan name, price (large), features list with checkmarks
- Region/CPU selector tabs above VPS cards
- "Coming Soon" badges: aqua text with dark background, subtle glow

**Service Sections**
- Each hosting type gets dedicated section
- Icon + title + description layout
- Cards display in 2-3 column grid
- Minecraft, Discord, VPS sections clearly separated

**Interactive Elements**
- Tab system for VPS region/CPU selection
- Smooth transitions (300ms)
- Hover states: slight scale (1.02), glow effects

**Footer**
- 4-column grid: Company, Services, Support, Legal
- Social icons with aqua hover states
- Newsletter signup with red accent button

## Images

**Hero Image**: Dark server room or abstract digital network visualization with red/aqua lighting effects. Image should convey power, speed, and technology. Apply dark gradient overlay (black to transparent) for text readability.

**Section Backgrounds**: Subtle grid patterns or circuit board textures as section dividers, very low opacity (5-10%)

**Service Icons**: Use Heroicons for consistency - server, globe, cpu, shield icons throughout

## Layout Structure

1. Hero with image background
2. Trust bar (stats/features strip)
3. Game Hosting section (Minecraft cards + RUST coming soon)
4. Other Hosting section (Discord Bot cards + Web coming soon)
5. Compute Hosting section (VPS with region/CPU tabs, 8 plans + VDS coming soon)
6. Features/Benefits section (3-4 columns)
7. CTA section
8. Footer

## Visual Treatment
- **Depth**: Layered cards with subtle shadows
- **Accents**: Red for CTAs/important actions, aqua for highlights/hover states
- **Backgrounds**: Pure black (#000000) base, dark gray (#0a0a0a to #1a1a1a) for cards
- **Borders**: Subtle gray (#2a2a2a) with colored glows on interaction
- **Consistency**: All "Coming Soon" badges styled identically across sections