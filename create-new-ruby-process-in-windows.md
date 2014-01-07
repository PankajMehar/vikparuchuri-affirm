Title: Create a New Ruby Process in Windows
Date: 2012-01-10 18:20
Slug: create-new-ruby-process-in-windows
Modified: 2014-01-07 18:47
Status: published
Category: 
Tags: Ruby, windows, parallel


<div class='post'>
I recently had a problem whereby I needed one Ruby program to spawn another Ruby program, but I did not need or want the two programs to interact after the second program was instantiated. I solved this issue by using the system function in Ruby and the Windows start command.<br> <pre class="ruby">system('start ruby.exe C:\script.rb')</pre> This will create a new Ruby window, which will run the specified script, and close when it is complete.</div>