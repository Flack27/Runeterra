## Description

Quathala is the seat of Baron [[Roderick Voss]]'s domain, a once-prosperous Noxian city now caught between ambitious beautification projects and growing civil unrest. The city showcases a jarring contrast between expensive marble facades and suffering citizens, reflecting the psychological state of its traumatized ruler.

## Locations
```dataview
TABLE status, importance
FROM "2 - Locations/Noxus/Quathala"
WHERE parent-location = "[[Quathala]]" OR contains(file.path, "Quathala")
SORT importance DESC, file.name ASC
```

## Active NPCs
```dataview
TABLE relationship, status, importance
FROM "1 - Characters/NPC's"
WHERE type = "npc" AND location = "Quathala"
SORT importance DESC
```

## Current Situation

- **Beautification Obsession:** Marble construction and canal projects bankrupting the treasury while citizens struggle with high taxes
- **No Military:** Entire garrison abandoned after commandant's dismissal, leaving city defenseless against bandits
- **Growing Unrest:** Citizens openly complaining about "marble over bread" policies, minor protests occurring
- **Matthias' Control:** Baron increasingly isolated and dependent on his advisor's guidance
- **External Interest:** Unknown agents (Guy's people) quietly assessing the city's vulnerabilities

## Rumors & Gossip

**General Topics:**

- Baron Roderick's mental state and erratic behavior
- The dismissed commandant and garrison abandonment
- The expensive beautification projects bankrupting the city

**Current Complaints:**

- Taxes too high to afford basic necessities
- Roads unsafe without military patrols - bandits increasing
- Construction noise and disruption from marble work
- Local businesses failing while imported materials arrive
- No protection for merchant caravans or travelers
- Neighbors organizing watch groups since guards are gone

