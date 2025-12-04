## Current Status
**Act:** 1 - Stonewall
**Current Session:** [[session 1]] 
**Party Location:** [[Stonewall]] / [[Quathala]] / [[Immortal Bastion]]
**Last Session:** [[Session 0]]

---
## Campaign Structure Overview

### Act 1: Stonewall & Noxian Politics

**Aethera Power Level:** Imprisoned/Useless → Broken (0-5%) **Focus:** Regional conflict, Guy du Bas-Tyra's coup attempt, party gets Stonewall **Ends With:** Swain's coup, major downtime, Aethera begins manifesting physical form

### Act 2: Ionia & First Hunt

**Aethera Power Level:** Fractured Form (30-40%) **Focus:** Guy's redemption arc, Marduun's transformation, first Keth'vyss encounter **Ends With:** Return to Stonewall, major downtime, Aethera significantly strengthened

### Act 3: Loose Ends & Rising Power

**Aethera Power Level:** Restored Form (60-70%) **Focus:** Severing Hand pursuit, side plots, character development, preparation **Ends With:** Aethera at full strength, party empowered, ready for Keth'vyss hunt

### Act 4: The Hunt & Betrayal

**Aethera Power Level:** Full Power (95%+) **Focus:** Hunt for Keth'vyss, Aethera's betrayal, Lifestone revelation, final confrontation **Ends With:** Campaign conclusion - save or doom Runeterra

---
## To Do

### Next Session
- Aethera hinting like done in First Law with bayaz
- Demon whispers like when ferro touches the seed
### Feature
- Another Adventuring Day for road back to stonewall with Carnage Demon?
- Tease the severing hand in Ionia with another destroyed monastery
- Satisfying way for healing of Bennar

---
## Next Tasks from Act 1
```dataview
TASK
FROM "0 - Dashboard/Act 1 - Stonewall"
WHERE !completed
LIMIT 10
```

---

## This Session's NPCs
```dataview
TABLE relationship, status, importance
FROM "1 - Characters/NPC's"
WHERE location = "Quathala" AND status = "alive"
SORT importance DESC
```

**Manual Update:** Change `[current location]` to match where party is

---

## All Major NPCs (Reference)
```dataview
TABLE status, location, relationship, act-introduced
FROM "1 - Characters/NPC's"
WHERE importance = "major"
SORT act-introduced ASC
```

---

