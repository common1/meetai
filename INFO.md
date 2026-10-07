# Project meetai

## 1 - Setup

```
[https://www.youtube.com/watch?v=xEDCEmqyvC8&t=337s]
```

### 1.1 Create project
```
npx create-next-app@15.3.2
√ What is your project named? ... meetai
√ Would you like to use TypeScript? ... Yes
√ Would you like to use ESLint? ... Yes
√ Would you like to use Tailwind CSS? ... Yes
√ Would you like your code inside a `src/` directory? ... Yes
√ Would you like to use App Router? (recommended) ... Yes
√ Would you like to use Turbopack for `next dev`? ... Yes
? Would you like to customize the import alias (`@/*` by default)? » No
```

### 1.2 Install shadcn

```
npx shadcn@4.21.3 init
Need to install the following packages:
shadcn@4.21.3
Ok to proceed? (y) y

√ Select a component library » Radix UI
√ Which preset would you like to use? » Nova
✔ Preflight checks.
✔ Verifying framework. Found Next.js.
✔ Validating Tailwind CSS. Found v4.
✔ Validating import alias.
✔ Writing components.json.
✔ Checking registry.
✔ Installing dependencies.
✔ Updating fonts.
✔ Created 2 files:
  - src\components\ui\button.tsx
  - src\lib\utils.ts
✔ Updating src\app\globals.css

Project initialization completed.
You may now add components.
```

### 1.3 Add components

```
npx shadcn@4.21.3 add --all --overwrite
√ You need to create a components.json file to add components. Proceed? ... yes
√ Select a component library » Radix UI
√ Which preset would you like to use? » Nova
✔ Preflight checks.
✔ Verifying framework. Found Next.js.
✔ Validating Tailwind CSS. Found v4.
✔ Validating import alias.
✔ Writing components.json.
✔ Checking registry.
✔ Installing dependencies.
✔ Updating fonts.
✔ Created 63 files:
  - src\components\ui\accordion.tsx
  - src\components\ui\alert.tsx
  - src\components\ui\aspect-ratio.tsx
  - src\components\ui\avatar.tsx
  - src\components\ui\badge.tsx
  - src\components\ui\breadcrumb.tsx
  - src\components\ui\bubble.tsx
  - src\components\ui\button.tsx
  - src\components\ui\card.tsx
  - src\components\ui\chart.tsx
  - src\components\ui\checkbox.tsx
  - src\components\ui\collapsible.tsx
  - src\components\ui\context-menu.tsx
  - src\components\ui\direction.tsx
  - src\components\ui\drawer.tsx
  - src\components\ui\dropdown-menu.tsx
  - src\components\ui\empty.tsx
  - src\components\ui\hover-card.tsx
  - src\components\ui\input.tsx
  - src\components\ui\input-otp.tsx
  - src\components\ui\kbd.tsx
  - src\components\ui\label.tsx
  - src\components\ui\marker.tsx
  - src\components\ui\menubar.tsx
  - src\components\ui\message.tsx
  - src\components\ui\native-select.tsx
  - src\components\ui\navigation-menu.tsx
  - src\components\ui\popover.tsx
  - src\components\ui\progress.tsx
  - src\components\ui\radio-group.tsx
  - src\components\ui\resizable.tsx
  - src\components\ui\scroll-area.tsx
  - src\components\ui\select.tsx
  - src\components\ui\separator.tsx
  - src\components\ui\skeleton.tsx
  - src\components\ui\slider.tsx
  - src\components\ui\sonner.tsx
  - src\components\ui\spinner.tsx
  - src\components\ui\switch.tsx
  - src\components\ui\table.tsx
  - src\components\ui\tabs.tsx
  - src\components\ui\textarea.tsx
  - src\components\ui\toggle.tsx
  - src\components\ui\tooltip.tsx
  - src\lib\utils.ts
  - src\hooks\use-mobile.ts
  - src\components\ui\alert-dialog.tsx
  - src\components\ui\attachment.tsx
  - src\components\ui\calendar.tsx
  - src\components\ui\carousel.tsx
  - src\components\ui\dialog.tsx
  - src\components\ui\message-scroller.tsx
  - src\components\ui\pagination.tsx
  - src\components\ui\questionnaire.tsx
  - src\components\ui\sheet.tsx
  - src\components\ui\button-group.tsx
  - src\components\ui\field.tsx
  - src\components\ui\item.tsx
  - src\components\ui\input-group.tsx
  - src\components\ui\toggle-group.tsx
  - src\components\ui\sidebar.tsx
  - src\components\ui\combobox.tsx
  - src\components\ui\command.tsx
✔ Updating src\app\globals.css
```

