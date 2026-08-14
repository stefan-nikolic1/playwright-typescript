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
    - locator resolved to <nb-card _nghost-mst-c98="" _ngcontent-mst-c290="">…</nb-card>
  - taking element screenshot
    - disabled all CSS animations
  - waiting for fonts to load...
  - fonts loaded
  - attempting scroll into view action
    - waiting for element to be stable
  - Expected an image 461px by 383px, received 459px by 383px. 487 pixels (ratio 0.01 of all image pixels) are different.
  - waiting 100ms before taking screenshot
  - waiting for locator('nb-card').filter({ hasText: 'Using the Grid' })
    - locator resolved to <nb-card _nghost-mst-c98="" _ngcontent-mst-c290="">…</nb-card>
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
- generic [ref=f118e7]:
  - navigation [ref=f118e9]:
    - generic [ref=f118e10]:
      - generic [ref=f118e11]:
        - generic [ref=f118e12]:
          - link [ref=f118e13] [cursor=pointer]:
            - /url: "#"
          - link "PW-test" [ref=f118e23] [cursor=pointer]:
            - /url: "#"
        - button "Light" [ref=f118e25] [cursor=pointer]
      - generic [ref=f118e34]:
        - button [ref=f118e37] [cursor=pointer]
        - link [ref=f118e45] [cursor=pointer]:
          - /url: "#"
        - link [ref=f118e53] [cursor=pointer]:
          - /url: "#"
        - generic [ref=f118e60]: Nick Jones
  - generic [ref=f118e66]:
    - list [ref=f118e71]:
      - listitem [ref=f118e72]:
        - link "IoT Dashboard" [ref=f118e73] [cursor=pointer]:
          - /url: /pages/iot-dashboard
      - listitem [ref=f118e80]:
        - generic [ref=f118e81]: FEATURES
      - listitem [ref=f118e82]:
        - link "Forms" [expanded] [ref=f118e83] [cursor=pointer]:
          - /url: "#"
        - list [ref=f118e97]:
          - listitem [ref=f118e98]:
            - link "Form Layouts" [ref=f118e99] [cursor=pointer]:
              - /url: /pages/forms/layouts
          - listitem [ref=f118e100]:
            - link "Datepicker" [ref=f118e101] [cursor=pointer]:
              - /url: /pages/forms/datepicker
      - listitem [ref=f118e102]:
        - link "Modal & Overlays" [ref=f118e103] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f118e118]:
            - link "Dialog" [ref=f118e119] [cursor=pointer]:
              - /url: /pages/modal-overlays/dialog
          - listitem [ref=f118e120]:
            - link "Window" [ref=f118e121] [cursor=pointer]:
              - /url: /pages/modal-overlays/window
          - listitem [ref=f118e122]:
            - link "Popover" [ref=f118e123] [cursor=pointer]:
              - /url: /pages/modal-overlays/popover
          - listitem [ref=f118e124]:
            - link "Toastr" [ref=f118e125] [cursor=pointer]:
              - /url: /pages/modal-overlays/toastr
          - listitem [ref=f118e126]:
            - link "Tooltip" [ref=f118e127] [cursor=pointer]:
              - /url: /pages/modal-overlays/tooltip
      - listitem [ref=f118e128]:
        - link "Extra Components" [ref=f118e129] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f118e145]:
            - link "Calendar" [ref=f118e146] [cursor=pointer]:
              - /url: /pages/extra-components/calendar
      - listitem [ref=f118e147]:
        - link "Charts" [ref=f118e148] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f118e162]:
            - link "Echarts" [ref=f118e163] [cursor=pointer]:
              - /url: /pages/charts/echarts
      - listitem [ref=f118e164]:
        - link "Tables & Data" [ref=f118e165] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f118e181]:
            - link "Smart Table" [ref=f118e182] [cursor=pointer]:
              - /url: /pages/tables/smart-table
          - listitem [ref=f118e183]:
            - link "Tree Grid" [ref=f118e184] [cursor=pointer]:
              - /url: /pages/tables/tree-grid
      - listitem [ref=f118e185]:
        - link "Auth" [ref=f118e186] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f118e200]:
            - link "Login" [ref=f118e201] [cursor=pointer]:
              - /url: /auth/login
          - listitem [ref=f118e202]:
            - link "Register" [ref=f118e203] [cursor=pointer]:
              - /url: /auth/register
          - listitem [ref=f118e204]:
            - link "Request Password" [ref=f118e205] [cursor=pointer]:
              - /url: /auth/request-password
          - listitem [ref=f118e206]:
            - link "Reset Password" [ref=f118e207] [cursor=pointer]:
              - /url: /auth/reset-password
    - generic [ref=f118e208]:
      - generic [ref=f118e212]:
        - generic [ref=f118e215]:
          - generic [ref=f118e216]: Inline form
          - generic [ref=f118e218]:
            - textbox "Jane Doe" [ref=f118e219]
            - textbox "Email" [ref=f118e220]
            - generic [ref=f118e222]:
              - checkbox "Remember me" [ref=f118e223]
              - generic [ref=f118e225]: Remember me
            - button "Submit" [ref=f118e226] [cursor=pointer]
        - generic [ref=f118e227]:
          - generic [ref=f118e228]:
            - generic [ref=f118e229]:
              - generic [ref=f118e230]: Using the Grid
              - generic [ref=f118e232]:
                - generic [ref=f118e233]:
                  - generic [ref=f118e234]: Email
                  - textbox "Email" [ref=f118e236]
                - generic [ref=f118e237]:
                  - generic [ref=f118e238]: Password
                  - textbox "Password" [ref=f118e240]
                - generic [ref=f118e241]:
                  - generic [ref=f118e242]: Radios
                  - generic [ref=f118e244]:
                    - generic [ref=f118e246]:
                      - radio "Option 1" [ref=f118e247]
                      - generic [ref=f118e250]: Option 1
                    - generic [ref=f118e252]:
                      - radio "Option 2" [checked] [active] [ref=f118e253]
                      - generic [ref=f118e256]: Option 2
                    - generic [ref=f118e258]:
                      - radio "Disabled Option" [disabled] [ref=f118e259]
                      - generic [ref=f118e262]: Disabled Option
                - button "Sign in" [ref=f118e265] [cursor=pointer]
            - generic [ref=f118e266]:
              - generic [ref=f118e267]: Form without labels
              - generic [ref=f118e269]:
                - textbox "Recipients" [ref=f118e271]
                - textbox "Subject" [ref=f118e273]
                - textbox "Message" [ref=f118e275]
                - button "Send" [ref=f118e276] [cursor=pointer]
          - generic [ref=f118e277]:
            - generic [ref=f118e278]:
              - generic [ref=f118e279]: Basic form
              - generic [ref=f118e281]:
                - generic [ref=f118e282]:
                  - generic [ref=f118e283]: Email address
                  - textbox "Email address" [ref=f118e284]:
                    - /placeholder: Email
                - generic [ref=f118e285]:
                  - generic [ref=f118e286]: Password
                  - textbox "Password" [ref=f118e287]
                - generic [ref=f118e290]:
                  - checkbox "Check me out" [ref=f118e291]
                  - generic [ref=f118e293]: Check me out
                - button "Submit" [ref=f118e294] [cursor=pointer]
            - generic [ref=f118e295]:
              - generic [ref=f118e296]: Block form
              - generic [ref=f118e297]:
                - generic [ref=f118e298]:
                  - generic [ref=f118e300]:
                    - generic [ref=f118e301]: First Name
                    - textbox "First Name" [ref=f118e302]
                  - generic [ref=f118e304]:
                    - generic [ref=f118e305]: Last Name
                    - textbox "Last Name" [ref=f118e306]
                - generic [ref=f118e307]:
                  - generic [ref=f118e309]:
                    - generic [ref=f118e310]: Email
                    - textbox "Email" [ref=f118e311]
                  - generic [ref=f118e313]:
                    - generic [ref=f118e314]: Website
                    - textbox "Website" [ref=f118e315]
                - button "Submit" [ref=f118e316] [cursor=pointer]
        - generic [ref=f118e319]:
          - generic [ref=f118e320]: Horizontal form
          - generic [ref=f118e322]:
            - generic [ref=f118e323]:
              - generic [ref=f118e324]: Email
              - textbox "Email" [ref=f118e326]
            - generic [ref=f118e327]:
              - generic [ref=f118e328]: Password
              - textbox "Password" [ref=f118e330]
            - generic [ref=f118e335]:
              - checkbox "Remember me" [ref=f118e336]
              - generic [ref=f118e338]: Remember me
            - button "Sign in" [ref=f118e341] [cursor=pointer]
      - navigation [ref=f118e343]:
        - generic [ref=f118e344]:
          - generic [ref=f118e345]:
            - text: Created with ♥ by
            - link "Akveo" [ref=f118e347] [cursor=pointer]:
              - /url: https://akveo.page.link/8V2f
            - text: "2019"
          - generic [ref=f118e348]:
            - link "" [ref=f118e349] [cursor=pointer]:
              - /url: "#"
            - link "" [ref=f118e350] [cursor=pointer]:
              - /url: "#"
            - link "" [ref=f118e351] [cursor=pointer]:
              - /url: "#"
            - link "" [ref=f118e352] [cursor=pointer]:
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