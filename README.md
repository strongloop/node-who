# nodewho

Who contributes to Node.js?

## Getting Started

Get the code: `git clone git@github.com:strongloop/node-who.git`

Work from the code directory: `cd node-who`

Grab the code for local analysis: `bin/nodewho-getcode`

## Use The Analyzer

See who contributed to the current codebase: `bin/nodewho-current`  
_Note: this can take a while_

If some time has passed since your last analysis, update the code before running `nodewho-current`: `bin/nodewho-getcode`

## Bonus: Calculate Percentages

Enter the results of `bin/nodewho-current` into `etc/Node-Current.xlsx` to see the percentage contributions from top contributors.

## Caveats

Due to how different tools work with different file types in the source base, the contribution line counts may not add up to the total line count for the source base. If you have ideas on how to improve that, feel free to fork and send us a pull request.

## License
Copyright (c) 2013 StrongLoop, Inc.
Licensed under the MIT license.
