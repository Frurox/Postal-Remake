# Changelog

All notable changes to Postal-Remake will be documented here.

## [1.0.2-release] - 2026-04-28

### Fixed
- `Media/Postal-Remake_logo.tga` was an empty (0-byte) file causing `IconTexture` to not display in the addon list; replaced with a valid 64×64 32-bit TGA generated from `Postal-Remake.png`

## [1.0.1-Release] - 2026-04-28

### Added
- Re-Release of the Remake of Postal
- Changed into single multi-TOC.

---

## Original Postal Addon — Feature Summary

Postal-Remake is a modern continuation of the original **Postal** addon by *Xinhuan*, which provided enhanced mailbox tools for World of Warcraft. Below is a summary of the features carried over from the original addon.

### Modules

| Module | Description |
|---|---|
| **OpenAll** | A button that collects all attachments and coins from mail. Includes simple filters for AH mail (cancelled, expired, outbid, sold, won) and Postmaster mail. |
| **Express** | Mouse-click shortcuts for mail. Shift-Click takes items/money; Alt-Click auto-sends; supports bulk send and mouse wheel scrolling through mail. |
| **BlackBook** | Adds a contact list next to the To: field. Tracks the last 10 recipients mailed, and auto-completes from alts, friends, guild mates, and saved contacts. |
| **Select** | Adds checkboxes to the inbox for batch operations. Selected mail can be batch-opened or returned to sender. |
| **Wire** | Automatically sets the subject field to the value of coins sent when the subject is left blank. |
| **Rake** | Prints the total amount of money collected during a mail session. |
| **Forward** | Allows forwarding the contents of a mail to another recipient. (Not supported for mail sent with money or COD.) |
| **CarbonCopy** | Allows copying the contents of a mail. |
| **DoNotWant** | Shows a clickable visual icon indicating whether a mail will be returned or deleted on expiry. |
| **QuickAttach** | Quickly attach different trade item types to a mail. Supports per-button default recipient via right-click. |
| **TradeBlock** | Blocks incoming trade requests while in a mail session. |

### Core Features

- Dropdown menu accessible from the mailbox with per-module enable/disable toggles
- Configurable mail-opening speed
- Configurable chat output frame for Postal messages
- AceDB profile support (create, copy, delete, reset profiles)
- Tooltip on long mail subjects (hover to see full subject text)
- Minimap mail icon auto-hides when all mail has been read
- Multi-version support: Retail, Classic, TBC, WotLK, Cataclysm, Mists of Pandaria