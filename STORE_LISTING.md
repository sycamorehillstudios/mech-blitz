# Mech Blitz - Google Play Store Listing

## App Title (30 char max)
```
Mech Blitz: Roguelike Shooter
```

## Short Description (80 char max)
```
Pilot battle mechs, auto-fire through 30 floors of enemies, bosses & upgrades!
```

## Full Description (4000 char max)

```
Suit up. Shoot. Survive. Mech Blitz is an action-packed roguelike auto-fire shooter where you pilot powerful battle mechs through intense floor-by-floor combat. Fight waves of enemies, defeat massive bosses, and power up with game-changing perks — all with one hand.

⚙️ PILOT 4 UNIQUE MECHS
Choose your war machine — each mech has unique stats and a devastating special ability:
• Ironclad — Balanced tank with Missile Barrage
• Phantom — Lightning-fast with Phase Shift invisibility
• Titan — Heavy armor with Fortress Mode invincibility
• Striker — Glass cannon with Overclock triple fire rate

🔫 AUTO-FIRE ACTION
Your mech auto-targets and fires at the nearest enemy. Focus on dodging, jumping, and positioning while your guns do the talking. Simple controls, deep strategy.

🏰 30 FLOORS PER WORLD
Battle through 30 hand-crafted floors across 10 unique worlds — from junkyards to volcanic forges to alien ruins. Every floor has strategic platform layouts with multiple combat levels. Face bosses at floors 10, 20, and 30.

🤖 NPC SUPPLY STATIONS
Meet friendly mechanics at floors 15 and 29 who offer a critical choice: repair your mech or overclock your weapons. Choose wisely — it could save your run.

⚡ 80+ POWERFUL UPGRADES
Collect perks every floor to build insane combos:
• Flamethrower — Cone of fire melts groups
• Omnidirectional Fire — Shoot in all directions at once
• Double & Triple Jump — Reach any platform
• Poison Trail — Leave toxic puddles behind you
• Chain Lightning, Homing Missiles, Explosive Rounds & more
Unlock 22 perk synergies for massive power spikes!

🎯 DEEP PROGRESSION
• Level up your pilot and each mech individually
• Equip gear — weapons, armor, boots, and modules with rarity tiers
• Permanent stat upgrades as a gold sink
• Battle Pass with free and premium reward tracks
• Seasonal events with limited-time challenges
• Daily missions and achievements

🌍 10 UNIQUE WORLDS
Scrapyard, Frozen Outpost, Volcanic Forge, Sky Citadel, Neon Underground, Toxic Wastes, Alien Ruins, Space Station, Digital Void, and Mech Graveyard — each with a unique boss.

♾️ ENDLESS MODE
Think you're tough? Endless Mode scales infinitely with escalating enemy HP, damage, and speed. Climb the leaderboard and prove you're the ultimate pilot.

🏆 WEEKLY CHALLENGES
Compete in weekly challenge runs with unique modifiers — Giant enemies, Bullet Hell, Heavy Hitters, and more. Earn exclusive rewards.

Play offline anytime. No Wi-Fi required!

Download Mech Blitz now and become the ultimate mech pilot!
```

---

## App Category
```
Game → Action
```

## Content Rating
```
Everyone 10+ (Fantasy Violence)
```

## Tags / Keywords (for Google Play Console)
```
mech, robot, shooter, roguelike, action, auto fire, battle mech, platform shooter,
run and gun, mech arena, robot game, shooting game, offline game, auto shooter,
roguelite, bullet hell, mech warrior, robot shooter, boss fight, upgrade
```

---

## Visual Assets

### App Icon (512x512 PNG)
- **Recommended:** `store_assets/app_icon_2.webp` (the close-up mech with lightning)
- Convert to 512x512 PNG before uploading
- Google requires: 32-bit PNG, 512x512px, up to 1MB

### Feature Graphic (1024x500 PNG)
- **Recommended:** `store_assets/feature_graphic_1.webp` (action scene with title)
- Convert to 1024x500 PNG before uploading
- Google requires: JPEG or 24-bit PNG, 1024x500px

### Screenshots (min 2, max 8)
- Required: Phone screenshots (16:9 or 9:16)
- Take in-game at 1920x1080 or 1080x1920
- Recommended shots:
  1. Gameplay — mech fighting enemies on platforms
  2. Perk selection screen — showing upgrade variety
  3. Boss fight — dramatic boss encounter
  4. NPC encounter — supply station choice screen
  5. Mech selection / hangar screen
  6. Gear / equipment screen
  7. Shop screen
  8. World select map

---

## Google Play In-App Products Setup

### Managed Products (Consumable)

| Product ID | Name | Description | Price |
|---|---|---|---|
| `gem_small` | 100 Gems | A small pouch of gems to unlock mechs, skins, and more | $0.99 |
| `gem_large` | 500 Gems | A hefty crate of gems — best for unlocking a new mech | $4.99 |
| `gem_mega` | 1200 Gems | A massive vault of gems — unlock everything faster | $9.99 |
| `starter_pack` | Starter Pack | 500 Gems + 5000 Gold — the perfect head start for new pilots | $4.99 |

### Setup Instructions (Google Play Console)

1. Go to **Google Play Console** → Your App → **Monetize** → **Products** → **In-app products**
2. Click **Create product** for each item above
3. Fill in:
   - **Product ID**: Use the exact ID from the table (e.g., `gem_small`)
   - **Name**: The display name shown to users
   - **Description**: The description from the table
   - **Default price**: Set the price, Google auto-converts to other currencies
   - **Product type**: Select **Consumable** (player can buy multiple times)
4. Set status to **Active** for each product
5. Products won't work until the app is published (at least to internal testing track)

### Important Notes
- Product IDs are **permanent** — they cannot be changed or reused after creation
- The Product IDs must exactly match what's in `iap_manager.gd` SKUS dictionary
- Test with **license testers** (Settings → License testing) before going live
- Use Google Play Billing Library v7+ (via Godot plugin)
- All products are consumable (can be purchased repeatedly)
- No subscriptions or non-consumable products currently

---

## Privacy Policy Requirement

Google Play requires a privacy policy URL. At minimum, host a simple page stating:
- App does not collect personal data
- App uses AdMob (Google) for serving ads — link to Google's privacy policy
- App uses Google Play Billing for purchases
- No accounts or user-generated content

Host on GitHub Pages, your website, or a free hosting service.

---

## Pre-Launch Checklist

- [ ] Convert app_icon_2.webp → 512x512 PNG
- [ ] Convert feature_graphic_1.webp → 1024x500 PNG
- [ ] Take 4-8 in-game screenshots
- [ ] Create privacy policy page and get URL
- [ ] Set up AdMob account and create rewarded ad unit IDs
- [ ] Create all 4 IAP products in Google Play Console
- [ ] Add license testers for IAP testing
- [ ] Upload AAB to internal testing track first
- [ ] Test IAP and rewarded ads on a real device
- [ ] Promote to production when ready
