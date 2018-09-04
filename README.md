# py_res_change
<pre>
Ever had issues when running code for automated tasks, resembling mouse clicks and keyboard strokes when running on different machines
with different resolutions (thus your x & y coordinates will be different on each machine)? 
With this Python library, you can change your resolution before you start your tests, so each test will run exactly the same.
At the end of your test, you can revert back to the normal resolution.

How to use:

from resolution_changer import revert_resolution, change_resolution


width = 800
height = 600

print change_resolution(width, height)

print revert_resolution()

</pre>
