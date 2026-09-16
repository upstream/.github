## What this PR does

* Description; why this is needed; context for anyone reading this in 6 months or years

fix #{{issue-no}}

## How to QA this

* setup (data, feature switches):
* what to test/look for
* edge cases:
* check for custom color issues in the member/public section:
  * [switch on old custom colors](https://backend.cobot.localhost:3000/features/disable_customize_member_portal_and_homepage)
  * As admin, go to Customize » set weird inverted colors, all 4 colors
  * test the UI as member/visitor
* scan each page for a11y issues in [axe dev tools](https://www.deque.com/axe/devtools/)

## Screenshots
