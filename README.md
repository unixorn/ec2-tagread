# ec2-tagread

ec2-tagread is a helper script I wrote so that bash scripts can read ec2 tags. It assumes you're running on an instance that has an IAM role that allows reading ec2 tags.

Wrote this one at work, but they've allowed me to Open Source it, so it's under the BSD 2-Clause license (see LICENSE, in this directory)

## Requirements
* Boto
* An AWS IAM role or user account with permission to read EC2 tags

## Installation
* Create an IAM role or account with EC2 tag reading permission. Use the supplied allow-ec2-tag-reading.json file to create a policy you can attach to the account/role to grant the necessary access rights.
