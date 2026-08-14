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
Error: locator.click: Test timeout of 10000ms exceeded.
Call log:
  - waiting for locator('[tabtitle="Temperature"] ngx-temperature-dragger circle')
    - locator resolved to <circle r="16" cx="232.630" cy="232.630" fill="#f7f9fc" stroke-width="3" stroke="#3366ff" _ngcontent-sug-c275=""></circle>
  - attempting click action
    - waiting for element to be visible, enabled and stable
    - element is not stable
  - retrying click action
    - waiting for element to be visible, enabled and stable
  - element was detached from the DOM, retrying
  - operation was aborted: Test timeout of 10000ms exceeded.

```

# Page snapshot

```yaml
- generic [ref=f320e7]:
  - navigation [ref=f320e9]:
    - generic [ref=f320e10]:
      - generic [ref=f320e11]:
        - generic [ref=f320e12]:
          - link [ref=f320e13] [cursor=pointer]:
            - /url: "#"
          - link "PW-test" [ref=f320e23] [cursor=pointer]:
            - /url: "#"
        - button "Light" [ref=f320e25] [cursor=pointer]
      - generic [ref=f320e34]:
        - button [active] [ref=f320e37] [cursor=pointer]
        - link [ref=f320e45] [cursor=pointer]:
          - /url: "#"
        - link [ref=f320e53] [cursor=pointer]:
          - /url: "#"
        - generic [ref=f320e60]: Nick Jones
  - generic [ref=f320e66]:
    - list [ref=f320e71]:
      - listitem [ref=f320e72]:
        - link "IoT Dashboard" [ref=f320e73] [cursor=pointer]:
          - /url: /pages/iot-dashboard
      - listitem [ref=f320e80]:
        - generic [ref=f320e81]: FEATURES
      - listitem [ref=f320e82]:
        - link "Forms" [expanded] [ref=f320e83] [cursor=pointer]:
          - /url: "#"
        - list [ref=f320e97]:
          - listitem [ref=f320e98]:
            - link "Form Layouts" [ref=f320e99] [cursor=pointer]:
              - /url: /pages/forms/layouts
          - listitem [ref=f320e100]:
            - link "Datepicker" [ref=f320e101] [cursor=pointer]:
              - /url: /pages/forms/datepicker
      - listitem [ref=f320e102]:
        - link "Modal & Overlays" [ref=f320e103] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f320e118]:
            - link "Dialog" [ref=f320e119] [cursor=pointer]:
              - /url: /pages/modal-overlays/dialog
          - listitem [ref=f320e120]:
            - link "Window" [ref=f320e121] [cursor=pointer]:
              - /url: /pages/modal-overlays/window
          - listitem [ref=f320e122]:
            - link "Popover" [ref=f320e123] [cursor=pointer]:
              - /url: /pages/modal-overlays/popover
          - listitem [ref=f320e124]:
            - link "Toastr" [ref=f320e125] [cursor=pointer]:
              - /url: /pages/modal-overlays/toastr
          - listitem [ref=f320e126]:
            - link "Tooltip" [ref=f320e127] [cursor=pointer]:
              - /url: /pages/modal-overlays/tooltip
      - listitem [ref=f320e128]:
        - link "Extra Components" [ref=f320e129] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f320e145]:
            - link "Calendar" [ref=f320e146] [cursor=pointer]:
              - /url: /pages/extra-components/calendar
      - listitem [ref=f320e147]:
        - link "Charts" [ref=f320e148] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f320e162]:
            - link "Echarts" [ref=f320e163] [cursor=pointer]:
              - /url: /pages/charts/echarts
      - listitem [ref=f320e164]:
        - link "Tables & Data" [ref=f320e165] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f320e181]:
            - link "Smart Table" [ref=f320e182] [cursor=pointer]:
              - /url: /pages/tables/smart-table
          - listitem [ref=f320e183]:
            - link "Tree Grid" [ref=f320e184] [cursor=pointer]:
              - /url: /pages/tables/tree-grid
      - listitem [ref=f320e185]:
        - link "Auth" [ref=f320e186] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f320e200]:
            - link "Login" [ref=f320e201] [cursor=pointer]:
              - /url: /auth/login
          - listitem [ref=f320e202]:
            - link "Register" [ref=f320e203] [cursor=pointer]:
              - /url: /auth/register
          - listitem [ref=f320e204]:
            - link "Request Password" [ref=f320e205] [cursor=pointer]:
              - /url: /auth/request-password
          - listitem [ref=f320e206]:
            - link "Reset Password" [ref=f320e207] [cursor=pointer]:
              - /url: /auth/reset-password
    - generic [ref=f320e208]:
      - generic [ref=f320e212]:
        - generic [ref=f320e215]:
          - generic [ref=f320e216]: Inline form
          - generic [ref=f320e218]:
            - textbox "Jane Doe" [ref=f320e219]
            - textbox "Email" [ref=f320e220]
            - generic [ref=f320e222]:
              - checkbox "Remember me" [ref=f320e223]
              - generic [ref=f320e225]: Remember me
            - button "Submit" [ref=f320e226] [cursor=pointer]
        - generic [ref=f320e227]:
          - generic [ref=f320e228]:
            - generic [ref=f320e229]:
              - generic [ref=f320e230]: Using the Grid
              - generic [ref=f320e232]:
                - generic [ref=f320e233]:
                  - generic [ref=f320e234]: Email
                  - textbox "Email" [ref=f320e236]
                - generic [ref=f320e237]:
                  - generic [ref=f320e238]: Password
                  - textbox "Password" [ref=f320e240]
                - generic [ref=f320e241]:
                  - generic [ref=f320e242]: Radios
                  - generic [ref=f320e244]:
                    - generic [ref=f320e246]:
                      - radio "Option 1" [ref=f320e247]
                      - generic [ref=f320e250]: Option 1
                    - generic [ref=f320e252]:
                      - radio "Option 2" [ref=f320e253]
                      - generic [ref=f320e256]: Option 2
                    - generic [ref=f320e258]:
                      - radio "Disabled Option" [checked] [disabled] [ref=f320e259]
                      - generic [ref=f320e262]: Disabled Option
                - button "Sign in" [ref=f320e265] [cursor=pointer]
            - generic [ref=f320e266]:
              - generic [ref=f320e267]: Form without labels
              - generic [ref=f320e269]:
                - textbox "Recipients" [ref=f320e271]
                - textbox "Subject" [ref=f320e273]
                - textbox "Message" [ref=f320e275]
                - button "Send" [ref=f320e276] [cursor=pointer]
          - generic [ref=f320e277]:
            - generic [ref=f320e278]:
              - generic [ref=f320e279]: Basic form
              - generic [ref=f320e281]:
                - generic [ref=f320e282]:
                  - generic [ref=f320e283]: Email address
                  - textbox "Email address" [ref=f320e284]:
                    - /placeholder: Email
                - generic [ref=f320e285]:
                  - generic [ref=f320e286]: Password
                  - textbox "Password" [ref=f320e287]
                - generic [ref=f320e290]:
                  - checkbox "Check me out" [ref=f320e291]
                  - generic [ref=f320e293]: Check me out
                - button "Submit" [ref=f320e294] [cursor=pointer]
            - generic [ref=f320e295]:
              - generic [ref=f320e296]: Block form
              - generic [ref=f320e297]:
                - generic [ref=f320e298]:
                  - generic [ref=f320e300]:
                    - generic [ref=f320e301]: First Name
                    - textbox "First Name" [ref=f320e302]
                  - generic [ref=f320e304]:
                    - generic [ref=f320e305]: Last Name
                    - textbox "Last Name" [ref=f320e306]
                - generic [ref=f320e307]:
                  - generic [ref=f320e309]:
                    - generic [ref=f320e310]: Email
                    - textbox "Email" [ref=f320e311]
                  - generic [ref=f320e313]:
                    - generic [ref=f320e314]: Website
                    - textbox "Website" [ref=f320e315]
                - button "Submit" [ref=f320e316] [cursor=pointer]
        - generic [ref=f320e319]:
          - generic [ref=f320e320]: Horizontal form
          - generic [ref=f320e322]:
            - generic [ref=f320e323]:
              - generic [ref=f320e324]: Email
              - textbox "Email" [ref=f320e326]
            - generic [ref=f320e327]:
              - generic [ref=f320e328]: Password
              - textbox "Password" [ref=f320e330]
            - generic [ref=f320e335]:
              - checkbox "Remember me" [ref=f320e336]
              - generic [ref=f320e338]: Remember me
            - button "Sign in" [ref=f320e341] [cursor=pointer]
      - navigation [ref=f320e343]:
        - generic [ref=f320e344]:
          - generic [ref=f320e345]:
            - text: Created with ♥ by
            - link "Akveo" [ref=f320e347] [cursor=pointer]:
              - /url: https://akveo.page.link/8V2f
            - text: "2019"
          - generic [ref=f320e348]:
            - link "" [ref=f320e349] [cursor=pointer]:
              - /url: "#"
            - link "" [ref=f320e350] [cursor=pointer]:
              - /url: "#"
            - link "" [ref=f320e351] [cursor=pointer]:
              - /url: "#"
            - link "" [ref=f320e352] [cursor=pointer]:
              - /url: "#"
```

# Test source

```ts
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
  189 |         await tempGauge.evaluate(node => {
  190 |             node.setAttribute('cx', '232.630')
  191 |             node.setAttribute('cy', '232.630')
  192 |         })
> 193 |         await tempGauge.click()
      |                         ^ Error: locator.click: Test timeout of 10000ms exceeded.
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