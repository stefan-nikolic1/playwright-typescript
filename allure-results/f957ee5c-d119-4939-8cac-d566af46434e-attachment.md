# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: tests/uiComponents.spec.ts >> Form Layouts page >> sliders
- Location: tests/uiComponents.spec.ts:186:9

# Error details

```
Test timeout of 10000ms exceeded.
```

```
Error: locator.evaluate: Test timeout of 10000ms exceeded.
Call log:
  - waiting for locator('[tabtitle="Temperature"] ngx-temperature-dragger circle')
  - operation was aborted: Test timeout of 10000ms exceeded.

```

# Page snapshot

```yaml
- generic [ref=f449e7]:
  - navigation [ref=f449e9]:
    - generic [ref=f449e10]:
      - generic [ref=f449e11]:
        - generic [ref=f449e12]:
          - link [ref=f449e13] [cursor=pointer]:
            - /url: "#"
          - link "PW-test" [ref=f449e23] [cursor=pointer]:
            - /url: "#"
        - button "Light" [ref=f449e25] [cursor=pointer]
      - generic [ref=f449e34]:
        - button [active] [ref=f449e37] [cursor=pointer]
        - link [ref=f449e45] [cursor=pointer]:
          - /url: "#"
        - link [ref=f449e53] [cursor=pointer]:
          - /url: "#"
        - generic [ref=f449e60]: Nick Jones
  - generic [ref=f449e66]:
    - list [ref=f449e71]:
      - listitem [ref=f449e72]:
        - link "IoT Dashboard" [ref=f449e73] [cursor=pointer]:
          - /url: /pages/iot-dashboard
      - listitem [ref=f449e80]:
        - generic [ref=f449e81]: FEATURES
      - listitem [ref=f449e82]:
        - link "Forms" [expanded] [ref=f449e83] [cursor=pointer]:
          - /url: "#"
        - list [ref=f449e97]:
          - listitem [ref=f449e98]:
            - link "Form Layouts" [ref=f449e99] [cursor=pointer]:
              - /url: /pages/forms/layouts
          - listitem [ref=f449e100]:
            - link "Datepicker" [ref=f449e101] [cursor=pointer]:
              - /url: /pages/forms/datepicker
      - listitem [ref=f449e102]:
        - link "Modal & Overlays" [ref=f449e103] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f449e118]:
            - link "Dialog" [ref=f449e119] [cursor=pointer]:
              - /url: /pages/modal-overlays/dialog
          - listitem [ref=f449e120]:
            - link "Window" [ref=f449e121] [cursor=pointer]:
              - /url: /pages/modal-overlays/window
          - listitem [ref=f449e122]:
            - link "Popover" [ref=f449e123] [cursor=pointer]:
              - /url: /pages/modal-overlays/popover
          - listitem [ref=f449e124]:
            - link "Toastr" [ref=f449e125] [cursor=pointer]:
              - /url: /pages/modal-overlays/toastr
          - listitem [ref=f449e126]:
            - link "Tooltip" [ref=f449e127] [cursor=pointer]:
              - /url: /pages/modal-overlays/tooltip
      - listitem [ref=f449e128]:
        - link "Extra Components" [ref=f449e129] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f449e145]:
            - link "Calendar" [ref=f449e146] [cursor=pointer]:
              - /url: /pages/extra-components/calendar
      - listitem [ref=f449e147]:
        - link "Charts" [ref=f449e148] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f449e162]:
            - link "Echarts" [ref=f449e163] [cursor=pointer]:
              - /url: /pages/charts/echarts
      - listitem [ref=f449e164]:
        - link "Tables & Data" [ref=f449e165] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f449e181]:
            - link "Smart Table" [ref=f449e182] [cursor=pointer]:
              - /url: /pages/tables/smart-table
          - listitem [ref=f449e183]:
            - link "Tree Grid" [ref=f449e184] [cursor=pointer]:
              - /url: /pages/tables/tree-grid
      - listitem [ref=f449e185]:
        - link "Auth" [ref=f449e186] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f449e200]:
            - link "Login" [ref=f449e201] [cursor=pointer]:
              - /url: /auth/login
          - listitem [ref=f449e202]:
            - link "Register" [ref=f449e203] [cursor=pointer]:
              - /url: /auth/register
          - listitem [ref=f449e204]:
            - link "Request Password" [ref=f449e205] [cursor=pointer]:
              - /url: /auth/request-password
          - listitem [ref=f449e206]:
            - link "Reset Password" [ref=f449e207] [cursor=pointer]:
              - /url: /auth/reset-password
    - generic [ref=f449e208]:
      - generic [ref=f449e212]:
        - generic [ref=f449e215]:
          - generic [ref=f449e216]: Inline form
          - generic [ref=f449e218]:
            - textbox "Jane Doe" [ref=f449e219]
            - textbox "Email" [ref=f449e220]
            - generic [ref=f449e222]:
              - checkbox "Remember me" [ref=f449e223]
              - generic [ref=f449e225]: Remember me
            - button "Submit" [ref=f449e226] [cursor=pointer]
        - generic [ref=f449e227]:
          - generic [ref=f449e228]:
            - generic [ref=f449e229]:
              - generic [ref=f449e230]: Using the Grid
              - generic [ref=f449e232]:
                - generic [ref=f449e233]:
                  - generic [ref=f449e234]: Email
                  - textbox "Email" [ref=f449e236]
                - generic [ref=f449e237]:
                  - generic [ref=f449e238]: Password
                  - textbox "Password" [ref=f449e240]
                - generic [ref=f449e241]:
                  - generic [ref=f449e242]: Radios
                  - generic [ref=f449e244]:
                    - generic [ref=f449e246]:
                      - radio "Option 1" [ref=f449e247]
                      - generic [ref=f449e250]: Option 1
                    - generic [ref=f449e252]:
                      - radio "Option 2" [ref=f449e253]
                      - generic [ref=f449e256]: Option 2
                    - generic [ref=f449e258]:
                      - radio "Disabled Option" [checked] [disabled] [ref=f449e259]
                      - generic [ref=f449e262]: Disabled Option
                - button "Sign in" [ref=f449e265] [cursor=pointer]
            - generic [ref=f449e266]:
              - generic [ref=f449e267]: Form without labels
              - generic [ref=f449e269]:
                - textbox "Recipients" [ref=f449e271]
                - textbox "Subject" [ref=f449e273]
                - textbox "Message" [ref=f449e275]
                - button "Send" [ref=f449e276] [cursor=pointer]
          - generic [ref=f449e277]:
            - generic [ref=f449e278]:
              - generic [ref=f449e279]: Basic form
              - generic [ref=f449e281]:
                - generic [ref=f449e282]:
                  - generic [ref=f449e283]: Email address
                  - textbox "Email address" [ref=f449e284]:
                    - /placeholder: Email
                - generic [ref=f449e285]:
                  - generic [ref=f449e286]: Password
                  - textbox "Password" [ref=f449e287]
                - generic [ref=f449e290]:
                  - checkbox "Check me out" [ref=f449e291]
                  - generic [ref=f449e293]: Check me out
                - button "Submit" [ref=f449e294] [cursor=pointer]
            - generic [ref=f449e295]:
              - generic [ref=f449e296]: Block form
              - generic [ref=f449e297]:
                - generic [ref=f449e298]:
                  - generic [ref=f449e300]:
                    - generic [ref=f449e301]: First Name
                    - textbox "First Name" [ref=f449e302]
                  - generic [ref=f449e304]:
                    - generic [ref=f449e305]: Last Name
                    - textbox "Last Name" [ref=f449e306]
                - generic [ref=f449e307]:
                  - generic [ref=f449e309]:
                    - generic [ref=f449e310]: Email
                    - textbox "Email" [ref=f449e311]
                  - generic [ref=f449e313]:
                    - generic [ref=f449e314]: Website
                    - textbox "Website" [ref=f449e315]
                - button "Submit" [ref=f449e316] [cursor=pointer]
        - generic [ref=f449e319]:
          - generic [ref=f449e320]: Horizontal form
          - generic [ref=f449e322]:
            - generic [ref=f449e323]:
              - generic [ref=f449e324]: Email
              - textbox "Email" [ref=f449e326]
            - generic [ref=f449e327]:
              - generic [ref=f449e328]: Password
              - textbox "Password" [ref=f449e330]
            - generic [ref=f449e335]:
              - checkbox "Remember me" [ref=f449e336]
              - generic [ref=f449e338]: Remember me
            - button "Sign in" [ref=f449e341] [cursor=pointer]
      - navigation [ref=f449e343]:
        - generic [ref=f449e344]:
          - generic [ref=f449e345]:
            - text: Created with ♥ by
            - link "Akveo" [ref=f449e347] [cursor=pointer]:
              - /url: https://akveo.page.link/8V2f
            - text: "2019"
          - generic [ref=f449e348]:
            - link "" [ref=f449e349] [cursor=pointer]:
              - /url: "#"
            - link "" [ref=f449e350] [cursor=pointer]:
              - /url: "#"
            - link "" [ref=f449e351] [cursor=pointer]:
              - /url: "#"
            - link "" [ref=f449e352] [cursor=pointer]:
              - /url: "#"
```

