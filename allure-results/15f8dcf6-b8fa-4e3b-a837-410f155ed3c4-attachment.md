# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: tests/uiComponents.spec.ts >> Form Layouts page >> radio buttons
- Location: tests/uiComponents.spec.ts:36:9

# Error details

```
Error: expect(locator).toHaveScreenshot(expected) failed

Locator: locator('nb-card').filter({ hasText: 'Using the Grid' })
  Expected an image 461px by 383px, received 459px by 383px. 487 pixels (ratio 0.01 of all image pixels) are different.

Call log:
  - Expect "toHaveScreenshot" with timeout 2000ms
    - verifying given screenshot expectation
  - waiting for locator('nb-card').filter({ hasText: 'Using the Grid' })
    - locator resolved to <nb-card _nghost-cbc-c98="" _ngcontent-cbc-c290="">…</nb-card>
  - taking element screenshot
    - disabled all CSS animations
  - waiting for fonts to load...
  - fonts loaded
  - attempting scroll into view action
    - waiting for element to be stable
  - Expected an image 461px by 383px, received 459px by 383px. 487 pixels (ratio 0.01 of all image pixels) are different.
  - waiting 100ms before taking screenshot
  - waiting for locator('nb-card').filter({ hasText: 'Using the Grid' })
    - locator resolved to <nb-card _nghost-cbc-c98="" _ngcontent-cbc-c290="">…</nb-card>
  - taking element screenshot
    - disabled all CSS animations
  - waiting for fonts to load...
  - fonts loaded
  - attempting scroll into view action
    - waiting for element to be stable
  - captured a stable screenshot
  - Expected an image 461px by 383px, received 459px by 383px. 487 pixels (ratio 0.01 of all image pixels) are different.

```

# Page snapshot

