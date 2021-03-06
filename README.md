# Tax Receipt

A means of visualizing the major Federal programs to which your tax dollars were allocated, written in D3.js.

<h1 align="center">
    <img src="https://github.com/supermanzer/tax_receipt/blob/master/static/images/tax_receipt_screenshot.png" width="220">
</h1>

## Motivation
This project is intended to allow tax payers a means to view the amount of their tax dollars allocated to specific Federal programs.  Ultimately I would like users to be able to drill down from general categories to specific programs *and* see the language in specific appropriation bills that are responsible for allocating those funds.

## Tech
#### D3.js
I am using D3 v4 for this visualization.  While it's not the most up to date, it does have a greater wealth of tutorials than the current version.


## Contributing
#### D3:
I am still a painful novice at using D3 and as such, any help building out the basic functionality would be very much appreciated.
#### Data:
I have used dummy data to build this out and I am not yet certain how to gather the actual data to fulfill the functionality I am looking for.  Anyone seeking to contribute to this project who can assist with gathering federal spending data, linking larger categories of spending to individual programs, or attributing spending to appropriation bills would be very much welcome.

# Next Steps

 - Data : Find a reliable source of federal spending data that traces funds through major categories to individual programs.
 - Graph: Work on zoom in animation to make it more smooth and color schemes to convery information more meaningfully.
 - Mobile Friendly:  Develop sizing functions for graph and table to allow for a more mobile friendly graph.
 - Budget Legend: BUild out a tree like legend that shows users the level they are drilled down to.  Each legend entry would trigger zooming to that level.
