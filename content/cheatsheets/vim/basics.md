+++
type = "vim"
date = "2018-07-29"
title = "Some Forgotten Basics"
draft = true
toc = true
logo = "https://upload.wikimedia.org/wikipedia/commons/thumb/4/4f/Neovim-logo.svg/1280px-Neovim-logo.svg.png"
tags = ["vim", "neovim", "basics", "motions",]
+++
-----

This is about the interesting points of &nbsp; ```:help quickref``` &nbsp; in vim.

# Motions

[Nice Youtube Presentation](https://youtu.be/Qem8cpbJeYc)


## Moving cursor on screen

|        action        | key |
|:--------------------:|----:|
|   top of the screen  | `H` |
| middle of the screen | `M` |
| bottom of the scrren | `L` |


## Moving screen, not cursor

| action                      | key        |
| :-------------------------: | ---------: |
| to the middle               | `zz`       |
| to the top                  | `zt`       |
| to the bottom               | `zb`       |
| one line to the top         | `C-e`      |
| one line to the bottom      | `C-y`      |

## Scrolling

By the way: [Nice plugin for smoothed scrolling](https://github.com/terryma/vim-smooth-scroll).

| action                      | key        |
| :-------------------------: | ---------: |
| scroll full-page up         | `C-b`      |
| scroll full-page down       | `C-f`      |
| scroll half-page up         | `C-u`      |
| scroll half-page-down       | `C-d`      |


## Within a line

|       action       |  key |
|:------------------:|-----:|
|  beginning of line |  `0` |
| first char of line |  `^` |
|     end of line    |  `$` |
|  last char on line | `g_` |


## Search navigation

| Action                 | Next   | Previous           |
| :--------------------: | :----: | :-----------:      |
| f &nbsp; something     | `;`    | `,` &nbsp; (comma) |
| F &nbsp; something     | `;`    | `,` &nbsp; (comma) |
| t &nbsp; something     | `;`    | `,` &nbsp; (comma) |
| T &nbsp; something     | `;`    | `,` &nbsp; (comma) |

*Warning*: `,` (comma) is often used for leader key


# Commands

|           Action           |      Command     |
|:--------------------------:|:----------------:|
| open help in vertical split | :&nbsp;vert help |

Lorem. Sed turpis enim, faucibus quis, pharetra in, sagittis sed, magna.
Curabitur ultricies felis ut libero. Nullam tincidunt enim eu nibh. Nunc eget
ipsum in sem facilisis convallis. Proin fermentum risus. Vestibulum ante ipsum
primis in faucibus orci luctus et ultrices posuere cubilia Curae; Vestibulum
hendrerit malesuada odio. Fusce ut elit ut augue sollicitudin blandit. Phasellus
volutpat lorem. Duis non pede et neque luctus tincidunt. Duis interdum tempus
elit.

# Another title

Aenean metus. Vestibulum ac lacus. Vivamus porttitor, massa ut hendrerit
bibendum, metus augue aliquet turpis, vitae pellentesque velit est vitae metus.
Duis eros enim, fermentum at, sagittis id, lacinia eget, tellus. Nunc consequat
pede et nulla. Donec nibh. Pellentesque cursus orci vitae urna. Cum sociis
natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
Pellentesque risus turpis, aliquet ac, accumsan vel, iaculis eget, enim.
Pellentesque nibh neque, malesuada id, tempor vel, aliquet ut, eros. In hac
habitasse platea dictumst. Integer neque purus, congue sed, mattis sed,
vulputate ac, pede. Donec vestibulum purus non tortor. Integer at nunc.

Suspendisse fermentum velit quis sem. Phasellus suscipit nunc in risus. Nulla
sed lectus. Morbi sollicitudin, diam ac bibendum scelerisque, enim tortor
rhoncus sapien, vel posuere dolor neque in sem. Pellentesque tellus augue,
tempus nec, laoreet at, porttitor blandit, leo. Phasellus in odio. Duis
lobortis, metus eu laoreet tristique, pede mi congue mi, quis posuere augue
nulla a augue. Pellentesque sed est. Mauris cursus urna id lectus. Integer
dignissim feugiat eros. Sed tempor volutpat dolor. Vestibulum vel lectus nec
mauris semper adipiscing.

Aliquam tincidunt enim sit amet tellus. Sed mauris nulla, semper tincidunt,
luctus a, sodales eget, leo. Sed ligula augue, cursus et, posuere non, mollis
sit amet, est. Mauris massa. Proin hendrerit massa. Phasellus eu purus. Donec
est neque, dignissim a, eleifend vitae, lobortis ut, nibh. Nullam sed lorem.
Proin laoreet augue quis eros. Suspendisse vehicula nunc ac nisi.

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Fusce mi. Vivamus enim
velit, condimentum sit amet, laoreet quis, fermentum non, ipsum. Etiam quis
felis. Curabitur tincidunt, sapien et luctus faucibus, nibh nisi commodo arcu,
vitae cursus neque ante sed elit. Sed sit amet erat. Phasellus luctus cursus
risus. Phasellus ac felis. Proin nec eros quis ipsum pellentesque congue.
Curabitur et diam sed odio accumsan cursus. Pellentesque ultricies. Quisque
aliquam. Sed nisi velit, consectetuer eget, dictum ac, molestie a, magna.
Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia
Curae; Curabitur consequat leo et dui. Aenean ligula mi, dignissim ut, imperdiet
tristique, interdum a, dolor.

Vestibulum elit nibh, rhoncus non, euismod sit amet, pretium eu, enim. Nunc
commodo ultricies dui. Cras gravida rutrum massa. Donec accumsan mattis turpis.
Quisque sem. Quisque elementum sapien iaculis augue. In dui sem, congue sit
amet, feugiat quis, lobortis at, eros.

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Proin interdum
vehicula purus. Cum sociis natoque penatibus et magnis dis parturient montes,
nascetur ridiculus mus.

Aenean risus dui, volutpat non, posuere vitae, sollicitudin in, urna. Nam eget
eros a enim pulvinar rhoncus. Cum sociis natoque penatibus et magnis dis
parturient montes, nascetur ridiculus mus. Nulla facilisis massa ut massa. Sed
nisi purus, malesuada eu, porta vulputate, suscipit auctor, nunc. Vestibulum
convallis, augue eu luctus malesuada, mi ante mattis odio, ac venenatis neque
sem vitae nisi. Donec pellentesque purus a lorem. Etiam in massa. Nam ut metus.
In rhoncus venenatis tellus. Etiam aliquam. Ut aliquam lectus ut lectus. Nam
turpis lacus, tristique sit amet, convallis sollicitudin, commodo a, purus.
Nulla vitae eros a diam blandit mollis. Proin luctus feugiat eros. Pellentesque
habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.
Duis ultricies urna. Etiam enim urna, pharetra suscipit, varius et, congue quis,
odio. Donec lobortis, elit bibendum euismod faucibus, velit nibh egestas libero,
vitae pellentesque elit augue ut massa.

Nulla consequat erat at massa. Vivamus id mi. Morbi purus enim, dapibus a,
facilisis non, tincidunt at, enim. Vestibulum ante ipsum primis in faucibus orci
luctus et ultrices posuere cubilia Curae; Duis imperdiet eleifend arcu. Cras
magna ligula, consequat at, tempor non, posuere nec, libero. Vestibulum vel
ipsum. Praesent congue justo et nunc. Vestibulum nec felis vitae nisl pharetra
sollicitudin. Quisque nec arcu vel tellus tristique vestibulum. Aenean vel
lacus. Mauris dolor erat, commodo ut, dapibus vehicula, lobortis sit amet, orci.
Aliquam augue. In semper nisi nec libero. Cras magna ipsum, scelerisque et,
tempor eget, gravida nec, lacus. Fusce eros nisi, ullamcorper blandit, ultricies
eget, elementum eget, pede. Phasellus id risus vitae nisl ullamcorper congue.
Proin est.

Sed eleifend odio sed leo. Mauris tortor turpis, dignissim vel, ornare ac,
ultricies quis, magna. Phasellus lacinia, augue ac dictum tempor, nisi felis
ornare magna, eu vehicula tellus enim eu neque. Fusce est eros, sagittis eget,
interdum a, ornare suscipit, massa. Sed vehicula elementum ligula. Aliquam erat
volutpat. Donec odio. Quisque nunc. Integer cursus feugiat magna. Fusce ac elit
ut elit aliquam suscipit. Duis leo est, interdum nec, varius in, facilisis
vitae, odio. Phasellus eget leo at urna adipiscing vulputate. Nam eu erat vel
arcu tristique mattis. Nullam placerat lorem non augue. Cras et velit. Morbi
sapien nulla, volutpat a, tristique eu, molestie ac, felis.

Suspendisse sit amet tellus non odio porta pellentesque. Nulla facilisi. Integer
iaculis condimentum augue. Nullam urna nulla, vestibulum quis, lacinia eget,
ullamcorper eu, dui. Quisque dignissim consequat nisl. Pellentesque porta augue
in diam. Duis mattis. Aliquam et mi quis turpis pellentesque consequat.
Suspendisse nulla erat, lacinia nec, pretium vitae, feugiat ac, quam. Etiam sed
tellus vel est ultrices condimentum. Vestibulum euismod. Vivamus blandit.
Pellentesque eu urna. Vestibulum consequat sem vitae dui. In dictum feugiat
quam. Phasellus placerat. In sem nisl, elementum vitae, venenatis nec, lacinia
ac, arcu. Pellentesque gravida egestas mi. Integer rutrum tincidunt libero.

Duis viverra. Nulla diam lectus, tincidunt et, scelerisque vitae, aliquam vitae,
justo. Quisque eget erat. Donec aliquet porta magna. Sed nisl. Ut tellus.
Suspendisse quis mi eget dolor sagittis tristique. Aenean non pede eget nisl
bibendum gravida. Class aptent taciti sociosqu ad litora torquent per conubia
nostra, per inceptos himenaeos. Morbi laoreet. Suspendisse potenti. Donec
accumsan porta felis.

Fusce tristique leo quis pede. Cras nibh. Sed eget est vitae tortor mollis
ullamcorper. 

