# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: tests/uiComponents.spec.ts >> Form Layouts page >> radio buttons
- Location: tests/uiComponents.spec.ts:36:9

# Error details

```
Test timeout of 4000ms exceeded while running "beforeEach" hook.
```

```
Error: page.goto: Test timeout of 4000ms exceeded.
Call log:
  - navigating to "http://localhost:4200/", waiting until "load"

```

# Test source

```ts
  1   | import { test, expect } from '@playwright/test'
  2   | 
  3   | test.describe.configure({ mode: 'parallel' })
  4   | 
  5   | test.beforeEach(async ({ page }) => {
> 6   |     await page.goto('/')
      |                ^ Error: page.goto: Test timeout of 4000ms exceeded.
  7   | })
  8   | 
  9   | test.describe('Form Layouts page', () => {
  10  |     test.describe.configure({ retries: 2 })
  11  |     test.describe.configure({ mode: 'serial' })
  12  | 
  13  |     test.beforeEach(async ({ page }) => {
  14  |         await page.getByText('Forms').click()
  15  |         await page.getByText('Form Layouts').click()
  16  |     })
  17  | 
  18  |     test('input fields', async ({ page }, testInfo) => {
  19  |         if (testInfo.retry) {
  20  |             //do something
  21  |         }
  22  |         const usingTheGridEmailInput = page.locator('nb-card', { hasText: "Using the Grid" }).getByRole('textbox', { name: "Email" })
  23  | 
  24  |         await usingTheGridEmailInput.fill('test@test.com')
  25  |         await usingTheGridEmailInput.clear()
  26  |         await usingTheGridEmailInput.type('test2@test.com')
  27  | 
  28  |         //generic assertion
  29  |         const inputValue = await usingTheGridEmailInput.inputValue()
  30  |         expect(inputValue).toEqual('test2@test.com')
  31  | 
  32  |         //locator assertion
  33  |         await expect(usingTheGridEmailInput).toHaveValue('test2@test.com')
  34  |     })
  35  | 
  36  |     test('radio buttons', async ({ page }) => {
  37  |         const usingTheGridForm = page.locator('nb-card', { hasText: "Using the Grid" })
  38  | 
  39  |         // await usingTheGridForm.getByLabel('Option 1').check({ force: true })
  40  |         await usingTheGridForm.getByRole('radio', { name: "Option 2" }).check({ force: true })
  41  |         const radioStatus = await usingTheGridForm.getByRole('radio', { name: "Option 1" }).isChecked()
  42  |         await expect(usingTheGridForm).toHaveScreenshot({ maxDiffPixels: 250 })
  43  |         // expect(radioStatus).toBeTruthy()
  44  |         // await expect(usingTheGridForm.getByRole('radio', { name: "Option 1" })).toBeChecked()
  45  | 
  46  |         // await usingTheGridForm.getByRole('radio', { name: "Option 2" }).check({ force: true })
  47  |         // expect(await usingTheGridForm.getByRole('radio', { name: "Option 1" }).isChecked()).toBeFalsy()
  48  |         // expect(await usingTheGridForm.getByRole('radio', { name: "Option 2" }).isChecked()).toBeTruthy()
  49  |     })
  50  | 
  51  |     test('checkboxes', async ({ page }) => {
  52  |         await page.getByText('Modal & Overlays').click()
  53  |         await page.getByText('Toastr').click()
  54  | 
  55  |         await page.getByRole('checkbox', { name: "Hide on click" }).uncheck({ force: true })
  56  |         await page.getByRole('checkbox', { name: "Prevent arising of duplicate toast" }).check({ force: true })
  57  | 
  58  |         const allBoxes = page.getByRole('checkbox')
  59  |         for (const box of await allBoxes.all()) {
  60  |             await box.uncheck({ force: true })
  61  |             expect(await box.isChecked()).toBeFalsy()
  62  |         }
  63  |     })
  64  | 
  65  |     test('lists and dropdowns', async ({ page }) => {
  66  |         const dropDownMenu = page.locator('ngx-header nb-select')
  67  |         await dropDownMenu.click()
  68  | 
  69  |         page.getByRole('list') //when the list has a UL tag
  70  |         page.getByRole('listitem') //when the list has LI tag
  71  | 
  72  |         //const optionList = page.getByRole('list').locator('nb-option')
  73  |         const optionList = page.locator('nb-option-list nb-option')
  74  |         await expect(optionList).toHaveText(["Light", "Dark", "Cosmic", "Corporate"])
  75  |         await optionList.filter({ hasText: "Cosmic" }).click()
  76  |         const header = page.locator('nb-layout-header')
  77  |         await expect(header).toHaveCSS('background-color', 'rgb(50, 50, 89)')
  78  | 
  79  |         const colors = {
  80  |             "Light": "rgb(255, 255, 255)",
  81  |             "Dark": "rgb(34, 43, 69)",
  82  |             "Cosmic": "rgb(50, 50, 89)",
  83  |             "Corporate": "rgb(255, 255, 255)"
  84  |         }
  85  | 
  86  |         await dropDownMenu.click()
  87  |         for (const color in colors) {
  88  |             await optionList.filter({ hasText: color }).click()
  89  |             await expect(header).toHaveCSS('background-color', colors[color as keyof typeof colors])
  90  |             if (color != "Corporate")
  91  |                 await dropDownMenu.click()
  92  |         }
  93  |     })
  94  | 
  95  |     test('tooltips', async ({ page }) => {
  96  |         await page.getByText('Modal & Overlays').click()
  97  |         await page.getByText('Tooltip').click()
  98  | 
  99  |         const toolTipCard = page.locator('nb-card', { hasText: "Tooltip Placements" })
  100 |         await toolTipCard.getByRole('button', { name: "Top" }).hover()
  101 | 
  102 |         page.getByRole('tooltip') //if you have a role tooltip created
  103 |         const tooltip = await page.locator('nb-tooltip').textContent()
  104 |         expect(tooltip).toEqual('This is a tooltip')
  105 |     })
  106 | 
```