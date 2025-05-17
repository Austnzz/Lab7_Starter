Name: Austin Choi

**Check Your Understanding**
1) It would probably be best to havie it inside a github action that will run the checks once new code is pushed. It creates a seamless integradtion that will immediately catch and check every commit that way it won't break main. Its also clean and works well in group and collaborative settings.
2) No. Since E2E checks an entire workflow, they are extremely detailed and sometimes even slow. A simple check like a function return value can just be done in a simple unit test, that way it keeps it isolated for this specific purpose.
3) Navigation gave the results: Performance - 75, Accessibility - 95, Best Practice - 93, SEO - 91. while the Snap shot gave Performance - 2/4, Accessibility - 19/20, Best Practice - 4/6, SEO - 4/5. Navigation also captures the speed index and load-timr metrics while snapshot does not. Navigation also doesnt tell you how the page behaves if users begin clicking around, and Snapshot wont tell you additional details on why load is slow or what scripts might be blocking rendering.
4) Potentially properly sizing images can help lower this overhead. The flag also pointed out having No <meta name="viewport"> tag, as this docks performance. There is also a 492 KiB unuesed JS warning, so removing unused JS can help in performanc ein this regard.





