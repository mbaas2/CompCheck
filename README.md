# CompCheck

A compatibility-checker for [Dyalog APL](http://dyalog.com).

Helps to find out if Dyalog-code will run under a certain (older) version (12.1 or later) and/or in a Classic interpreter.

## Usage

* Clone the repository (or download to a folder of your choice)

* ]link.create /git/CompCheck #.CompCheck  ⍝  adjust names as you like 

* `15 #.CompCheck.Run #.foo`

  test function (or ns) foo for compatibility with version ≥ v15

* `1 #.CompCheck '/git/goo/hoo.dyalog`

  test file `hoo.dyalog` for compatibility with Classic interpreter

* `14.1 1 #.CompCheck '/git/goo/hoo.dyalog`

  test file `hoo.dyalog` for compatibility with Classic interpreter and versions ≥14.1

## Contributing

You are invited to contribute to this repository through Pull-requests or by creating Issues.
