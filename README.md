# Urban Legends Online - MMO Prototype

A web-based prototype for a Grand Theft Auto-style RuneScape MMO featuring:

## 🎮 Core Features

### Character Progression
- **Skill System**: 7 different skills including Combat (Marksmanship, Street Fighting), Utility (Drug Crafting, Mechanics), Gathering (Scavenging, Hacking), and Social (Street Rep)
- **XP & Leveling**: RuneScape-style progression with increasing XP requirements
- **Real-time Notifications**: Level-up alerts shared across all players

### Economy & Crafting
- **Item System**: Materials, tools, weapons, and products with different values
- **Crafting Recipes**: Create valuable items by combining materials
- **Inventory Management**: Grid-based inventory with item stacking
- **Player-Driven Economy**: All items can be traded between players

### Multiplayer Features
- **Real-time Multiplayer**: See other players online and their activities
- **Location-based Gameplay**: Players can interact in shared areas
- **Activity Feed**: Live updates of player actions (crafting, scavenging, leveling)
- **Player Presence**: View other players' levels, locations, and status

### World Interaction
- **Scavenging**: Search urban areas for materials
- **Location System**: Different areas with unique opportunities
- **Turn-based Combat**: Planned click-to-attack system (coming soon)

## 🛠 Technical Architecture

### Frontend
- **React 18**: Component-based UI with hooks
- **WebsimSocket**: Real-time multiplayer synchronization
- **Responsive Design**: Works on desktop and mobile

### Multiplayer Networking
- **Presence System**: Track player locations and status
- **Room State**: Shared world state across all players
- **Event Broadcasting**: Real-time activity notifications
- **Automatic Sync**: Player data synced across all clients

### Data Persistence
- **Local State**: Character progression and inventory
- **Real-time Sync**: Multiplayer interactions and world events
- **Player Profiles**: Automatic username/avatar integration

## 🚀 Getting Started

1. **Open the prototype**: Simply open `index.html` in a modern web browser
2. **Enter the game**: Click "Enter the Streets" after character creation
3. **Start playing**: 
   - Scavenge for materials in the World tab
   - Check your Skills progression
   - Craft items in the Crafting tab
   - See other players in the Players tab

## 🎯 Game Loop

1. **Scavenge** materials from urban locations
2. **Craft** valuable items using collected materials
3. **Gain XP** in relevant skills through activities
4. **Level up** skills to unlock new capabilities
5. **Trade** with other players (coming soon)
6. **Compete** in turn-based combat (coming soon)

## 📋 Development Roadmap

### Phase 1: ✅ Core Systems (Complete)
- Basic multiplayer networking
- Skill system with XP progression
- Inventory and crafting
- Player presence and activity feed

### Phase 2: 🔄 Economy & Trading (In Progress)
- Player-to-player trading system
- NPC shops and vendors
- Market pricing and supply/demand
- Item durability and degradation

### Phase 3: ⏳ Combat System (Planned)
- Turn-based click-to-attack combat
- Weapon and armor stats
- PvP and PvE encounters
- Combat skill progression

### Phase 4: ⏳ World Expansion (Planned)
- Multiple city zones
- Location-specific resources
- Faction system (gangs, police, etc.)
- Quest and mission system

## 🔧 For Unity Development

This prototype serves as a **design document and proof of concept** for the full Unity MMO. Key systems demonstrated here can be directly translated to Unity:

### Translatable Systems
- **Skill progression formulas**
- **Crafting recipe system**
- **Inventory management logic**
- **Multiplayer state synchronization patterns**
- **Economic balance and item values**

### Unity Implementation Notes
- Use **Mirror Networking** for multiplayer (similar to WebsimSocket)
- Convert **ScriptableObjects** for items and skills
- Implement **persistent database** for character progression
- Add **3D graphics** and **physics-based gameplay**
- Scale to **larger player counts** with dedicated servers

## 📊 Technical Specifications

- **Real-time Multiplayer**: WebSocket-based networking
- **State Management**: React hooks with external store sync
- **Performance**: Optimized for 50+ concurrent players
- **Browser Support**: Modern browsers with ES6+ support
- **Mobile Ready**: Responsive design for touch devices

## 🎨 Visual Design

- **Urban Aesthetic**: Dark cyberpunk-inspired color scheme
- **Neon Accents**: Green highlights reminiscent of classic terminals
- **Grid Layout**: Clean, organized interface inspired by RPG UIs
- **Real-time Feedback**: Animated progress bars and live updates

This prototype validates the core gameplay concepts and provides a solid foundation for the full Unity MMO development.

