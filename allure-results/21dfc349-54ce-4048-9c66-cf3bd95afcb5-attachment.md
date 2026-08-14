# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: tests/dragAndDropWithinFrame.spec.ts >> drag and drop with iframe
- Location: tests/dragAndDropWithinFrame.spec.ts:4:5

# Error details

```
Error: expect(locator).toHaveText(expected) failed

Locator: locator('[rel-title="Photo Manager"] iframe').contentFrame().locator('#trash li h5')
Timeout: 2000ms
- Expected  - 1
+ Received  + 0

  Array [
    "High Tatras 2",
-   "High Tatras 4",
  ]

Call log:
  - Expect "toHaveText" with timeout 2000ms
  - waiting for locator('[rel-title="Photo Manager"] iframe').contentFrame().locator('#trash li h5')
    11 × locator resolved to 1 element

```

# Page snapshot

```yaml
- generic [ref=f258e2]:
  - banner [ref=f258e3]:
    - generic [ref=f258e7]:
      - generic:
        - generic:
          - generic:
            - button [ref=f258e8] [cursor=pointer]
            - textbox "Search..." [ref=f258e9]
        - link "pinterest" [ref=f258e10] [cursor=pointer]:
          - /url: https://in.pinterest.com/globalsqa/
        - link "twitter" [ref=f258e11] [cursor=pointer]:
          - /url: https://twitter.com/Global_SQA
        - link "linkedin" [ref=f258e12] [cursor=pointer]:
          - /url: https://www.linkedin.com/company/globalsqa
        - link "google" [ref=f258e13] [cursor=pointer]:
          - /url: https://plus.google.com/103761557396023531439/posts
        - link "facebook" [ref=f258e14] [cursor=pointer]:
          - /url: https://facebook.com/globalsqa
        - generic [ref=f258e15]: contact@globalsqa.com
    - generic [ref=f258e19]:
      - link [ref=f258e22] [cursor=pointer]:
        - /url: https://www.globalsqa.com/
        - img "GlobalSQA" [ref=f258e23]
      - generic [ref=f258e24]:
        - list:
          - listitem [ref=f258e25]:
            - link "About" [ref=f258e26] [cursor=pointer]:
              - /url: https://www.globalsqa.com/about/
          - listitem [ref=f258e27]:
            - link "CheatSheets" [ref=f258e28] [cursor=pointer]:
              - /url: https://www.globalsqa.com/cheatsheets/
          - listitem [ref=f258e29]:
            - link "Free Ebooks" [ref=f258e30] [cursor=pointer]:
              - /url: https://www.globalsqa.com/free-ebooks/
          - listitem [ref=f258e32]:
            - link "Tester’s Hub" [ref=f258e33] [cursor=pointer]:
              - /url: https://www.globalsqa.com/testers-hub/
            - text:  
          - listitem [ref=f258e35]:
            - link "Contact Us" [ref=f258e36] [cursor=pointer]:
              - /url: https://www.globalsqa.com/contact-us/
    - text:    
  - generic [ref=f258e37]:
    - generic [ref=f258e41]:
      - generic [ref=f258e42]:
        - link "Home" [ref=f258e43] [cursor=pointer]:
          - /url: https://www.globalsqa.com/
        - link "Demo Testing Site" [ref=f258e45] [cursor=pointer]:
          - /url: https://www.globalsqa.com/demo-site/
        - link "Drag And Drop" [ref=f258e47] [cursor=pointer]:
          - /url: https://www.globalsqa.com/demo-site/draganddrop/
      - heading "Drag And Drop" [level=1] [ref=f258e50]
    - generic [ref=f258e53]:
      - generic [ref=f258e54]:
        - generic [ref=f258e55]:
          - heading "Interaction" [level=4] [ref=f258e56]
          - list [ref=f258e58]:
            - listitem [ref=f258e59]:
              - link "Sortable" [ref=f258e60] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/sorting/
            - listitem [ref=f258e62]:
              - link "Drag And Drop" [ref=f258e63] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/draganddrop/
            - listitem [ref=f258e65]:
              - link "Select Elements" [ref=f258e66] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/select-elements/
            - listitem [ref=f258e68]:
              - link "Draggable Boxes" [ref=f258e69] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/draggableboxes/
            - listitem [ref=f258e71]:
              - link "DropDown Menu" [ref=f258e72] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/select-dropdown-menu/
        - generic [ref=f258e74]:
          - heading "Widgets" [level=4] [ref=f258e75]
          - list [ref=f258e77]:
            - listitem [ref=f258e78]:
              - link "Tooltip" [ref=f258e79] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/tooltip/
            - listitem [ref=f258e81]:
              - link "Sliders" [ref=f258e82] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/sliders/
            - listitem [ref=f258e84]:
              - link "Spinner" [ref=f258e85] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/spinner/
            - listitem [ref=f258e87]:
              - link "DatePicker" [ref=f258e88] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/datepicker/
            - listitem [ref=f258e90]:
              - link "Progress Bar" [ref=f258e91] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/progress-bar/
            - listitem [ref=f258e93]:
              - link "Dialog Boxes" [ref=f258e94] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/dialog-boxes/
            - listitem [ref=f258e96]:
              - link "Auto Complete" [ref=f258e97] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/auto-complete/
            - listitem [ref=f258e99]:
              - link "Accordion And Tabs" [ref=f258e100] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/accordion-and-tabs/
        - iframe [ref=f258e103]:
          
        - generic [ref=f258e106]:
          - heading "These are topics related to the article that might interest you" [level=2] [ref=f258e108]: Discover more
          - link "Dropdown Menu Testing" [ref=f258e109] [cursor=pointer]
          - link "Social Media Marketing" [ref=f258e114] [cursor=pointer]
          - link "QA Cheat Sheets" [ref=f258e119] [cursor=pointer]
          - link "Tooltip Widget Demo" [ref=f258e124] [cursor=pointer]
          - link "Calendar & Scheduling Software" [ref=f258e129] [cursor=pointer]
          - link "Spreadsheet Software" [ref=f258e134] [cursor=pointer]
          - link "Contact Management CRM" [ref=f258e139] [cursor=pointer]
          - link "Website Development Services" [ref=f258e144] [cursor=pointer]
        - iframe [ref=f258e150]:
          
      - generic [ref=f258e152]:
        - list [ref=f258e153]:
          - tab "Photo Manager" [ref=f258e154] [cursor=pointer]
          - tab "Accepted Elements" [ref=f258e155] [cursor=pointer]
          - tab "Propagation" [ref=f258e156] [cursor=pointer]
        - paragraph [ref=f258e159]:
          - iframe [ref=f258e160]:
            - generic [ref=f259e1]:
              - generic [ref=f259e2]:
                - list [ref=f259e3]:
                  - listitem [ref=f259e4]:
                    - heading "High Tatras" [level=5] [ref=f259e5]
                    - img "The peaks of High Tatras" [ref=f259e6]
                    - link "View larger" [ref=f259e7] [cursor=pointer]:
                      - /url: images/high_tatras.jpg
                    - link "Delete image" [ref=f259e8] [cursor=pointer]:
                      - /url: link/to/trash/script/when/we/have/js/off
                  - listitem [ref=f259e9]:
                    - heading "High Tatras 3" [level=5] [ref=f259e10]
                    - img "Planning the ascent" [ref=f259e11]
                    - link "View larger" [ref=f259e12] [cursor=pointer]:
                      - /url: images/high_tatras3.jpg
                    - link "Delete image" [ref=f259e13] [cursor=pointer]:
                      - /url: link/to/trash/script/when/we/have/js/off
                  - listitem [ref=f259e14]:
                    - heading "High Tatras 4" [level=5] [ref=f259e15]
                    - img "On top of Kozi kopka" [ref=f259e16]
                    - link "View larger" [ref=f259e17] [cursor=pointer]:
                      - /url: images/high_tatras4.jpg
                    - link "Delete image" [ref=f259e18] [cursor=pointer]:
                      - /url: link/to/trash/script/when/we/have/js/off
                - generic [ref=f259e19]:
                  - heading "Trash Trash" [level=4] [ref=f259e20]:
                    - generic [ref=f259e21]: Trash
                    - text: Trash
                  - list:
                    - listitem [ref=f259e22]:
                      - img "The chalet at the Green mountain lake" [ref=f259e23]
                      - link "View larger" [ref=f259e24] [cursor=pointer]:
                        - /url: images/high_tatras2.jpg
                      - link "Recycle image" [ref=f259e25] [cursor=pointer]:
                        - /url: link/to/recycle/script/when/we/have/js/off
              - generic [ref=f259e26]:
                - paragraph [ref=f259e27]: You can delete an image either by dragging it to the Trash or by clicking the trash icon.
                - paragraph [ref=f259e28]: You can "recycle" an image by dragging it back to the gallery or by clicking the recycle icon.
                - paragraph [ref=f259e29]: You can view larger image by clicking the zoom icon. Selenium Practice dialog widget is used for the modal window.
          - insertion [ref=f258e161]
  - generic:
    - insertion:
      - iframe [ref=f258e163]:
        
  - generic [ref=f258e164]:
    - generic [ref=f258e166]:
      - generic [ref=f258e167]:
        - heading "Footer Widget Area 1" [level=3] [ref=f258e168]
        - paragraph [ref=f258e169]:
          - link "Assign a widget to this area now." [ref=f258e170] [cursor=pointer]:
            - /url: https://www.globalsqa.com/wp-admin/widgets.php
      - generic [ref=f258e171]:
        - heading "Footer Widget Area 2" [level=3] [ref=f258e172]
        - paragraph [ref=f258e173]:
          - link "Assign a widget to this area now." [ref=f258e174] [cursor=pointer]:
            - /url: https://www.globalsqa.com/wp-admin/widgets.php
      - generic [ref=f258e175]:
        - heading "Footer Widget Area 3" [level=3] [ref=f258e176]
        - paragraph [ref=f258e177]:
          - link "Assign a widget to this area now." [ref=f258e178] [cursor=pointer]:
            - /url: https://www.globalsqa.com/wp-admin/widgets.php
      - generic [ref=f258e179]:
        - heading "Footer Widget Area 4" [level=3] [ref=f258e180]
        - paragraph [ref=f258e181]:
          - link "Assign a widget to this area now." [ref=f258e182] [cursor=pointer]:
            - /url: https://www.globalsqa.com/wp-admin/widgets.php
    - generic [ref=f258e187]:
      - link "pinterest" [ref=f258e188] [cursor=pointer]:
        - /url: https://in.pinterest.com/globalsqa/
      - link "twitter" [ref=f258e189] [cursor=pointer]:
        - /url: https://twitter.com/Global_SQA
      - link "linkedin" [ref=f258e190] [cursor=pointer]:
        - /url: https://www.linkedin.com/company/globalsqa
      - link "google" [ref=f258e191] [cursor=pointer]:
        - /url: https://plus.google.com/103761557396023531439/posts
      - link "facebook" [ref=f258e192] [cursor=pointer]:
        - /url: https://facebook.com/globalsqa
      - generic [ref=f258e193]:
        - text: "Website Designed & Developed by :"
        - link "GlobalSQA" [ref=f258e194] [cursor=pointer]:
          - /url: https://www.globalsqa.com
```

# Test source

```ts
  1  | import {expect} from '@playwright/test'
  2  | import {test} from '../test-options'
  3  | 
  4  | test('drag and drop with iframe', async({page, globalsQaURL}) => {
  5  |     await page.goto(globalsQaURL, {
  6  |     waitUntil: 'domcontentloaded'
  7  |     })
  8  | 
  9  |     const frame = page.frameLocator('[rel-title="Photo Manager"] iframe')
  10 |     await frame.locator('li', {hasText:"High Tatras 2"}).dragTo(frame.locator('#trash'))
  11 | 
  12 |     //more presice control
  13 |     await frame.locator('li', {hasText:"High Tatras 4"}).hover()
  14 |     await page.mouse.down()
  15 |     await frame.locator('#trash').hover()
  16 |     await page.mouse.up()
  17 | 
> 18 |     await expect(frame.locator('#trash li h5')).toHaveText(["High Tatras 2", "High Tatras 4"])
     |                                                 ^ Error: expect(locator).toHaveText(expected) failed
  19 | })
```