# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: tests/uiComponents.spec.ts >> Form Layouts page >> sliders
- Location: tests/uiComponents.spec.ts:188:9

# Error details

```
Test timeout of 4000ms exceeded.
```

```
Error: locator.evaluate: Test timeout of 4000ms exceeded.
Call log:
  - waiting for locator('[tabtitle="Temperature"] ngx-temperature-dragger circle')

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
  143 | 
  144 |         for (let age of ages) {
  145 |             await page.locator('input-filter').getByPlaceholder('Age').clear()
  146 |             await page.locator('input-filter').getByPlaceholder('Age').fill(age)
  147 |             await page.waitForTimeout(500)
  148 |             const ageRows = page.locator('tbody tr')
  149 | 
  150 |             for (let row of await ageRows.all()) {
  151 |                 const cellValue = await row.locator('td').last().textContent()
  152 | 
  153 |                 if (age == "200") {
  154 |                     expect(await page.getByRole('table').textContent()).toContain('No data found')
  155 |                 } else {
  156 |                     expect(cellValue).toEqual(age)
  157 |                 }
  158 |             }
  159 |         }
  160 |     })
  161 | 
  162 |     test('datepicker', async ({ page }) => {
  163 |         await page.getByText('Forms').click()
  164 |         await page.getByText('Datepicker').click()
  165 | 
  166 |         const calendarInputField = page.getByPlaceholder('Form Picker')
  167 |         await calendarInputField.click()
  168 | 
  169 |         let date = new Date()
  170 |         date.setDate(date.getDate() + 7)
  171 |         const expectedDate = date.getDate().toString()
  172 |         const expectedMonthShot = date.toLocaleString('En-US', { month: 'short' })
  173 |         const expectedMonthLong = date.toLocaleString('En-US', { month: 'long' })
  174 |         const expectedYear = date.getFullYear()
  175 |         const dateToAssert = `${expectedMonthShot} ${expectedDate}, ${expectedYear}`
  176 | 
  177 |         let calendarMonthAndYear = await page.locator('nb-calendar-view-mode').textContent() ?? ''
  178 |         const expectedMonthAndYear = ` ${expectedMonthLong} ${expectedYear}`
  179 |         while (!calendarMonthAndYear.includes(expectedMonthAndYear)) {
  180 |             await page.locator('nb-calendar-pageable-navigation [data-name="chevron-right"]').click()
  181 |             calendarMonthAndYear = await page.locator('nb-calendar-view-mode').textContent() ?? ''
  182 |         }
  183 | 
  184 |         await page.locator('[class="day-cell ng-star-inserted"]').getByText(expectedDate, { exact: true }).click()
  185 |         await expect(calendarInputField).toHaveValue(dateToAssert)
  186 |     })
  187 | 
  188 |     test('sliders', async ({ page }) => {
  189 |         // Update attribute
  190 |         const tempGauge = page.locator('[tabtitle="Temperature"] ngx-temperature-dragger circle')
> 191 |         await tempGauge.evaluate(node => {
      |                         ^ Error: locator.evaluate: Test timeout of 4000ms exceeded.
  192 |             node.setAttribute('cx', '232.630')
  193 |             node.setAttribute('cy', '232.630')
  194 |         })
  195 |         await tempGauge.click()
  196 | 
  197 |         //Mouse movement
  198 |         const tempBox = page.locator('[tabtitle="Temperature"] ngx-temperature-dragger')
  199 |         await tempBox.scrollIntoViewIfNeeded()
  200 | 
  201 |         const box = await tempBox.boundingBox()
  202 |         if (box) {
  203 |             const x = box.x + box.width / 2
  204 |             const y = box.y + box.height / 2
  205 |             await page.mouse.move(x, y)
  206 |             await page.mouse.down()
  207 |             await page.mouse.move(x + 100, y)
  208 |             await page.mouse.move(x + 100, y + 100)
  209 |             await page.mouse.up()
  210 |         }
  211 |         await expect(tempBox).toContainText('30')
  212 |     })
  213 | })
```