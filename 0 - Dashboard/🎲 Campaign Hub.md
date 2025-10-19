## Current Status
**Act:** 1 - Stonewall
**Current Session:** [[session 1]] 
**Party Location:** [[Stonewall]] / [[Quathala]] / [[Immortal Bastion]]
**Last Session:** [[Session 0]]

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

