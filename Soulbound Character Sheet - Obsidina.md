---
cssclasses:
  - soulbound-character-sheet-note
character_name: ""
archetype: ""
species: ""
age: ""
eyes: ""
hair: ""
height: ""
weight: ""
distinguishing_features: ""
xp: ""
body: ""
mind: ""
soul: ""
natural_awareness: ""
goals: ""
connections: ""
talents_1: ""
talents_2: ""
initiative: ""
mettle_current: ""
mettle_total: ""
armour: ""
toughness_current: ""
toughness_total: ""
background: ""
notes: ""
other_gear_1: ""
other_gear_2: ""
drops: ""
phials: ""
spheres: ""
portrait: ""
arcana_training: 0
arcana_focus: 0
athletics_training: 0
athletics_focus: 0
awareness_training: 0
awareness_focus: 0
ballistic_skill_training: 0
ballistic_skill_focus: 0
beast_handling_training: 0
beast_handling_focus: 0
channelling_training: 0
channelling_focus: 0
crafting_training: 0
crafting_focus: 0
determination_training: 0
determination_focus: 0
devotion_training: 0
devotion_focus: 0
dexterity_training: 0
dexterity_focus: 0
entertain_training: 0
entertain_focus: 0
fortitude_training: 0
fortitude_focus: 0
guile_training: 0
guile_focus: 0
intimidation_training: 0
intimidation_focus: 0
intuition_training: 0
intuition_focus: 0
lore_training: 0
lore_focus: 0
medicine_training: 0
medicine_focus: 0
might_training: 0
might_focus: 0
nature_training: 0
nature_focus: 0
reflexes_training: 0
reflexes_focus: 0
stealth_training: 0
stealth_focus: 0
survival_training: 0
survival_focus: 0
theology_training: 0
theology_focus: 0
weapon_skill_training: 0
weapon_skill_focus: 0
combat_melee: ""
combat_accuracy: ""
combat_defence: ""
wound_1: false
wound_note_1: ""
wound_2: false
wound_note_2: ""
wound_3: false
wound_note_3: ""
wound_4: false
wound_note_4: ""
wound_5: false
wound_note_5: ""
wound_6: false
wound_note_6: ""
wound_7: false
wound_note_7: ""
wound_8: false
wound_note_8: ""
wound_9: false
wound_note_9: ""
wound_10: false
wound_note_10: ""
wound_11: false
wound_note_11: ""
wound_12: false
wound_note_12: ""
mortally_wounded: false
attack_1_weapon: ""
attack_1_pool: ""
attack_1_focus: ""
attack_1_damage: ""
attack_1_traits: ""
attack_2_weapon: ""
attack_2_pool: ""
attack_2_focus: ""
attack_2_damage: ""
attack_2_traits: ""
attack_3_weapon: ""
attack_3_pool: ""
attack_3_focus: ""
attack_3_damage: ""
attack_3_traits: ""
attack_4_weapon: ""
attack_4_pool: ""
attack_4_focus: ""
attack_4_damage: ""
attack_4_traits: ""
attack_5_weapon: ""
attack_5_pool: ""
attack_5_focus: ""
attack_5_damage: ""
attack_5_traits: ""
equipment_head: ""
equipment_cloak: ""
equipment_armour: ""
equipment_right_hand: ""
equipment_left_hand: ""
equipment_arms: ""
equipment_boots: ""
equipment_jewellery: ""
equipment_other_1: ""
equipment_other_2: ""
spell_1_name: ""
spell_1_dn_cost: ""
spell_1_target: ""
spell_1_range: ""
spell_1_duration: ""
spell_1_effect: ""
spell_2_name: ""
spell_2_dn_cost: ""
spell_2_target: ""
spell_2_range: ""
spell_2_duration: ""
spell_2_effect: ""
spell_3_name: ""
spell_3_dn_cost: ""
spell_3_target: ""
spell_3_range: ""
spell_3_duration: ""
spell_3_effect: ""
spell_4_name: ""
spell_4_dn_cost: ""
spell_4_target: ""
spell_4_range: ""
spell_4_duration: ""
spell_4_effect: ""
spell_5_name: ""
spell_5_dn_cost: ""
spell_5_target: ""
spell_5_range: ""
spell_5_duration: ""
spell_5_effect: ""
spell_6_name: ""
spell_6_dn_cost: ""
spell_6_target: ""
spell_6_range: ""
spell_6_duration: ""
spell_6_effect: ""
spell_7_name: ""
spell_7_dn_cost: ""
spell_7_target: ""
spell_7_range: ""
spell_7_duration: ""
spell_7_effect: ""
spell_8_name: ""
spell_8_dn_cost: ""
spell_8_target: ""
spell_8_range: ""
spell_8_duration: ""
spell_8_effect: ""
spell_9_name: ""
spell_9_dn_cost: ""
spell_9_target: ""
spell_9_range: ""
spell_9_duration: ""
spell_9_effect: ""
spell_10_name: ""
spell_10_dn_cost: ""
spell_10_target: ""
spell_10_range: ""
spell_10_duration: ""
spell_10_effect: ""
spell_11_name: ""
spell_11_dn_cost: ""
spell_11_target: ""
spell_11_range: ""
spell_11_duration: ""
spell_11_effect: ""
spell_12_name: ""
spell_12_dn_cost: ""
spell_12_target: ""
spell_12_range: ""
spell_12_duration: ""
spell_12_effect: ""
---

# Soulbound Character Sheet

Edit the character through the collapsible sections below. The two graphical pages update automatically.

