# 407Assignment2

Current Output of the program.

+  [eflemin8@cdmlinux assignment2]$ ./launcherTimer 
+  Yo I LAUNCHED
+  Timer: "13 seconds"
+  I FORKED and about to execl ANSWERER
+  Answerer: "(Don't tell, but the answer is 77)"
I FORKED and about to execute GUESSER
+  Guesser: "Is there a 128?"
+  Timer: "12 seconds"
+  Timer: "11 seconds"
+  Timer: "10 seconds"
+  Timer: "9 seconds"
+  Timer: "8 seconds"
+  Timer: "7 seconds"
+  Timer: "6 seconds"
+  Timer: "5 seconds"
+  Timer: "4 seconds"
+  Timer: "3 seconds"
+  Timer: "2 seconds"
+  Timer: "1 seconds"
+  Timer: "0 seconds"
+  sent SIGINT
+  ^C

## Thoughts
+  I realized I never created sig actions in launcherTimer() and I suppose there should have been because there is a sighandler dangling there left unused.  That's gotta fix something. 
+  Also, are my kill() statements making sense in general in both files now?
