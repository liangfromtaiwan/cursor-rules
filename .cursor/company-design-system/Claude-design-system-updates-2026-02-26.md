**Dimensions:**
- Width (expanded): **256px**
- Width (collapsed): **64px**
- Height: 100vh
- Position: Fixed left

**Colors:**
- Background: `var(--sem-layer-sidebar)` = `var(--colors-sand-1)` (#fdfdfc, Warm Neutral/Neutral 1)
- Border-right: `1px solid var(--colors-sand-3)` (#f1f2f2, Warm Neutral/Neutral 3)

**Header:**
- Height: 56px (matches top header bar)
- Padding: `var(--spacing-4)` (16px)
- Border-bottom: `1px solid var(--sem-border-accent)`

**Menu Items:**
- Height: `var(--tokens-space-menu-item-height-2)` (32px) minimum
- Padding: `var(--spacing-2)` (8px) vertical, `var(--spacing-4)` (16px) horizontal
- Border-radius: `var(--radius-2)` (4px)
- Margin: `0 var(--spacing-2)` (8px) horizontal
- Gap: `var(--spacing-1)` (4px)

**Menu Item States:**
- **Default**: Background transparent, Text `--sem-text-secondary`, Icon `--sem-text-tertiary`
- **Hover**: Background `--sem-hover-bg` (`--colors-sand-3`), Text `--sem-text-primary`
- **Selected**: Background `--sem-brand-primary` (`--colors-equ-blue-9`), Text white, Font-weight 500

**Icons:**
- Size: 24px × 24px
- Margin-right: `var(--spacing-3)` (12px) from label

**Section Dividers:**
- Height: 1px
- Background: `var(--sem-divider)`
- Margin: `var(--spacing-4)` (16px) vertical

**Collapsed State (64px width):**
- Show icons only (centered)
- Logo remains same size
- No text labels
- **Tooltip on hover:**
  - Position: Right of icon (left: 64px)
  - Background: `var(--colors-sand-12)` (dark)
  - Text: white
  - Font: 13px, weight 500
  - Padding: 8px 12px
  - Border-radius: 4px
  - Offset: 8px from sidebar
  - Animation: fade in 150ms
  - No arrow
  - Content: Menu label (e.g., "ダッシュボード")

---

### 2. TOP HEADER BAR

**Dimensions:**
- Height: **56px**

**Colors:**
- Background: `var(--sem-layer-header)` = `var(--colors-sand-3)` (#f1f2f2)
- Border-bottom: `1px solid var(--sem-border-default)`

**Layout:**
- Padding: `0 var(--spacing-6)` (32px)
- Display: flex, items-center, justify-between

**Breadcrumbs:**
- Font-size: 13px
- Color: `var(--sem-text-secondary)`
- Separator: "/" with 8px margin

**Page Title:**
- Font-size: 24px
- Font-weight: 600
- Color: `var(--sem-text-primary)`
- Margin-top: 8px

**Search Bar:**
- Width: 320px
- Height: 32px
- Border: `1px solid var(--sem-border-default)`
- Border-radius: `var(--radius-2)` (4px)
- Placeholder: "検索する"

**Right Actions:**
- Icon buttons: 32px × 32px
- Border-radius: `var(--radius-2)`
- Hover: Background `--sem-hover-bg`
- Gap: 8px

---

### 2.5 MAIN CONTENT AREA

**Colors:**
- Background: `var(--sem-layer-main)` = `var(--colors-sand-1)` (#fdfdfc)

---

### 3. DRAWER FORM

**Dimensions:**
- Width: **720px**
- Height: 100vh
- Position: Fixed right

**Colors:**
- Background: `var(--sem-layer-1)` = `var(--colors-sand-1)` (#fdfdfc, Warm Neutral/Neutral 1)
- Box-shadow: `-4px 0 12px rgba(0,0,0,0.1)`
- Z-index: 1000

**Header:**
- Height: 64px
- Padding: `0 var(--spacing-6)` (32px)
- Border-bottom: `1px solid var(--sem-border-default)`
- Display: flex, align-items-center

**Close Button:**
- Size: 32px × 32px
- Icon: Left arrow or X (20px)
- Color: `var(--sem-text-tertiary)`
- Hover: Background `--sem-hover-bg`

**Title:**
- Font-size: 18px
- Font-weight: 600
- Margin-left: 12px

**Form Content:**
- Padding: `var(--spacing-6)` (32px)
- Overflow-y: auto
- Max-height: calc(100vh - 64px - 80px)

**Form Fields:**
- Margin-bottom: `var(--spacing-5)` (24px)
- Label: 13px, weight 600, `--sem-text-primary`
- Input: Height 32px, Border `--sem-input-border`
- Input focus: Border `--sem-input-border-focus` (`--colors-equ-blue-alpha-8`)
- Helper text: 12px, `--sem-text-secondary`

**Footer:**
- Height: 80px
- Position: Sticky bottom
- Background: `var(--sem-layer-1)`
- Border-top: `1px solid var(--sem-border-default)`
- Padding: `var(--spacing-4)` `var(--spacing-6)`
- Display: flex, justify-end
- Gap: 12px

**Buttons:**
- Cancel: Background transparent, Border `--sem-border-default`, Text `--sem-text-secondary`
- Submit: Background `--sem-btn-primary-bg`, Text white

---

### 4. TABLE VIEW

**Container:**
- Background: `var(--sem-layer-1)`
- Border-radius: `var(--radius-3)` (6px)
- Border: `1px solid var(--sem-border-default)`
- Margin: `var(--spacing-6)` (32px)

**Filter Bar:**
- Height: 56px
- Padding: `var(--spacing-4)` (16px)
- Background: `var(--sem-layer-1)`
- Border-bottom: `1px solid var(--sem-border-default)`

**Primary CTA (top-right):**
- Height: 32px
- Background: `--sem-btn-primary-bg`
- Color: white
- Font-size: 13px
- Padding: `0 var(--spacing-4)` (16px)
- Border-radius: `var(--radius-2)` (4px)
- Icon: Plus 16px

**Table Header:**
- Height: 48px
- Background: `--sem-table-header-bg`
- Border-bottom: `1px solid var(--sem-border-default)`
- Font-size: 13px
- Font-weight: 600
- Color: `--sem-text-secondary`

**Table Rows:**
- Height: 48px minimum
- Padding: 12px 16px
- Border-bottom: `1px solid var(--sem-border-default)`
- Font-size: 14px
- Hover: Background `--sem-table-row-hover` (`--colors-sand-3`)

**Status Badge:**
- Background: `--sem-badge-success-bg` (soft green)
- Color: `--sem-badge-success-text`
- Padding: 4px 8px
- Border-radius: 3px
- Font-size: 12px
- Font-weight: 500

**Kebab Menu:**
- Size: 32px × 32px
- Border-radius: 4px
- Hover: Background `--sem-hover-bg`
- Icon: Three dots (20px)

---

### 5. DIALOG / ALERT DIALOG

**Overlay:**
- Background: `var(--sem-layer-overlay)` (rgba(0,0,0,0.5))
- Position: Fixed, full screen

**Dialog Container:**
- Width: 480px (medium dialog)
- Background: `var(--sem-layer-1)`
- Border-radius: `var(--radius-3)` (6px)
- Box-shadow: `0 10px 40px rgba(0,0,0,0.2)`
- Position: Fixed center
- Padding: `var(--spacing-6)` (32px)

**Title:**
- Font-size: 18px
- Font-weight: 600
- Color: `--sem-text-primary`
- Margin-bottom: 12px

**Description:**
- Font-size: 14px
- Color: `--sem-text-secondary`
- Line-height: 1.5
- Margin-bottom: 24px

**Button Group:**
- Display: flex, justify-end
- Gap: 12px

---

## ADMIN LAYOUT GRID CONTRACT

All admin pages MUST follow this grid system.

### Global Container
- Max width: **1440px** (centered)
- Horizontal padding: **24px** (`--sem-space-6`)
- Vertical spacing: **`--sem-space-8`** between sections

### Desktop Grid (≥1024px)
- Type: **12-column grid**
- Column width: **32px** each
- Gap: **20px**
- **Allowed spans ONLY: 12 / 8 / 6 / 4 / 3**

| Use Case | Span |
|----------|------|
| Main content | 8–12 |
| Sidebar panel | 3–4 |
| Form full width | 12 |
| Form half width | 6 |
| Form third width | 4 |

### Table Layout
- Tables span **full width** (12 columns)
- Horizontal scroll if overflow
- Action column: **80–120px**, right-aligned

### Responsive Breakpoints
- **Mobile (<768px)**: 1 column, sidebar → overlay drawer
- **Tablet (768–1023px)**: 8 columns
- **Desktop (≥1024px)**: 12 columns

### Vertical Spacing
- Major blocks: `--sem-space-8` (48px)
- Related groups: `--sem-space-6` (32px)
- Form fields: `--sem-space-4` (16px)

### Sidebar Behavior
- Desktop expanded: 256px
- Desktop collapsed: 64px (tooltip on hover)
- Mobile: overlay drawer with backdrop

### Dialog Widths
- Small: 400px
- Medium: 600px
- Large: 800px
- Padding: `--sem-space-6`
- Always centered

---

## USAGE GUIDELINES

### Token Priority

```
1st: --sem-*           ← ALWAYS USE FIRST
2nd: --tokens-*        ← Component-specific
3rd: --spacing-*, --radius-*
4th: --colors-*        ← Only when no semantic exists
❌ Never: hardcoded values
```

### Color Usage

| Situation | ✅ Use | Value |
|-----------|--------|-------|
| Sidebar/Drawer bg | `--sem-layer-sidebar` | `--colors-sand-1` (#fdfdfc) |
| Header bg | `--sem-layer-header` | `--colors-sand-3` (#f1f2f2) |
| Main content bg | `--sem-layer-main` | `--colors-sand-1` (#fdfdfc) |
| Page bg | `--sem-bg-canvas` | `--colors-sand-2` |
| Primary button | `--sem-btn-primary-bg` | `--colors-equ-blue-9` |
| Danger button | `--sem-btn-danger-bg` | `--colors-red-red-9` |
| Primary text | `--sem-text-primary` | `--colors-sand-12` |
| Secondary text | `--sem-text-secondary` | `--colors-sand-11` |
| Border default | `--sem-border-default` | `--colors-sand-6` |
| Border accent | `--sem-border-accent` | `--colors-sand-3` (#f1f2f2) |
| Hover bg | `--sem-hover-bg` | `--colors-sand-3` |
| Input border | `--sem-input-border` | `--colors-sand-6` |
| Input focus/active | `--sem-input-border-focus` | `--colors-equ-blue-alpha-8` |
| Focus ring | `--sem-focus-ring` | `--colors-equ-blue-alpha-8` |

### Spacing Usage
- Tight: `--sem-space-1` (4px)
- Form fields: `--sem-space-4` (16px)
- Section padding: `--sem-space-6` (32px)
- Major blocks: `--sem-space-8` (48px)

### Radius Usage
- Buttons, inputs: `--sem-radius-sm` (4px)
- Cards, dialogs: `--sem-radius-md` (6px)
- Pills: `--sem-radius-full`

---

## COMPONENT RULES

### Buttons
- Variants: primary / secondary / danger
- **Only ONE primary per view**
- Heights: 32px (default), 24px (small), 40px (large)
- Use semantic tokens

### Forms
- All inputs have labels
- Error messages below input
- Helper text optional
- Focus ring: `--sem-focus-ring`
- Focus/Active border: `--sem-input-border-focus`

### Tables
- Row height: 48px
- Header bg: `--sem-table-header-bg`
- Row hover: `--sem-table-row-hover`
- Border: `--sem-table-border`

---

## STATES

Every interactive component must support:
- default
- hover
- active
- focus-visible
- disabled
- loading (if async)
- error (if form)

---

## IMPLEMENTATION GUARDRAILS

### CSS Rules
- **ALWAYS use `--sem-*` tokens first**
- Never hardcode hex, px, rgba
- Use spacing/radius scale tokens only

### Component Policy
- ALWAYS use Radix UI first
- Style with semantic tokens
- Never override accessibility
- Maintain keyboard nav and ARIA

### Accessibility
- Keyboard navigable
- Visible focus ring (`--sem-focus-ring`)
- Proper ARIA
- Dialog focus trap

---

## OUTPUT STRUCTURE

When generating UI:
1. Read semantic tokens (`--sem-*`)
2. Check layout grid contract
3. Identify Radix UI components
4. Plan structure
5. Implement with semantic tokens
6. Verify all states

---

**Updated**: 2026-02-26