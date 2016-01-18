#iOS Programming: The Big Nerd Ranch Guide
##Errata for 5th Edition, First Printing

###Chapter 2:  The Swift Language
* **p.37** (Loops and String Interpolation) — There should not be a space after the half-open, or exclusive, range operator. It should be `0..<countingUp` instead of `0..< countingUp`.

###Chapter 11:  Subclassing UITableViewCell
* **p.178** (Exposing the Properties of ItemCell) — In the last paragraph, it should be `ItemCell` instead of `ItemViewCell`.

###Chapter 13: UINavigationController
* **p.214** (Dismissing by tapping elsewhere) — The signature for `backgroundTapped(_:)` should be `@IBAction func backgroundTapped(sender: UITapGestureRecognizer)` instead of `@IBAction func backgroundTapped(sender: AnyObject)`. If you followed the directions in the book, the code that Xcode generated will match this.