> [!user]- Identity and attributes
> **Character name:** `INPUT[text:character_name]`  
> **Archetype:** `INPUT[text:archetype]`  
> **Species:** `INPUT[text:species]`  
> **Age:** `INPUT[text:age]` · **Eyes:** `INPUT[text:eyes]` · **Hair:** `INPUT[text:hair]`  
> **Height:** `INPUT[text:height]` · **Weight:** `INPUT[text:weight]` · **XP:** `INPUT[text:xp]`  
> **Distinguishing features:**  
> `INPUT[textArea:distinguishing_features]`  
>
> **Body:** `INPUT[text:body]` · **Mind:** `INPUT[text:mind]` · **Soul:** `INPUT[text:soul]`  
> **Natural awareness:** `INPUT[text:natural_awareness]`  

> [!list-checks]- Skills
> Choose a value from **0–3** for training and focus.  
> **Arcana:** Training `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):arcana_training]` · Focus `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):arcana_focus]`  
> **Athletics:** Training `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):athletics_training]` · Focus `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):athletics_focus]`  
> **Awareness:** Training `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):awareness_training]` · Focus `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):awareness_focus]`  
> **Ballistic Skill:** Training `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):ballistic_skill_training]` · Focus `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):ballistic_skill_focus]`  
> **Beast Handling:** Training `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):beast_handling_training]` · Focus `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):beast_handling_focus]`  
> **Channelling:** Training `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):channelling_training]` · Focus `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):channelling_focus]`  
> **Crafting:** Training `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):crafting_training]` · Focus `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):crafting_focus]`  
> **Determination:** Training `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):determination_training]` · Focus `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):determination_focus]`  
> **Devotion:** Training `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):devotion_training]` · Focus `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):devotion_focus]`  
> **Dexterity:** Training `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):dexterity_training]` · Focus `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):dexterity_focus]`  
> **Entertain:** Training `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):entertain_training]` · Focus `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):entertain_focus]`  
> **Fortitude:** Training `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):fortitude_training]` · Focus `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):fortitude_focus]`  
> **Guile:** Training `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):guile_training]` · Focus `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):guile_focus]`  
> **Intimidation:** Training `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):intimidation_training]` · Focus `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):intimidation_focus]`  
> **Intuition:** Training `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):intuition_training]` · Focus `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):intuition_focus]`  
> **Lore:** Training `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):lore_training]` · Focus `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):lore_focus]`  
> **Medicine:** Training `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):medicine_training]` · Focus `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):medicine_focus]`  
> **Might:** Training `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):might_training]` · Focus `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):might_focus]`  
> **Nature:** Training `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):nature_training]` · Focus `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):nature_focus]`  
> **Reflexes:** Training `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):reflexes_training]` · Focus `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):reflexes_focus]`  
> **Stealth:** Training `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):stealth_training]` · Focus `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):stealth_focus]`  
> **Survival:** Training `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):survival_training]` · Focus `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):survival_focus]`  
> **Theology:** Training `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):theology_training]` · Focus `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):theology_focus]`  
> **Weapon Skill:** Training `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):weapon_skill_training]` · Focus `INPUT[inlineSelect(option(0), option(1), option(2), option(3)):weapon_skill_focus]`  

> [!scroll-text]- Goals, connections, and talents
> **Goals:**  
> `INPUT[textArea:goals]`  
> **Connections:**  
> `INPUT[textArea:connections]`  
> **Talents — left column:**  
> `INPUT[textArea:talents_1]`  
> **Talents — right column:**  
> `INPUT[textArea:talents_2]`  

> [!swords]- Combat and wounds
> **Melee:** `INPUT[inlineSelect(option(Poor), option(Average), option(Good), option(Great), option(Superb), option(Extraordinary)):combat_melee]`  
> **Accuracy:** `INPUT[inlineSelect(option(Poor), option(Average), option(Good), option(Great), option(Superb), option(Extraordinary)):combat_accuracy]`  
> **Defence:** `INPUT[inlineSelect(option(Poor), option(Average), option(Good), option(Great), option(Superb), option(Extraordinary)):combat_defence]`  
>
> **Initiative:** `INPUT[text:initiative]`  
> **Mettle:** Current `INPUT[text:mettle_current]` · Total `INPUT[text:mettle_total]`  
> **Armour:** `INPUT[text:armour]`  
> **Toughness:** Current `INPUT[text:toughness_current]` · Total `INPUT[text:toughness_total]`  
>
> **Wounds:**  
> 1. `INPUT[toggle:wound_1]` Note: `INPUT[text:wound_note_1]`  
> 2. `INPUT[toggle:wound_2]` Note: `INPUT[text:wound_note_2]`  
> 3. `INPUT[toggle:wound_3]` Note: `INPUT[text:wound_note_3]`  
> 4. `INPUT[toggle:wound_4]` Note: `INPUT[text:wound_note_4]`  
> 5. `INPUT[toggle:wound_5]` Note: `INPUT[text:wound_note_5]`  
> 6. `INPUT[toggle:wound_6]` Note: `INPUT[text:wound_note_6]`  
> 7. `INPUT[toggle:wound_7]` Note: `INPUT[text:wound_note_7]`  
> 8. `INPUT[toggle:wound_8]` Note: `INPUT[text:wound_note_8]`  
> 9. `INPUT[toggle:wound_9]` Note: `INPUT[text:wound_note_9]`  
> 10. `INPUT[toggle:wound_10]` Note: `INPUT[text:wound_note_10]`  
> 11. `INPUT[toggle:wound_11]` Note: `INPUT[text:wound_note_11]`  
> 12. `INPUT[toggle:wound_12]` Note: `INPUT[text:wound_note_12]`  
> **Mortally wounded:** `INPUT[toggle:mortally_wounded]`  

