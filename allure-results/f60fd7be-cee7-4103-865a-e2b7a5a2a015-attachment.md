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
    - locator resolved to <circle r="16" cx="232.630" cy="232.630" fill="#f7f9fc" stroke-width="3" stroke="#3366ff" _ngcontent-hlt-c275=""></circle>
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
- generic [ref=f356e7]:
  - navigation [ref=f356e9]:
    - generic [ref=f356e10]:
      - generic [ref=f356e11]:
        - generic [ref=f356e12]:
          - link [ref=f356e13] [cursor=pointer]:
            - /url: "#"
          - link "PW-test" [ref=f356e23] [cursor=pointer]:
            - /url: "#"
        - button "Light" [ref=f356e25] [cursor=pointer]
      - generic [ref=f356e34]:
        - button [active] [ref=f356e37] [cursor=pointer]
        - link [ref=f356e45] [cursor=pointer]:
          - /url: "#"
        - link [ref=f356e53] [cursor=pointer]:
          - /url: "#"
        - generic [ref=f356e60]: Nick Jones
  - generic [ref=f356e66]:
    - list [ref=f356e71]:
      - listitem [ref=f356e72]:
        - link "IoT Dashboard" [ref=f356e73] [cursor=pointer]:
          - /url: /pages/iot-dashboard
      - listitem [ref=f356e80]:
        - generic [ref=f356e81]: FEATURES
      - listitem [ref=f356e82]:
        - link "Forms" [expanded] [ref=f356e83] [cursor=pointer]:
          - /url: "#"
        - list [ref=f356e97]:
          - listitem [ref=f356e98]:
            - link "Form Layouts" [ref=f356e99] [cursor=pointer]:
              - /url: /pages/forms/layouts
          - listitem [ref=f356e100]:
            - link "Datepicker" [ref=f356e101] [cursor=pointer]:
              - /url: /pages/forms/datepicker
      - listitem [ref=f356e102]:
        - link "Modal & Overlays" [ref=f356e103] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f356e118]:
            - link "Dialog" [ref=f356e119] [cursor=pointer]:
              - /url: /pages/modal-overlays/dialog
          - listitem [ref=f356e120]:
            - link "Window" [ref=f356e121] [cursor=pointer]:
              - /url: /pages/modal-overlays/window
          - listitem [ref=f356e122]:
            - link "Popover" [ref=f356e123] [cursor=pointer]:
              - /url: /pages/modal-overlays/popover
          - listitem [ref=f356e124]:
            - link "Toastr" [ref=f356e125] [cursor=pointer]:
              - /url: /pages/modal-overlays/toastr
          - listitem [ref=f356e126]:
            - link "Tooltip" [ref=f356e127] [cursor=pointer]:
              - /url: /pages/modal-overlays/tooltip
      - listitem [ref=f356e128]:
        - link "Extra Components" [ref=f356e129] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f356e145]:
            - link "Calendar" [ref=f356e146] [cursor=pointer]:
              - /url: /pages/extra-components/calendar
      - listitem [ref=f356e147]:
        - link "Charts" [ref=f356e148] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f356e162]:
            - link "Echarts" [ref=f356e163] [cursor=pointer]:
              - /url: /pages/charts/echarts
      - listitem [ref=f356e164]:
        - link "Tables & Data" [ref=f356e165] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f356e181]:
            - link "Smart Table" [ref=f356e182] [cursor=pointer]:
              - /url: /pages/tables/smart-table
          - listitem [ref=f356e183]:
            - link "Tree Grid" [ref=f356e184] [cursor=pointer]:
              - /url: /pages/tables/tree-grid
      - listitem [ref=f356e185]:
        - link "Auth" [ref=f356e186] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f356e200]:
            - link "Login" [ref=f356e201] [cursor=pointer]:
              - /url: /auth/login
          - listitem [ref=f356e202]:
            - link "Register" [ref=f356e203] [cursor=pointer]:
              - /url: /auth/register
          - listitem [ref=f356e204]:
            - link "Request Password" [ref=f356e205] [cursor=pointer]:
              - /url: /auth/request-password
          - listitem [ref=f356e206]:
            - link "Reset Password" [ref=f356e207] [cursor=pointer]:
              - /url: /auth/reset-password
    - generic [ref=f356e208]:
      - generic [ref=f356e212]:
        - generic [ref=f356e215]:
          - generic [ref=f356e216]: Inline form
          - generic [ref=f356e218]:
            - textbox "Jane Doe" [ref=f356e219]
            - textbox "Email" [ref=f356e220]
            - generic [ref=f356e222]:
              - checkbox "Remember me" [ref=f356e223]
              - generic [ref=f356e225]: Remember me
            - button "Submit" [ref=f356e226] [cursor=pointer]
        - generic [ref=f356e227]:
          - generic [ref=f356e228]:
            - generic [ref=f356e229]:
              - generic [ref=f356e230]: Using the Grid
              - generic [ref=f356e232]:
                - generic [ref=f356e233]:
                  - generic [ref=f356e234]: Email
                  - textbox "Email" [ref=f356e236]
                - generic [ref=f356e237]:
                  - generic [ref=f356e238]: Password
                  - textbox "Password" [ref=f356e240]
                - generic [ref=f356e241]:
                  - generic [ref=f356e242]: Radios
                  - generic [ref=f356e244]:
                    - generic [ref=f356e246]:
                      - radio "Option 1" [ref=f356e247]
                      - generic [ref=f356e250]: Option 1
                    - generic [ref=f356e252]:
                      - radio "Option 2" [ref=f356e253]
                      - generic [ref=f356e256]: Option 2
                    - generic [ref=f356e258]:
                      - radio "Disabled Option" [checked] [disabled] [ref=f356e259]
                      - generic [ref=f356e262]: Disabled Option
                - button "Sign in" [ref=f356e265] [cursor=pointer]
            - generic [ref=f356e266]:
              - generic [ref=f356e267]: Form without labels
              - generic [ref=f356e269]:
                - textbox "Recipients" [ref=f356e271]
                - textbox "Subject" [ref=f356e273]
                - textbox "Message" [ref=f356e275]
                - button "Send" [ref=f356e276] [cursor=pointer]
          - generic [ref=f356e277]:
            - generic [ref=f356e278]:
              - generic [ref=f356e279]: Basic form
              - generic [ref=f356e281]:
                - generic [ref=f356e282]:
                  - generic [ref=f356e283]: Email address
                  - textbox "Email address" [ref=f356e284]:
                    - /placeholder: Email
                - generic [ref=f356e285]:
                  - generic [ref=f356e286]: Password
                  - textbox "Password" [ref=f356e287]
                - generic [ref=f356e290]:
                  - checkbox "Check me out" [ref=f356e291]
                  - generic [ref=f356e293]: Check me out
                - button "Submit" [ref=f356e294] [cursor=pointer]
            - generic [ref=f356e295]:
              - generic [ref=f356e296]: Block form
              - generic [ref=f356e297]:
                - generic [ref=f356e298]:
                  - generic [ref=f356e300]:
                    - generic [ref=f356e301]: First Name
                    - textbox "First Name" [ref=f356e302]
                  - generic [ref=f356e304]:
                    - generic [ref=f356e305]: Last Name
                    - textbox "Last Name" [ref=f356e306]
                - generic [ref=f356e307]:
                  - generic [ref=f356e309]:
                    - generic [ref=f356e310]: Email
                    - textbox "Email" [ref=f356e311]
                  - generic [ref=f356e313]:
                    - generic [ref=f356e314]: Website
                    - textbox "Website" [ref=f356e315]
                - button "Submit" [ref=f356e316] [cursor=pointer]
        - generic [ref=f356e319]:
          - generic [ref=f356e320]: Horizontal form
          - generic [ref=f356e322]:
            - generic [ref=f356e323]:
              - generic [ref=f356e324]: Email
              - textbox "Email" [ref=f356e326]
            - generic [ref=f356e327]:
              - generic [ref=f356e328]: Password
              - textbox "Password" [ref=f356e330]
            - generic [ref=f356e335]:
              - checkbox "Remember me" [ref=f356e336]
              - generic [ref=f356e338]: Remember me
            - button "Sign in" [ref=f356e341] [cursor=pointer]
      - navigation [ref=f356e343]:
        - generic [ref=f356e344]:
          - generic [ref=f356e345]:
            - text: Created with ♥ by
            - link "Akveo" [ref=f356e347] [cursor=pointer]:
              - /url: https://akveo.page.link/8V2f
            - text: "2019"
          - generic [ref=f356e348]:
            - link "" [ref=f356e349] [cursor=pointer]:
              - /url: "#"
            - link "" [ref=f356e350] [cursor=pointer]:
              - /url: "#"
            - link "" [ref=f356e351] [cursor=pointer]:
              - /url: "#"
            - link "" [ref=f356e352] [cursor=pointer]:
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