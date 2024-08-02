# exercicio01
Aula IMPACTA

b) resultado:

"""
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

  new file:   arquivo.txt
"""
c) resultado:

 git add example - arquivo.txt
 1 file changed, 1 insertion(+)
 create mode 100644 arquivo.txt

e) resultado:

--- a/arquivo.txt
+++ b/arquivo.txt
@@ -1 +1 @@
-01
+02

f) resultado:

Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

  modified:   arquivo.txt

g) resultado:

diff --git a/arquivo.txt b/arquivo.txt
--- a/arquivo.txt
+++ b/arquivo.txt
@@ -1 +1 @@
-01
+02


i) resultado:

diff --git a/arquivo.txt b/arquivo.txt
--- a/arquivo.txt
+++ b/arquivo.txt
@@ -1 +1 @@
-02
+03

j) resultado:

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
    modified:   arquivo.txt

k) resultado:

Updated arquivo.txt to 02
git add example - arquivo.txt

l) resultado:

Add gitignore to exclude .txt files
 1 file changed, 1 insertion(+)
 create mode 100644 .gitignore

m) resultado
nothing to commit, working tree clean
