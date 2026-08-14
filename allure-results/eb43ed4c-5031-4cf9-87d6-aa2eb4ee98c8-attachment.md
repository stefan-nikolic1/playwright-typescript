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
    - locator resolved to <circle r="16" cx="232.630" cy="232.630" fill="#f7f9fc" stroke-width="3" stroke="#3366ff" _ngcontent-jpc-c275=""></circle>
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
- generic [ref=f338e7]:
  - navigation [ref=f338e9]:
    - generic [ref=f338e10]:
      - generic [ref=f338e11]:
        - generic [ref=f338e12]:
          - link [ref=f338e13] [cursor=pointer]:
            - /url: "#"
          - link "PW-test" [ref=f338e23] [cursor=pointer]:
            - /url: "#"
        - button "Light" [ref=f338e25] [cursor=pointer]
      - generic [ref=f338e34]:
        - button [active] [ref=f338e37] [cursor=pointer]
        - link [ref=f338e45] [cursor=pointer]:
          - /url: "#"
        - link [ref=f338e53] [cursor=pointer]:
          - /url: "#"
        - generic [ref=f338e60]: Nick Jones
  - generic [ref=f338e66]:
    - list [ref=f338e71]:
      - listitem [ref=f338e72]:
        - link "IoT Dashboard" [ref=f338e73] [cursor=pointer]:
          - /url: /pages/iot-dashboard
      - listitem [ref=f338e80]:
        - generic [ref=f338e81]: FEATURES
      - listitem [ref=f338e82]:
        - link "Forms" [expanded] [ref=f338e83] [cursor=pointer]:
          - /url: "#"
        - list [ref=f338e97]:
          - listitem [ref=f338e98]:
            - link "Form Layouts" [ref=f338e99] [cursor=pointer]:
              - /url: /pages/forms/layouts
          - listitem [ref=f338e100]:
            - link "Datepicker" [ref=f338e101] [cursor=pointer]:
              - /url: /pages/forms/datepicker
      - listitem [ref=f338e102]:
        - link "Modal & Overlays" [ref=f338e103] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f338e118]:
            - link "Dialog" [ref=f338e119] [cursor=pointer]:
              - /url: /pages/modal-overlays/dialog
          - listitem [ref=f338e120]:
            - link "Window" [ref=f338e121] [cursor=pointer]:
              - /url: /pages/modal-overlays/window
          - listitem [ref=f338e122]:
            - link "Popover" [ref=f338e123] [cursor=pointer]:
              - /url: /pages/modal-overlays/popover
          - listitem [ref=f338e124]:
            - link "Toastr" [ref=f338e125] [cursor=pointer]:
              - /url: /pages/modal-overlays/toastr
          - listitem [ref=f338e126]:
            - link "Tooltip" [ref=f338e127] [cursor=pointer]:
              - /url: /pages/modal-overlays/tooltip
      - listitem [ref=f338e128]:
        - link "Extra Components" [ref=f338e129] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f338e145]:
            - link "Calendar" [ref=f338e146] [cursor=pointer]:
              - /url: /pages/extra-components/calendar
      - listitem [ref=f338e147]:
        - link "Charts" [ref=f338e148] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f338e162]:
            - link "Echarts" [ref=f338e163] [cursor=pointer]:
              - /url: /pages/charts/echarts
      - listitem [ref=f338e164]:
        - link "Tables & Data" [ref=f338e165] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f338e181]:
            - link "Smart Table" [ref=f338e182] [cursor=pointer]:
              - /url: /pages/tables/smart-table
          - listitem [ref=f338e183]:
            - link "Tree Grid" [ref=f338e184] [cursor=pointer]:
              - /url: /pages/tables/tree-grid
      - listitem [ref=f338e185]:
        - link "Auth" [ref=f338e186] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=f338e200]:
            - link "Login" [ref=f338e201] [cursor=pointer]:
              - /url: /auth/login
          - listitem [ref=f338e202]:
            - link "Register" [ref=f338e203] [cursor=pointer]:
              - /url: /auth/register
          - listitem [ref=f338e204]:
            - link "Request Password" [ref=f338e205] [cursor=pointer]:
              - /url: /auth/request-password
          - listitem [ref=f338e206]:
            - link "Reset Password" [ref=f338e207] [cursor=pointer]:
              - /url: /auth/reset-password
    - generic [ref=f338e208]:
      - generic [ref=f338e212]:
        - generic [ref=f338e215]:
          - generic [ref=f338e216]: Inline form
          - generic [ref=f338e218]:
            - textbox "Jane Doe" [ref=f338e219]
            - textbox "Email" [ref=f338e220]
            - generic [ref=f338e222]:
              - checkbox "Remember me" [ref=f338e223]
              - generic [ref=f338e225]: Remember me
            - button "Submit" [ref=f338e226] [cursor=pointer]
        - generic [ref=f338e227]:
          - generic [ref=f338e228]:
            - generic [ref=f338e229]:
              - generic [ref=f338e230]: Using the Grid
              - generic [ref=f338e232]:
                - generic [ref=f338e233]:
                  - generic [ref=f338e234]: Email
                  - textbox "Email" [ref=f338e236]
                - generic [ref=f338e237]:
                  - generic [ref=f338e238]: Password
                  - textbox "Password" [ref=f338e240]
                - generic [ref=f338e241]:
                  - generic [ref=f338e242]: Radios
                  - generic [ref=f338e244]:
                    - generic [ref=f338e246]:
                      - radio "Option 1" [ref=f338e247]
                      - generic [ref=f338e250]: Option 1
                    - generic [ref=f338e252]:
                      - radio "Option 2" [ref=f338e253]
                      - generic [ref=f338e256]: Option 2
                    - generic [ref=f338e258]:
                      - radio "Disabled Option" [checked] [disabled] [ref=f338e259]
                      - generic [ref=f338e262]: Disabled Option
                - button "Sign in" [ref=f338e265] [cursor=pointer]
            - generic [ref=f338e266]:
              - generic [ref=f338e267]: Form without labels
              - generic [ref=f338e269]:
                - textbox "Recipients" [ref=f338e271]
                - textbox "Subject" [ref=f338e273]
                - textbox "Message" [ref=f338e275]
                - button "Send" [ref=f338e276] [cursor=pointer]
          - generic [ref=f338e277]:
            - generic [ref=f338e278]:
              - generic [ref=f338e279]: Basic form
              - generic [ref=f338e281]:
                - generic [ref=f338e282]:
                  - generic [ref=f338e283]: Email address
                  - textbox "Email address" [ref=f338e284]:
                    - /placeholder: Email
                - generic [ref=f338e285]:
                  - generic [ref=f338e286]: Password
                  - textbox "Password" [ref=f338e287]
                - generic [ref=f338e290]:
                  - checkbox "Check me out" [ref=f338e291]
                  - generic [ref=f338e293]: Check me out
                - button "Submit" [ref=f338e294] [cursor=pointer]
            - generic [ref=f338e295]:
              - generic [ref=f338e296]: Block form
              - generic [ref=f338e297]:
                - generic [ref=f338e298]:
                  - generic [ref=f338e300]:
                    - generic [ref=f338e301]: First Name
                    - textbox "First Name" [ref=f338e302]
                  - generic [ref=f338e304]:
                    - generic [ref=f338e305]: Last Name
                    - textbox "Last Name" [ref=f338e306]
                - generic [ref=f338e307]:
                  - generic [ref=f338e309]:
                    - generic [ref=f338e310]: Email
                    - textbox "Email" [ref=f338e311]
                  - generic [ref=f338e313]:
                    - generic [ref=f338e314]: Website
                    - textbox "Website" [ref=f338e315]
                - button "Submit" [ref=f338e316] [cursor=pointer]
        - generic [ref=f338e319]:
          - generic [ref=f338e320]: Horizontal form
          - generic [ref=f338e322]:
            - generic [ref=f338e323]:
              - generic [ref=f338e324]: Email
              - textbox "Email" [ref=f338e326]
            - generic [ref=f338e327]:
              - generic [ref=f338e328]: Password
              - textbox "Password" [ref=f338e330]
            - generic [ref=f338e335]:
              - checkbox "Remember me" [ref=f338e336]
              - generic [ref=f338e338]: Remember me
            - button "Sign in" [ref=f338e341] [cursor=pointer]
      - navigation [ref=f338e343]:
        - generic [ref=f338e344]:
          - generic [ref=f338e345]:
            - text: Created with ♥ by
            - link "Akveo" [ref=f338e347] [cursor=pointer]:
              - /url: https://akveo.page.link/8V2f
            - text: "2019"
          - generic [ref=f338e348]:
            - link "" [ref=f338e349] [cursor=pointer]:
              - /url: "#"
            - link "" [ref=f338e350] [cursor=pointer]:
              - /url: "#"
            - link "" [ref=f338e351] [cursor=pointer]:
              - /url: "#"
            - link "" [ref=f338e352] [cursor=pointer]:
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