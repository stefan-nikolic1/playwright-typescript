# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: tests/uiComponents.spec.ts >> Form Layouts page >> input fields
- Location: tests/uiComponents.spec.ts:18:9

# Error details

```
TimeoutError: page.goto: Timeout 5000ms exceeded.
Call log:
  - navigating to "http://localhost:4200/", waiting until "load"

```

# Page snapshot

```yaml
- generic [ref=e7]:
  - navigation [ref=e9]:
    - generic [ref=e10]:
      - generic [ref=e11]:
        - generic [ref=e12]:
          - link [ref=e13] [cursor=pointer]:
            - /url: "#"
          - link "PW-test" [ref=e23] [cursor=pointer]:
            - /url: "#"
        - button "Light" [ref=e25] [cursor=pointer]
      - generic [ref=e34]:
        - button [active] [ref=e37] [cursor=pointer]
        - link [ref=e45] [cursor=pointer]:
          - /url: "#"
        - link [ref=e53] [cursor=pointer]:
          - /url: "#"
        - generic [ref=e60]: Nick Jones
  - generic [ref=e66]:
    - list [ref=e71]:
      - listitem [ref=e72]:
        - link "IoT Dashboard" [ref=e73] [cursor=pointer]:
          - /url: /pages/iot-dashboard
      - listitem [ref=e80]:
        - generic [ref=e81]: FEATURES
      - listitem [ref=e82]:
        - link "Forms" [expanded] [ref=e83] [cursor=pointer]:
          - /url: "#"
        - list [ref=e97]:
          - listitem [ref=e98]:
            - link "Form Layouts" [ref=e99] [cursor=pointer]:
              - /url: /pages/forms/layouts
          - listitem [ref=e100]:
            - link "Datepicker" [ref=e101] [cursor=pointer]:
              - /url: /pages/forms/datepicker
      - listitem [ref=e102]:
        - link "Modal & Overlays" [ref=e103] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=e118]:
            - link "Dialog" [ref=e119] [cursor=pointer]:
              - /url: /pages/modal-overlays/dialog
          - listitem [ref=e120]:
            - link "Window" [ref=e121] [cursor=pointer]:
              - /url: /pages/modal-overlays/window
          - listitem [ref=e122]:
            - link "Popover" [ref=e123] [cursor=pointer]:
              - /url: /pages/modal-overlays/popover
          - listitem [ref=e124]:
            - link "Toastr" [ref=e125] [cursor=pointer]:
              - /url: /pages/modal-overlays/toastr
          - listitem [ref=e126]:
            - link "Tooltip" [ref=e127] [cursor=pointer]:
              - /url: /pages/modal-overlays/tooltip
      - listitem [ref=e128]:
        - link "Extra Components" [ref=e129] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=e145]:
            - link "Calendar" [ref=e146] [cursor=pointer]:
              - /url: /pages/extra-components/calendar
      - listitem [ref=e147]:
        - link "Charts" [ref=e148] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=e162]:
            - link "Echarts" [ref=e163] [cursor=pointer]:
              - /url: /pages/charts/echarts
      - listitem [ref=e164]:
        - link "Tables & Data" [ref=e165] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=e181]:
            - link "Smart Table" [ref=e182] [cursor=pointer]:
              - /url: /pages/tables/smart-table
          - listitem [ref=e183]:
            - link "Tree Grid" [ref=e184] [cursor=pointer]:
              - /url: /pages/tables/tree-grid
      - listitem [ref=e185]:
        - link "Auth" [ref=e186] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=e200]:
            - link "Login" [ref=e201] [cursor=pointer]:
              - /url: /auth/login
          - listitem [ref=e202]:
            - link "Register" [ref=e203] [cursor=pointer]:
              - /url: /auth/register
          - listitem [ref=e204]:
            - link "Request Password" [ref=e205] [cursor=pointer]:
              - /url: /auth/request-password
          - listitem [ref=e206]:
            - link "Reset Password" [ref=e207] [cursor=pointer]:
              - /url: /auth/reset-password
    - generic [ref=e208]:
      - generic [ref=e212]:
        - generic [ref=e215]:
          - generic [ref=e216]: Inline form
          - generic [ref=e218]:
            - textbox "Jane Doe" [ref=e219]
            - textbox "Email" [ref=e220]
            - generic [ref=e222]:
              - checkbox "Remember me" [ref=e223]
              - generic [ref=e225]: Remember me
            - button "Submit" [ref=e226] [cursor=pointer]
        - generic [ref=e227]:
          - generic [ref=e228]:
            - generic [ref=e229]:
              - generic [ref=e230]: Using the Grid
              - generic [ref=e232]:
                - generic [ref=e233]:
                  - generic [ref=e234]: Email
                  - textbox "Email" [ref=e236]
                - generic [ref=e237]:
                  - generic [ref=e238]: Password
                  - textbox "Password" [ref=e240]
                - generic [ref=e241]:
                  - generic [ref=e242]: Radios
                  - generic [ref=e244]:
                    - generic [ref=e246]:
                      - radio "Option 1" [ref=e247]
                      - generic [ref=e250]: Option 1
                    - generic [ref=e252]:
                      - radio "Option 2" [ref=e253]
                      - generic [ref=e256]: Option 2
                    - generic [ref=e258]:
                      - radio "Disabled Option" [checked] [disabled] [ref=e259]
                      - generic [ref=e262]: Disabled Option
                - button "Sign in" [ref=e265] [cursor=pointer]
            - generic [ref=e266]:
              - generic [ref=e267]: Form without labels
              - generic [ref=e269]:
                - textbox "Recipients" [ref=e271]
                - textbox "Subject" [ref=e273]
                - textbox "Message" [ref=e275]
                - button "Send" [ref=e276] [cursor=pointer]
          - generic [ref=e277]:
            - generic [ref=e278]:
              - generic [ref=e279]: Basic form
              - generic [ref=e281]:
                - generic [ref=e282]:
                  - generic [ref=e283]: Email address
                  - textbox "Email address" [ref=e284]:
                    - /placeholder: Email
                - generic [ref=e285]:
                  - generic [ref=e286]: Password
                  - textbox "Password" [ref=e287]
                - generic [ref=e290]:
                  - checkbox "Check me out" [ref=e291]
                  - generic [ref=e293]: Check me out
                - button "Submit" [ref=e294] [cursor=pointer]
            - generic [ref=e295]:
              - generic [ref=e296]: Block form
              - generic [ref=e297]:
                - generic [ref=e298]:
                  - generic [ref=e300]:
                    - generic [ref=e301]: First Name
                    - textbox "First Name" [ref=e302]
                  - generic [ref=e304]:
                    - generic [ref=e305]: Last Name
                    - textbox "Last Name" [ref=e306]
                - generic [ref=e307]:
                  - generic [ref=e309]:
                    - generic [ref=e310]: Email
                    - textbox "Email" [ref=e311]
                  - generic [ref=e313]:
                    - generic [ref=e314]: Website
                    - textbox "Website" [ref=e315]
                - button "Submit" [ref=e316] [cursor=pointer]
        - generic [ref=e319]:
          - generic [ref=e320]: Horizontal form
          - generic [ref=e322]:
            - generic [ref=e323]:
              - generic [ref=e324]: Email
              - textbox "Email" [ref=e326]
            - generic [ref=e327]:
              - generic [ref=e328]: Password
              - textbox "Password" [ref=e330]
            - generic [ref=e335]:
              - checkbox "Remember me" [ref=e336]
              - generic [ref=e338]: Remember me
            - button "Sign in" [ref=e341] [cursor=pointer]
      - navigation [ref=e343]:
        - generic [ref=e344]:
          - generic [ref=e345]:
            - text: Created with ♥ by
            - link "Akveo" [ref=e347] [cursor=pointer]:
              - /url: https://akveo.page.link/8V2f
            - text: "2019"
          - generic [ref=e348]:
            - link "" [ref=e349] [cursor=pointer]:
              - /url: "#"
            - link "" [ref=e350] [cursor=pointer]:
              - /url: "#"
            - link "" [ref=e351] [cursor=pointer]:
              - /url: "#"
            - link "" [ref=e352] [cursor=pointer]:
              - /url: "#"
```