```yaml
- generic [ref=f110e7]:
  - navigation [ref=f110e9]:
    - generic [ref=f110e10]:
      - generic [ref=f110e11]:
        - generic [ref=f110e12]:
          - link [ref=f110e13] [cursor=pointer]:
            - /url: "#"
          - link "PW-test" [ref=f110e23] [cursor=pointer]:
            - /url: "#"
        - button "Light" [ref=f110e25] [cursor=pointer]
      - generic [ref=f110e34]:
        - button [ref=f110e37] [cursor=pointer]
        - link [ref=f110e45] [cursor=pointer]:
          - /url: "#"
        - link [ref=f110e53] [cursor=pointer]:
          - /url: "#"
        - generic [ref=f110e60]: Nick Jones
  - generic [ref=f110e66]:
    - list [ref=f110e71]:
      - listitem [ref=f110e72]:
        - link "IoT Dashboard" [ref=f110e73] [cursor=pointer]:
          - /url: /pages/iot-dashboard
      - listitem [ref=f110e80]:
        - generic [ref=f110e81]: FEATURES
      - listitem [ref=f110e82]:
        - link "Forms" [expanded] [ref=f110e83] [cursor=pointer]:
          - /url: "#"
        - list [ref=f110e97]:
          - listitem [ref=f110e98]:
            - link "Form Layouts" [ref=f110e99] [cursor=pointer]:
              - /url: /pages/forms/layouts
          - listitem [ref=f110e100]:
            - link "Datepicker" [ref=f110e101] [cursor=pointer]:
              - /url: /pages/forms/datepicker
      - listitem [ref=f110e102]:
        - link "Modal & Overlays" [ref=f110e103] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f110e118]:
            - link "Dialog" [ref=f110e119] [cursor=pointer]:
              - /url: /pages/modal-overlays/dialog
          - listitem [ref=f110e120]:
            - link "Window" [ref=f110e121] [cursor=pointer]:
              - /url: /pages/modal-overlays/window
          - listitem [ref=f110e122]:
            - link "Popover" [ref=f110e123] [cursor=pointer]:
              - /url: /pages/modal-overlays/popover
          - listitem [ref=f110e124]:
            - link "Toastr" [ref=f110e125] [cursor=pointer]:
              - /url: /pages/modal-overlays/toastr
          - listitem [ref=f110e126]:
            - link "Tooltip" [ref=f110e127] [cursor=pointer]:
              - /url: /pages/modal-overlays/tooltip
      - listitem [ref=f110e128]:
        - link "Extra Components" [ref=f110e129] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f110e145]:
            - link "Calendar" [ref=f110e146] [cursor=pointer]:
              - /url: /pages/extra-components/calendar
      - listitem [ref=f110e147]:
        - link "Charts" [ref=f110e148] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f110e162]:
            - link "Echarts" [ref=f110e163] [cursor=pointer]:
              - /url: /pages/charts/echarts
      - listitem [ref=f110e164]:
        - link "Tables & Data" [ref=f110e165] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f110e181]:
            - link "Smart Table" [ref=f110e182] [cursor=pointer]:
              - /url: /pages/tables/smart-table
          - listitem [ref=f110e183]:
            - link "Tree Grid" [ref=f110e184] [cursor=pointer]:
              - /url: /pages/tables/tree-grid
      - listitem [ref=f110e185]:
        - link "Auth" [ref=f110e186] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f110e200]:
            - link "Login" [ref=f110e201] [cursor=pointer]:
              - /url: /auth/login
          - listitem [ref=f110e202]:
            - link "Register" [ref=f110e203] [cursor=pointer]:
              - /url: /auth/register
          - listitem [ref=f110e204]:
            - link "Request Password" [ref=f110e205] [cursor=pointer]:
              - /url: /auth/request-password
          - listitem [ref=f110e206]:
            - link "Reset Password" [ref=f110e207] [cursor=pointer]:
              - /url: /auth/reset-password
    - generic [ref=f110e208]:
      - generic [ref=f110e212]:
        - generic [ref=f110e215]:
          - generic [ref=f110e216]: Inline form
          - generic [ref=f110e218]:
            - textbox "Jane Doe" [ref=f110e219]
            - textbox "Email" [ref=f110e220]
            - generic [ref=f110e222]:
              - checkbox "Remember me" [ref=f110e223]
              - generic [ref=f110e225]: Remember me
            - button "Submit" [ref=f110e226] [cursor=pointer]
        - generic [ref=f110e227]:
          - generic [ref=f110e228]:
            - generic [ref=f110e229]:
              - generic [ref=f110e230]: Using the Grid
              - generic [ref=f110e232]:
                - generic [ref=f110e233]:
                  - generic [ref=f110e234]: Email
                  - textbox "Email" [ref=f110e236]
                - generic [ref=f110e237]:
                  - generic [ref=f110e238]: Password
                  - textbox "Password" [ref=f110e240]
                - generic [ref=f110e241]:
                  - generic [ref=f110e242]: Radios
                  - generic [ref=f110e244]:
                    - generic [ref=f110e246]:
                      - radio "Option 1" [ref=f110e247]
                      - generic [ref=f110e250]: Option 1
                    - generic [ref=f110e252]:
                      - radio "Option 2" [checked] [active] [ref=f110e253]
                      - generic [ref=f110e256]: Option 2
                    - generic [ref=f110e258]:
                      - radio "Disabled Option" [disabled] [ref=f110e259]
                      - generic [ref=f110e262]: Disabled Option
                - button "Sign in" [ref=f110e265] [cursor=pointer]
            - generic [ref=f110e266]:
              - generic [ref=f110e267]: Form without labels
              - generic [ref=f110e269]:
                - textbox "Recipients" [ref=f110e271]
                - textbox "Subject" [ref=f110e273]
                - textbox "Message" [ref=f110e275]
                - button "Send" [ref=f110e276] [cursor=pointer]
          - generic [ref=f110e277]:
            - generic [ref=f110e278]:
              - generic [ref=f110e279]: Basic form
              - generic [ref=f110e281]:
                - generic [ref=f110e282]:
                  - generic [ref=f110e283]: Email address
                  - textbox "Email address" [ref=f110e284]:
                    - /placeholder: Email
                - generic [ref=f110e285]:
                  - generic [ref=f110e286]: Password
                  - textbox "Password" [ref=f110e287]
                - generic [ref=f110e290]:
                  - checkbox "Check me out" [ref=f110e291]
                  - generic [ref=f110e293]: Check me out
                - button "Submit" [ref=f110e294] [cursor=pointer]
            - generic [ref=f110e295]:
              - generic [ref=f110e296]: Block form
              - generic [ref=f110e297]:
                - generic [ref=f110e298]:
                  - generic [ref=f110e300]:
                    - generic [ref=f110e301]: First Name
                    - textbox "First Name" [ref=f110e302]
                  - generic [ref=f110e304]:
                    - generic [ref=f110e305]: Last Name
                    - textbox "Last Name" [ref=f110e306]
                - generic [ref=f110e307]:
                  - generic [ref=f110e309]:
                    - generic [ref=f110e310]: Email
                    - textbox "Email" [ref=f110e311]
                  - generic [ref=f110e313]:
                    - generic [ref=f110e314]: Website
                    - textbox "Website" [ref=f110e315]
                - button "Submit" [ref=f110e316] [cursor=pointer]
        - generic [ref=f110e319]:
          - generic [ref=f110e320]: Horizontal form
          - generic [ref=f110e322]:
            - generic [ref=f110e323]:
              - generic [ref=f110e324]: Email
              - textbox "Email" [ref=f110e326]
            - generic [ref=f110e327]:
              - generic [ref=f110e328]: Password
              - textbox "Password" [ref=f110e330]
            - generic [ref=f110e335]:
              - checkbox "Remember me" [ref=f110e336]
              - generic [ref=f110e338]: Remember me
            - button "Sign in" [ref=f110e341] [cursor=pointer]
      - navigation [ref=f110e343]:
        - generic [ref=f110e344]:
          - generic [ref=f110e345]:
            - text: Created with ♥ by
            - link "Akveo" [ref=f110e347] [cursor=pointer]:
              - /url: https://akveo.page.link/8V2f
            - text: "2019"
          - generic [ref=f110e348]:
            - link "" [ref=f110e349] [cursor=pointer]:
              - /url: "#"
            - link "" [ref=f110e350] [cursor=pointer]:
              - /url: "#"
            - link "" [ref=f110e351] [cursor=pointer]:
              - /url: "#"
            - link "" [ref=f110e352] [cursor=pointer]:
              - /url: "#"
```

