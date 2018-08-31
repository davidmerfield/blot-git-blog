This repository is the source folder for [this blog](http://git.blot.im/) on [Blot](https://blot.im). Here's how I got it onto GitHub:

1. Create new blog on Blot, set up git client and clone to my machine per instructions:

```
git clone https://blot.im/clients/git/end/git.git
```

2. Go to GitHub, create new empty repository and copy its URL which in my case is 

```
https://github.com/davidmerfield/blotgitblogtest.git
```

3. On my machine, add remote 'github' with this command

```
git remote add github https://github.com/davidmerfield/blotgitblogtest.git
```

4. Verify additional remote location:

```
git remote -v
> github	https://github.com/davidmerfield/blotgitblogtest.git (fetch)
> github	https://github.com/davidmerfield/blotgitblogtest.git (push)
> origin	https://blot.im/clients/git/end/git.git (fetch)
> origin	https://blot.im/clients/git/end/git.git (push)
```

5. Now I can ```git push github``` or ```git push origin``` as needed!
