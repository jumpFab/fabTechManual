---
title: Shopbot PRS alpha
description: Documentation for the Shopbot PRS alpha CNC Router
tags: [milling_cnc, shopbot, router]
---

# Shopbot PRS alpha


**Manufacturer**: Shopbot
**Model**:  PRS alpha
**Tool Type**: CNC Router


[Product Page](https://shopbottools.com/products/shopbot-prs5-alpha/)
[Manufacturer Manual](https://shopbottools.com/support-resources/documentation/shopbot-gantry-tools/)
[Software Download](https://shopbottools.com/support-resources/control-software/)

## Safety Requirements

!!! danger "Required PPE"
    - [ ] Eye protection
    - [ ] Ear protection
    - [ ] No loose clothing
    - [ ] Long hair tied back

!!! warning "Hazards"
    | Hazard | Mitigation |
    |--------|------------|
    | Open Gantry CNC Spindle | Never leave running unattended. Always be within arms reach of a stop or E-stop button. Do not reach into the tool while the tool is in motion. |
    | Dust Extraction | Cutting produces large amounts of sawdust. Always enable dust collection system.  |

!!! info "Emergency Stop"
    Location: operator station pendant or software stop


<!--[Link to detailed safety procedures](../safety/[tool-type]-safety.md) -->

---

## ShopBot Operational Checklist

### Prep
- [ ] Vacuum off the surface and check for nail heads or metal embedded in the spoil board.
- [ ] Confirm the bed is clean and flat.
- [ ] If nail heads are found, sand them off flush.
- [ ] If any metal found remove it before cutting.

### Machine Setup
- [ ] **Power on ShopBot:** rotate Yellow, Red switch to ON. (Key should be disabled at this time).
- [ ] Hit the **blue Reset button** on the control pendant at the work staiton.
- [ ] Open **Sb3 software**.
- [ ] Zero **X and Y** in the Position dialog window.
- [ ] Install the first tool, then insert and turn the key.
- [ ] **Spindle Warmup:** If this is the first cut of the day, run the routine: `Cuts` > `C5` in Sb3.
- [ ] **Zero Z-axis** (if zeroing from the machine bed).
- [ ] Move gantry aside for loading (e.g., move to `96, 42, 6`).
- [ ] Load material onto the bed and fasten securely.
- [ ] **Zero Z-axis** (if zeroing from the material surface instead of the bed).
- [ ] Install the **dust collector shoe**.
- [ ] Insert and engage the key.
- [ ] **Put on eye and ear protection.**

### Executing the Cut
- [ ] **Select toolpath file:**
    - Save directly from VCarve to ShopBot, OR
    - Choose `Cut Part` in Sb3 and open your file.
- [ ] Click **Start**.
- [ ] Verify tool number and Z-zero confirmation on screen.
- [ ] Start spindle by pressing the **Green Button** on the pendant.
- [ ] Manually engage dust collection if it does not start automatically.
- [ ] Press **OK** on the screen to begin the cut.

!!! warning "During the Cut"
    Watch and listen to the cut at all times. Hit the Space Bar on the computer to pause the operation. Use the E-Stop button immediately in case of an emergency.

### After Cut
- [ ] Turn off dust collector if not automatically disengaged.
- [ ] **Tool Changes:** If required, change the tool, re-zero the Z-axis, and repeat the cutting steps.

### Shutdown & Cleanup
- [ ] Park the gantry near the operator station.
- [ ] **Disengage key.**
- [ ] Vacuum dust from the cuts.
- [ ] Chisel any remaining tabs.
- [ ] Remove waste material from the bed.
- [ ] Remove the dust collection shoe.
- [ ] **Remove the tool** from the spindle.
- [ ] Power off the ShopBot.
- [ ] Vacuum the bed and surrounding area thoroughly.

## Software


### Required Software

<!--
| Software | Purpose  |
|----------|---------|
| Sb3 |  | [Machine Control Panel] |
| [Vcarve] | | [CAM toolpath generation] |


### Configuration Files

- [Machine configuration/profile](#)
- [Post-processor](#)
- [Material profiles](#)

### Installation Notes

```bash
# Any specific installation commands or paths
```

---

## Materials

### Approved Materials

| Material | Thickness | Settings | Notes |
|----------|-----------|----------|-------|
| [e.g., Birch Plywood] | [e.g., 3mm, 6mm] | [Link to settings] | [e.g., Use high speed, low power] |
| [e.g., PLA filament] | [1.75mm] | [Link to profiles] | [e.g., Bed temp 60°C] |

### Prohibited Materials

| Material | Reason |
|----------|--------|
| [e.g., PVC / Vinyl] | [e.g., Releases chlorine gas when cut] |
| [e.g., Carbon fiber] | [e.g., Damages equipment, health hazard] |

### Material Preparation

[How to prepare materials: securing, cleaning, etc.]

---


[Link to full maintenance schedule](maintenance.md)

---

## Operating Instructions

### Basic Operation

#### 1. Startup Procedure

1. [Step 1]
2. [Step 2]
3. [Step 3 with warning or note]

    !!! tip
        Helpful tip about this step

4. [Step 4]

#### 2. Loading/Preparing Work

```bash
# Example command or code snippet if applicable
```

#### 3. Running a Job

[Step-by-step with screenshots where helpful]

#### 4. Shutdown Procedure

1. [Step 1]
2. [Step 2]
3. [Step 3]

---

## Advanced Operations

### [Advanced Topic 1]

[Detailed instructions for advanced features]

### [Advanced Topic 2]

---

## Troubleshooting

| Symptom | Possible Cause | Solution |
|---------|---------------|----------|
| [e.g., Poor cut quality] | [e.g., Dull bit, wrong speed] | [e.g., Replace bit, adjust feeds/speeds] |
| [e.g., Failed prints] | [e.g., Bed not level] | [Re-level bed following procedure] |

[Link to detailed troubleshooting](troubleshooting.md)

---

## Maintenance

| Task | Frequency | Procedure | Last Completed |
|------|-----------|-----------|--------------|
| [e.g., Clean rails] | [Daily/Weekly/Monthly] | [Brief description] | [YYYY-MM-DD] |
| [e.g., Lubricate bearings] | [Hours of operation] | [Link to procedure] | [YYYY-MM-DD] |

[Link to full maintenance documentation](maintenance.md)

---

## Project Examples

<div class="grid cards" markdown>

-   [Project Name](../projects/[project].md)

    ---

    Brief description of what this project demonstrates.

    [:octicons-arrow-right-24: View project](../projects/[project].md)

</div>

---

## Resources

### Documentation

- [Manufacturer Manual](https://)
- [Manufacturer Support Forum](https://)
- [Community Wiki](https://)

### Internal Resources

- [Fab Lab maintenance log](./maintenance-log.md)
- [Material settings database](../../materials/)

### Training

- [Online training module](#)
- [In-person certification schedule](#)

---
-->
