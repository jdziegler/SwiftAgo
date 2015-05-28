# SwiftAgo
Format NSDate's in Swift to the format "x minutes ago" and all other combinations.

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
