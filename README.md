# tweetarchive

Github will only show 1000 files in the directory list, but all of the files should still be searchable.

Archive begins on 2019-02-24

Learn more about Boogie: https://www.reddit.com/r/SamandTolki/comments/ajzm5h/the_hidden_truth_boogie_doesnt_want_you_to_know/

2019-02-25: An error with archive.today resulted in missing a handful of tweets at the worst time. At least one of the missed tweets was deleted by Boogie following some backlash. The problem has been fixed.

2019-02-25: A second repo is available where all of the tweets the API can access are backed up as well. Find that here: https://github.com/absolute-beginner/pasttweetarchive

2019-03-04: Server dropped connection, so a few tweets were missed. I've collected the ones still available after the problem was noticed.

2019-03-04: I have a function I'll be adding today or tomorrow that will also backup videos since the archive sites don't do that. I'm holding off to test it a little bit more.

I'll be using Streamable to backup the Twitter videos for now. If nobody watches the video within three months the video will be deleted though, so if this is still a thing in a few months the videos may or may not be there. I'll see if there's a better alternative that will allow me to import the videos directly from Twitter the way Streamable does, but I'm not expecting anything (pulling the video to the server and reuploading would likely run up some usage fees, and this isn't something I'm going to put money out for).

I'm also working on a function that will automatically check for deleted tweets and post those separately once detected. The issue I'm running into with this is my own knowledge (or lack thereof). My current solution would involve text files storing tweet ids and checking the current ids vs the archived ids. That works fine by itself, but needing to manipulate the same file for archiving and checking for deleted tweets causes an issue with the logging of the IDs. So... not sure when that will be added, but it'll probably be soon assuming nothing comes up.
