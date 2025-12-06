# Zap for IDOR

[Recap of IDOR](../../attacks/app-level.html#9-insecure-direct-object-reference-idor):
>Occurs when applications expose internal object identifiers (like user IDs or filenames) without proper authorization checks, allowing attackers to access or modify other users’ data.

I have discovered this tool with this level: [IDOR - Santa’s Little IDOR](https://tryhackme.com/room/idor-aoc2025-zl6MywQid9)

![Image of an IDOR bug](/images/cybersecurity/tools/zap/IDOR/IDOR.png)

You can access to storage section and see that they store your access through a simple id:
![Image of the storage](/images/cybersecurity/tools/zap/IDOR/storage.png)

Now you can update it by hand and refresh to see the panel of another one.

Now let's scrap it with zap:
![Image of the IDOR](/images/cybersecurity/tools/zap/IDOR/zap_IDOR_detection.png)
As you can see we found the request, let's automate:
![fuzz image](/images/cybersecurity/tools/zap/IDOR/fuzz.png)

We got some pretty result let's find out.
![Image of the result](/images/cybersecurity/tools/zap/IDOR/fuzz_result.png)
Just need to take a look for now !
