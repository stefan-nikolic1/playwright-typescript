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
- generic [ref=f467e7]:
  - navigation [ref=f467e9]:
    - generic [ref=f467e10]:
      - generic [ref=f467e11]:
        - generic [ref=f467e12]:
          - link [ref=f467e13] [cursor=pointer]:
            - /url: "#"
          - link "PW-test" [ref=f467e23] [cursor=pointer]:
            - /url: "#"
        - button "Light" [ref=f467e25] [cursor=pointer]
      - generic [ref=f467e34]:
        - button [active] [ref=f467e37] [cursor=pointer]
        - link [ref=f467e45] [cursor=pointer]:
          - /url: "#"
        - link [ref=f467e53] [cursor=pointer]:
          - /url: "#"
        - generic [ref=f467e60]: Nick Jones
  - generic [ref=f467e66]:
    - list [ref=f467e71]:
      - listitem [ref=f467e72]:
        - link "IoT Dashboard" [ref=f467e73] [cursor=pointer]:
          - /url: /pages/iot-dashboard
      - listitem [ref=f467e80]:
        - generic [ref=f467e81]: FEATURES
      - listitem [ref=f467e82]:
        - link "Forms" [expanded] [ref=f467e83] [cursor=pointer]:
          - /url: "#"
        - list [ref=f467e97]:
          - listitem [ref=f467e98]:
            - link "Form Layouts" [ref=f467e99] [cursor=pointer]:
              - /url: /pages/forms/layouts
          - listitem [ref=f467e100]:
            - link "Datepicker" [ref=f467e101] [cursor=pointer]:
              - /url: /pages/forms/datepicker
      - listitem [ref=f467e102]:
        - link "Modal & Overlays" [ref=f467e103] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f467e118]:
            - link "Dialog" [ref=f467e119] [cursor=pointer]:
              - /url: /pages/modal-overlays/dialog
          - listitem [ref=f467e120]:
            - link "Window" [ref=f467e121] [cursor=pointer]:
              - /url: /pages/modal-overlays/window
          - listitem [ref=f467e122]:
            - link "Popover" [ref=f467e123] [cursor=pointer]:
              - /url: /pages/modal-overlays/popover
          - listitem [ref=f467e124]:
            - link "Toastr" [ref=f467e125] [cursor=pointer]:
              - /url: /pages/modal-overlays/toastr
          - listitem [ref=f467e126]:
            - link "Tooltip" [ref=f467e127] [cursor=pointer]:
              - /url: /pages/modal-overlays/tooltip
      - listitem [ref=f467e128]:
        - link "Extra Components" [ref=f467e129] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f467e145]:
            - link "Calendar" [ref=f467e146] [cursor=pointer]:
              - /url: /pages/extra-components/calendar
      - listitem [ref=f467e147]:
        - link "Charts" [ref=f467e148] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f467e162]:
            - link "Echarts" [ref=f467e163] [cursor=pointer]:
              - /url: /pages/charts/echarts
      - listitem [ref=f467e164]:
        - link "Tables & Data" [ref=f467e165] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f467e181]:
            - link "Smart Table" [ref=f467e182] [cursor=pointer]:
              - /url: /pages/tables/smart-table
          - listitem [ref=f467e183]:
            - link "Tree Grid" [ref=f467e184] [cursor=pointer]:
              - /url: /pages/tables/tree-grid
      - listitem [ref=f467e185]:
        - link "Auth" [ref=f467e186] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f467e200]:
            - link "Login" [ref=f467e201] [cursor=pointer]:
              - /url: /auth/login
          - listitem [ref=f467e202]:
            - link "Register" [ref=f467e203] [cursor=pointer]:
              - /url: /auth/register
          - listitem [ref=f467e204]:
            - link "Request Password" [ref=f467e205] [cursor=pointer]:
              - /url: /auth/request-password
          - listitem [ref=f467e206]:
            - link "Reset Password" [ref=f467e207] [cursor=pointer]:
              - /url: /auth/reset-password
    - generic [ref=f467e208]:
      - generic [ref=f467e212]:
        - generic [ref=f467e215]:
          - generic [ref=f467e216]: Inline form
          - generic [ref=f467e218]:
            - textbox "Jane Doe" [ref=f467e219]
            - textbox "Email" [ref=f467e220]
            - generic [ref=f467e222]:
              - checkbox "Remember me" [ref=f467e223]
              - generic [ref=f467e225]: Remember me
            - button "Submit" [ref=f467e226] [cursor=pointer]
        - generic [ref=f467e227]:
          - generic [ref=f467e228]:
            - generic [ref=f467e229]:
              - generic [ref=f467e230]: Using the Grid
              - generic [ref=f467e232]:
                - generic [ref=f467e233]:
                  - generic [ref=f467e234]: Email
                  - textbox "Email" [ref=f467e236]
                - generic [ref=f467e237]:
                  - generic [ref=f467e238]: Password
                  - textbox "Password" [ref=f467e240]
                - generic [ref=f467e241]:
                  - generic [ref=f467e242]: Radios
                  - generic [ref=f467e244]:
                    - generic [ref=f467e246]:
                      - radio "Option 1" [ref=f467e247]
                      - generic [ref=f467e250]: Option 1
                    - generic [ref=f467e252]:
                      - radio "Option 2" [ref=f467e253]
                      - generic [ref=f467e256]: Option 2
                    - generic [ref=f467e258]:
                      - radio "Disabled Option" [checked] [disabled] [ref=f467e259]
                      - generic [ref=f467e262]: Disabled Option
                - button "Sign in" [ref=f467e265] [cursor=pointer]
            - generic [ref=f467e266]:
              - generic [ref=f467e267]: Form without labels
              - generic [ref=f467e269]:
                - textbox "Recipients" [ref=f467e271]
                - textbox "Subject" [ref=f467e273]
                - textbox "Message" [ref=f467e275]
                - button "Send" [ref=f467e276] [cursor=pointer]
          - generic [ref=f467e277]:
            - generic [ref=f467e278]:
              - generic [ref=f467e279]: Basic form
              - generic [ref=f467e281]:
                - generic [ref=f467e282]:
                  - generic [ref=f467e283]: Email address
                  - textbox "Email address" [ref=f467e284]:
                    - /placeholder: Email
                - generic [ref=f467e285]:
                  - generic [ref=f467e286]: Password
                  - textbox "Password" [ref=f467e287]
                - generic [ref=f467e290]:
                  - checkbox "Check me out" [ref=f467e291]
                  - generic [ref=f467e293]: Check me out
                - button "Submit" [ref=f467e294] [cursor=pointer]
            - generic [ref=f467e295]:
              - generic [ref=f467e296]: Block form
              - generic [ref=f467e297]:
                - generic [ref=f467e298]:
                  - generic [ref=f467e300]:
                    - generic [ref=f467e301]: First Name
                    - textbox "First Name" [ref=f467e302]
                  - generic [ref=f467e304]:
                    - generic [ref=f467e305]: Last Name
                    - textbox "Last Name" [ref=f467e306]
                - generic [ref=f467e307]:
                  - generic [ref=f467e309]:
                    - generic [ref=f467e310]: Email
                    - textbox "Email" [ref=f467e311]
                  - generic [ref=f467e313]:
                    - generic [ref=f467e314]: Website
                    - textbox "Website" [ref=f467e315]
                - button "Submit" [ref=f467e316] [cursor=pointer]
        - generic [ref=f467e319]:
          - generic [ref=f467e320]: Horizontal form
          - generic [ref=f467e322]:
            - generic [ref=f467e323]:
              - generic [ref=f467e324]: Email
              - textbox "Email" [ref=f467e326]
            - generic [ref=f467e327]:
              - generic [ref=f467e328]: Password
              - textbox "Password" [ref=f467e330]
            - generic [ref=f467e335]:
              - checkbox "Remember me" [ref=f467e336]
              - generic [ref=f467e338]: Remember me
            - button "Sign in" [ref=f467e341] [cursor=pointer]
      - navigation [ref=f467e343]:
        - generic [ref=f467e344]:
          - generic [ref=f467e345]:
            - text: Created with ♥ by
            - link "Akveo" [ref=f467e347] [cursor=pointer]:
              - /url: https://akveo.page.link/8V2f
            - text: "2019"
          - generic [ref=f467e348]:
            - link "" [ref=f467e349] [cursor=pointer]:
              - /url: "#"
            - link "" [ref=f467e350] [cursor=pointer]:
              - /url: "#"
            - link "" [ref=f467e351] [cursor=pointer]:
              - /url: "#"
            - link "" [ref=f467e352] [cursor=pointer]:
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