> [!crosshair]- Attacks
> **Attack 1**  
> Weapon `INPUT[text:attack_1_weapon]` · Pool `INPUT[text:attack_1_pool]` · Focus `INPUT[text:attack_1_focus]` · Damage `INPUT[text:attack_1_damage]`  
> Traits `INPUT[text:attack_1_traits]`  
>
> **Attack 2**  
> Weapon `INPUT[text:attack_2_weapon]` · Pool `INPUT[text:attack_2_pool]` · Focus `INPUT[text:attack_2_focus]` · Damage `INPUT[text:attack_2_damage]`  
> Traits `INPUT[text:attack_2_traits]`  
>
> **Attack 3**  
> Weapon `INPUT[text:attack_3_weapon]` · Pool `INPUT[text:attack_3_pool]` · Focus `INPUT[text:attack_3_focus]` · Damage `INPUT[text:attack_3_damage]`  
> Traits `INPUT[text:attack_3_traits]`  
>
> **Attack 4**  
> Weapon `INPUT[text:attack_4_weapon]` · Pool `INPUT[text:attack_4_pool]` · Focus `INPUT[text:attack_4_focus]` · Damage `INPUT[text:attack_4_damage]`  
> Traits `INPUT[text:attack_4_traits]`  
>
> **Attack 5**  
> Weapon `INPUT[text:attack_5_weapon]` · Pool `INPUT[text:attack_5_pool]` · Focus `INPUT[text:attack_5_focus]` · Damage `INPUT[text:attack_5_damage]`  
> Traits `INPUT[text:attack_5_traits]`  
>

> [!image]- Portrait, background, and notes
> Put the portrait image in your vault, then enter its vault path or wiki-link.  
> **Portrait:** `INPUT[text(placeholder(path/to/image.png)):portrait]`  
> **Background:**  
> `INPUT[textArea:background]`  
> **Notes:**  
> `INPUT[textArea:notes]`  

> [!backpack]- Equipment, other gear, and currency
> **Head:** `INPUT[text:equipment_head]`  
> **Cloak:** `INPUT[text:equipment_cloak]`  
> **Armour:** `INPUT[text:equipment_armour]`  
> **Right hand:** `INPUT[text:equipment_right_hand]`  
> **Left hand:** `INPUT[text:equipment_left_hand]`  
> **Arms:** `INPUT[text:equipment_arms]`  
> **Boots:** `INPUT[text:equipment_boots]`  
> **Jewellery:** `INPUT[text:equipment_jewellery]`  
> **Other 1:** `INPUT[text:equipment_other_1]`  
> **Other 2:** `INPUT[text:equipment_other_2]`  
> **Other gear — left column:**  
> `INPUT[textArea:other_gear_1]`  
> **Other gear — right column:**  
> `INPUT[textArea:other_gear_2]`  
> **Drops:** `INPUT[text:drops]` · **Phials:** `INPUT[text:phials]` · **Spheres:** `INPUT[text:spheres]`  

> [!sparkles]- Spells and miracles
> **Spell or miracle 1**  
> Name `INPUT[text:spell_1_name]` · DN/Cost `INPUT[text:spell_1_dn_cost]` · Target `INPUT[text:spell_1_target]`  
> Range `INPUT[text:spell_1_range]` · Duration `INPUT[text:spell_1_duration]`  
> Effect `INPUT[text:spell_1_effect]`  
>
> **Spell or miracle 2**  
> Name `INPUT[text:spell_2_name]` · DN/Cost `INPUT[text:spell_2_dn_cost]` · Target `INPUT[text:spell_2_target]`  
> Range `INPUT[text:spell_2_range]` · Duration `INPUT[text:spell_2_duration]`  
> Effect `INPUT[text:spell_2_effect]`  
>
> **Spell or miracle 3**  
> Name `INPUT[text:spell_3_name]` · DN/Cost `INPUT[text:spell_3_dn_cost]` · Target `INPUT[text:spell_3_target]`  
> Range `INPUT[text:spell_3_range]` · Duration `INPUT[text:spell_3_duration]`  
> Effect `INPUT[text:spell_3_effect]`  
>
> **Spell or miracle 4**  
> Name `INPUT[text:spell_4_name]` · DN/Cost `INPUT[text:spell_4_dn_cost]` · Target `INPUT[text:spell_4_target]`  
> Range `INPUT[text:spell_4_range]` · Duration `INPUT[text:spell_4_duration]`  
> Effect `INPUT[text:spell_4_effect]`  
>
> **Spell or miracle 5**  
> Name `INPUT[text:spell_5_name]` · DN/Cost `INPUT[text:spell_5_dn_cost]` · Target `INPUT[text:spell_5_target]`  
> Range `INPUT[text:spell_5_range]` · Duration `INPUT[text:spell_5_duration]`  
> Effect `INPUT[text:spell_5_effect]`  
>
> **Spell or miracle 6**  
> Name `INPUT[text:spell_6_name]` · DN/Cost `INPUT[text:spell_6_dn_cost]` · Target `INPUT[text:spell_6_target]`  
> Range `INPUT[text:spell_6_range]` · Duration `INPUT[text:spell_6_duration]`  
> Effect `INPUT[text:spell_6_effect]`  
>
> **Spell or miracle 7**  
> Name `INPUT[text:spell_7_name]` · DN/Cost `INPUT[text:spell_7_dn_cost]` · Target `INPUT[text:spell_7_target]`  
> Range `INPUT[text:spell_7_range]` · Duration `INPUT[text:spell_7_duration]`  
> Effect `INPUT[text:spell_7_effect]`  
>
> **Spell or miracle 8**  
> Name `INPUT[text:spell_8_name]` · DN/Cost `INPUT[text:spell_8_dn_cost]` · Target `INPUT[text:spell_8_target]`  
> Range `INPUT[text:spell_8_range]` · Duration `INPUT[text:spell_8_duration]`  
> Effect `INPUT[text:spell_8_effect]`  
>
> **Spell or miracle 9**  
> Name `INPUT[text:spell_9_name]` · DN/Cost `INPUT[text:spell_9_dn_cost]` · Target `INPUT[text:spell_9_target]`  
> Range `INPUT[text:spell_9_range]` · Duration `INPUT[text:spell_9_duration]`  
> Effect `INPUT[text:spell_9_effect]`  
>
> **Spell or miracle 10**  
> Name `INPUT[text:spell_10_name]` · DN/Cost `INPUT[text:spell_10_dn_cost]` · Target `INPUT[text:spell_10_target]`  
> Range `INPUT[text:spell_10_range]` · Duration `INPUT[text:spell_10_duration]`  
> Effect `INPUT[text:spell_10_effect]`  
>
> **Spell or miracle 11**  
> Name `INPUT[text:spell_11_name]` · DN/Cost `INPUT[text:spell_11_dn_cost]` · Target `INPUT[text:spell_11_target]`  
> Range `INPUT[text:spell_11_range]` · Duration `INPUT[text:spell_11_duration]`  
> Effect `INPUT[text:spell_11_effect]`  
>
> **Spell or miracle 12**  
> Name `INPUT[text:spell_12_name]` · DN/Cost `INPUT[text:spell_12_dn_cost]` · Target `INPUT[text:spell_12_target]`  
> Range `INPUT[text:spell_12_range]` · Duration `INPUT[text:spell_12_duration]`  
> Effect `INPUT[text:spell_12_effect]`  
>

