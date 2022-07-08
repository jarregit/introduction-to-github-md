# Markdown for beginners
## Heading
### towards
#### smaller
##### headings
###### end here

![twenty-percent-cooler-octocat for fast magick](https://octodex.github.com/images/twenty-percent-cooler-octocat.png)

Add some code
```powershell
# Start-up
Add-type -AssemblyName office
add-type -assembly microsoft.office.interop.powerpoint

$Application = New-Object -ComObject powerpoint.application
$application.visible = [Microsoft.Office.Core.MsoTriState]::msoTrue

$slideType = "microsoft.office.interop.powerpoint.ppSlideLayout" -as [type]
$slideAnim = "microsoft.office.interop.powerpoint.SlideShowTransition" -as [type]

$blanklayout = $slideType::ppLayoutTitleOnly
$ppEffectBlindsVertical = "microsoft.office.interop.powerpoint.SlideShowTransition.EntryEffect.ppEffectBlindsVertical" -as [type]
```

Adding a task-list 
- [x] Add Headers
- [x] Add an Image
- [x] Add a code example
- [ ] Make a task list
- [ ] Merge your pull request
- [ ] Continue your journey

