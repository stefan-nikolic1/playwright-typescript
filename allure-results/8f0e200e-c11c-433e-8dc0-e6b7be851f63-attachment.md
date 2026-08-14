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
    - locator resolved to <nb-card _nghost-kqt-c98="" _ngcontent-kqt-c290="">…</nb-card>
  - taking element screenshot
    - disabled all CSS animations
  - waiting for fonts to load...
  - fonts loaded
  - attempting scroll into view action
    - waiting for element to be stable
  - Expected an image 461px by 383px, received 459px by 383px. 487 pixels (ratio 0.01 of all image pixels) are different.
  - waiting 100ms before taking screenshot
  - waiting for locator('nb-card').filter({ hasText: 'Using the Grid' })
    - locator resolved to <nb-card _nghost-kqt-c98="" _ngcontent-kqt-c290="">…</nb-card>
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
- generic [ref=f49e7]:
  - navigation [ref=f49e9]:
    - generic [ref=f49e10]:
      - generic [ref=f49e11]:
        - generic [ref=f49e12]:
          - link [ref=f49e13] [cursor=pointer]:
            - /url: "#"
          - link "PW-test" [ref=f49e23] [cursor=pointer]:
            - /url: "#"
        - button "Light" [ref=f49e25] [cursor=pointer]
      - generic [ref=f49e34]:
        - button [ref=f49e37] [cursor=pointer]
        - link [ref=f49e45] [cursor=pointer]:
          - /url: "#"
        - link [ref=f49e53] [cursor=pointer]:
          - /url: "#"
        - generic [ref=f49e60]: Nick Jones
  - generic [ref=f49e66]:
    - list [ref=f49e71]:
      - listitem [ref=f49e72]:
        - link "IoT Dashboard" [ref=f49e73] [cursor=pointer]:
          - /url: /pages/iot-dashboard
      - listitem [ref=f49e80]:
        - generic [ref=f49e81]: FEATURES
      - listitem [ref=f49e82]:
        - link "Forms" [expanded] [ref=f49e83] [cursor=pointer]:
          - /url: "#"
        - list [ref=f49e97]:
          - listitem [ref=f49e98]:
            - link "Form Layouts" [ref=f49e99] [cursor=pointer]:
              - /url: /pages/forms/layouts
          - listitem [ref=f49e100]:
            - link "Datepicker" [ref=f49e101] [cursor=pointer]:
              - /url: /pages/forms/datepicker
      - listitem [ref=f49e102]:
        - link "Modal & Overlays" [ref=f49e103] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f49e118]:
            - link "Dialog" [ref=f49e119] [cursor=pointer]:
              - /url: /pages/modal-overlays/dialog
          - listitem [ref=f49e120]:
            - link "Window" [ref=f49e121] [cursor=pointer]:
              - /url: /pages/modal-overlays/window
          - listitem [ref=f49e122]:
            - link "Popover" [ref=f49e123] [cursor=pointer]:
              - /url: /pages/modal-overlays/popover
          - listitem [ref=f49e124]:
            - link "Toastr" [ref=f49e125] [cursor=pointer]:
              - /url: /pages/modal-overlays/toastr
          - listitem [ref=f49e126]:
            - link "Tooltip" [ref=f49e127] [cursor=pointer]:
              - /url: /pages/modal-overlays/tooltip
      - listitem [ref=f49e128]:
        - link "Extra Components" [ref=f49e129] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f49e145]:
            - link "Calendar" [ref=f49e146] [cursor=pointer]:
              - /url: /pages/extra-components/calendar
      - listitem [ref=f49e147]:
        - link "Charts" [ref=f49e148] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f49e162]:
            - link "Echarts" [ref=f49e163] [cursor=pointer]:
              - /url: /pages/charts/echarts
      - listitem [ref=f49e164]:
        - link "Tables & Data" [ref=f49e165] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f49e181]:
            - link "Smart Table" [ref=f49e182] [cursor=pointer]:
              - /url: /pages/tables/smart-table
          - listitem [ref=f49e183]:
            - link "Tree Grid" [ref=f49e184] [cursor=pointer]:
              - /url: /pages/tables/tree-grid
      - listitem [ref=f49e185]:
        - link "Auth" [ref=f49e186] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f49e200]:
            - link "Login" [ref=f49e201] [cursor=pointer]:
              - /url: /auth/login
          - listitem [ref=f49e202]:
            - link "Register" [ref=f49e203] [cursor=pointer]:
              - /url: /auth/register
          - listitem [ref=f49e204]:
            - link "Request Password" [ref=f49e205] [cursor=pointer]:
              - /url: /auth/request-password
          - listitem [ref=f49e206]:
            - link "Reset Password" [ref=f49e207] [cursor=pointer]:
              - /url: /auth/reset-password
    - generic [ref=f49e208]:
      - generic [ref=f49e212]:
        - generic [ref=f49e215]:
          - generic [ref=f49e216]: Inline form
          - generic [ref=f49e218]:
            - textbox "Jane Doe" [ref=f49e219]
            - textbox "Email" [ref=f49e220]
            - generic [ref=f49e222]:
              - checkbox "Remember me" [ref=f49e223]
              - generic [ref=f49e225]: Remember me
            - button "Submit" [ref=f49e226] [cursor=pointer]
        - generic [ref=f49e227]:
          - generic [ref=f49e228]:
            - generic [ref=f49e229]:
              - generic [ref=f49e230]: Using the Grid
              - generic [ref=f49e232]:
                - generic [ref=f49e233]:
                  - generic [ref=f49e234]: Email
                  - textbox "Email" [ref=f49e236]
                - generic [ref=f49e237]:
                  - generic [ref=f49e238]: Password
                  - textbox "Password" [ref=f49e240]
                - generic [ref=f49e241]:
                  - generic [ref=f49e242]: Radios
                  - generic [ref=f49e244]:
                    - generic [ref=f49e246]:
                      - radio "Option 1" [ref=f49e247]
                      - generic [ref=f49e250]: Option 1
                    - generic [ref=f49e252]:
                      - radio "Option 2" [checked] [active] [ref=f49e253]
                      - generic [ref=f49e256]: Option 2
                    - generic [ref=f49e258]:
                      - radio "Disabled Option" [disabled] [ref=f49e259]
                      - generic [ref=f49e262]: Disabled Option
                - button "Sign in" [ref=f49e265] [cursor=pointer]
            - generic [ref=f49e266]:
              - generic [ref=f49e267]: Form without labels
              - generic [ref=f49e269]:
                - textbox "Recipients" [ref=f49e271]
                - textbox "Subject" [ref=f49e273]
                - textbox "Message" [ref=f49e275]
                - button "Send" [ref=f49e276] [cursor=pointer]
          - generic [ref=f49e277]:
            - generic [ref=f49e278]:
              - generic [ref=f49e279]: Basic form
              - generic [ref=f49e281]:
                - generic [ref=f49e282]:
                  - generic [ref=f49e283]: Email address
                  - textbox "Email address" [ref=f49e284]:
                    - /placeholder: Email
                - generic [ref=f49e285]:
                  - generic [ref=f49e286]: Password
                  - textbox "Password" [ref=f49e287]
                - generic [ref=f49e290]:
                  - checkbox "Check me out" [ref=f49e291]
                  - generic [ref=f49e293]: Check me out
                - button "Submit" [ref=f49e294] [cursor=pointer]
            - generic [ref=f49e295]:
              - generic [ref=f49e296]: Block form
              - generic [ref=f49e297]:
                - generic [ref=f49e298]:
                  - generic [ref=f49e300]:
                    - generic [ref=f49e301]: First Name
                    - textbox "First Name" [ref=f49e302]
                  - generic [ref=f49e304]:
                    - generic [ref=f49e305]: Last Name
                    - textbox "Last Name" [ref=f49e306]
                - generic [ref=f49e307]:
                  - generic [ref=f49e309]:
                    - generic [ref=f49e310]: Email
                    - textbox "Email" [ref=f49e311]
                  - generic [ref=f49e313]:
                    - generic [ref=f49e314]: Website
                    - textbox "Website" [ref=f49e315]
                - button "Submit" [ref=f49e316] [cursor=pointer]
        - generic [ref=f49e319]:
          - generic [ref=f49e320]: Horizontal form
          - generic [ref=f49e322]:
            - generic [ref=f49e323]:
              - generic [ref=f49e324]: Email
              - textbox "Email" [ref=f49e326]
            - generic [ref=f49e327]:
              - generic [ref=f49e328]: Password
              - textbox "Password" [ref=f49e330]
            - generic [ref=f49e335]:
              - checkbox "Remember me" [ref=f49e336]
              - generic [ref=f49e338]: Remember me
            - button "Sign in" [ref=f49e341] [cursor=pointer]
      - navigation [ref=f49e343]:
        - generic [ref=f49e344]:
          - generic [ref=f49e345]:
            - text: Created with ♥ by
            - link "Akveo" [ref=f49e347] [cursor=pointer]:
              - /url: https://akveo.page.link/8V2f
            - text: "2019"
          - generic [ref=f49e348]:
            - link "" [ref=f49e349] [cursor=pointer]:
              - /url: "#"
            - link "" [ref=f49e350] [cursor=pointer]:
              - /url: "#"
            - link "" [ref=f49e351] [cursor=pointer]:
              - /url: "#"
            - link "" [ref=f49e352] [cursor=pointer]:
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