# SwiftAgo
Time-Ago for Swift. Format NSDate's in Swift to the format "x minutes ago" and all other combinations.
Similar to that the way GitHub puts a timestamp on your commits. "just now", "3 minutes ago", "an hour ago", "2 days ago", "last week", etc.

This is an extension of NSDate, which means any types declared as NSDate automatically gain this functionality by accessing the "ago" variable. This retrieves a 'time since' date, the date relative to now, nicely formatted into a string end users will understand.

##Example Use:
<pre>
var now = NSDate()

println( now.ago )  //--> just now
</pre>


This can be used in Applications that require a user friendly time stamp.
<pre>
println("submitted by Jesse Ziegler \(date.ago).") 
//--> submitted by Jesse Ziegler 5 minutes ago.
</pre>



Inspired by NSDate-TimeAgo for Objective C.