# Test source

```ts
  1   | import { test, expect } from '@playwright/test'
  2   | 
  3   | test.describe.configure({ mode: 'parallel' })
  4   | 
  5   | test.beforeEach(async ({ page }) => {
> 6   |     await page.goto('/')
      |                ^ TimeoutError: page.goto: Timeout 5000ms exceeded.
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
  39  |         await usingTheGridForm.getByRole('radio', { name: "Option 2" }).check({ force: true })
  40  | 
  41  |         await expect(usingTheGridForm.getByRole('radio', { name: "Option 1" })).not.toBeChecked()
  42  |         await expect(usingTheGridForm.getByRole('radio', { name: "Option 2" })).toBeChecked()
  43  | 
  44  |         await usingTheGridForm.getByRole('radio', { name: "Option 1" }).check({ force: true })
  45  |         await expect(usingTheGridForm.getByRole('radio', { name: "Option 1" })).toBeChecked()
  46  |         await expect(usingTheGridForm.getByRole('radio', { name: "Option 2" })).not.toBeChecked()
  47  |     })
  48  | 
  49  |     test('checkboxes', async ({ page }) => {
  50  |         await page.getByText('Modal & Overlays').click()
  51  |         await page.getByText('Toastr').click()
  52  | 
  53  |         await page.getByRole('checkbox', { name: "Hide on click" }).uncheck({ force: true })
  54  |         await page.getByRole('checkbox', { name: "Prevent arising of duplicate toast" }).check({ force: true })
  55  | 
  56  |         const allBoxes = page.getByRole('checkbox')
  57  |         for (const box of await allBoxes.all()) {
  58  |             await box.uncheck({ force: true })
  59  |             expect(await box.isChecked()).toBeFalsy()
  60  |         }
  61  |     })
  62  | 
  63  |     test('lists and dropdowns', async ({ page }) => {
  64  |         const dropDownMenu = page.locator('ngx-header nb-select')
  65  |         await dropDownMenu.click()
  66  | 
  67  |         page.getByRole('list') //when the list has a UL tag
  68  |         page.getByRole('listitem') //when the list has LI tag
  69  | 
  70  |         //const optionList = page.getByRole('list').locator('nb-option')
  71  |         const optionList = page.locator('nb-option-list nb-option')
  72  |         await expect(optionList).toHaveText(["Light", "Dark", "Cosmic", "Corporate"])
  73  |         await optionList.filter({ hasText: "Cosmic" }).click()
  74  |         const header = page.locator('nb-layout-header')
  75  |         await expect(header).toHaveCSS('background-color', 'rgb(50, 50, 89)')
  76  | 
  77  |         const colors = {
  78  |             "Light": "rgb(255, 255, 255)",
  79  |             "Dark": "rgb(34, 43, 69)",
  80  |             "Cosmic": "rgb(50, 50, 89)",
  81  |             "Corporate": "rgb(255, 255, 255)"
  82  |         }
  83  | 
  84  |         await dropDownMenu.click()
  85  |         for (const color in colors) {
  86  |             await optionList.filter({ hasText: color }).click()
  87  |             await expect(header).toHaveCSS('background-color', colors[color as keyof typeof colors])
  88  |             if (color != "Corporate")
  89  |                 await dropDownMenu.click()
  90  |         }
  91  |     })
  92  | 
  93  |     test('tooltips', async ({ page }) => {
  94  |         await page.getByText('Modal & Overlays').click()
  95  |         await page.getByText('Tooltip').click()
  96  | 
  97  |         const toolTipCard = page.locator('nb-card', { hasText: "Tooltip Placements" })
  98  |         await toolTipCard.getByRole('button', { name: "Top" }).hover()
  99  | 
  100 |         page.getByRole('tooltip') //if you have a role tooltip created
  101 |         const tooltip = await page.locator('nb-tooltip').textContent()
  102 |         expect(tooltip).toEqual('This is a tooltip')
  103 |     })
  104 | 
  105 |     test('dialog box', async ({ page }) => {
  106 |         await page.getByText('Tables & Data').click()
```