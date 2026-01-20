# BoB Bot - Complete Documentation

**Version**: 2.0  
**Last Updated**: January 20, 2026  
**Bot Prefix**: `b` (customizable per server)

---

## 📑 Table of Contents

1. [Introduction](#introduction)
2. [Getting Started](#getting-started)
3. [Command Categories](#command-categories)
4. [Economy System](#economy-system)
5. [Animal & Battle System](#animal--battle-system)
6. [Leveling System](#leveling-system)
7. [Gambling & Games](#gambling--games)
8. [Social & Roleplay](#social--roleplay)
9. [Moderation Tools](#moderation-tools)
10. [Utility Commands](#utility-commands)
11. [Server Configuration](#server-configuration)
12. [FAQ & Troubleshooting](#faq--troubleshooting)

---

## Introduction

Welcome to **BoB Bot** - your all-in-one Discord companion! BoB Bot brings entertainment, economy, gaming, and community features to your Discord server.

### Key Features

- 🎯 **200+ Commands** across 9 categories
- 🐾 **100+ Collectible Animals** with battle mechanics
- 💰 **Full Economy System** with banking and trading
- 🎮 **10+ Casino Games** and mini-games
- 📊 **Leveling System** with custom progression cards
- 🎭 **20+ Roleplay Commands** with GIF animations
- 🛡️ **Moderation Tools** for server management
- ⚡ **Performance Optimized** with sharding support

### Quick Links

- [GitHub Repository](https://github.com/Sophan-Developer/BoB)
- [Support Server](https://discord.gg/your-invite)
- [Privacy Policy](./PRIVACY_POLICY.md)
- [Terms of Service](./TERMS_OF_SERVICE.md)
- [Report Issues](https://github.com/Sophan-Developer/BoB/issues)

---

## Getting Started

### First Time Setup

1. **Invite the Bot**
   - Use the invite link from our website or support server
   - Grant required permissions (Send Messages, Embed Links, Attach Files, etc.)

2. **Register Your Account**
   ```
   b balance
   ```
   - The bot will prompt you to register
   - Click "Accept" to agree to Terms of Service and Privacy Policy
   - You'll receive a starting balance of 250,000 coins!

3. **Check Available Commands**
   ```
   b help
   ```
   - Browse all available commands by category
   - Use `b help [command]` for detailed command information

4. **Customize Your Experience**
   ```
   b profile          # View your profile
   b settings         # Configure personal settings
   ```

### Basic Command Syntax

```
b [command] [arguments]
```

**Examples:**
- `b balance` - Check your balance
- `b hunt` - Hunt for animals
- `b slots 1000` - Play slots with 1000 coins bet
- `b transfer @user 5000` - Transfer 5000 coins to a user

---

## Command Categories

### 🐾 Animals (17 commands)

Collect, battle, and manage your animal collection!

| Command | Description | Usage |
|---------|-------------|-------|
| `hunt` | Hunt for animals | `b hunt` |
| `zoo` | View your animal collection | `b zoo [rank]` |
| `inventory` / `inv` | View your inventory | `b inv [rank]` |
| `dex` | View animal information | `b dex [animal]` |
| `team` | Manage your battle team | `b team [add/remove/view]` |
| `battle` | Battle other users | `b battle @user` |
| `battlesetting` | Configure battle settings | `b battlesetting` |
| `weapon` | Manage weapons | `b weapon [id]` |
| `crate` | Open weapon crates | `b crate [type]` |
| `dismantle` | Dismantle weapons for shards | `b dismantle [id]` |
| `sacrifice` | Sacrifice animals for shards | `b sacrifice [animal] [amount]` |
| `sell` | Sell animals | `b sell [animal] [amount]` |
| `use` | Use items | `b use [item]` |
| `nickname` | Set animal nickname | `b nickname [animal] [name]` |
| `quest` | View and complete quests | `b quest` |
| `checklist` | View hunt checklist | `b checklist` |
| `animalguide` | Learn about the animal system | `b animalguide` |

### 💰 Economy (19 commands)

Earn, manage, and trade virtual currency!

| Command | Description | Usage |
|---------|-------------|-------|
| `balance` / `bal` | Check your balance | `b balance [@user]` |
| `daily` | Claim daily rewards | `b daily` |
| `weekly` | Claim weekly rewards | `b weekly` |
| `work` | Work to earn money | `b work` |
| `deposit` / `dep` | Deposit coins to bank | `b deposit [amount/all]` |
| `withdraw` / `with` | Withdraw from bank | `b withdraw [amount/all]` |
| `transfer` | Transfer coins to user | `b transfer @user [amount]` |
| `history` | View transaction history | `b history` |
| `level` / `lvl` | View your level | `b level [@user]` |
| `ranking` / `lb` | View server leaderboards | `b ranking [category]` |
| `rep` | Give reputation points | `b rep @user` |
| `cookie` | Manage cookies | `b cookie [give/take] @user` |
| `ticket` | View your tickets | `b ticket` |
| `claimticket` | Claim reward tickets | `b claimticket` |
| `spin` | Spin the fortune wheel | `b spin` |
| `pray` | Pray for blessings | `b pray` |
| `boostexp` | Boost your XP | `b boostexp` |
| `exchange` | Exchange currency | `b exchange [amount]` |
| `xpinfo` | View XP information | `b xpinfo` |

### 🎮 Gambling (10 commands)

Test your luck with casino games!

| Command | Description | Usage |
|---------|-------------|-------|
| `slots` | Slot machine | `b slots [bet]` |
| `blackjack` / `bj` | Play blackjack | `b blackjack [bet]` |
| `roulette` | Roulette game | `b roulette [bet] [choice]` |
| `coinflip` / `cf` | Flip a coin | `b coinflip [bet] [heads/tails]` |
| `dice` | Roll dice | `b dice [bet]` |
| `rps` | Rock Paper Scissors | `b rps [choice]` |
| `guess` | Guess the number | `b guess [number]` |
| `tictactoe` / `ttt` | Tic Tac Toe | `b ttt @user` |
| `klahklok` | Cambodian coin game | `b klahklok [bet]` |
| `pok` | Teen Patti (3-card poker) | `b pok [bet]` |

### 🎭 Roleplay (20+ commands)

Express yourself with animated GIF responses!

| Command | Usage |
|---------|-------|
| `hug` | `b hug @user` |
| `kiss` | `b kiss @user` |
| `pat` | `b pat @user` |
| `slap` | `b slap @user` |
| `punch` | `b punch @user` |
| `cuddle` | `b cuddle @user` |
| `poke` | `b poke @user` |
| `bite` | `b bite @user` |
| `cry` | `b cry` |
| `blush` | `b blush` |
| `smile` | `b smile` |
| `wave` | `b wave @user` |
| `dance` | `b dance` |
| `sleep` | `b sleep` |
| `eat` | `b eat` |
| `laugh` | `b laugh` |
| `happy` | `b happy` |
| `sad` | `b sad` |
| `angry` | `b angry` |
| `love` | `b love @user` |

### 🎨 Meme & Image (15 commands)

Create funny images and memes!

| Command | Description | Usage |
|---------|-------------|-------|
| `jail` | Put someone in jail | `b jail [@user]` |
| `wanted` | Create wanted poster | `b wanted [@user]` |
| `rip` | RIP memorial | `b rip [@user]` |
| `wasted` | GTA wasted effect | `b wasted [@user]` |
| `triggered` | Triggered effect | `b triggered [@user]` |
| `trash` | Throw to trash | `b trash [@user]` |
| `beautiful` | Beautiful butterfly meme | `b beautiful [@user]` |
| `affect` | Affect baby meme | `b affect [@user]` |
| `bonk` | Bonk to horny jail | `b bonk @user` |
| `slap` | Slap someone | `b slap @user [@user]` |
| `spank` | Spank someone | `b spank @user` |
| `flip` | Flip image | `b flip [@user]` |
| `glitch` | Glitch effect | `b glitch [@user]` |
| `posterize` | Posterize effect | `b posterize [@user]` |
| `caption` | Add caption to image | `b caption [text]` |

### 🛡️ Moderation (Admin Only)

Server management and moderation tools!

| Command | Description | Usage |
|---------|-------------|-------|
| `kick` | Kick a member | `b kick @user [reason]` |
| `ban` | Ban a member | `b ban @user [reason]` |
| `unban` | Unban a user | `b unban [user-id]` |
| `mute` | Mute a member | `b mute @user [duration]` |
| `unmute` | Unmute a member | `b unmute @user` |
| `warn` | Warn a member | `b warn @user [reason]` |
| `warnings` | View warnings | `b warnings @user` |
| `clear` / `purge` | Delete messages | `b clear [amount]` |
| `lock` | Lock a channel | `b lock` |
| `unlock` | Unlock a channel | `b unlock` |
| `slowmode` | Set slowmode | `b slowmode [seconds]` |

### 🔧 Utility (15+ commands)

Helpful utility commands!

| Command | Description | Usage |
|---------|-------------|-------|
| `help` | View help menu | `b help [command]` |
| `ping` | Check bot latency | `b ping` |
| `serverinfo` | Server information | `b serverinfo` |
| `userinfo` | User information | `b userinfo [@user]` |
| `avatar` | Get user avatar | `b avatar [@user]` |
| `banner` | Get user banner | `b banner [@user]` |
| `botinfo` | Bot information | `b botinfo` |
| `invite` | Get bot invite link | `b invite` |
| `uptime` | Bot uptime | `b uptime` |
| `suggest` | Send suggestion | `b suggest [text]` |
| `report` | Report a bug | `b report [text]` |
| `poll` | Create a poll | `b poll [question]` |
| `remindme` | Set a reminder | `b remindme [time] [message]` |
| `weather` | Get weather info | `b weather [city]` |
| `translate` | Translate text | `b translate [lang] [text]` |

---

## Economy System

### Currency Types

1. **Coins** 💰
   - Main currency
   - Earn: Daily, weekly, work, games, selling
   - Use: Buy items, gamble, transfer

2. **Bank** 🏦
   - Safe storage for coins
   - No loss on gambles
   - Withdraw/deposit anytime

3. **BoB Points** 🎯
   - Premium currency
   - Earn: Special events, rewards
   - Use: Exclusive items and features

4. **Tickets** 🎫
   - Reward currency
   - Earn: Daily claims, events
   - Use: Special purchases

5. **Cookies** 🍪
   - Gift currency
   - Give to other users
   - Social currency

### Earning Money

#### Daily & Weekly Rewards
```
b daily     # Claim every 24 hours
b weekly    # Claim every 7 days
```
- Daily: 1,000 - 5,000 coins
- Weekly: 10,000 - 50,000 coins
- Streak bonuses available!

#### Work System
```
b work
```
- 15+ job options
- Earn 500 - 3,000 coins per work
- 10-minute cooldown
- Random job descriptions with humor!

#### Gambling Earnings
- Slots: Up to 10x multiplier
- Blackjack: Even money + 3:2 on blackjack
- Roulette: Up to 35x on single numbers
- Coinflip: 2x your bet

### Banking System

#### Deposit Coins
```
b deposit [amount]
b deposit all
b dep 5000
```

#### Withdraw Coins
```
b withdraw [amount]
b withdraw all
b with 10000
```

#### Bank Capacity
- Default: 1,000,000 coins
- Upgrades available at higher levels
- Safe from gambling losses

### Transactions

#### Transfer to Users
```
b transfer @user [amount]
b transfer @JohnDoe 5000
```
- Minimum: 100 coins
- Maximum: Your balance
- Validates recipient exists

#### Transaction History
```
b history
```
- View last 10 transactions
- Timestamps included
- Track deposits, withdrawals, transfers

### Leaderboards

```
b ranking [category]
b lb coins        # Top coin holders
b lb bank         # Top bank holders
b lb level        # Top levels
b lb voice        # Top voice time
b lb ticket       # Top ticket holders
b lb rep          # Top reputation
```

---

## Animal & Battle System

### Hunting Animals

#### Basic Hunting
```
b hunt
b autohunt     # Auto-hunt feature
```
- Catch 1-3 animals per hunt
- 15-second cooldown
- 100+ unique animals
- Rarity ranks: Common → Fabled

### Animal Ranks

| Rank | Drop Rate | Shards | Description |
|------|-----------|--------|-------------|
| Common | 50% | 10 | Everyday animals |
| Uncommon | 30% | 25 | Slightly rare |
| Rare | 12% | 75 | Hard to find |
| Epic | 5% | 200 | Very rare |
| Mythical | 2% | 500 | Extremely rare |
| Legendary | 0.9% | 1,250 | Ultra rare |
| Fabled | 0.1% | 3,000 | Nearly impossible |

### Managing Animals

#### View Collection
```
b zoo              # All animals
b zoo common       # Filter by rank
b zoo legendary    # View legendaries
```

#### View Inventory
```
b inv              # Count per animal
b inv epic         # Filter by rank
```

#### Animal Dex
```
b dex [animal]
b dex dog          # Dog information
```

#### Nicknames
```
b nickname [animal] [name]
b nickname dog "Fluffy"
```
- Custom names for your animals
- 30-character limit
- Must own the animal

### Battle System

#### Team Management
```
b team view                    # View current team
b team add [animal]            # Add to team
b team remove [animal]         # Remove from team
```
- Max 3 animals per team
- Best animals recommended
- Balanced team comp important

#### Battle Mechanics
```
b battle @user
```

**Battle Flow:**
1. Teams are compared
2. Each animal attacks in sequence
3. Weapons add damage bonuses
4. Passive abilities can trigger
5. Winner gets rewards

**Rewards:**
- Winner: 1,000-10,000 coins
- Loser: 100-500 coins (participation)
- XP for both players

#### Battle Settings
```
b battlesetting
```
- Enable/disable battle requests
- Set auto-accept
- Configure notifications

### Weapon System

#### Weapon Types

1. **Physical Weapons**
   - Great Sword, Lightning Blade, Poison Dagger
   - High base damage
   - STR scaling

2. **Magic Weapons**
   - Inferno Staff, Orb of Potency, Frost Wand
   - Magic damage
   - INT scaling

3. **Support Weapons**
   - Healing Staff, Divine Shield, Battle Horn
   - Healing and buffs
   - Team support

4. **Special Weapons**
   - Culling Scythe, Rune of Luck
   - Unique effects
   - Game-changing passives

#### Getting Weapons

##### Weapon Crates
```
b crate [type]
```

| Crate | Cost | Contents |
|-------|------|----------|
| Common | 1,000 coins | Common-Uncommon |
| Uncommon | 5,000 coins | Uncommon-Rare |
| Rare | 15,000 coins | Rare-Epic |
| Epic | 50,000 coins | Epic-Mythical |
| Mythical | 150,000 coins | Mythical-Legendary |
| Legendary | 500,000 coins | Legendary-Fabled |
| Fabled | 2,000,000 coins | Fabled guaranteed |

#### Weapon Management

##### View Weapons
```
b weapon           # List all weapons
b weapon [id]      # View specific weapon
```

##### Equip Weapons
```
b team add [weapon-id]
```
- Each team member can have 1 weapon
- Match weapon type to animal stats

##### Dismantle Weapons
```
b dismantle [id]
```
- Get shards based on rank
- Common: 10 shards
- Legendary: 1,250 shards
- Fabled: 3,000 shards

#### Weapon Rerolling
```
b weapon reroll [id] [type]
```
- `rank` - Reroll weapon rank
- `passive` - Reroll passive ability
- `both` - Reroll everything
- Costs shards based on type

### Sacrifice System

```
b sacrifice [animal] [amount]
```
- Trade animals for shards
- Higher ranks = more shards
- Used for weapon upgrades

### Quest System

```
b quest
```
- Daily and weekly quests
- Hunt X animals
- Battle X times
- Win X games
- Rewards: Coins, tickets, items

---

## Leveling System

### How Leveling Works

- Gain XP by using commands
- Each level requires more XP
- Formula: `XP = level² × 100`
- Max level: None (infinite progression)

### XP Gain

| Activity | XP Reward |
|----------|-----------|
| Message commands | 15-25 XP |
| Economy commands | 10-20 XP |
| Game commands | 20-30 XP |
| Battle commands | 30-50 XP |
| Voice chat (per min) | 5-10 XP |

### Level Rewards

Every 5 levels:
- Coins bonus
- Ticket rewards
- Bank capacity increase
- Special titles

### Voice XP

- Earn XP in voice channels
- 5-10 XP per minute
- AFK detection (future feature)
- Leaderboard: `b ranking voice`

### View Level

```
b level [@user]     # View level card
b xpinfo            # XP details
b ranking level     # Level leaderboard
```

---

## Gambling & Games

### Slots 🎰

```
b slots [bet]
b slots 1000
```

**Payouts:**
- 🍒🍒🍒 Cherry: 2x
- 🍋🍋🍋 Lemon: 3x
- 🍊🍊🍊 Orange: 4x
- 🍇🍇🍇 Grape: 5x
- 💎💎💎 Diamond: 10x
- 🎰🎰🎰 Jackpot: 50x

### Blackjack 🂡

```
b blackjack [bet]
b bj 5000
```

**Rules:**
- Get closer to 21 than dealer
- Blackjack pays 3:2
- Dealer stands on 17
- Buttons: Hit, Stand, Double Down

### Roulette 🎡

```
b roulette [bet] [choice]
b roulette 1000 red
b roulette 2000 17
```

**Bet Types:**
- Red/Black: 2x payout
- Odd/Even: 2x payout
- Single number (0-36): 35x payout
- High (19-36)/Low (1-18): 2x payout

### Coinflip 🪙

```
b coinflip [bet] [heads/tails]
b cf 1000 heads
```

**Rules:**
- 50/50 chance
- Correct guess: 2x payout
- Wrong guess: Lose bet

### Rock Paper Scissors ✊✋✌️

```
b rps [choice]
b rps rock
```

**Rules:**
- Rock beats Scissors
- Scissors beats Paper
- Paper beats Rock
- Win: 100 coins
- Draw: 50 coins

### Guess the Number 🔢

```
b guess [number]
b guess 50
```

**Rules:**
- Guess number between 1-100
- Closer guess = more coins
- Exact match: 5,000 coins bonus

### Dice Roll 🎲

```
b dice [bet]
b dice 500
```

**Rules:**
- Roll 2 dice
- Doubles: 3x payout
- Sum over 7: 2x payout
- Sum 7 or under: Lose

### Klahklok (Cambodian Game) 🇰🇭

```
b klahklok [bet]
b klahklok 1000
```

**Rules:**
- Traditional Cambodian coin game
- Flip multiple coins
- More heads = bigger payout
- Cultural gambling experience

---

## Social & Roleplay

### Profile System

```
b profile [@user]
```

**Profile Shows:**
- Level and XP
- Balance and bank
- Total animals collected
- Marriage status
- Reputation points
- Join date
- Command usage stats

### Marriage System

```
b marry @user         # Propose marriage
b divorce @user       # End marriage
b partner            # View partner
```

**Benefits:**
- Special couple badge
- Shared achievements
- Partner commands

### Reputation System

```
b rep @user          # Give reputation
b rep                # Check your rep
```

**Rules:**
- Give once per 24 hours
- Can't give to yourself
- Leaderboard: `b ranking rep`

### Ship Calculator

```
b ship @user1 @user2
```
- Calculate compatibility
- Generates couple image
- Fun percentage (0-100%)

---

## Moderation Tools

### Warning System

```
b warn @user [reason]          # Warn user
b warnings @user               # View warnings
b clearwarnings @user          # Clear warnings
```

**Auto-Actions:**
- 3 warnings: 24h mute
- 5 warnings: Kick
- 7 warnings: Ban

### Message Management

```
b clear [amount]              # Delete messages
b clear 10                    # Delete 10 messages
b clear 100 @user             # Delete user's messages
```

### Channel Control

```
b lock                        # Lock channel
b unlock                      # Unlock channel
b slowmode [seconds]          # Set slowmode
b slowmode 5                  # 5-second slowmode
b slowmode off                # Disable slowmode
```

### Member Management

```
b kick @user [reason]
b ban @user [reason]
b unban [user-id]
b mute @user [duration]
b unmute @user
```

---

## Server Configuration

### Custom Prefix

```
b prefix [new-prefix]
b prefix !                    # Set prefix to !
b prefix reset                # Reset to default (b)
```

### Welcome Messages

```
b welcome set #channel
b welcome message [text]
b welcome toggle
```

### Auto-Moderation

```
b automod enable
b automod configure
b automod disable
```

---

## FAQ & Troubleshooting

### Common Questions

**Q: How do I start using the bot?**
A: Type `b balance` to register, then use `b help` to see commands.

**Q: I lost coins gambling, can I get them back?**
A: No, gambling losses are final. Gamble responsibly!

**Q: How do I get rare animals?**
A: Keep hunting! Rare animals have low drop rates but appear randomly.

**Q: Can I trade animals with other users?**
A: Not directly, but you can sell animals for coins and trade coins.

**Q: How do I report a bug?**
A: Use `b report [description]` or join our support server.

**Q: Is my data safe?**
A: Yes! Read our [Privacy Policy](./PRIVACY_POLICY.md) for details.

### Troubleshooting

**Bot not responding?**
- Check bot has permissions
- Verify correct prefix
- Check bot status in support server

**Commands not working?**
- Ensure you're registered: `b balance`
- Check cooldowns with `b cooldown`
- Verify command syntax: `b help [command]`

**Missing permissions?**
- Bot needs: Send Messages, Embed Links, Attach Files
- Admin commands require Manage Server

### Support

**Need Help?**
- Join our [Support Discord](https://discord.gg/your-invite)
- Check [GitHub Issues](https://github.com/Sophan-Developer/BoB/issues)
- Read documentation thoroughly

---

## Credits

**Developer**: Sophan-Developer  
**Contributors**: See GitHub repository  
**Libraries**: Discord.js, Canvas, Mongoose, and more  
**License**: MIT License

**Special Thanks:**
- Discord.js community
- All users and testers
- Contributors and supporters

---

**Last Updated**: January 20, 2026  
**Documentation Version**: 2.0  
**Bot Version**: 1.0.0

For the latest updates, visit our [GitHub Repository](https://github.com/Sophan-Developer/BoB)!
