# Start of Maintaining Old Code

When you being maintaining a body of code, the very first thing to do _before 
making any changes_ is to build the code and run it through whatever tests 
already exist. The reason for this is that you will own any problems that are
found after you make any changes.

If there are any problems with the build not working or test not passing,
then it is important to carefully capture a log of the build and describe
the problems. These problems must be explained to the client with the goals
of adjusting schedules and 
[setting client expectations](manage-client-expectations.md). 

## If there is no Automated Build Process
The preceding advice assumes that someone knows how to build the code or
that there is an automated build process that uses build tools that are so
well standardized that it is obvious how to accomplish a build.

If no one knows how to build the code or there is no automated process, then
the first thing to do is create an automated build process that you know how 
to run and document the build process.

there is an automated build process set up
for the code and that there are automated tests ( or at least a test plan).
It also assumes that 