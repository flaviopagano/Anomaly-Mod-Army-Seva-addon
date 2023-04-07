
- Armor is available in Agroprom military base only, sold by Sgt. Spooner,
- Unlocked at 900 goodwill
- Price around 100k (may vary upon changing difficulty settings)



-----------------
Known bugs:

Using 'Visible body' addon will show default actor legs, without any armor.

-----------------

Fix:

location: gamedata\configs\items\items


in the LTX file named "items_actor_legs.ltx"    (open with notepad or notepad++)


add this line under  ";o_seva.ltx" string       (CTRL + f to find the line)


[army_seva_outfit_legs]:monster_base, actor_legs      (copy and paste these 2 lines)
visual = sm\actor_legs\seva_outfit       


^ this is my Military Seva