# Test source

```ts
  1   | import { test, expect } from '@playwright/test'
  2   | 
  3   | test.describe.configure({ mode: 'parallel' })
  4   | 
  5   | test.beforeEach(async ({ page }) => {
  6   |     await page.goto('/')
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
> 42  |         await expect(usingTheGridForm).toHaveScreenshot({ maxDiffPixels: 250 })
      |                                        ^ Error: expect(locator).toHaveScreenshot(expected) failed
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
  107 |     test('dialog box', async ({ page }) => {
  108 |         await page.getByText('Tables & Data').click()
  109 |         await page.getByText('Smart Table').click()
  110 | 
  111 |         page.on('dialog', dialog => {
  112 |             expect(dialog.message()).toEqual('Are you sure you want to delete?')
  113 |             dialog.accept()
  114 |         })
  115 | 
  116 |         await page.getByRole('table').locator('tr', { hasText: "mdo@gmail.com" }).locator('.nb-trash').click()
  117 |         await expect(page.locator('table tr').first()).not.toHaveText('mdo@gmail.com')
  118 |     })
  119 | 
  120 |     test('web tables', async ({ page }) => {
  121 |         await page.getByText('Tables & Data').click()
  122 |         await page.getByText('Smart Table').click()
  123 | 
  124 |         //1 get the row by any text in this row
  125 |         const targetRow = page.getByRole('row', { name: "twitter@outlook.com" })
  126 |         await targetRow.locator('.nb-edit').click()
  127 |         await page.locator('input-editor').getByPlaceholder('Age').clear()
  128 |         await page.locator('input-editor').getByPlaceholder('Age').fill('35')
  129 |         await page.locator('.nb-checkmark').click()
  130 | 
  131 |         //2 get the row based on the value in the specific column
  132 |         await page.locator('.ng2-smart-pagination-nav').getByText('2').click()
  133 |         const targetRowById = page.getByRole('row', { name: "11" }).filter({ has: page.locator('td').nth(1).getByText('11') })
  134 |         await targetRowById.locator('.nb-edit').click()
  135 |         await page.locator('input-editor').getByPlaceholder('E-mail').clear()
  136 |         await page.locator('input-editor').getByPlaceholder('E-mail').fill('test@test.com')
  137 |         await page.locator('.nb-checkmark').click()
  138 |         await expect(targetRowById.locator('td').nth(5)).toHaveText('test@test.com')
  139 | 
  140 |         //3 test filter of the table
  141 | 
  142 |         const ages = ["20", "30", "40", "200"]
```