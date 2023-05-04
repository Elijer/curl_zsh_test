# The low-down
Testing out curl commands outputting to zsh

# Background
So I was reading [this excellent real python article](Managing Multiple Python Versions With pyenv) and I came across this very simple line of code:

```
curl https://pyenv.run | bash
```

And realized for maybe the second or third time this week that a line of code like this simple uses the curl command to retrieve a script from github, pipes it to bash, and runs it.
1. This seems sort of dangerous. Couldn't it do anything? [Here is an article on that](https://www.djm.org.uk/posts/protect-yourself-from-non-obvious-dangers-curl-url-pipe-sh/), and basially it seems like the conversation on this is that it's relatively safe given that you read the file yourself, AND use a simple go-around to verify you are running what you see hosted online
2. I wanted to host one of these myself

# How to use
So I've hosted this on github. I went to the page where this file is hosted, and pressed the `raw` viewing options, and copied that URL to make the following command:
```
https://raw.githubusercontent.com/Elijer/curl_zsh_test/main/test
```

^Which runs it successfull! Voile.