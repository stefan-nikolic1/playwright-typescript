# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: tests/uiComponents.spec.ts >> Form Layouts page >> web tables
- Location: tests/uiComponents.spec.ts:120:9

# Error details

```
Test timeout of 4000ms exceeded.
```

```
Error: page.waitForTimeout: Test timeout of 4000ms exceeded.
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
        - button [ref=e37] [cursor=pointer]
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
        - link "Tables & Data" [expanded] [ref=e165] [cursor=pointer]:
          - /url: "#"
        - list [ref=e181]:
          - listitem [ref=e182]:
            - link "Smart Table" [ref=e183] [cursor=pointer]:
              - /url: /pages/tables/smart-table
          - listitem [ref=e184]:
            - link "Tree Grid" [ref=e185] [cursor=pointer]:
              - /url: /pages/tables/tree-grid
      - listitem [ref=e186]:
        - link "Auth" [ref=e187] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=e201]:
            - link "Login" [ref=e202] [cursor=pointer]:
              - /url: /auth/login
          - listitem [ref=e203]:
            - link "Register" [ref=e204] [cursor=pointer]:
              - /url: /auth/register
          - listitem [ref=e205]:
            - link "Request Password" [ref=e206] [cursor=pointer]:
              - /url: /auth/request-password
          - listitem [ref=e207]:
            - link "Reset Password" [ref=e208] [cursor=pointer]:
              - /url: /auth/reset-password
    - generic [ref=e209]:
      - generic [ref=e214]:
        - generic [ref=e215]: Smart Table
        - table [ref=e218]:
          - rowgroup [ref=e219]:
            - row [ref=e220]:
              - columnheader "Actions" [ref=e221]
              - columnheader [ref=e223]:
                - link "ID" [ref=e227] [cursor=pointer]:
                  - /url: "#"
              - columnheader [ref=e228]:
                - link "First Name" [ref=e232] [cursor=pointer]:
                  - /url: "#"
              - columnheader [ref=e233]:
                - link "Last Name" [ref=e237] [cursor=pointer]:
                  - /url: "#"
              - columnheader [ref=e238]:
                - link "Username" [ref=e242] [cursor=pointer]:
                  - /url: "#"
              - columnheader [ref=e243]:
                - link "E-mail" [ref=e247] [cursor=pointer]:
                  - /url: "#"
              - columnheader [ref=e248]:
                - link "Age" [ref=e252] [cursor=pointer]:
                  - /url: "#"
            - row [ref=e253]:
              - columnheader [ref=e254]:
                - link "" [ref=e255] [cursor=pointer]:
                  - /url: "#"
              - columnheader [ref=e257]:
                - textbox "ID" [ref=e262]
              - columnheader [ref=e263]:
                - textbox "First Name" [ref=e268]
              - columnheader [ref=e269]:
                - textbox "Last Name" [ref=e274]
              - columnheader [ref=e275]:
                - textbox "Username" [ref=e280]
              - columnheader [ref=e281]:
                - textbox "E-mail" [ref=e286]
              - columnheader [ref=e287]:
                - textbox "Age" [active] [ref=e292]: "200"
          - rowgroup [ref=e293]:
            - row [ref=e294]:
              - cell " " [ref=e295]:
                - generic:
                  - link "":
                    - /url: "#"
                  - link "":
                    - /url: "#"
              - cell "14" [ref=e298]
              - cell "Garegin" [ref=e303]
              - cell "Jirair" [ref=e308]
              - cell "@garegin" [ref=e313]
              - cell "garegin@gmail.com" [ref=e318]
              - cell "40" [ref=e323]
            - row [ref=e328]:
              - cell " " [ref=e329]:
                - generic:
                  - link "":
                    - /url: "#"
                  - link "":
                    - /url: "#"
              - cell "50" [ref=e332]
              - cell "Rebekah" [ref=e337]
              - cell "Duran" [ref=e342]
              - cell "@Gross" [ref=e347]
              - cell "rebekahgross@comtours.com" [ref=e352]
              - cell "40" [ref=e357]
      - navigation [ref=e363]:
        - generic [ref=e364]:
          - generic [ref=e365]:
            - text: Created with ♥ by
            - link "Akveo" [ref=e367] [cursor=pointer]:
              - /url: https://akveo.page.link/8V2f
            - text: "2019"
          - generic [ref=e368]:
            - link "" [ref=e369] [cursor=pointer]:
              - /url: "#"
            - link "" [ref=e370] [cursor=pointer]:
              - /url: "#"
            - link "" [ref=e371] [cursor=pointer]:
              - /url: "#"
            - link "" [ref=e372] [cursor=pointer]:
              - /url: "#"
```

# Test source

```ts
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
  143 | 
  144 |         for (let age of ages) {
  145 |             await page.locator('input-filter').getByPlaceholder('Age').clear()
  146 |             await page.locator('input-filter').getByPlaceholder('Age').fill(age)
> 147 |             await page.waitForTimeout(500)
      |                        ^ Error: page.waitForTimeout: Test timeout of 4000ms exceeded.
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
  191 |         await tempGauge.evaluate(node => {
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