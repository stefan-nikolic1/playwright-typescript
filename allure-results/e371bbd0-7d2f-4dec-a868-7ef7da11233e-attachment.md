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
  8  |     await frame.locator('li', { hasText: "High Tatras 4" }).dragTo(frame.locator('#trash'))
  9  | 
  10 |     await expect(frame.locator('#trash li h5')).toHaveText(["High Tatras 2", "High Tatras 4"])
  11 | })
```