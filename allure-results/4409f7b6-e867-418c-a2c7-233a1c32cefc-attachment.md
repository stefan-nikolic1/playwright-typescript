# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: tests/usePageObjects.spec.ts >> parametrized methods
- Location: tests/usePageObjects.spec.ts:18:5

# Error details

```
Test timeout of 4000ms exceeded.
```

```
Error: locator.click: Test timeout of 4000ms exceeded.
Call log:
  - waiting for locator('.day-cell.ng-star-inserted:not(.bounding-month)').getByText('24', { exact: true })
    - locator resolved to <div class="cell-content">24</div>
  - attempting click action
    - waiting for element to be visible, enabled and stable
    - element is not stable
  - retrying click action
    - waiting for element to be visible, enabled and stable
  - operation was aborted: Test timeout of 4000ms exceeded.

```

# Page snapshot

```yaml
- generic [ref=f61e5]:
  - generic [ref=f61e7]:
    - navigation [ref=f61e9]:
      - generic [ref=f61e10]:
        - generic [ref=f61e11]:
          - generic [ref=f61e12]:
            - link [ref=f61e13] [cursor=pointer]:
              - /url: "#"
            - link "PW-test" [ref=f61e23] [cursor=pointer]:
              - /url: "#"
          - button "Light" [ref=f61e25] [cursor=pointer]
        - generic [ref=f61e34]:
          - button [ref=f61e37] [cursor=pointer]
          - link [ref=f61e45] [cursor=pointer]:
            - /url: "#"
          - link [ref=f61e53] [cursor=pointer]:
            - /url: "#"
          - generic [ref=f61e60]: Nick Jones
    - generic [ref=f61e66]:
      - list [ref=f61e71]:
        - listitem [ref=f61e72]:
          - link "IoT Dashboard" [ref=f61e73] [cursor=pointer]:
            - /url: /pages/iot-dashboard
        - listitem [ref=f61e80]:
          - generic [ref=f61e81]: FEATURES
        - listitem [ref=f61e82]:
          - link "Forms" [expanded] [ref=f61e83] [cursor=pointer]:
            - /url: "#"
          - list [ref=f61e97]:
            - listitem [ref=f61e98]:
              - link "Form Layouts" [ref=f61e99] [cursor=pointer]:
                - /url: /pages/forms/layouts
            - listitem [ref=f61e100]:
              - link "Datepicker" [ref=f61e101] [cursor=pointer]:
                - /url: /pages/forms/datepicker
        - listitem [ref=f61e102]:
          - link "Modal & Overlays" [ref=f61e103] [cursor=pointer]:
            - /url: "#"
          - list:
            - listitem [ref=f61e118]:
              - link "Dialog" [ref=f61e119] [cursor=pointer]:
                - /url: /pages/modal-overlays/dialog
            - listitem [ref=f61e120]:
              - link "Window" [ref=f61e121] [cursor=pointer]:
                - /url: /pages/modal-overlays/window
            - listitem [ref=f61e122]:
              - link "Popover" [ref=f61e123] [cursor=pointer]:
                - /url: /pages/modal-overlays/popover
            - listitem [ref=f61e124]:
              - link "Toastr" [ref=f61e125] [cursor=pointer]:
                - /url: /pages/modal-overlays/toastr
            - listitem [ref=f61e126]:
              - link "Tooltip" [ref=f61e127] [cursor=pointer]:
                - /url: /pages/modal-overlays/tooltip
        - listitem [ref=f61e128]:
          - link "Extra Components" [ref=f61e129] [cursor=pointer]:
            - /url: "#"
          - list:
            - listitem [ref=f61e145]:
              - link "Calendar" [ref=f61e146] [cursor=pointer]:
                - /url: /pages/extra-components/calendar
        - listitem [ref=f61e147]:
          - link "Charts" [ref=f61e148] [cursor=pointer]:
            - /url: "#"
          - list:
            - listitem [ref=f61e162]:
              - link "Echarts" [ref=f61e163] [cursor=pointer]:
                - /url: /pages/charts/echarts
        - listitem [ref=f61e164]:
          - link "Tables & Data" [ref=f61e165] [cursor=pointer]:
            - /url: "#"
          - list:
            - listitem [ref=f61e181]:
              - link "Smart Table" [ref=f61e182] [cursor=pointer]:
                - /url: /pages/tables/smart-table
            - listitem [ref=f61e183]:
              - link "Tree Grid" [ref=f61e184] [cursor=pointer]:
                - /url: /pages/tables/tree-grid
        - listitem [ref=f61e185]:
          - link "Auth" [ref=f61e186] [cursor=pointer]:
            - /url: "#"
          - list:
            - listitem [ref=f61e200]:
              - link "Login" [ref=f61e201] [cursor=pointer]:
                - /url: /auth/login
            - listitem [ref=f61e202]:
              - link "Register" [ref=f61e203] [cursor=pointer]:
                - /url: /auth/register
            - listitem [ref=f61e204]:
              - link "Request Password" [ref=f61e205] [cursor=pointer]:
                - /url: /auth/request-password
            - listitem [ref=f61e206]:
              - link "Reset Password" [ref=f61e207] [cursor=pointer]:
                - /url: /auth/reset-password
      - generic [ref=f61e208]:
        - generic [ref=f61e213]:
          - generic [ref=f61e215]:
            - generic [ref=f61e216]: Common Datepicker
            - textbox "Form Picker" [ref=f61e218]: Aug 24, 2026
          - generic [ref=f61e220]:
            - generic [ref=f61e221]: Datepicker With Range
            - textbox "Range Picker" [ref=f61e223]: Aug 20, 2026
          - generic [ref=f61e225]:
            - generic [ref=f61e226]: Datepicker With Disabled Min Max Values
            - textbox "Min Max Picker" [ref=f61e228]
        - navigation [ref=f61e230]:
          - generic [ref=f61e231]:
            - generic [ref=f61e232]:
              - text: Created with ♥ by
              - link "Akveo" [ref=f61e234] [cursor=pointer]:
                - /url: https://akveo.page.link/8V2f
              - text: "2019"
            - generic [ref=f61e235]:
              - link "" [ref=f61e236] [cursor=pointer]:
                - /url: "#"
              - link "" [ref=f61e237] [cursor=pointer]:
                - /url: "#"
              - link "" [ref=f61e238] [cursor=pointer]:
                - /url: "#"
              - link "" [ref=f61e239] [cursor=pointer]:
                - /url: "#"
  - generic [ref=f61e245]:
    - generic [ref=f61e246]:
      - button "August 2026" [ref=f61e248] [cursor=pointer]
      - generic [ref=f61e255]:
        - button [ref=f61e256] [cursor=pointer]
        - button [ref=f61e263] [cursor=pointer]
    - generic [ref=f61e272]:
      - generic [ref=f61e273]:
        - generic [ref=f61e274]: Su
        - generic [ref=f61e275]: Mo
        - generic [ref=f61e276]: Tu
        - generic [ref=f61e277]: We
        - generic [ref=f61e278]: Th
        - generic [ref=f61e279]: Fr
        - generic [ref=f61e280]: Sa
      - generic [ref=f61e281]:
        - generic [ref=f61e282]:
          - generic [ref=f61e283] [cursor=pointer]: "26"
          - generic [ref=f61e285] [cursor=pointer]: "27"
          - generic [ref=f61e287] [cursor=pointer]: "28"
          - generic [ref=f61e289] [cursor=pointer]: "29"
          - generic [ref=f61e291] [cursor=pointer]: "30"
          - generic [ref=f61e293] [cursor=pointer]: "31"
          - generic [ref=f61e295] [cursor=pointer]: "1"
        - generic [ref=f61e297]:
          - generic [ref=f61e298] [cursor=pointer]: "2"
          - generic [ref=f61e300] [cursor=pointer]: "3"
          - generic [ref=f61e302] [cursor=pointer]: "4"
          - generic [ref=f61e304] [cursor=pointer]: "5"
          - generic [ref=f61e306] [cursor=pointer]: "6"
          - generic [ref=f61e308] [cursor=pointer]: "7"
          - generic [ref=f61e310] [cursor=pointer]: "8"
        - generic [ref=f61e312]:
          - generic [ref=f61e313] [cursor=pointer]: "9"
          - generic [ref=f61e315] [cursor=pointer]: "10"
          - generic [ref=f61e317] [cursor=pointer]: "11"
          - generic [ref=f61e319] [cursor=pointer]: "12"
          - generic [ref=f61e321] [cursor=pointer]: "13"
          - generic [ref=f61e323] [cursor=pointer]: "14"
          - generic [ref=f61e325] [cursor=pointer]: "15"
        - generic [ref=f61e327]:
          - generic [ref=f61e328] [cursor=pointer]: "16"
          - generic [ref=f61e330] [cursor=pointer]: "17"
          - generic [ref=f61e332] [cursor=pointer]: "18"
          - generic [ref=f61e334] [cursor=pointer]: "19"
          - generic [ref=f61e336] [cursor=pointer]: "20"
          - generic [ref=f61e338] [cursor=pointer]: "21"
          - generic [ref=f61e340] [cursor=pointer]: "22"
        - generic [ref=f61e342]:
          - generic [ref=f61e343] [cursor=pointer]: "23"
          - generic [ref=f61e345] [cursor=pointer]: "24"
          - generic [ref=f61e347] [cursor=pointer]: "25"
          - generic [ref=f61e349] [cursor=pointer]: "26"
          - generic [ref=f61e351] [cursor=pointer]: "27"
          - generic [ref=f61e353] [cursor=pointer]: "28"
          - generic [ref=f61e355] [cursor=pointer]: "29"
        - generic [ref=f61e357]:
          - generic [ref=f61e358] [cursor=pointer]: "30"
          - generic [ref=f61e360] [cursor=pointer]: "31"
          - generic [ref=f61e362] [cursor=pointer]: "1"
          - generic [ref=f61e364] [cursor=pointer]: "2"
          - generic [ref=f61e366] [cursor=pointer]: "3"
          - generic [ref=f61e368] [cursor=pointer]: "4"
          - generic [ref=f61e370] [cursor=pointer]: "5"
```

