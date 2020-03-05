# Cobiro QA Test

## Structure

- Created folder page-objects
- Page-object folder conteins two files
- app.po.ts file contains description of elements of main page and details page
- navigation-page.po.ts contains description of elements of navigation block and header
- in specs folder there are two files
- app.spec.ts contains tests wich is covered Acceptance criteria
- navigation-page.spec.ts contains bonus points tests


## Acceptance criteria

First Acceptance criteria (On the main page I should see a tree structure of items) was not meet. The stucture is looks like Tree but it is not Tree. Tree structure shpuld have a root node.
test  'check tree structure' is failed because there is no child element for element with css '[class=""]'

Last Acceptance criteria (All items will have a call to action that links to a page containing information on the item)  is meet partially. You can look at test 'navigate to details page' there are several comments on rows 54 and 60, 83, 83, 85.


