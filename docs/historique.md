reminder to the team : git diff <branch> <branch> shows the history of a branch and its differences with another branch.

here's an exemple between dev, and main :

diff --git a/docs/exo7.md b/docs/exo7.md
deleted file mode 100644
index dded056..0000000
--- a/docs/exo7.md
+++ /dev/null
@@ -1,5 +0,0 @@
-testing a feature on exercice 7, hope ill make it
-
-edit : solved exercice 7. "git stash" was used. in order to make it work, you have to type "git stash", swap branches, "git stash show", just to make sure your stash still exists, and then you may "git stash apply".
-
-si je traduis en français, j'ai tapé git stash, changé de branche vers main puis retour vers dev. J'ai utilisé git stas: