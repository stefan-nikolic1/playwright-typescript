# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: tests/dragAndDropWithinFrame.spec.ts >> drag and drop with iframe
- Location: tests/dragAndDropWithinFrame.spec.ts:4:5

# Error details

```
TimeoutError: page.goto: Timeout 5000ms exceeded.
Call log:
  - navigating to "https://www.globalsqa.com/demo-site/draganddrop/", waiting until "load"

```

# Page snapshot

```yaml
- generic [ref=e2]:
  - banner [ref=e3]:
    - generic [ref=e7]:
      - generic:
        - generic:
          - generic:
            - button [ref=e8] [cursor=pointer]
            - textbox "Search..." [ref=e9]
        - link "pinterest" [ref=e10] [cursor=pointer]:
          - /url: https://in.pinterest.com/globalsqa/
        - link "twitter" [ref=e11] [cursor=pointer]:
          - /url: https://twitter.com/Global_SQA
        - link "linkedin" [ref=e12] [cursor=pointer]:
          - /url: https://www.linkedin.com/company/globalsqa
        - link "google" [ref=e13] [cursor=pointer]:
          - /url: https://plus.google.com/103761557396023531439/posts
        - link "facebook" [ref=e14] [cursor=pointer]:
          - /url: https://facebook.com/globalsqa
        - generic [ref=e15]: contact@globalsqa.com
    - generic [ref=e19]:
      - link [ref=e22] [cursor=pointer]:
        - /url: https://www.globalsqa.com/
        - img "GlobalSQA" [ref=e23]
      - generic [ref=e24]:
        - list:
          - listitem [ref=e25]:
            - link "About" [ref=e26] [cursor=pointer]:
              - /url: https://www.globalsqa.com/about/
          - listitem [ref=e27]:
            - link "CheatSheets" [ref=e28] [cursor=pointer]:
              - /url: https://www.globalsqa.com/cheatsheets/
          - listitem [ref=e29]:
            - link "Free Ebooks" [ref=e30] [cursor=pointer]:
              - /url: https://www.globalsqa.com/free-ebooks/
          - listitem [ref=e32]:
            - link "Tester’s Hub" [ref=e33] [cursor=pointer]:
              - /url: https://www.globalsqa.com/testers-hub/
            - text:  
          - listitem [ref=e35]:
            - link "Contact Us" [ref=e36] [cursor=pointer]:
              - /url: https://www.globalsqa.com/contact-us/
    - text:    
  - generic [ref=e37]:
    - generic [ref=e41]:
      - generic [ref=e42]:
        - link "Home" [ref=e43] [cursor=pointer]:
          - /url: https://www.globalsqa.com/
        - link "Demo Testing Site" [ref=e45] [cursor=pointer]:
          - /url: https://www.globalsqa.com/demo-site/
        - link "Drag And Drop" [ref=e47] [cursor=pointer]:
          - /url: https://www.globalsqa.com/demo-site/draganddrop/
      - heading "Drag And Drop" [level=1] [ref=e50]
    - generic [ref=e53]:
      - generic [ref=e54]:
        - generic [ref=e55]:
          - heading "Interaction" [level=4] [ref=e56]
          - list [ref=e58]:
            - listitem [ref=e59]:
              - link "Sortable" [ref=e60] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/sorting/
            - listitem [ref=e62]:
              - link "Drag And Drop" [ref=e63] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/draganddrop/
            - listitem [ref=e65]:
              - link "Select Elements" [ref=e66] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/select-elements/
            - listitem [ref=e68]:
              - link "Draggable Boxes" [ref=e69] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/draggableboxes/
            - listitem [ref=e71]:
              - link "DropDown Menu" [ref=e72] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/select-dropdown-menu/
        - generic [ref=e74]:
          - heading "Widgets" [level=4] [ref=e75]
          - list [ref=e77]:
            - listitem [ref=e78]:
              - link "Tooltip" [ref=e79] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/tooltip/
            - listitem [ref=e81]:
              - link "Sliders" [ref=e82] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/sliders/
            - listitem [ref=e84]:
              - link "Spinner" [ref=e85] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/spinner/
            - listitem [ref=e87]:
              - link "DatePicker" [ref=e88] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/datepicker/
            - listitem [ref=e90]:
              - link "Progress Bar" [ref=e91] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/progress-bar/
            - listitem [ref=e93]:
              - link "Dialog Boxes" [ref=e94] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/dialog-boxes/
            - listitem [ref=e96]:
              - link "Auto Complete" [ref=e97] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/auto-complete/
            - listitem [ref=e99]:
              - link "Accordion And Tabs" [ref=e100] [cursor=pointer]:
                - /url: https://www.globalsqa.com/demo-site/accordion-and-tabs/
        - generic [ref=e104]:
          - heading "These are topics related to the article that might interest you" [level=2] [ref=e106]: Discover more
          - link "Hiking & Camping" [ref=e107] [cursor=pointer]
          - link "User Interface Design" [ref=e112] [cursor=pointer]
          - link "Drag Drop Tools" [ref=e117] [cursor=pointer]
          - link "QA Cheat Sheets" [ref=e122] [cursor=pointer]
          - link "Testing Site Access" [ref=e127] [cursor=pointer]
          - link "Toolbar Widget Testing" [ref=e132] [cursor=pointer]
          - link "Draggable Box Testing" [ref=e137] [cursor=pointer]
          - link "Demo Site Hosting" [ref=e142] [cursor=pointer]
        - iframe [ref=e148]:
          
      - generic [ref=e150]:
        - list [ref=e151]:
          - tab "Photo Manager" [ref=e152] [cursor=pointer]
          - tab "Accepted Elements" [ref=e153] [cursor=pointer]
          - tab "Propagation" [ref=e154] [cursor=pointer]
        - paragraph [ref=e157]:
          - iframe [ref=e158]:
            
          - insertion [ref=e159]
  - generic [ref=e160]:
    - generic [ref=e162]:
      - generic [ref=e163]:
        - heading "Footer Widget Area 1" [level=3] [ref=e164]
        - paragraph [ref=e165]:
          - link "Assign a widget to this area now." [ref=e166] [cursor=pointer]:
            - /url: https://www.globalsqa.com/wp-admin/widgets.php
      - generic [ref=e167]:
        - heading "Footer Widget Area 2" [level=3] [ref=e168]
        - paragraph [ref=e169]:
          - link "Assign a widget to this area now." [ref=e170] [cursor=pointer]:
            - /url: https://www.globalsqa.com/wp-admin/widgets.php
      - generic [ref=e171]:
        - heading "Footer Widget Area 3" [level=3] [ref=e172]
        - paragraph [ref=e173]:
          - link "Assign a widget to this area now." [ref=e174] [cursor=pointer]:
            - /url: https://www.globalsqa.com/wp-admin/widgets.php
      - generic [ref=e175]:
        - heading "Footer Widget Area 4" [level=3] [ref=e176]
        - paragraph [ref=e177]:
          - link "Assign a widget to this area now." [ref=e178] [cursor=pointer]:
            - /url: https://www.globalsqa.com/wp-admin/widgets.php
    - generic [ref=e183]:
      - link "pinterest" [ref=e184] [cursor=pointer]:
        - /url: https://in.pinterest.com/globalsqa/
      - link "twitter" [ref=e185] [cursor=pointer]:
        - /url: https://twitter.com/Global_SQA
      - link "linkedin" [ref=e186] [cursor=pointer]:
        - /url: https://www.linkedin.com/company/globalsqa
      - link "google" [ref=e187] [cursor=pointer]:
        - /url: https://plus.google.com/103761557396023531439/posts
      - link "facebook" [ref=e188] [cursor=pointer]:
        - /url: https://facebook.com/globalsqa
      - generic [ref=e189]:
        - text: "Website Designed & Developed by :"
        - link "GlobalSQA" [ref=e190] [cursor=pointer]:
          - /url: https://www.globalsqa.com
```

# Test source

```ts
  1  | import {expect} from '@playwright/test'
  2  | import {test} from '../test-options'
  3  | 
  4  | test('drag and drop with iframe', async ({ page, globalsQaURL }) => {
> 5  |     await page.goto(globalsQaURL)
     |                ^ TimeoutError: page.goto: Timeout 5000ms exceeded.
  6  |     const frame = page.frameLocator('[rel-title="Photo Manager"] iframe')
  7  |     
  8  |     await frame.locator('li', { hasText: "High Tatras 2" }).dragTo(frame.locator('#trash'))
  9  |     await frame.locator('li', { hasText: "High Tatras 4" }).dragTo(frame.locator('#trash'))
  10 | 
  11 |     await expect(frame.locator('#trash li h5')).toHaveText(["High Tatras 2", "High Tatras 4"])
  12 | })
```