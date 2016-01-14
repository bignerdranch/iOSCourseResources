#iOS Programming: The Big Nerd Ranch Guide
##5th Edition, First Printing
##Errata

###Chapter 1:  A Simple iOS Application
* None

###Chapter 2:  The Swift Language
* **p.37** — There should not be a space after the half-open, or exclusive, range operator. It should be `0..<countingUp` instead of `0..< countingUp`

###Chapter 13: UINavigationController
* **p.214** The signature for `backgroundTapped(_:)` should be `@IBAction func backgroundTapped(sender: UITapGestureRecognizer)` instead of `@IBAction func backgroundTapped(sender: AnyObject)`. If you followed the directions in the book, the code that Xcode generated will match this.

