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
    19 × locator resolved to 1 element

```

# Page snapshot

```yaml
- generic [ref=f368e2]:
  - banner [ref=f368e3]:
    - generic [ref=f368e7]:
      - generic:
        - generic:
          - generic:
            - button [ref=f368e8] [cursor=pointer]
            - textbox "Search..." [ref=f368e9]
        - link "pinterest" [ref=f368e10] [cursor=pointer]:
          - /url: https://in.pinterest.com/globalsqa/
        - link "twitter" [ref=f368e11] [cursor=pointer]:
          - /url: https://twitter.com/Global_SQA
        - link "linkedin" [ref=f368e12] [cursor=pointer]:
          - /url: https://www.linkedin.com/company/globalsqa
        - link "google" [ref=f368e13] [cursor=pointer]:
          - /url: https://plus.google.com/103761557396023531439/posts
        - link "facebook" [ref=f368e14] [cursor=pointer]:
          - /url: https://facebook.com/globalsqa
        - generic [ref=f368e15]: contact@globalsqa.com
    - generic [ref=f368e19]:
      - link [ref=f368e22] [cursor=pointer]:
        - /url: https://www.globalsqa.com/
        - img "GlobalSQA" [ref=f368e23]
      - generic [ref=f368e24]:
        - list:
          - listitem [ref=f368e25]:
            - link "About" [ref=f368e26] [cursor=pointer]:
              - /url: https://www.globalsqa.com/about/
          - listitem [ref=f368e27]:
            - link "CheatSheets" [ref=f368e28] [cursor=pointer]:
              - /url: https://www.globalsqa.com/cheatsheets/
          - listitem [ref=f368e29]:
            - link "Free Ebooks" [ref=f368e30] [cursor=pointer]:
              - /url: https://www.globalsqa.com/free-ebooks/
          - listitem [ref=f368e32]:
            - link "Tester’s Hub" [ref=f368e33] [cursor=pointer]:
              - /url: https://www.globalsqa.com/testers-hub/
            - text:  
          - listitem [ref=f368e35]:
            - link "Contact Us" [ref=f368e36] [cursor=pointer]:
              - /url: https://www.globalsqa.com/contact-us/
    - text:    
  - generic [ref=f368e37]:
    - generic [ref=f368e41]:
      - generic [ref=f368e42]:
        - link "Home" [ref=f368e43] [cursor=pointer]:
          - /url: https://www.globalsqa.com/
        - link "Demo Testing Site" [ref=f368e45] [cursor=pointer]:
          - /url: https://www.globalsqa.com/demo-site/
        - link "Drag And Drop" [ref=f368e47] [cursor=pointer]:
          - /url: https://www.globalsqa.com/demo-site/draganddrop/
      - heading "Drag And Drop" [level=1] [ref=f368e50]
    - generic [ref=f368e53]:
      - generic [ref=f368e54]:
        - generic [ref=f368e55]:
          - heading "Interaction" [level=4] [ref=f368e56]
          - list [ref=f368e58]:
            - listitem [ref=f368e59]:
              - link "Sortable" [ref=f368e60] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/sorting/
            - listitem [ref=f368e62]:
              - link "Drag And Drop" [ref=f368e63] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/draganddrop/
            - listitem [ref=f368e65]:
              - link "Select Elements" [ref=f368e66] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/select-elements/
            - listitem [ref=f368e68]:
              - link "Draggable Boxes" [ref=f368e69] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/draggableboxes/
            - listitem [ref=f368e71]:
              - link "DropDown Menu" [ref=f368e72] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/select-dropdown-menu/
        - generic [ref=f368e74]:
          - heading "Widgets" [level=4] [ref=f368e75]
          - list [ref=f368e77]:
            - listitem [ref=f368e78]:
              - link "Tooltip" [ref=f368e79] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/tooltip/
            - listitem [ref=f368e81]:
              - link "Sliders" [ref=f368e82] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/sliders/
            - listitem [ref=f368e84]:
              - link "Spinner" [ref=f368e85] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/spinner/
            - listitem [ref=f368e87]:
              - link "DatePicker" [ref=f368e88] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/datepicker/
            - listitem [ref=f368e90]:
              - link "Progress Bar" [ref=f368e91] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/progress-bar/
            - listitem [ref=f368e93]:
              - link "Dialog Boxes" [ref=f368e94] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/dialog-boxes/
            - listitem [ref=f368e96]:
              - link "Auto Complete" [ref=f368e97] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/auto-complete/
            - listitem [ref=f368e99]:
              - link "Accordion And Tabs" [ref=f368e100] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/accordion-and-tabs/
        - iframe [ref=f368e103]:
          
        - iframe [ref=f368e105]:
          
        - generic [ref=f368e108]:
          - heading "These are topics related to the article that might interest you" [level=2] [ref=f368e110]: Discover more
          - link "User Interface Design" [ref=f368e111] [cursor=pointer]
          - link "Progress Bar Widgets" [ref=f368e116] [cursor=pointer]
          - link "Contact Management CRM" [ref=f368e121] [cursor=pointer]
          - link "Testing Site Access" [ref=f368e126] [cursor=pointer]
          - link "Sortable Element Demo" [ref=f368e131] [cursor=pointer]
          - link "Programming" [ref=f368e136] [cursor=pointer]
          - link "Social Media Marketing" [ref=f368e141] [cursor=pointer]
          - link "Computers & Electronics" [ref=f368e146] [cursor=pointer]
      - generic [ref=f368e152]:
        - list [ref=f368e153]:
          - tab "Photo Manager" [ref=f368e154] [cursor=pointer]
          - tab "Accepted Elements" [ref=f368e155] [cursor=pointer]
          - tab "Propagation" [ref=f368e156] [cursor=pointer]
        - paragraph [ref=f368e159]:
          - iframe [ref=f368e160]:
            - generic [ref=f369e1]:
              - generic [ref=f369e2]:
                - list [ref=f369e3]:
                  - listitem [ref=f369e4]:
                    - heading "High Tatras" [level=5] [ref=f369e5]
                    - img "The peaks of High Tatras" [ref=f369e6]
                    - link "View larger" [ref=f369e7] [cursor=pointer]:
                      - /url: images/high_tatras.jpg
                    - link "Delete image" [ref=f369e8] [cursor=pointer]:
                      - /url: link/to/trash/script/when/we/have/js/off
                  - listitem [ref=f369e9]:
                    - heading "High Tatras 3" [level=5] [ref=f369e10]
                    - img "Planning the ascent" [ref=f369e11]
                    - link "View larger" [ref=f369e12] [cursor=pointer]:
                      - /url: images/high_tatras3.jpg
                    - link "Delete image" [ref=f369e13] [cursor=pointer]:
                      - /url: link/to/trash/script/when/we/have/js/off
                  - listitem [ref=f369e14]:
                    - heading "High Tatras 4" [level=5] [ref=f369e15]
                    - img "On top of Kozi kopka" [ref=f369e16]
                    - link "View larger" [ref=f369e17] [cursor=pointer]:
                      - /url: images/high_tatras4.jpg
                    - link "Delete image" [ref=f369e18] [cursor=pointer]:
                      - /url: link/to/trash/script/when/we/have/js/off
                - generic [ref=f369e19]:
                  - heading "Trash Trash" [level=4] [ref=f369e20]:
                    - generic [ref=f369e21]: Trash
                    - text: Trash
                  - list:
                    - listitem [ref=f369e22]:
                      - img "The chalet at the Green mountain lake" [ref=f369e23]
                      - link "View larger" [ref=f369e24] [cursor=pointer]:
                        - /url: images/high_tatras2.jpg
                      - link "Recycle image" [ref=f369e25] [cursor=pointer]:
                        - /url: link/to/recycle/script/when/we/have/js/off
              - generic [ref=f369e26]:
                - paragraph [ref=f369e27]: You can delete an image either by dragging it to the Trash or by clicking the trash icon.
                - paragraph [ref=f369e28]: You can "recycle" an image by dragging it back to the gallery or by clicking the recycle icon.
                - paragraph [ref=f369e29]: You can view larger image by clicking the zoom icon. Selenium Practice dialog widget is used for the modal window.
          - insertion [ref=f368e161]
  - generic:
    - insertion:
      - iframe [ref=f368e163]:
        
  - generic [ref=f368e164]:
    - generic [ref=f368e166]:
      - generic [ref=f368e167]:
        - heading "Footer Widget Area 1" [level=3] [ref=f368e168]
        - paragraph [ref=f368e169]:
          - link "Assign a widget to this area now." [ref=f368e170] [cursor=pointer]:
            - /url: https://www.globalsqa.com/wp-admin/widgets.php
      - generic [ref=f368e171]:
        - heading "Footer Widget Area 2" [level=3] [ref=f368e172]
        - paragraph [ref=f368e173]:
          - link "Assign a widget to this area now." [ref=f368e174] [cursor=pointer]:
            - /url: https://www.globalsqa.com/wp-admin/widgets.php
      - generic [ref=f368e175]:
        - heading "Footer Widget Area 3" [level=3] [ref=f368e176]
        - paragraph [ref=f368e177]:
          - link "Assign a widget to this area now." [ref=f368e178] [cursor=pointer]:
            - /url: https://www.globalsqa.com/wp-admin/widgets.php
      - generic [ref=f368e179]:
        - heading "Footer Widget Area 4" [level=3] [ref=f368e180]
        - paragraph [ref=f368e181]:
          - link "Assign a widget to this area now." [ref=f368e182] [cursor=pointer]:
            - /url: https://www.globalsqa.com/wp-admin/widgets.php
    - generic [ref=f368e187]:
      - link "pinterest" [ref=f368e188] [cursor=pointer]:
        - /url: https://in.pinterest.com/globalsqa/
      - link "twitter" [ref=f368e189] [cursor=pointer]:
        - /url: https://twitter.com/Global_SQA
      - link "linkedin" [ref=f368e190] [cursor=pointer]:
        - /url: https://www.linkedin.com/company/globalsqa
      - link "google" [ref=f368e191] [cursor=pointer]:
        - /url: https://plus.google.com/103761557396023531439/posts
      - link "facebook" [ref=f368e192] [cursor=pointer]:
        - /url: https://facebook.com/globalsqa
      - generic [ref=f368e193]:
        - text: "Website Designed & Developed by :"
        - link "GlobalSQA" [ref=f368e194] [cursor=pointer]:
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