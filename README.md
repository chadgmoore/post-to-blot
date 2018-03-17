# post-to-blot
## An applescript you can use to post to Blot.im

You'll need to setup an account on blot.im and configure the settings. Normal usage for Blot is to simply drag a markdown file to the Dropbox folder for Blot to publish a post.

This applescript allows you to type your post from anywhere, and it names the file based on date-time (2018-03-17-15-50-47.md) and places it into the Blot folder. You'll need to change that in the script itself before running the script. Tie the applescript as a service and hotkey, so you can launch it from anywhere.

### Full disclosure
I couldn't figure out the permissions errors I was getting for writing the file directory for Blot in Dropbox. So, I write it to the desktop, then move it from the desktop to the Blot folder. It's a hack but it works. 
