# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: tests/testMobile.spec.ts >> input fields
- Location: tests/testMobile.spec.ts:3:5

# Error details

```
Test timeout of 4000ms exceeded.
```

```
Error: page.goto: Test timeout of 4000ms exceeded.
Call log:
  - navigating to "http://localhost:4200/", waiting until "load"
  - operation was aborted: Test timeout of 4000ms exceeded.

```

# Page snapshot

```yaml
- generic [ref=f2e7]:
  - navigation [ref=f2e9]:
    - generic [ref=f2e10]:
      - generic [ref=f2e12]:
        - link [ref=f2e13]:
          - /url: "#"
        - link "PW-test" [ref=f2e23]:
          - /url: "#"
      - generic [ref=f2e27] [cursor=pointer]
  - generic [ref=f2e30]:
    - list [ref=f2e32]:
      - listitem [ref=f2e33]:
        - link "IoT Dashboard" [ref=f2e34]:
          - /url: /pages/iot-dashboard
      - listitem [ref=f2e39]:
        - generic [ref=f2e40]: FEATURES
      - listitem [ref=f2e41]:
        - link "Forms" [ref=f2e42]:
          - /url: "#"
        - list:
          - listitem:
            - link "Form Layouts" [ref=f2e52]:
              - /url: /pages/forms/layouts
          - listitem:
            - link "Datepicker" [ref=f2e53]:
              - /url: /pages/forms/datepicker
      - listitem [ref=f2e54]:
        - link "Modal & Overlays" [ref=f2e55]:
          - /url: "#"
        - list:
          - listitem:
            - link "Dialog" [ref=f2e66]:
              - /url: /pages/modal-overlays/dialog
          - listitem:
            - link "Window" [ref=f2e67]:
              - /url: /pages/modal-overlays/window
          - listitem:
            - link "Popover" [ref=f2e68]:
              - /url: /pages/modal-overlays/popover
          - listitem:
            - link "Toastr" [ref=f2e69]:
              - /url: /pages/modal-overlays/toastr
          - listitem:
            - link "Tooltip" [ref=f2e70]:
              - /url: /pages/modal-overlays/tooltip
      - listitem [ref=f2e71]:
        - link "Extra Components" [ref=f2e72]:
          - /url: "#"
        - list:
          - listitem:
            - link "Calendar" [ref=f2e84]:
              - /url: /pages/extra-components/calendar
      - listitem [ref=f2e85]:
        - link "Charts" [ref=f2e86]:
          - /url: "#"
        - list:
          - listitem:
            - link "Echarts" [ref=f2e96]:
              - /url: /pages/charts/echarts
      - listitem [ref=f2e97]:
        - link "Tables & Data" [ref=f2e98]:
          - /url: "#"
        - list:
          - listitem:
            - link "Smart Table" [ref=f2e110]:
              - /url: /pages/tables/smart-table
          - listitem:
            - link "Tree Grid" [ref=f2e111]:
              - /url: /pages/tables/tree-grid
      - listitem [ref=f2e112]:
        - link "Auth" [ref=f2e113]:
          - /url: "#"
        - list:
          - listitem:
            - link "Login" [ref=f2e123]:
              - /url: /auth/login
          - listitem:
            - link "Register" [ref=f2e124]:
              - /url: /auth/register
          - listitem:
            - link "Request Password" [ref=f2e125]:
              - /url: /auth/request-password
          - listitem:
            - link "Reset Password" [ref=f2e126]:
              - /url: /auth/reset-password
    - generic [ref=f2e127]:
      - generic [ref=f2e130]:
        - generic [ref=f2e131]:
          - generic [ref=f2e134]:
            - generic [ref=f2e135]: 
            - generic [ref=f2e138]:
              - generic [ref=f2e139]: Light
              - generic [ref=f2e140]: "ON"
          - generic [ref=f2e143]:
            - generic [ref=f2e144]: 
            - generic [ref=f2e147]:
              - generic [ref=f2e148]: Roller Shades
              - generic [ref=f2e149]: "ON"
          - generic [ref=f2e152]:
            - generic [ref=f2e153]: 
            - generic [ref=f2e156]:
              - generic [ref=f2e157]: Wireless Audio
              - generic [ref=f2e158]: "ON"
          - generic [ref=f2e161]:
            - generic [ref=f2e162]: 
            - generic [ref=f2e165]:
              - generic [ref=f2e166]: Coffee Maker
              - generic [ref=f2e167]: "ON"
        - generic [ref=f2e168]:
          - generic [ref=f2e172]:
            - list [ref=f2e173]:
              - listitem [ref=f2e174]:
                - link "Temperature" [ref=f2e175] [cursor=pointer]:
                  - /url: ""
              - listitem [ref=f2e177]:
                - link "Humidity" [ref=f2e178] [cursor=pointer]:
                  - /url: ""
            - text: °     %    
          - generic [ref=f2e184]:
            - generic [ref=f2e185]:
              - generic [ref=f2e186]: Consumed
              - generic [ref=f2e187]: 816 kWh
            - generic [ref=f2e188]:
              - generic [ref=f2e189]: Spent
              - generic [ref=f2e190]: 291 USD
            - button "week" [ref=f2e192] [cursor=pointer]
        - generic [ref=f2e202]:
          - generic [ref=f2e205]:
            - generic [ref=f2e207]:
              - generic [ref=f2e208]: Room Management
              - img [ref=f2e210]:
                - generic [ref=f2e271]:
                  - generic [ref=f2e272] [cursor=pointer]
                  - generic: Kitchen
                - generic [ref=f2e275]:
                  - generic [ref=f2e276] [cursor=pointer]
                  - generic: Bedroom
                - generic [ref=f2e279]:
                  - generic [ref=f2e280] [cursor=pointer]
                  - generic: Hallway
                - generic [ref=f2e283]:
                  - generic [ref=f2e284] [cursor=pointer]
                  - generic: Living Room
            - generic [ref=f2e289]:
              - generic [ref=f2e292]:
                - heading "Come Together" [level=4] [ref=f2e293]
                - generic [ref=f2e294]: Beatles
              - slider [ref=f2e296]: "0"
              - button [ref=f2e298] [cursor=pointer]
          - list [ref=f2e310]:
            - listitem [ref=f2e311]:
              - link "Contacts" [ref=f2e312] [cursor=pointer]:
                - /url: ""
            - listitem [ref=f2e314]:
              - link "Recent" [ref=f2e315] [cursor=pointer]:
                - /url: ""
          - generic [ref=f2e317]:
            - generic [ref=f2e319]:
              - generic [ref=f2e320]: Solar Energy Consumption
              - generic [ref=f2e323]:
                - generic [ref=f2e324]: 6.421 kWh
                - generic [ref=f2e325]: out of 8.421 kWh
            - generic [ref=f2e327]:
              - generic [ref=f2e329]:
                - generic [ref=f2e330]: UI Kitten
                - generic [ref=f2e331]: "UI Kitten is a framework that contains a set of commonly used UI components styled in a similar way. The most awesome thing: you can change themes on the fly by just passing a different set of variables. 100% native. Give our kitten a try!"
              - generic [ref=f2e332]:
                - link [ref=f2e333]:
                  - /url: https://akveo.github.io/react-native-ui-kitten?utm_campaign=ui_kitten%20-%20home%20-%20ngx_admin%20code%20embed&utm_source=ngx_admin&utm_medium=embedded&utm_content=iot_dashboard_kitten_card
                - link "" [ref=f2e340]:
                  - /url: https://itunes.apple.com/us/app/kitten-tricks/id1246143230
                - link "" [ref=f2e342]:
                  - /url: https://play.google.com/store/apps/details?id=com.akveo.kittenTricks
                - link [ref=f2e344]:
                  - /url: https://github.com/akveo/react-native-ui-kitten
          - generic [ref=f2e353]:
            - generic [ref=f2e354]: New York
            - generic [ref=f2e355]: Mon 29 May
            - generic [ref=f2e356]: 20°
            - generic [ref=f2e372]:
              - generic [ref=f2e373]:
                - generic [ref=f2e374]: max
                - generic [ref=f2e375]: 23°
              - generic [ref=f2e376]:
                - generic [ref=f2e377]: min
                - generic [ref=f2e378]: 19°
              - generic [ref=f2e379]:
                - generic [ref=f2e380]: wind
                - generic [ref=f2e381]: 4 km/h
              - generic [ref=f2e382]:
                - generic [ref=f2e383]: hum
                - generic [ref=f2e384]: 87%
            - generic [ref=f2e385]:
              - generic [ref=f2e386]:
                - generic [ref=f2e387]: Sun
                - generic [ref=f2e388]: 
                - generic [ref=f2e389]: 17°
              - generic [ref=f2e390]:
                - generic [ref=f2e391]: Mon
                - generic [ref=f2e392]: 
                - generic [ref=f2e393]: 19°
              - generic [ref=f2e394]:
                - generic [ref=f2e395]: Tue
                - generic [ref=f2e396]: 
                - generic [ref=f2e397]: 22°
              - generic [ref=f2e398]:
                - generic [ref=f2e399]: Wed
                - generic [ref=f2e400]: 
                - generic [ref=f2e401]: 21°
          - generic [ref=f2e404]:
            - generic [ref=f2e405]:
              - text: Security Cameras
              - button "" [ref=f2e406] [cursor=pointer]
              - button [ref=f2e408] [cursor=pointer]
            - generic [ref=f2e419]:
              - generic [ref=f2e420]: "Camera #1"
              - generic [ref=f2e422]: "Camera #2"
              - generic [ref=f2e424]: "Camera #3"
              - generic [ref=f2e426]: "Camera #4"
            - generic [ref=f2e429]:
              - generic [ref=f2e430]: Pause
              - generic [ref=f2e439]: Logs
              - generic [ref=f2e451]: Search
              - generic [ref=f2e458]: Setup
      - navigation [ref=f2e467]:
        - generic [ref=f2e468]:
          - generic [ref=f2e469]:
            - text: Created with ♥ by
            - link "Akveo" [ref=f2e471]:
              - /url: https://akveo.page.link/8V2f
            - text: "2019"
          - generic [ref=f2e472]:
            - link "" [ref=f2e473]:
              - /url: "#"
            - link "" [ref=f2e474]:
              - /url: "#"
            - link "" [ref=f2e475]:
              - /url: "#"
            - link "" [ref=f2e476]:
              - /url: "#"
```

# Test source

```ts
  1  | import { test, expect } from '@playwright/test'
  2  | 
  3  | test('input fields', async ({ page }, testInfo) => {
  4  | 
> 5  |   await page.goto('/')
     |              ^ Error: page.goto: Test timeout of 4000ms exceeded.
  6  |   if (testInfo.project.name == 'mobile') {
  7  |     await page.locator('.sidebar-toggle').click()
  8  |   }
  9  |   await page.getByText('Forms').click()
  10 |   await page.getByText('Form Layouts').click()
  11 |   if (testInfo.project.name == 'mobile') {
  12 |     await page.locator('.sidebar-toggle').click()
  13 |   }
  14 |   const usingTheGridEmailInput = page.locator('nb-card', { hasText: "Using the Grid" }).getByRole('textbox', { name: "Email" })
  15 |   await usingTheGridEmailInput.fill('test@test.com')
  16 |   await usingTheGridEmailInput.clear()
  17 |   await usingTheGridEmailInput.type('test2@test.com')
  18 | 
  19 | })
```