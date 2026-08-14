# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: tests/testMobile.spec.ts >> input fields
- Location: tests/testMobile.spec.ts:3:5

# Error details

```
TimeoutError: page.goto: Timeout 5000ms exceeded.
Call log:
  - navigating to "http://localhost:4200/", waiting until "load"

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
        - link "Forms" [ref=e83] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=e97]:
            - link "Form Layouts" [ref=e98] [cursor=pointer]:
              - /url: /pages/forms/layouts
          - listitem [ref=e99]:
            - link "Datepicker" [ref=e100] [cursor=pointer]:
              - /url: /pages/forms/datepicker
      - listitem [ref=e101]:
        - link "Modal & Overlays" [ref=e102] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=e117]:
            - link "Dialog" [ref=e118] [cursor=pointer]:
              - /url: /pages/modal-overlays/dialog
          - listitem [ref=e119]:
            - link "Window" [ref=e120] [cursor=pointer]:
              - /url: /pages/modal-overlays/window
          - listitem [ref=e121]:
            - link "Popover" [ref=e122] [cursor=pointer]:
              - /url: /pages/modal-overlays/popover
          - listitem [ref=e123]:
            - link "Toastr" [ref=e124] [cursor=pointer]:
              - /url: /pages/modal-overlays/toastr
          - listitem [ref=e125]:
            - link "Tooltip" [ref=e126] [cursor=pointer]:
              - /url: /pages/modal-overlays/tooltip
      - listitem [ref=e127]:
        - link "Extra Components" [ref=e128] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=e144]:
            - link "Calendar" [ref=e145] [cursor=pointer]:
              - /url: /pages/extra-components/calendar
      - listitem [ref=e146]:
        - link "Charts" [ref=e147] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=e161]:
            - link "Echarts" [ref=e162] [cursor=pointer]:
              - /url: /pages/charts/echarts
      - listitem [ref=e163]:
        - link "Tables & Data" [ref=e164] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=e180]:
            - link "Smart Table" [ref=e181] [cursor=pointer]:
              - /url: /pages/tables/smart-table
          - listitem [ref=e182]:
            - link "Tree Grid" [ref=e183] [cursor=pointer]:
              - /url: /pages/tables/tree-grid
      - listitem [ref=e184]:
        - link "Auth" [ref=e185] [cursor=pointer]:
          - /url: "#"
        - list:
          - listitem [ref=e199]:
            - link "Login" [ref=e200] [cursor=pointer]:
              - /url: /auth/login
          - listitem [ref=e201]:
            - link "Register" [ref=e202] [cursor=pointer]:
              - /url: /auth/register
          - listitem [ref=e203]:
            - link "Request Password" [ref=e204] [cursor=pointer]:
              - /url: /auth/request-password
          - listitem [ref=e205]:
            - link "Reset Password" [ref=e206] [cursor=pointer]:
              - /url: /auth/reset-password
    - generic [ref=e207]:
      - generic [ref=e210]:
        - generic [ref=e211]:
          - generic [ref=e214]:
            - generic [ref=e215]: 
            - generic [ref=e218]:
              - generic [ref=e219]: Light
              - generic [ref=e220]: "ON"
          - generic [ref=e223]:
            - generic [ref=e224]: 
            - generic [ref=e227]:
              - generic [ref=e228]: Roller Shades
              - generic [ref=e229]: "ON"
          - generic [ref=e232]:
            - generic [ref=e233]: 
            - generic [ref=e236]:
              - generic [ref=e237]: Wireless Audio
              - generic [ref=e238]: "ON"
          - generic [ref=e241]:
            - generic [ref=e242]: 
            - generic [ref=e245]:
              - generic [ref=e246]: Coffee Maker
              - generic [ref=e247]: "ON"
        - generic [ref=e248]:
          - generic [ref=e252]:
            - list [ref=e253]:
              - listitem [ref=e254]:
                - link "Temperature" [ref=e255] [cursor=pointer]:
                  - /url: ""
              - listitem [ref=e257]:
                - link "Humidity" [ref=e258] [cursor=pointer]:
                  - /url: ""
            - generic [ref=e260]:
              - generic [ref=e262]:
                - generic [ref=e281]:
                  - generic [ref=e282]: ° 24
                  - generic [ref=e283]: Celsius
                - button [ref=e284] [cursor=pointer]
              - generic [ref=e292]:
                - generic [ref=e294]:
                  - radio "" [checked] [ref=e295]
                  - generic [ref=e296]: 
                - generic [ref=e299]:
                  - radio "" [ref=e300]
                  - generic [ref=e301]: 
                - generic [ref=e304]:
                  - radio "" [ref=e305]
                  - generic [ref=e306]: 
                - generic [ref=e309]:
                  - radio "" [ref=e310]
                  - generic [ref=e311]: 
            - text: "%    "
          - generic [ref=e317]:
            - generic [ref=e318]:
              - generic [ref=e319]: Consumed
              - generic [ref=e320]: 816 kWh
            - generic [ref=e321]:
              - generic [ref=e322]: Spent
              - generic [ref=e323]: 291 USD
            - button "week" [ref=e325] [cursor=pointer]
        - generic [ref=e337]:
          - generic [ref=e340]:
            - generic [ref=e342]:
              - generic [ref=e343]: Room Management
              - img [ref=e345]:
                - generic [ref=e352]:
                  - generic [ref=e353] [cursor=pointer]
                  - generic: Kitchen
                - generic [ref=e356]:
                  - generic [ref=e357] [cursor=pointer]
                  - generic: Bedroom
                - generic [ref=e360]:
                  - generic [ref=e361] [cursor=pointer]
                  - generic: Hallway
                - generic [ref=e364]:
                  - generic [ref=e365] [cursor=pointer]
                  - generic: Living Room
            - generic [ref=e369]:
              - generic [ref=e370]: My Playlist
              - generic [ref=e371]:
                - generic [ref=e374]:
                  - heading "Harder" [level=4] [ref=e375]
                  - text: Daft Punk
                - slider [ref=e377]: "0"
                - generic [ref=e378]:
                  - generic [ref=e379]: 00:00
                  - generic [ref=e380]: "- 00:30"
                - generic [ref=e381]:
                  - button [ref=e382] [cursor=pointer]
                  - button [ref=e389] [cursor=pointer]
                  - button [ref=e396] [cursor=pointer]
                  - button [ref=e404] [cursor=pointer]
                  - button [ref=e411] [cursor=pointer]
              - generic [ref=e420]:
                - button [ref=e421] [cursor=pointer]
                - slider [ref=e430]: "100"
                - button [ref=e432] [cursor=pointer]
          - generic [ref=e444]:
            - list [ref=e445]:
              - listitem [ref=e446]:
                - link "Contacts" [ref=e447] [cursor=pointer]:
                  - /url: ""
              - listitem [ref=e449]:
                - link "Recent" [ref=e450] [cursor=pointer]:
                  - /url: ""
            - list [ref=e453]:
              - listitem [ref=e454]:
                - generic [ref=e458]:
                  - generic [ref=e459]: Nick Jones
                  - generic [ref=e460]: mobile
              - listitem [ref=e467]:
                - generic [ref=e471]:
                  - generic [ref=e472]: Eva Moor
                  - generic [ref=e473]: home
              - listitem [ref=e480]:
                - generic [ref=e484]:
                  - generic [ref=e485]: Jack Williams
                  - generic [ref=e486]: mobile
              - listitem [ref=e493]:
                - generic [ref=e497]:
                  - generic [ref=e498]: Lee Wong
                  - generic [ref=e499]: mobile
              - listitem [ref=e506]:
                - generic [ref=e510]:
                  - generic [ref=e511]: Alan Thompson
                  - generic [ref=e512]: home
              - listitem [ref=e519]:
                - generic [ref=e523]:
                  - generic [ref=e524]: Kate Martinez
                  - generic [ref=e525]: work
          - generic [ref=e532]:
            - generic [ref=e534]:
              - generic [ref=e535]: Solar Energy Consumption
              - generic [ref=e540]:
                - generic [ref=e541]: 6.421 kWh
                - generic [ref=e542]: out of 8.421 kWh
            - generic [ref=e544]:
              - generic [ref=e546]:
                - generic [ref=e547]: UI Kitten
                - generic [ref=e548]: "UI Kitten is a framework that contains a set of commonly used UI components styled in a similar way. The most awesome thing: you can change themes on the fly by just passing a different set of variables. 100% native. Give our kitten a try!"
              - generic [ref=e549]:
                - link [ref=e550] [cursor=pointer]:
                  - /url: https://akveo.github.io/react-native-ui-kitten?utm_campaign=ui_kitten%20-%20home%20-%20ngx_admin%20code%20embed&utm_source=ngx_admin&utm_medium=embedded&utm_content=iot_dashboard_kitten_card
                - link "" [ref=e557] [cursor=pointer]:
                  - /url: https://itunes.apple.com/us/app/kitten-tricks/id1246143230
                - link "" [ref=e559] [cursor=pointer]:
                  - /url: https://play.google.com/store/apps/details?id=com.akveo.kittenTricks
                - link [ref=e561] [cursor=pointer]:
                  - /url: https://github.com/akveo/react-native-ui-kitten
          - generic [ref=e567]:
            - generic [ref=e570]:
              - generic [ref=e571]: Traffic Consumption
              - button "month" [ref=e573] [cursor=pointer]
            - generic [ref=e587]:
              - generic [ref=e588]: New York
              - generic [ref=e589]: Mon 29 May
              - generic [ref=e590]: 20°
              - generic [ref=e606]:
                - generic [ref=e607]:
                  - generic [ref=e608]: max
                  - generic [ref=e609]: 23°
                - generic [ref=e610]:
                  - generic [ref=e611]: min
                  - generic [ref=e612]: 19°
                - generic [ref=e613]:
                  - generic [ref=e614]: wind
                  - generic [ref=e615]: 4 km/h
                - generic [ref=e616]:
                  - generic [ref=e617]: hum
                  - generic [ref=e618]: 87%
              - generic [ref=e619]:
                - generic [ref=e620]:
                  - generic [ref=e621]: Sun
                  - generic [ref=e622]: 
                  - generic [ref=e623]: 17°
                - generic [ref=e624]:
                  - generic [ref=e625]: Mon
                  - generic [ref=e626]: 
                  - generic [ref=e627]: 19°
                - generic [ref=e628]:
                  - generic [ref=e629]: Tue
                  - generic [ref=e630]: 
                  - generic [ref=e631]: 22°
                - generic [ref=e632]:
                  - generic [ref=e633]: Wed
                  - generic [ref=e634]: 
                  - generic [ref=e635]: 21°
          - generic [ref=e638]:
            - generic [ref=e639]:
              - text: Security Cameras
              - button "" [ref=e640] [cursor=pointer]
              - button [ref=e642] [cursor=pointer]
            - generic [ref=e653]:
              - generic [ref=e654]: "Camera #1"
              - generic [ref=e656]: "Camera #2"
              - generic [ref=e658]: "Camera #3"
              - generic [ref=e660]: "Camera #4"
            - generic [ref=e663]:
              - generic [ref=e664]: Pause
              - generic [ref=e673]: Logs
              - generic [ref=e685]: Search
              - generic [ref=e692]: Setup
      - navigation [ref=e701]:
        - generic [ref=e702]:
          - generic [ref=e703]:
            - text: Created with ♥ by
            - link "Akveo" [ref=e705] [cursor=pointer]:
              - /url: https://akveo.page.link/8V2f
            - text: "2019"
          - generic [ref=e706]:
            - link "" [ref=e707] [cursor=pointer]:
              - /url: "#"
            - link "" [ref=e708] [cursor=pointer]:
              - /url: "#"
            - link "" [ref=e709] [cursor=pointer]:
              - /url: "#"
            - link "" [ref=e710] [cursor=pointer]:
              - /url: "#"
```

# Test source

```ts
  1  | import { test, expect } from '@playwright/test'
  2  | 
  3  | test('input fields', async ({ page }, testInfo) => {
  4  | 
> 5  |   await page.goto('/')
     |              ^ TimeoutError: page.goto: Timeout 5000ms exceeded.
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