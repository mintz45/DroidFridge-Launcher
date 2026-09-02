# DFL
What's DFL? DFL is a version of DBL that applies offline account patches.

## Why does this exist?
Because there's a lot of people who's been complaining about DBL
having no offline account, and me, knowing that I have knowledge about
reverse engineering reimplementing the offline account.

## How?
Because Android needs to understand a specific code language,
it is easy to reverse engineer every application but really complex at the same time.
Why? because one wrong character breaks the whole logics of those dexes.
I made it by using Jadx on my pc and translating dex to java so it can be easily 
understood, then I will find the specific classes responsible for the offline blocks
in the ui and patch them manually one by one.
