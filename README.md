# composite
## https://github.com/cmusphinx
```
D:\_workspace\omssphinx>git clone https://github.com/cmusphinx/pocketsphinx.git
Cloning into 'pocketsphinx'...
remote: Counting objects: 12247, done.
remote: Compressing objects: 100% (6/6), done.
remote: Total 12247 (delta 0), reused 2 (delta 0), pack-reused 12241
Receiving objects: 100% (12247/12247), 202.74 MiB | 8.89 MiB/s, done.
Resolving deltas: 100% (9184/9184), done.

D:\_workspace\omssphinx>git clone https://github.com/cmusphinx/pocketsphinx-android.git
Cloning into 'pocketsphinx-android'...
remote: Counting objects: 572, done.
remote: Total 572 (delta 0), reused 0 (delta 0), pack-reused 572 eceiving objects:  99% (567/572)
Receiving objects: 100% (572/572), 158.45 KiB | 811.00 KiB/s, done.
Resolving deltas: 100% (213/213), done.

D:\_workspace\omssphinx>git clone https://github.com/cmusphinx/sphinxbase.git
Cloning into 'sphinxbase'...
remote: Counting objects: 10748, done.
remote: Total 10748 (delta 0), reused 0 (delta 0), pack-reused 10748
Receiving objects: 100% (10748/10748), 8.98 MiB | 5.71 MiB/s, done.
Resolving deltas: 100% (8488/8488), done.

D:\_workspace\omssphinx>git clone https://github.com/cmusphinx/pocketsphinx-android-demo.git
Cloning into 'pocketsphinx-android-demo'...
remote: Counting objects: 1616, done.
remote: Total 1616 (delta 0), reused 0 (delta 0), pack-reused 1616
Receiving objects: 100% (1616/1616), 43.18 MiB | 5.38 MiB/s, done.
Resolving deltas: 100% (594/594), done.
```
# build
```
MS Windows™ (MS Visual Studio 2012 (or newer - we test with VC++ 2012 Express)
load sphinxbase.sln located in sphinxbase directory

compile all the projects in SphinxBase (from sphinxbase.sln)

load pocketsphinx.sln in pocketsphinx directory

compile all the projects in PocketSphinx
```
## android studio build(ex. D:\_workspace\omssphinx\pocketsphinx-android)
export POCKETSPHINX_HOME=D:\_workspace\omssphinx\pocketsphinx
export SPINXBASE_HOME=D:\_workspace\omssphinx\sphinxbase