# Test source

```ts
  1  | import { Page, expect } from "@playwright/test";
  2  | import { HelperBase } from "./helperBase";
  3  | 
  4  | export class DatepickerPage extends HelperBase{
  5  | 
  6  |     constructor(page: Page){
  7  |         super(page)
  8  |     }
  9  | 
  10 |     async selectCommonDatePickerDateFromToday(numberOfDaysFromToday: number){
  11 |         const calendarInputField = this.page.getByPlaceholder('Form Picker')
  12 |         await calendarInputField.click()
  13 |         const dateToAssert = await this.selectDateInTheCalendar(numberOfDaysFromToday)
  14 |         await expect(calendarInputField).toHaveValue(dateToAssert)
  15 |     }
  16 | 
  17 |     async selectDatepickerWithRangeFromToday(startDayFromToday: number, endDayFromToday: number){
  18 |         const calendarInputField = this.page.getByPlaceholder('Range Picker')
  19 |         await calendarInputField.click()
  20 |         const dateToAssertStart = await this.selectDateInTheCalendar(startDayFromToday)
  21 |         const dateToAssertEnd = await this.selectDateInTheCalendar(endDayFromToday)
  22 |         const dateToAssert = `${dateToAssertStart} - ${dateToAssertEnd}`
  23 |         await expect(calendarInputField).toHaveValue(dateToAssert)
  24 |     }
  25 | 
  26 |     private async selectDateInTheCalendar(numberOfDaysFromToday: number){
  27 |         let date = new Date()
  28 |         date.setDate(date.getDate() + numberOfDaysFromToday)
  29 |         const expectedDate = date.getDate().toString()
  30 |         const expectedMonthShot = date.toLocaleString('En-US', {month: 'short'})
  31 |         const expectedMonthLong = date.toLocaleString('En-US', {month: 'long'})
  32 |         const expectedYear = date.getFullYear()
  33 |         const dateToAssert = `${expectedMonthShot} ${expectedDate}, ${expectedYear}`
  34 | 
  35 |         let calendarMonthAndYear = await this.page.locator('nb-calendar-view-mode').textContent() ?? ''
  36 |         const expectedMonthAndYear = ` ${expectedMonthLong} ${expectedYear}`
  37 |         while(!calendarMonthAndYear.includes(expectedMonthAndYear)){
  38 |             await this.page.locator('nb-calendar-pageable-navigation [data-name="chevron-right"]').click()
  39 |             calendarMonthAndYear = await this.page.locator('nb-calendar-view-mode').textContent() ?? ''
  40 |         }
> 41 |         await this.page.locator('.day-cell.ng-star-inserted:not(.bounding-month)').getByText(expectedDate, {exact: true}).click()
     |                                                                                                                           ^ Error: locator.click: Test timeout of 4000ms exceeded.
  42 |         return dateToAssert
  43 |     }
  44 | }
```