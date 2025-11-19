# TODO #

## Publisher



### IEEE

```bash
(("Full Text .AND. Metadata": "elearning" OR
"Full Text .AND. Metadata": "e-learning" OR
"Full Text .AND. Metadata": "digital learning")

AND

(NOT
("Full Text .AND. Metadata": "mooc" OR
"Full Text .AND. Metadata": "moocs" OR
"Full Text .AND. Metadata": "Massive Open Online Course")))
```

*OR*

```bash
(("Search_All_Text": "elearning" OR
"Search_All_Text": "e-learning" OR
"Search_All_Text": "digital learning")

AND

(NOT
("Search_All_Text": "mooc" OR
"Search_All_Text": "moocs" OR
"Search_All_Text": "Massive Open Online Course")))
```





> **& manual filtering according to the corresponding year for the publication date, since automatic filtering via the search querie is not possible so far.**





### ACM

```bash
[[All: "elearning"] OR
[All: "e-learning"] OR
[All: "digital learning"]]

AND

[NOT
[[All: "mooc"] OR
[All: "moocs"] OR
[All: "Massive Open Online Course"]]]

AND

[E-Publication Date: (01/01/2000 TO 12/31/2000)]
```

*OR*

```bash
(AllField:("elearning") OR
AllField:("e-learning") OR
AllField:("digital learning"))

AND

(NOT
(AllField:("mooc") OR
AllField:("moocs") OR
AllField:("Massive Open Online Course")))
```





### Elsevier

```bash
("elearning" OR
"e-learning" OR
"digital learning")

AND

(NOT
("mooc" OR
"moocs" OR
"Massive Open Online Course"))
```

> **& manual filtering according to the corresponding year for the publication date, since automatic filtering via the search querie is not possible so far.**





### Springer

```bash
("elearning" OR
"e-learning" OR
"digital learning")

AND

(NOT
("mooc" OR
"moocs" OR
"Massive Open Online Course"))
```