## Character Sheet

> [!soulbound-page-1]
> `VIEW[{archetype}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-000))]`
> `VIEW[{species}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-001))]`
> `VIEW[{age}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-002))]`
> `VIEW[{eyes}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-003))]`
> `VIEW[{hair}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-004))]`
> `VIEW[{height}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-005))]`
> `VIEW[{weight}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-006))]`
> `VIEW[{character_name}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-007))]`
> `VIEW[{distinguishing_features}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-008))]`
> `VIEW[{xp}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-009))]`
> `VIEW[{body}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-010), class(sb-sheet-large))]`
> `VIEW[{arcana_training} >= 1 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-011))]`
> `VIEW[{arcana_training} >= 2 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-012))]`
> `VIEW[{arcana_training} >= 3 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-013))]`
> `VIEW[{arcana_focus} >= 1 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-014))]`
> `VIEW[{arcana_focus} >= 2 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-015))]`
> `VIEW[{arcana_focus} >= 3 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-016))]`
> `VIEW[{devotion_training} >= 1 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-017))]`
> `VIEW[{devotion_training} >= 2 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-018))]`
> `VIEW[{devotion_training} >= 3 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-019))]`
> `VIEW[{devotion_focus} >= 1 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-020))]`
> `VIEW[{devotion_focus} >= 2 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-021))]`
> `VIEW[{devotion_focus} >= 3 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-022))]`
> `VIEW[{medicine_training} >= 1 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-023))]`
> `VIEW[{medicine_training} >= 2 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-024))]`
> `VIEW[{medicine_training} >= 3 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-025))]`
> `VIEW[{medicine_focus} >= 1 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-026))]`
> `VIEW[{medicine_focus} >= 2 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-027))]`
> `VIEW[{medicine_focus} >= 3 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-028))]`
> `VIEW[{might_training} >= 1 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-029))]`
> `VIEW[{might_training} >= 2 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-030))]`
> `VIEW[{might_training} >= 3 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-031))]`
> `VIEW[{athletics_training} >= 1 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-032))]`
> `VIEW[{athletics_training} >= 2 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-033))]`
> `VIEW[{athletics_training} >= 3 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-034))]`
> `VIEW[{athletics_focus} >= 1 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-035))]`
> `VIEW[{athletics_focus} >= 2 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-036))]`
> `VIEW[{athletics_focus} >= 3 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-037))]`
> `VIEW[{dexterity_training} >= 1 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-038))]`
> `VIEW[{dexterity_training} >= 2 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-039))]`
> `VIEW[{dexterity_training} >= 3 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-040))]`
> `VIEW[{dexterity_focus} >= 1 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-041))]`
> `VIEW[{dexterity_focus} >= 2 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-042))]`
> `VIEW[{dexterity_focus} >= 3 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-043))]`
> `VIEW[{might_focus} >= 1 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-044))]`
> `VIEW[{might_focus} >= 2 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-045))]`
> `VIEW[{might_focus} >= 3 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-046))]`
> `VIEW[{mind}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-047), class(sb-sheet-large))]`
> `VIEW[{nature_training} >= 1 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-048))]`
> `VIEW[{nature_training} >= 2 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-049))]`
> `VIEW[{nature_training} >= 3 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-050))]`
> `VIEW[{awareness_training} >= 1 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-051))]`
> `VIEW[{awareness_training} >= 2 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-052))]`
> `VIEW[{awareness_training} >= 3 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-053))]`
> `VIEW[{awareness_focus} >= 1 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-054))]`
> `VIEW[{awareness_focus} >= 2 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-055))]`
> `VIEW[{awareness_focus} >= 3 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-056))]`
> `VIEW[{entertain_training} >= 1 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-057))]`
> `VIEW[{entertain_training} >= 2 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-058))]`
> `VIEW[{entertain_training} >= 3 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-059))]`
> `VIEW[{entertain_focus} >= 1 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-060))]`
> `VIEW[{entertain_focus} >= 2 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-061))]`
> `VIEW[{entertain_focus} >= 3 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-062))]`
> `VIEW[{nature_focus} >= 1 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-063))]`
> `VIEW[{nature_focus} >= 2 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-064))]`
> `VIEW[{nature_focus} >= 3 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-065))]`
> `VIEW[{reflexes_training} >= 1 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-066))]`
> `VIEW[{reflexes_training} >= 2 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-067))]`
> `VIEW[{reflexes_training} >= 3 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-068))]`
> `VIEW[{ballistic_skill_training} >= 1 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-069))]`
> `VIEW[{ballistic_skill_training} >= 2 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-070))]`
> `VIEW[{ballistic_skill_training} >= 3 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-071))]`
> `VIEW[{ballistic_skill_focus} >= 1 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-072))]`
> `VIEW[{ballistic_skill_focus} >= 2 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-073))]`
> `VIEW[{ballistic_skill_focus} >= 3 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-074))]`
> `VIEW[{fortitude_training} >= 1 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-075))]`
> `VIEW[{fortitude_training} >= 2 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-076))]`
> `VIEW[{fortitude_training} >= 3 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-077))]`
> `VIEW[{fortitude_focus} >= 1 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-078))]`
> `VIEW[{fortitude_focus} >= 2 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-079))]`
> `VIEW[{fortitude_focus} >= 3 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-080))]`
> `VIEW[{reflexes_focus} >= 1 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-081))]`
> `VIEW[{reflexes_focus} >= 2 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-082))]`
> `VIEW[{reflexes_focus} >= 3 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-083))]`
> `VIEW[{stealth_training} >= 1 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-084))]`
> `VIEW[{stealth_training} >= 2 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-085))]`
> `VIEW[{stealth_training} >= 3 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-086))]`
> `VIEW[{beast_handling_training} >= 1 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-087))]`
> `VIEW[{beast_handling_training} >= 2 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-088))]`
> `VIEW[{beast_handling_training} >= 3 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-089))]`
> `VIEW[{beast_handling_focus} >= 1 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-090))]`
> `VIEW[{beast_handling_focus} >= 2 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-091))]`
> `VIEW[{beast_handling_focus} >= 3 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-092))]`
> `VIEW[{guile_training} >= 1 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-093))]`
> `VIEW[{guile_training} >= 2 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-094))]`
> `VIEW[{guile_training} >= 3 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-095))]`
> `VIEW[{guile_focus} >= 1 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-096))]`
> `VIEW[{guile_focus} >= 2 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-097))]`
> `VIEW[{guile_focus} >= 3 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-098))]`
> `VIEW[{stealth_focus} >= 1 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-099))]`
> `VIEW[{stealth_focus} >= 2 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-100))]`
> `VIEW[{stealth_focus} >= 3 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-101))]`
> `VIEW[{soul}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-102), class(sb-sheet-large))]`
> `VIEW[{survival_training} >= 1 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-103))]`
> `VIEW[{survival_training} >= 2 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-104))]`
> `VIEW[{survival_training} >= 3 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-105))]`
> `VIEW[{channelling_training} >= 1 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-106))]`
> `VIEW[{channelling_training} >= 2 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-107))]`
> `VIEW[{channelling_training} >= 3 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-108))]`
> `VIEW[{channelling_focus} >= 1 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-109))]`
> `VIEW[{channelling_focus} >= 2 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-110))]`
> `VIEW[{channelling_focus} >= 3 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-111))]`
> `VIEW[{intimidation_training} >= 1 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-112))]`
> `VIEW[{intimidation_training} >= 2 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-113))]`
> `VIEW[{intimidation_training} >= 3 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-114))]`
> `VIEW[{intimidation_focus} >= 1 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-115))]`
> `VIEW[{intimidation_focus} >= 2 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-116))]`
> `VIEW[{intimidation_focus} >= 3 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-117))]`
> `VIEW[{survival_focus} >= 1 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-118))]`
> `VIEW[{survival_focus} >= 2 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-119))]`
> `VIEW[{survival_focus} >= 3 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-120))]`
> `VIEW[{theology_training} >= 1 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-121))]`
> `VIEW[{theology_training} >= 2 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-122))]`
> `VIEW[{theology_training} >= 3 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-123))]`
> `VIEW[{crafting_training} >= 1 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-124))]`
> `VIEW[{crafting_training} >= 2 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-125))]`
> `VIEW[{crafting_training} >= 3 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-126))]`
> `VIEW[{crafting_focus} >= 1 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-127))]`
> `VIEW[{crafting_focus} >= 2 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-128))]`
> `VIEW[{crafting_focus} >= 3 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-129))]`
> `VIEW[{intuition_training} >= 1 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-130))]`
> `VIEW[{intuition_training} >= 2 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-131))]`
> `VIEW[{intuition_training} >= 3 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-132))]`
> `VIEW[{intuition_focus} >= 1 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-133))]`
> `VIEW[{intuition_focus} >= 2 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-134))]`
> `VIEW[{intuition_focus} >= 3 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-135))]`
> `VIEW[{theology_focus} >= 1 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-136))]`
> `VIEW[{theology_focus} >= 2 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-137))]`
> `VIEW[{theology_focus} >= 3 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-138))]`
> `VIEW[{weapon_skill_training} >= 1 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-139))]`
> `VIEW[{weapon_skill_training} >= 2 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-140))]`
> `VIEW[{weapon_skill_training} >= 3 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-141))]`
> `VIEW[{determination_training} >= 1 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-142))]`
> `VIEW[{determination_training} >= 2 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-143))]`
> `VIEW[{determination_training} >= 3 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-144))]`
> `VIEW[{determination_focus} >= 1 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-145))]`
> `VIEW[{determination_focus} >= 2 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-146))]`
> `VIEW[{determination_focus} >= 3 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-147))]`
> `VIEW[{lore_training} >= 1 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-148))]`
> `VIEW[{lore_training} >= 2 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-149))]`
> `VIEW[{lore_training} >= 3 ? "■" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-training-marker), class(sb-v-1-150))]`
> `VIEW[{lore_focus} >= 1 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-151))]`
> `VIEW[{lore_focus} >= 2 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-152))]`
> `VIEW[{lore_focus} >= 3 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-153))]`
> `VIEW[{weapon_skill_focus} >= 1 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-154))]`
> `VIEW[{weapon_skill_focus} >= 2 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-155))]`
> `VIEW[{weapon_skill_focus} >= 3 ? "◆" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-focus-marker), class(sb-v-1-156))]`
> `VIEW[{natural_awareness}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-157))]`
> `VIEW[{talents_1}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-158), class(sb-sheet-multiline))]`
> `VIEW[{talents_2}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-159), class(sb-sheet-multiline))]`
> `VIEW[{goals}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-160), class(sb-sheet-multiline))]`
> `VIEW[{connections}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-161), class(sb-sheet-multiline))]`
> `VIEW[{wound_note_1}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-162), class(sb-sheet-small))]`
> `VIEW[{wound_1} ? "●" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-wound-marker), class(sb-v-1-163))]`
> `VIEW[{wound_note_2}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-164), class(sb-sheet-small))]`
> `VIEW[{wound_2} ? "●" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-wound-marker), class(sb-v-1-165))]`
> `VIEW[{mettle_current}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-166), class(sb-sheet-large))]`
> `VIEW[{mettle_total}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-167), class(sb-sheet-large))]`
> `VIEW[{initiative}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-168), class(sb-sheet-large))]`
> `VIEW[equalText({combat_melee}, "Extraordinary") ? "●" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-combat-marker), class(sb-v-1-169))]`
> `VIEW[equalText({combat_accuracy}, "Extraordinary") ? "●" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-combat-marker), class(sb-v-1-170))]`
> `VIEW[equalText({combat_defence}, "Extraordinary") ? "●" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-combat-marker), class(sb-v-1-171))]`
> `VIEW[{wound_note_3}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-172), class(sb-sheet-small))]`
> `VIEW[{wound_3} ? "●" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-wound-marker), class(sb-v-1-173))]`
> `VIEW[equalText({combat_melee}, "Superb") ? "●" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-combat-marker), class(sb-v-1-174))]`
> `VIEW[equalText({combat_accuracy}, "Superb") ? "●" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-combat-marker), class(sb-v-1-175))]`
> `VIEW[equalText({combat_defence}, "Superb") ? "●" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-combat-marker), class(sb-v-1-176))]`
> `VIEW[{wound_note_4}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-177), class(sb-sheet-small))]`
> `VIEW[{wound_4} ? "●" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-wound-marker), class(sb-v-1-178))]`
> `VIEW[equalText({combat_melee}, "Great") ? "●" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-combat-marker), class(sb-v-1-179))]`
> `VIEW[equalText({combat_accuracy}, "Great") ? "●" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-combat-marker), class(sb-v-1-180))]`
> `VIEW[equalText({combat_defence}, "Great") ? "●" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-combat-marker), class(sb-v-1-181))]`
> `VIEW[{wound_note_5}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-182), class(sb-sheet-small))]`
> `VIEW[{wound_5} ? "●" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-wound-marker), class(sb-v-1-183))]`
> `VIEW[equalText({combat_melee}, "Good") ? "●" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-combat-marker), class(sb-v-1-184))]`
> `VIEW[equalText({combat_accuracy}, "Good") ? "●" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-combat-marker), class(sb-v-1-185))]`
> `VIEW[equalText({combat_defence}, "Good") ? "●" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-combat-marker), class(sb-v-1-186))]`
> `VIEW[{wound_note_6}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-187), class(sb-sheet-small))]`
> `VIEW[{wound_6} ? "●" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-wound-marker), class(sb-v-1-188))]`
> `VIEW[{toughness_current}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-189), class(sb-sheet-large))]`
> `VIEW[{toughness_total}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-190), class(sb-sheet-large))]`
> `VIEW[{armour}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-191), class(sb-sheet-large))]`
> `VIEW[equalText({combat_melee}, "Average") ? "●" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-combat-marker), class(sb-v-1-192))]`
> `VIEW[equalText({combat_accuracy}, "Average") ? "●" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-combat-marker), class(sb-v-1-193))]`
> `VIEW[equalText({combat_defence}, "Average") ? "●" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-combat-marker), class(sb-v-1-194))]`
> `VIEW[{wound_note_7}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-195), class(sb-sheet-small))]`
> `VIEW[{wound_7} ? "●" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-wound-marker), class(sb-v-1-196))]`
> `VIEW[equalText({combat_melee}, "Poor") ? "●" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-combat-marker), class(sb-v-1-197))]`
> `VIEW[equalText({combat_accuracy}, "Poor") ? "●" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-combat-marker), class(sb-v-1-198))]`
> `VIEW[equalText({combat_defence}, "Poor") ? "●" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-combat-marker), class(sb-v-1-199))]`
> `VIEW[{wound_note_8}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-200), class(sb-sheet-small))]`
> `VIEW[{wound_8} ? "●" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-wound-marker), class(sb-v-1-201))]`
> `VIEW[{wound_note_9}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-202), class(sb-sheet-small))]`
> `VIEW[{wound_9} ? "●" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-wound-marker), class(sb-v-1-203))]`
> `VIEW[{wound_note_10}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-204), class(sb-sheet-small))]`
> `VIEW[{wound_10} ? "●" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-wound-marker), class(sb-v-1-205))]`
> `VIEW[{wound_note_11}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-206), class(sb-sheet-small))]`
> `VIEW[{wound_11} ? "●" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-wound-marker), class(sb-v-1-207))]`
> `VIEW[{attack_1_weapon}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-208), class(sb-sheet-small))]`
> `VIEW[{attack_1_pool}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-209), class(sb-sheet-small))]`
> `VIEW[{attack_1_focus}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-210), class(sb-sheet-small))]`
> `VIEW[{attack_1_damage}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-211), class(sb-sheet-small))]`
> `VIEW[{attack_1_traits}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-212), class(sb-sheet-small))]`
> `VIEW[{wound_note_12}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-213), class(sb-sheet-small))]`
> `VIEW[{attack_2_weapon}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-214), class(sb-sheet-small))]`
> `VIEW[{attack_2_pool}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-215), class(sb-sheet-small))]`
> `VIEW[{attack_2_focus}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-216), class(sb-sheet-small))]`
> `VIEW[{attack_2_damage}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-217), class(sb-sheet-small))]`
> `VIEW[{attack_2_traits}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-218), class(sb-sheet-small))]`
> `VIEW[{wound_12} ? "●" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-wound-marker), class(sb-v-1-219))]`
> `VIEW[{attack_3_weapon}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-220), class(sb-sheet-small))]`
> `VIEW[{attack_3_pool}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-221), class(sb-sheet-small))]`
> `VIEW[{attack_3_focus}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-222), class(sb-sheet-small))]`
> `VIEW[{attack_3_damage}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-223), class(sb-sheet-small))]`
> `VIEW[{attack_3_traits}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-224), class(sb-sheet-small))]`
> `VIEW[{attack_4_weapon}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-225), class(sb-sheet-small))]`
> `VIEW[{attack_4_pool}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-226), class(sb-sheet-small))]`
> `VIEW[{attack_4_focus}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-227), class(sb-sheet-small))]`
> `VIEW[{attack_4_damage}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-228), class(sb-sheet-small))]`
> `VIEW[{attack_4_traits}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-229), class(sb-sheet-small))]`
> `VIEW[{mortally_wounded} ? "●" : ""][math(class(sb-sheet-field), class(sb-sheet-marker), class(sb-sheet-wound-marker), class(sb-v-1-230))]`
> `VIEW[{attack_5_weapon}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-231), class(sb-sheet-small))]`
> `VIEW[{attack_5_pool}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-232), class(sb-sheet-small))]`
> `VIEW[{attack_5_focus}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-233), class(sb-sheet-small))]`
> `VIEW[{attack_5_damage}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-234), class(sb-sheet-small))]`
> `VIEW[{attack_5_traits}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-1-235), class(sb-sheet-small))]`

