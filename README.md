# Collins

## A simple (single file) microblogging tool, mostly just for you.

Mike Collins was all alone.

He knew the two nearest humans were at least 2,000 miles away. After them, nobody for another 232,000 miles. (As far, it turns out, as the earth is from the moon.)

His radio stopped working 14 minutes ago. It would be 34 more before he’d be back in contact with the world.

“I am alone now, truly alone, and absolutely isolated from any known life. I am it. If a count were taken, the score would be three billion plus two over on the other side of the moon, and one plus *God knows what on this side*.”

Sometimes it’s good to be solo.

Get away from the bustle of social media. Take notes for your own benefit. Log your days. Journal your dreams.

You, your microblogging software, and *God knows what on this side*.

That’s the premise of Collins.

Collins is a simple microblogging tool. Load it onto your own server and have it running in 30 seconds. Then post at will. It looks like [this](https://collins.charliepark.org/collins).

## Requirements

You'll need three things to use Collins. All are normal server-y things. If you have a server you put projects on, you're all set. Just for clarity, though, here's what you need:

1. A normal run-of-the-mill server that can handle PHP. The basic shared server at DreamHost or any other hosting provider will do.
2. A domain that people can visit.
3. Comfort using SSH and a Terminal-based editor (vi, vim, nano, etc) to edit files on your server.

## Getting Started

The beauty of Collins is that it starts out as a single file. It creates a few more files that live in the same project directory, but it stays simple. The core of it is really only about 300 lines of PHP (and HTML/CSS). The code is pretty readable.

### 1. Fork this project to your own GitHub account.

It'll make it easier for you as you make changes and add posts and such.

### 2. SSH in to your server and clone your forked project.

yourdomain.com/collins is a nice home, but you can put it wherever you like.

### 3. Using vi/vim/nano/etc, make a few edits to index.php.

* Add a password (check out line 30).
* Give your Collins a title while you're there.

### 4. Visit your domain.

You'll see a box where you can write posts. You'll also be able to enter your password.

### 5. Post away.

* yourdomain.com/collins will be where your posts live (technically, yourdomain.com/collins/index.html)
* yourdomain.com/collins/index.php will be where you can post new messages. There are also some FAQs on that page, so you don't have to come back here to remember how to post.

That's it! If you use Collins, let me know! I'd love to check yours out!
