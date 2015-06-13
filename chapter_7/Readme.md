## Story Questions
**Can you remove the tmp directory?**
> I'd type `rmdir /tmp`.

**Let's remove the tmp directory.**
> I'd type `rm -rf tmp`. --I'm not sure how to do this with `rmdir`. There doesn't seem to be an option to remove everything non-empty folders when I `man rmdir`, and all the stackoverflows that I've found only use `rm -rf`, and Zed says *"If you try to remove a directory with contents you will get an error. I'll show you how to remove these in later exercises."*, so I'm lost on this one!
> If it's empty, I'd type `rmdir tmp/`

## Do More
**Make 20 more directories and remove them all.**
> I typed `mkdir {1..20}`, then `rm -r {1..20}`   

**Make a single path of directories that is 10 deep and remove them one at a time just like I did above.**
> I typed `mkdir -p temp/2/3/4/5/6/7/8/9/10`, then `rmdir temp/2/3/4/5/6/7/8/9/10`, `rmdir temp/2/3/4/5/6/7/8/9`, 

**If you try to remove a directory with contents you will get an error. I'll show you how to remove these in later exercises.**
> Indeed! `rmdir` on a directory with content throws an error.
