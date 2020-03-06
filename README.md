POEMS
=====

## 1. Subfolders

Root folder should contain subfolder for poets.
Each subfolder should use the folowing format:

```
asnyk
blake
mickiewicz
shakespeare
slowacki
```

Format details:

* surname only
* small case letters
* only a-z characters
* use dash `-` as a separator (e.g. `o-hara`) 

## 2. Commit format

Conventional commit:

```
feat: [Adam Mickiewicz] Pan Tadeusz
```

## 3. File encoding

Please use utf-8 encoding.


## 4. Filenames

Format details:

* small case letters
* only a-z characters
* use dash `-` as a separator (e.g. `o-hara`) 

Examples:

```
pan-tadeusz.txt
o-dwoch-takich-co-ukradli-ksiezyc.txt
endless-night.txt
```

## 5. Poem format

The file with poem must contain:

* poets full names
* poem title
* empty line
* contents

For example:

```
William Blake
Endless Night

Every Night and every Morn
Some to Misery are born.
Every Morn and every Night
Some are born to Sweet Delight,
Some are born to Endless Night. 
```

## 6. Branch name

Branch name should be created on the basis of the poem's title, for example:

```
endless-night
pan-tadeusz
```

## 7. Which poems can I choose?

Poems must be unique.

## 8. GIT configuration

Please use the following git commands to set up your personal info:

```
git config user.name "John Doe"
git config user.email john.doe@example.net
```

All the commits must contain your personal info. The output of
`git log` command must list you as the author of the commie:


```
commit a6357c7bc8bfa7e514c16bda3df568a207322fb5
Author: Włodzimierz Gajda <wlodzimierz.gajda@aiqa.tech>
Date:   Fri Oct 25 12:58:45 2019 +0200
```