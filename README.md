# renovate-node-grouping

It would be helpful if we could limit Node.js updates to the latest LTS version (currently v18). The problem is that when the currently installed major node version is lower than the current LTS (e.g. v16 in this example), we will not get an MR to update the major version to the LTS version but rather the newest major version (currently v19).
