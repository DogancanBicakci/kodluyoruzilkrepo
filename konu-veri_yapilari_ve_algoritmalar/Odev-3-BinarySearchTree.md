<!--
Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin 

1.Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
-->



1.Root 6'dır.

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

#Step 1:
#                       6 <-- Root
#                        \
#                         7      <!--7 Eklendi-->

#Step2:
#                       6
#                      / \
#                     5   7      <!--5 Eklendi-->

#Step3
#                       6
#                      / \
#                     5   7
#                    /
#                   1            <!--1 Eklendi-->

#Step4:
#                       6
#                      / \
#                     5   7
#                    /     \
#                   1       8   <!--8 Eklendi-->


#Step5:
#                       6
#                      / \
#                     5   7
#                    /     \
#                   1       8
#                    \
#                     3         <!--3 Eklendi-->
#Step6:
#                       6
#                      / \
#                     5   7
#                    /     \
#                   1       8
#                  / \
#                 0   3        <!--0 Eklendi-->

#Step7:
#                       6
#                      / \
#                     5   7
#                    /     \
#                   1       8
#                  / \       \
#                 0   3       9 <!--9 Eklendi-->

#Step8:
#                       6
#                      / \
#                     5   7
#                    /     \
#                   1       8
#                  / \       \
#                 0   3       9
#                      \
#                       4       <!--4 Eklendi-->

#Step9 (Last):
#                       6
#                      / \
#                     5   7
#                    /     \
#                   1       8
#                  / \       \
#                 0   3       9
#                    / \
#                   2   4       <!--2 Eklendi-->