> [!soulbound-page-2]
> `VIEW[{portrait}][image(class(sb-sheet-field), class(sb-sheet-image), class(sb-v-2-000))]`
> `VIEW[{background}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-001), class(sb-sheet-multiline))]`
> `VIEW[{notes}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-002), class(sb-sheet-multiline))]`
> `VIEW[{equipment_head}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-003), class(sb-sheet-small))]`
> `VIEW[{other_gear_1}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-004), class(sb-sheet-multiline))]`
> `VIEW[{other_gear_2}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-005), class(sb-sheet-multiline))]`
> `VIEW[{equipment_cloak}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-006), class(sb-sheet-small))]`
> `VIEW[{equipment_armour}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-007), class(sb-sheet-small))]`
> `VIEW[{equipment_right_hand}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-008), class(sb-sheet-small))]`
> `VIEW[{equipment_left_hand}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-009), class(sb-sheet-small))]`
> `VIEW[{equipment_arms}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-010), class(sb-sheet-small))]`
> `VIEW[{equipment_boots}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-011), class(sb-sheet-small))]`
> `VIEW[{equipment_jewellery}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-012), class(sb-sheet-small))]`
> `VIEW[{equipment_other_1}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-013), class(sb-sheet-small))]`
> `VIEW[{equipment_other_2}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-014), class(sb-sheet-small))]`
> `VIEW[{drops}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-015), class(sb-sheet-large))]`
> `VIEW[{phials}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-016), class(sb-sheet-large))]`
> `VIEW[{spheres}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-017), class(sb-sheet-large))]`
> `VIEW[{spell_1_name}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-018), class(sb-sheet-small))]`
> `VIEW[{spell_1_dn_cost}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-019), class(sb-sheet-small))]`
> `VIEW[{spell_1_target}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-020), class(sb-sheet-small))]`
> `VIEW[{spell_1_range}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-021), class(sb-sheet-small))]`
> `VIEW[{spell_1_duration}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-022), class(sb-sheet-small))]`
> `VIEW[{spell_1_effect}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-023), class(sb-sheet-small))]`
> `VIEW[{spell_2_name}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-024), class(sb-sheet-small))]`
> `VIEW[{spell_2_dn_cost}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-025), class(sb-sheet-small))]`
> `VIEW[{spell_2_target}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-026), class(sb-sheet-small))]`
> `VIEW[{spell_2_range}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-027), class(sb-sheet-small))]`
> `VIEW[{spell_2_duration}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-028), class(sb-sheet-small))]`
> `VIEW[{spell_2_effect}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-029), class(sb-sheet-small))]`
> `VIEW[{spell_3_name}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-030), class(sb-sheet-small))]`
> `VIEW[{spell_3_dn_cost}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-031), class(sb-sheet-small))]`
> `VIEW[{spell_3_target}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-032), class(sb-sheet-small))]`
> `VIEW[{spell_3_range}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-033), class(sb-sheet-small))]`
> `VIEW[{spell_3_duration}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-034), class(sb-sheet-small))]`
> `VIEW[{spell_3_effect}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-035), class(sb-sheet-small))]`
> `VIEW[{spell_4_name}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-036), class(sb-sheet-small))]`
> `VIEW[{spell_4_dn_cost}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-037), class(sb-sheet-small))]`
> `VIEW[{spell_4_target}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-038), class(sb-sheet-small))]`
> `VIEW[{spell_4_range}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-039), class(sb-sheet-small))]`
> `VIEW[{spell_4_duration}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-040), class(sb-sheet-small))]`
> `VIEW[{spell_4_effect}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-041), class(sb-sheet-small))]`
> `VIEW[{spell_5_name}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-042), class(sb-sheet-small))]`
> `VIEW[{spell_5_dn_cost}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-043), class(sb-sheet-small))]`
> `VIEW[{spell_5_target}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-044), class(sb-sheet-small))]`
> `VIEW[{spell_5_range}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-045), class(sb-sheet-small))]`
> `VIEW[{spell_5_duration}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-046), class(sb-sheet-small))]`
> `VIEW[{spell_5_effect}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-047), class(sb-sheet-small))]`
> `VIEW[{spell_6_name}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-048), class(sb-sheet-small))]`
> `VIEW[{spell_6_dn_cost}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-049), class(sb-sheet-small))]`
> `VIEW[{spell_6_target}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-050), class(sb-sheet-small))]`
> `VIEW[{spell_6_range}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-051), class(sb-sheet-small))]`
> `VIEW[{spell_6_duration}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-052), class(sb-sheet-small))]`
> `VIEW[{spell_6_effect}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-053), class(sb-sheet-small))]`
> `VIEW[{spell_7_name}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-054), class(sb-sheet-small))]`
> `VIEW[{spell_7_dn_cost}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-055), class(sb-sheet-small))]`
> `VIEW[{spell_7_target}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-056), class(sb-sheet-small))]`
> `VIEW[{spell_7_range}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-057), class(sb-sheet-small))]`
> `VIEW[{spell_7_duration}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-058), class(sb-sheet-small))]`
> `VIEW[{spell_7_effect}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-059), class(sb-sheet-small))]`
> `VIEW[{spell_8_name}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-060), class(sb-sheet-small))]`
> `VIEW[{spell_8_dn_cost}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-061), class(sb-sheet-small))]`
> `VIEW[{spell_8_target}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-062), class(sb-sheet-small))]`
> `VIEW[{spell_8_range}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-063), class(sb-sheet-small))]`
> `VIEW[{spell_8_duration}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-064), class(sb-sheet-small))]`
> `VIEW[{spell_8_effect}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-065), class(sb-sheet-small))]`
> `VIEW[{spell_9_name}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-066), class(sb-sheet-small))]`
> `VIEW[{spell_9_dn_cost}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-067), class(sb-sheet-small))]`
> `VIEW[{spell_9_target}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-068), class(sb-sheet-small))]`
> `VIEW[{spell_9_range}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-069), class(sb-sheet-small))]`
> `VIEW[{spell_9_duration}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-070), class(sb-sheet-small))]`
> `VIEW[{spell_9_effect}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-071), class(sb-sheet-small))]`
> `VIEW[{spell_10_name}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-072), class(sb-sheet-small))]`
> `VIEW[{spell_10_dn_cost}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-073), class(sb-sheet-small))]`
> `VIEW[{spell_10_target}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-074), class(sb-sheet-small))]`
> `VIEW[{spell_10_range}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-075), class(sb-sheet-small))]`
> `VIEW[{spell_10_duration}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-076), class(sb-sheet-small))]`
> `VIEW[{spell_10_effect}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-077), class(sb-sheet-small))]`
> `VIEW[{spell_11_name}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-078), class(sb-sheet-small))]`
> `VIEW[{spell_11_dn_cost}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-079), class(sb-sheet-small))]`
> `VIEW[{spell_11_target}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-080), class(sb-sheet-small))]`
> `VIEW[{spell_11_range}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-081), class(sb-sheet-small))]`
> `VIEW[{spell_11_duration}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-082), class(sb-sheet-small))]`
> `VIEW[{spell_11_effect}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-083), class(sb-sheet-small))]`
> `VIEW[{spell_12_name}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-084), class(sb-sheet-small))]`
> `VIEW[{spell_12_dn_cost}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-085), class(sb-sheet-small))]`
> `VIEW[{spell_12_target}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-086), class(sb-sheet-small))]`
> `VIEW[{spell_12_range}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-087), class(sb-sheet-small))]`
> `VIEW[{spell_12_duration}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-088), class(sb-sheet-small))]`
> `VIEW[{spell_12_effect}][text(class(sb-sheet-field), class(sb-sheet-text), class(sb-v-2-089), class(sb-sheet-small))]`
