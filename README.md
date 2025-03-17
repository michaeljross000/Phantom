
# Phantom  

Not really interested in making money off this—just trying to get some publicity for my project, **X-Intel**: [https://beta.xint.app](https://beta.xint.app).  

This is more or less my take on **C5hackr's Phantom**. It took me a couple of days to really understand what most of this does. I'm still a little in the dark about a lot of it, but I'm getting better every day.  

What I'm doing to make it **FUD-ish** is keeping the actual obfuscation but adding a step at the start of the script where it encodes all of the code in **Base64**, decodes it, and then runs it using `call`. This makes it look like a normal Base64 decoding script.  

I'm also working on something to detect **any.run** so that the command doesn't execute if it detects a sandbox environment.  

I've just optomized the code and made a really simple patch untill i know how to actually "code" in batch/powershell cus right now AI is taking a big part in the batch/powershell parts of the code also im gonna have to find the updated offsets for basically everything in this project

If ya'll have any of your own suggestions/fixes for this project just make PR's or discuss it with me in https://github.com/michaeljross000/Phantom/discussions ❤
