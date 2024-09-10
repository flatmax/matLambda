# matLambda
Allows you to run Matlab on AWS Lambda

# History

In around 2016 I wrote these scripts to tree shake the Matlab MCR so that it
will fit within the AWS Lambda resource limits.

# Usage

Update vars.sh to fit your matlab compiled binary. Run makeCloudReady.sh to
first directory tree shake and then file shake the MCR.

Take the freshly shaken archive and extract it into your target. 