# Test source

```ts
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
  107 |         await page.getByText('Smart Table').click()
  108 | 
  109 |         page.on('dialog', dialog => {
  110 |             expect(dialog.message()).toEqual('Are you sure you want to delete?')
  111 |             dialog.accept()
  112 |         })
  113 | 
  114 |         await page.getByRole('table').locator('tr', { hasText: "mdo@gmail.com" }).locator('.nb-trash').click()
  115 |         await expect(page.locator('table tr').first()).not.toHaveText('mdo@gmail.com')
  116 |     })
  117 | 
  118 |     test('web tables', async ({ page }) => {
  119 |         await page.getByText('Tables & Data').click()
  120 |         await page.getByText('Smart Table').click()
  121 | 
  122 |         //1 get the row by any text in this row
  123 |         const targetRow = page.getByRole('row', { name: "twitter@outlook.com" })
  124 |         await targetRow.locator('.nb-edit').click()
  125 |         await page.locator('input-editor').getByPlaceholder('Age').clear()
  126 |         await page.locator('input-editor').getByPlaceholder('Age').fill('35')
  127 |         await page.locator('.nb-checkmark').click()
  128 | 
  129 |         //2 get the row based on the value in the specific column
  130 |         await page.locator('.ng2-smart-pagination-nav').getByText('2').click()
  131 |         const targetRowById = page.getByRole('row', { name: "11" }).filter({ has: page.locator('td').nth(1).getByText('11') })
  132 |         await targetRowById.locator('.nb-edit').click()
  133 |         await page.locator('input-editor').getByPlaceholder('E-mail').clear()
  134 |         await page.locator('input-editor').getByPlaceholder('E-mail').fill('test@test.com')
  135 |         await page.locator('.nb-checkmark').click()
  136 |         await expect(targetRowById.locator('td').nth(5)).toHaveText('test@test.com')
  137 | 
  138 |         //3 test filter of the table
  139 | 
  140 |         const ages = ["20", "30", "40", "200"]
  141 | 
  142 |         for (let age of ages) {
  143 |             await page.locator('input-filter').getByPlaceholder('Age').clear()
  144 |             await page.locator('input-filter').getByPlaceholder('Age').fill(age)
  145 |             await page.waitForTimeout(500)
  146 |             const ageRows = page.locator('tbody tr')
  147 | 
  148 |             for (let row of await ageRows.all()) {
  149 |                 const cellValue = await row.locator('td').last().textContent()
  150 | 
  151 |                 if (age == "200") {
  152 |                     expect(await page.getByRole('table').textContent()).toContain('No data found')
  153 |                 } else {
  154 |                     expect(cellValue).toEqual(age)
  155 |                 }
  156 |             }
  157 |         }
  158 |     })
  159 | 
  160 |     test('datepicker', async ({ page }) => {
  161 |         await page.getByText('Forms').click()
  162 |         await page.getByText('Datepicker').click()
  163 | 
  164 |         const calendarInputField = page.getByPlaceholder('Form Picker')
  165 |         await calendarInputField.click()
  166 | 
  167 |         let date = new Date()
  168 |         date.setDate(date.getDate() + 7)
  169 |         const expectedDate = date.getDate().toString()
  170 |         const expectedMonthShot = date.toLocaleString('En-US', { month: 'short' })
  171 |         const expectedMonthLong = date.toLocaleString('En-US', { month: 'long' })
  172 |         const expectedYear = date.getFullYear()
  173 |         const dateToAssert = `${expectedMonthShot} ${expectedDate}, ${expectedYear}`
  174 | 
  175 |         let calendarMonthAndYear = await page.locator('nb-calendar-view-mode').textContent() ?? ''
  176 |         const expectedMonthAndYear = ` ${expectedMonthLong} ${expectedYear}`
  177 |         while (!calendarMonthAndYear.includes(expectedMonthAndYear)) {
  178 |             await page.locator('nb-calendar-pageable-navigation [data-name="chevron-right"]').click()
  179 |             calendarMonthAndYear = await page.locator('nb-calendar-view-mode').textContent() ?? ''
  180 |         }
  181 | 
  182 |         await page.locator('[class="day-cell ng-star-inserted"]').getByText(expectedDate, { exact: true }).click()
  183 |         await expect(calendarInputField).toHaveValue(dateToAssert)
  184 |     })
  185 | 
  186 |     test('sliders', async ({ page }) => {
  187 |         // Update attribute
  188 |         const tempGauge = page.locator('[tabtitle="Temperature"] ngx-temperature-dragger circle')
> 189 |         await tempGauge.evaluate(node => {
      |                         ^ Error: locator.evaluate: Test timeout of 10000ms exceeded.
  190 |             node.setAttribute('cx', '232.630')
  191 |             node.setAttribute('cy', '232.630')
  192 |         })
  193 |         await tempGauge.click()
  194 | 
  195 |         //Mouse movement
  196 |         const tempBox = page.locator('[tabtitle="Temperature"] ngx-temperature-dragger')
  197 |         await tempBox.scrollIntoViewIfNeeded()
  198 | 
  199 |         const box = await tempBox.boundingBox()
  200 |         if (box) {
  201 |             const x = box.x + box.width / 2
  202 |             const y = box.y + box.height / 2
  203 |             await page.mouse.move(x, y)
  204 |             await page.mouse.down()
  205 |             await page.mouse.move(x + 100, y)
  206 |             await page.mouse.move(x + 100, y + 100)
  207 |             await page.mouse.up()
  208 |         }
  209 |         await expect(tempBox).toContainText('30')
  210 |     })
  211 | })
```