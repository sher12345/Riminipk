# Rimini (riminipk.com)
Cloned from OvenX-Intelligence and rebranded (name, purple/pink palette, logo, icons).

## Before going live
1. ~~Create Supabase project(s)~~ DONE (all pages now use one project: htlqprvfbmjydpfqcbhd; publishable key set); replace in all pages: `https://YOUR-RIMINI-PROJECT.supabase.co` and `YOUR_RIMINI_PUBLISHABLE_KEY`
   (Hiring.html and Staff.html used separate projects: `YOUR-RIMINI-HR-PROJECT`, `YOUR-RIMINI-STAFF-PROJECT`).
2. Recreate tables, RPCs, edge functions (`admin-actions`, `rimini-chat` - renamed from ovenx-chat) and run the Gold Club v2 SQL.
3. Replace `CHANGE_ME*` passwords/PINs (index.html ADM_PASSWORDS, inventoryPassword; Fleet-Control.html ADMIN_PIN).
4. Fill BRANCH_CONFIG in index.html (addresses, coordinates, phones, riders) and the menu data.
5. Landing page copy still describes OvenX food (pizza/burgers, Multan/Bahawalpur) - to be replaced with Rimini text.


## Menu
Menu data (index.html, POS.html, COMS.html) replaced with the Rimini cafe/ice-cream menu. Old pizza deals removed (`dealsData = []`).
