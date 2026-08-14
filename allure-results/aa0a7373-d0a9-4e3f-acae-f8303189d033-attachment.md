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
  - element was detached from the DOM, retrying
    - locator resolved to <div class="cell-content">24</div>
  - attempting click action
    - waiting for element to be visible, enabled and stable
    - element is visible, enabled and stable
    - scrolling into view if needed
    - done scrolling
    - performing click action
  - operation was aborted: Test timeout of 4000ms exceeded.

```

# Page snapshot

```yaml
- generic [ref=f122e5]:
  - generic [ref=f122e7]:
    - navigation [ref=f122e9]:
      - generic [ref=f122e10]:
        - generic [ref=f122e11]:
          - generic [ref=f122e12]:
            - link [ref=f122e13] [cursor=pointer]:
              - /url: "#"
            - link "PW-test" [ref=f122e23] [cursor=pointer]:
              - /url: "#"
          - button "Light" [ref=f122e25] [cursor=pointer]
        - generic [ref=f122e34]:
          - button [ref=f122e37] [cursor=pointer]
          - link [ref=f122e45] [cursor=pointer]:
            - /url: "#"
          - link [ref=f122e53] [cursor=pointer]:
            - /url: "#"
          - generic [ref=f122e60]: Nick Jones
    - generic [ref=f122e66]:
      - list [ref=f122e71]:
        - listitem [ref=f122e72]:
          - link "IoT Dashboard" [ref=f122e73] [cursor=pointer]:
            - /url: /pages/iot-dashboard
        - listitem [ref=f122e80]:
          - generic [ref=f122e81]: FEATURES
        - listitem [ref=f122e82]:
          - link "Forms" [expanded] [ref=f122e83] [cursor=pointer]:
            - /url: "#"
          - list [ref=f122e97]:
            - listitem [ref=f122e98]:
              - link "Form Layouts" [ref=f122e99] [cursor=pointer]:
                - /url: /pages/forms/layouts
            - listitem [ref=f122e100]:
              - link "Datepicker" [ref=f122e101] [cursor=pointer]:
                - /url: /pages/forms/datepicker
        - listitem [ref=f122e102]:
          - link "Modal & Overlays" [ref=f122e103] [cursor=pointer]:
            - /url: "#"
          - list:
            - listitem [ref=f122e118]:
              - link "Dialog" [ref=f122e119] [cursor=pointer]:
                - /url: /pages/modal-overlays/dialog
            - listitem [ref=f122e120]:
              - link "Window" [ref=f122e121] [cursor=pointer]:
                - /url: /pages/modal-overlays/window
            - listitem [ref=f122e122]:
              - link "Popover" [ref=f122e123] [cursor=pointer]:
                - /url: /pages/modal-overlays/popover
            - listitem [ref=f122e124]:
              - link "Toastr" [ref=f122e125] [cursor=pointer]:
                - /url: /pages/modal-overlays/toastr
            - listitem [ref=f122e126]:
              - link "Tooltip" [ref=f122e127] [cursor=pointer]:
                - /url: /pages/modal-overlays/tooltip
        - listitem [ref=f122e128]:
          - link "Extra Components" [ref=f122e129] [cursor=pointer]:
            - /url: "#"
          - list:
            - listitem [ref=f122e145]:
              - link "Calendar" [ref=f122e146] [cursor=pointer]:
                - /url: /pages/extra-components/calendar
        - listitem [ref=f122e147]:
          - link "Charts" [ref=f122e148] [cursor=pointer]:
            - /url: "#"
          - list:
            - listitem [ref=f122e162]:
              - link "Echarts" [ref=f122e163] [cursor=pointer]:
                - /url: /pages/charts/echarts
        - listitem [ref=f122e164]:
          - link "Tables & Data" [ref=f122e165] [cursor=pointer]:
            - /url: "#"
          - list:
            - listitem [ref=f122e181]:
              - link "Smart Table" [ref=f122e182] [cursor=pointer]:
                - /url: /pages/tables/smart-table
            - listitem [ref=f122e183]:
              - link "Tree Grid" [ref=f122e184] [cursor=pointer]:
                - /url: /pages/tables/tree-grid
        - listitem [ref=f122e185]:
          - link "Auth" [ref=f122e186] [cursor=pointer]:
            - /url: "#"
          - list:
            - listitem [ref=f122e200]:
              - link "Login" [ref=f122e201] [cursor=pointer]:
                - /url: /auth/login
            - listitem [ref=f122e202]:
              - link "Register" [ref=f122e203] [cursor=pointer]:
                - /url: /auth/register
            - listitem [ref=f122e204]:
              - link "Request Password" [ref=f122e205] [cursor=pointer]:
                - /url: /auth/request-password
            - listitem [ref=f122e206]:
              - link "Reset Password" [ref=f122e207] [cursor=pointer]:
                - /url: /auth/reset-password
      - generic [ref=f122e208]:
        - generic [ref=f122e213]:
          - generic [ref=f122e215]:
            - generic [ref=f122e216]: Common Datepicker
            - textbox "Form Picker" [ref=f122e218]: Aug 24, 2026
          - generic [ref=f122e220]:
            - generic [ref=f122e221]: Datepicker With Range
            - textbox "Range Picker" [ref=f122e223]: Aug 20, 2026
          - generic [ref=f122e225]:
            - generic [ref=f122e226]: Datepicker With Disabled Min Max Values
            - textbox "Min Max Picker" [ref=f122e228]
        - navigation [ref=f122e230]:
          - generic [ref=f122e231]:
            - generic [ref=f122e232]:
              - text: Created with ♥ by
              - link "Akveo" [ref=f122e234] [cursor=pointer]:
                - /url: https://akveo.page.link/8V2f
              - text: "2019"
            - generic [ref=f122e235]:
              - link "" [ref=f122e236] [cursor=pointer]:
                - /url: "#"
              - link "" [ref=f122e237] [cursor=pointer]:
                - /url: "#"
              - link "" [ref=f122e238] [cursor=pointer]:
                - /url: "#"
              - link "" [ref=f122e239] [cursor=pointer]:
                - /url: "#"
  - generic [ref=f122e245]:
    - generic [ref=f122e246]:
      - button "August 2026" [ref=f122e248] [cursor=pointer]
      - generic [ref=f122e255]:
        - button [ref=f122e256] [cursor=pointer]
        - button [ref=f122e263] [cursor=pointer]
    - generic [ref=f122e272]:
      - generic [ref=f122e273]:
        - generic [ref=f122e274]: Su
        - generic [ref=f122e275]: Mo
        - generic [ref=f122e276]: Tu
        - generic [ref=f122e277]: We
        - generic [ref=f122e278]: Th
        - generic [ref=f122e279]: Fr
        - generic [ref=f122e280]: Sa
      - generic [ref=f122e281]:
        - generic [ref=f122e282]:
          - generic [ref=f122e283] [cursor=pointer]: "26"
          - generic [ref=f122e285] [cursor=pointer]: "27"
          - generic [ref=f122e287] [cursor=pointer]: "28"
          - generic [ref=f122e289] [cursor=pointer]: "29"
          - generic [ref=f122e291] [cursor=pointer]: "30"
          - generic [ref=f122e293] [cursor=pointer]: "31"
          - generic [ref=f122e295] [cursor=pointer]: "1"
        - generic [ref=f122e297]:
          - generic [ref=f122e298] [cursor=pointer]: "2"
          - generic [ref=f122e300] [cursor=pointer]: "3"
          - generic [ref=f122e302] [cursor=pointer]: "4"
          - generic [ref=f122e304] [cursor=pointer]: "5"
          - generic [ref=f122e306] [cursor=pointer]: "6"
          - generic [ref=f122e308] [cursor=pointer]: "7"
          - generic [ref=f122e310] [cursor=pointer]: "8"
        - generic [ref=f122e312]:
          - generic [ref=f122e313] [cursor=pointer]: "9"
          - generic [ref=f122e315] [cursor=pointer]: "10"
          - generic [ref=f122e317] [cursor=pointer]: "11"
          - generic [ref=f122e319] [cursor=pointer]: "12"
          - generic [ref=f122e321] [cursor=pointer]: "13"
          - generic [ref=f122e323] [cursor=pointer]: "14"
          - generic [ref=f122e325] [cursor=pointer]: "15"
        - generic [ref=f122e327]:
          - generic [ref=f122e328] [cursor=pointer]: "16"
          - generic [ref=f122e330] [cursor=pointer]: "17"
          - generic [ref=f122e332] [cursor=pointer]: "18"
          - generic [ref=f122e334] [cursor=pointer]: "19"
          - generic [ref=f122e336] [cursor=pointer]: "20"
          - generic [ref=f122e338] [cursor=pointer]: "21"
          - generic [ref=f122e340] [cursor=pointer]: "22"
        - generic [ref=f122e342]:
          - generic [ref=f122e343] [cursor=pointer]: "23"
          - generic [ref=f122e345] [cursor=pointer]: "24"
          - generic [ref=f122e347] [cursor=pointer]: "25"
          - generic [ref=f122e349] [cursor=pointer]: "26"
          - generic [ref=f122e351] [cursor=pointer]: "27"
          - generic [ref=f122e353] [cursor=pointer]: "28"
          - generic [ref=f122e355] [cursor=pointer]: "29"
        - generic [ref=f122e357]:
          - generic [ref=f122e358] [cursor=pointer]: "30"
          - generic [ref=f122e360] [cursor=pointer]: "31"
          - generic [ref=f122e362] [cursor=pointer]: "1"
          - generic [ref=f122e364] [cursor=pointer]: "2"
          - generic [ref=f122e366] [cursor=pointer]: "3"
          - generic [ref=f122e368] [cursor=pointer]: "4"
          - generic [ref=f122e370] [cursor=pointer]: "5"
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